---
layout: page
title: publications
permalink: /publications/
nav: true
nav_order: 6
---
Up-to-date publications are also available on  
[<i class="ai ai-google-scholar"></i> Google Scholar](https://scholar.google.fr/citations?user=X0s6r3QAAAAJ&hl=fr),  
[<i class="ai ai-orcid"></i> ORCID](https://orcid.org/0000-0002-9545-988X), or  
[<i class="ai ai-researchgate"></i> ResearchGate](https://www.researchgate.net/profile/Arthur-Clerjon).


<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">
</div>

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

</div>

</div>