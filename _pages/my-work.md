---
title: "My Work"
layout: archive
classes: wide
sitemap: true
permalink: /my-work/
author_profile: true
toc: true
toc_label: "Category"
toc_icon: "gear"
---

<h3 class="archive__subtitle">{{ "My Favorite Projects" }}</h3>

{% if paginator %}
{% assign posts = paginator.posts %}
{% else %}
{% assign posts = site.posts %}
{% endif %}

{% assign entries_layout = page.entries_layout | default: 'grid' %}
<div class="entries-{{ entries_layout }}">
    {% for post in posts %}
    {% if post.categories contains 'work' %}
    {% include archive-single.html type=entries_layout %}
    {% endif %}
    {% endfor %}
</div>


<h3 class="archive__subtitle">{{ "Code Samples" }}</h3>

{% if paginator %}
{% assign posts = paginator.posts %}
{% else %}
{% assign posts = site.posts %}
{% endif %}

{% assign entries_layout = page.entries_layout | default: 'grid' %}
<div class="entries-{{ entries_layout }}">
    {% for post in posts %}
    {% if post.categories contains 'sample' %}
    {% include archive-single.html type=entries_layout %}
    {% endif %}
    {% endfor %}
</div>