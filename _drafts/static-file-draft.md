---
layout: staticfiles
title:  "pagina staticfiles"
---

texto en **md** tal vez

***


{% for category in site.categories %}
  <h3> categoria [0] {{ category[0] }}</h3>
  <ul>
    {% for post in category[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}