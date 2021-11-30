---

layout: page
title: House

---

# Updates

<h3 class="category-head">{{ house }}</h3>
<a name="{{ house | slugize }}"></a>
{% for post in site.categories["house"] %}
  <article class="archive-item">
    <h4><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></h4>
  </article>
{% endfor %}