# Architecture decisions

Public, English version of a selected architecture decision record (ADR) by Thiago Ribeiro. It states what was decided, what was rejected, what was measured and what failed.

| ADR | Topic | Status |
|---|---|---|
| [ADR-023](ADR-023-brand-fidelity-evaluation.md) | How to evaluate whether a multi-agent system follows a brand book, including an LLM judge that failed calibration | Accepted with a change. Measured on 48 outputs |

Related public work: [ea-impact-matrix](https://github.com/biotbone/ea-impact-matrix), a Claude skill that builds an Enterprise Architecture impact matrix from proposal documents, with a test suite.

## Read this first

- These are condensed from longer private notes. The lab code (harness, Terraform, broker) is not published, so the numbers describe my own runs and cannot be reproduced from this repository.
- All data in the experiments is synthetic. No client data appears anywhere.
- Where a result is negative, it is kept. ADR-023 records four failed hypotheses on purpose.

MIT licence, see `LICENSE`.
