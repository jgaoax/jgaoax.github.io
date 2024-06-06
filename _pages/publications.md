---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

***

{% include base_path %}

Journal
======
1. Gao, J., & Li, S. (2024). Regulating for-hire autonomous vehicles for an equitable multimodal transportation network. Transportation Research Part B: Methodological, 183, 102925.
2. Ao, D., Gao, J., Lai, Z., & Li, S. (2024). Regulating transportation network companies with a mixture of autonomous vehicles and for-hire human drivers. Transportation research part A: policy and practice, 180, 103975.

Conference Proccedings
======
1. This is one conference.
2. This is another conference.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
