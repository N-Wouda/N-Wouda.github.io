<!--
.. title: PyVRP in 2024 and 2025
.. slug: pyvrp-in-2024-and-2025
.. date: 2025-01-02 13:21:16 UTC+01:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text
-->

This is a brief summary of the progress made on PyVRP in 2024, and a look at some things planned for 2025.<!-- TEASER_END -->

# Looking back: PyVRP in 2024

In 2024 we continued with a roughly quarterly release cycle.
There were four releases in total, from 0.7 in January 2024, through 0.10, released in November last year.
Each version added lots of new functionality, some of which includes:

- 0.7 (January 2024) added support for multiple depots to PyVRP, as well as maximum duration constraints.
  I was surprised to find out this also happened just last year - in my mind, we added this so long ago, it had to be much further in the past.

- 0.8 (March 2024) added support for return shipments (backhaul), maximum distance constraints, and mutually exclusive client groups.
  The latter was added mostly because it was a fun addition at the time, but is actually quite useful for many practical applications, because it can be used to model multiple time windows.

- 0.9 (June 2024) added support for mixed distance and duration objectives, and different driving profiles.
  The profiles can be used to model zone restrictions, but also to account for the differences between for example cars, trucks, and bicycles.

- 0.10 (Nov 2024) added support for multiple load dimensions.
  This can be used to account for e.g. both weight and volume, or different vehicle and driver skills.

Besides new functionality, the adoption of the PyVRP project itself also took off quite a bit.
The repository gained some 250 stars last year, and the discussion feature is now regularly used for Q&A.
Further, the paper has been cited more than a dozen times last year, and additionally, PyVRP is increasingly being used in the wild to solve actual business problems (some of which I helped make happen, others I was told about).
All in all, 2024 was a productive year.

# Looking ahead: PyVRP in 2025

In 2025 we will continue to add new features and improve the project quality.
The upcoming release (0.11) is scheduled for February or March 2025, and will contain some performance improvements.
Additionally, there will be some updates to the documentation and support for a latest start constraint on the vehicles.

The release thereafter (0.12) is scheduled for the summer of 2025, and will probably add support for multiple trips to PyVRP.
At some point we will also write another paper about PyVRP, and that will probably happen based on the 0.12 release.
There is no roadmap yet for releases later in the year, but good candidates for those are general pickup and delivery between clients ('pickup and delivery'), and groups of clients that all need to be serviced on the same route ('clustered VRP').
