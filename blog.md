---
layout: default
title: Blog
permalink: /blog.html
---

# Blog

{% if site.posts.size == 0 %}
*No posts yet.*
{% endif %}

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url | relative_url }})
<p class="post-meta">{{ post.date | date: "%B %-d, %Y" }}</p>
{{ post.excerpt }}
{% endfor %}
