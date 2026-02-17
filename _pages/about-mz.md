---
layout: default
title: hero
permalink: /about-mz/
nav: false
---

<div class="container my-5">
  <div class="row">    
    <!-- Left Column (20% width) -->
    <div class="col-lg-3 col-md-4 mb-4">
      <div class="mb-3">
        <!-- Profile Image -->
        {% include figure.liquid path="assets/img/people/avatar-mz.jpg" title="Maider Zarrabeitia" class="rounded z-depth-1 rounded-circle" %}
      </div>
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
            <i class="fa-regular fa-envelope"></i> maider.zarrabeitia (at) icmse.csic.es<br>
            <i class="fa-solid fa-square-phone"></i> +34 954 13 92 35 (446170)
          </p>
      </div>
      <!-- Social Icons -->
      <div class="mt-4">
        <h6 class="text-muted mb-1 tracking-wider">LINKS</h6>
          <!-- ORCID -->
          <a href="https://orcid.org/0000-0003-1305-2136" title="ORCID">
          <i class="ai ai-orcid-square ai-2x"></i></a>
          <!-- Google Scholar -->
          <a href="https://scholar.google.es/citations?user=YYmTcZcAAAAJ&hl=es" title="Google Scholar">
          <i class="ai ai-google-scholar-square ai-2x"></i></a>
          <!-- Scopus -->
          <a href="https://www.scopus.com/authid/detail.uri?authorId=56533588600" title="Scopus">
          <i class="ai ai-scopus-square ai-2x"></i></a>
          <!-- Linkedin -->
          <a href="https://www.linkedin.com/in/maider-zarrabeitia-ipi%C3%B1a-9178a3109/" title="Linkedin">
          <i class="fa-brands fa-linkedin fa-2x"></i></a>
          <!-- Publons -->
          <a href="https://publons.com/researcher/3127967/maider-zarrabeitia/" title="Publons">
          <i class="ai ai-publons-square ai-2x"></i></a>
        </div>
    </div>
    <!-- Right Column (Main Content) -->
    <div class="col-lg-9 col-md-8">
      <h1 class="mb-3">Dr. Maider Zarrabeitia</h1>
      <h4 class="text-muted mb-4">Tenured Scientist, CSIC</h4>
      <!-- About Section -->
      <section class="mb-4">
        <h3>About</h3>
        <p>Dr. Zarrabeitia holds a Chemistry degree (2012), a Master&#39;s degree in New Materials (2013), and a PhD (2016) in Materials Science and Technology from UPV/EHU (Spain). Her PhD thesis, developed at CIC energigune (Spain) and supported by a predoctoral fellowship, including two research stays at the University of Camerino (Italy), received Extraordinary Doctoral Prizes. She joined the UPV/EHU as a postdoctoral researcher in 2017, and in 2018, she was awarded a postdoctoral fellowship to further develop her skills at the Helmholtz Institute Ulm (HIU, Germany). In 2020, she became a researcher at Karlsruhe Institute of Technology (KIT, Germany). In 2022, she became an Associated Principal Investigator and Group Leader of &quot;Beyond Li-batteries: materials &amp; interphases&quot; at HIU/KIT (Germany). In addition, she conducted a short research stay at the Warwick Manufacturing Group (Warwick University, UK) and ICTP-CSIC (Spain), respectively, financially supported by i-link 2023, for manufacturing solid-state polymer electrolyte-based Na-pouch cells and broadband spectroscopy dielectric (BSD) experiments. In December 2025, she joined ICMS-CSIC as a Ramón y Cajal research fellow (ranked first in Materials Science) and, in January 2026, became a tenured scientist.</p>
        <p>Her research activities focus on the synthesis, design, optimization, and characterization of sustainable anode and cathode materials/electrodes, as well as polymer electrolytes for sodium- and potassium-batteries. Her main expertise is understanding the mechanisms of electrolyte (liquids and polymers) decomposition and investigating electrode-electrolyte interfaces using X-ray photoelectron spectroscopy (XPS) and electrochemical impedance spectroscopy (EIS). Her extensive background in the field led her to collaborate extensively with research groups abroad (UK, Portugal, Italy, Spain, France, Germany).</p>
        <p>She was/is the (co-) principal investigator of national and international competitive research projects and has also participated in industrial projects/partnerships. She is the author of 70 articles published in high-impact international journals, with &gt;2700 citations (h-index = 30; Q1 journals). She has supervised 1 TFG, 2 TFM, and 3 Doctoral theses. She also participated in several workshops on electrochemistry and electrode-electrolyte interfaces for young researchers and disseminated the results at &gt;50 national and international conferences. She is a regular reviewer for high-impact journals and competitive calls. She has been organizing international conferences (INaC 2023 – Germany, KIC-25 – Spain &amp; MATSUS2025 - Spain). Finally, she is a member of RSEQ and RSEQ-GEE, where she was recently awarded the Electrochemistry 2025 Group &quot;Young Talents&quot; Award from the Spanish Royal Society of Chemistry and Electrochemistry Group (RSEQ-GEE) and the &quot;Emerging Investigator&quot; award by the Journal of Materials Chemistry A.</p>
      </section>
      <!-- Research Interests -->
      <section class="mb-4">
        <h3>Research Interests</h3>
        <ul>
          <li>Electrode – electrolyte interphase studies</li>
          <li>Advanced solid polymer electrolytes</li>
          <li>Development of sustainable materials for batteries</li>
          <li>Beyond Li-technology</li>
        </ul>
      </section>
      <!-- Publications -->
      <section class="mb-4">
        <h3>
            <a href="{{ '/publications/' | relative_url }}" style="color: inherit">Selected publications</a>
        </h3>
        <div class="publications">
          {% bibliography -f selected-mz --group_by none %}
        </div>
      </section>
    </div>
  </div>
</div>