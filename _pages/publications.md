---
layout: archive
title: "Research Interests"
permalink: /publications/
author_profile: false
---
My research interests broadly lie in the connection between stable homotopy theory and algebraic geometry like chromatic homotopy theory, elliptic cohomology theories, and spectral algebraic geometry. Specifically, I am interested in the (E_∞)orientation from Thom spectra, reformulations of chromatic homotopy theory by formal (spectral) algebraic geometry, and spectral moduli problems.

Notes
======
* [Elliptic cohomology theories and the σ-orientation](https://552jc.github.io/ljc552.github.io/files/sigmaorientation.pdf)
* [Postnikov-type convergence in ∞-categorical framework](https://552jc.github.io/ljc552.github.io/files/convergence.pdf)
* [The Right Adjunction of Thom spectrum Functor](https://552jc.github.io/ljc552.github.io/files/thomsp.pdf)
* [Notes on elliptic curves and abelian varieties](https://552jc.github.io/ljc552.github.io/files/Ellabvar.pdf)

Talks
======
* [The σ-orientation and its AHR E_∞-refinement Mstring to tmf](https://552jc.github.io/ljc552.github.io/files/Orientation.pdf)<br>
IWoAT Summer School 2023: Operads, spectra, and multiplicative structures,BIMSA, Beijing, China, 2023-8-17
* [Thom spectra, infinite loop spaces, generalized cocycles, and the σ-orientation](https://sustech-topology.github.io/grad/23spr/0523-Liang.pdf)




{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
