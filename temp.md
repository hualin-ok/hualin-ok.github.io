---
layout: default
title: temp
---

{{ content }}
<ul class="myposts">
{% for post in site.posts %}
      <h1>{{ post.title }}</h1>
       <li><a href="{{ post.url }}">{{ post.title}}</a>
    </li>
{% endfor %}
</ul>
