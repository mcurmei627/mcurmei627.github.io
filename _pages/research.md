---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<!-- {% assign cyear = '0' %}
{% for post in site.research reversed %}
  {% if post.year > cyear %}
    {% assign cyear = post.year %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %} -->


{% include group-by-array collection=site.posts field="year" %}

{% for tag in group_names %}
  {% assign posts = group_items[forloop.index0] %}
  <h2 id="{{ tag | slugify }}" class="archive__subtitle">{{ tag }}</h2>
  {% for post in posts %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}