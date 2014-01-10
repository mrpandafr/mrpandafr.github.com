---
layout: page
title: Le blog dev de MrPandaFr
tagline: Un endroit sombre / Such a dark place
---
{% include JB/setup %}

Latest posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

Have fun :)