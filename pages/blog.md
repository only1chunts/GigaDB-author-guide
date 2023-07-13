---
layout: page
title: GigaDB author guide pages
cover-img: /assets/img/header.jpg
---

This page will auto update when new pages are added.


## To find relevant pages use the Search tool by clicking the magnifying glass icon in the top right of this page.

{% if site.post_search %}
        <li class="nav-item">
          <a class="nav-link" id="nav-search-link" href="#" title="Search">
            <span id="nav-search-icon" class="fa fa-search"></span>
            <span id="nav-search-text">Search</span>
          </a>
        </li>
      {%- endif -%}
{% include search.html %}

<ui>
  {% for post in site.posts %}
  * <a href="{{ site.url }}/GigaDB-author-guide/{{ post.url }}">{{ post.title }}</a>
        <br>
  {% endfor %}
</ui>



<!--<ui> #this would add dates of each post
  {% for post in site.posts %}
  * {{ post.date | date: "%-d %B %Y" }} - <a href="{{ site.url }}/GigaDB-author-guide/{{ post.url }}">{{ post.title }}</a>
        <br>
  {% endfor %}
</ui>
-->