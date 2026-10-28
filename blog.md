---
layout: default
title: Blog
description: Notes, experiments, and updates.
permalink: /blog/
---

## Posts

{% if site.posts.size > 0 %}
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }}) <span class="post-meta">— {{ post.date | date: "%B %-d, %Y" }}</span>
{% endfor %}
{% else %}
No posts yet.
{% endif %}
