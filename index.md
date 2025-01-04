---
layout: default
title: CoreDump
---

# Welcome to My Site

- [About Me](/about/) - Learn more about who I am and what I do.
- [Free and Open Source Software Contributions](/foss/) - Check out my contributions to FOSS projects.

---

## Latest Posts

{% for post in site.posts limit:5 %}
### {{ post.title }}
**Published on** {{ post.date | date: "%B %d, %Y" }}

{{ post.excerpt }}

[Read More]({{ post.url }})

---
{% endfor %}

[View All Posts](/archives/)
