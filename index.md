---
layout: base
---

{{ site.title }}
================

This is an example of how the [Jekyll Gallery plugin][1] can be used to create
navigable galleries from a set of images. The source that generated this site
can be found on [github][2].

<p id="start">
{% for page in site.gallery_old_first limit:1 %}
<a href="{{ site.base_url }}{{ page.url }}">Start view the gallery!</a>
{% endfor %}
</p>

---

[Peter Dodds](http://pddds.com). All content and source are [MIT license][3].

[1]:https://github.com/m0tive/jekyll-gallery
[2]:https://github.com/m0tive/jekyll-gallery-example
[3]:https://github.com/m0tive/jekyll-gallery-example#license
