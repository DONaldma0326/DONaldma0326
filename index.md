---
layout: home
author_profile: true
---

# Welcome to my space!

I'm Don Ma. This is my digital notebook where I document my journey through data engineering, MLOps, and the evolving landscape of AI.

## Latest Posts

{% for post in site.posts limit: 2 %}
### [{{ post.title }}]({{ post.url | relative_url }})
<p class="archive__item-excerpt">{{ post.excerpt | strip_html | truncatewords: 20 }}</p>
<p><a href="{{ post.url | relative_url }}" class="btn btn--primary btn--small">Read More</a></p>
{% endfor %}

[View all posts](/posts/)
---

### Quick Links
- [View my projects on GitHub](https://github.com/DONaldma0326)
- [LinkedIn](www.linkedin.com/in/don-ma-b478a9180)