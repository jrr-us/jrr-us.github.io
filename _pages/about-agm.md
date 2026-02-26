---
layout: default
title: Aurora Gómez
permalink: /about-agm/
nav: false
---

<div class="container my-5">
  <div class="row">    
    <!-- Left Column (20% width) -->
    <div class="col-lg-3 col-md-4 mb-4">
      <div class="mb-3">
        <!-- Profile Image -->
        {% include figure.liquid path="assets/img/people/avatar-agm.jpg" title="Aurora Gómez" class="rounded z-depth-1 rounded-circle" %}
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
            <i class="fa-regular fa-envelope"></i>agomez28 (at) us.es<br>
            <i class="fa-regular fa-envelope"></i>aurora.gmartin (at) icmse.csic.es<br>
            <i class="fa-solid fa-square-phone"></i> +34 954 13 92 35
          </p>
      </div>
      <!-- Social Icons -->
      <div class="mt-4">
        <h6 class="text-muted mb-1 tracking-wider">LINKS</h6>
          <!-- ORCID -->
          <a href="https://orcid.org/0000-0001-7053-3986" title="ORCID">
          <i class="ai ai-orcid-square ai-2x"></i></a>
          <!-- Google Scholar -->
          <a href="https://scholar.google.com/citations?user=9YcbQwYAAAAJ" title="Google Scholar">
          <i class="ai ai-google-scholar-square ai-2x"></i></a>
          <!-- Scopus -->
          <a href="https://www.scopus.com/authid/detail.uri?authorId=57189361571" title="Scopus">
          <i class="ai ai-scopus-square ai-2x"></i></a>
          <!-- Linkedin -->
          <a href="https://www.linkedin.com/in/dr-aurora-gomez-martin/" title="Linkedin">
          <i class="fa-brands fa-linkedin fa-2x"></i></a>
        </div>
    </div>
    <!-- Right Column (Main Content) -->
    <div class="col-lg-9 col-md-8">
      <h1 class="mb-3">Dr. Aurora Gómez Martín</h1>
      <h4 class="text-muted mb-4">Postdoctoral Researcher</h4>
      <!-- About Section -->
      <section class="mb-4">
        <h3>About</h3>
        <p>Dr. Gómez Martín is currently a researcher at the Institute of Materials Science of Seville (ICMS, US–CSIC), where she develops 3D-printed hierarchical carbon-based lattice structures for energy-storage applications, with a strong focus on tailoring structure–property relationships. Her prior research focused on the development of advanced functional materials for the energy transition and environmental sustainability, particularly for energy storage. Her work includes designing active electrode materials—carbon- and silicon-based anodes and metal-oxide cathodes—for lithium- and sodium-ion batteries, prelithiation strategies, and in-depth studies of degradation phenomena to understand the mechanisms limiting performance and lifetime in laboratory-scale and large-format cells. This research has taken place in both academic and industrial R&amp;D environments within the automotive sector.</p>
        <p>She earned her BSc in Physics (2014), MSc (2015), and PhD (2019) in Science and Technology of New Materials from the University of Seville (Spain). Her doctoral research on graphitization of biomass-derived carbon anodes for lithium- and sodium-ion batteries was recognized with the Extraordinary Doctorate Award. During this period, she completed two competitive DAAD fellowships for research stays at the MEET Battery Research Center (University of Münster, Germany).</p>
        <p>Following her PhD, she joined MEET as a postdoctoral researcher (2020–2023) within a Horizon 2020 European consortium developing high-energy lithium cells. She focused on advanced electrode materials, including nickel-rich cathodes and silicon-based anodes, with emphasis on degradation mechanisms and prelithiation strategies. She led independent research lines, directly supervised three MSc and four PhD students, and served as sub-coordinator of two work packages.</p>
        <p>From 2023 to 2025, she worked at BMW Group’s Battery Cell Competence Center (BCCC, Munich, Germany) as technical lead for cell aging and failure analysis. She led a research and engineering team, developing methodologies to identify and understand degradation processes in large-format lithium-ion cells. This work involved close collaboration with global cell manufacturers, material suppliers, and research centres.</p>
        <p>She is co-author of 38 peer-reviewed publications (82% in Q1 journals; ten featured on journal covers) and one book chapter. Her work has accumulated over 1,800 citations and an h-index of 21. She has presented her research at 12 conferences, including three invited talks, and has received four best-presentation awards. She has participated in 6 competitive research projects, including national and international initiatives funded by the European Union, the German government, and the Spanish government. </p>
      </section>
      <!-- Research Interests -->
      <section class="mb-4">
        <h3>Research Interests</h3>
        <ul>
          <ul>
            <li>Sustainable carbon materials</li>
            <li>Anode and cathode active materials</li>
            <li>Li-ion and post-Li batteries</li>
            <li>Cell aging and lifetime</li>
            <li>Advanced characterization techniques</li>
          </ul>
        </ul>
      </section>
      <!-- Publications -->
      <section class="mb-4">
        <h3>
            <a href="{{ '/publications/' | relative_url }}" style="color: inherit">Selected publications</a>
        </h3>
        <div class="publications">
          {% bibliography -f selected-agm --group_by none %}
        </div>
      </section>
    </div>
  </div>
</div>





