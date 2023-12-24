---
layout: layout.html
---

<h2>Blog</h2>

{% for post in collections.post %}
<h3><a href="{{ post.url }}">{{post.data.title}}</a></h2>
{{post.content}} {% endfor %}
