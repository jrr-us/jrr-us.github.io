---
layout: default
title: hero
permalink: /about-jrr/
nav: false
---

<div class="container my-5">
  <div class="row">    
    <!-- Left Column (20% width) -->
    <div class="col-lg-3 col-md-4 mb-4">
      <div class="mb-3">
        <!-- Profile Image -->
        {% include figure.liquid path="assets/img/people/avatar-jrr.jpg" title="Joaquin Ramirez-Rico" class="rounded z-depth-1 rounded-circle" %}
      </div>
      <!-- Affiliation -->
      <div class="mb-3">
        <h6 class="text-muted mb-1 tracking-wider">AFFILIATION</h6>
        <p class="mb-0">University of Seville<br>
        Materials Science Institute<br>
        Seville, Spain</p>
      </div>
      <div class="mb-3">
        <h6 class="text-muted mb-1 tracking-wider">CONTACT</h6>
          <p>
            <i class="fa-regular fa-envelope"></i> jrr (at) us.es<br>
            <i class="fa-solid fa-square-phone"></i> +34 954550963
          </p>
      </div>
      <!-- Social Icons -->
      <div class="mt-4">
        <h6 class="text-muted mb-1 tracking-wider">LINKS</h6>
        <!-- ORCID -->
        <a href="https://orcid.org/0000-0002-1184-0756" title="ORCID">
        <i class="ai ai-orcid-square ai-2x"></i></a>
        <!-- Google Scholar -->
        <a href="https://scholar.google.com/citations?user=xZAS4bUAAAAJ" title="Google Scholar">
        <i class="ai ai-google-scholar-square ai-2x"></i></a>
        <!-- Scopus -->
        <a href="https://www.scopus.com/authid/detail.uri?authorId=12769290000" title="Scopus">
        <i class="ai ai-scopus-square ai-2x"></i></a>
        <!-- Linkedin -->
        <a href="https://www.linkedin.com/in/joaquin-ramirez-rico-a7a716a6/" title="Linkedin">
        <i class="fa-brands fa-linkedin fa-2x"></i></a>
      </div>
    </div>
    <!-- Right Column (Main Content) -->
    <div class="col-lg-9 col-md-8">
      <h1 class="mb-3">Dr. Joaquín Ramírez-Rico</h1>
      <h4 class="text-muted mb-4">Full Professor, University of Seville</h4>
      <!-- About Section -->
      <section class="mb-4">
        <h3>About</h3>
        <p>Joaquín Ramírez Rico is a Full Professor (<em>Catedrático</em>) in the Department of Condensed Matter Physics at the University of Seville, Spain, and a researcher at the Materials Science Institute of Seville (ICMS), a joint University of Seville–CSIC research center. Since 2019, he leads the Biomimetic and Multifunctional Materials Research Group (FQM342), coordinating multidisciplinary efforts at the intersection of materials science, energy, and sustainability.</p>
        <p>His research career traces a deliberate arc from structural ceramics to functional materials for the energy transition. After earning his PhD in Materials Science from the University of Seville in 2008 — with work focused on the micromechanics of eutectic ceramics and advanced characterization at large-scale facilities including Argonne National Laboratory — he completed a postdoctoral stay at Northwestern University (USA), where he specialized in stress analysis of complex composite materials.</p>
        <p>Since 2012, he has pioneered research on biomass-derived carbon materials for high-impact energy applications, including supercapacitors, capacitive desalination, and lithium-ion and sodium-ion battery anodes. This work is carried out in close collaboration with leading international institutions such as the Münster Electrochemical Energy Technology Institute (Germany) and the University of Birmingham (UK). He also maintains active lines of research on high-temperature proton conductors for solid oxide fuel cells and electrolyzers, as well as porous biomorphic silicon carbide for environmental filtration.</p>
        <p>Beyond the lab, Joaquín has served since 2016 as Scientific Director of the X-ray Laboratory within the University of Seville&#39;s General Research Services, overseeing a team of six permanent technicians and managing high-value scientific instrumentation. His capacity for securing resources is reflected in over €4.5 million in funding obtained as Principal Investigator, spanning competitive research grants and major infrastructure projects — including two projects exceeding €1 million each awarded in 2024. He also holds two patents on porous material applications and has led an industrial research contract with the refractory company Alfran.</p>
        <p>He is the author or co-author of 95 indexed publications (Scopus), with an h-index of 31 (Google Scholar) and over 2,700 citations. He has supervised four doctoral theses and holds three recognized six-year research periods (<em>sexenios</em>). His work has been presented as invited talks at international conferences across the Americas, Europe, and Asia, including events organized by the American Ceramic Society and the Brazilian MRS. He previously served as coordinator of the Materials Science MSc program at the University of Seville (2013–2016), reflecting a sustained commitment to training the next generation of materials scientists.</p>
      </section>
      <!-- Research Interests -->
      <section class="mb-4">
        <h3>Research Interests</h3>
        <ul>
          <li>Polymer-derived carbon materials</li>
          <li>Catalytic graphitization</li>
          <li>Porous materials</li>
          <li>Advanced X-ray characterization and in-situ techniques</li>
        </ul>
      </section>
      <!-- Publications -->
      <section class="mb-4">
        <h3>
            <a href="{{ '/publications/' | relative_url }}" style="color: inherit">Selected publications</a>
        </h3>
        <div class="publications">
          {% bibliography -f selected-jrr --group_by none %}
        </div>
      </section>
    </div>
  </div>
</div>