---
type: Curriculum Segment
id: SEG-005
title: BPMH NSW Health Segment 05 — Worked Example: Simple BPMH Interview
slug: bpmh-nsw-health-seg-05-worked-example-simple-bpmh
domain_ref: okf/domain/bpmh-nsw-health.md
certainty: inferred
sources:
  - kb_id: TSK-001
    kb_path: tasks/obtain-bpmh-admission.md
  - kb_id: PRC-001
    kb_path: procedures/collect-medication-information.md
  - kb_id: PRC-002
    kb_path: procedures/verify-medication-history-accuracy.md
  - kb_id: HEUR-002
    kb_path: heuristics/common-otc-prompt-list.md
  - kb_id: DEC-003
    kb_path: decisions/distinguish-allergy-from-side-effect.md
  - kb_id: DISC-002
    kb_path: discriminations/identify-immunological-vs-non-immunological-reaction.md
  - kb_id: MM-001
    kb_path: mentalmodels/bpmh-as-diagnostic-conversation.md
  - kb_id: LC-001
    kb_path: learningcurve/bpmh-skill-progression.md
related: [CUR-001, BLP-001, SEG-004, SEG-006]
generator: CurriculumArchitectAgent
generated: 2026-06-30
---

# BPMH NSW Health Segment 05 — Worked Example: Simple BPMH Interview

## Segment Metadata

| Property | Value |
|----------|-------|
| Segment ID | SEG-005 |
| Label | Worked Example — Simple BPMH |
| Segment type | worked_example |
| 4C/ID component | Learning Tasks |
| Task class | 1 |
| Scaffolding stage | Worked Example |
| Modality | eLearning |
| Primary purpose | Learner studies an expert conducting a BPMH interview for a patient on 2 medications, with expert reasoning narrated at each decision point |
| Linked tasks | [TSK-001] |
| Linked decisions | [DEC-003] |
| Linked CDA chains | Chain for [TSK-001] Steps 1–4 |
| Sequence order | 5 |
| Duration estimate (hours) | 1.0 |
| LTEM target tier | 4 (Knowledge) |
| Tooling — primary | Branching scenario (view-only mode) |


## Rationale

This is the first learning task segment and the first worked example in the curriculum. It introduces the learner to the whole task of obtaining a BPMH [TSK-001] in its simplest form: a cooperative patient on 2 medications with no complexity factors active. The expert narrates their reasoning at each step, modelling the diagnostic conversation approach [MM-001] rather than a checklist exercise. This establishes the expert mental model before the learner attempts any performance.

## Content Overview

The learner watches an expert pharmacist conduct a BPMH interview with a middle-aged patient admitted electively for a scheduled procedure. The patient takes two chronic medications (metformin and atorvastatin). The expert demonstrates: open-ended questioning followed by prompted recall using the OTC prompt list [HEUR-002]; probing for an reported "allergy" to codeine and distinguishing it from a side effect [DEC-003, DISC-002]; verifying against a pharmacy dispensing record [PRC-002]; and documenting the verified BPMH. At each decision point, the expert's reasoning is narrated: why they asked certain follow-up questions, how they interpreted the patient's responses, and why they chose the verification sources they did.

### What the learner encounters

- Expert-conducted BPMH interview with narrated reasoning
- Open-ended questioning technique [PRC-001]
- OTC prompt list application [HEUR-002]
- Allergy probing and discrimination [DEC-003, DISC-002]
- Verification source selection for a simple case [PRC-002]
- Expert narration of the diagnostic conversation mental model [MM-001]

### What the learner produces or performs

- No performance required — learner studies the worked example
- Optional: learner annotates the interview transcript, identifying decision points and the expert's reasoning

## Feedback Design

No learner feedback in this segment — learner studies the worked example. The expert narration serves as embedded cognitive feedback, explaining *why* each decision was made.

## LTEM Justification

This segment targets Tier 4 (Knowledge) because the learner studies and comprehends the expert's approach without yet performing. The worked example provides a model of competent performance that the learner internalises before attempting completion tasks or full performance.

## Implementation Notes

- Use video or audio with transcript for the interview simulation.
- Include "pause points" where the expert's reasoning is revealed — this allows the learner to predict what the expert would do before seeing the answer.
- Keep the scenario simple (2 medications, cooperative patient) to avoid cognitive overload during this first exposure to the whole task.
- The expert narration should explicitly contrast the diagnostic conversation approach with a checklist approach [MM-001].

## Source Traceability

| KB ID | Path | How used |
|-------|------|----------|
| [TSK-001] | tasks/obtain-bpmh-admission.md | Whole task being demonstrated |
| [PRC-001] | procedures/collect-medication-information.md | Interview procedure steps |
| [PRC-002] | procedures/verify-medication-history-accuracy.md | Verification procedure |
| [HEUR-002] | heuristics/common-otc-prompt-list.md | OTC prompting |
| [DEC-003] | decisions/distinguish-allergy-from-side-effect.md | Allergy decision point |
| [DISC-002] | discriminations/identify-immunological-vs-non-immunological-reaction.md | Allergy discrimination |
| [MM-001] | mentalmodels/bpmh-as-diagnostic-conversation.md | Expert mental model |
| [LC-001] | learningcurve/bpmh-skill-progression.md | Novice-to-expert progression context |
