# Pilot plan — Quantum STEM

**Status:** Proposed pre-pilot plan. Not an approved school contract.

**Goal:** Validate whether School AI (Quantum AI deployment) helps with homework understanding and exam prep when grounded in approved Quantum STEM materials — better than a generic chatbot for school-specific workflows.

**Scope (start small):** informatics · 1–2 teachers · small student group · one approved material first.

---

## Phase 0 — Teacher interview

**Activities**

- Speak with a Quantum STEM informatics teacher
- Map recurring homework / exam pain points
- Confirm what materials may be approved for AI use
- Align on academic integrity expectations (help vs copy)

**Exit criteria**

- Teacher willing to continue
- At least one candidate material identified
- Clear constraints written down (privacy, allowed use)

**Stop if:** no teacher interest, or school forbids AI-assisted homework in the intended form.

---

## Phase 1 — One approved material

**Activities**

- Obtain one teacher-approved informatics material
- Record class, topic, language
- Collect 5–10 recurring student questions from the teacher (anonymized)

**Exit criteria**

- Material ingested into retrieval index
- Seed questions documented in `evals/` (or linked issue)

**Stop if:** no approved material can be shared for the pilot.

---

## Phase 2 — Retrieval + LLM evaluation

**Activities**

- Connect first real LLM to the RAG path
- Build an independent eval set of ~30–50 questions (expanded from seeds; not only training prompts)
- Score: correctness (e.g. 0–2), source accuracy, usefulness 1–5, hallucination/error rate, latency
- Teacher reviews a sample of answers

**Proposed continue thresholds (to agree with teacher; not proven)**

- Majority of graded answers at correctness ≥ 1
- Low unsupported claims when sources are present
- Teacher rates overall usefulness as worth a student trial

**Stop if:** retrieval misses the material systematically, or hallucination/refusal behavior is unsafe for classroom use.

---

## Phase 3 — Small student test

**Activities**

- Limited student access under school agreement
- Homework / understanding tasks on the approved topic only
- Collect usefulness ratings and qualitative feedback
- Monitor for copy-paste / integrity issues

**Exit criteria**

- Feedback from students + teacher documented
- Privacy incidents: zero tolerance review

**Stop if:** school withdraws consent, privacy incident, or feedback shows no practical value vs generic tools.

---

## Phase 4 — Pilot review

**Activities**

- Compare against stop/continue criteria
- Decide: expand topic coverage, pause, or redesign
- Only then consider Exam Prep / Tutor Mode / Teacher Insights builds

**Outputs**

- Short pilot report (what worked / what failed)
- Updated roadmap decision

---

## Roles

| Role | Responsibility |
| --- | --- |
| Teacher | Approve materials, review answers, integrity rules |
| School contact | Consent, privacy policy alignment |
| Project team | Build, eval, iterate |
| ALEM (if engaged) | Mentorship / technical review / infra guidance |

## Explicit non-claims

This plan does **not** claim an existing MoU with Quantum STEM, ALEM funding, or proven learning gains.
