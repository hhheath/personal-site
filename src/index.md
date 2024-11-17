---
title: HB - Heath Blandford
layout: page.njk
---

## Welcome.

You can find what I'm working on _right now_ on my [now page](/now). 

The theme for this website uses the same color palette as [Catppuccin Mocha](https://catppuccin.com/). I just put the colors where I think they fit best. 

### Recent posts:

{% for post in collections.posts reversed %}

[{{post.data.title}}]({{post.url}}) ({{post.date | asPostDate }}) -- {{post.data.teaser}}

{% endfor %}

