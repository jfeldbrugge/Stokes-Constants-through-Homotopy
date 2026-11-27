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

This page accompanies the paper *Stokes Constants through Homotopy* [arXiv link to follow]. It animates the higher-order Stokes phenomenon of Figure 1, the rotation of the steepest descent manifolds of Figure 3, the homotopy continuation of the Stokes constants for the examples of Section V, Figures 4 to 8 of the paper, and the Stokes transition in the complex plane of Figure 9, for the Stokes constants $1$ and $2$.

**How to read the animations.** The homotopy deforms a factorisable reference integral, whose Stokes constants follow from one-dimensional integrals, into the integral of interest as the parameter $\lambda$ runs from $0$ to $1$. Every saddle point maps to a Borel singularity $t_j = -\mathrm{i} f(\boldsymbol{x}_j)$, which moves through the Borel plane along a coloured curve, one colour per saddle point. The red edges join adjacent saddle points, with widths proportional to the magnitude of the Stokes constant $|K_{jl}|$. A Stokes constant changes when the Borel singularity of a third saddle point crosses the segment between two others, a higher-order Stokes phenomenon. The black dots, labelled as in the paper, mark the saddle points that reach the integral of interest. The grey dots mark the saddle points that fly off to infinity, with their edges in pale red. All animations use the parameter $\gamma = e^{\mathrm{i}\pi/5}$ of the paper.

---

## The higher-order Stokes phenomenon

**Description:** The sketch of Figure 1 in motion. Three Borel singularities, with their branch cuts (grey zigzag lines) and the labels of the Riemann sheets the cuts connect, move through the Borel plane. At first, the three saddle points see each other (red lines). The singularity of saddle point $1$ then moves down, while those of saddle points $2$ and $3$ move up, until the three line up. At this higher-order Stokes phenomenon, the branch cut of saddle point $1$ moves in between the branch points of $2$ and $3$. Saddle point $1$ then obscures their vision, and $2$ and $3$ no longer see each other.

**Referenced in:** Section II B / Figure 1

**Animation:** [HigherOrderStokes.mp4](figures/HigherOrderStokes.mp4)

![The higher-order Stokes phenomenon](figures/HigherOrderStokes.mp4){width=70%}

---

## Rotating around the origin

**Description:** The left panel of Figure 3 in motion. For the integral $\int e^{-k(x^6/6 - x)}\,\mathrm{d}x$, the steepest descent manifolds (solid) and ascent manifolds (dashed) of the five saddle points rotate as the phase of $k = -\mathrm{i}\,e^{\mathrm{i}\pi\alpha}$ runs once around the origin, from $\alpha = 0$ to $2$. The background shows $\mathrm{Re}[-k f]$. The steepest descent manifold of saddle point $j$ runs into saddle point $l$ when $k(f_l - f_j)$ is real and positive, at a Stokes line. The manifold then flashes red, and the edge between $j$ and $l$ appears in the Borel plane on the right. By symmetry, the Stokes lines arrive in pairs. After one rotation, every pair of saddle points has seen each other, and the adjacency graph is complete.

**Referenced in:** Section III A / Figure 3

**Animation:** [RotatingK.mp4](figures/RotatingK.mp4)

![The steepest descent manifolds as the phase of k rotates](figures/RotatingK.mp4){width=100%}

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

---

## The Stokes transition in the complex plane

**Description:** What does a Stokes constant do to an integral? These two animations rotate the phase of $k$ across the Stokes line $\arg k = -\pi/2$ and follow the integration contour $\mathcal{C}$ in the complex $x$-plane, in the style of Figure 9 of the paper. Both exponents have the saddle points $x_1 = -1$ and $x_2 = 1$. The background shows $\mathrm{Re}[\mathrm{i}kf]$, red where the integrand grows and blue where it decays. The red curves, with arrows, show the contour as a sum of steepest descent manifolds $\mathcal{J}_j$, a double line marks a manifold counted twice, the grey curve the irrelevant manifold of $x_1$, and the dashed curves the steepest ascent manifolds. Before the Stokes line, the contour equals $\mathcal{J}_2$ and $x_1$ stays irrelevant. On the line, the steepest descent manifold of $x_2$ runs into $x_1$. Beyond it, $x_1$ turns relevant with a multiplicity equal to the magnitude of the Stokes constant. The animation finds this multiplicity in every frame from the valleys in which the ends of the oriented manifolds lie, with every manifold oriented as the continuation of its asymptotic series demands.

**Stokes constant 1.** For the cubic exponent $f = x - x^3/3$, the integral of the Airy type, the steepest descent manifold of $x_2$ runs into $x_1$ along a single path, and the contour becomes $\mathcal{C} = \mathcal{J}_2 - \mathcal{J}_1$. For a polynomial exponent in one variable, at most one steepest descent path joins two saddle points, and $|K_{jl}| \leq 1$.

**Animation:** [StokesTransition_K1.mp4](figures/StokesTransition_K1.mp4)

![Stokes transition with Stokes constant 1](figures/StokesTransition_K1.mp4){width=70%}

**Stokes constant 2.** For the Hankel function, $f = x + 1/x$, the steepest descent manifold of $x_2$ runs into $x_1$ along both halves of the unit circle, on either side of the pole at $x = 0$, and the contour becomes $\mathcal{C} = \mathcal{J}_2 + 2\mathcal{J}_1$. The pole keeps the two paths from cancelling.

**Referenced in:** Section V D / Figure 9

**Animation:** [StokesTransition_K2.mp4](figures/StokesTransition_K2.mp4)

![Stokes transition with Stokes constant 2](figures/StokesTransition_K2.mp4){width=70%}
