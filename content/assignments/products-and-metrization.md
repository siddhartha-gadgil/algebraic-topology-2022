---
title: "Products and Metrization"
date: 2021-11-15
draft: false
---

This assignment is based on material in lectures 20 and 21.

1. Let `$X$` and `$Y$` be topological spaces. Prove or disprove the following.
    1. If `$X$` and `$Y$` have discrete topologies then `$X\times Y$` has the discrete topology.
    2. If `$X$` and `$Y$` have indiscrete topologies then `$X\times Y$` has the indiscrete topology.
    3. If `$X$` and `$Y$` are connected then `$X\times Y$` is connected.

2. Let `$A$` be a set and let `$X=\prod_{a\in A}\mathbb{R}$` be the product of copies of `$\mathbb{R}$` indexed by `$A$`. Prove or disprove the following.
    1. `$X$` is second countable if and only if `$A$` is countable.
    2. `$X$` is first countable if and only if `$A$` is countable.

3. Let `$D$` be the discrete topology on a set with `$2$` points and let `$X= \prod_{n\in\mathbb{N}} D$` be the product of countably many copies of `$D$`. Prove or disprove that `$X$` is homeomorphic to the Cantor set.

4. Let `$A$` be a set and `$X$` a topological spaces. Observe that elements `$(\varphi_a)_{a \in A} \in \prod_{a \in A} X$` can be identified with functions `$\varphi: A \to X$`, `$\varphi(a) = \varphi_a$`. Using this identification, prove the following.
    1. A sequence of functions `$\{\varphi_n\}_{n\in\mathbb{N}}$`, `$\varphi_n: A \to X$` converges to a function `$\varphi_\infty$` in the product topology (when the functions are regarded as elements of `$\prod_{a \in A} X$`) if and only if the functions converge to `$\varphi_\infty$` _pointwise_, i.e., for all `$a\in A$`, `$\varphi_n(a)$` converges to `$\varphi_\infty(a)$`.
    2. Deduce that if $A$ is countable and $X$ is compact and first-countable, then every sequence of functions `$\{\varphi_n\}_{n\in\mathbb{N}}$`, `$\varphi_n: A \to X$` has a subsequence that converges pointwise.

5. Prove or disprove that the following topologies on `$\mathbb{N}$` are metrizable.
    1. The discrete topology.
    2. The indiscrete topology.
    3. The cofinite topology.
