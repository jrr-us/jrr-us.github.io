---
layout: default
title: hero
permalink: /about-jv/
nav: false
---

<div class="container my-5">
  <div class="row">    
    <!-- Left Column (20% width) -->
    <div class="col-lg-3 col-md-4 mb-4">
      <!-- Profile Image -->
      {% include figure.liquid path="assets/img/people/avatar-jc.jpg" title="Joao Coelho" class="rounded z-depth-1 rounded-circle" %}
      <!-- Affiliation -->
      <div class="mb-3">
        <h6 class="text-muted mb-1 tracking-wider">AFFILIATION</h6>
        <p class="mb-0">University of Sevilla<br>
        Materials Science Institute<br>
        Sevilla, Spain</p>
      </div>
      <div class="mb-3">
        <h6 class="text-muted mb-1 tracking-wider">CONTACT</h6>
          <p>
            <i class="fa-regular fa-envelope"></i> jmesquita (at) us.es<br>
            <i class="fa-solid fa-square-phone"></i> +34 607453334
          </p>
      </div>
      <!-- Social Icons -->
      <div class="mt-4">
        <h6 class="text-muted mb-1 tracking-wider">LINKS</h6>
          <!-- ORCID -->
          <a href="https://orcid.org/0000-0003-4217-3842" title="ORCID">
          <i class="ai ai-orcid-square ai-2x"></i></a>
          <!-- Google Scholar -->
          <a href="https://scholar.google.com/citations?user=STluLCYAAAAJ&hl=en" title="Google Scholar">
          <i class="ai ai-google-scholar-square ai-2x"></i></a>
          <!-- Scopus -->
          <a href="https://www.scopus.com/authid/detail.uri?authorId=56113316000" title="Scopus">
          <i class="ai ai-scopus-square ai-2x"></i></a>
          <!-- Linkedin -->
          <a href="https://www.linkedin.com/in/jcmcoelho/" title="Linkedin">
          <i class="fa-brands fa-linkedin fa-2x"></i></a>
          <!-- Publons -->
          <a href="https://www.webofscience.com/wos/author/record/O-5741-2019" title="Researcher ID">
          <i class="ai ai-resercherid-square ai-2x"></i></a>
        </div>
    </div>
    <!-- Right Column (Main Content) -->
    <div class="col-lg-9 col-md-8">
      <h1 class="mb-3">Dr.João C. Coelho</h1>
      <h4 class="text-muted mb-4">EMERGIA Fellow, US</h4>
      <!-- About Section -->
      <section class="mb-4">
        <h3>About</h3>
        <p>Dr. João Coelho is an EMERGIA Postdoctoral Researcher at the University of Sevilla and the Materials Science Institute of Sevilla (ICMS, US-CSIC), where he leads an independent research line dedicated to the sustainable development of flexible energy storage systems. </p>
        <p>He earned his PhD at Trinity College Dublin (2016) under Professor Valeria Nicolosi, specializing in the ultrasound-assisted exfoliation of layered crystals to produce high-performance 2D material electrodes. Following a postdoctoral tenure in Dublin (2017-2020) focused on printed supercapacitors and novel battery chemistries, he was awarded a prestigious FCT Individual Scientific Employment Stimulus grant in 2020 to join Professor Elvira Fortunato’s group <em>at Universidade NOVA de Lisboa</em>. There, he pioneered the use of laser-induced graphene (LIG) on paper substrates, significantly advancing the field of sustainable, thin-film energy devices. Since securing an EMERGIA talent grant in 2022, Dr. Coelho has established himself as an independent researcher in materials science.</p>
        <p>Dr. João Coelho served as Principal Investigator on four projects with total funding exceeding €580,000. His prolific research record includes 49 peer-reviewed papers—with a majority in Q1 journals—and over 5,700 citations, resulting in a h-index of 30 and a Field-Weighted Citation Impact (FWCI) of 2.77. Materials Research Society Spring 2024 (Virtual), 2024 IEEE International Flexible Electronics Technology Conference (IFETC) (Bologna, Italy) and Materials for Sustainable Development Conference (MATSUS25) Spring 2025 (Seville, Spain). He was also a guest editor in <em>npj 2d materials and applications</em> for a collection entitled <em>2D Nanomaterials for Energy Applications</em> and in a special issue on <em>Sustainable Development of Printed Electronics: From Materials Processing to Devices Implementation</em> from ACS Applied Electronic Materials. Since 2021, he organizes the printed electronics symposium for the Brazilian Materials Research Society, since 2021. Beyond his technical achievements, Dr. Coelho remains committed to scientific communication through his active role in the ICMS Commissions for Dissemination and Communication and Gender Equality, Diversity, and Ethics.</p>
      </section>
      <!-- Research Interests -->
      <section class="mb-4">
        <h3>Research Interests</h3>
        <ul>
          <li>2D nanomaterials</li>
          <li>Advanced Energy Storage Devices</li>
          <li>Printed and Flexible Electronics</li>
          <li>Green Chemistry and Manufacturing</li>
        </ul>
      </section>
      <!-- Publications -->
      <section class="mb-4">
        <h3>
            <a href="{{ '/publications/' | relative_url }}" style="color: inherit">Selected publications</a>
        </h3>
        <div class="publications">
          {% bibliography -f selected-jc --group_by none %}
        </div>
      </section>
    </div>
  </div>
</div>





