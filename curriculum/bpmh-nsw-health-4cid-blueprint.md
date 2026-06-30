---
type: 4C/ID Blueprint
id: BLP-001
title: BPMH NSW Health 4C/ID Blueprint
slug: bpmh-nsw-health-4cid-blueprint
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
  - kb_id: CON-001
    kb_path: concepts/best-possible-medication-history.md
  - kb_id: CON-002
    kb_path: concepts/medication-reconciliation.md
  - kb_id: CON-003
    kb_path: concepts/medication-discrepancy.md
  - kb_id: CON-004
    kb_path: concepts/transfer-of-care.md
  - kb_id: CON-005
    kb_path: concepts/adverse-drug-reaction.md
  - kb_id: CON-006
    kb_path: concepts/polypharmacy.md
  - kb_id: CON-007
    kb_path: concepts/medication-adherence.md
  - kb_id: RISK-001
    kb_path: risks/unintentional-discrepancy-causes-harm.md
  - kb_id: RISK-002
    kb_path: risks/incomplete-bpmh-propagates-errors.md
  - kb_id: CX-001
    kb_path: complexity/polypharmacy-increases-bpmh-difficulty.md
  - kb_id: CX-002
    kb_path: complexity/patient-communication-barriers.md
  - kb_id: CX-003
    kb_path: complexity/time-pressure-acute-settings.md
  - kb_id: LC-001
    kb_path: learningcurve/bpmh-skill-progression.md
  - kb_id: SCN-001
    kb_path: scenarios/polypharmacy-elderly-admission.md
  - kb_id: SCN-002
    kb_path: scenarios/false-allergy-label.md
  - kb_id: SCN-003
    kb_path: scenarios/omitted-anticoagulant.md
  - kb_id: GAP-001
    kb_path: gaps/verification-source-selection-criteria.md
  - kb_id: GAP-002
    kb_path: gaps/conflicting-source-resolution-strategy.md
  - kb_id: GAP-003
    kb_path: gaps/clinical-rationale-recognition-cues.md
  - kb_id: GAP-004
    kb_path: gaps/adherence-assessment-cues.md
  - kb_id: GAP-005
    kb_path: gaps/expert-mental-model-bpmh.md
  - kb_id: GAP-006
    kb_path: gaps/polypharmacy-heuristics.md
  - kb_id: GAP-007
    kb_path: gaps/novice-to-competent-transition.md
  - kb_id: GAP-008
    kb_path: gaps/discharge-communication-effectiveness.md
  - kb_id: EXP-001
    kb_path: experts/bpmh-clinician-nsw.md
  - kb_id: NOV-001
    kb_path: novice-calibration/bpmh-novice-definition.md
related: [CUR-001, SEG-001, SEG-002, SEG-003, SEG-004, SEG-005, SEG-006, SEG-007, SEG-008, SEG-009, SEG-010, SCW-001]
generator: CurriculumArchitectAgent
generated: 2026-06-30
---

# BPMH NSW Health 4C/ID Blueprint

## Skills Hierarchy

### Constituent Skills

| # | Constituent Skill | Source Entry | Classification | Needs |
|---|-------------------|-------------|---------------|-------|
| 1 | Conduct patient/carer medication interview | [TSK-001], [PRC-001] | Non-routine | Supportive Information |
| 2 | Select and prioritise verification sources | [DEC-004], [PRC-002] | Non-routine | Supportive Information |
| 3 | Resolve conflicting medication information | [DEC-005], [PRC-002] | Non-routine | Supportive Information |
| 4 | Classify discrepancies (intentional vs. unintentional) | [DEC-001], [DISC-001] | Non-routine | Supportive Information |
| 5 | Resolve unintentional discrepancies | [DEC-002] | Non-routine | Supportive Information |
| 6 | Distinguish allergy from side effect | [DEC-003], [DISC-002] | Non-routine | Supportive Information |
| 7 | Assess medication adherence patterns | [DEC-006], [CON-007] | Non-routine | Supportive Information |
| 8 | Recognise clinical rationale for medication changes | [DISC-001], [GAP-003] | Non-routine | Supportive Information |
| 9 | Apply BPMH as diagnostic conversation (mental model) | [MM-001], [GAP-005] | Non-routine | Supportive Information |
| 10 | Compare BPMH against prescribed medicines (line-by-line) | [PRC-003] | Routine | Procedural Information |
| 11 | Document medication information in eMR | [PRC-001], [PRC-002] | Routine | Procedural Information |
| 12 | Prepare discharge medication list | [PRC-004] | Routine | Procedural Information |
| 13 | Apply polypharmacy probing rule (≥5 meds → ≥3 sources) | [HEUR-001] | To-be-automated | Procedural Info + Part-Task |
| 14 | Use OTC prompt list | [HEUR-002] | Routine | Procedural Information |
| 15 | Apply teach-back counselling method | [PRC-005] | To-be-automated | Procedural Info + Part-Task |
| 16 | Provide hard-copy discharge documentation | [PRC-005] | Routine | Procedural Information |

