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
  * Blair Reasoner, Ph.D, Co-advised with Prof. Yuhua Chen at UH
  * Xinpeng Li, Ph.D, Co-advised with Prof. Shuai Xu at CWRU
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

<style>
.lab-highlights .lab-gallery {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 24px;
  margin-bottom: 32px;
}
.lab-highlights .lab-gallery-three {
  grid-template-columns: repeat(3, minmax(0, 1fr));
}
.lab-highlights .lab-photo {
  display: block;
  min-width: 0;
  margin: 0;
}
.lab-highlights .lab-photo > a { display: block; width: 100%; }
.lab-highlights .lab-photo img {
  display: block;
  width: 100%;
  height: 220px;
  margin: 0;
  object-fit: contain;
  border-radius: 8px;
}
.lab-highlights .lab-photo figcaption {
  display: block;
  width: 100%;
  margin: 10px 0 0;
  text-align: center;
  font-size: .85em;
  line-height: 1.5;
}
.lab-highlights .lab-gallery-compact {
  width: 80%;
  margin-left: auto;
  margin-right: auto;
}
.lab-highlights .lab-gallery-compact img { height: 190px; }
@media (max-width: 600px) {
  .lab-highlights .lab-gallery { grid-template-columns: 1fr; }
  .lab-highlights .lab-gallery-compact { width: 100%; max-width: 380px; }
}
</style>

<section class="lab-highlights" aria-labelledby="lab-highlights-title">
  <h2 id="lab-highlights-title">Lab Highlights</h2>
  <p>Photos through the years. Select a photo to view the full-size image.</p>
  <div class="lab-gallery">
    <figure class="lab-photo">
      <a href="{{ base_path }}/files/lab/doe%20kickoff%202025.png" aria-label="View DOE Kickoff, 2025, full size">
        <img src="{{ base_path }}/files/lab/doe%20kickoff%202025.png" alt="DOE Competitive Portfolio LAB-24-3210 Kickoff, 2025" width="528" height="240" loading="lazy" decoding="async">
      </a>
      <figcaption>DOE Kickoff &middot; 2025</figcaption>
    </figure>
    <figure class="lab-photo">
      <a href="{{ base_path }}/files/lab/reu%20icdm%202025.jpg" aria-label="View REU ICDM, 2025, full size">
        <img src="{{ base_path }}/files/lab/reu%20icdm%202025.jpg" alt="ICDM REU, 2025" width="188" height="141" loading="lazy" decoding="async">
      </a>
      <figcaption>REU ICDM &middot; 2025</figcaption>
    </figure>
  </div>
  <div class="lab-gallery lab-gallery-three">
    <figure class="lab-photo">
      <a href="{{ base_path }}/files/lab/nersc%202024.jpg" aria-label="View NERSC, 2024, full size">
        <img src="{{ base_path }}/files/lab/nersc%202024.jpg" alt="LBNL NERSC, 2024" width="154" height="163" loading="lazy" decoding="async">
      </a>
      <figcaption>NERSC &middot; 2024</figcaption>
    </figure>
    <figure class="lab-photo">
      <a href="{{ base_path }}/files/lab/mario%20lbl%202022.jpg" aria-label="View Mario at LBL, 2022, full size">
        <img src="{{ base_path }}/files/lab/mario%20lbl%202022.jpg" alt="Mario at LBNL, 2022" width="144" height="121" loading="lazy" decoding="async">
      </a>
      <figcaption>Mario at LBL &middot; 2022</figcaption>
    </figure>
    <figure class="lab-photo">
      <a href="{{ base_path }}/files/lab/blair%20lbl%202023.jpg" aria-label="View Blair at LBL, 2023, full size">
        <img src="{{ base_path }}/files/lab/blair%20lbl%202023.jpg" alt="Blair at LBNL, 2023" width="126" height="121" loading="lazy" decoding="async">
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
      <figcaption>AMD &middot; 2010<br><span style="font-weight: 300;">Cannot believe how low-quality my photos were that year :)</span></figcaption>
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


  

