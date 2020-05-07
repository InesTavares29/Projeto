---
layout: page
title: Case Studies
permalink: /work/
---

<nav>
	<ul>
	  {% for casestudies in site.casestudies %}
	    <li>
	     <a href="{{site.baseurl}}/casestudies/{{casestudies.slug}}">{{casestudies.title}}</a>
	    </li>
	  {% endfor %}
	</ul>
</nav>
