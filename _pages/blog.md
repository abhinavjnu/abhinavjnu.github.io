---
title: "Blog"
layout: home
permalink: /blog/
author_profile: true
---

Welcome to my research blog. Here I share thoughts and analysis on platform economy, labour studies, research methods, digital alternatives, and book reviews.

## Categories

- **Platform Economy** - Digital platforms, gig work, market dynamics
- **Labour Studies** - Worker conditions, resistance, unions
- **Research Methods** - Methodology, tools, data analysis
- **Digital Alternatives** - Platform co-ops, community systems
- **Reviews** - Book and paper reviews

Browse by [category](/categories/) or [tag](/tags/), or use the [search](/search/) to find specific topics.

---

## Start here

- **New to my work?** Start with: [Welcome to my Research Blog](/blog/welcome/)
- **Key argument:** [India’s Gig Workers Deserve More Than Flexibility Theatre](/blog/flexibility-theatre/)
- **Theory-focused:** [The Algorithm as Foreman](/blog/algorithm-as-foreman/)
- **Policy response:** [The National Social Security Board Is a Start — But It Won’t Fix What’s Broken](/blog/ssb-response/)

**Subscribe:** [RSS Feed](/feed.xml)

---

## Recent Posts

{% for post in site.posts limit:8 %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%b %d, %Y" }}
{% endfor %}
