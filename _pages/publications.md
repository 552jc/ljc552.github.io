---
layout: archive
title: "Research Interests"
permalink: /publications/
author_profile: false
---

<style>
  /* Force the page to use the full width */
  .archive, .page {
    width: 100% !important;
    float: none !important;
    max-width: 1200px !important;
    margin: 0 auto !important;
  }

  /* Hide the sidebar */
  .sidebar {
    display: none !important;
  }

  /* ---------- Publications ---------- */

  .publication {
    margin: 0 0 1.1em 0;
  }

  /* Hide the checkbox, but retain it for the collapse mechanism */
  .publication-toggle {
    position: absolute;
    opacity: 0;
    pointer-events: none;
  }

  .publication-header {
    display: flex;
    align-items: baseline;
    flex-wrap: wrap;
    gap: 0.45em;
    line-height: 1.65;
  }

  /* This is the clickable collapse area */
  .publication-title {
    cursor: pointer;
  }

  .publication-title:hover {
    color: #b31b1b;
  }

  /* Triangle before each publication title */
  .publication-title::before {
    content: "▸ ";
    color: #777;
  }

  .publication-toggle:checked + .publication-header .publication-title::before {
    content: "▾ ";
    color: #b31b1b;
  }

  /* arXiv is a separate link, not part of the clickable collapse label */
  .arxiv-button {
    display: inline-block;
    white-space: nowrap;
    font-size: 0.8em;
    border: 1px solid #b31b1b;
    color: #b31b1b !important;
    padding: 1px 6px;
    border-radius: 4px;
    text-decoration: none !important;
    font-weight: bold;
  }

  .arxiv-button:hover {
    background: #b31b1b;
    color: white !important;
  }

  .publication-description {
    display: none;
    margin: 0.45em 0 0.2em 1.4em;
    line-height: 1.65;
  }

  .publication-toggle:checked ~ .publication-description {
    display: block;
  }

  /* ---------- Writings ---------- */

  details.entry {
    margin: 0 0 1.1em 0;
    padding: 0;
  }

  details.entry summary {
    cursor: pointer;
    line-height: 1.65;
  }

  details.entry summary:hover {
    color: #b31b1b;
  }

  details.entry .entry-content {
    margin: 0.45em 0 0.2em 1.4em;
    line-height: 1.65;
  }

  /* ---------- Talk descriptions ---------- */

  details.talk-description {
    margin: 0.3em 0 1em 1.4em;
  }

  details.talk-description summary {
    cursor: pointer;
    font-size: 0.92em;
    color: #777;
  }

  details.talk-description summary:hover {
    color: #b31b1b;
  }

  details.talk-description .entry-content {
    margin: 0.4em 0 0 0;
    line-height: 1.65;
  }
</style>

My research interests broadly lie in the connections among stable homotopy theory, higher algebra, algebraic geometry and algebraic K-theory.

Currently, I am mainly interested in higher algebra in general prestable categories, dualizable categories, and rewritings of chromatic homotopy theory in a modern way.

Preprints & Publications
======

<div class="publication">
  <input class="publication-toggle" type="checkbox" id="publication-1">
  <div class="publication-header">
    <label class="publication-title" for="publication-1">
      <strong>Generalized Telescope Conjecture</strong>, 2026
    </label>
    <a class="arxiv-button" href="https://arxiv.org/abs/2609.03375">arXiv</a>
  </div>
  <div class="publication-description">
    Introduces the atomic smashing frame to generalize the Balmer Spectrum to any presentably symmetric monoidal $\infty$-category $\mathcal{V}$, and formulates the associated telescope conjecture. Resolves this conjecture in the settings of $\infty$-topoi and connective modules over connective $\mathbb{E}_\infty$-rings, establishes a recollement theorem in the stable setting, and introduces the Serre smashing frame.
  </div>
</div>

<div class="publication">
  <input class="publication-toggle" type="checkbox" id="publication-2">
  <div class="publication-header">
    <label class="publication-title" for="publication-2">
      <strong>Dualizable Additive Categories</strong>, 2026, joint with
      <a href="https://ishanina.github.io/">Ishan Levy</a>
      and
      <a href="https://vova-sosnilo.com/index.html">Vova Sosnilo</a>
    </label>
    <a class="arxiv-button" href="https://arxiv.org/abs/2608.04898">arXiv</a>
  </div>
  <div class="publication-description">
    Characterizes dualizable additive $\infty$-categories as separated Grothendieck prestable $\infty$-categories satisfying $\mathrm{AB4}^*$ and $\mathrm{AB6}$, identifies them with connective almost modules over almost connective $\mathbb{E}_{1}$-rings. Characterizes connective nuclear modules $\mathrm{Nuc}(R)_{\ge 0}$ in the sense of Clausen--Scholze as the additive rigidification of $\mathrm{Mod}_{R,\geq 0}^{\mathrm{cpl}}$. Also introduces prestable motives.
  </div>
</div>

<div class="publication">
  <input class="publication-toggle" type="checkbox" id="publication-3">
  <div class="publication-header">
    <label class="publication-title" for="publication-3">
      <strong>Smashing, Balmer, Zariski spectra: an ideal approach</strong>, 2026, joint with
      <a href="https://people.ucsc.edu/~czou3/">Changhan Zou</a>
    </label>
    <a class="arxiv-button" href="https://arxiv.org/abs/2607.13329">arXiv</a>
  </div>
  <div class="publication-description">
    We introduce a general Zariski frame functor to unify Zariski, Balmer and smashing spectrum. We introduce the notion of $\Sigma$-triviality for a pointed $\infty$-category, which allows the quotient by an ideal in it. We show that the $\Sigma$-trivialization of the $\infty$-category of spaces is a mode.
  </div>
