---
layout: archive
title: "Research Interests"
permalink: /publications/
author_profile: false
---
My research interests broadly lie in the connection between stable homotopy theory and algebraic geometry like chromatic homotopy theory, elliptic cohomology theories, and spectral algebraic geometry. Specifically, I am interested in the (E_∞)orientation from Thom spectra, reformulations of chromatic homotopy theory by formal (spectral) algebraic geometry, and spectral moduli problems.

Notes
======
* [Elliptic cohomology theories and the σ-orientation](https://552jc.github.io/ljc552.github.io/files/sigmaorientation.pdf)<br>Ando-Hopkins-Strickland found a special orientation from Thom spectra to elliptic cohomology theories, called σ-orientation. In this note we will give both topological and algebro-geometric settings of σ-orientation. Furthermore, we will introduce the precise definitions of formal groups, line bundles on a formal group, and particularly the n-connective cover of an E_∞-space, which seems not well-described in ordinary references.
* [Postnikov-type convergence in ∞-categorical framework](https://552jc.github.io/ljc552.github.io/files/convergence.pdf)<br>Lurie introduced an ∞-categorical framework for the postnikov tower in a presentable ∞-category. Here we will generalize it to the case of any ascending sequence of reflective full subcategories in an ∞-category.
* [The Right Adjunction of Thom spectrum Functor](https://552jc.github.io/ljc552.github.io/files/thomsp.pdf)<br>A specific description of the right adjoint functor to Thom spectrum functor, which is given by the total space of a fiber bundle with fibers infinite loop spaces.
* [Notes on elliptic curves and abelian varieties](https://552jc.github.io/ljc552.github.io/files/Ellabvar.pdf)<br>This note will provide an introduction to formal groups, elliptic curves and abelian varieties. We first introduce formal rings and how to get a natural formal group from a smooth group variety. Second we prove that any elliptic curve admits a natural structure of group variety by a technical method of relative effective Cartier divisor. After that, we introduce some basic properties of group scheme, étale-local decomposition of algebraic groups and the quotient scheme by an action of group scheme. In the last chapter we introduce abelian varieties, we will see that elliptic curves are exactly abelian varieties of dim = 1 and that any abelian variety is automatically commutative, smooth and projective. And then we will see that the group structure is unique on an abelian variety given a basepoint. 

Talks
======
* [The σ-orientation and its AHR E_∞-refinement Mstring to tmf](https://552jc.github.io/ljc552.github.io/files/Orientation.pdf)<br>IWoAT Summer School 2023: Operads, spectra, and multiplicative structures,BIMSA, Beijing, China, August 17, 2023
* [Thom spectra, infinite loop spaces, generalized cocycles, and the σ-orientation](https://sustech-topology.github.io/grad/23spr/0523-Liang.pdf)<br>Graduate Topology Seminar at SUSTech, May 23, 2023
* [Sites, Sheaves, Formal Groups and Stacks](https://sustech-topology.github.io/grad/22fal/FormalGeometry.pdf)<br>Graduate Topology Seminar at SUSTech, December 06, 2022
* [Elliptic curves and Abelian varieties](https://552jc.github.io/ljc552.github.io/files/Thesis.pdf)<br>Undergraduate topology seminar, Sichuan University, May 30, 2022
* <strong>Monads, E_∞-spectra and model categories</strong><br>Graduate Topology Seminar at SUSTech, December 01, 2021
* [The Stable homotopy theory and EKMM framework](https://552jc.github.io/ljc552.github.io/files/2021_12_28.pdf)<br>Graduate Topology Seminar at SUSTech, November 18, 2021
* Even earlier, I gave talks on [On Thom Spectra, Orientability, and Cobordism](https://link.springer.com/book/10.1007/978-3-540-77751-9) and more at Undergraduate topology seminar of Sichuan University.




{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
