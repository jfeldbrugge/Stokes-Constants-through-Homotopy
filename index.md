---
title: Additional Video Material - *Stokes Constants through Homotopy*
author: Inês Aniceto, Job Feldbrugge and Christopher J. Howls
header-includes:
  - |
    ```{=html}
    <link rel="icon" href="figures/icon.png" type="image/x-icon">
    ```
include-before:
  - |
    ```{=html}
    <div class="topnav">
      <a href="https://jfeldbrugge.github.io/">Home</a>
      <a href="https://jfeldbrugge.github.io/Projects-and-Codes/">Projects and Code</a>
    </div>
    ```
---

This page accompanies the paper *Stokes Constants through Homotopy* [arXiv link to follow]. It animates the homotopy continuation of the Stokes constants for the examples of Section V, Figures 4 to 8 of the paper.

**How to read the animations.** The homotopy deforms a factorisable reference integral, whose Stokes constants follow from one-dimensional integrals, into the integral of interest as the parameter $\lambda$ runs from $0$ to $1$. Every saddle point maps to a Borel singularity $t_j = -\mathrm{i} f(\boldsymbol{x}_j)$, which moves through the Borel plane along a coloured curve, one colour per saddle point. The red edges join adjacent saddle points, with widths proportional to the magnitude of the Stokes constant $|K_{jl}|$. A Stokes constant changes when the Borel singularity of a third saddle point crosses the segment between two others, a higher-order Stokes phenomenon. The black dots, labelled as in the paper, mark the saddle points that reach the integral of interest. The grey dots mark the saddle points that fly off to infinity, with their edges in pale red. All animations use the parameter $\gamma = e^{\mathrm{i}\pi/5}$ of the paper.

---

## The swallowtail catastrophe

**Description:** The diffraction integral of the swallowtail catastrophe, $\Psi = \sqrt{k/(2\pi \mathrm{i})} \int e^{\mathrm{i}k(t^5 + z t^3 + y t^2 + x t)}\,\mathrm{d}t$, with $x = y = 0.7$ and $z = -1$. The four saddle points of the reference integral all reach the four saddle points of the swallowtail, and the adjacency graph rearranges in three higher-order Stokes phenomena.

**Referenced in:** Section V A / Figure 4

**Animation:** [Swallowtail.mp4](figures/Swallowtail.mp4)

![Homotopy continuation for the swallowtail catastrophe](figures/Swallowtail.mp4){width=100%}

---

## The parabolic umbilic

**Description:** The two-dimensional diffraction integral of the parabolic umbilic, with the exponent $u^2 v + v^4 + x u^2 + y v^2 + z u + w v$ for $x = 0.1$, $y = -0.1$, $z = 1$ and $w = 0$. Five of the six saddle points of the reference integral reach the parabolic umbilic, and the sixth flies off to infinity.

**Referenced in:** Section V B / Figure 5

**Animation:** [Parabolic.mp4](figures/Parabolic.mp4)

![Homotopy continuation for the parabolic umbilic](figures/Parabolic.mp4){width=100%}

---

## The one-dimensional Lorentzian lens

**Description:** The Kirchhoff–Fresnel integral of a one-dimensional Lorentzian lens, with the rational exponent $f = (x - y)^2/2 + \beta/(1 + x^2)$ for $y = \beta = 1$, lifted to a polynomial exponent in three variables. Of the $48$ saddle points of the reference integral, $43$ fly off to infinity. On their way out, they cross the segments between the five survivors and leave Stokes constants of magnitude $2$ behind.

**Referenced in:** Section V C / Figure 6

**Animation:** [1DLens.mp4](figures/1DLens.mp4)

![Homotopy continuation for the one-dimensional Lorentzian lens](figures/1DLens.mp4){width=100%}

---

## The two-dimensional Lorentzian lens

**Description:** The two-dimensional Lorentzian lens, $f = |\boldsymbol{x} - \boldsymbol{y}|^2/2 + \beta/(1 + x_1^2 + 2x_2^2)$ for $\boldsymbol{y} = (1, 1)$ and $\beta = 1$, lifted to a polynomial exponent in four variables. Of the $192$ saddle points of the reference integral, $9$ survive. Of their $36$ pairs, $31$ end up adjacent, and $7$ carry Stokes constants $\pm 2$.

**Referenced in:** Section V C / Figure 7

**Animation:** [2DLens.mp4](figures/2DLens.mp4)

![Homotopy continuation for the two-dimensional Lorentzian lens](figures/2DLens.mp4){width=100%}

---

## The Hankel function

**Description:** The Hankel function of order one, $\int_0^\infty e^{\mathrm{i}k(x + 1/x)}\,\mathrm{d}x$, lifted to the polynomial exponent $(1 + x_1^2)\,x_2 + x_3(x_2 x_1 - 1)$. Two of the eight saddle points of the reference integral reach the saddle points $x = \pm 1$, with the Borel singularities $t_1 = 2\mathrm{i}$ and $t_2 = -2\mathrm{i}$. Near $\lambda \approx 0.83$, two escaping saddle points cross the segment between the survivors at the same moment, at opposite points, and the Stokes constant jumps from $0$ to $2$.

**Referenced in:** Section V D / Figure 8

**Animation:** [Hankel.mp4](figures/Hankel.mp4)

![Homotopy continuation for the Hankel function](figures/Hankel.mp4){width=100%}
