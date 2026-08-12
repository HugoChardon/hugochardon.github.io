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

[Scholar profile](https://scholar.google.com/citations?user=HmNggn4AAAAJ&hl=fr)

## Preprints

*Beyond Modern Asymptotics for Log-Likelihood Ratios in Logistic Regression*.\
Hugo Chardon, Reese Pathak, Nikita Zhivotovskiy.\
[arXiv](https://arxiv.org/abs/2608.02507) [paper](https://hugochardon.github.io/files/paper-wilks-arxiv.pdf)

*Finite-sample performance of the maximum likelihood estimator in logistic regression*\
Hugo Chardon, Matthieu Lerasle, Jaouad Mourtada.\
*submitted*\
[paper](https://arxiv.org/abs/2411.02137v2), [arxiv](https://arxiv.org/abs/2411.02137).



## Ph.D. dissertation 

*Finite-sample theory for maximum-likelihood estimation in logistic regression*
[manuscript](https://hugochardon.github.io/files/Manuscrit-HC.pdf)
