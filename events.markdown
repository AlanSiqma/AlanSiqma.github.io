---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title: Eventos
layout: default
permalink: /events/
---




<ul class="post-meta">
{% for event in site.events %}
    <li>
        <span class="post-meta">{{ event.date }}</span>
        <h3>
            <a class="post-link" href="{{event.url}}">
            {{ event.title }}
            </a>
        </h3>
    </li> 
 {% endfor %}
</ul>