---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


{% include base_path %}

Howdy!

I am a PhD student at the Department of Economics of UT Austin.

<!-- Insert my research interest -->

[Curriculum Vitae](https://ryuya-ko.github.io/files/cv_ryuyako.pdf)

Working Papers
------
  <div>{% for post in site.publications reversed %}
    {% include archive-single-cv-no-li.html %}
  {% endfor %}</div>


Work in Progress
------

1. Mergers, Information Spillovers, and Exploratory Investment: Evidence from Texas Shale Drilling
2. Empirical Study of Innovation-for-buyout in Drug Development (with Kosuke Shimamoto)