</div>

<div class="publication">
  <input class="publication-toggle" type="checkbox" id="publication-4">
  <div class="publication-header">
    <label class="publication-title" for="publication-4">
      <strong>Higher algebra in $t$-structured tensor triangulated $\infty$-categories</strong>, 2026; to appear in <i>Selecta Mathematica</i>.
    </label>
    <a class="arxiv-button" href="https://arxiv.org/abs/2603.27786">arXiv</a>
  </div>
  <div class="publication-description">
    Extends higher algebra concepts (finitely presented, flat, and étale morphisms) to $t$-structured tensor triangulated $\infty$-categories. Under “projective rigidity”—a condition shown to hold for spectra, filtered/graded spectra, genuine $G$-spectra, and Artin–Tate motivic spectra—we establish analogues of Lazard’s theorem, étale rigidity, and the universal property of the derived category.
  </div>
</div>

Talks and slides
======

* [$\infty$-topoi and parametrized homotopy theory](https://552jc.github.io/ljc552.github.io/files/infty_topos.pdf)<br>
  Graduate Topology Seminar at SUSTech, 2024/6/17

* [Picard $\infty$-groupoids, Picard groups of $E_\infty$-rings and generalized Thom spectra](https://552jc.github.io/ljc552.github.io/files/Picard_ljc.pdf)<br>
  Graduate Topology Seminar at SUSTech, 2024/4/23

* [Barr-Beck Theorem, Morita theory and Brauer groups in $\infty$-categories](https://552jc.github.io/ljc552.github.io/files/Morita_theory.pdf)<br>
  Graduate Topology Seminar at SUSTech, 2024/3/19

* [An overview of $\infty$-categories and higher algebra](https://552jc.github.io/ljc552.github.io/files/Higher_algebra_ljc.pdf)<br>
  Graduate Topology Seminar at SUSTech, 2023/12/26

* [The σ-orientation and its AHR $\mathbb{E}_{\infty}$-refinement $MString\to tmf$](https://552jc.github.io/ljc552.github.io/files/Orientation.pdf)<br>
  IWoAT Summer School 2023: Operads, spectra, and multiplicative structures, BIMSA, Beijing, China, 2023/08/17

* [Thom spectra, infinite loop spaces, generalized cocycles, and the $\sigma$-orientation](https://sustech-topology.github.io/grad/23spr/0523-Liang.pdf)<br>
  Graduate Topology Seminar at SUSTech, 2023/05/23

* [Sites, Sheaves, Formal Groups and Stacks](https://sustech-topology.github.io/grad/22fal/FormalGeometry.pdf)<br>
  Graduate Topology Seminar at SUSTech, 2022/12/06

* [Elliptic curves and Abelian varieties](https://552jc.github.io/ljc552.github.io/files/Thesis.pdf)<br>
  Undergraduate topology seminar, Sichuan University, 2022/05/30

* [The Stable homotopy theory and EKMM framework](https://552jc.github.io/ljc552.github.io/files/2021_12_28.pdf)<br>
  Graduate Topology Seminar at SUSTech, 2021/11/18

Writings
======

<!--
<details class="entry">
  <summary>
    <a href="https://552jc.github.io/ljc552.github.io/files/Sp_fin.pdf">Copointedlization and costabilization</a>
  </summary>
  <div class="entry-content">
    A concrete model of costabilization.
  </div>
</details>
-->

<details class="entry">
  <summary>
    <a href="https://552jc.github.io/ljc552.github.io/files/sigmaorientation.pdf">Elliptic cohomology theories and the $\sigma$-orientation</a>
  </summary>
  <div class="entry-content">
    Ando-Hopkins-Strickland found a special orientation from $MU\langle 6\rangle$ to elliptic cohomology theories, called $\sigma$-orientation. In this note we will give both topological and algebro-geometric settings of $\sigma$-orientation. Furthermore, we will introduce the precise definitions of formal groups, line bundles on a formal group, and particularly the $n$-connective cover of an $E_{\infty}$-space, which seems not well-described in ordinary references.
  </div>
</details>

<details class="entry">
  <summary>
    <a href="https://552jc.github.io/ljc552.github.io/files/thomsp.pdf">The Right Adjunction of Thom spectrum Functor</a>
  </summary>
  <div class="entry-content">
    A specific description of the right adjoint functor to Thom spectrum functor, which is given by the total space of a fiber bundle with fibers infinite loop spaces.
  </div>
</details>

<details class="entry">
  <summary>
    <a href="https://552jc.github.io/ljc552.github.io/files/Ellabvar.pdf">Notes on elliptic curves and abelian varieties</a>
  </summary>
  <div class="entry-content">
    This note will provide an introduction to formal groups, elliptic curves and abelian varieties. We first how to get a natural formal group from a smooth group variety. Second we prove that any elliptic curve admits a natural structure of group variety by a technique about relative effective Cartier divisor. After that, we introduce étale-local decomposition and the quotient scheme. In the last chapter we will see that elliptic curves are exactly abelian varieties of $\operatorname{dim}=1$ and that any abelian variety is automatically commutative, smooth and projective. Furthermore we can see that the group structure on an abelian variety is unique under a prescribed unit.
  </div>
</details>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a></u>.
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
