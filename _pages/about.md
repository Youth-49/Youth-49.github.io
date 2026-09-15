---
permalink: /
title: "About Me"
excerpt: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% include base_path %}
{% assign author = site.author %}

<div class="home-page" markdown="1">

<div class="home-intro">
  <p class="home-intro__eyebrow">Ph.D. Student · Peking University</p>
  <p class="home-intro__lead">I'm a <strong>fourth-year Ph.D. student</strong> at Peking University (School of Computer Science). Previously, I received an Honors Degree in Computer Science from Beijing Institute of Technology.</p>
  <div class="home-intro__focus" aria-label="Research interests">
    <span>LLM Agents</span>
    <span>Federated Learning</span>
  </div>
  <p class="home-intro__note">Feel free to contact me if you'd like to discuss ideas or collaborate.</p>
  <div class="home-intro__actions">
    <a class="btn btn--info btn--small" href="mailto:{{ author.email }}"><i class="fas fa-fw fa-envelope" aria-hidden="true"></i> Email</a>
    {% if author.googlescholar %}<a class="btn btn--inverse btn--small" href="{{ author.googlescholar }}"><i class="fas fa-fw fa-graduation-cap" aria-hidden="true"></i> Scholar</a>{% endif %}
    {% if author.github %}<a class="btn btn--inverse btn--small" href="https://github.com/{{ author.github }}"><i class="fab fa-fw fa-github" aria-hidden="true"></i> GitHub</a>{% endif %}
    <a class="btn btn--inverse btn--small" href="/publications/"><i class="fas fa-fw fa-book" aria-hidden="true"></i> Publications</a>
  </div>
</div>

## Education
- **2023/09 - present**: Peking University, School of Computer Science
- **2019/09 - 2023/06**: Beijing Institute of Technology, XuTeLi School, Computer Science

## Publications
\* indicates equal contribution
{: .notice--info}

<div class="publication-card" markdown="1">

### Exploring Information Seeking Agent Consolidation (EMNLP 2026 Findings)
**Guochen Yan\***, Jialong Wu\*, Zhengwei Tao, Bo Li, Qintong Zhang, Jiahao Xu, Haitao Mi, Yuejian Fang, Qingni Shen, Wentao Zhang, Zhonghai Wu<br />
[Paper](https://arxiv.org/abs/2602.00585){: .btn .btn--primary .btn--small}

</div>

<div class="publication-card" markdown="1">

### FedSRD: Sparsify-Reconstruct-Decompose for Communication-Efficient Federated Large Language Models Fine-Tuning (WWW 2026 Oral)
**Guochen Yan**, Luyuan Xie, Qingni Shen, Yuejian Fang, Zhonghai Wu  
[Paper](https://arxiv.org/abs/2510.04601){: .btn .btn--primary .btn--small} [Code](https://github.com/Youth-49/FedSRD_2025){: .btn .btn--inverse .btn--small}

</div>

<div class="publication-card" markdown="1">

### dFLMoE: Decentralized Federated Learning via Mixture of Experts for Medical Data Analysis (CVPR 2025)
Luyuan Xie, Tianyu Luan, Wenyuan Cai, **Guochen Yan**, Zhaoyu Chen, Nan Xi, Yuejian Fang, Qingni Shen, Zhonghai Wu, Junsong Yuan  
[Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Xie_dFLMoE_Decentralized_Federated_Learning_via_Mixture_of_Experts_for_Medical_Data_Analysis_CVPR_2025_paper.html){: .btn .btn--primary .btn--small}

</div>

<div class="publication-card" markdown="1">

### OpenFGL: A Comprehensive Benchmark for Federated Graph Learning (VLDB 2025)
Xunkai Li, Yinlin Zhu, Boyang Pang, **Guochen Yan**, Yeyu Yan, Zening Li, Zhengyu Wu, Wentao Zhang, Rong-Hua Li, Guoren Wang  
[Paper](https://arxiv.org/abs/2408.16288){: .btn .btn--primary .btn--small} [Code](https://github.com/xkLi-Allen/OpenFGL){: .btn .btn--inverse .btn--small}

</div>

<div class="publication-card" markdown="1">

### FedVCK: Non-IID Robust and Communication-Efficient Federated Learning via Valuable Condensed Knowledge for Medical Image Analysis (AAAI 2025)
**Guochen Yan**, Luyuan Xie, Xinyi Gao, Wentao Zhang, Qingni Shen, Yuejian Fang, Zhonghai Wu  
[Paper](https://arxiv.org/abs/2412.18557){: .btn .btn--primary .btn--small} [Code](https://github.com/Youth-49/FedVCK_2024){: .btn .btn--inverse .btn--small}

</div>

<div class="publication-card" markdown="1">

### NPA: Improving Large-scale Graph Neural Networks with Non-parametric Attention (SIGMOD 2024)
Wentao Zhang\*, **Guochen Yan\***, Yu Shen, Yang Ling, Yangyu Tao, Bin Cui, Jian Tang  
[Paper](https://dl.acm.org/doi/abs/10.1145/3626246.3653399){: .btn .btn--primary .btn--small} [Code](https://github.com/Youth-49/NPA){: .btn .btn--inverse .btn--small}

</div>

<div class="publication-card" markdown="1">

### A novel open-set clustering algorithm (Information Sciences 2023)
Qi Li\*, **Guochen Yan\***, Shuliang Wang, Boxiang Zhao  
[Paper](https://www.sciencedirect.com/science/article/pii/S0020025523011465){: .btn .btn--primary .btn--small} [Code](https://github.com/Youth-49/2023-DOS-IN){: .btn .btn--inverse .btn--small}

</div>

## Research
- Research intern in PKU-DAIR Lab (Supervisor: Dr. Wentao Zhang and Prof. Bin Cui, Peking University), 2023 - Now
  - Direction: Data-centric Large Language Models
- Research intern in PKU-DAIR Lab (Supervisor: Dr. Wentao Zhang and Prof. Bin Cui, Peking University), 2022 - 2023
  - Direction: Scalable Graph Neural Networks
- Mitacs research intern in Database System Lab (Supervisor: Prof. Jiannan Wang, Simon Fraser University), 2022/08 - 2022/11
  - Direction: Data provenance tracking system
- Research intern on clustering algorithm (Supervisor: Dr. Qi Li and Prof. Shuliang Wang, Beijing Institute of Technology), 2021/09 - 2022/05
  - Direction: Robust and efficient clustering, outliers detection

## Awards
- National Scholarship, 2020
- Excellent Graduates, 2023
- Multiple Academic Scholarship during 2020-2022
- Excellent Student during 2020-2022

## Skills
- Programming language: Python, C/C++
- Framework: Pytorch, PyG, transformers, trl, swift-megatron
- Tools: Git, LaTeX, Slurm

</div>
