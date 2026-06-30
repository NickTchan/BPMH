---
type: Curriculum Segment
id: SEG-001
title: BPMH NSW Health Segment 01 — Knowledge Foundations
slug: bpmh-nsw-health-seg-01-knowledge-foundations
domain_ref: okf/domain/bpmh-nsw-health.md
certainty: inferred
sources:
  - kb_id: CON-001
    kb_path: concepts/best-possible-medication-history.md
  - kb_id: CON-002
    kb_path: concepts/medication-reconciliation.md
  - kb_id: CON-003
    kb_path: concepts/medication-discrepancy.md
  - kb_id: CON-004
    kb_path: concepts/transfer-of-care.md
  - kb_id: TSK-001
    kb_path: tasks/obtain-bpmh-admission.md
  - kb_id: TSK-002
    kb_path: tasks/reconcile-medicines-transfer.md
  - kb_id: TSK-003
    kb_path: tasks/supply-medicines-info-discharge.md
  - kb_id: EXP-001
    kb_path: experts/bpmh-clinician-nsw.md
  - kb_id: NOV-001
    kb_path: novice-calibration/bpmh-novice-definition.md
related: [CUR-001, BLP-001, SEG-002]
generator: CurriculumArchitectAgent
generated: 2026-06-30
---

# BPMH NSW Health Segment 01 — Knowledge Foundations

## Segment Metadata

| Property | Value |
|----------|-------|
| Segment ID | SEG-001 |
| Label | Knowledge Foundations |
| Segment type | knowledge_foundations |
| 4C/ID component | Supportive Information (domain models) |
| Task class | All |
| Scaffolding stage | N/A |
| Modality | eLearning |
| Primary purpose | Establish foundational conceptual knowledge of BPMH, medication reconciliation, and the three whole tasks |
| Linked tasks | [TSK-001, TSK-002, TSK-003] |
| Linked decisions | [] |
| Linked CDA chains | N/A |
| Sequence order | 1 |
| Duration estimate (hours) | 0.5 |
| LTEM target tier | 4 (Knowledge) |
| Tooling — primary | LMS module |
| Tooling — supporting | — |

## Rationale

This segment provides the conceptual foundation upon which all subsequent segments build. Before learners can perform BPMH tasks or make classification decisions, they must understand what a BPMH is, how it fits into the four-step medication reconciliation process, what types of discrepancies exist, and where transfers of care occur. This segment addresses the "what" before the "how" and "why."

## Content Overview

This segment introduces the core concepts of the BPMH domain. Learners encounter the definition of a Best Possible Medication History [CON-001], the four-step medication reconciliation process (Collect → Confirm → Compare → Supply) [CON-002], the classification of medication discrepancies (intentional vs. unintentional; omission, commission, dose error, duplication) [CON-003], and the types of transfer of care that trigger reconciliation [CON-004]. The segment also introduces the archetypal BPMH practitioner [EXP-001] and the novice baseline [NOV-001] to set expectations for skill development.

### What the learner encounters

- Definition and scope of BPMH [CON-001]
- Four-step medication reconciliation process [CON-002]
- Medication discrepancy types and classification [CON-003]
- Transfer of care points and their significance [CON-004]
- The three whole tasks: admission [TSK-001], transfer [TSK-002], discharge [TSK-003]
- Archetypal BPMH practitioner profile [EXP-001]
- Novice baseline and common errors [NOV-001]

### What the learner produces or performs

- Identifies BPMH components from a list of medication information types
- Matches discrepancy types to examples
- Identifies transfer of care points in a patient journey scenario

## Feedback Design

| Feedback Type | When | Focus | Source |
|---------------|------|-------|--------|
| Corrective | After knowledge check questions | What the correct answer is and why the learner's answer was incorrect | [NOV-001] |

## LTEM Justification

This segment targets Tier 4 (Knowledge) because the learner comprehends and recalls foundational definitions, concepts, and process steps before progressing to application. The segment does not require decision-making or task performance — it establishes the conceptual vocabulary and framework that all subsequent segments depend on.

## Implementation Notes

- Keep this segment concise (30 minutes maximum) — it is foundational but not the focus of the curriculum.
- Use interactive elements (drag-and-drop matching, scenario-based identification) rather than static text to maintain engagement.
- Include a brief knowledge check at the end to confirm comprehension before learners proceed to Segment 02.

## Source Traceability

| KB ID | Path | How used |
|-------|------|----------|
| [CON-001] | concepts/best-possible-medication-history.md | BPMH definition and characteristics |
| [CON-002] | concepts/medication-reconciliation.md | Four-step process definition |
| [CON-003] | concepts/medication-discrepancy.md | Discrepancy types and classification |
| [CON-004] | concepts/transfer-of-care.md | Transfer of care types |
| [TSK-001] | tasks/obtain-bpmh-admission.md | Whole task 1 overview |
| [TSK-002] | tasks/reconcile-medicines-transfer.md | Whole task 2 overview |
| [TSK-003] | tasks/supply-medicines-info-discharge.md | Whole task 3 overview |
| [EXP-001] | experts/bpmh-clinician-nsw.md | Practitioner profile |
| [NOV-001] | novice-calibration/bpmh-novice-definition.md | Novice baseline |
