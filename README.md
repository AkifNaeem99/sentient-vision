# Sentient Vision

**CS2S567 – Professional Practice & Employability: Team-Based Software Development Workshop**

Project initiation repository for a **facial verification and facial-expression classification** prototype in a recruitment-exercise scenario in South and West Wales.

> **Status:** This repository contains planning materials and documentation templates, not proof of a completed software implementation or live biometric testing.

## Project boundaries

- **Verification stream:** Controlled, consent-led 1:1 facial verification for check-in, with an equally accessible manual alternative.
- **Expression stream:** Five-label facial-expression research (happy, sad, angry, surprise, neutral). **Not** used to judge emotions, engagement, personality or employment suitability.
- **Governance:** No capture or publication of identifiable biometric data until the necessary permissions and legal/data-protection requirements have been established.
- **Dataset:** FER2013's seven original labels require an explicit five-label mapping; excluded classes must be documented.

## Repository structure

| Folder | Purpose |
|---|---|
| `docs/client-brief/` | Scope decisions and formal changes |
| `docs/project-plan/` | WBS tasks, dependencies and milestones |
| `docs/governance/` | Risk register and DPIA questions |
| `docs/evaluation/` | Proposed evaluation evidence |
| `docs/diagrams/` | Editable draw.io architecture, privacy, leadership and Gantt diagrams |
| `src/verify/`, `src/expression/` | Planned separate modules (not yet implemented) |
| `tests/`, `config/`, `reports/` | Tests, safe configuration templates and reports |

## Work management

Use work-item IDs `W1.1–W8.2` with risk IDs `R1–R10`. The agreed working pattern is **daily asynchronous stand-up updates**, **two live team meetings a week**, and a **weekly risk review**. Use independent pull-request review, issue tracking and branch protection when configured.

## Public-repository safeguards

**Do not commit** candidate or participant images, biometric templates, recordings, student IDs, personal reflection data, passwords, access tokens or unpublished assessment content. Public access is not evidence of participant consent, client approval or deployment.

The project report is submitted separately to the university. The team must add genuine implementation evidence and tested results as they become available.
