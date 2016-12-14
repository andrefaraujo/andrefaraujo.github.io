---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

t1
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
  t3
{% endif %}
t2

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
