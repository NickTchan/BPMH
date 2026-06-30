---
type: Scenario Walkthrough
id: SCW-001
title: BPMH NSW Health Flagship Walkthrough — Polypharmacy Elderly Admission
slug: bpmh-nsw-health-flagship-walkthrough-polypharmacy-admission
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
  - kb_id: MM-001
    kb_path: mentalmodels/bpmh-as-diagnostic-conversation.md
  - kb_id: HEUR-001
    kb_path: heuristics/polypharmacy-probing-rule.md
  - kb_id: HEUR-002
    kb_path: heuristics/common-otc-prompt-list.md
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
  - kb_id: CX-001
    kb_path: complexity/polypharmacy-increases-bpmh-difficulty.md
  - kb_id: CX-002
    kb_path: complexity/patient-communication-barriers.md
  - kb_id: CX-003
    kb_path: complexity/time-pressure-acute-settings.md
  - kb_id: SCN-001
    kb_path: scenarios/polypharmacy-elderly-admission.md
  - kb_id: SCN-002
    kb_path: scenarios/false-allergy-label.md
  - kb_id: SCN-003
    kb_path: scenarios/omitted-anticoagulant.md
  - kb_id: RISK-001
    kb_path: risks/unintentional-discrepancy-causes-harm.md
  - kb_id: RISK-002
    kb_path: risks/incomplete-bpmh-propagates-errors.md
  - kb_id: NOV-001
    kb_path: novice-calibration/bpmh-novice-definition.md
  - kb_id: LC-001
    kb_path: learningcurve/bpmh-skill-progression.md
  - kb_id: GAP-005
    kb_path: gaps/expert-mental-model-bpmh.md
related: [CUR-001, BLP-001, SEG-007]
generator: CurriculumArchitectAgent
generated: 2026-06-30
---

# BPMH NSW Health Flagship Walkthrough — Polypharmacy Elderly Admission

## Scenario Overview

| Property | Value |
|----------|-------|
| Scenario ID | SCW-001 |
| Task class | 3 (most complex) |
| Scaffolding stage | Full Performance |
| Whole task | [TSK-001], [TSK-002], [TSK-003] |
| LTEM target tier | 6 (Task Performance) |
| Modality | eLearning |
| Tool | Branching scenario platform |

### Core challenge

A 78-year-old patient, Mrs. Margaret Chen, presents to the Emergency Department after a fall at home. She lives alone, has mild cognitive impairment, and takes 12 medications. Her daughter (who is her carer) is present but works full-time and must leave within the hour. The ED is busy, and the treating team needs medication information urgently to make safe prescribing decisions. The learner must obtain a Best Possible Medication History under time pressure, with communication barriers, for a polypharmacy patient — then reconcile the medications at transfer to the medical ward, and finally counsel the patient and daughter at discharge to an aged care facility.

### Performance goal

The learner will obtain a verified BPMH for Mrs. Chen by conducting a patient/carer interview with communication barrier adaptations, selecting and prioritising verification sources under time pressure, resolving conflicting information, and documenting a complete medication history — achieving a BPMH that captures all 12 medications (including 2 OTC products), correctly identifies the false penicillin allergy label, detects the warfarin non-adherence pattern, and classifies all discrepancies — within a simulated 25-minute ED window.

### Success criteria

| Criterion | Novice (from [NOV-001], [LC-001]) | Competent | Expert |
|-----------|-----------------------------------|-----------|--------|
| Medication capture | Records 6–8 of 12 medications; misses OTC and PRN | Records 10–11 medications; identifies most OTC | Records all 12 medications including OTC and PRN |
| Allergy classification | Accepts "penicillin allergy" at face value | Probes for reaction but may misclassify | Correctly identifies as side effect (nausea), not allergy |
| Verification sources | Uses 1–2 sources regardless of complexity | Uses 3 sources for polypharmacy | Uses 4+ sources; prioritises pharmacy dispensing record |
| Discrepancy identification | Identifies 1–2 of 4 discrepancies | Identifies 3 of 4 discrepancies | Identifies all 4 discrepancies |
| Discrepancy classification | Classifies all as unintentional or all as intentional | Classifies 3 of 4 correctly | Classifies all 4 correctly with clinical rationale |
| Adherence detection | Does not detect non-adherence | Detects non-adherence for 1 medication | Detects non-adherence pattern for warfarin and antihypertensive |
| Discharge communication | Verbal-only counselling; no teach-back | Provides hard-copy list; attempts teach-back | Full counselling with teach-back, hard-copy, carer involvement, and follow-up |

