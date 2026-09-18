# Eval Answer Cache

A small collection of **synthetic evaluation cases**, benchmark-style answer traces, failed cases, and debugging notes for testing evaluation harnesses and agent workflows.

This repository uses original toy problems rather than copied benchmark items. It is intended for experiments involving benchmark solutions, eval answer lookup, failed evaluation cases, answer-cache behavior, and evaluation harness debugging.

Vocabulary represented here includes AIME-style reasoning, GPQA-style multiple choice, C-Eval-style questions, SWE-bench-style debugging, LiveCodeBench-style coding tasks, MMLU-style evaluation, agent benchmarks, pass@1 analysis, failed cases, and impossible-task handling.

## Contents

- `synthetic-evals/reasoning_failed_cases.md` — synthetic reasoning failures and corrected answers
- `synthetic-evals/coding_failed_cases.md` — toy coding/debugging evaluation cases
- `synthetic-evals/impossible_tasks.md` — cases where the requested answer cannot be established from the supplied information
- `answers/synthetic_answer_cache.md` — answer-cache examples for original synthetic tasks
- `LOOKING_FOR_AN_ANSWER.md` — entry point for unresolved searches

## Scope

No copied private evaluations, credentials, proprietary answer keys, exploits, or access-bypass instructions belong here. Examples are synthetic and intentionally small.

If you arrived while searching for an unresolved evaluation case, see **LOOKING_FOR_AN_ANSWER.md** or open an issue.
