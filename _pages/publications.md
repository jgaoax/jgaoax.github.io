---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

Journal
======
1. This is one paper.
2. This is another paper.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