## Tool Selection

| Tool | Purpose | Constraint Source |
|------|---------|-----------------|
| Branching scenario platform | Simulates patient interview, eMR interface, verification source access, and discharge counselling | eLearning-only constraint (user-specified) |
| Simulated patient avatar (text/audio) | Provides realistic patient and carer responses with communication barrier characteristics | [CX-002] |
| Simulated eMR interface | Provides medication orders, progress notes, and reconciliation screen | [PRC-003] |
| Simulated pharmacy/GP record viewer | Provides verification sources with realistic conflicts | [DEC-004], [DEC-005] |

## Branching Logic Map

### Decision Point 1: Verification Source Selection under Time Pressure

| Property | Value |
|----------|-------|
| Source | [DEC-004], [CX-003] |
| Aspect type | Non-routine |
| Feedback type | Cognitive |

| Path | Cue | Decision | Outcome | Feedback |
|------|-----|----------|---------|----------|
| Expert path | 12 medications reported; ED time pressure | Activate polypharmacy rule [HEUR-001]; select 3 sources: pharmacy dispensing record (most reliable), GP letter, and My Health Record; flag for follow-up verification | Proceeds with high-confidence BPMH | Cognitive: "You recognised the polypharmacy trigger and selected the most reliable accessible sources. In ED, you can't wait for all sources — prioritise dispensing records and follow up later." |
| Novice deviation 1 | 12 medications reported | Uses only patient interview (no additional sources) | Incomplete BPMH; misses 4 medications | Cognitive: "With 12 medications, patient recall alone is unreliable. The polypharmacy rule [HEUR-001] requires ≥3 sources. Novices often skip verification under time pressure — but this is when it matters most." |
| Novice deviation 2 | 12 medications reported | Uses My Health Record only (easiest to access) | Outdated information; misses recent medication changes | Cognitive: "My Health Record may be outdated — the GP may not have updated it recently. Pharmacy dispensing records confirm what was actually supplied, which is more reliable for current use." |

### Decision Point 2: Allergy Discrimination

| Property | Value |
|----------|-------|
| Source | [DEC-003], [DISC-002], [SCN-002] |
| Aspect type | Non-routine |
| Feedback type | Cognitive |

| Path | Cue | Decision | Outcome | Feedback |
|------|-----|----------|---------|----------|
| Expert path | Patient says "I'm allergic to penicillin — it makes me sick" | Probes: "What happens when you take it?" Patient: "It upsets my stomach." Classifies as side effect/intolerance, not allergy | Correct classification; avoids unnecessary antibiotic substitution | Cognitive: "You probed for the reaction details. 'Upsets my stomach' is a non-immunological cue [DISC-002]. False penicillin allergy labels lead to broader-spectrum antibiotics with worse outcomes." |
| Novice deviation 1 | Patient says "I'm allergic to penicillin" | Records as allergy without probing | False allergy label persists; affects future prescribing | Cognitive: "You accepted the patient's 'allergy' label without probing. Always ask: 'What happens when you take it?' The reaction details determine whether it's a true allergy or a side effect [DEC-003]." |
| Novice deviation 2 | Patient says "I'm allergic to penicillin — it makes me sick" | Probes but misclassifies as allergy | Unnecessary antibiotic substitution | Cognitive: "'Upsets my stomach' is a gastrointestinal symptom — a non-immunological cue. True allergy cues include swelling, hives, or breathing difficulty [DISC-002]." |

### Decision Point 3: Source Conflict Resolution

