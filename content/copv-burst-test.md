---
startDate: "June 2026"
endDate: "July 2026"
title: 'COPV Burst Test Analysis'
description: 'Composite pressure vessel burst test simulation and validation using Abaqus/Explicit.'
skills:
  - Abaqus
  - Composites
  - FEA
---

## Skills:

{{< project-skills >}}

## Highlights:

- Modelled a half-symmetry model of a Type-V composite pressure vessel on Abaqus, consisting of a 3D solid model of the metallic head and a 2D shell model of the composite shell
- Defined the composite layup, constraints, and boundary conditions acccording to the reference PhD dissertation
- Simulated a burst test using Abaqus/Explicit, predicting ultimate failure within 11% of experimental benchmark data using Hashin damage
- Conducted a mesh sensitivity analysis to optimize the element size and step parameters, reducing runtime by around 32% while maintaining simulation accuracy and mesh convergence

## Abaqus Model:

<div class="project-image-grid">

<figure>
    <img src="/images/copv-head.png" alt="Head">
    <figcaption>3D Solid Model of the Metallic Head</figcaption>
</figure>

<figure>
    <img src="/images/copv-shell.png" alt="Shell">
    <figcaption>2D Shell Model of the Composite Shell</figcaption>
</figure>

</div>

## Burst Test Simulation:

<div class="project-image-grid">

<figure>
    <img src="/images/copv-fail.png" alt="Fail">
    <figcaption>Hashin Failure Plot at Burst Pressure</figcaption>
</figure>

<figure>
    <img src="/images/copv-burst.png" alt="Burst">
    <figcaption>Pressure Vessel Model after Simulation Completion</figcaption>
</figure>

</div>