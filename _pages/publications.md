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

**Finite-sample performance estimator of the maximum likelihood estimator in logistic regression**
Hugo Chardon, Matthieu Lerasle, Jaouad Mourtada.
[paper](https://arxiv.org/pdf/2411.02137v1)