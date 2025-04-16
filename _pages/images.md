---
layout: page
title: "Images"
permalink: /images/
author_profile: true
---
# Phase transitions

Part of my work concerns the percolative properties of Gaussian fields. A nice (open access) survey of this topic can be found [here](https://doi.org/10.1214/23-PS24).

The most fundamental result in this area, is the occurrence of a phase transition: for a given field $f$ (satisfying appropriate assumptions) there is a critical level $\ell_c$ such that with probability one

  * for all $\ell>\ell_c$, the excursion set $\lbrace f\geq\ell\rbrace$ contains only bounded components, and
  * for all $\ell<\ell_c$, the excursion set $\lbrace f\geq\ell\rbrace$ contains a unique unbounded component.

The following two graphics illustrate the phase transition for the planar Gaussian field $f$ with covariance function

$$\mathrm{Cov}[f(x),f(y)]=\exp\left(-\frac{\lvert x-y\rvert^2}{2}\right).$$

This model is known as the Bargmann-Fock field and is the scaling limit of a canonical family of random homogeneous polynomials. Further details can be found [here](https://doi.org/10.1007/s10240-017-0093-0).

At each instant, the black points show the lower excursion set $\lbrace f\leq\ell \rbrace$ for a given value of $\ell$. The white and green points show the upper excursion set $\lbrace f > \ell\rbrace$, with one particular component of this highlighted in green. The level $\ell$ decreases over time, so that the upper excursion set becomes larger. Eventually the space is dominated by a single component of this excursion set, representing the phase transition.

<img src="/images/growing_comp_bf_pix=2k_seed=default.gif" alt="Phase transition for Bargmann-Fock field" width="40%" />
<img src="/images/growing_comp_bf_pix=2k_scale=0.3_seed=default.gif" alt="Phase transition for Bargmann-Fock field (large scale)" width="40%" />

The left and right graphics show the same phenomenon on different scales. The transition appears to occur more quickly on the right picture

The following two graphics illustrate the phase transition for the Gaussian field with covariance function

$$\mathrm{Cov}[f(x),f(y)]=J_0(\lvert x-y\rvert),$$

where $J_0$ denotes the $0$-th Bessel function. This model is known as the Random Plane Wave and is studied in connection with quantum chaos. See [here](https://doi.org/10.1007/s41468-023-00140-x) for further background.

<img src="/images/growing_comp_RPW_pix=2k_scale=1_seed=default.gif" alt="Phase transition for Bargmann-Fock field" width="40%" />
<img src="/images/growing_comp_RPW_pix=2k_scale=0.3_seed=default.gif" alt="Phase transition for Bargmann-Fock field (large scale)" width="40%" />

