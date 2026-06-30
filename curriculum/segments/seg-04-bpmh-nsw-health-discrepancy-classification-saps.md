---
type: Curriculum Segment
id: SEG-004
title: BPMH NSW Health Segment 04 — Discrepancy Classification and Clinical Rationale SAPs
slug: bpmh-nsw-health-seg-04-discrepancy-classification-saps
domain_ref: okf/domain/bpmh-nsw-health.md
certainty: inferred
sources:
  - kb_id: DEC-001
    kb_path: decisions/classify-discrepancy-intentional-vs-unintentional.md
  - kb_id: DEC-002
    kb_path: decisions/resolve-unintentional-discrepancy.md
  - kb_id: DISC-001
    kb_path: discriminations/recognise-clinical-rationale-for-change.md
  - kb_id: GAP-003
    kb_path: gaps/clinical-rationale-recognition-cues.md
  - kb_id: RISK-001
    kb_path: risks/unintentional-discrepancy-causes-harm.md
related: [CUR-001, BLP-001, SEG-002, SEG-003, SEG-005]
generator: CurriculumArchitectAgent
generated: 2026-06-30
---

# BPMH NSW Health Segment 04 — Discrepancy Classification and Clinical Rationale SAPs

## Segment Metadata

| Property | Value |
|----------|-------|
| Segment ID | SEG-004 |
| Label | Discrepancy Classification SAPs |
| Segment type | sap_presentation |
| 4C/ID component | Supportive Information (SAPs) |
| Task class | 2 |
| Scaffolding stage | N/A |
| Modality | eLearning |
| Primary purpose | Teach systematic approaches for classifying discrepancies and recognising clinical rationale |
| Linked tasks | [TSK-001, TSK-002] |
| Linked decisions | [DEC-001, DEC-002] |
| Linked CDA chains | Chain for [TSK-002] Steps 3–4 |
| Sequence order | 4 |
| Duration estimate (hours) | 1.0 |
| LTEM target tier | 5 (Decision-Making) |
| Tooling — primary | LMS module |
| Tooling — supporting | — |

## Rationale

This segment bridges conceptual understanding (Segment 02) and practical application (Segments 05–07). It teaches the SAPs for classifying discrepancies as intentional or unintentional [DEC-001] and resolving unintentional discrepancies [DEC-002], along with the discrimination skill of recognising clinical rationale for medication changes [DISC-001]. This is a Tier 5 segment because learners apply heuristics to make decisions in context, not just recall definitions.

## Content Overview

This segment presents the discrepancy classification framework: check for documented rationale → assess clinical obviousness → if uncertain, discuss with prescriber → classify as intentional or unintentional [DEC-001]. It covers the expert red flags for unintentional discrepancy (no documentation, indication doesn't match presentation, abnormal starting dose, possible wrong-patient dispensing) [GAP-003]. It presents the resolution action table by discrepancy type (omission → add; commission → cease/investigate; dose error → correct; duplication → cease one) [DEC-002]. The segment also addresses the discrimination of recognising when a clinical context makes a medication change obviously intentional [DISC-001].

### What the learner encounters

- Discrepancy classification action table with competing considerations [DEC-001]
- Expert red flags for unintentional discrepancy [GAP-003]
- Investigation pathways: review progress notes → consult prescriber → inquire with nursing staff [DEC-001]
- Unintentional discrepancy resolution action table by type [DEC-002]
- Clinical rationale recognition: obvious intentional vs. unclear cases [DISC-001]

### What the learner produces or performs

- Classifies 5–7 sample discrepancies as intentional or unintentional, with justification
- Recommends resolution actions for classified unintentional discrepancies
- Identifies clinical rationale cues from patient presentation scenarios

## Feedback Design

| Feedback Type | When | Focus | Source |
|---------------|------|-------|--------|
| Cognitive | After classification exercises | Why a discrepancy is classified a certain way; how clinical context and documentation quality inform the decision; comparison of novice vs. expert classification patterns | [DEC-001], [DISC-001], [NOV-001] |
| Corrective | After resolution exercises | What the correct resolution action is for each discrepancy type | [DEC-002] |

## LTEM Justification

This segment targets Tier 5 (Decision-Making) because the learner applies the classification framework and red-flag heuristics to make decisions in context. The learner is not yet performing the whole task but is making discrete classification decisions that require judgement, not just recall.

## Implementation Notes

- Use realistic clinical scenarios with patient presentations, investigation results, and medication charts.
- Include at least one "borderline" case where the clinical rationale is plausible but not certain, to teach learners when to escalate to prescriber discussion.
- The red-flag heuristics from [GAP-003] are probed expert knowledge — present them as expert-validated cues.

## Source Traceability

| KB ID | Path | How used |
|-------|------|----------|
| [DEC-001] | decisions/classify-discrepancy-intentional-vs-unintentional.md | Classification framework and red flags |
| [DEC-002] | decisions/resolve-unintentional-discrepancy.md | Resolution action table |
| [DISC-001] | discriminations/recognise-clinical-rationale-for-change.md | Clinical rationale recognition |
| [GAP-003] | gaps/clinical-rationale-recognition-cues.md | Probed expert red-flag cues |
| [RISK-001] | risks/unintentional-discrepancy-causes-harm.md | Risk context |
