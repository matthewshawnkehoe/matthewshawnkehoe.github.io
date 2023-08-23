---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Generally speaking, I am interested in problems related to deep learning, numerical partial differential equations, computational number theory, and computational electromagnetics. As a graduate student, I developed algorithms to solve diffraction problems in periodic media, as well as methods for calculating zeros of the Riemann zeta function.

In recent years, I have become increasingly interested in applying machine learning techniques (especially deep learning) to applied mathematics and industry. I enjoy creating and testing different types of neural networks.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