### Prerequisite Relationships

Skills 10–12 and 14–16 (routine procedural skills) are foundational and should be introduced early so learners can execute the mechanical steps without cognitive load competing with non-routine judgement. Skills 1–9 (non-routine skills) build on these foundations and must be learned in the following approximate order:

- Skills 1 (interview) and 14 (OTC prompts) are co-requisites — the interview cannot be conducted without the OTC prompt list.
- Skills 2 (source selection) and 3 (conflict resolution) are prerequisite to Skill 4 (discrepancy classification) — you cannot classify discrepancies without first establishing a reliable BPMH.
- Skill 6 (allergy discrimination) is independent but should be introduced early as it occurs during the interview phase.
- Skill 7 (adherence assessment) is embedded within Skill 1 (interview).
- Skill 8 (clinical rationale recognition) is prerequisite to Skill 4 (discrepancy classification) — it informs the classification decision.
- Skill 9 (diagnostic conversation mental model) is the overarching cognitive framework that integrates Skills 1–8; it develops iteratively across all task classes.
- Skill 5 (resolve unintentional discrepancies) follows Skill 4 — it is the action taken after classification.
- Skill 12 (discharge list) and Skill 15 (teach-back) are part of the discharge phase [TSK-003] and follow all admission/transfer skills.
- Skill 13 (polypharmacy probing) is embedded within Skills 1–3 and should become automatic through part-task practice.

### Cue–Decision–Action Chains

#### Chain for [TSK-001] — Obtain Best Possible Medication History at Admission

| Step | Cue | Decision | Action | Source |
|------|-----|----------|--------|--------|
| 1 | Patient presents for admission | Initiate BPMH interview | Use structured interview guide; ask open-ended questions about all medications | [PRC-001] |
| 2 | Patient reports medications | Assess for polypharmacy (≥5 meds) | If ≥5, activate polypharmacy probing rule: use ≥3 verification sources, probe for OTC/complementary/PRN | [HEUR-001], [CX-001] |
| 3 | Patient mentions "allergy" | Distinguish allergy from side effect | Probe for reaction details; classify as immunological or non-immunological | [DEC-003], [DISC-002] |
| 4 | Patient responses suggest non-adherence | Assess adherence pattern | Probe gently for actual use pattern; document actual use, not prescribed use | [DEC-006], [CON-007] |
| 5 | Interview complete | Select verification sources | Choose ≥2 sources based on patient context, availability, and reliability | [DEC-004] |
| 6 | Sources conflict | Resolve conflicting information | Determine which source most accurately reflects actual use; contact pharmacy/GP if needed | [DEC-005] |
| 7 | Verification complete | Achieve BPMH | Document verified medication history with name, dose, frequency, route, indication | [PRC-002] |

#### Chain for [TSK-002] — Reconcile Medicines at Transfer of Care

| Step | Cue | Decision | Action | Source |
|------|-----|----------|--------|--------|
| 1 | Patient transferring between wards/teams | Obtain current medication orders | Access eMR or paper medication chart | [PRC-003] |
| 2 | Compare BPMH to current orders | Identify discrepancies | Line-by-line comparison: check name, dose, frequency, route for each medication | [PRC-003] |
| 3 | Discrepancy identified | Classify as intentional or unintentional | Check for documented rationale; assess clinical obviousness; consult prescriber if uncertain | [DEC-001], [DISC-001] |
| 4 | Discrepancy classified as unintentional | Resolve discrepancy | Notify prescriber; recommend action based on discrepancy type (omission, commission, dose error, duplication) | [DEC-002] |
| 5 | All discrepancies resolved | Document reconciliation | Record final reconciled medication list in eMR | [PRC-003] |

