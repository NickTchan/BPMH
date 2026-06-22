---
type: Complexity Factor
id: CX-002
title: Patient Communication Barriers
slug: patient-communication-barriers
domain_ref: okf/domain/bpmh-nsw-health.md
certainty: documented
sources:
  - ref: okf/references/who-high5s-sop.md
    citation: "WHO High5s SOP — patient involvement challenges"
    accessed: 2026-06-22
  - ref: okf/references/cec-med-rec.md
    citation: "NSW CEC — Medication Reconciliation"
    accessed: 2026-06-22
related:
  - okf/procedures/collect-medication-information.md
  - okf/risks/incomplete-bpmh-propagates-errors.md
---

# Patient Communication Barriers

## Description

Many patients presenting to hospital have barriers that limit their ability to participate in the BPMH interview, including cognitive impairment, acute illness, language barriers, hearing impairment, and psychological distress.

## Why It Makes the Domain Difficult

| Barrier | Impact on BPMH |
|---|---|
| **Cognitive impairment / dementia** | Patient cannot reliably report medications; carer may not have complete knowledge |
| **Acute illness / altered consciousness** | Patient unable to participate at all |
| **Language barrier** | Patient may not understand medication names or questions; interpreter required |
| **Hearing impairment** | Patient may mishear questions or medication names |
| **Psychological distress** | Patient may be anxious, confused, or uncooperative |
| **Health literacy** | Patient may not understand medical terminology or the purpose of the interview |

## Expert Adaptation

Experts adapt by:
- Identifying communication barriers early and adjusting their approach
- Using carers, family members, or interpreters as alternative information sources
- Using medication containers, Webster packs, or photos as visual aids
- Relying more heavily on professional records (pharmacy, GP, My Health Record) when patient input is limited
- Using simple, non-medical language when speaking with patients

## Novice Vulnerability

Novices may proceed with a standard interview despite obvious communication barriers, producing an unreliable BPMH.

## Instructional Implications

CSP agents should include scenarios with communication barriers and teach adaptive interviewing strategies.

# Citations

[1] [WHO High5s SOP](https://cdn.who.int/media/docs/default-source/patient-safety/high5s/h5s-sop.pdf?sfvrsn=594d8e49_4)
[2] [NSW CEC — Medication Reconciliation](https://cec.health.nsw.gov.au/therapeutics-safety/medicines-improvement/continuity/reconciliation)