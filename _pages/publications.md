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


## PhD Thesis
{% bibliography -f papers -q @phdthesis %}

## Peer-reviewed Articles
{% bibliography -f papers -q @article{note:Peer-reviewed} %}

## Under Review
{% bibliography -f papers -q @article{note:Under review} %}
{% bibliography -f papers -q @unpublished %}

## Conference Papers
{% bibliography -f papers -q @inproceedings %}
{% bibliography -f papers -q @misc{note:Conference presentation} %}
{% bibliography -f papers -q @misc{note:Workshop presentation} %}

