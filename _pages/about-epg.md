---
layout: default
title: Esperanza Pavón
permalink: /about-epg/
nav: false
---

<div class="container my-5">
  <div class="row">    
    <!-- Left Column (20% width) -->
    <div class="col-lg-3 col-md-4 mb-4">
      <div class="mb-3">
        <!-- Profile Image -->
        {% include figure.liquid path="assets/img/people/avatar-epg.jpg" title="Esperanza Pavón" class="rounded z-depth-1 rounded-circle" %}
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
            <i class="fa-regular fa-envelope"></i> epavon (at) us.es<br>
            <i class="fa-solid fa-square-phone"></i> +34 954489546
          </p>
      </div>
      <!-- Social Icons -->
      <div class="mt-4">
        <h6 class="text-muted mb-1 tracking-wider">LINKS</h6>
          <!-- ORCID -->
          <a href="https://orcid.org/0000-0002-4476-4403" title="ORCID">
          <i class="ai ai-orcid-square ai-2x"></i></a>
          <!-- Google Scholar -->
          <a href="https://scholar.google.es/citations?user=qCJv1kAAAAAJ" title="Google Scholar">
          <i class="ai ai-google-scholar-square ai-2x"></i></a>
          <!-- Scopus -->
          <a href="https://www.scopus.com/authid/detail.uri?authorId=14034550500" title="Scopus">
          <i class="ai ai-scopus-square ai-2x"></i></a>
          <!-- Linkedin -->
          <a href="www.linkedin.com/in/esperanza-p-64b78928" title="Linkedin">
          <i class="fa-brands fa-linkedin fa-2x"></i></a>
          <!-- Researched ID -->
          <a href="https://www.webofscience.com/wos/author/record/E-6336-2010" title="Researched Id">
          <i class="ai ai-researcherid-square ai-2x"></i></a>
        </div>
    </div>
    <!-- Right Column (Main Content) -->
    <div class="col-lg-9 col-md-8">
      <h1 class="mb-3">Dr. Esperanza Pavón González</h1>
      <h4 class="text-muted mb-4">Associate Professor</h4>
      <!-- About Section -->
      <section class="mb-4">
        <h3>About</h3>
        <p>I am an Associate Professor in the Department of Condensed Matter Physics at the University of Seville and a researcher at the Materials Science Institute of Seville (ICMS), a joint US-CSIC centre.  Since 2024, I have led the Solid State Chemistry Group (FQM212), where we employ a multidisciplinary approach bridging materials science, environmental chemistry, and advanced structural characterization. My career is driven by a commitment to understanding the fundamental structure of materials to design practical solutions for pressing global environmental challenges.</p>
        <p>My research expertise is rooted in advanced structural characterization, particularly through Solid State NMR, a field I refined during my postdoctoral time at the University of Lille (France). Currently, I apply this knowledge to two critical pillars: environmental remediation and radioactive waste management. In the latter, I serve as Principal Investigator (PI) for a project funded by the Spanish Nuclear Safety Council (CSN), to optimize dry storage systems for nuclear waste materials. Simultaneously, I am spearheading a strategic line focused on 2D silicates for energy storage, aiming to develop advanced solid-state electrolytes for the next generation of Li-ion batteries in the EU—a project currently supported by the Junta de Andalucía (2026–2029).</p>
        <p>Throughout my career, I have published 43 papers in high-impact journals (76% in Q1), co-authored 3 patents, and participated in 14 research projects, leading four of them with combined funding exceeding 400k€. My international profile is highlighted by active collaborations in France, Chile, and Colombia, as well as being honoured with the International NMR Bruker-University of Seville Prize.</p>
        <p>Beyond research, I balance my scientific activity with teaching across Chemistry, Pharmacy, Physics, and Materials Engineering degrees, alongside international postgraduate courses. I have organized four international schools on Solid State NMR. I have supervised 1 PhD student (Dr. Osuna, 2019) and nowadays, I am the codirector of 3 PhD, including a co-direction with EC-JRC Karlsruhe. </p>
      </section>
      <!-- Research Interests -->
      <section class="mb-4">
        <h3>Research Interests</h3>
        <ul>
          <li>Silicate-based 2D nanomaterials</li>
          <li>Solid-State NMR</li>
          <li>Nuclear Waste Management</li>
          <li>Hybrid Solid-State Electrolytes</li>
        </ul>
      </section>
      <!-- Publications -->
      <section class="mb-4">
        <h3>
            <a href="{{ '/publications/' | relative_url }}" style="color: inherit">Selected publications</a>
        </h3>
        <div class="publications">
          {% bibliography -f selected-epg --group_by none %}
        </div>
      </section>
    </div>
  </div>
</div>





