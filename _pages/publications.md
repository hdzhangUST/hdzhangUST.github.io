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

<span id='publist'>Selected Publications</span>
------
* Chen Zhang<sup>#</sup>, **Haodi Zhang<sup>#*</sup>**, Weiteng Xie, Nan Liu, Kaishun Wu and Lei Chen, Where To: Crowd-Aided Path Selection by Selective Bayesian Network, in _IEEE Transactions on Knowledge and Data Engineering_ (TKDE, early access), 2021
* Chen Zhang<sup>#</sup>, **Haodi Zhang<sup>#*</sup>**, Weiteng Xie, Nan Liu, Qifan Li, Kaishun Wu, Di Jiang, Peiguang Lin and Lei Chen, Cleaning Uncertain Data with Crowdsourcing - a General Model with Diverse Accuracy Rates, in _IEEE Transactions on Knowledge and Data Engineering_ (TKDE, early access), 2021
* Zhidan Liu, Junhong Zheng, Zengyang Gong, **Haodi Zhang<sup>*</sup>** and Kaishun Wu<sup>*</sup>, Exploiting Multi-source Data for Adversarial Driving Style Representation Learning, in _Proceedings of 26th International Conference of DASFAA_, 2021:491-508
* Zihang Gao, Fangzhen Lin, Yi Zhou, Hao Zhang, Kaishun Wu, **Haodi Zhang<sup>*</sup>**, Embedding High-Level Knowledge into DQNs to Learn Faster and More Safely, in _Proceedings of AAAI (short paper)_ 2020:13608-13609
* Yusen Liu, Fangyuan He, **Haodi Zhang**, Guozheng Rao, Zhiyong Feng, Yi Zhou, How Well Do Machines Perform on IQ tests: a Comparison Study on a Large-Scale Dataset, in _Proceedings of IJCAI_ 2019:6110-6116
* **Haodi Zhang**, Yu Wang, Xiangtong Qi, Weiping Xu, Tao Peng, Shucheng Liu, Demo abstract: An intent solver for enabling intent-based SDN, in _Proceedings of INFOCOM (demo paper)_ 2017:968-969
* **Haodi Zhang**, Fangzhen Lin, Characterizing causal action theories and their implementations in answer set programming, in _Artificial Intelligence_ (AIJ) 248:1-8, 2017
* **Haodi Zhang**, Fangzhen Lin, Mapping Action Language BC to Logic Programs: A Characterization by Postulates, in _Proceedings of AAAI_ 2016:1116-1123
* **Haodi Zhang**, Fangzhen Lin, Characterizing Causal Action Theories and Their Implementations in Answer Set Programming: Action Languages B, C, and Beyond, in _Proceedings of IJCAI_ 2015:3285-3291

<br>
Full list of my publications is available on [DBLP](https://dblp.org/pid/165/3321.html)

Grant
------
* PI, _National Natural Science Foundation of China (NSFC)_, RMB 250,000, 2019-2021 (国家自然科学基金青年项目，主持)
* PI, _Finance Commission of Shenzhen Municipality_, RMB 2,700,000, 2019-2021 (深圳市“孔雀计划”海外高层次人才科研基金，主持)
* PI, _Tencent 'Rhinoceros Birds' - Scientific Research Foundation_ for Young Faculty of Shenzhen University, RMB 5,000, 2018-2019 (腾讯“犀牛鸟”-深圳大学青年教师科研基金项目，主持)
* PI, _High-level University Construction Fund_ of Shenzhen University, RMB 140,000, 2019-2020 (深圳市高水平大学建设项目，主持)
* PI, _Natural Science Foundation_ of Shenzhen University, RMB 60,000, 2018-2019 (深圳大学新引进教师科研启动项目，主持)
* Co-PI, _Joint Funds of National Natural Science Foundation of China (NSFC)_, Key Project, RMB 2,600,000, 2021-2024 (国家自然科学基金广东联合重点项目，参与)

<div style='display: none'>
Research Group Members
------
* Current students
  * Qifan Lin, MPhil student, 2019.09~
  * Zhao Chen, MPhil student, 2019.09~
  * Zhenhao Chen, MPhil student, 2019.09~
  * Zhichao Zeng, MPhil student, 2019.09~
  * Chenyu Xu, MPhil student, 2020.09~
  * Wenxi Huang, MPhil student, 2020.09~
* Graduated students
  * Weiteng Xie, MPhil student, 2018.09~2021.06, Huawei 
  * Di Zhan, MPhil student, 2018.09~2021.06, Huawei 
  * Zihang Gao, MPhil student, 2018.09~2021.06, Guangdong second provincal general hospital
  * Hao Ren, MPhil student, 2018.09~2021.06, Guangdong second provincal general hospital


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
</div>