---
layout: page
title: Contacts!
tagline: Supporting tagline
---
{% include JB/setup %}

Привет. Меня зовут Игорь и я индивидуальный разработчик игр. Я создаю игры, а также занимаюсь фрилансом.

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
