---
title: HB - Heath Blandford
layout: page.njk
---

## Welcome.

This is a place for me to write sweet nothings about the things that I find important right now. 

You can find what I'm working on _right now_ on my [now page](/now). 

### Recent posts:

{% for post in collections.posts reversed %}

[{{post.data.title}}]({{post.url}}) - {{post.data.teaser}}

{% endfor %}