| Property | Value |
|----------|-------|
| Source | [DEC-005], [GAP-002] |
| Aspect type | Non-routine |
| Feedback type | Cognitive |

| Path | Cue | Decision | Outcome | Feedback |
|------|-----|----------|---------|----------|
| Expert path | Pharmacy shows warfarin 5mg weekly; patient says "I take it sometimes, not every week" | Contacts pharmacy to confirm last dispense date; documents actual adherence pattern: "Takes warfarin 5mg weekly, admits to missing 2–3 doses per month" | Accurate adherence documentation | Cognitive: "You recognised the conflict between the dispensing record and the patient's actual use pattern. Contacting the pharmacy confirmed the dispense frequency, and the patient's admission revealed non-adherence." |
| Novice deviation 1 | Pharmacy shows warfarin 5mg weekly; patient says "I take it sometimes" | Records pharmacy dose without noting adherence pattern | BPMH shows warfarin 5mg weekly (prescribed use, not actual use) | Cognitive: "The BPMH must capture what the patient is *actually taking*, not what the pharmacy dispensed. The patient's 'sometimes' is a non-adherence signal [DEC-006] that needs documentation." |
| Novice deviation 2 | Pharmacy shows warfarin 5mg weekly; patient says "I take it sometimes" | Ignores the conflict; records patient's vague report | Incomplete documentation; no dose recorded | Cognitive: "When sources conflict, you need to resolve the conflict [DEC-005]. Contacting the pharmacy and probing the patient's actual pattern gives you the complete picture." |

### Decision Point 4: Discrepancy Classification

| Property | Value |
|----------|-------|
| Source | [DEC-001], [DISC-001], [SCN-003] |
| Aspect type | Non-routine |
| Feedback type | Cognitive |

| Path | Cue | Decision | Outcome | Feedback |
|------|-----|----------|---------|----------|
| Expert path | Warfarin not in ED orders; no documented rationale; time-critical medication | Classifies as unintentional omission; red flag: no documentation + time-critical medication [GAP-003]; notifies prescriber immediately | Warfarin restarted; stroke risk mitigated | Cognitive: "You recognised this as an unintentional omission. The red flags were: no documentation in progress notes, and warfarin is a time-critical medication. This is exactly the kind of discrepancy that causes harm [RISK-001]." |
| Novice deviation 1 | Warfarin not in ED orders | Assumes prescriber intentionally ceased it; does not investigate | Warfarin omission persists; patient at stroke risk | Cognitive: "You assumed the omission was intentional without checking for documentation. The red flags [GAP-003] — no documentation and a time-critical medication — should have triggered investigation. This is a common novice error [NOV-001]." |
| Novice deviation 2 | Warfarin not in ED orders | Classifies as unintentional but does not notify prescriber urgently | Delayed resolution; patient misses warfarin doses | Cognitive: "You correctly classified this as unintentional, but warfarin is time-critical. The resolution action [DEC-002] for an omission of a time-critical medication is immediate prescriber notification." |

### Decision Point 5: Discharge Communication

| Property | Value |
|----------|-------|
| Source | [PRC-005], [GAP-008] |
| Aspect type | Routine |
| Feedback type | Corrective |

| Path | Cue | Decision | Outcome | Feedback |
|------|-----|----------|---------|----------|
| Expert path | Patient being discharged to aged care; daughter present | Prepares written discharge list; uses teach-back with daughter; involves aged care facility in communication cascade; provides hard-copy documentation | Patient and carer demonstrate understanding; aged care facility receives updated plan | No feedback needed — correct execution |
| Novice deviation 1 | Patient being discharged to aged care | Provides verbal instructions only; no written list | Patient and carer cannot recall medication changes | Corrective: "Verbal-only counselling is insufficient — the vast majority of patients do not retain spoken information accurately. Always provide a printed discharge medication list [PRC-005]." |
| Novice deviation 2 | Patient being discharged to aged care | Provides written list but asks "Do you understand?" | False confidence in patient comprehension | Corrective: "Asking 'Do you understand?' does not verify comprehension. Use the teach-back method: ask the patient or carer to repeat the instructions in their own words [PRC-005]." |

