---
title: Unstructured Grid Adaptation Working Group
---

# UGAWG
The Unstructured Grid Adaptation Working Group (UGAWG) is composed of
researchers that develop tools to modify unstructured grids to conform
to a metric (anisotropic size request).
Computational Fluid Dynamics
(CFD) turbulent flow simulation with solution-adapted grids is a target
application of the working group researchers.
The group meets virtually for detailed implementation details discussions
and to make plans for publication.

# Verification Benchmark
The repositories in the UGAWG GitHub group house test cases for the
verification of adaptive grid mechanics and integrated grid adaptation
processes (Flow solver, error estimate, metric construction, grid mechanics).
This benchmark is available to evaluate modifications to
existing methods and develop new approaches to metric conforming
grid adaptation, grid generation, and integrated grid adaptation
processes.
The benchmark is collection of case descriptions,
geometry, input grids, and output grids,
which define expected performance
and enables verification by comparison.

The Gamma Mesh Format is used for grid, geometry association, solution, and
metric interchange.
A reference implementation of readers and writers with
documentation is available at
[LoicMarechal/libMeshb](https://github.com/LoicMarechal/libMeshb).
File conventions and evaluation methods are described in
[adapt-benchmarks](https://github.com/UGAWG/adapt-benchmarks).
Grid adaptation tools are applied to these benchmarks and
the resulting grids are available in repositories via
[Git Large File Storage](https://git-lfs.github.com/).

# References
- Geometry Modeling for Unstructured Mesh Adaptation, AVIATION 2019.
- Parallel Anisotropic Unstructured Grid Adaptation, [AIAA-2019-1995](https://arc.aiaa.org/doi/abs/10.2514/6.2019-1995).  PDF of the [SciTech 2019 Presentation](pdf/aiaa-2019-1995-parallel-adapt-talk.pdf).
- Verification of Unstructured Grid Adaptation Components, [AIAA-2019-1723](https://arc.aiaa.org/doi/abs/10.2514/6.2019-1723).  PDF of the [SciTech 2019 Presentation](pdf/aiaa-2019-1723-adapt-verification-talk.pdf).
- Unstructured Grid Adaptation and Solver Technology for Turbulent Flows, [AIAA-2018-1103](https://arc.aiaa.org/doi/abs/10.2514/6.2018-1103). PDF of the [SciTech 2018 Presentation](pdf/aiaa-2018-1103-solver-tech-adapt-talk.pdf). 
- First benchmark of the Unstructured Grid Adaptation Working Group, [Procedia Engineering, Volume 203, 2017, Pages 154-166](https://doi.org/10.1016/j.proeng.2017.09.800). PDF of the [IMR 2017 Presentation](pdf/ugawg-imr-2017-benchmark-1-talk.pdf).
- Unstructured Grid Adaptation: Status, Potential
Impacts, and Recommended Investments Toward
CFD Vision 2030, [AIAA-2016-3323](https://arc.aiaa.org/doi/abs/10.2514/6.2016-3323). PDF of the [AVIATION 2016 Presentation](pdf/aiaa-2016-3323-grid-adapt-2030-talk.pdf).
- Comparing Anisotropic Output-Based Grid Adaptation Methods by Decomposition, [AIAA-2015-2292](https://arc.aiaa.org/doi/abs/10.2514/6.2015-2292). PDF of the [AVIATION 2015 Presentation](pdf/aiaa-2015-2292-decomposition-talk.pdf).
- CFD Vision 2030 Study: A Path to Revolutionary Computational Aerosciences, [NASA/CR-2014-218178](https://ntrs.nasa.gov/search.jsp?R=20140003093).