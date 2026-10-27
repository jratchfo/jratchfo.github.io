---
layout: default
title: Blog
description: Notes, experiments, and updates.
permalink: /blog/
---

<section aria-labelledby="posts-heading">
  <h2 id="posts-heading">Posts</h2>
  {% if site.posts.size > 0 %}
    <ul>
      {% for post in site.posts %}
        <li>
          <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
          <span class="post-meta">— {{ post.date | date: "%B %-d, %Y" }}</span>
        </li>
      {% endfor %}
    </ul>
  {% else %}
    <p>No posts yet.</p>
  {% endif %}
</section>