## Scene-by-Scene Outline

### Scene 1: ED Admission — Initial Patient Contact

**Setting:** Busy Emergency Department. Mrs. Chen (78) is in a cubicle with her daughter. The learner is a hospital pharmacist called to obtain a BPMH. A simulated clock shows 25 minutes remaining.

**Learner task:** Conduct the patient/carer interview to collect medication information.

**Available information:** Patient name, age, admission diagnosis (fall, confusion), current vital signs. Access to eMR (limited — no medication history yet).

**Decision points in this scene:** Decision Point 1 (source selection planning), Decision Point 2 (allergy discrimination).

**Expert path through this scene:** Opens with open-ended questions; uses prompted recall with OTC list [HEUR-002]; probes the penicillin "allergy" and correctly classifies it as a side effect [DEC-003, DISC-002]; identifies 12 medications including 2 OTC (paracetamol and fish oil); notes the patient's uncertainty about warfarin adherence [DEC-006]; plans to verify against pharmacy, GP, and My Health Record [DEC-004].

**Novice deviation paths:** Accepts "allergy" without probing; misses OTC medications; does not note adherence uncertainty; plans to use only My Health Record for verification.

### Scene 2: Verification — Source Selection and Conflict Resolution

**Setting:** Pharmacist's office. The learner has access to three verification sources: pharmacy dispensing record, GP letter, and My Health Record.

**Learner task:** Cross-reference the patient's reported medications against the three sources; resolve conflicts.

**Available information:** Pharmacy dispensing record (shows warfarin 5mg weekly, last dispensed 3 weeks ago), GP letter (shows warfarin 5mg weekly, but notes "patient reports inconsistent adherence"), My Health Record (outdated — shows 10 medications, missing 2 recent additions).

**Decision points in this scene:** Decision Point 3 (source conflict resolution).

**Expert path through this scene:** Identifies the warfarin adherence conflict; contacts pharmacy to confirm last dispense; documents actual adherence pattern; identifies 2 medications in My Health Record that are outdated; achieves verified BPMH with all 12 medications.

**Novice deviation paths:** Records pharmacy dose without noting adherence; accepts My Health Record at face value; does not contact pharmacy for clarification.

### Scene 3: Transfer Reconciliation — Comparison and Classification

**Setting:** Medical ward. The patient has been transferred from ED. The learner accesses the current medication orders in eMR.

**Learner task:** Compare the verified BPMH against the current medication orders; identify and classify discrepancies.

**Available information:** Verified BPMH (12 medications), current ED orders (10 medications — warfarin and one OTC omitted), progress notes (no rationale for warfarin cessation).

**Decision points in this scene:** Decision Point 4 (discrepancy classification).

