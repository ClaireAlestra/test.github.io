---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Publications

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Working Papers

{% for post in site.WP reversed %}
  {% include archive-single.html %}
{% endfor %}

## Work in Progress

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
