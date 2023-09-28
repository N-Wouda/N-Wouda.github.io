<!--
.. title: Useful resources
.. slug: resources
.. date: 2020-11-23 19:15:58 UTC+01:00
.. updated: 2023-09-28 22:43 UTC+01:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text
-->

This page contains a number of essays and books I found particularly instructive,
and software packages I frequently use. The resource list below is obviously not
exhaustive.

# Readings in programming

Various materials available online:

- Peter Norvig's classic _Teach Yourself Programming in Ten Years_, [here](https://norvig.com/21-days.html).

- MIT's _The Missing Semester of Your CS Education_, [here](https://missing.csail.mit.edu/).

- Ben Kuhn's _Essays on programming I think about a lot_, [here](https://www.benkuhn.net/progessays/).
  Equally interesting are the many blogs people reference in the comments.

- I like the ['code review pyramid'](https://www.morling.dev/blog/the-code-review-pyramid/).

Physical books:

- GoF's _Design Patterns_. This is best read once or twice, and then kept as a
  reference book.
  
- Martin Fowler's _Refactoring_. Combined with GoF, this is a great resource on
  how to do OOP right, and improve the structure of existing code. 

- Kent Beck's _Test-Driven Development_. This book is short, to the point, and
  really hammers down the concepts of TDD. I often sin against the TDD premise 
  of "test first, code later", but do agree that (almost all) code should - and
  can - be supported by meaningful tests or validation tools.
  
- Andrew Hunt and David Thomas' _The Pragmatic Programmer_. This book is a classic,
  touching upon many aspects of software development. I like this book so much, it
  has not been on my book shelf for years: I keep lending it to friends and 
  colleagues to read.

# Software

Most of my personal projects are in Python because that language covers almost
all of my needs, is extremely flexible, and I find its code structure visually
pleasing (I am the first to concede all these points are extremely subjective).
When performance is critical for a particular application, I often switch to C or
C++, sometimes with Python bindings.

Most of my projects use numbers in some way, so in Python I often work with 
[numpy](https://numpy.org/), [pandas](https://pandas.pydata.org/) and the like.
In C++ I use [Armadillo](http://arma.sourceforge.net/) (`arma`) as a
`numpy`-equivalent. 

Interfacing C++ and Python is achieved by the excellent [pybind11](https://github.com/pybind/pybind11) 
project. I sometimes complement `pybind11` with [carma](https://github.com/RUrlus/carma) 
for the conversion between `numpy` and `arma` types.

My mathematical programming problems are mostly solved with [Gurobi](https://www.gurobi.com/), 
but I have also used IBM's [CPLEX](https://www.ibm.com/analytics/cplex-optimizer)
and Google's [OR-Tools](https://developers.google.com/optimization) in the past. 
For an open-source project, `OR-Tools` works really well and I intend to use it
more often in the future.
