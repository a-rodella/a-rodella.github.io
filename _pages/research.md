---
layout: page
permalink: /research/
title: research
description: research areas and ongoing directions
nav: true
nav_order: 3
---

<div id="top"></div>

I work at the intersection of **computational mechanics** and **variational methods**, with a focus on **fracture, fatigue, plasticity**, and **micro-structured/fibrous materials**.

---

## research areas

<div class="row">

  <!-- 1) Gradient plasticity -->
  <div class="col-12 col-md-6 col-lg-4 mb-4">
    <div class="card h-100 shadow-sm">
      <div class="card-body">
        <h5 class="card-title mb-2">Gradient plasticity & anisotropic shear bands</h5>
        <p class="card-text">
          A variational curl-plasticity model with a <strong>one-homogeneous defect energy</strong>,
          enabling <strong>sharp localization</strong> and geometry-dependent yielding, with anisotropy steering band orientation.
        </p>
        <div class="mb-2">
          <span class="badge badge-pill badge-light">curl plasticity</span>
          <span class="badge badge-pill badge-light">one-homogeneous energy</span>
          <span class="badge badge-pill badge-light">anisotropy</span>
          <span class="badge badge-pill badge-light">shear bands</span>
        </div>
        <div class="text-muted small">Read more →</div>
        <a href="#gradient-plasticity" class="stretched-link" aria-label="Gradient plasticity details"></a>
      </div>
    </div>
  </div>

  <!-- 2) Cohesive fracture -->
  <div class="col-12 col-md-6 col-lg-4 mb-4">
    <div class="card h-100 shadow-sm">
      <div class="card-body">
        <h5 class="card-title mb-2">Sharp-interface cohesive fracture</h5>
        <p class="card-text">
          Cohesive fracture with <strong>relaxed bulk energy</strong> (quadratic-to-linear growth)
          to avoid unrealistic stress predictions, validated with FEM crack simulations.
        </p>
        <div class="mb-2">
          <span class="badge badge-pill badge-light">cohesive zone</span>
          <span class="badge badge-pill badge-light">fracture</span>
          <span class="badge badge-pill badge-light">relaxed bulk energy</span>
          <span class="badge badge-pill badge-light">FEM</span>
        </div>
        <div class="text-muted small">Read more →</div>
        <a href="#cohesive-fracture" class="stretched-link" aria-label="Cohesive fracture details"></a>
      </div>
    </div>
  </div>

  <!-- 3) Fatigue phase-field -->
  <div class="col-12 col-md-6 col-lg-4 mb-4">
    <div class="card h-100 shadow-sm">
      <div class="card-body">
        <h5 class="card-title mb-2">Phase-field models for fatigue</h5>
        <p class="card-text">
          Variational phase-field formulations that recover Paris-type behavior,
          with efficient FE implementations and extensions beyond the classical validity regime.
        </p>
        <div class="mb-2">
          <span class="badge badge-pill badge-light">phase-field</span>
          <span class="badge badge-pill badge-light">fatigue</span>
          <span class="badge badge-pill badge-light">Paris law</span>
          <span class="badge badge-pill badge-light">FEM</span>
        </div>
        <div class="text-muted small">Read more →</div>
        <a href="#fatigue-phasefield" class="stretched-link" aria-label="Fatigue details"></a>
      </div>
    </div>
  </div>

  <!-- 4) Remodeling -->
  <div class="col-12 col-md-6 col-lg-4 mb-4">
    <div class="card h-100 shadow-sm">
      <div class="card-body">
        <h5 class="card-title mb-2">Dissipative remodeling in fibrous materials</h5>
        <p class="card-text">
          Internal-variable and generalized-standard-material frameworks for
          reorientation, instability patterns, and memory effects in transversely isotropic fibrous media.
        </p>
        <div class="mb-2">
          <span class="badge badge-pill badge-light">remodeling</span>
          <span class="badge badge-pill badge-light">instabilities</span>
          <span class="badge badge-pill badge-light">anisotropy</span>
          <span class="badge badge-pill badge-light">GSM</span>
        </div>
        <div class="text-muted small">Read more →</div>
        <a href="#remodeling-fibrous" class="stretched-link" aria-label="Remodeling details"></a>
      </div>
    </div>
  </div>

  <!-- 5) Locomotion -->
  <div class="col-12 col-md-6 col-lg-4 mb-4">
    <div class="card h-100 shadow-sm">
      <div class="card-body">
        <h5 class="card-title mb-2">Undulatory locomotion in complex media</h5>
        <p class="card-text">
          Analytical and numerical modeling of locomotion in granular/viscous environments:
          FE–DE simulations, resistive-force modeling, and calibration to biological locomotion.
        </p>
        <div class="mb-2">
          <span class="badge badge-pill badge-light">locomotion</span>
          <span class="badge badge-pill badge-light">granular media</span>
          <span class="badge badge-pill badge-light">RFT</span>
          <span class="badge badge-pill badge-light">FE–DE</span>
        </div>
        <div class="text-muted small">Read more →</div>
        <a href="#locomotion" class="stretched-link" aria-label="Locomotion details"></a>
      </div>
    </div>
  </div>

  <!-- 6) IPMC -->
  <div class="col-12 col-md-6 col-lg-4 mb-4">
    <div class="card h-100 shadow-sm">
      <div class="card-body">
        <h5 class="card-title mb-2">IPMC multiphysics</h5>
        <p class="card-text">
          Continuum multiphysics for ionic polymer–metal composites (finite deformations + modified PNP),
          with perturbative closed-form solutions and FE validation.
        </p>
        <div class="mb-2">
          <span class="badge badge-pill badge-light">IPMC</span>
          <span class="badge badge-pill badge-light">multiphysics</span>
          <span class="badge badge-pill badge-light">PNP</span>
          <span class="badge badge-pill badge-light">finite elements</span>
        </div>
        <div class="text-muted small">Read more →</div>
        <a href="#ipmc" class="stretched-link" aria-label="IPMC details"></a>
      </div>
    </div>
  </div>

