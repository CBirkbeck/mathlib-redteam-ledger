# Mathlib red-team ledger

A browsable list of every issue an LLM-driven adversarial audit found in
[Mathlib](https://github.com/leanprover-community/mathlib4), one declaration at a time.

**Browse it at https://cbirkbeck.github.io/mathlib-redteam-ledger/**

The findings are LLM-generated (Claude, with GPT as a second opinion) and have not been
reviewed by Mathlib maintainers, so treat each one as a claim to check. Each finding records
its Lean evidence, and the critical and major ones also record the second model's attempt to
refute them. The raw data is [`findings.json`](findings.json).

This repository is regenerated from the audit's ledger after each audited file.
