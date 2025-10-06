---
title: "Number Project & Cats "
date: 2025-09-01
draft: false
weight: 1
---

## Overview
Number Project (with Prof. Robin Hillyard), 2024–present

[Robin Hillyard](https://coe.northeastern.edu/people/hillyard-robin/)

[Number GitHub Repo](https://github.com/rchillyard/Number)

## Current Work
✅ I integrated Cats😺 into the Number project by adding cats-kernel/core and providing type class instances: Eq/Order/Show for Rational, Order/Show/Eq for ExactNumber, and PartialOrder/Eq/Show for Number (favoring PartialOrder to respect fuzzy/NaN semantics).

✅ I wrote a Discipline-based law tests for them.

✅ I separated the error scalars of the fuzzy number into two distinct monoids—more precisely, CommutativeMonoids—one is CommutativeMonoid[AbsSigma] and the other is CommutativeMonoid[RelSigma].
Decoupled parallel: nominal accumulation and sigma folding run independently.

⏳ Writer+Eval simplification pipeline: records each step of the four stages of simplify as a log, and finally outputs (result, log).


## Publications
Writing....