---
layout: default
title: "Blog de Dialberth Ayala"
---

# Bienvenido a mi Blog

Aquí comparto mi visión sobre negocios, finanzas, desarrollo web y aprendizaje continuo. 

## Últimas Publicaciones

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> — {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>