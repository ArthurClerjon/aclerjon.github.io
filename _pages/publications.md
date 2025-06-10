---
layout: page
title: publications
permalink: /publications/
nav: true
nav_order: 6
---
[<i class="ai ai-google-scholar"></i> Google Scholar](https://scholar.google.com/...) •  
[<i class="ai ai-orcid"></i> ORCID](https://orcid.org/...) •  
[<i class="ai ai-researchgate"></i> ResearchGate](https://www.researchgate.net/...)

{% include bib_search.liquid %}

{% bibliography %}

## PhD Thesis
{% bibliography --query @phdthesis %}
- 📺 [Watch the PhD thesis defense on YouTube](https://theses.hal.science/tel-03230033)

## Peer-reviewed Articles
{% bibliography --query @article %}

## Under Review
{% bibliography --query @unpublished %}

## Conference Papers
{% bibliography --query @inproceedings %}

## Public Presentations
{% bibliography --query @misc %}