</div>

---

## Gradient plasticity & anisotropic shear-band localization {#gradient-plasticity}

In this work, anisotropy is embedded in a novel **variational gradient plasticity** model through a curl-based **one-homogeneous defect energy** (used as a first-order contribution to the internal energy, rather than the classical quadratic defect energy). This choice admits **non-smooth solutions** and enables **sharp localization** without diffusive regularization.  
As in curl-plasticity, the defect term depends on the **curl of the plastic strain**, providing a continuum measure of plastic incompatibility associated with dislocations and internal defects. Owing to positive homogeneity of degree one, the defect energy yields non-trivial contributions already at the onset of plastic flow and allows **localization of the curl**, leading to an improved representation of **shear bands** as highly localized zones of intense plastic deformation.  
Within this variational setting, yielding is no longer purely local: the yield condition **emerges from a global energetic balance** involving the defect energy, producing **geometry-dependent size effects** governed by an intrinsic length scale.  
Anisotropy is introduced by modulating the defect energy with an **anisotropic operator** that weights the curl components, thereby selecting preferred directions for plastic incompatibilities and driving **anisotropic shear-band nucleation and evolution**. Numerical simulations highlight how the interplay between anisotropy and global yielding controls localization patterns and band orientation.

<!-- Image placeholder -->
<!-- ![Shear band localization example]({{ '/assets/img/research/gradient_plasticity.png' | relative_url }}){: .img-fluid .rounded } -->

<p class="mb-0"><a href="#top">↑ back to research areas</a></p>

---

## Sharp-interface cohesive fracture with relaxed bulk energy {#cohesive-fracture}

