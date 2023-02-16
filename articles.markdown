---
title: Articles
date: 2023-02-15 23:09:00 -05:00
page.subtitle: 'boosting your web savvy '
layout: page
---

<h1>Articles</h1>

<ul>
{% for post in site.posts %}
<li>
<strong><a href="{{ post.url }}">{{ post.title }}</a></strong>
</li>
{% endfor %}
</ul>

---

![dotbible 250p.png](/uploads/dotbible%20250p.png)