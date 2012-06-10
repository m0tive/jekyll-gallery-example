---
layout: base
---

{{ site.title }}
================

This is an example of how the [Jekyll Gallery plugin][1] can be used to create
navigable galleries from a set of images. The source that generated this site
can be found on [github][2].

{% for page in site.gallery_old_first limit:1 %}
[Start view the gallery!]({{ site.base_url }}{{ page.url }})
{% endfor %}

---

All content and source are [MIT license][3].
Peter Dodds 2012.

[1]:https://github.com/m0tive/jekyll-gallery
[2]:https://github.com/m0tive/jekyll-gallery-example
[3]:https://github.com/m0tive/jekyll-gallery-example#license
