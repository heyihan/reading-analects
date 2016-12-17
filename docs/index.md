---
title: Welcome
---

Welcome to read _The Analects of Confucius_.

<ul>
    {% for post in site.posts %}
    <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        {{ post.excerpt }}
    </li>
    {% endfor %}
</ul>
