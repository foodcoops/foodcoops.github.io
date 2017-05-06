---
layout: archive
permalink: /categories/
title: "Posts by Category"
author_profile: false
sidebar:
  nav: links
---

{% include group-by-array collection=site.posts field="categories" %}

{% for category in group_names %}
  {% assign posts = group_items[forloop.index0] | sort:'date' | reverse %}
  <h2 id="{{ category | slugify }}">
    <i class="fa fa-fw fa-folder-open" aria-hidden="true"></i>
    <span class="page__taxonomy-item">{{ category }}</span>
  </h2>
  <ul>
    {% for post in posts %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}
