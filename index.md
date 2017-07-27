---
layout: default
title: Ogibero
navigation_weight: 1 
---

![]({{ site.github.url }}/irudiak/logo.png){:.logo}

<div class="imageContainer">
{% for post in site.posts limit:20 %}
<a href="{{ site.github.url }}{{ post.url }}" title="{{post.title}}"><img src="{{ post.image| prepend:site.github.url }}" class="preview-image" align="center" /></a>
{% endfor %}
</div>

Proiektu honi buruz gehiago jakin nahi baduzu sar zaitez
[hemen]({{ site.github.url }}/faq)

<br/>

<!-- Local Variables: -->
<!-- ispell-local-dictionary: "euskera"-->
<!-- End: -->
