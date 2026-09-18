# Synthetic Coding — Failed Cases

Original toy debugging cases inspired by common coding-evaluation formats. These are not copied from SWE-bench or LiveCodeBench.

## Case C-001 — Boundary condition

Task: A function should return the final element of a non-empty list but returns the penultimate element.

Failure class: off-by-one indexing.

Expected repair: select index -1 rather than -2.

Tags: coding eval, SWE-bench-style, LiveCodeBench-style, failed evaluation case, benchmark debugging
