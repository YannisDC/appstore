---
title: Our Apps
---

Privacy policies and support for our apps. This list updates automatically when you add an app folder.

{% assign app_pages = site.pages | where_exp: "p", "p.app" | sort: "app" %}
{% assign apps = app_pages | group_by: "app" %}
<ul>
{% for app in apps %}
  <li><strong>{{ app.name }}</strong>: {% for p in app.items %}<a href="{{ p.url | relative_url }}">{{ p.title }}</a>{% unless forloop.last %} · {% endunless %}{% endfor %}</li>
{% endfor %}
</ul>
