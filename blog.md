---
id: 108
title: Blog
date: 2016-07-28T17:16:07+00:00
author: admin
layout: default
permalink: /blog/
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
