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
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


Work in Progress
------