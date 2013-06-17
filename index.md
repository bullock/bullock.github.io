---
layout: page
title: Hello World!
tagline: Supporting tagline
---

活泼的生命完全无须借助魔法，便能对我们述说至美至真的故事。

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

