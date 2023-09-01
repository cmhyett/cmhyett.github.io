---
layout: gsoc
title: 'Google Summer of Code'
date: 2023-08-27
permalink: /portfolio/gsoc/
tags:
  - Google Summer of Code
  - Julia
  - SciML
  - Numerical PDEs
---

Here I will document work done in fulfillment of the project _NumFocus & SciML, PDEs on Graphs_.

This work was meant to encapsulate 3 related efforts:
1. Implement staggered grid discretization inside `MethodOfLines.jl`
2. Pathfind for integration of `FENICS.jl` and `DolphinX`
3. Leverage those toolsets to create an accessible and lightweight backed for solving PDEs on networks.

The effort to stand up staggered grid discretizations (correctly) was a _much_ longer PR than originally anticipated, and thus the summer 2023 was mainly spent learning symbolic programming, and staggered numerical methods before implementing the discretization backend. The majority of the work is captured in this [MethodOfLines.jl pull request](https://github.com/SciML/MethodOfLines.jl/pull/285)

## Symbolic Programming

## Staggered Discretization

## Numerical Examples

![Reflecting Boundary Conditions](../../images/staggered_grids/reflecting_bcs.png)
*Reflecting Boundary Conditions*


![Transparent Boundary Conditions](../../images/staggered_grids/transparent_bcs.png)
*Transparent Boundary Conditions*