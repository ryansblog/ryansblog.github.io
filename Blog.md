---
layout: page
title: Blog
permalink: /blog
---

a word
{% for post in site.posts %}
    
{{ post.date | date: "%B %Y" }} - {{ post.title }}
  
{% endfor %}
