---
layout: page
show_meta: false
title: "Science"
subheadline: "All things science!"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/science/"
---
<ul>
    {% for post in site.categories.science %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
