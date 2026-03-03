---
layout: default
title: home
permalink: /
announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder
social: true
---

<div class="row justify-content-center text-center mb-4">
  <div class="col-8 col-xl-4 col-lg-4 col-md-4 col-sm-6">
    {% include figure.liquid loading="eager" path="assets/img/logos/mates-logo-light.svg" title="Logo" class="img-fluid only-light" %}
    {% include figure.liquid loading="eager" path="assets/img/logos/mates-logo-dark.svg" title="Logo" class="img-fluid only-dark" %}
  </div>
</div>

<h1 class="display-5 fw-bold text-body-emphasis text-center">Materials for Energy and Sustainability</h1>
<div class="py-3 rounded">
  <div class="col-lg-11 mx-auto">
    <p class="lead mb-0">
      <p>Located at the <strong>Instituto de Ciencia de Materiales de Sevilla (ICMS)</strong>—a joint research center of the <a href='https://www.csic.es'>CSIC</a> and the <a href='https://www.us.es'>University of Seville</a>—the MatES Lab is dedicated to addressing the global challenges of the 21st century through advanced materials science.</p>
      <p>Our research is driven by the urgent need for <strong>sustainable technological solutions</strong>. We focus on the rational design and synthesis of functional materials that can drive the transition to a green economy. By combining novel synthesis routes with advanced characterization techniques, we aim to unravel the mechanistic aspects of material performance.</p>
      <p><strong>Our Research Areas Include:</strong></p>
      <ul>
        <li><strong>Eco-Efficient Synthesis:</strong> Development of low-impact synthetic pathways and bio-inspired material processing.</li>
        <li><strong>Next-Gen Energy Storage:</strong> reducing critical raw materials in battery chemistries and enhancing energy density.</li>
        <li><strong>Environmental Remediation:</strong> Design of porous and active materials for the capture and degradation of environmental pollutants.</li>
        <li><strong>Advanced Characterization:</strong> In-situ and operando studies to elucidate structure-property relationships.</li>
      </ul>
      <p>We invite you to explore our publications, learn about our ongoing projects, and connect with our team of scientists.</p>
    </p>
    <div class="d-flex flex-wrap justify-content-center gap-2 mb-3">
      <a href="/research/" class="btn btn-secondary btn-lg px-4" role="button">
        ⚛️ Learn about our research
      </a>
      <a href="/people/" class="btn btn-secondary btn-lg px-4" role="button">
        🤲 Meet the MatES
      </a>
      <a href="/publications/" class="btn btn-secondary btn-lg px-4" role="button">
        📖 Check out our papers
      </a>
    </div>
    <!-- News -->
    <div class="post">
      {% if page.announcements and page.announcements.enabled %}
      <h2>
        <a href="{{ '/news/' | relative_url }}" style="color: inherit">news</a>
      </h2>
      {% include news.liquid limit=true %}
      {% endif %} 
    </div>
    <!-- Social -->
    {% if page.social %}
      <div class="social">
        <div class="contact-icons">{% include social.liquid %}</div>
        <div class="contact-note">{{ site.contact_note }}</div>
      </div>
    {% endif %}
  </div>
</div>






