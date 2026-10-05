---
permalink: /personal/
title: "Personal"
author_profile: true
---

<ul style="list-style: none; padding-left: 0;">
{% assign items = site.personal | sort: "date" | reverse %}
{% for p in items %}
  <li><a href="{{ p.url }}">{{ p.title }}</a></li>
{% endfor %}
</ul>
