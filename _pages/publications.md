---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}
{% assign author = site.author %}

\* indicates equal contribution
{: .notice--info}

{% if author.googlescholar %}
[Google Scholar]({{ author.googlescholar }}){: .btn .btn--primary .btn--small}
{% endif %}

## Selected publications

### FedSRD: Sparsify-Reconstruct-Decompose for Communication-Efficient Federated Large Language Models Fine-Tuning (WWW 2026)
**Guochen Yan**, Luyuan Xie, Qingni Shen, Yuejian Fang, Zhonghai Wu  
[ACM](https://dl.acm.org/doi/10.1145/3774904.3792144){: .btn .btn--primary .btn--small} [arXiv](https://arxiv.org/abs/2510.04601){: .btn .btn--inverse .btn--small} [Code](https://github.com/Youth-49/FedSRD_2025){: .btn .btn--inverse .btn--small}

FedSRD (Sparsify-Reconstruct-Decompose) improves communication-efficient federated fine-tuning for LLMs by pruning client updates with an importance-aware strategy, reconstructing in full-rank space for robust aggregation under non-IID data, then decomposing back to sparse low-rank updates for broadcast.
{: .notice}

### FedVCK: Non-IID Robust and Communication-Efficient Federated Learning via Valuable Condensed Knowledge for Medical Image Analysis (AAAI 2025)
**Guochen Yan**, Luyuan Xie, Xinyi Gao, Wentao Zhang, Qingni Shen, Yuejian Fang, Zhonghai Wu  
[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/35497){: .btn .btn--primary .btn--small} [arXiv](https://arxiv.org/abs/2412.18557){: .btn .btn--inverse .btn--small} [Code](https://github.com/Youth-49/FedVCK_2024){: .btn .btn--inverse .btn--small}

FedVCK aggregates condensed knowledge distilled from each client’s local dataset. It enforces latent distribution constraints and uses hard-sample selection to improve robustness and communication efficiency under severe non-IID settings.
{: .notice}

### NPA: Improving Large-scale Graph Neural Networks with Non-parametric Attention (SIGMOD/PODS 2024)
Wentao Zhang\*, **Guochen Yan\***, Yu Shen, Yang Ling, Yangyu Tao, Bin Cui, Jian Tang  
[ACM](https://dl.acm.org/doi/abs/10.1145/3626246.3653399){: .btn .btn--primary .btn--small} [Code](https://github.com/Youth-49/NPA){: .btn .btn--inverse .btn--small}

NPA is a plug-and-play non-parametric attention module for scalable GNNs. It models feature relations within neighborhoods and across propagation steps to support better propagation and mitigate over-smoothing.
{: .notice}

### A novel open-set clustering algorithm (Information Sciences 2023)
Qi Li\*, **Guochen Yan\***, Shuliang Wang, Boxiang Zhao  
[ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0020025523011465){: .btn .btn--primary .btn--small} [Code](https://github.com/Youth-49/2023-DOS-IN){: .btn .btn--inverse .btn--small}

This work transforms cluster identification into irregular set identification. The algorithm is robust across data distributions, adapts to overlapping and Gaussian clustering, detects outliers, and performs strongly on real-world datasets.
{: .notice}

{% if site.publications and site.publications.size > 0 %}
## Full list

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
{% endif %}

