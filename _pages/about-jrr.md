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
      <!-- Profile Image -->
      {% include figure.liquid path="assets/img/people/avatar-1.jpg" title="My Profile" class="rounded z-depth-1 rounded-circle" %}
      <!-- Affiliation -->
      <div class="mb-3">
        <h6 class="text-muted mb-1 tracking-wider">AFFILIATION</h6>
        <p class="mb-0">Condensed Matter Physics<br>
        Materials Science Institute<br>
        Sevilla, Spain</p>
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
        <!-- Google Scholar -->
        <h6 class="text-muted mb-1 tracking-wider">LINKS</h6>
        <a href="https://scholar.google.com/citations?user=xZAS4bUAAAAJ" title="Google Scholar">
        <i class="ai ai-google-scholar-square ai-2x"></i></a>
        <!-- Scopus -->
        <a href="https://www.scopus.com/authid/detail.uri?authorId=1234567890" title="Scopus">
        <i class="ai ai-scopus ai-2x"></i></a>
        <a href="https://www.linkedin.com/in/joaquin-ramirez-rico-a7a716a6/" title="Scopus">
        <i class="fa-brands fa-linkedin fa-2x"></i></a>
        <!-- Google Scholar -->
      </div>
    </div>
    <!-- Right Column (Main Content) -->
    <div class="col-lg-9 col-md-8">
      <h1 class="mb-3">Dr. Joaquín Ramírez-Rico</h1>
      <h4 class="text-muted mb-4">Full Professor</h4>
      <!-- About Section -->
      <section class="mb-4">
        <h3>About</h3>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod 
          tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, 
          quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
        </p>
        <p>
          Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore 
          eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.
        </p>
      </section>
      <!-- Research Interests -->
      <section class="mb-4">
        <h3>Research Interests</h3>
        <ul>
          <li>Machine Learning</li>
          <li>Artificial Intelligence</li>
          <li>Data Science</li>
          <li>Natural Language Processing</li>
        </ul>
      </section>
      <!-- Publications -->
      <section class="mb-4">
        <h2>
            <a href="{{ '/publications/' | relative_url }}" style="color: inherit">Selected publications</a>
        </h2>
        {% include selected_papers.liquid %}
        <div class="publications">
          {% bibliography --group_by none --query @*[selected=true && author=ramirez-rico]* %}
        </div>
      </section>
    </div>
  </div>
</div>





