---
layout: page
title: Windows Defender Application Control & Code Integrity Policies
---

### All WDAC posts

{% for category in site.categories %}
    <h3>{{ tag[0] }}</h3>
    <ul>
        {% for post in tag[1] %}
        <li>
            <a href="{{ post.url }}">{{ post.title }}</a>
        </li>
        {% endfor %}
    </ul>
{% endfor %}
