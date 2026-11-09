---
layout: archive
title: "Chip Design Lab"
permalink: /lab/
author_profile: true
redirect_from:
  - /lab
---

{% include base_path %}

<h2 id="projects">Research Projects</h2>

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

Team
======
* Current Students
  * Blair Reasoner, Ph.D, UH
  * Sumera Anjum, Ph.D, Co-advised with Prof. Yunhe Feng at University of North Texas
  * Dania Mosuli, MS, UHCL
  * Cameron D. DiSomma, MS, UHCL
  * Muhammad Athar Waqas, MS, UHCL
  * Spencer Buchanan, UG, UHCL
  * Jeremy Turner, UG, UHCL
* Former Students
  * Blair Reasoner, 2024, RTL CPU Designer, IBM
  * Mario Vega, 2023, Computer Systems Engineer, Lawrence Berkeley National Laboratory
  * Anthony Cruz, 2025, Amazon
  * Madineni, Mukesh Chowdary, 2022, Graduation Implementation Engineer, ARM
  * April Reed, 2021, ASIC and FPGA Design Engineer, Lockheed Martin
  * Harold William Schmoyer, 2021
  * Isaac Westby, 2020, Graduate Applications Engineer, ARM
  * Yunxiang Zhang, 2019, Assistant Professor, University of Arkansas
  * Archit Gajjar, 2018, Postdoctoral Research Associate, HP Labs 

## Lab Photos

<h2>Lab Highlights</h2>

<style>
.lab-gallery {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 24px;
  margin-bottom: 32px;
}
.lab-gallery figure {
  margin: 0;
}
.lab-gallery img {
  display: block;
  width: 100%;
  height: 220px;
  object-fit: contain;
  background: #f4f4f4;
  border-radius: 8px;
}
.lab-gallery figcaption {
  margin-top: 8px;
  text-align: center;
  font-size: 0.9em;
}
@media (max-width: 600px) {
  .lab-gallery {
    grid-template-columns: 1fr;
  }
}
.lab-highlights .lab-gallery-compact { width: 66.666%; margin-left: auto; margin-right: auto; }
.lab-highlights .lab-gallery-compact img { height: 160px; object-fit: contain; }
@media (max-width: 600px) {
  .lab-highlights .lab-gallery-compact { width: 100%; max-width: 320px; }
}
</style>

<div class="lab-gallery">
  <figure>
    <a href="{{ base_path }}/files/lab/doe%20kickoff%202025.png">
      <img src="{{ base_path }}/files/lab/doe%20kickoff%202025.png"
           alt="DOE kickoff, 2025" loading="lazy">
    </a>
    <figcaption>DOE Kickoff · 2025</figcaption>
  </figure>

  <figure>
    <a href="{{ base_path }}/files/lab/reu%20icdm%202025.jpg">
      <img src="{{ base_path }}/files/lab/reu%20icdm%202025.jpg"
           alt="REU ICDM, 2025" loading="lazy">
    </a>
    <figcaption>REU ICDM · 2025</figcaption>
  </figure>

  <figure>
    <a href="{{ base_path }}/files/lab/nersc%202024.jpg">
      <img src="{{ base_path }}/files/lab/nersc%202024.jpg"
           alt="NERSC, 2024" loading="lazy">
    </a>
    <figcaption>NERSC · 2024</figcaption>
  </figure>

  <figure>
    <a href="{{ base_path }}/files/lab/blair%20lbl%202023.jpg">
      <img src="{{ base_path }}/files/lab/blair%20lbl%202023.jpg"
           alt="Blair at LBL, 2023" loading="lazy">
    </a>
    <figcaption>Blair at LBL · 2023</figcaption>
  </figure>

  <figure>
    <a href="{{ base_path }}/files/lab/mario%20lbl%202022.jpg">
      <img src="{{ base_path }}/files/lab/mario%20lbl%202022.jpg"
           alt="Mario at LBL, 2022" loading="lazy">
    </a>
    <figcaption>Mario at LBL · 2022</figcaption>
  </figure>

  <figure>
    <a href="{{ base_path }}/files/lab/amd%202010.jpg">
      <img src="{{ base_path }}/files/lab/amd%202010.jpg"
           alt="AMD, 2010" loading="lazy">
    </a>
    <figcaption>AMD · 2010</figcaption>
  </figure>
