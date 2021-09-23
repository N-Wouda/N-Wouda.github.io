<!--
.. title: Revealed preference for the partial order problem
.. slug: revealed-preference-for-the-partial-order-problem
.. date: 2021-09-22 20:03:58 UTC+02:00
.. has_math: true
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text
-->

In this post we consider the problem of recovering a rational ordering of items from revealed preferences.
<!-- TEASER_END -->

# Problem definition

We consider the problem of recovering an agent's preference ordering over $N$ goods $G = \lbrace g_1, g_2, \ldots, g_N \rbrace$.
We assume a data set of $M$ data points of agent choices are available.
In particular, we assume each choice consists of the agent choosing one item $g$ from a subset $S$ of the $N$ goods.
This results in a partial order, since the one item is revealed preferred over the other items in the subset.
Each data point $i = 1, \ldots, M$ is described as the tuple $(g_i, S_i)$ of the revealed preferred good $g_i$ and the subset $S_i \subseteq G$ of goods that the agent was offered to choose from.

The problem is that we wish to recover an ordering of $G$ that is consistent with the $M$ data points.
Two particularly pressing issues are dealt with in this post:

1. How large must $M$ minimally be to fully recover an ordering of $G$? How does that depend on the subset size $S_i$? ($i = 1,\ldots,M$)

2. TODO time, or inconsistency?
