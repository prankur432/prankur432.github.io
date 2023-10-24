---
layout: archive
title: "Research"
permalink: /research/
---

{% assign author = site.author %}

{% if author.googlescholar %}
  You can also find my articles on <a href="{{author.googlescholar}}" target="_blank" rel="noopener noreferrer">my Google Scholar profile</a>.
{% else %}
  This is my research page
{% endif %}

{% include base_path %}

{% include publications.html %}