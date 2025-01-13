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







## [NPA: Improving Large-scale Graph Neural Networks with Non-parametric Attention](https://dl.acm.org/doi/abs/10.1145/3626246.3653399)

Published in SIGMOD/PODS 2024

The paper designs a plug-and-play non-parametric attention module called NPA to improve the performance of scalable GNNs. The key motivation is 1) consider the feature relationship between node itself and its neighborhood to support better propagation, 2) consider feature relationship between different propagation step in a node-adaptive manner to alleviate over-smoothing. Experiments show that NPA is compatible with most scalable GNN models and enable better performance, deeper architecture and high scalability.





## [A novel open-set clustering algorithm](https://www.sciencedirect.com/science/article/pii/S0020025523011465)

Published in Information Sciences in 2023

The paper is about transforming cluster identification into irregular set identification. The proposed clustering algorithm is robust to various data distribution, more adaptive to overlapping and Gaussian clustering and more stable under different parameters, while preserves the ability to detect outliers. It also outperforms other baseline methods in real world datasets in accuracy, running time and parameter sensitivity.

