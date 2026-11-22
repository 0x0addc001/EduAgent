# EduAgent

**A tutoring agent that grounds answers in the curriculum and grades against the rubric.**

EduAgent explains with the course material in hand, grades against the rubric instead of
fluency, and hands at-risk learners to a human teacher.

| Stage | Responsibility |
|---|---|
| Data | Slides, textbooks, rubrics, learner submissions |
| Model | Tutor model + retrieval over the curriculum |
| Training | SFT on tutoring dialogues, DPO on pedagogy preferences |
| Inference | Streaming explanations and step-by-step hints |
| Harness | LMS, grading, scheduling, plagiarism tools |
| Eval | Answer correctness, hint quality, learning gain |
| Ops | Class SLOs, safeguarding alerts, teacher review |

## Non-negotiables

1. Every answer cites the syllabus or the learner's own work.
2. Grades come from the rubric, not from confident wording.
3. At-risk learners and grade appeals escalate to a human teacher.

Project page: <https://0x0addc001.github.io/EduAgent/>
