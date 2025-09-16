---
layout: default
title: Blog
nav_order: 8
---

# Blog

{% assign posts = site.posts %}
{% if posts.size == 0 %}
<p>No posts yet.</p>
{% endif %}

<ul class="post-list">
  {% for post in posts %}
  <li class="card" style="margin-bottom: 1rem;">
    <h3 style="margin: 0 0 0.25rem 0;"><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
    <small class="text-grey">{{ post.date | date: "%-d %B %Y" }}</small>
    {% if post.excerpt %}
      <p>{{ post.excerpt | strip_html | truncate: 220 }}</p>
    {% endif %}
  </li>
  {% endfor %}
</ul>
