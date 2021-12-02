---
title:  "News"
layout: archive
permalink: /News/
author_profile: true
comments: true
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
