---
title: Electronics
layout: page

---

## Code and Electronics Projects

- [Classroom Sound Meter](https://github.com/baileysage/ClassroomSoundMeter)
- [Lunch Club Mailer](https://github.com/baileysage/LunchClubMailer)

## Updates

<a name="{{ electronics | slugize }}"></a>
{% for post in site.categories["electronics"] %}
  <article class="archive-item">
    <h4><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></h4>
  </article>
{% endfor %}
