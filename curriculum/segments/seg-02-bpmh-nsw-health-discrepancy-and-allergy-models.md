---
type: Curriculum Segment
id: SEG-002
title: BPMH NSW Health Segment 02 — Discrepancy and Allergy Domain Models
slug: bpmh-nsw-health-seg-02-discrepancy-and-allergy-models
domain_ref: okf/domain/bpmh-nsw-health.md
certainty: inferred
sources:
  - kb_id: CON-003
    kb_path: concepts/medication-discrepancy.md
  - kb_id: CON-005
    kb_path: concepts/adverse-drug-reaction.md
  - kb_id: CON-006
    kb_path: concepts/polypharmacy.md
  - kb_id: CON-007
    kb_path: concepts/medication-adherence.md
  - kb_id: DEC-001
    kb_path: decisions/classify-discrepancy-intentional-vs-unintentional.md
  - kb_id: DEC-003
    kb_path: decisions/distinguish-allergy-from-side-effect.md
  - kb_id: DISC-002
    kb_path: discriminations/identify-immunological-vs-non-immunological-reaction.md
  - kb_id: RISK-001
    kb_path: risks/unintentional-discrepancy-causes-harm.md
  - kb_id: RISK-002
    kb_path: risks/incomplete-bpmh-propagates-errors.md
  - kb_id: CX-001
    kb_path: complexity/polypharmacy-increases-bpmh-difficulty.md
related: [CUR-001, BLP-001, SEG-001, SEG-003]
generator: CurriculumArchitectAgent
generated: 2026-06-30
---

# BPMH NSW Health Segment 02 — Discrepancy and Allergy Domain Models

## Segment Metadata

| Property | Value |
|----------|-------|
| Segment ID | SEG-002 |
| Label | Discrepancy and Allergy Models |
| Segment type | domain_model_presentation |
| 4C/ID component | Supportive Information (conceptual + causal models) |
| Task class | 1, 2 |
| Scaffolding stage | N/A |
| Modality | eLearning |
| Primary purpose | Build conceptual and causal models for discrepancy classification, allergy discrimination, and polypharmacy risk |
| Linked tasks | [TSK-001, TSK-002] |
| Linked decisions | [DEC-001, DEC-003] |
| Linked CDA chains | Chain for [TSK-001] Steps 3–4; Chain for [TSK-002] Steps 3–4 |
| Sequence order | 2 |
| Duration estimate (hours) | 0.75 |
| LTEM target tier | 4 (Knowledge) |
| Tooling — primary | LMS module |
| Tooling — supporting | — |

## Rationale

Before learners can classify discrepancies or distinguish allergies from side effects, they need robust conceptual models of what discrepancies are, why they matter, and how allergic reactions differ from intolerances. This segment builds the causal models that connect incomplete BPMH to patient harm [RISK-001, RISK-002] and introduces the polypharmacy complexity factor [CX-001] that drives much of the domain's difficulty.

## Content Overview

This segment deepens the learner's understanding of medication discrepancies and their consequences. It covers the distinction between intentional and unintentional discrepancies [CON-003, DEC-001], the causal chain from unintentional discrepancy to adverse drug event [RISK-001], the distinction between drug allergy and side effect/intolerance [CON-005, DEC-003, DISC-002], the impact of polypharmacy on BPMH complexity [CON-006, CX-001], and the importance of capturing actual medication adherence [CON-007].

### What the learner encounters

- Intentional vs. unintentional discrepancy classification framework [DEC-001]
- Causal model: unintentional discrepancy → adverse drug event [RISK-001]
- Causal model: incomplete BPMH → propagated errors through episode of care [RISK-002]
- Allergy vs. side effect discrimination with perceptual cues [DEC-003, DISC-002]
- Polypharmacy complexity: why ≥5 medications increases difficulty non-linearly [CX-001]
- Medication adherence: actual use vs. prescribed use [CON-007]

### What the learner produces or performs

- Classifies sample discrepancies as intentional or unintentional
- Identifies allergic vs. non-allergic reaction descriptions from patient narratives
- Predicts downstream consequences of an incomplete BPMH in a patient journey

## Feedback Design

| Feedback Type | When | Focus | Source |
|---------------|------|-------|--------|
| Cognitive | After discrepancy classification exercises | Why a discrepancy is classified as intentional or unintentional; how clinical context informs the decision | [DEC-001], [DISC-001] |
| Corrective | After allergy discrimination exercises | What reaction descriptors indicate immunological vs. non-immunological responses | [DISC-002] |

## LTEM Justification

This segment targets Tier 4 (Knowledge) because the learner comprehends conceptual models (discrepancy types, allergy classification) and causal relationships (incomplete BPMH → harm) before progressing to decision-making application. The classification exercises test comprehension of models, not yet independent decision-making in context.

## Implementation Notes

- Use realistic patient narratives for allergy discrimination practice — the learner should hear/read the patient's actual words.
- Include at least one "unclear" allergy case where the patient cannot describe the reaction, to prepare learners for real-world ambiguity.
- The polypharmacy section should include concrete examples showing how complexity increases non-linearly (e.g., 3 medications = 3 potential interactions; 10 medications = 45 potential interactions).

## Source Traceability

| KB ID | Path | How used |
|-------|------|----------|
| [CON-003] | concepts/medication-discrepancy.md | Discrepancy types and clinical significance |
| [CON-005] | concepts/adverse-drug-reaction.md | Allergy vs. side effect definitions |
| [CON-006] | concepts/polypharmacy.md | Polypharmacy definition and relevance |
| [CON-007] | concepts/medication-adherence.md | Adherence concept |
| [DEC-001] | decisions/classify-discrepancy-intentional-vs-unintentional.md | Classification framework and action table |
| [DEC-003] | decisions/distinguish-allergy-from-side-effect.md | Allergy discrimination action table |
| [DISC-002] | discriminations/identify-immunological-vs-non-immunological-reaction.md | Perceptual cues for allergy discrimination |
| [RISK-001] | risks/unintentional-discrepancy-causes-harm.md | Causal model for harm |
| [RISK-002] | risks/incomplete-bpmh-propagates-errors.md | Causal model for error propagation |
| [CX-001] | complexity/polypharmacy-increases-bpmh-difficulty.md | Complexity factor |
