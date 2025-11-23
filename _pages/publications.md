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

## Preprints

**Finite-sample performance of the maximum likelihood estimator in logistic regression**  
Hugo Chardon, Matthieu Lerasle, Jaouad Mourtada.  
[paper](https://arxiv.org/abs/2411.02137v2)


##Ph.D. dissertation *Finite-sample theory for maximum-likelihood estimation in logistic regression* [manuscript](https://hugochardon.github.io/files/Manuscrit-HC.pdf)
