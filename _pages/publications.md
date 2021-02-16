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

- Behrooz Zarebavani, **Foad Jafarinejad**, Matin Hashemi, and Saber Salehkaleybar. "[cuPC: CUDA-based Parallel PC Algorithm for Causal Structure Learning on GPU](https://ieeexplore.ieee.org/document/8823064)." *IEEE transactions on Parallel and Distributed Systems*, 31(3):530–542,  2019. Also, [arXiv 1812.08491](https://arxiv.org/abs/1812.08491)