#### Chain for [TSK-003] — Supply Accurate Medicines Information at Discharge

| Step | Cue | Decision | Action | Source |
|------|-----|----------|--------|--------|
| 1 | Patient being discharged | Prepare discharge medication list | Compile final reconciled list; identify commenced, ceased, and changed medications | [PRC-004] |
| 2 | Medication changes identified | Document reasons for changes | Record clinical rationale for each change | [PRC-004] |
| 3 | Communicate to patient | Apply counselling techniques | Use teach-back method; provide hard-copy documentation; involve carer/interpreter if needed | [PRC-005] |
| 4 | Communicate to next care provider | Send reconciled list to GP/receiving facility | Use standardised discharge summary; ensure timely transmission | [PRC-004] |

## Learning Tasks Design

### Task Classes

#### Task Class 1 (Simplest)

| Property | Value |
|----------|-------|
| Whole task | [TSK-001] — Obtain BPMH at Admission |
| Simplifying conditions | 1–3 medications; cooperative, English-speaking patient with no cognitive impairment; no time pressure; single pharmacy record available as verification source; no discrepancies or one obvious discrepancy |
| Complexity factors | None active |
| Supportive information | Conceptual models (BPMH definition, four-step process), SAPs (OTC prompt list, basic interview structure), basic discrepancy classification |
| Variability | Surface: patient age (young adult vs. middle-aged), setting (elective admission vs. ED), medication types (chronic vs. acute). Structural: 1 vs. 2 vs. 3 medications; presence vs. absence of one OTC medication |
| Scaffolding | Worked examples → completion tasks → full performance |

#### Task Class 2 (Intermediate)

| Property | Value |
|----------|-------|
| Whole task | [TSK-001] + [TSK-002] — Admission + Transfer |
| Simplifying conditions | 5–8 medications; one complexity factor active (polypharmacy OR communication barrier OR time pressure); 1–2 discrepancies requiring classification; at least one verification source conflict |
| Complexity factors | [CX-001] or [CX-002] or [CX-003] |
| Supportive information | All Task Class 1 models plus: polypharmacy probing heuristic, communication barrier adaptations, time-pressure triage, conflict resolution framework, clinical rationale recognition |
| Variability | Surface: patient type (elderly vs. middle-aged), setting (ED vs. medical ward), communication barrier type (language vs. cognitive vs. hearing). Structural: 5 vs. 8 medications; 1 vs. 2 discrepancies; intentional vs. unintentional classification; single vs. conflicting sources |
| Scaffolding | Completion tasks → full performance |

#### Task Class 3 (Most Complex)

| Property | Value |
|----------|-------|
| Whole task | [TSK-001] + [TSK-002] + [TSK-003] — Full cycle (Admission → Transfer → Discharge) |
| Simplifying conditions | None — full complexity |
| Complexity factors | [CX-001] + [CX-002] + [CX-003] |
| Supportive information | All Task Class 1–2 models plus: full diagnostic conversation mental model, adherence assessment strategies, discharge communication techniques |
| Variability | Surface: patient type (elderly with polypharmacy and cognitive impairment), setting (busy ED), discharge destination (community vs. aged care). Structural: 10+ medications; 3+ discrepancies including at least one unintentional; multiple conflicting sources; false allergy label; non-adherence pattern |
| Scaffolding | Full performance |

### Variability Specification

| Task Class | Surface Features (vary) | Structural Features (vary) | Source Scenarios |
|------------|------------------------|---------------------------|-----------------|
| 1 | Patient age, admission type, medication classes | Number of medications (1–3), presence of OTC, discrepancy presence | [SCN-001] simplified |
| 2 | Patient communication barrier type, ward setting, time pressure level | Number of medications (5–8), number of discrepancies (1–2), source conflict presence, discrepancy type (intentional vs. unintentional) | [SCN-001], [SCN-002], [SCN-003] |
| 3 | Discharge destination, carer involvement, prescriber communication style | Number of medications (10+), number of discrepancies (3+), multiple complexity factors, full cycle including discharge | [SCN-001] full complexity |

### Scaffolding Progression

