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
      <div class="mb-3">
        <!-- Profile Image -->
        {% include figure.liquid path="assets/img/people/avatar-mda.jpg" title="María D. Alba" class="rounded z-depth-1 rounded-circle" %}
      </div>
      <!-- Affiliation -->
      <div class="mb-3">
        <h6 class="text-muted mb-1 tracking-wider">AFFILIATION</h6>
        <p class="mb-0">Spanish National Research Council<br>
        Materials Science Institute<br>
        Seville, Spain</p>
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
          <i class="ai ai-scopus-square ai-2x"></i></a>
          <!-- Linkedin -->
          <a href="https://www.linkedin.com/in/maria-d-alba-81b336112/" title="Linkedin">
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
        <p>Dr. Alba is a Research Scientist at the CSIC. She has teaching and research experience spanning 35 years and has been granted six five-year terms and five six-year terms. She is accredited by the Council of Universities for a Full Professor position. She is a scientist specializing in Materials Science and Technology, with experience in the development, characterization, and analysis of sustainable materials from an experimental and applied perspective. Her scientific trajectory focuses on the generation of knowledge based on rigorous methodologies, interdisciplinary research, and the transfer of results toward technological applications. She has participated in research projects aimed at understanding the relationship between structure, properties, and performance of materials, contributing to advances in the field and fostering high-level scientific collaborations.</p>
        <p>She has published extensively in SCI journals, with a significant proportion of her work appearing in first-quartile publications, including Open Access reviews by invitation. She has contributed her own results at numerous national and international conferences and has been invited to give talks in seminars and conference series. Her work has earned her the Extraordinary Doctorate Award, granted by the University of Seville, and the Young Investigators Award of the Real Maestranza de Caballería, awarded by the Royal Academy of Sciences of Seville.</p>
        <p>She has been responsible for teaching undergraduate, postgraduate, and Master&#39;s theoretical courses at the University of Seville. She has participated in teaching innovation projects and has a contribution in the journal <em>Enseñanza Universitaria</em>. She has been the director of a postgraduate course at the CSIC and has been invited to participate in postgraduate and Master&#39;s courses at IACT, ICV, Peking University (China), the University of Córdoba, the State University of Londrina (Brazil), and the Pedagogical and Technological University of Colombia (Tunja, Colombia). She has directed multiple Bachelor&#39;s theses, doctoral theses, Final Degree Projects, and Master&#39;s Final Projects, and has tutored Erasmus Mundus students. Currently, she directs one doctoral thesis.</p>
        <p>Since December 2012, she has been the head of the ICMS &quot;Design of Materials for Energy and Environment&quot; research group and, since 2017, also of the Solid-State Chemistry group (FQM-212) of the Junta de Andalucía. She has been the scientific manager of cicCartuja&#39;s Solid-State Nuclear Magnetic Resonance Service and the director of the ICMS Spectroscopy Service.</p>
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
          {% bibliography -f selected-mda --group_by none %}
        </div>
      </section>
    </div>
  </div>
</div>





