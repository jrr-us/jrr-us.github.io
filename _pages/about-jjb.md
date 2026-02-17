---
layout: default
title: hero
permalink: /about-jjb/
nav: false
---

<div class="container my-5">
  <div class="row">    
    <!-- Left Column (20% width) -->
    <div class="col-lg-3 col-md-4 mb-4">
      <!-- Profile Image -->
      {% include figure.liquid path="assets/img/people/avatar-aral.jpg" title="José Jesús Benítez" class="rounded z-depth-1 rounded-circle" %}
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
            <i class="fa-regular fa-envelope"></i> benitez (at) icmse.csic.es<br>
            <i class="fa-solid fa-square-phone"></i> +34 9554489551
          </p>
      </div>
      <!-- Social Icons -->
      <div class="mt-4">
        <h6 class="text-muted mb-1 tracking-wider">LINKS</h6>
          <!-- ORCID -->
          <a href="https://orcid.org/0000-0002-3222-0564" title="ORCID">
          <i class="ai ai-orcid-square ai-2x"></i></a>
          <!-- Scopus -->
          <a href="https://www.scopus.com/authid/detail.uri?authorId=7203010370" title="Scopus">
          <i class="ai ai-scopus-square ai-2x"></i></a>
          <!-- ResearcherID -->
          <a href="https://www.webofscience.com/wos/author/record/K-5662-2014" title="Researcher ID">
          <i class="ai ai-researcherid-square ai-2x"></i></a>
        </div>
    </div>
    <!-- Right Column (Main Content) -->
    <div class="col-lg-9 col-md-8">
      <h1 class="mb-3">Dr. José Jesús Benítez Jiménez</h1>
      <h4 class="text-muted mb-4">Tenured Scientist, CSIC</h4>
      <!-- About Section -->
      <section class="mb-4">
        <h3>About</h3>
        <p>I hold a PhD from University of Seville in Materials Science from 1991 supported by a predoctoral PFPI Andalusian government grant (1988-1991). I spent a postdoctoral period (1991-1993) at the Materials Division of the Lawrence Berkeley National Laboratory (California) as a senior Fulbright fellow in professor Salmeron&#39;s group working in surface characterization with scanning probe microscopies (STM, AFM, SPFM). I returned to the Materials Science Institute of Seville (ICMS) under a competitive call from the Spanish Ministry of Education and Science as a postdoctoral researcher from 1993 to 1995. This same year I became associated professor at the Department of Inorganic Chemistry of the University of Seville (1995-1997) and in 1997 I got a permanent position as a Tenured Scientist at ICMS (Spanish Research Council).</p>
        <p>I reinforced my relationship with Surface Science and Catalysis laboratory at LBNL with the support of a NATO grant in 2000 and an on-leave program by the Spanish Ministry de Education and Science in 2001. My research has covered several topics ranging from surface structure and reactivity, metal corrosion, catalysis, coatings and molecular self-assembly and, in the last two decades, to the design of bioinspired polymers and coatings for food packaging and preservation as well as the physical and chemical characterization of fruit cuticles. As a researcher, I have participated in 29 research projects funded by National and European programs and private organizations. As the main researcher, I have directed and co-directed 4 projects of the National I+D+I program, 2 funded by the Innovation, Science and Industry department of the Andalusian government and 2 supported by private companies. I was also responsible for a section of a Marie Curie Action (EST) from the European Union. </p>
        <p>My current research is concentrated on the characterization of plant cuticles and in the obtaining of bioinspired polymers and biodegradable coatings and composites from agricultural wastes for food packaging. I have published 126 articles in indexed scientific journals, 19 book chapters and I co-edited 4 books. I have also coauthored 16 confidential scientific reports to private companies and government agencies and participated in 4 research contracts with industries. I hold 5 patents (one national and four international) four of them related to the preparation of polymeric materials from renewable sources. I made contributions to 87 national or international congresses and I have directed one PhD thesis and 7 master degree projects. I have been a member of the evaluation committee of 13 PhD theses. I have also taught in 2 masters at Spanish Universities and in 24 specializing courses and participated in 2 international conferences as invited speaker. I hosted 18 graduated students and postdocs under different national and international formation programs.</p>
      </section>
      <!-- Research Interests -->
      <section class="mb-4">
        <h3>Research Interests</h3>
          <ul>
            <li>Biopolymers</li>
            <li>Bioinspired polymeric materials</li>
            <li>Food packaging materials</li>
            <li>Plant cuticle characterization</li>
            <li>Pre and postharvest treatments</li>
          </ul>
      </section>
      <!-- Publications -->
      <section class="mb-4">
        <h3>
            <a href="{{ '/publications/' | relative_url }}" style="color: inherit">Selected publications</a>
        </h3>
        <div class="publications">
          {% bibliography -f selected-jjb --group_by none %}
        </div>
      </section>
    </div>
  </div>
</div>