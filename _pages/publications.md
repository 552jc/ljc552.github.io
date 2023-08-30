---
layout: archive
title: "Notes"
permalink: /publications/
author_profile: false
---
[Notes on elliptic curves and abelian varieties](https://552jc.github.io/ljc552.github.io//publications/files/Ellabvar.pdf)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
