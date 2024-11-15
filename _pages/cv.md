---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education
* PhD in Economics, University College London, 2019
  - Essays in Public Economics.
* MSc in Economics, Trinity College Dublin, 2012
* BA in Economics, Trinity College Dublin, 2011

## Employment
* Trinity College Dublin
  - Assistant Professor in Economics (2023-present)


* Economic and Social Research Institute, Dublin
  - Research Affiliate (2023-present)
  - Research Officer (2018-2023)

* Institute for Fiscal Studies, London
  - Research Associate (2018-present)
  - Research Economist (2012-2018)
  
## Publications
  <ol>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ol>
  
  
## Teaching
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

