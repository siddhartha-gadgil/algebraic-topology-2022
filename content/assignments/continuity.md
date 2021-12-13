---
title: "Continuity"
date: 2021-09-13
draft: false
---

This assignment is based on material in lectures 7 and 8.

1. Let `$f: X\to Y$` be a function and `$A, B\subset X$`. Prove or disprove the following.
    1. `$f(A\cup B)\subset f(A)\cup f(B)$`.
    2. `$f(A\cup B)\supset f(A)\cup f(B)$`.
    3. `$f(A\cap B)\subset f(A)\cap f(B)$`.
    4. `$f(A\cap B)\supset f(A)\cap f(B)$`.

2. Let `$(X, d_X)$` and `$(Y, d_Y)$` be metric spaces. A map `$f: X\to Y$` is said to be Lipschitz if there exists a constant `$K> 0$` such that `$$\forall p, q\in X,\ d_Y(f(p), f(q)) \leq K d_X(p, q).$$` Prove or disprove the following.
    1. Every Lipschitz map is continuous.
    2. Every continuous map is Lipschitz.

3. Let `$Y$` be a topological space such that for all topological spaces `$X$`, every map `$f: X\to Y$` is continuous. Prove that `$Y$` has the indiscrete topology.

4. Suppose $f: X\to Y$ is a map between topological spaces and $A\subset X$ is a subspace. Prove or disprove the following.
    1. If the restriction $f\vert_A: A \to Y$ is continuous, then for all $x\in A$, $f$ is continuous at $x$.
    2. If, for all $x\in A$, $f$ is continuous at $x$, the restriction $f\vert_A: A \to Y$ is continuous.

5. Let $X$ be a space with the discrete topology. Prove or disprove the following.
    1. If $x\in X$, then any neighbourhood basis of $x$ contains the singleton set $\{x\}$.
    2. Every point has a neighbourhood basis with just one open set.

6. Let `$f, g: X\to \mathbb{R}$` be continuous functions from a topological space to the reals. Prove or disprove that the following must be continuous?
    1. `$\min(f, g)$`.
    2. `$\max(f, g)$`.
    3. `$\vert f\vert - \vert g\vert$`.

