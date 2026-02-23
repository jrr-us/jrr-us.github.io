---
layout: default
title: hero
permalink: /about-aral/
nav: false
---

<div class="container my-5">
  <div class="row">    
    <!-- Left Column (20% width) -->
    <div class="col-lg-3 col-md-4 mb-4">
      <div class="mb-3">
        <!-- Profile Image -->
        {% include figure.liquid path="assets/img/people/avatar-aral.jpg" title="Antonio R. de Arellano" class="rounded z-depth-1 rounded-circle" %}
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
            <i class="fa-regular fa-envelope"></i> aral (at) us.es<br>
            <i class="fa-solid fa-square-phone"></i> +34 954 55 97 23 (446170)
          </p>
      </div>
      <!-- Social Icons -->
      <div class="mt-4">
        <h6 class="text-muted mb-1 tracking-wider">LINKS</h6>
          <!-- ORCID -->
          <a href="https://orcid.org/0000-0002-7443-0244" title="ORCID">
          <i class="ai ai-orcid-square ai-2x"></i></a>
          <!-- Google Scholar -->
          <a href="https://scholar.google.com/citations?user=7VapokUAAAAJ" title="Google Scholar">
          <i class="ai ai-google-scholar-square ai-2x"></i></a>
          <!-- Scopus -->
          <a href="https://www.scopus.com/authid/detail.uri?authorId=7003586930" title="Scopus">
          <i class="ai ai-scopus-square ai-2x"></i></a>
          <!-- Linkedin -->
          <a href="https://www.linkedin.com/in/antonio-ram%C3%ADrez-de-arellano-46bb70226/" title="Linkedin">
          <i class="fa-brands fa-linkedin fa-2x"></i></a>
          <!-- Publons -->
          <a href="https://www.researchgate.net/profile/Antonio-Ramirez-De-Arellano-Lopez" title="Researchgate">
          <i class="ai ai-researchgate-square ai-2x"></i></a>
        </div>
    </div>
    <!-- Right Column (Main Content) -->
    <div class="col-lg-9 col-md-8">
      <h1 class="mb-3">Prof. Antonio R. de Arellano</h1>
      <h4 class="text-muted mb-4">Full Professor, University of Seville</h4>
      <!-- About Section -->
      <section class="mb-4">
        <h3>About</h3>
        <p>Antonio Ramírez de Arellano López is currently a Full Professor of Condensed Matter Physics at the University of Seville, Spain, where he received his B.S. (1987) and Ph.D. (1991) in Physics. He also holds a B.S. in Economics (1997) from the University of Seville.</p>
        <p>He is an expert in advanced technological ceramics, especially in mechanical properties and microstructural characterization of materials. Since 1990, he authored more numerous publications in the field of Material Science and Engineering. His long-term stays in important U.S.A. research institutions include Argonne National Laboratory, National Institute of Standards and Technology and Northwestern University.</p>
        <p>Original interests were related to the microscopic mechanisms that govern the high-temperature plastic deformation of ceramics, also as means of obtaining information of diffusion dynamics of minority species. His Ph.D. research, and subsequent work, was on structural ceramics and ceramic composites for high temperature applications, such as whisker- and particulate-reinforced Al2O3, Si3N4, mullite, … He has also conducted studies on the microstructural evolution of ceramic compounds and special structures, such as thermal barrier ceramic coatings. This expertise was subsequently applied to research on high-temperature superconductors with perovskite structures and proton conductors, including directional growth microstructures, such as those obtained for eutectic compositions.</p>
        <p>In 2004 Prof. Ramírez de Arellano López was one of the applicants that filed for a patent on the fabrication of Si/SiC composites (bioSiC) by reactive- melt-infiltration of Si in C preforms obtained from the pyrolization of natural precursors, as wood, resulting in an ample number of collaborations and international publications. A total of six patents or patent extensions were filed in subsequent years.</p>
        <p>From 2000 to 20012 seven Ph.D. thesis were advised or co-advised in Graduate and Ph.D. Programs in the University of Seville. At the same time, he was co-founder of the research Group ‘Materiales Biomiméticos y Multifuncionales - BMM’ (Biomimetic and Multifunctional Materials).</p>
        <p>In this period, he participated in several projects and contracts. In 12 of them the role was Principal Investigator, being a member of the research team in more than 30 other research initiatives and contracts, both public and private.</p>
        <p>Since 2000, he has been heavily involved in managing Academic and R&amp;D matters in the University of Seville, first as Vice-Dean of the Faculty of Physics, then as Director of Central R&amp;D Advanced Instrumentation Services, and finally as Vice-Rector of the university. In 2012, he was elected Rector of the University of Seville.</p>
        <p>In 2015, Prof. Antonio Ramírez de Arellano was appointed Regional Minister for Economy, University and R&amp;D in the Andalusian Regional Government (Junta de Andalucía). In charge of the basic matters and funding of Andalusian Public Universities and the development and funding of regional R&amp;D programs. From 2019 until 2022, he was a member of the Andalusian Regional Parliament (Socialist Party). Spoke person for Regional Finances, and member of the parliamentary committee on Universities and R&amp;D.</p>
        <p>In April 2022, he came back to the Full Professor position in the University of Seville, and to the BMM Research Group, led by Professor Joaquín Ramírez Rico, getting again involved in the research activities of the Group.</p>
      </section>
      <!-- Research Interests -->
      <section class="mb-4">
        <h3>Research Interests</h3>
        <ul>
          <li>Advanced Structural and Functional Materials</li>
          <li>Mechanical Properties</li>
          <li>Microstructural Characterization</li>
        </ul>
      </section>
      <!-- Publications -->
      <section class="mb-4">
        <h3>
            <a href="{{ '/publications/' | relative_url }}" style="color: inherit">Selected publications</a>
        </h3>
        <div class="publications">
          {% bibliography -f selected-aral --group_by none %}
        </div>
      </section>
    </div>
  </div>
</div>