---
type: Curriculum Segment
id: SEG-008
title: BPMH NSW Health Segment 08 — Procedural Instruction: Documentation, Comparison and Discharge
slug: bpmh-nsw-health-seg-08-procedural-instruction
domain_ref: okf/domain/bpmh-nsw-health.md
certainty: inferred
sources:
  - kb_id: PRC-001
    kb_path: procedures/collect-medication-information.md
  - kb_id: PRC-002
    kb_path: procedures/verify-medication-history-accuracy.md
  - kb_id: PRC-003
    kb_path: procedures/compare-bpmh-to-prescribed-medicines.md
  - kb_id: PRC-004
    kb_path: procedures/supply-medicines-information.md
  - kb_id: PRC-005
    kb_path: procedures/patient-counselling-techniques.md
  - kb_id: CON-001
    kb_path: concepts/best-possible-medication-history.md
  - kb_id: CON-003
    kb_path: concepts/medication-discrepancy.md
related: [CUR-001, BLP-001, SEG-007, SEG-009]
generator: CurriculumArchitectAgent
generated: 2026-06-30
---

# BPMH NSW Health Segment 08 — Procedural Instruction: Documentation, Comparison and Discharge

## Segment Metadata

| Property | Value |
|----------|-------|
| Segment ID | SEG-008 |
| Label | Procedural Instruction |
| Segment type | procedural_instruction |
| 4C/ID component | Procedural Information |
| Task class | All |
| Scaffolding stage | N/A |
| Modality | eLearning |
| Primary purpose | Teach step-by-step procedures for documentation, BPMH comparison, discharge list preparation, and patient counselling |
| Linked tasks | [TSK-001, TSK-002, TSK-003] |
| Linked decisions | [] |
| Linked CDA chains | All three CDA chains (procedural steps only) |
| Sequence order | 8 |
| Duration estimate (hours) | 0.75 |
| LTEM target tier | 4 (Knowledge) |
| Tooling — primary | LMS module |
| Tooling — supporting | — |

## Rationale

This segment provides the just-in-time procedural information that learners need to execute the routine aspects of BPMH: documenting medication information, performing line-by-line comparison, preparing discharge lists, and applying counselling techniques. These are routine skills (always performed the same way) that are coupled to individual learning tasks and will fade as proficiency increases.

## Content Overview

This segment presents the step-by-step procedures for four routine aspects of BPMH. First, the documentation procedure: recording name, dose, frequency, route, and indication for each medication [PRC-001, PRC-002]. Second, the comparison procedure: line-by-line comparison of BPMH against current orders, documenting all discrepancies without yet classifying them [PRC-003]. Third, the discharge list procedure: compiling the final reconciled list, identifying commenced/ceased/changed medications, and documenting reasons for changes [PRC-004]. Fourth, the patient counselling procedure: preparing written materials, delivering the session with contrastive language, applying teach-back, providing hard-copy documentation, and addressing special circumstances [PRC-005]. The segment also covers the role division in NSW Health EMR workflow (pharmacist prepares BPMH, prescriber executes EMR reconciliation) [PRC-003].

### What the learner encounters

- Documentation procedure with required fields [PRC-001, PRC-002]
- Line-by-line comparison procedure [PRC-003]
- EMR role division: pharmacist vs. prescriber responsibilities [PRC-003]
- Discharge list preparation procedure [PRC-004]
- Patient counselling procedure with teach-back and hard-copy mandate [PRC-005]
- Special circumstances: cognitive impairment, non-English speakers, telehealth [PRC-005]

### What the learner produces or performs

- Completes a documentation exercise: records medication information from a patient interview transcript
- Performs a line-by-line comparison exercise: identifies discrepancies between a BPMH and medication orders
- Prepares a discharge medication list from a reconciled medication record

## Feedback Design

| Feedback Type | When | Focus | Source |
|---------------|------|-------|--------|
| Corrective | After documentation exercise | What fields were missed or incorrectly recorded | [NOV-001] |
| Corrective | After comparison exercise | Which discrepancies were missed; how to perform systematic line-by-line comparison | [NOV-001] |
| Corrective | After discharge list exercise | Whether commenced/ceased/changed medications were correctly identified | [PRC-004] |

## LTEM Justification

This segment targets Tier 4 (Knowledge) because the learner comprehends step-by-step procedures and demonstrates understanding through structured exercises. The learner is not yet making decisions in context — they are learning the "how-to" that will be applied during learning task segments.

## Implementation Notes

- Use interactive exercises with immediate corrective feedback.
- The EMR role division section should note that local workflow may vary by LHD [PRC-003].
- The counselling procedure should include audio examples of contrastive language ("This is the same drug, just in a different package" vs. "We don't want you to take that one anymore").
- This segment can be completed in parallel with Segments 05–06, as procedural information supports learning tasks at all complexity levels.

## Source Traceability

| KB ID | Path | How used |
|-------|------|----------|
| [PRC-001] | procedures/collect-medication-information.md | Documentation procedure |
| [PRC-002] | procedures/verify-medication-history-accuracy.md | Verification procedure |
| [PRC-003] | procedures/compare-bpmh-to-prescribed-medicines.md | Comparison procedure and role division |
| [PRC-004] | procedures/supply-medicines-information.md | Discharge list procedure |
| [PRC-005] | procedures/patient-counselling-techniques.md | Counselling procedure |
| [CON-001] | concepts/best-possible-medication-history.md | BPMH definition (prerequisite knowledge) |
| [CON-003] | concepts/medication-discrepancy.md | Discrepancy types (prerequisite knowledge) |
