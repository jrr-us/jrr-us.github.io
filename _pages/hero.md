---
layout: default
title: hero
permalink: /hero/
nav: true
---

<div class="px-4 py-5 my-5 text-center rounded">
  <img
    class="d-block mx-auto mb-4"
    src="/assets/img/logos/hero-logo.svg"
    alt=""
    width="120"
  />
  <h1 class="display-5 fw-bold text-body-emphasis">Centered hero</h1>
  <div class="col-lg-11 mx-auto">
    <p class="lead mb-0">
      Quickly design and customize responsive mobile-first sites with Bootstrap,
      the world’s most popular front-end open source toolkit, featuring Sass
      variables and mixins, responsive grid system, extensive prebuilt
      components, and powerful JavaScript plugins.
    </p>
    >
    <div class="d-grid gap-2 d-sm-flex justify-content-sm-center">
      <button type="button" class="btn btn-primary btn-lg px-4 gap-3">
        Primary button
      </button>
      <button type="button" class="btn btn-outline-secondary btn-lg px-4">
        Secondary
      </button>
    </div>
  </div>
</div>

<div class="container my-5">
  <div class="row">    
    <!-- Left Column (20% width) -->
    <div class="col-lg-3 col-md-4 mb-4">
      <!-- Profile Image -->
      {% include figure.liquid path="assets/img/people/avatar-1.jpg" title="My Profile" class="rounded z-depth-1 rounded-circle" %}
      <!-- Affiliation -->
      <div class="mb-3">
        <h6 class="text-muted mb-1">Affiliation</h6>
        <p class="mb-0">Department of Computer Science<br>
        University of Example<br>
        City, Country</p>
      </div>
      <!-- Social Icons -->
      <div class="mt-4">
        <!-- Google Scholar -->
        <a href="https://scholar.google.com/citations?user=xZAS4bUAAAAJ" title="Google Scholar">
        <i class="ai ai-google-scholar-square ai-2x"></i></a>
        <!-- Scopus -->
        <a href="https://www.scopus.com/authid/detail.uri?authorId=1234567890" title="Scopus">
        <i class="ai ai-scopus ai-2x"></i></a>
        <!-- Google Scholar -->
      </div>
    </div>
    <!-- Right Column (Main Content) -->
    <div class="col-lg-9 col-md-8">
      <h1 class="mb-3">Dr. Jane Doe</h1>
      <h4 class="text-muted mb-4">Associate Professor of Computer Science</h4>
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
            <a href="{{ '/publications/' | relative_url }}" style="color: inherit">selected publications</a>
        </h2>
        {% include selected_papers.liquid %}
      </section>
      <!-- Contact -->
      <section>
        <h3>Contact</h3>
        <p>
          <i class="bi bi-envelope"></i> jane.doe@university.edu<br>
          <i class="bi bi-telephone"></i> +1 (555) 123-4567
        </p>
      </section>
    </div>
  </div>
</div>





