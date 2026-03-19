---
layout: default
title: "Open Challenges and Emerging Opportunities in Robot Control"
description: "Workshop ECC 2026 - Reykjavík, IEEE CSS"
---

<style>
  .header-logos {
    position: absolute;
    top: 20px;
    left: 0;
    width: 100%;
    display: flex;
    justify-content: space-between; /* Puts one logo on the left, one on the right */
    padding: 0 5vw; /* Adds space on the left and right edges */
    box-sizing: border-box;
    pointer-events: none; /* Prevents logos from blocking clicks on the header */
  }
  .header-logos img {
    height: 80px; 
    width: auto;
    pointer-events: auto;
  }
  
  /* Hides the logos on very small mobile screens so they don't overlap the title */
  @media (max-width: 768px) {
    .header-logos {
      display: none; 
    }
  }
</style>

<div id="custom-header-logos" style="display: flex; justify-content: center; align-items: center; gap: 25vw; margin-top: 30px;">
  <img src="assets/logos/ecc26.svg" alt="ECC 2026" style="height: 80px; width: auto; object-fit: contain;">
  <img src="assets/logos/robot_control_tc.svg" alt="TC" style="height: 80px; width: auto; object-fit: contain;">
</div>

<script>
  // This script waits for the page to load, then moves the logos inside the Cayman green header
  document.addEventListener("DOMContentLoaded", function() {
    var pageHeader = document.querySelector('.page-header');
    var logos = document.getElementById('custom-header-logos');
    if (pageHeader && logos) {
      pageHeader.appendChild(logos);
    }
  });
</script>

## About the Workshop
Robot control has matured into a rich and diverse discipline, yet its intellectual coherence is increasingly strained by fragmentation across paradigms, application domains, and publication venues. Classical problems stability under interaction, modeling uncertainty, underactuation, hybrid dynamics, etc. are often treated as "solved" by practitioners, yet they persistently reappear in modern robotic systems operating in contact-rich, uncertain, and learning-enabled environments. 

At the same time, new challenges and opportunities are emerging, ranging from unconventional robotic platforms (e.g., soft and biohybrid robots) to the growing role of machine learning and large-scale physical data. This workshop provides a focused forum to reassess which problems in robot control remain fundamentally open, how their formulation has evolved with advances in hardware, autonomy, and learning, and which challenges genuinely require new control-theoretic perspectives rather than incremental refinements. The emphasis is on conceptual clarity, modeling assumptions, and the limits of existing methods, rather than polished experimental performance.

## Objectives
The objectives are threefold:
* To collectively articulate the most pressing open challenges for control in robotics, across systems, paradigms, and application domains.
* To clarify how recent technological and conceptual advances reshape both long-standing and emerging control problems.
* To strengthen intellectual cohesion across the control and robotics communities by fostering dialogue grounded in shared concepts and explicit problem formulation.

## Target Audience
The workshop targets researchers in control and robotics whose work engages with the modeling, analysis, and control of complex robotic systems, particularly in settings involving physical interaction, uncertainty, hybrid behavior, and learning-enabled components. It is especially relevant for those interested in the foundations of robotics control, the limits of existing frameworks, and the formulation of new problems arising from emerging robotic platforms and technologies.

<style>
  .profile-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    margin-bottom: 2rem;
  }
  .profile-card {
    background: #f9f9f9;
    border: 1px solid #e1e4e8;
    border-radius: 6px;
    padding: 15px;
    width: calc(50% - 10px); /* Creates a 2-column grid */
    box-sizing: border-box;
    display: flex;
    align-items: flex-start;
    gap: 15px;
  }
  .profile-image {
    width: 80px;
    height: 80px;
    border-radius: 50%;
    object-fit: cover;
    flex-shrink: 0;
    border: 2px solid #159957; /* Cayman theme green */
  }
  .profile-info {
    display: flex;
    flex-direction: column;
  }
  .profile-info h3 {
    margin: 0 0 5px 0 !important;
    font-size: 1.1rem;
    color: #159957;
  }
  .profile-info h4 {
    margin: 0 0 8px 0 !important;
    font-size: 0.9rem;
    color: #606c71;
    font-style: italic;
  }
  .profile-info p {
    margin: 0;
    font-size: 0.85rem;
    line-height: 1.4;
  }
  /* Make it 1 column on smaller screens */
  @media (max-width: 768px) {
    .profile-card {
      width: 100%;
    }
  }
</style>

## Invited Speakers

