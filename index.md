---
layout: page
title: Welcome!
tagline: Supporting tagline
---
{% include JB/setup %}

Эй парень, [немножко моих работ]({{ site.url }}/works/) не хочешь?

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
