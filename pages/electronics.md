---
title: Electronics
layout: page

---

# Updates

<a name="{{ electronics | slugize }}"></a>
{% for post in site.categories["electronics"] %}
  <article class="archive-item">
    <h4><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></h4>
  </article>
{% endfor %}
