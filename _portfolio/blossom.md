---
layout: gsoc
title: 'Implementing Blossom Algorithm'
date: 2024-12-04
permalink: /portfolio/blossom
tags:
  - Julia
  - SciML
  - Graphs
---

I stumbled upon the opportunity to contribute to `GraphsMatching.jl` via a bug-bounty program, (cannot emphasize enough how powerful even a small amount of money can be to get latent developers off the sidelines), by implementing the Blossom algorithm.

As I implemented it, it was really the Edmond's algorithm, and this algorithm is a beautiful bit of computer science history. Graphs were a fundamental object of study in the early days of computation; memory was scarce, and graphs could be stored and operated on efficiently (especially if the edges had integer weights).

Jack Edmonds in 1965(?) published an algorithm to find a maximum perfect matching for edges of a general graph. His insight, and construction of a polynomial time algorithm to determine this matching, reverberates even now, after massive algorithmic parallelization on GPU, and when AI/ML seem to find approximate solution in a fraction of the time of traditional algorithms.