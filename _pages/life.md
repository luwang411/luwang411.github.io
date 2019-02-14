---
layout: archive
title: "Life"
permalink: /life/
author_profile: true
excerpt: "The unicorn just wakes up in the morning<br/><img src='/images/Jinjiaobaobao.pdf'>"
collection: portfolio
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
