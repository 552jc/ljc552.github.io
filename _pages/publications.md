---
layout: archive
title: "Research Interests"
permalink: /publications/
author_profile: false
---
My research interests broadly lie in the connection between stable homotopy theory and algebraic geometry like chromatic homotopy theory, elliptic cohomology theories, and spectral algebraic geometry. Specifically, I am interested in the orientation from Thom spectra, reformulations of chromatic homotopy theory by formal (spectral) algebraic geometry, and spectral moduli problems.

Notes
======
* [Elliptic cohomology theories and the $\sigma$-orientation](https://552jc.github.io/ljc552.github.io/files/sigmaorientation.pdf)<br>Ando-Hopkins-Strickland found a special orientation from $MU\langle 6\rangle$ to elliptic cohomology theories, called $\sigma$-orientation. In this note we will give both topological and algebro-geometric settings of $\sigma$-orientation. Furthermore, we will introduce the precise definitions of formal groups, line bundles on a formal group, and particularly the $n$-connective cover of an $E_{\infty}$-space, which seems not well-described in ordinary references.
* [Postnikov-type convergence in $\infty$-categorical framework](https://552jc.github.io/ljc552.github.io/files/convergence.pdf)<br>Lurie introduced an $\infty$-categorical framework for the postnikov tower in a presentable $\infty$-category in his HTT. Here we will generalize it to the case of any ascending sequence of reflective full subcategories in an $\infty$-category.
* [The Right Adjunction of Thom spectrum Functor](https://552jc.github.io/ljc552.github.io/files/thomsp.pdf)<br>A specific description of the right adjoint functor to Thom spectrum functor, which is given by the total space of a fiber bundle with fibers infinite loop spaces.
* [Notes on elliptic curves and abelian varieties](https://552jc.github.io/ljc552.github.io/files/Ellabvar.pdf)<br>This note will provide an introduction to formal groups, elliptic curves and abelian varieties. We first how to get a natural formal group from a smooth group variety. Second we prove that any elliptic curve admits a natural structure of group variety by a technique about relative effective Cartier divisor. After that, we introduce étale-local decomposition and the quotient scheme. In the last chapter we will see that elliptic curves are exactly abelian varieties of $\operatorname{dim}=1$ and that any abelian variety is automatically commutative, smooth and projective. Furthermore we can see that the group structure on an abelian variety is unique under a prescribed unit. 

Talks
======
* [An overview of $\infty$-category and Higher Algebra](https://552jc.github.io/ljc552.github.io/files/Higher\ algebra\ ljc.pdf)<br>Graduate Topology Seminar at SUSTech, December 26, 2023
* [The σ-orientation and its AHR $E_{\infty}$-refinement $MString\to tmf$](https://552jc.github.io/ljc552.github.io/files/Orientation.pdf)<br>IWoAT Summer School 2023: Operads, spectra, and multiplicative structures, BIMSA, Beijing, China, August 17, 2023
* [Thom spectra, infinite loop spaces, generalized cocycles, and the $\sigma$-orientation](https://sustech-topology.github.io/grad/23spr/0523-Liang.pdf)<br>Graduate Topology Seminar at SUSTech, May 23, 2023
* [Sites, Sheaves, Formal Groups and Stacks](https://sustech-topology.github.io/grad/22fal/FormalGeometry.pdf)<br>Graduate Topology Seminar at SUSTech, December 06, 2022
* [Elliptic curves and Abelian varieties](https://552jc.github.io/ljc552.github.io/files/Thesis.pdf)<br>Undergraduate topology seminar, Sichuan University, May 30, 2022
* <strong>Monads, $E_{\infty}$-spectra and model categories</strong><br>Graduate Topology Seminar at SUSTech, December 01, 2021
* [The Stable homotopy theory and EKMM framework](https://552jc.github.io/ljc552.github.io/files/2021_12_28.pdf)<br>Graduate Topology Seminar at SUSTech, November 18, 2021
* Even earlier, I gave talks on ["On Thom Spectra, Orientability, and Cobordism"](https://link.springer.com/book/10.1007/978-3-540-77751-9) and more at Undergraduate topology seminar of Sichuan University.




{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
