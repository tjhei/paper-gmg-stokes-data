# Additional Data for the Stokes GMG Paper

This repository contains source code, parameter files, and additional data
used in the computations of the paper:

```
Thomas C. Clevenger, Timo Heister
Comparison Between Algebraic and Matrix-free Geometric Multigrid for
a Stokes Problem on an Adaptive Mesh with Variable Viscosity
submitted, 2019
```
[preprint on Arxiv](https://arxiv.org/abs/1907.06696)

Note: This repository contains git submodules for the dependencies deal.II and
ASPECT. Please clone this repository using ``git clone --recurse-submodules``
or initialize the repositories using ``git submodule init`` if you cloned
without it.

## Contents

This repository contains the following:
1. ``deal.II`` -- Snapshot of the [deal.II](https://github.com/dealii/dealii) master branch from Feb 28, 2020 (after deal.II v9.2.0 with many important performance and 64bit fixes)
2. ``aspect`` -- Experimental branch of [ASPECT](https://github.com/geodynamics/aspect), see https://github.com/tjhei/aspect/tree/gmg-stokes-paper

## Details about the computational setup

