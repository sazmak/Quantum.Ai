# Evaluations

Plan for measuring School AI answer quality before claiming pilot success.

## Goal

Build an **independent** evaluation set and score source-grounded answers honestly.

## Planned flow

1. Collect **5–10** teacher-provided recurring questions (anonymized)
2. Expand to an independent set of about **30–50** questions (not only the seed prompts)
3. Run retrieval + LLM (v0.2) against approved Quantum material
4. Score and review with a teacher

## Metrics

| Metric | Notes |
| --- | --- |
| Correctness | Rubric e.g. 0–2 (define with teacher) |
| Source accuracy | Did cited material actually support the answer? |
| Usefulness | 1–5 (student and/or teacher) |
| Hallucination / error rate | Unsupported claims, especially when sources missing |
| Latency | Time to answer |
| Repeat usage | Only if logged under agreed privacy rules |
| Teacher feedback | Qualitative + continue/stop |

## Layout (as artifacts appear)

```text
evals/
  README.md
  rubrics/
  sets/           # question sets (no student PII)
  results/        # scored runs (gitignored locally if sensitive)
```

## Rules

- No fabricated scores in this repository
- No student PII in committed eval sets
- Publish summaries, not raw private conversations

See [docs/PILOT_PLAN.md](../docs/PILOT_PLAN.md) for phase gates.
