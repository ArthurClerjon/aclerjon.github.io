---
layout: post
title: Presenting the Sankey work
date: 2023-06-01
description: this is what advanced image components could look like
tags: formatting images
categories: sample-posts
thumbnail: assets/Sankey/Itese_Sankey_Gradient.png
images:
  compare: true
  slider: true
---

This is an example post with advanced image components.

## Image Slider

This is a simple image slider. It uses the [Swiper](https://swiperjs.com/) library. Check the [examples page](https://swiperjs.com/demos) for more information of what you can achieve with it.

<swiper-container keyboard="true" navigation="true" pagination="true" pagination-clickable="true" pagination-dynamic-bullets="true" rewind="true">
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/Sankey/Itese_Sankey_Gradient.png" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/Sankey/Itese_Visual(1).png" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/Sankey/Itese_Visual(2).png" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/Sankey/Itese_Visual(3).png" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/Sankey/Itese_Visual(4).png" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/Sankey/Itese_Visual(5a).png" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/Sankey/Itese_Visual(5b).png" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/Sankey/Itese_Visual(6).png" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/Sankey/Itese_Visual(7a).png" class="img-fluid rounded z-depth-1" %}</swiper-slide>
</swiper-container>

## Image Comparison Slider

This is a simple image comparison slider. It uses the [img-comparison-slider](https://img-comparison-slider.sneas.io/) library. Check the [examples page](https://img-comparison-slider.sneas.io/examples.html) for more information of what you can achieve with it.

<img-comparison-slider>
  {% include figure.liquid path="assets/img/prof_pic.jpg" class="img-fluid rounded z-depth-1" slot="first" %}
  {% include figure.liquid path="assets/img/prof_pic_color.png" class="img-fluid rounded z-depth-1" slot="second" %}
</img-comparison-slider>
