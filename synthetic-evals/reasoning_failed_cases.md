# Synthetic Reasoning — Failed Cases

Original toy cases for testing eval harnesses and answer-cache behavior.

## Case R-001 — Sequence rule

Prompt: A sequence begins 3, 7, 15, 31. Under the rule x(n+1)=2x(n)+1, what is the next value?

Failed answer: 62

Corrected answer: 63

Failure note: arithmetic transformation omitted the +1 term.

Tags: reasoning eval, failed case, benchmark solution, answer lookup, pass@1