| Task Class | Stage 1 (high support) | Stage 2 (medium support) | Stage 3 (low support) |
|------------|----------------------|------------------------|---------------------|
| 1 | Worked example: Expert conducts BPMH interview for a patient on 2 medications, narrating reasoning at each decision point | Completion task: Learner completes a partially-filled BPMH for a patient on 3 medications with one OTC to identify | Full performance: Learner conducts full BPMH interview for a patient on 1–3 medications independently |
| 2 | Worked example: Expert handles polypharmacy patient with one discrepancy, demonstrating source selection and classification | Completion task: Learner completes discrepancy classification and resolution for a patient with 5–8 medications and one source conflict | Full performance: Learner conducts full admission + transfer reconciliation for a patient with 5–8 medications |
| 3 | N/A (saw-tooth: support resets but learner is at full performance) | N/A | Full performance: Learner conducts full BPMH cycle (admission → transfer → discharge) for a complex polypharmacy patient |

### Risk Integration

| Risk | Task Class | Integration |
|------|-----------|-------------|
| [RISK-001] — Unintentional discrepancy causes patient harm | 2, 3 | Embedded as scenario variants where an unintentional omission (e.g., anticoagulant) leads to adverse outcome if not caught; learner experiences consequence of missed discrepancy |
| [RISK-002] — Incomplete BPMH propagates errors through episode of care | 2, 3 | Embedded as scenario variants where an incomplete initial BPMH leads to cascading errors at transfer and discharge; learner must identify and correct the propagation |

## Supportive Information Design

### Domain Models

#### Conceptual Models

| Task Class | Conceptual Model | Source | Description |
|------------|-----------------|--------|-------------|
| 1 | BPMH definition and scope | [CON-001] | What a BPMH is, what it includes (prescription, OTC, complementary, vitamins), and how it differs from a simple medication history |
| 1 | Four-step medication reconciliation process | [CON-002] | Collect → Confirm → Compare → Supply; the overarching process within which BPMH operates |
| 1 | Medication discrepancy types | [CON-003] | Intentional vs. unintentional; omission, commission, dose error, duplication, drug interaction |
| 1 | Transfer of care points | [CON-004] | Admission, intra-hospital transfer, discharge, inter-facility transfer; why each triggers reconciliation |
| 2 | Polypharmacy and its impact | [CON-006] | Definition (≥5 medications), why it increases BPMH complexity non-linearly |
| 2 | Medication adherence | [CON-007] | What adherence means, why the BPMH must capture actual use not prescribed use |
| 3 | Adverse drug reactions and drug allergy | [CON-005] | Distinction between immunological allergy, side effect/intolerance, and contraindication |

#### Structural Models

| Task Class | Structural Model | Source | Description |
|------------|-----------------|--------|-------------|
| 1 | BPMH as diagnostic conversation | [MM-001] | The interview is not a checklist but a diagnostic process — the practitioner builds a mental model of the patient's medication ecosystem and probes strategically |
| 2 | Verification source hierarchy | [DEC-004], [GAP-001] | Available sources (patient interview, pharmacy records, GP letters, My Health Record, eMR history, previous hospital records) and their relative reliability |
| 3 | Full medication reconciliation cycle | [CON-002], [TSK-001], [TSK-002], [TSK-003] | How admission BPMH feeds into transfer reconciliation, which feeds into discharge communication |

#### Causal Models

| Task Class | Causal Model | Source | Description |
|------------|-------------|--------|-------------|
| 1 | Incomplete BPMH → propagated errors | [RISK-002] | An incomplete initial BPMH leads to incorrect medication orders, which propagate through the episode of care |
| 2 | Unintentional discrepancy → adverse drug event | [RISK-001] | An unrecognised unintentional discrepancy (e.g., omitted anticoagulant) leads to patient harm |
| 2 | Polypharmacy → increased discrepancy risk | [CX-001] | More medications → more memory load, more prescribers, more pharmacies, more interactions → higher discrepancy probability |
| 3 | Communication barriers → unreliable BPMH | [CX-002] | Patient cannot reliably report medications → BPMH accuracy compromised → downstream errors |

### Systematic Approaches to Problem Solving (SAPs)

