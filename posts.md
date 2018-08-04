---
layout: default
---

## Posts
{% assign sorted_posts = site.posts | sort:'date' %}
{% for post in sorted_posts %}
  * {{ post.date | date: "%b %d, %Y" }} -- [{{ post.title }}]({{ post.url }})
{% endfor %}
