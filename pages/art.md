---

layout: page
title: Crochet

---

# Updates

<h3 class="category-head">{{ art }}</h3>
<a name="{{ art | slugize }}"></a>
{% for post in site.categories["art"] %}
  <article class="archive-item">
    <h4><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></h4>
  </article>
{% endfor %}