---
layout: page
title: Publications
permalink: /publications/
nav: true
nav_order: 6
---

<!-- _pages/publications.md -->

<!-- External Links with Icons -->
<p>
  Up-to-date publications are also available on:<br>
  <a href="https://scholar.google.fr/citations?user=X0s6r3QAAAAJ&hl=fr" target="_blank">
    <i class="ai ai-google-scholar"></i> Google Scholar
  </a><br>
  <a href="https://orcid.org/0000-0002-9545-988X" target="_blank">
    <i class="ai ai-orcid"></i> ORCID
  </a><br>
  <a href="https://www.researchgate.net/profile/Arthur-Clerjon" target="_blank">
    <i class="ai ai-researchgate"></i> ResearchGate
  </a>
</p>

<!-- Bibsearch Feature -->
{% include bib_search.liquid %}

<div class="publications">

<h2>PhD Thesis</h2>
{% bibliography -f papers -q @phdthesis %}

<h2>Peer-reviewed Articles</h2>
{% bibliography -f papers -q @article{note:Peer-reviewed} %}

<h2>Under Review</h2>
{% bibliography -f papers -q @article{note:Under review} %}
{% bibliography -f papers -q @unpublished %}

<h2>Conference Papers</h2>
{% bibliography -f papers -q @inproceedings %}
{% bibliography -f papers -q @misc{note:Conference presentation} %}
{% bibliography -f papers -q @misc{note:Workshop presentation} %}

</div>