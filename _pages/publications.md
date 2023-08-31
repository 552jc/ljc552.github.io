---
layout: archive
title: "Research"
permalink: /publications/
author_profile: false
---
My research interests lie in the connection between stable homotopy theory and algebraic geometry like chromatic homotopy theory, elliptic cohomology theories, and spectral algebraic geometry. Specifically, I'm interested in the (E_infty)orientation from Thom spectra, higher algebra, and spectral moduli problems.

Notes
======
* [The Right Adjunction of Thom spectrum Functor](https://552jc.github.io/ljc552.github.io//publications/files/thomsp.pdf)
* [Notes on elliptic curves and abelian varieties](https://552jc.github.io/ljc552.github.io//publications/files/Ellabvar.pdf)
* [Elliptic cohomology theories and the σ-orientation](https://552jc.github.io/ljc552.github.io//publications/files/sigmaorientation.pdf)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
