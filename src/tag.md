---
pagination:
    data: collections
    size: 1
    alias: tag
    addAllPagesToCollections: true
layout: page.njk
permalink: /posts/tag/{{ tag | slugify }}/
eleventyComputed: 
    title: Posts Tagged with "{{ tag }}"
----

{% for post in collections[tag] reversed %}
[{{post.data.title}}]({{post.url}}) - {{post.data.teaser}}
{% endfor %}