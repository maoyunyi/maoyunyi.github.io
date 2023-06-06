---
layout: page
title: Archive
---
{% for post in site.posts %}
<li>
<a href="{{ site.url }}{{ post.url }}">{{ post.date | date: "%F" }} - {{ post.title }}</a>
</li>
{% endfor %}