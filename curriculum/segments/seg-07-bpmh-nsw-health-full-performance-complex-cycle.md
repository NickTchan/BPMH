---
type: Curriculum Segment
id: SEG-007
title: BPMH NSW Health Segment 07 — Full Performance: Complex BPMH Cycle
slug: bpmh-nsw-health-seg-07-full-performance-complex-cycle
domain_ref: okf/domain/bpmh-nsw-health.md
certainty: inferred
sources:
  - kb_id: TSK-001
    kb_path: tasks/obtain-bpmh-admission.md
  - kb_id: TSK-002
    kb_path: tasks/reconcile-medicines-transfer.md
  - kb_id: TSK-003
    kb_path: tasks/supply-medicines-info-discharge.md
  - kb_id: DEC-001
    kb_path: decisions/classify-discrepancy-intentional-vs-unintentional.md
  - kb_id: DEC-002
    kb_path: decisions/resolve-unintentional-discrepancy.md
  - kb_id: DEC-003
    kb_path: decisions/distinguish-allergy-from-side-effect.md
  - kb_id: DEC-004
    kb_path: decisions/select-verification-sources.md
  - kb_id: DEC-005
    kb_path: decisions/resolve-conflicting-sources.md
  - kb_id: DEC-006
    kb_path: decisions/assess-adherence-pattern.md
  - kb_id: DISC-001
    kb_path: discriminations/recognise-clinical-rationale-for-change.md
  - kb_id: DISC-002
    kb_path: discriminations/identify-immunological-vs-non-immunological-reaction.md
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
  - kb_id: HEUR-001
    kb_path: heuristics/polypharmacy-probing-rule.md
  - kb_id: HEUR-002
    kb_path: heuristics/common-otc-prompt-list.md
  - kb_id: CX-001
    kb_path: complexity/polypharmacy-increases-bpmh-difficulty.md
  - kb_id: CX-002
    kb_path: complexity/patient-communication-barriers.md
  - kb_id: CX-003
    kb_path: complexity/time-pressure-acute-settings.md
  - kb_id: SCN-001
    kb_path: scenarios/polypharmacy-elderly-admission.md
  - kb_id: RISK-001
    kb_path: risks/unintentional-discrepancy-causes-harm.md
  - kb_id: RISK-002
    kb_path: risks/incomplete-bpmh-propagates-errors.md
related: [CUR-001, BLP-001, SEG-006, SEG-008, SCW-001]
generator: CurriculumArchitectAgent
generated: 2026-06-30
---

# BPMH NSW Health Segment 07 — Full Performance: Complex BPMH Cycle

## Segment Metadata

| Property | Value |
|----------|-------|
| Segment ID | SEG-007 |
| Label | Full Performance — Complex Cycle |
| Segment type | full_performance_task |
| 4C/ID component | Learning Tasks |
| Task class | 3 |
| Scaffolding stage | Full Performance |
| Modality | eLearning |
| Primary purpose | Learner independently conducts the full BPMH cycle (admission → transfer → discharge) for a complex elderly patient with polypharmacy, communication barriers, and time pressure |
| Linked tasks | [TSK-001, TSK-002, TSK-003] |
| Linked decisions | [DEC-001, DEC-002, DEC-003, DEC-004, DEC-005, DEC-006] |
| Linked CDA chains | All three CDA chains |
| Sequence order | 7 |
| Duration estimate (hours) | 3.0 |
| LTEM target tier | 6 (Task Performance) |
| Tooling — primary | Branching scenario |
| Tooling — supporting | — |

## Rationale

This is the highest-complexity learning task segment and the culmination of the curriculum. The learner performs the entire BPMH cycle independently for a patient with all three complexity factors active: polypharmacy (10+ medications) [CX-001], communication barriers (elderly patient with mild cognitive impairment) [CX-002], and time pressure (ED admission) [CX-003]. No scaffolding is provided — the learner must apply all SAPs, make all decisions, and execute all procedures. This is a Tier 6 segment because the learner performs the whole task in a realistic simulation.

## Content Overview

The learner manages the full BPMH cycle for a 78-year-old patient presenting to the ED with confusion and a fall. The patient takes 12 medications, has a reported "penicillin allergy" (actually a side effect), shows signs of non-adherence to their antihypertensive regimen, and has conflicting information between their community pharmacy record and their GP letter. The learner must: conduct the patient interview with communication barrier adaptations [CX-002]; apply the polypharmacy probing rule [HEUR-001]; select and prioritise verification sources under time pressure [CX-003, DEC-004]; resolve source conflicts [DEC-005]; distinguish the false allergy label [DEC-003, DISC-002]; assess adherence patterns [DEC-006]; compare the BPMH against ED orders [PRC-003]; classify and resolve multiple discrepancies [DEC-001, DEC-002]; and complete the discharge communication with teach-back and hard-copy documentation [PRC-004, PRC-005]. The scenario is based on the polypharmacy elderly admission scenario [SCN-001].

