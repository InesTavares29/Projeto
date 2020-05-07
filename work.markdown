---
layout: page
title: Work
permalink: /work/
---

<h1>Case Studies</h1>

<ul>
  {% for casestudies in site.casestudies %}
    <li>
      <h2><a href="{{ casestudies.url }}">{{ casestudies.name }}</a></h2>
      <p>{{ casestudies.content | markdownify }}</p>
    </li>
  {% endfor %}
</ul>
