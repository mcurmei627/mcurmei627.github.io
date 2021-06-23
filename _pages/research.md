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

<!-- {% assign cyear = 0 %}
{% for post in site.research reversed %}
  {% if post.year > cyear %}
    <h2> {{post.year}} </h2>
    {% assign cyear = post.year %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %} -->


{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}