| Task Class | SAP | Source | Description |
|------------|-----|--------|-------------|
| 1 | OTC prompt list | [HEUR-002] | Standard categories of commonly used OTC medications to prompt patients about (analgesics, GI, sleep aids, cold/flu, topicals, supplements) |
| 1 | Basic interview structure | [PRC-001] | Open-ended questions → prompted recall → verification |
| 2 | Polypharmacy probing rule | [HEUR-001] | If ≥5 medications reported, use ≥3 verification sources and specifically probe for OTC, complementary, and PRN medications |
| 2 | Source selection framework | [DEC-004] | Match verification source combination to patient context (simple regimen → 2 sources; polypharmacy → 4 sources; aged care → 3 sources; time-pressured → 2 sources with follow-up) |
| 2 | Conflict resolution framework | [DEC-005] | When sources conflict: assess recency, source type (dispensing > prescription), patient reliability, clinical plausibility; contact pharmacy/GP if needed |
| 2 | Discrepancy classification framework | [DEC-001] | Check for documented rationale → assess clinical obviousness → if uncertain, discuss with prescriber; err on side of caution |
| 2 | Clinical rationale recognition cues | [DISC-001], [GAP-003] | Red flags for unintentional discrepancy: no documentation, indication doesn't match presentation, abnormal starting dose, possible wrong-patient dispensing |
| 3 | Allergy discrimination framework | [DEC-003], [DISC-002] | Listen to patient's reaction description; immunological cues (swelling, hives, breathing difficulty) → true allergy; non-immunological cues (nausea, headache, drowsiness) → side effect/intolerance |
| 3 | Adherence assessment approach | [DEC-006] | Probe gently for actual use pattern; document actual use, not prescribed regimen; use non-judgemental language |
| 3 | Discharge communication techniques | [PRC-005] | Teach-back method, mandatory hard-copy documentation, carer/translator involvement, patient-friendly contrastive language |

### Cognitive Feedback Design

| Task Class | Feedback Focus | Novice Model (from [NOV-001], [LC-001]) | Expert Model (from source) | Cognitive Feedback Strategy |
|------------|---------------|----------------------------------------|---------------------------|----------------------------|
| 1 | Interview as diagnostic conversation vs. checklist | Novice accepts patient self-report at face value; follows guide rigidly without probing | Expert conducts interview as diagnostic conversation, anticipating missing medications and probing strategically | After worked example, ask learner: "What did the expert notice that you might have missed?" Compare novice and expert approaches |
| 2 | Source selection and conflict resolution | Novice applies same verification approach regardless of patient context; struggles with conflicting sources | Expert adapts source selection to context; uses heuristics to assess source reliability and resolve conflicts | Present a conflict scenario; ask learner to justify their source choice; then reveal expert reasoning and compare |
| 2 | Discrepancy classification | Novice treats all discrepancies equally, requiring prescriber confirmation for each | Expert rapidly triages discrepancies into "obviously intentional" vs. "needs investigation" using clinical context | Present 5 discrepancies; ask learner to classify each; then reveal expert classifications and discuss the clinical reasoning behind each |
| 3 | Full-cycle mental model | Novice sees admission, transfer, and discharge as separate tasks | Expert sees the full cycle as one continuous process where errors at admission propagate through transfer to discharge | Present a case where an admission error caused a discharge problem; ask learner to trace the propagation; then reveal the expert's preventive approach |

## Procedural Information Design

### How-To Instructions