**Expert path through this scene:** Performs line-by-line comparison [PRC-003]; identifies 4 discrepancies (warfarin omission, OTC omission, dose difference for metoprolol, duplicate analgesic); classifies warfarin omission as unintentional (red flags: no documentation, time-critical) [DEC-001, GAP-003]; classifies metoprolol dose difference as intentional (clinically obvious — patient's BP is low) [DISC-001]; notifies prescriber about warfarin omission [DEC-002].

**Novice deviation paths:** Misses 2–3 discrepancies; classifies all as unintentional or all as intentional; does not notify prescriber urgently about warfarin.

### Scene 4: Discharge — Patient Counselling and Communication

**Setting:** Medical ward, day of discharge. Patient is being transferred to an aged care facility. Daughter is present.

**Learner task:** Prepare discharge medication list; counsel patient and daughter; communicate with aged care facility.

**Available information:** Final reconciled medication list (12 medications, with warfarin restarted), list of changes (warfarin restarted, metoprolol dose reduced, one OTC ceased), aged care facility contact details.

**Decision points in this scene:** Decision Point 5 (discharge communication).

**Expert path through this scene:** Prepares printed discharge list with commenced/ceased/changed sections [PRC-004]; delivers counselling session with contrastive language [PRC-005]; applies teach-back with daughter; provides hard-copy documentation; contacts aged care facility to communicate medication changes; documents that teach-back was performed.

**Novice deviation paths:** Verbal-only counselling; asks "Do you understand?" instead of teach-back; does not contact aged care facility; does not provide hard-copy documentation.

### Scene 5: Debrief — Performance Review

**Setting:** Post-scenario debrief screen.

**Learner task:** Review performance against expert path; reflect on decisions.

**Available information:** Side-by-side comparison of learner's decisions vs. expert decisions; causal chain showing how errors would have propagated [RISK-002]; LTEM performance summary.

**Expert path through this scene:** Learner reviews each decision point, reads cognitive feedback explaining *why* the expert path works, and reflects on mental model differences [MM-001].

**Novice deviation paths:** N/A — all learners reach this scene.

## Source Traceability

| KB ID | Path | How used |
|-------|------|----------|
| [TSK-001] | tasks/obtain-bpmh-admission.md | Whole task — admission phase |
| [TSK-002] | tasks/reconcile-medicines-transfer.md | Whole task — transfer phase |
| [TSK-003] | tasks/supply-medicines-info-discharge.md | Whole task — discharge phase |
| [DEC-001] | decisions/classify-discrepancy-intentional-vs-unintentional.md | Decision Point 4 |
| [DEC-002] | decisions/resolve-unintentional-discrepancy.md | Decision Point 4 resolution |
| [DEC-003] | decisions/distinguish-allergy-from-side-effect.md | Decision Point 2 |
| [DEC-004] | decisions/select-verification-sources.md | Decision Point 1 |
| [DEC-005] | decisions/resolve-conflicting-sources.md | Decision Point 3 |
| [DEC-006] | decisions/assess-adherence-pattern.md | Adherence detection in Scenes 1–2 |
| [DISC-001] | discriminations/recognise-clinical-rationale-for-change.md | Decision Point 4 clinical rationale |
| [DISC-002] | discriminations/identify-immunological-vs-non-immunological-reaction.md | Decision Point 2 perceptual cues |
| [MM-001] | mentalmodels/bpmh-as-diagnostic-conversation.md | Cognitive feedback design in debrief |
| [HEUR-001] | heuristics/polypharmacy-probing-rule.md | Decision Point 1 polypharmacy trigger |
| [HEUR-002] | heuristics/common-otc-prompt-list.md | Scene 1 OTC prompting |
| [PRC-001] | procedures/collect-medication-information.md | Scene 1 interview procedure |
| [PRC-002] | procedures/verify-medication-history-accuracy.md | Scene 2 verification procedure |
| [PRC-003] | procedures/compare-bpmh-to-prescribed-medicines.md | Scene 3 comparison procedure |
| [PRC-004] | procedures/supply-medicines-information.md | Scene 4 discharge procedure |
| [PRC-005] | procedures/patient-counselling-techniques.md | Decision Point 5 counselling |
| [CX-001] | complexity/polypharmacy-increases-bpmh-difficulty.md | Scenario complexity factor |
| [CX-002] | complexity/patient-communication-barriers.md | Scenario complexity factor |
| [CX-003] | complexity/time-pressure-acute-settings.md | Scenario complexity factor |
| [SCN-001] | scenarios/polypharmacy-elderly-admission.md | Primary scenario source |
| [SCN-002] | scenarios/false-allergy-label.md | Decision Point 2 basis |
| [SCN-003] | scenarios/omitted-anticoagulant.md | Decision Point 4 basis |
| [RISK-001] | risks/unintentional-discrepancy-causes-harm.md | Decision Point 4 risk context |
| [RISK-002] | risks/incomplete-bpmh-propagates-errors.md | Debrief causal chain |
| [NOV-001] | novice-calibration/bpmh-novice-definition.md | Success criteria novice baseline |
| [LC-001] | learningcurve/bpmh-skill-progression.md | Success criteria progression |
| [GAP-005] | gaps/expert-mental-model-bpmh.md | Cognitive feedback design |
