---
permalink: /personal/
title: "Personal"
author_profile: true
---

<ul style="list-style: none; padding-left: 0;">
{% assign items = site.resources | sort: "date" | reverse %}
{% for p in items %}
  <li><a href="{{ p.url }}">{{ p.title }}</a></li>
{% endfor %}
</ul>

Under construction!
