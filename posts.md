---
layout: default
title: Posts
permalink: /posts/
---
# Blog
<ul class="post-list">
{% for post in site.posts %}
  <li>
    <a href="{{ post.url | relative_url }}"><strong>{{ post.title }}</strong></a>
    <div>{{ post.date | date: "%Y-%m-%d" }}</div>
    {% if post.excerpt %}<div>{{ post.excerpt }}</div>{% endif %}
  </li>
{% endfor %}
</ul>
