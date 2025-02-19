---
layout: page
title: "Blog"
permalink: /blog/
---

# Blog Posts

{% for post in site.posts %}
- **[{{ post.title }}]({{ post.url }})** <br>
  📅 {{ post.date | date: "%B %d, %Y" }}  
  {% endfor %}