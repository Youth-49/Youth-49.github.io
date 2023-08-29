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



## [A novel open-set clustering algorithm](https://www.sciencedirect.com/science/article/pii/S0020025523011465) (co-first author)

Published in Information Sciences, 2023

The paper is about transforming cluster identification into irregular set identification. It is robust to various data distribution, more adaptive to overlapping and Gaussian clustering and more stable under different parameters, while preserves the ability to detect outliers.  It also outperforms other baseline methods in real world datasets in accuracy, running time and parameter sensitivity.