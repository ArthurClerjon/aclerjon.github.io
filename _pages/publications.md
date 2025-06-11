---
layout: page
title: publications
permalink: /publications/
nav: true
nav_order: 6
---

<!-- _pages/publications.md -->

<!-- External Links with Icons -->
<p>
  Up-to-date publications are also available on:
</p>
<p style="display: flex; gap: 1rem; flex-wrap: wrap; align-items: center; margin-top: 0.5em;">
  <a href="https://scholar.google.fr/citations?user=X0s6r3QAAAAJ&hl=fr" target="_blank">
    <i class="ai ai-google-scholar"></i> Google Scholar
  </a>
  <a href="https://orcid.org/0000-0002-9545-988X" target="_blank">
    <i class="ai ai-orcid"></i> ORCID
  </a>
  <a href="https://www.researchgate.net/profile/Arthur-Clerjon" target="_blank">
    <i class="ai ai-researchgate"></i> ResearchGate
  </a>
</p>

<!-- Bibsearch Feature -->
{% include bib_search.liquid %}

<div class="publications">

<h2>PhD Thesis</h2>
{% bibliography -f papers --query "note == 'Thesis'" %}

<h2>Peer-reviewed Articles</h2>
{% bibliography -f papers --query "note == 'Peer-reviewed'" %}

<h2>Under Review</h2>
{% bibliography -f papers --query "note == 'Under review'" %}

<h2>Conference Proceedings</h2>
{% bibliography -f papers --query "note == 'Conference proceedings'" %}

<h2>Presentations</h2>
{% bibliography -f papers --query "note == 'Presentation'" %}


</div>