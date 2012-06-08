---
---
<p>Jekyll Gallery plugin example site

<p>This site was generated from source located at: <a href="https://github.com/m0tive/jekyll-gallery-example">https://github.com/m0tive/jekyll-gallery-example</a>

{% for page in site.gallery_old_first limit:1 %}
<p><a href="{{ site.base_url }}{{ page.url }}">View Gallery</a>
{% endfor %}
