---
layout: page
permalink: /publications/
title: publications
description: Find here a list of our publications in reversed chronological order.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">
{% bibliography --query @*[year>2019] %}
</div>