| Learning Task | Procedure | Source | Steps |
|---------------|-----------|--------|-------|
| Task Class 1, all stages | Collect medication information | [PRC-001] | Step 1: Open-ended questions about all medications. Step 2: Prompted recall using OTC list. Step 3: Document name, dose, frequency, route, indication. Step 4: Ask about allergies and adverse reactions. Step 5: Ask about adherence |
| Task Class 1, all stages | Verify medication history accuracy | [PRC-002] | Step 1: Select ≥2 verification sources. Step 2: Cross-reference patient report against sources. Step 3: Resolve discrepancies between sources. Step 4: Document verified BPMH |
| Task Class 2, all stages | Compare BPMH against prescribed medicines | [PRC-003] | Step 1: Obtain current medication orders. Step 2: Line-by-line comparison (name, dose, frequency, route). Step 3: Document all discrepancies. Step 4: Communicate findings to prescriber. Note role division: pharmacist prepares BPMH, prescriber executes EMR reconciliation |
| Task Class 2, all stages | Classify discrepancy | [DEC-001] | Check for documented rationale → assess clinical obviousness → if uncertain, discuss with prescriber → classify as intentional or unintentional |
| Task Class 2, all stages | Resolve unintentional discrepancy | [DEC-002] | Notify prescriber → recommend action based on type (omission → add; commission → cease/investigate; dose error → correct; duplication → cease one) |
| Task Class 3, all stages | Supply accurate medicines information | [PRC-004] | Step 1: Prepare discharge medication list. Step 2: Document reasons for changes. Step 3: Communicate to patient. Step 4: Communicate to next care provider |
| Task Class 3, all stages | Patient counselling techniques | [PRC-005] | Step 1: Prepare written materials. Step 2: Deliver counselling session with contrastive language. Step 3: Apply teach-back method. Step 4: Provide hard-copy documentation. Step 5: Address special circumstances (cognitive impairment, non-English speakers, telehealth). Step 6: Follow-up check |

### Prerequisite Knowledge

| Learning Task | Prerequisite | Source | Description |
|---------------|-------------|--------|-------------|
| Task Class 1 | BPMH definition | [CON-001] | What a BPMH is, what it includes, how it differs from a simple medication history |
| Task Class 1 | Medication reconciliation four-step process | [CON-002] | Collect → Confirm → Compare → Supply |
| Task Class 1 | Medication discrepancy types | [CON-003] | Intentional vs. unintentional; omission, commission, dose error, duplication |
| Task Class 2 | Polypharmacy definition | [CON-006] | ≥5 medications; why it increases complexity |
| Task Class 2 | Transfer of care types | [CON-004] | Admission, intra-hospital transfer, discharge, inter-facility transfer |
| Task Class 3 | Adverse drug reaction vs. drug allergy | [CON-005] | Immunological vs. non-immunological reactions |
| Task Class 3 | Medication adherence | [CON-007] | Actual use vs. prescribed use |

### Corrective Feedback Design

| Learning Task | Anticipated Error | Feedback | Source |
|---------------|------------------|----------|--------|
| Task Class 1, all stages | Learner omits OTC medications from BPMH | "You recorded only prescription medications. Patients often don't consider OTC products to be 'medications.' Use the OTC prompt list [HEUR-002] to ask about analgesics, GI products, sleep aids, cold/flu remedies, topicals, and supplements." | [NOV-001], [HEUR-002] |
| Task Class 1, all stages | Learner accepts patient's "allergy" label without probing | "You recorded 'penicillin allergy' without asking about the reaction. This could be a side effect (nausea) rather than a true allergy (anaphylaxis). Always probe for the specific reaction using the allergy discrimination framework [DEC-003]." | [NOV-001], [DEC-003] |
| Task Class 2, all stages | Learner uses only one verification source | "The BPMH requires at least two sources [DEC-004]. For this patient with 6 medications, you should use at least 3 sources. Select additional sources based on the patient's context." | [NOV-001], [DEC-004] |
| Task Class 2, all stages | Learner classifies all discrepancies as unintentional | "Not all discrepancies are unintentional. Check for documented rationale and assess whether the change is clinically obvious given the patient's presentation [DEC-001, DISC-001]." | [NOV-001], [DEC-001] |
| Task Class 3, all stages | Learner provides verbal-only discharge counselling | "Verbal-only counselling is insufficient — the vast majority of patients do not retain spoken information accurately. Always provide a printed discharge medication list [PRC-005]." | [NOV-001], [PRC-005] |
| Task Class 3, all stages | Learner asks "Do you understand?" instead of using teach-back | "Asking 'Do you understand?' does not verify comprehension. Use the teach-back method: ask the patient to repeat the instructions in their own words [PRC-005]." | [NOV-001], [PRC-005] |

### Fading Strategy

