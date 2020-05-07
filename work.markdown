---
layout: page
title: Case Studies
permalink: /work/
---

<nav>
	<ul>
	  {% for casestudies in site.casestudies %}
	    <li>
	      <h2><a href="{{site.baseurl}}/casestudies/{{casestudies.slug}}">{{casestudies.title}}</a></h2>
	      <p>{{ casestudies.content }}</p>
	    </li>
	  {% endfor %}
	</ul>
</nav>