</div>

  
<section class="lab-highlights" aria-labelledby="lab-highlights-title">
  <h2 id="lab-highlights-title">Lab Highlights</h2>
  <p>Photos through the years. Select a photo to view the full-size image.</p>
  <div class="lab-gallery">
    <figure class="lab-photo">
      <a href="{{ base_path }}/files/lab/doe%20kickoff%202025.png" aria-label="View DOE Kickoff, 2025, full size">
        <img src="{{ base_path }}/files/lab/doe%20kickoff%202025.png" alt="DOE Kickoff, 2025" width="528" height="240" loading="lazy" decoding="async">
      </a>
      <figcaption>DOE Kickoff &middot; 2025</figcaption>
    </figure>
    <figure class="lab-photo">
      <a href="{{ base_path }}/files/lab/reu%20icdm%202025.jpg" aria-label="View REU ICDM, 2025, full size">
        <img src="{{ base_path }}/files/lab/reu%20icdm%202025.jpg" alt="REU ICDM, 2025" width="188" height="141" loading="lazy" decoding="async">
      </a>
      <figcaption>REU ICDM &middot; 2025</figcaption>
    </figure>
  </div>
  <div class="lab-gallery lab-gallery-three">
    <figure class="lab-photo">
      <a href="{{ base_path }}/files/lab/nersc%202024.jpg" aria-label="View NERSC, 2024, full size">
        <img src="{{ base_path }}/files/lab/nersc%202024.jpg" alt="NERSC, 2024" width="154" height="163" loading="lazy" decoding="async">
      </a>
      <figcaption>NERSC &middot; 2024</figcaption>
    </figure>
    <figure class="lab-photo">
      <a href="{{ base_path }}/files/lab/mario%20lbl%202022.jpg" aria-label="View Mario at LBL, 2022, full size">
        <img src="{{ base_path }}/files/lab/mario%20lbl%202022.jpg" alt="Mario at LBL, 2022" width="144" height="121" loading="lazy" decoding="async">
      </a>
      <figcaption>Mario at LBL &middot; 2022</figcaption>
    </figure>
    <figure class="lab-photo">
      <a href="{{ base_path }}/files/lab/blair%20lbl%202023.jpg" aria-label="View Blair at LBL, 2023, full size">
        <img src="{{ base_path }}/files/lab/blair%20lbl%202023.jpg" alt="Blair at LBL, 2023" width="126" height="121" loading="lazy" decoding="async">
      </a>
      <figcaption>Blair at LBL &middot; 2023</figcaption>
    </figure>
  </div>
  <div class="lab-gallery lab-gallery-compact">
    <figure class="lab-photo">
      <a href="{{ base_path }}/files/lab/hfa%202022%20soccer.jpg" aria-label="View HFA Soccer Team, 2022, full size">
        <img src="{{ base_path }}/files/lab/hfa%202022%20soccer.jpg" alt="HFA soccer team, 2022" width="1200" height="1080" loading="lazy" decoding="async">
      </a>
      <figcaption>HFA Soccer Team &middot; 2022</figcaption>
    </figure>
    <figure class="lab-photo">
      <a href="{{ base_path }}/files/lab/amd%202010.jpg" aria-label="View AMD, 2010, full size">
        <img src="{{ base_path }}/files/lab/amd%202010.jpg" alt="AMD, 2010" width="216" height="161" loading="lazy" decoding="async">
      </a>
      <figcaption>AMD &middot; 2010<br><span style="font-weight: 300;">Cannot believe how low-quality my phone photos were that year :)</span></figcaption>
    </figure>
  </div>
</section>

IC Design Flow
======
* IC Design Tutorials
  * <a href="{{ base_path }}/files/chip/Appendix A.pdf" target="_blank">📄 Project Directory and Vim Editor Tutorial</a>
  * <a href="{{ base_path }}/files/chip/Appendix B.pdf" target="_blank">📄 Siemens ModelSim Tutorial</a>
  * <a href="{{ base_path }}/files/chip/Appendix C.pdf" target="_blank">📄 AMD Vivado Tutorial </a>
* Chisel Tutorials
  * <a href="{{ base_path }}/files/chisel/Chisel and IC Projects Structuring - XY.pdf" target="_blank">📄 Chisel and IC Projects Structuring</a>
  * <a href="{{ base_path }}/files/chisel/Chisel Env Setup - XY.pdf" target="_blank">📄 IntelliJ IDEA Setup for Chisel</a>
  * <a href="{{ base_path }}/files/chisel/Chisel Design - XY.pdf" target="_blank">📄 Chisel Design on Fundamental IC</a>


  

