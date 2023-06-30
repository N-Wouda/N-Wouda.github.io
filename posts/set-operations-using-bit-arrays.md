<!--
.. title: Set operations using bit arrays
.. slug: set-operations-using-bit-arrays
.. date: 2023-06-30 15:31:24 UTC+02:00
.. tags: 
.. category: 
.. has_math: true
.. link: 
.. description: 
.. type: text
-->

Let $X, Y \subseteq \lbrace 0, 1, \ldots, N \rbrace$.
These sets can be written in equivalent form as bit arrays of size $N + 1$.
Let $x$ be the bit array form of $X$ (and similarly, $y$ of $Y$): the bit $x_i$ is flipped iff $i \in X$, and not set otherwise (where $i \in \lbrace 0, \ldots, N \rbrace$).
Such bit arrays enable the following set operations:

- The *membership* test of $i \in X$ is given by ``(x >> i) & 1``.
- The *complement* $X^\complement$ is given by ``~x``.
- The *intersection* $X \cap Y$ is given by ``x & y``.
- The *union* $X \cup Y$ is given by ``x | y``.
- The *relative complement* $X \setminus Y$ is given by ``x & ~y``.
- The *symmetric difference* $X~\Delta~Y$ is given by ``(x & ~y) | (y & ~x)``, which is equivalent to ``x ^ y``.

These operations can be performed very efficiently in hardware, which sometimes offers substantial performance gains over other approaches (e.g., those based on hash sets).
