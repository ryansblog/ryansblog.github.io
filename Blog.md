---
layout: page
title: Blog
permalink: /blog
---

{% for tag in site.tags %}
<h3>{{ tag[0] }}</h3>

    {% for post in tag[1] %}
    
    {{ post.date | date: "%B %Y" }} - [{{ post.title }}]({{post.url}}/)
  
    {% endfor %}

{% endfor %}
