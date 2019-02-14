---
layout: archive
title: "Life"
permalink: /life/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Daily life

* Morning: watching my female hoster sleep
* Daytime: sitting on the bed with the bear, sometimes get chance to have a sleep
* Nighttime: watch my hoster couple sleep, sometimes have a meeting with my team members

