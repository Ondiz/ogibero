---
layout: default
title: Errezetak
navigation_weight: 2
---

# Errezetak

<ul class="posts">
  {% for post in site.posts %}
	<li><span>
	{{ post.date | date: "%Yko" }}
	{% assign m = post.date | date: "%-m" %}
	{% case m %}
	  {% when '1' %}urtarrilak
	  {% when '2' %}otsailak
	  {% when '3' %}martxoak
	  {% when '4' %}apirilak
	  {% when '5' %}maiatzak
	  {% when '6' %}ekainak
	  {% when '7' %}uztailak
	  {% when '8' %}abuztuak
	  {% when '9' %}irailak
	  {% when '10' %}urriak
	  {% when '11' %}azaroak
	  {% when '12' %}abenduak
	{% endcase %}
	{{ post.date | date: "%-d" }}
  </span> » <a href="{{ post.url | prepend: site.github.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
