---
layout: default
title: OMIBCS
permalink: /
author_twitter: Crbll
---
<h1>Últimas publicaciones</h1>

<ul>
    {% for post in site.posts %}
    <li>
        <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
        <p>{{ post.excerpt }}</p>
    </li>
    {% endfor %}
</ul>