---
layout: page
title: == yield
tagline: tips, tricks, and rants on software development
---
{% include JB/setup %}

<ul class="posts">
  {% for post in site.posts %}
    <li>
      <h3>
        <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
      </h3>
      <p>{{ post.content }}</p>
      <span class='small'>{{ post.date | date_to_string }}</span>
    </li>
  {% endfor %}
</ul>