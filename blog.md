---
layout: default
title: Insights & Blog
---

<h2>Latest Posts</h2>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> <br />
      <small>{{ post.date | date: "%B %d, %Y" }}</small>
      <p>{{ post.description }}</p>
    </li>
  {% endfor %}
</ul>
