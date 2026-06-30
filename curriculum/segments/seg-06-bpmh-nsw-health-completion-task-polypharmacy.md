---
type: Curriculum Segment
id: SEG-006
title: BPMH NSW Health Segment 06 — Completion Task: Moderate BPMH with Polypharmacy
slug: bpmh-nsw-health-seg-06-completion-task-polypharmacy
domain_ref: okf/domain/bpmh-nsw-health.md
certainty: inferred
sources:
  - kb_id: TSK-001
    kb_path: tasks/obtain-bpmh-admission.md
  - kb_id: TSK-002
    kb_path: tasks/reconcile-medicines-transfer.md
  - kb_id: PRC-001
    kb_path: procedures/collect-medication-information.md
  - kb_id: PRC-002
    kb_path: procedures/verify-medication-history-accuracy.md
  - kb_id: PRC-003
    kb_path: procedures/compare-bpmh-to-prescribed-medicines.md
  - kb_id: DEC-001
    kb_path: decisions/classify-discrepancy-intentional-vs-unintentional.md
  - kb_id: DEC-004
    kb_path: decisions/select-verification-sources.md
  - kb_id: DEC-005
    kb_path: decisions/resolve-conflicting-sources.md
  - kb_id: HEUR-001
    kb_path: heuristics/polypharmacy-probing-rule.md
  - kb_id: CX-001
    kb_path: complexity/polypharmacy-increases-bpmh-difficulty.md
  - kb_id: SCN-003
    kb_path: scenarios/omitted-anticoagulant.md
related: [CUR-001, BLP-001, SEG-005, SEG-007]
generator: CurriculumArchitectAgent
generated: 2026-06-30
---

# BPMH NSW Health Segment 06 — Completion Task: Moderate BPMH with Polypharmacy

## Segment Metadata

| Property | Value |
|----------|-------|
| Segment ID | SEG-006 |
| Label | Completion Task — Polypharmacy |
| Segment type | completion_task |
| 4C/ID component | Learning Tasks |
| Task class | 2 |
| Scaffolding stage | Completion Task |
| Modality | eLearning |
| Primary purpose | Learner completes a partially-performed BPMH for a patient with 6 medications, including one discrepancy to classify and one source conflict to resolve |
| Linked tasks | [TSK-001, TSK-002] |
| Linked decisions | [DEC-001, DEC-004, DEC-005] |
| Linked CDA chains | Chain for [TSK-001] Steps 2, 5–7; Chain for [TSK-002] Steps 2–4 |
| Sequence order | 6 |
| Duration estimate (hours) | 1.5 |
| LTEM target tier | 5 (Decision-Making) |
| Tooling — primary | Branching scenario |
| Tooling — supporting | — |

## Rationale

This segment moves the learner from observation (Segment 05) to partial performance. The polypharmacy complexity factor [CX-001] is introduced: the patient takes 6 medications, triggering the polypharmacy probing rule [HEUR-001]. The expert has already conducted the patient interview; the learner must complete the verification, discrepancy identification, and classification steps. This is a Tier 5 segment because the learner makes decisions in context.

## Content Overview

The learner is presented with a partially-completed BPMH for a 68-year-old patient admitted to the medical ward with heart failure exacerbation. The patient takes 6 medications (frusemide, spironolactone, metoprolol, perindopril, digoxin, warfarin). The expert has already interviewed the patient and documented the reported medications. The learner must: select appropriate verification sources for a polypharmacy patient [DEC-004]; resolve a conflict between the pharmacy record and the patient's report for one medication [DEC-005]; compare the verified BPMH against the current medication orders [PRC-003]; identify one omission discrepancy (warfarin not prescribed); and classify the discrepancy as intentional or unintentional [DEC-001]. The scenario is based on the omitted anticoagulant scenario [SCN-003].

### What the learner encounters

- Partially-completed BPMH with patient interview already done
- Pharmacy dispensing record and GP letter as available verification sources
- Current medication orders in eMR for comparison
- One source conflict (patient reports warfarin 5mg, pharmacy shows 3mg)
- One omission discrepancy (warfarin not in current orders)

### What the learner produces or performs

- Selects verification sources and justifies the choice
- Resolves the source conflict for warfarin dose
- Identifies the warfarin omission discrepancy
- Classifies the discrepancy and recommends a resolution action

## Feedback Design

| Feedback Type | When | Focus | Source |
|---------------|------|-------|--------|
| Cognitive | After source selection | Why polypharmacy requires ≥3 sources; how the expert would prioritise sources in this context | [DEC-004], [HEUR-001] |
| Cognitive | After discrepancy classification | Why the warfarin omission is likely unintentional (no documented rationale, time-critical medication); what the consequences could be | [DEC-001], [RISK-001] |
| Corrective | After source conflict resolution | What the correct approach is when pharmacy and patient reports differ | [DEC-005] |

## LTEM Justification

This segment targets Tier 5 (Decision-Making) because the learner makes discrete decisions in context: selecting verification sources, resolving a source conflict, identifying a discrepancy, and classifying it. The learner is not yet performing the whole task independently (the interview is already done) but is applying SAPs and heuristics to make judgements.

## Implementation Notes

- The scenario should feel realistic: use actual medication names, doses, and eMR-style interfaces.
- The warfarin omission should be time-critical — the patient is at risk of stroke if warfarin is not restarted.
- Include a "hint" system that fades: full hints available on first attempt, reduced hints on second attempt, no hints on third attempt.
- If the learner classifies the discrepancy as intentional without checking for documentation, provide corrective feedback immediately.

## Source Traceability

| KB ID | Path | How used |
|-------|------|----------|
| [TSK-001] | tasks/obtain-bpmh-admission.md | Whole task (admission phase) |
| [TSK-002] | tasks/reconcile-medicines-transfer.md | Whole task (transfer phase) |
| [PRC-001] | procedures/collect-medication-information.md | Interview context |
| [PRC-002] | procedures/verify-medication-history-accuracy.md | Verification procedure |
| [PRC-003] | procedures/compare-bpmh-to-prescribed-medicines.md | Comparison procedure |
| [DEC-001] | decisions/classify-discrepancy-intentional-vs-unintentional.md | Classification decision |
| [DEC-004] | decisions/select-verification-sources.md | Source selection decision |
| [DEC-005] | decisions/resolve-conflicting-sources.md | Conflict resolution decision |
| [HEUR-001] | heuristics/polypharmacy-probing-rule.md | Polypharmacy rule |
| [CX-001] | complexity/polypharmacy-increases-bpmh-difficulty.md | Complexity factor |
| [SCN-003] | scenarios/omitted-anticoagulant.md | Scenario basis |
