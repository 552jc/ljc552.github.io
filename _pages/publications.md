---
layout: archive
title: "Research Interests"
permalink: /publications/
author_profile: false
---
My research interests broadly lie in the connection between stable homotopy theory and algebraic geometry like chromatic homotopy theory, elliptic cohomology theories, and spectral algebraic geometry. Specifically, I am interested in the (E_infty)orientation from Thom spectra, reinterpretations of chromatic homotopy theory by formal algebraic geometry, and spectral moduli problems.

Notes
======
* [Elliptic cohomology theories and the σ-orientation(unfinished)](https://552jc.github.io/ljc552.github.io/files/sigmaorientation.pdf)
* [The Right Adjunction of Thom spectrum Functor](https://552jc.github.io/ljc552.github.io/files/thomsp.pdf)
* [Notes on elliptic curves and abelian varieties](https://552jc.github.io/ljc552.github.io/files/Ellabvar.pdf)



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