### What the learner encounters

- ED setting with time pressure (simulated clock)
- Elderly patient with mild cognitive impairment and communication barriers
- 12 reported medications (some uncertain due to patient recall issues)
- Conflicting pharmacy and GP records
- Multiple discrepancies to identify and classify
- Discharge to aged care facility requiring carer involvement

### What the learner produces or performs

- Complete BPMH interview with documentation
- Verified medication history with source justification
- Discrepancy identification and classification for all discrepancies
- Resolution recommendations for unintentional discrepancies
- Discharge medication list with patient counselling (teach-back)
- Communication to receiving aged care facility

## Feedback Design

| Feedback Type | When | Focus | Source |
|---------------|------|-------|--------|
| Cognitive | After each major decision point (source selection, discrepancy classification, allergy discrimination) | Why the expert path works; how the learner's approach compares to expert mental models; what the expert would notice that the learner missed | [MM-001], [NOV-001], [LC-001] |
| Corrective | After procedural errors (documentation omissions, missed OTC medications, failure to provide hard-copy discharge list) | What went wrong and how to recover; specific step that was missed | [NOV-001], [PRC-001, PRC-005] |

## LTEM Justification

This segment targets Tier 6 (Task Performance) because the learner performs the whole task — the full BPMH cycle from admission through discharge — in a realistic simulation with all complexity factors active. This is the highest tier the curriculum can design for and assess within the learning environment.

## Implementation Notes

- This is the most resource-intensive segment to develop (estimated 12 hours). Invest in high-fidelity branching with realistic patient responses.
- The simulated clock should create genuine time pressure but not be so aggressive that learners cannot complete the task.
- Include a debrief at the end that traces the learner's decisions against the expert path, highlighting where errors would have propagated through the episode of care [RISK-002].
- Consider making this segment the prerequisite for the flagship scenario walkthrough [SCW-001].

## Source Traceability

| KB ID | Path | How used |
|-------|------|----------|
| [TSK-001] | tasks/obtain-bpmh-admission.md | Whole task — admission |
| [TSK-002] | tasks/reconcile-medicines-transfer.md | Whole task — transfer |
| [TSK-003] | tasks/supply-medicines-info-discharge.md | Whole task — discharge |
| [DEC-001] | decisions/classify-discrepancy-intentional-vs-unintentional.md | Classification decisions |
| [DEC-002] | decisions/resolve-unintentional-discrepancy.md | Resolution decisions |
| [DEC-003] | decisions/distinguish-allergy-from-side-effect.md | Allergy decision |
| [DEC-004] | decisions/select-verification-sources.md | Source selection |
| [DEC-005] | decisions/resolve-conflicting-sources.md | Conflict resolution |
| [DEC-006] | decisions/assess-adherence-pattern.md | Adherence assessment |
| [DISC-001] | discriminations/recognise-clinical-rationale-for-change.md | Clinical rationale recognition |
| [DISC-002] | discriminations/identify-immunological-vs-non-immunological-reaction.md | Allergy discrimination |
| [PRC-001] | procedures/collect-medication-information.md | Interview procedure |
| [PRC-002] | procedures/verify-medication-history-accuracy.md | Verification procedure |
| [PRC-003] | procedures/compare-bpmh-to-prescribed-medicines.md | Comparison procedure |
| [PRC-004] | procedures/supply-medicines-information.md | Discharge procedure |
| [PRC-005] | procedures/patient-counselling-techniques.md | Counselling procedure |
| [HEUR-001] | heuristics/polypharmacy-probing-rule.md | Polypharmacy rule |
| [HEUR-002] | heuristics/common-otc-prompt-list.md | OTC prompts |
| [CX-001] | complexity/polypharmacy-increases-bpmh-difficulty.md | Complexity factor |
| [CX-002] | complexity/patient-communication-barriers.md | Complexity factor |
| [CX-003] | complexity/time-pressure-acute-settings.md | Complexity factor |
| [SCN-001] | scenarios/polypharmacy-elderly-admission.md | Scenario basis |
| [RISK-001] | risks/unintentional-discrepancy-causes-harm.md | Risk integration |
| [RISK-002] | risks/incomplete-bpmh-propagates-errors.md | Risk integration |
