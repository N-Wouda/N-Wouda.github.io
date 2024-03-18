<!--
.. title: Projects
.. slug: projects
.. date: 2020-11-23 18:53:07 UTC+01:00
.. updated: 2024-03-18 18:04 UTC+01:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text
-->

# Ongoing projects

- PyVRP, a high-performance vehicle routing problem (VRP) solver that achieves exceptional performance on a number of VRP variants.
  The solver is written in C++ and Python, and available on the Python package index as `pyvrp`; the repository is available [here](https://github.com/PyVRP/PyVRP/).
  We published [a paper](https://doi.org/10.1287/ijoc.2023.0055) in _INFORMS Journal on Computing_.
  Work is ongoing to support additional VRP variants in new releases of PyVRP.

- [nearing completion]
  A project optimising waste collection for the Municipality of Groningen.
  One of the unusual aspects of this particular waste collection problem is that we have some sensor data about arrivals at each waste container, but that data is incomplete: we do not observe the amount of waste arriving, only that an arrival has taken place.
  It is thus not clear which containers are actually full, and which can still take more arrivals.
  The goal is to select which containers to visit, and then optimise the routing decisions given those containers.
  We are developing an efficient policy that integrates the routing and container selection decisions based on the available data.

# Past projects

A selection:

- A project optimising chance-constrained network design problems under demand uncertainty.
  We developed an exact solution approach based on row generation for this problem.
  Computational experiments show our method is much more performant than the current state-of-the-art.
  We have submitted [a paper](https://arxiv.org/abs/2403.03567), and the software repository is available [here](https://github.com/N-Wouda/CC-NDP).

- I organised a team of motivated PhD candidates to join in the [EURO meets NeurIPS 2022 vehicle routing challenge](https://euro-neurips-vrp-2022.challenges.ortec.com/).
  Together, we developed algorithms solving two variants of a vehicle routing problem with time windows.
  Our team (OptiML) finished first on the static problem variant, and third on the dynamic, for an overall second place!
  The software repository is available [here](https://github.com/N-Wouda/Euro-NeurIPS-2022).

- A metaheuristic for an hourly learner timetabling problem arising in Dutch secondary education, where learners are scheduled by their demands for various courses and modules (a variant of personalised learning).
  We published [a paper](https://doi.org/10.1016/j.cor.2022.106089) in _Computers & Operations Research_.
  The software repository is available [here](https://github.com/N-Wouda/PL-Heuristic).

- A Python implementation of the adaptive large neighbourhood search (ALNS) metaheuristic.
  The package is available on the Python package index as `alns`; the repository is available [here](https://github.com/N-Wouda/ALNS).
  We published [a paper](https://doi.org/10.21105/joss.05028) in the _Journal of Open Source Software_.
