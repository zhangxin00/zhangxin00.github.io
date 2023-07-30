---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
- <sub> [2023] **SHISRCNet: Super-resolution And Classification Network For Low-resolution Breast Cancer Histopathology Image** [[paper](https://arxiv.org/pdf/2306.14119.pdf)] <br/>
   Luyuan Xie, Cong	Li, Zirui	Wang, **Xin	Zhang**, Boyan	Chen, Qingni Shen, Zhonghai	Wu. <br/>
   International Conference on Medical Image Computing and Computer Assisted Intervention (CCF B) <br/> 

  

  .
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