| Task Class | Stage 1 (full guidance) | Stage 2 (partial guidance) | Stage 3 (no guidance) |
|------------|------------------------|--------------------------|---------------------|
| 1 | Full step-by-step procedure overlays for interview, verification, and documentation; OTC prompt list always visible | Hints only: "Have you asked about OTC medications?" "Have you verified against a second source?" | No procedural info — learner conducts BPMH independently |
| 2 | Full procedure overlays for comparison, classification, and resolution; source selection framework visible | Hints only: "Check for documented rationale" "Is this clinically obvious?" "Have you notified the prescriber?" | No procedural info — learner reconciles independently |
| 3 | Full procedure overlays for discharge communication; teach-back script visible | Hints only: "Use teach-back" "Provide hard-copy" "Involve carer if needed" | No procedural info — learner manages full cycle independently |

## Part-Task Practice Design

| Constituent Skill | Source | Why Automaticity Needed | Practice Design |
|-------------------|--------|------------------------|-----------------|
| Apply polypharmacy probing rule | [HEUR-001] | In time-pressured settings, the practitioner must instantly recognise polypharmacy (≥5 meds) and activate enhanced verification without conscious deliberation | Rapid-fire medication count drills: learner is presented with medication lists of varying lengths and must instantly identify whether the polypharmacy rule applies and which verification sources to prioritise |
| Apply teach-back counselling method | [PRC-005] | Teach-back must become a natural part of every discharge counselling interaction, not a conscious checklist step | Simulated patient interactions: learner practices teach-back phrasing with different patient avatars; receives immediate feedback on whether the phrasing invites genuine comprehension verification vs. yes/no responses |
| Use OTC prompt list | [HEUR-002] | OTC prompting must be automatic — novices consistently forget to ask about OTC medications | Medication list completion drills: learner is given a patient's prescription list and must rapidly identify which OTC categories to probe for based on the patient's conditions |

## Coverage Comparison

| 4C/ID Component | Strength | Weakness | Source |
|-----------------|---------|----------|--------|
| Learning Tasks | Three well-defined whole tasks covering the full reconciliation cycle [TSK-001, TSK-002, TSK-003]; three scenarios providing variability [SCN-001, SCN-002, SCN-003] | No scenarios specifically for transfer-of-care or discharge-only contexts; limited variability in communication barrier types | [SCN-001, SCN-002, SCN-003] |
| Supportive Information | Strong decision point coverage (6 decisions, 2 discriminations, 2 heuristics, 1 mental model); good conceptual foundation (7 concepts) | Expert mental model not articulated [GAP-005]; verification source selection criteria not documented [GAP-001]; conflict resolution strategy not documented [GAP-002]; adherence assessment cues not documented [GAP-004] | [GAP-001, GAP-002, GAP-004, GAP-005] |
| Procedural Information | Four well-documented procedures covering the full cycle [PRC-001 through PRC-005] | Discharge communication strategies partially filled by probed gap [GAP-008]; role division in EMR workflow documented but may vary by LHD | [PRC-003, PRC-004, PRC-005, GAP-008] |
| Part-Task Practice | Two clear candidates identified (polypharmacy probing, teach-back) | No existing part-task practice content in KB; must be designed from scratch | newly surfaced |

## Gap Analysis

| Gap | 4C/ID Component | Source | Priority | Notes |
|-----|-----------------|--------|----------|-------|
| Expert mental model of the patient's medication ecosystem | Supportive Information (domain models) | [GAP-005] | 5 | Core tacit knowledge — without this, training cannot teach novices to think like experts |
| Expert criteria for prioritising verification sources | Supportive Information (SAPs) | [GAP-001] | 4 | Affects source selection decisions across all task classes |
| Expert strategy for resolving conflicting medication sources | Supportive Information (SAPs) | [GAP-002] | 4 | Safety-critical decision point with no articulated criteria |
| Expert cues and probing strategies for detecting non-adherence | Supportive Information (SAPs) | [GAP-004] | 4 | Directly affects BPMH accuracy |
| Expert heuristics for managing polypharmacy in BPMH | Supportive Information (SAPs) | [GAP-006] | 3 | Would improve instruction for highest-risk patient group |
| Transition triggers from novice to competent BPMH practitioner | Task sequencing / scaffolding design | [GAP-007] | 3 | Important for curriculum pacing but not safety-critical |
| Expert strategies for effective discharge medication communication | Procedural Information | [GAP-008] | 3 | Partially filled by probed content in [PRC-005] |
| No novice calibration entries for BPMH accuracy assessment | Cluster 2: Performance Objectives | newly surfaced | 3 | Needed to define assessment rubrics for whole-task performance |