This research tackles unrealistic stress predictions that may arise when coupling cohesive interface energies with standard linear elasticity. Focusing on anti-plane elasticity (mode III) and leveraging LEFM insights, a **relaxed bulk energy** is introduced: **quadratic** at small strains, transitioning to **linear growth** beyond a material-dependent threshold. This yields a better-posed model that respects stress limitations. Numerical FEM simulations demonstrate crack nucleation and propagation along a prescribed path, and ongoing work targets **bulk extensions** to overcome the limitation of pre-defined crack trajectories.

<!-- Image placeholder -->
<!-- ![Cohesive fracture simulation]({{ '/assets/img/research/cohesive_fracture.png' | relative_url }}){: .img-fluid .rounded } -->

<p class="mb-0"><a href="#top">↑ back to research areas</a></p>

---

## Phase-field models describing fatigue {#fatigue-phasefield}

Fatigue is highly relevant and notoriously hard to predict; classic approaches are largely phenomenological (e.g., Paris’ law). I work on **variational phase-field formulations** that couple brittle fracture (Griffith) with fatigue behavior by minimizing a total energy composed of elastic energy plus a dissipation potential (as a power law of the newly created crack surface). The model has been implemented via finite elements (e.g., **FEniCSx**) and tested on both simple and more complex crack paths. Current directions include extending the formulation **above and below** the standard Paris-law regime and validating it against widely used engineering alloys, aiming at a predictive tool that reduces reliance on costly experimental campaigns.

<!-- Image placeholder -->
<!-- ![Fatigue phase-field]({{ '/assets/img/research/fatigue_phasefield.png' | relative_url }}){: .img-fluid .rounded } -->

<p class="mb-0"><a href="#top">↑ back to research areas</a></p>

---

## Dissipative remodeling in fibrous materials {#remodeling-fibrous}

Fibrous materials—especially biological tissues—can reorganize internally under chemo-mechanical stimuli (aging, disease, interventions), with fiber reorientation linked to changes in stored energy and irreversible deformations. I investigate remodeling from a mechanics standpoint by focusing on general **2D transversely isotropic** settings and adopting **generalized standard materials** with **internal variables** to track inelastic processes. The goal is to provide theoretical and numerical tools to predict reorientation, the emergence of **fingering-like patterns**, and **memory effects**, with potential impact on prosthetics, implants, and tissue engineering.

<!-- Image placeholder -->
<!-- ![Remodeling patterns]({{ '/assets/img/research/remodeling.png' | relative_url }}){: .img-fluid .rounded } -->

<p class="mb-0"><a href="#top">↑ back to research areas</a></p>

---

## Undulatory locomotion in complex media {#locomotion}

Undulatory locomotion is widely used in nature to move through flowable media. Inspired by this strategy, I model locomotion in complex environments to inform soft-robot design for soil exploration. The work combines: (i) parametric **FE–DE** simulations for slender bodies moving in particle layers; (ii) analytical derivations via **Lagrangian mechanics** with resistive-force-type terms to emulate viscous environments; (iii) calibration to reproduce biological features (e.g., characteristic speeds); and (iv) prototyping via an in-house soft robot.

<!-- Image placeholder -->
<!-- ![Locomotion in granular media]({{ '/assets/img/research/locomotion.png' | relative_url }}){: .img-fluid .rounded } -->

<p class="mb-0"><a href="#top">↑ back to research areas</a></p>

---

## Multiphysics of ionic polymer–metal composites (IPMCs) {#ipmc}

IPMCs are smart materials used as sensors/actuators: mechanical loading can generate voltage across electrodes and electric fields can induce deformation. Their dynamics require a multiphysics description. I work within a continuum framework coupling **finite deformations** with a modified **Poisson–Nernst–Planck** system for electrochemistry. For compression sensing, I developed both a perturbative **closed-form solution** and a **finite element implementation**, and performed systematic comparisons to clarify accuracy vs mathematical complexity trade-offs.

<!-- Image placeholder -->
<!-- ![IPMC sensing]({{ '/assets/img/research/ipmc.png' | relative_url }}){: .img-fluid .rounded } -->

<p class="mb-0"><a href="#top">↑ back to research areas</a></p>