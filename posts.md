---
layout: layout.njk
title: Posts
---

# Posts

{% for post in collections.posts %}
- [{{ post.data.title }}]({{ post.url }}) <small>{{ post.date | readableDate }}</small>
{% endfor %}

{% if collections.posts.length == 0 %}
No posts yet. Check back soon!
{% endif %}
