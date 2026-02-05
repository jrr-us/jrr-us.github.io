---
layout: default
title: hero
permalink: /about-mda/
nav: false
---

<div class="container my-5">
  <div class="row">    
    <!-- Left Column (20% width) -->
    <div class="col-lg-3 col-md-4 mb-4">
      <!-- Profile Image -->
      {% include figure.liquid path="assets/img/people/avatar-mda.jpg" title="My Profile" class="rounded z-depth-1 rounded-circle" %}
      <!-- Affiliation -->
      <div class="mb-3">
        <h6 class="text-muted mb-1 tracking-wider">AFFILIATION</h6>
        <p class="mb-0">Spanish National Research Council<br>
        Materials Science Institute<br>
        Sevilla, Spain</p>
      </div>
      <div class="mb-3">
        <h6 class="text-muted mb-1 tracking-wider">CONTACT</h6>
          <p>
            <i class="fa-regular fa-envelope"></i> alba (at) icmse.csic.es<br>
            <i class="fa-solid fa-square-phone"></i> +34 954489546
          </p>
      </div>
      <!-- Social Icons -->
      <div class="mt-4">
        <h6 class="text-muted mb-1 tracking-wider">LINKS</h6>
          <!-- ORCID -->
          <a href="https://orcid.org/0000-0003-0025-3078" title="ORCID">
          <i class="ai ai-orcid-square ai-2x"></i></a>
          <!-- Google Scholar -->
          <a href="https://scholar.google.com/citations?hl=es&user=DUCxg8UAAAAJ" title="Google Scholar">
          <i class="ai ai-google-scholar-square ai-2x"></i></a>
          <!-- Scopus -->
          <a href="https://www.scopus.com/authid/detail.uri?authorId=54981240100" title="Scopus">
          <i class="ai ai-scopus ai-2x"></i></a>
          <!-- Google Linkedin -->
          <a href="https://www.linkedin.com/in/joaquin-ramirez-rico-a7a716a6/" title="Linkedin">
          <i class="fa-brands fa-linkedin fa-2x"></i></a>
        </div>
    </div>
    <!-- Right Column (Main Content) -->
    <div class="col-lg-9 col-md-8">
      <h1 class="mb-3">Dr. María D. Alba</h1>
      <h4 class="text-muted mb-4">Research Scientist, CSIC</h4>
      <!-- About Section -->
      <section class="mb-4">
        <h3>About</h3>
        <p>
          Scientist specializing in Materials Science and Technology, with experience in the
          development, characterization, and analysis of sustainable materials from an experimental and
          applied perspective. Her scientific trajectory focuses on the generation of knowledge based on
          rigorous methodologies, interdisciplinary research, and the transfer of results toward
          technological applications. She has participated in research projects aimed at understanding
          the relationship between structure, properties, and performance of materials, contributing to
          advances in the field and fostering high-level scientific collaborations.
        </p>
      </section>
      <!-- Research Interests -->
      <section class="mb-4">
        <h3>Research Interests</h3>
        <ul>
          <li>Design of porous architectures</li>
          <li>Solid-State NMR</li>
          <li>Nuclear Waste Management</li>
          <li>Clay and 2D-Si based solid electrolytes</li>
        </ul>
      </section>
      <!-- Publications -->
      <section class="mb-4">
        <h3>
            <a href="{{ '/publications/' | relative_url }}" style="color: inherit">Selected publications</a>
        </h3>
        <div class="publications">
          {% bibliography --group_by none --query @*[selected=mda] %}
        </div>
      </section>
    </div>
  </div>
</div>





