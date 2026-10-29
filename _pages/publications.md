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

<h2>Manuscripts under review</h2>
<ul>
  <li><b>N. Wang</b>, Y. Li, D. V. Dimarogonas. "Scalable Topology Identification of Large-Scale Directed Networks Under Partial Excitation." Under review at <i>IEEE Transactions on Automatic Control</i>.</li>
  <li><b>N. Wang</b>, D. V. Dimarogonas. "Direct and Filter-Based Topology Estimation for Dynamical Networks Under Partial Excitation." Under review at <i>Automatica</i>.</li>
  <li><b>N. Wang</b>, D. V. Dimarogonas. "Network Identification for Multi-Agent Dynamical Systems under Time-Varying Topologies." Under review at <i>IEEE Transactions on Control of Network Systems</i>.</li>
</ul>

<h2>Published and accepted</h2>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
