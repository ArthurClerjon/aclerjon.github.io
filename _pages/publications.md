---
layout: page
title: Publications
description: "Liste complète des publications scientifiques d’Arthur Clerjon : énergie, décarbonation, modélisation, climat."
permalink: /publications/
nav: true
nav_order: 3
---

<!-- _pages/publications.md -->

<!-- External Links with Icons -->
<p style="display: flex; flex-wrap: wrap; align-items: center; gap: 0.5rem;">
  <span>Up-to-date publications are also available on:</span>
  <a href="https://scholar.google.fr/citations?user=X0s6r3QAAAAJ&hl=fr" target="_blank">
    <i class="ai ai-google-scholar"></i> Google Scholar
  </a>
  <a href="https://orcid.org/0000-0002-9545-988X" target="_blank">
    <i class="ai ai-orcid"></i> ORCID
  </a>
  <a href="https://www.researchgate.net/profile/Arthur-Clerjon" target="_blank">
    <i class="ai ai-researchgate"></i> ResearchGate
  </a>
  <a href="https://hal.science/search/index/?q=arthur+clerjon" target="_blank">
    <i class="ai ai-hal"></i> HAL
  </a>
</p>

<!-- Bibsearch Feature -->
{% include bib_search.liquid %}

<div class="publications">

<h2>PhD Thesis</h2>
{% bibliography -f papers -q @phdthesis %}

<h2>Peer-reviewed Articles</h2>
{% bibliography -f papers -q @article %}

<h2>Under Review</h2>
{% bibliography -f papers -q @unpublished %}

<h2>Conference Proceedings</h2>
{% bibliography -f papers -q @inproceedings %}

<h2>Presentations</h2>
{% bibliography -f papers -q @misc %}

</div>