---
layout: home
title: "Blog"
permalink: /blog/
author_profile: true
---

Here you'll find updates on my technical journey — building projects, learning new tools, and exploring artificial intelligence.

---

{% for post in site.posts %}

## [{{ post.title }}]({{ post.url }})

### {{ post.date | date: "%B %d, %Y" }}

{{ post.excerpt }}

---
{% endfor %}