### Early to Mid Career
<div class="profile-grid">
  <div class="profile-card">
    <img src="assets/speakers/early_mid/laura.jpg" alt="Laura Ferranti" class="profile-image">
    <div class="profile-info">
      <h3>Laura Ferranti</h3>
      <h4>Delft University of Technology, Netherlands</h4>
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/speakers/early_mid/chiara.png" alt="Chiara Gabellieri" class="profile-image">
    <div class="profile-info">
      <h3>Chiara Gabellieri</h3>
      <h4>University of Twente, Netherlands</h4>
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/speakers/early_mid/manuel.jpg" alt="Manuel Keppler" class="profile-image">
    <div class="profile-info">
      <h3>Manuel Keppler</h3>
      <h4>German Aerospace Center (DLR), Germany</h4>
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/speakers/early_mid/kyoungchul.png" alt="Kyoungchul Kong" class="profile-image">
    <div class="profile-info">
      <h3>Kyoungchul Kong</h3>
      <h4>KAIST, South Korea</h4>
    </div>
  </div>
</div>

### Senior
<div class="profile-grid">
  <div class="profile-card">
    <img src="assets/speakers/senior/alessandro-a.jpg" alt="Alessandro Astolfi" class="profile-image">
    <div class="profile-info">
      <h3>Alessandro Astolfi</h3>
      <h4>Imperial College London, UK</h4>
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/speakers/senior/maria.jpg" alt="Maria Pia Fanti" class="profile-image">
    <div class="profile-info">
      <h3>Maria Pia Fanti</h3>
      <h4>Politecnico di Bari, Italy</h4>
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/speakers/senior/melanie.jpg" alt="Melanie Zeilinger" class="profile-image">
    <div class="profile-info">
      <h3>Melanie Zeilinger</h3>
      <h4>ETH, Switzerland</h4>
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/speakers/senior/naira.jpg" alt="Naira Hovakimyan" class="profile-image">
    <div class="profile-info">
      <h3>Naira Hovakimyan</h3>
      <h4>UIUC, USA</h4>
    </div>
  </div>
</div>

## Tentative Program
Format: Full-day workshop 

* **09:00-09:15:** Opening and workshop framing (Organizers) 
* **09:15-10:55:** Session I - Invited perspective talks by Melanie Zeilinger, Laura Ferranti, and Chiara Gabellieri 
* **10:55-11:25:** Coffee break 
* **11:25-13:05:** Session II - Invited perspective talks by Alessandro Astolfi, Manuel Keppler, and Kyoungchul Kong 
* **13:05-14:15:** Lunch break 
* **14:15-15:55:** Session III - Invited perspective talks by Naira Hovakimyan and Maria Pia Fanti 
* **15:55-16:25:** Coffee break 
* **16:25-17:45:** Session IV - Panel with all speakers, focused on synthesizing open challenges, questioning implicit assumptions, and identifying shared research directions for robot control 
* **17:45-18:00:** Closing remarks 


## Organizers

<div class="profile-grid">
  <div class="profile-card">
    <img src="assets/organizers/cosimo.jpg" alt="Cosimo Della Santina" class="profile-image">
    <div class="profile-info">
      <h3>Cosimo Della Santina</h3>
      <h4>TU Delft, NL - Primary Contact</h4>
      <p>Associate Professor in Robotics and Control. Research on nonlinear control, soft and underactuated robots, and physical interaction. Email: c.dellasantina@tudelft.nl</p>
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/organizers/kaoru.jpg" alt="Kaoru Yamamoto" class="profile-image">
    <div class="profile-info">
      <h3>Kaoru Yamamoto</h3>
      <h4>Kyushu University, JP</h4>
      <p>Professor of Control and Robotics. Research on control of interconnected dynamical systems, distributed control, multi-agent systems, mechanical networks, and passivity-based control.</p>
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/organizers/manuel.jpg" alt="Manuel Keppler" class="profile-image">
    <div class="profile-info">
      <h3>Manuel Keppler</h3>
      <h4>German Aerospace Center - DLR, DE</h4>
      <p>Senior researcher in articulated soft and humanoid robot control, with strong links between theory and large-scale experimental platforms.</p>
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/organizers/sylvia.jpg" alt="Sylvia Herbert" class="profile-image">
    <div class="profile-info">
      <h3>Sylvia Herbert</h3>
      <h4>University of California San Diego, US</h4>
      <p>Assistant Professor working on scalable safety assurances and control policies based on available models and data about the system and environment.</p>
    </div>
  </div>
</div>

## Future Outcomes
The organizers aim for the outcomes of this workshop to feed into a joint community effort, such as a position or perspective paper outlining a coherent set of open challenges in robot control. This document would serve as a reference point for future research and discussion within the control and robotics communities.