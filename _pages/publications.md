---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---


> Do not go gentle into that good night.<br>
Rage, rage against the dying of the light. ---<cite>Dylan Thomas</cite>

Research Interests
------
* Knowledge embedding in reinforcement learning for
  * Game playing
  * Dialog policy learning
  * Communication policy learning
* Interpretable AI models for
  * Diagnosis
  * Dialog management
* Intelligence measurements
* Crowdingsourcing for
  * Uncertain data cleaning
  * Path selection

Publications
------
Full list of my publications is available on [DBLP](https://dblp.org/pid/165/3321.html)

Research Group Members
------
* Current students
  * Weiteng Xie, MPhil student, 2018.09~
  * Di Zhan, MPhil student, 2018.09~
  * Zihang Gao, MPhil student, 2018.09~
  * Hao Ren, MPhil student, 2018.09~
  * Qifan Lin, MPhil student, 2019.09~
  * Zhao Chen, MPhil student, 2019.09~
  * Zhenhao Chen, MPhil student, 2019.09~
  * Zhichao Zeng, MPhil student, 2019.09~
  * Chenyu Xu, MPhil student, 2020.09~
  * Wenxi Huang, MPhil student, 2020.09~

<div style='display: none'>
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
</div>