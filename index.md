---
layout: base
---

{{ site.title }}
================

This is an example of how the [Jekyll Gallery plugin][1] can be used to create
navigable galleries from a set of images. The source that generated this site
can be found on [github][2].

{% for page in site.gallery_old_first limit:1 %}
[View Gallery]({{ site.base_url }}{{ page.url }})
{% endfor %}

[1]:https://github.com/m0tive/jekyll-gallery
[2]:https://github.com/m0tive/jekyll-gallery-example
