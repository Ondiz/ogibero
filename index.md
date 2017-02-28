---
layout: default
title: Ogibero
navigation_weight: 1 
---

{:.center}
![]({{ site.github.url }}/irudiak/logo.png)

<div class="imageContainer">
{% for post in site.posts limit:5 %}
<a href="{{ site.github.url }}{{ post.url }}" title="{{post.title}}"><img src="{{ post.image| prepend:site.github.url }}" style="height: 280px" align="center" /></a>
{% endfor %}
</div>

Proiektu honi buruz gehiago jakin nahi baduzu sar zaitez
[hemen]({{ site.github.url }}/faq)

<br/>
