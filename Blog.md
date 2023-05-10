---
layout: page
title: Blog
permalink: /blog/
---

{% for post in site.posts %}
    <ul>
      <li><a href="{{ post.url }}">{{ post.date | date: "%B %Y" }} - {{ post.title }}</a></li>
  </ul>
{% endfor %}
