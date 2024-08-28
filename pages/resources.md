<!--
.. title: Useful resources
.. slug: resources
.. date: 2020-11-23 19:15:58 UTC+01:00
.. updated: 2024-02-27 12:29 UTC+01:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text
-->

This page contains a number of essays and books I found particularly instructive, and software packages I frequently use.
The resource list below is obviously not exhaustive.

# Readings in programming

Various materials available online:

- Peter Norvig's classic _Teach Yourself Programming in Ten Years_, [here](https://norvig.com/21-days.html).
  I re-read this essay about once a year.

- MIT's _The Missing Semester of Your CS Education_, [here](https://missing.csail.mit.edu/).

- Ben Kuhn's _Essays on programming I think about a lot_, [here](https://www.benkuhn.net/progessays/). Equally interesting are the many blogs people reference in the comments.

- I like the ['code review pyramid'](https://www.morling.dev/blog/the-code-review-pyramid/).

Physical books:

- GoF's _Design Patterns_.
  This is best read once or twice, and then kept as a reference book.

- Martin Fowler's _Refactoring_.
  Combined with GoF, this is a great resource on how to do OOP, and improve the structure of existing code. 

- Kent Beck's _Test-Driven Development_.
  This book is short, to the point, and really hammers down the concepts of TDD.
  I often sin against the TDD premise of "test first, code later", but do agree that (almost all) code should - and can - be supported by meaningful tests or validation tools.

# Software

Most of my personal projects are in Python because that language covers almost all of my needs, is extremely flexible, and I find its code structure visually pleasing (I concede all these points are extremely subjective).
When performance is critical for a particular application, I prefer to use C++, sometimes with Python bindings.

Most of my projects use numbers in some way, so in Python I often work with [numpy](https://numpy.org/), [pandas](https://pandas.pydata.org/) and the like.
In C++ I use [Armadillo](http://arma.sourceforge.net/) (`arma`) as a numpy equivalent, if needed.
Interfacing C++ and Python is achieved by the excellent [pybind11](https://github.com/pybind/pybind11) project. 

My mathematical programming problems are today mostly solved with [Gurobi](https://www.gurobi.com/).
I have also used [CPLEX](https://www.ibm.com/analytics/cplex-optimizer) and [OR-Tools](https://developers.google.com/optimization) in the past.
I want to use [HiGHS](https://highs.dev/) more in the future.
