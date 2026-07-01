---
type: Curriculum Segment
id: SEG-009
title: BPMH NSW Health Segment 09 — "Part-Task Practice: Polypharmacy Probing and Teach-Back"
slug: bpmh-nsw-health-seg-09-part-task-practice
domain_ref: okf/domain/bpmh-nsw-health.md
certainty: inferred
sources:
  - kb_id: HEUR-001
    kb_path: heuristics/polypharmacy-probing-rule.md
  - kb_id: HEUR-002
    kb_path: heuristics/common-otc-prompt-list.md
  - kb_id: PRC-005
    kb_path: procedures/patient-counselling-techniques.md
  - kb_id: LC-001
    kb_path: learningcurve/bpmh-skill-progression.md
related: [CUR-001, BLP-001, SEG-006, SEG-007]
generator: CurriculumArchitectAgent
generated: 2026-06-30
---

# BPMH NSW Health Segment 09 — Part-Task Practice: Polypharmacy Probing and Teach-Back

## Segment Metadata

| Property | Value |
|----------|-------|
| Segment ID | SEG-009 |
| Label | Part-Task Practice |
| Segment type | part_task_practice |
| 4C/ID component | Part-Task Practice |
| Task class | All |
| Scaffolding stage | N/A |
| Modality | eLearning |
| Primary purpose | Build automaticity for polypharmacy probing rule application and teach-back counselling technique through repetitive drill |
| Linked tasks | [TSK-001, TSK-003] |
| Linked decisions | [] |
| Linked CDA chains | Chain for [TSK-001] Step 2; Chain for [TSK-003] Step 3 |
| Sequence order | 9 |
| Duration estimate (hours) | 0.5 |
| LTEM target tier | 5 (Decision-Making) |
| Tooling — primary | Drill module |
| Tooling — supporting | — |

## Rationale

This segment provides repetitive practice for two routine skills that must reach automaticity: the polypharmacy probing rule (instantly recognising ≥5 medications and activating enhanced verification) [HEUR-001] and the teach-back counselling technique (naturally asking patients to repeat instructions in their own words) [PRC-005]. These skills are embedded within larger tasks but must become fast and effortless so they do not compete for cognitive load during complex performance.

## Content Overview

This segment contains two drill modules. The first module presents rapid-fire medication lists of varying lengths (1–15 medications); the learner must instantly identify whether the polypharmacy rule applies and which verification sources to prioritise. The second module presents simulated patient interactions where the learner practices teach-back phrasing with different patient avatars, receiving immediate feedback on whether the phrasing invites genuine comprehension verification vs. yes/no responses. The OTC prompt list [HEUR-002] is also practised: the learner is given prescription lists and must rapidly identify which OTC categories to probe for based on the patient's conditions.

### What the learner encounters

- Rapid-fire medication count drills (15–20 items per session)
- Simulated patient interactions for teach-back practice (8–10 scenarios)
- OTC category identification drills (10–15 items per session)

### What the learner produces or performs

- Instantly classifies medication lists as requiring polypharmacy probing or not
- Produces teach-back questions for different patient scenarios
- Identifies OTC categories to probe for based on patient conditions

## Feedback Design

| Feedback Type | When | Focus | Source |
|---------------|------|-------|--------|
| Corrective | After each drill item | Whether the response was correct; what the correct response is; why | [HEUR-001, HEUR-002, PRC-005] |

## LTEM Justification

This segment targets Tier 5 (Decision-Making) because the learner applies routine skills in context with immediate corrective feedback. The drills are designed to build toward automaticity, but the assessment is whether the learner can apply the skill correctly in varied contexts, not just recall the rule.

## Implementation Notes

- Drills should be short (5–10 minutes each) and repeatable — learners should be able to run them multiple times.
- Use a scoring system that tracks accuracy and response time to measure progress toward automaticity.
- The teach-back module should include audio recording capability so learners can hear their own phrasing.
- This segment should be available throughout the curriculum, not just at this point — learners can return to it for additional practice at any time.

## Source Traceability

| KB ID | Path | How used |
|-------|------|----------|
| [HEUR-001] | heuristics/polypharmacy-probing-rule.md | Polypharmacy probing rule |
| [HEUR-002] | heuristics/common-otc-prompt-list.md | OTC prompt list |
| [PRC-005] | procedures/patient-counselling-techniques.md | Teach-back procedure |
| [LC-001] | learningcurve/bpmh-skill-progression.md | Skill progression context |
