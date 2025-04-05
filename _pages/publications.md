---
layout: archive
title: "Research Interests"
permalink: /publications/
author_profile: false
---
My research interests broadly lie in the connections among stable homotopy theory, higher algebra and algebraic geometry like chromatic homotopy theory, elliptic cohomology, and spectral algebraic geometry (SAG). Specifically, I am interested in orientations from Thom spectra, rewritings of stable homotopy theory by higher algebra, reformulations of chromatic homotopy theory by SAG, and spectral moduli problems.

Preprints
======
* __Higher algebra in t-structured tensor triangulated $\infty$-categories__ (joint with Xiangrui Shen; in preparation)<br>We observe that many concepts from Lurie's Higher Algebra can be generalized to the setting of t-structured tt-∞-categories, including notions such as flatness, and étale morphisms. Under suitable conditions on a tt-∞-category, we can establish Lazard's theorem, étale rigidity, and the universal property of the derived category, among others.

Talks and slides
======
* [$\infty$-topoi and parametrized homotopy theory](https://552jc.github.io/ljc552.github.io/files/infty_topos.pdf)<br>Graduate Topology Seminar at SUSTech, 2024/6/17
* [Picard $\infty$-groupoids, Picard groups of $E_\infty$-rings and generalized Thom spectra](https://552jc.github.io/ljc552.github.io/files/Picard_ljc.pdf)<br>Graduate Topology Seminar at SUSTech, 2024/4/23 <br> In this talk, we will introduce the Picard $\infty$-groupoids and calculate Picard groups of several $\mathbb{E}_\infty$-rings, like K-theory spectra and topological modular forms. Besides, we also introduce how to generalize the Thom spectrum functor into any presentably symmetric monoidal $\infty$-category, by using the universal property of Picard $\infty$-groupoids.
* [Barr-Beck Theorem, Morita theory and Brauer groups in $\infty$-categories](https://552jc.github.io/ljc552.github.io/files/Morita_theory.pdf)<br>Graduate Topology Seminar at SUSTech, 2024/3/19<br>In this talk, we will introduce the $\infty$-categorical version of the Barr-Beck theorem, Morita theory and Brauer groups.  And we will see that the Brauer group $\operatorname{Br}(\mathbb{S})$ of the sphere spectrum is zero using the spectral sequence involving the etale cohomology by Antieau–Gepner's work in 2012.
* [An overview of $\infty$-categories and higher algebra](https://552jc.github.io/ljc552.github.io/files/Higher_algebra_ljc.pdf)<br>Graduate Topology Seminar at SUSTech, 2023/12/26
* [The σ-orientation and its AHR $\mathbb{E}_{\infty}$-refinement $MString\to tmf$](https://552jc.github.io/ljc552.github.io/files/Orientation.pdf)<br>IWoAT Summer School 2023: Operads, spectra, and multiplicative structures, BIMSA, Beijing, China, 2023/08/17
* [Thom spectra, infinite loop spaces, generalized cocycles, and the $\sigma$-orientation](https://sustech-topology.github.io/grad/23spr/0523-Liang.pdf)<br>Graduate Topology Seminar at SUSTech, 2023/05/23
* [Sites, Sheaves, Formal Groups and Stacks](https://sustech-topology.github.io/grad/22fal/FormalGeometry.pdf)<br>Graduate Topology Seminar at SUSTech, 2022/12/06
* [Elliptic curves and Abelian varieties](https://552jc.github.io/ljc552.github.io/files/Thesis.pdf)<br>Undergraduate topology seminar, Sichuan University, 2022/05/30
* [The Stable homotopy theory and EKMM framework](https://552jc.github.io/ljc552.github.io/files/2021_12_28.pdf)<br>Graduate Topology Seminar at SUSTech, 2021/11/18

Notes
======
<!-- * [Copointedlization and costabilization](https://552jc.github.io/ljc552.github.io/files/Sp_fin.pdf)<br>A concrete model of costabilization -->
* [Elliptic cohomology theories and the $\sigma$-orientation](https://552jc.github.io/ljc552.github.io/files/sigmaorientation.pdf)<br>Ando-Hopkins-Strickland found a special orientation from $MU\langle 6\rangle$ to elliptic cohomology theories, called $\sigma$-orientation. In this note we will give both topological and algebro-geometric settings of $\sigma$-orientation. Furthermore, we will introduce the precise definitions of formal groups, line bundles on a formal group, and particularly the $n$-connective cover of an $E_{\infty}$-space, which seems not well-described in ordinary references.
* [Postnikov-type convergence in $\infty$-categorical framework](https://552jc.github.io/ljc552.github.io/files/convergence.pdf)<br>Lurie introduced an $\infty$-categorical framework for the postnikov tower in a presentable $\infty$-category in his HTT. Here we will generalize it to the case of any ascending sequence of reflective full subcategories in an $\infty$-category.
* [The Right Adjunction of Thom spectrum Functor](https://552jc.github.io/ljc552.github.io/files/thomsp.pdf)<br>A specific description of the right adjoint functor to Thom spectrum functor, which is given by the total space of a fiber bundle with fibers infinite loop spaces.
* [Notes on elliptic curves and abelian varieties](https://552jc.github.io/ljc552.github.io/files/Ellabvar.pdf)<br>This note will provide an introduction to formal groups, elliptic curves and abelian varieties. We first how to get a natural formal group from a smooth group variety. Second we prove that any elliptic curve admits a natural structure of group variety by a technique about relative effective Cartier divisor. After that, we introduce étale-local decomposition and the quotient scheme. In the last chapter we will see that elliptic curves are exactly abelian varieties of $\operatorname{dim}=1$ and that any abelian variety is automatically commutative, smooth and projective. Furthermore we can see that the group structure on an abelian variety is unique under a prescribed unit. 






{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
