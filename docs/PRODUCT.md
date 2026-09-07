# Product

**Product:** School AI  
**First deployment name:** Quantum AI (Quantum STEM School)  
**Stage:** Technical MVP → Pre-pilot

Labels used below:

- **Fact** — true of the project as documented today
- **Hypothesis** — believed, not yet proven
- **To validate** — explicit learning goal for the next experiments

## Users

| Role | Relationship | Notes |
| --- | --- | --- |
| Student | End user | Asks questions, practices, prepares for exams |
| Teacher | End user + gatekeeper | Approves materials, reviews quality, may use insights later |
| School admin | Buyer / approver | Privacy, policy, pilot permission |
| Mentor / lab (e.g. ALEM) | Potential technical partner | Review, mentorship, infrastructure guidance |

### Customer vs user

| | Who | Job |
| --- | --- | --- |
| **User** | Students (primary), teachers (secondary) | Learn / teach with safer school-grounded AI |
| **Customer (hypothesized)** | School or lab program that sponsors a pilot | Improve learning support under school control |

**Hypothesis:** The economic buyer is the school (or a talent lab supporting a school pilot), not the individual student paying out of pocket.  
**To validate:** Who actually decides and funds a pilot after Quantum STEM.

## Jobs to be done

### Student

| Job | Type |
| --- | --- |
| Get unstuck on homework using explanations aligned with class materials | Hypothesis / To validate |
| Understand a difficult topic with steps and sources | Hypothesis / To validate |
| Practice for exams via questions, flashcards, tests | Hypothesis / To validate (mostly post-MVP) |
| Trust that answers come from approved school content | Hypothesis / To validate |

### Teacher

| Job | Type |
| --- | --- |
| Know what materials the AI is allowed to use | Fact (design intent) / To validate in pilot |
| Review whether answers cite the right sources | To validate |
| See aggregated weak topics without reading private chats by default | Future / To validate after core quality |

## Student workflow (target)

1. Open Quantum AI web app
2. Ask a question related to class / homework / exam prep
3. System retrieves from **approved** school knowledge
4. Model generates an answer **with sources** (or refuses if insufficient)
5. Student rates usefulness; optional follow-up

**Fact:** A closed prototype exists for chat + demo-note retrieval + sources UI + usefulness rating + session export.  
**To validate:** Same workflow on real Quantum materials with a connected LLM.

## Teacher workflow (target)

1. Select / approve materials for a topic
2. Optionally provide recurring student questions
3. Review sample answers and source accuracy
4. Decide continue / stop for broader student access
5. Later: view aggregated insights (out of MVP scope)

## Product hypotheses

| ID | Statement | Status |
| --- | --- | --- |
| H1 | Generic AI lacks school-specific material context | Hypothesis |
| H2 | Students already use AI for homework and exam prep | Hypothesis |
| H3 | Approved materials + citations increase usefulness and controllability | Hypothesis |
| H4 | Exam prep is a strong recurring use case | Hypothesis |
| H5 | School-scoped RAG can beat generic chatbots for school tasks when corpus coverage is adequate | Hypothesis |

## Differentiators (design intent)

Compared with a generic chatbot:

1. Built around **one school**, not the open web
2. Uses **teacher-approved** materials and shows sources
3. Can **refuse** when school sources are insufficient
4. Focused on homework / exam-prep workflows
5. Path to **teacher insights** without exposing private conversations by default

These are differentiators **we aim to prove**, not proven advantages.

## MVP scope

### In scope for technical MVP 0.1 — Fact

- Closed web prototype
- Retrieval over demo notes
- Openable sources
- Usefulness rating
- Session export

### In scope for v0.2 / pre-pilot — To validate

- One approved Quantum STEM informatics material
- Connected LLM with source-grounded answers
- Small independent eval set (target 30-50 questions after 5-10 teacher seeds)
- Teacher review of answer quality

### Explicitly out of scope (for now)

- Multi-school marketplace
- Fully autonomous grading / replacing teachers
- Unrestricted internet browsing as the knowledge base
- Production student rollout without school agreement
- Claiming proven learning gains
- Full Exam Prep / Tutor / Teacher Insights product suite before core RAG quality is shown

## Naming

| Term | Meaning |
| --- | --- |
| School AI | Platform / product |
| Quantum AI | First school deployment branding for Quantum STEM |
| Quantum STEM School | First pilot school target |
| ALEM AI Talent Lab | Potential technology / mentorship partner (not a claimed sponsor) |
