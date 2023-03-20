<!--
.. title: Projects
.. slug: projects
.. date: 2020-11-23 18:53:07 UTC+01:00
.. updated: 2023-03-20 20:29 UTC+01:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text
-->

# Current projects

Most recently started first:

- [early]
  A project optimising waste collection for the Municipality of Groningen.
  One of the neat/unusual aspects of this particular waste collection problem is that we have some sensor data about arrivals at each waste container, but that data is incomplete: we do not observe the amounts.
  We are currently working on efficiently emptying a system with such containers making good use of the available data.
  More on this later in 2023. 

- [early] 
  A project optimising the scheduling of elective hours in Dutch secondary
  education. We are developing a scheduling algorithm that schedules electives 
  based on (changing) learner needs.
  More on this later in 2023. 

- [ongoing]
  A high-performance vehicle routing problem (VRP) solver that achieves exceptional performance on a number of VRP variants.
  The solver is writting in C++ and Python, and available on the Python package index as `pyvrp`;
  the repository is available [here](https://github.com/N-Wouda/PyVRP/).
  We submitted a paper to _INFORMS Journal on Computing_.

- [nearing completion]
  My first PhD project, on optimising supply chain network design problems under
  supply and demand uncertainty. We developed an exact solution approach based on
  row generation for this problem. Computational experiments show our method is
  much more performant than the current state-of-the-art. Using our method, we are
  currently investigating an interesting e-fuel network design problem arising
  in the Netherlands.

# Past projects

A selection:

- I organised a team of motivated PhD candidates to join in the
  [EURO meets NeurIPS 2022 vehicle routing challenge](https://euro-neurips-vrp-2022.challenges.ortec.com/).
  Together, we developed algorithms solving two variants of a vehicle routing problem with time windows.
  Our team (OptiML) finished first on the static problem variant, and third on the dynamic, for an
  overall second place! The software repository is available [here](https://github.com/N-Wouda/Euro-NeurIPS-2022).

- A metaheuristic for an hourly learner timetabling problem arising in Dutch
  secondary education, when learners are scheduled by their demands or preferences
  for various courses and modules (a variant of personalised learning).
  We published [a paper](https://doi.org/10.1016/j.cor.2022.106089) in 
  _Computers & Operations Research_. The software repository is available 
  [here](https://github.com/N-Wouda/PL-Heuristic).

- The [Rome Hinterland Project](http://comparativesurveyarchaeology.org/) (RHP)
  database. The RHP combines archaeological survey data collected over the past
  70 years in the territory of Rome to create the largest integrated regional
  dataset for the hinterland of any ancient Mediterranean city. We published 
  [a paper](https://doi.org/10.1017/eaa.2021.51) in the _European Journal of
  Archaeology_ motivating the need for the RHP database.
  <br />
  In early 2021, I gave two presentations about my work on the RHP. The first,
  [here](https://nielswouda.com/slides/rhp_tech), explains the implementation
  process. The second, [here](https://nielswouda.com/slides/rhp_user), explains
  several common queries one might perform.

- A Python implementation of the adaptive large neighbourhood search (ALNS) 
  metaheuristic. The package is available on the Python package index as `alns`; 
  the repository is available [here](https://github.com/N-Wouda/ALNS). We published 
  [a paper](https://doi.org/10.21105/joss.05028) in the _Journal of Open Source Software_.
