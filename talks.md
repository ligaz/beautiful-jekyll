---
layout: page
title: Talks
subtitle: Me on stage
---

I have done numerous talks at conferences and universities during the years. Here is a list of them:

<ul>
{% for talk in site.data.talks %}
  <li>
    <a href="{{ talk.url }}">{{ talk.name }}</a> ({{ talk.event }}, {{ talk.date }})
  </li>
{% endfor %}
</ul>
