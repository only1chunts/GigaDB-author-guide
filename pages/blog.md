---
layout: page
title: GigaDB author guide pages
cover-img: /assets/img/header.jpg
---

{% include header.html %}

This page will auto update when new items are added. <!-- to "_posts" folder, I think that should be happening below now.-->


## To find relevant pages use the Search tool by clicking the magnifying glass icon in the top right of this page.


<ui>
  {% for post in site.posts %}
  * <a href="{{ site.url }}/GigaDB-author-guide/{{ post.url }}">{{ post.title }}</a>
        <br>
  {% endfor %}
</ui>

<!--<ui>
  {% for post in site.posts %}
  * {{ post.date | date: "%-d %B %Y" }} - <a href="{{ site.url }}/GigaDB-author-guide/{{ post.url }}">{{ post.title }}</a>
        <br>
  {% endfor %}
</ui>
-->