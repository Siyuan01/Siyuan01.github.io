---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

* $\color{red}{[Dblp]}$ Limin Wang, Peng Chen, Musa Mammadov, Yang Liu, **Si-Yuan Wu**. [Alleviating the independence assumptions of averaged one-dependence estimators by model weighting.](https://content.iospress.com/articles/intelligent-data-analysis/ida205400) Intelligent Data Analysis, vol. 25, no. 6, pp. 1431-1451, 2021

<!-- 

* $\color{red}{[INFOCOM]}$ **Nan Yu**, Haipeng Dai, Alex X. Liu and Bingchuan Tian. [Placement of Connected Wireless 
Chargers.](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8485934) In Proceedings of the 37th Annual IEEE International Conference on Computer Communications (INFOCOM), Honolulu, HI, USA, April 15-19, 2018. Acceptance rate: 309/1606 = 19.2%.
* $\color{red}{[Ubicomp]}$ **Nan Yu**, Wei Wang, Alex X. Liu and Lingtao Kong. [QGesture: Quantifying Gesture Distance and Direction with WiFi Signals.](https://dl.acm.org/citation.cfm?id=3191783) In Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies (UbiCOMP), Volume 2 ,Issue 1, Article No. 51, March 2018.
* $\color{red}{[Springer]}$ Haipeng Dai, **Nan Yu**, Alex X. Liu, Bingchuan Tian and Chen, Guihai. [Wireless Charger Deployment with Communication Constraint.](https://link.springer.com/content/pdf/10.1007%2F978-3-319-32903-1_271-1.pdf) In Proceedings of book Encyclopedia of Wireless Networks, Springer International Publishing.
* $\color{red}{[TMC]}$ Xiaoyu Wang, Haipeng Dai, Wang Weijun, Jiaqi Zheng, **Nan Yu**, Guihai Chen, Wanchun Dou, Xiaobing Wu. [Practical Heterogeneous Wireless Charger Placement with Obstacles.](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8714083) IEEE Transactions on Mobile Computing (TMC), 2019. TBD -->
