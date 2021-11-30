---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: LED Projects

---

# Barn Quilt

# Updates

<h3 class="category-head">{{ led_project }}</h3>
<a name="{{ led_project | slugize }}"></a>
{% for post in site.categories["led_project"] %}
  <article class="archive-item">
    <h4><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></h4>
  </article>
{% endfor %}