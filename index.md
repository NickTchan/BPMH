---
title: Best Possible Medication History (BPMH) in NSW Health — Expertise Map
slug: bpmh-nsw-health-expertise-map
domain_ref: okf/domain/bpmh-nsw-health.md
generated: 2026-06-29
generator: ExpertiseMappingAgent
okf_version: 0.1
phase_completed: 1 2 3
concept_count: 42
gap_count: 8
high_priority_gap_count: 5
---

# Best Possible Medication History (BPMH) in NSW Health — Expertise Map

## Domain Scope

This Expertise Map covers the knowledge, procedures, decisions, and tacit expertise involved in obtaining a Best Possible Medication History (BPMH) within the NSW Health public hospital system. The BPMH is the foundational step in medication reconciliation — a formal four-step process mandated by NSW Health policy (PD2022_032) and the NSQHS Medication Safety Standard. The stakes are high: unintentional medication discrepancies affect >50% of hospitalised patients and are linked to adverse drug events, readmission, and mortality.

## Consumer Guide

| Downstream Agent | Bundle Sections to Read | Purpose |
|---|---|---|
| **CTA Interview Architect** | `gaps/` (all, especially GAP-001 through GAP-005), `novice-calibration/`, `decisions/`, `discriminations/` | Probe tacit knowledge at decision points, validate novice definition, explore expert mental models |
| **CSP Generator** | `concepts/`, `procedures/`, `tasks/`, `learningcurve/`, `complexity/` | Build foundational knowledge modules, procedural modules, and progressive skill development |
| **Curriculum Architects** | `tasks/`, `complexity/`, `learningcurve/`, `scenarios/` | Structure 4C/ID curriculum from simple to complex BPMH scenarios |
| **Assessment Designers** | `scenarios/`, `risks/`, `decisions/`, `discriminations/` | Build scenario-based knowledge checks and decision-point assessments |
| **Survey/Audit Instrument Designers** | `concepts/`, `procedures/`, `complexity/` | Frame evaluation instruments for BPMH competency assessment |

## Bundle Navigation

### Domain & Experts
| ID | Title | Type | Certainty |
|----|-------|------|----------|
| [DOM-001](domain/bpmh-nsw-health.md) | Best Possible Medication History (BPMH) in NSW Health | Performance Domain | documented |
| [EXP-001](experts/bpmh-clinician-nsw.md) | Archetypal BPMH Practitioner — NSW Health Hospital Pharmacist | Expert Profile | inferred |
| [NOV-001](novice-calibration/bpmh-novice-definition.md) | Novice Definition — BPMH Practitioner | Novice Calibration | inferred |

### Whole Tasks
| ID | Title | Type | Certainty |
|----|-------|------|----------|
| [TSK-001](tasks/obtain-bpmh-admission.md) | Obtain Best Possible Medication History at Admission | Whole Task | documented |
| [TSK-002](tasks/reconcile-medicines-transfer.md) | Reconcile Medicines at Transfer of Care | Whole Task | documented |
| [TSK-003](tasks/supply-medicines-info-discharge.md) | Supply Accurate Medicines Information at Discharge | Whole Task | documented |

### Foundational Concepts
| ID | Term | Type | Certainty |
|----|------|------|----------|
| [CON-001](concepts/best-possible-medication-history.md) | Best Possible Medication History (BPMH) | Concept Definition | documented |
| [CON-002](concepts/medication-reconciliation.md) | Medication Reconciliation | Concept Definition | documented |
| [CON-003](concepts/medication-discrepancy.md) | Medication Discrepancy | Concept Definition | documented |
| [CON-004](concepts/transfer-of-care.md) | Transfer of Care | Concept Definition | documented |
| [CON-005](concepts/adverse-drug-reaction.md) | Adverse Drug Reaction (ADR) and Drug Allergy | Concept Definition | documented |
| [CON-006](concepts/polypharmacy.md) | Polypharmacy | Concept Definition | documented |
| [CON-007](concepts/medication-adherence.md) | Medication Adherence | Concept Definition | documented |

### Procedures
| ID | Title | Type | Certainty |
|----|-------|------|----------|
| [PRC-001](procedures/collect-medication-information.md) | Collect Medication Information for BPMH | Procedure | documented |
| [PRC-002](procedures/verify-medication-history-accuracy.md) | Verify Medication History Accuracy to Achieve BPMH | Procedure | documented |
| [PRC-003](procedures/compare-bpmh-to-prescribed-medicines.md) | Compare BPMH Against Prescribed Medicines | Procedure | documented |
| [PRC-004](procedures/supply-medicines-information.md) | Supply Accurate Medicines Information | Procedure | documented |
| [PRC-005](procedures/patient-counselling-techniques.md) | Patient Counselling Techniques for Medication Changes | Procedure | documented |

### Decision Points
| ID | Title | Type | Certainty |
|----|-------|------|----------|
| [DEC-001](decisions/classify-discrepancy-intentional-vs-unintentional.md) | Classify Discrepancy as Intentional or Unintentional | Decision Point | documented |
| [DEC-002](decisions/resolve-unintentional-discrepancy.md) | Resolve Unintentional Medication Discrepancy | Decision Point | documented |
| [DEC-003](decisions/distinguish-allergy-from-side-effect.md) | Distinguish Drug Allergy from Side Effect or Intolerance | Decision Point | documented |
| [DEC-004](decisions/select-verification-sources.md) | Select Verification Sources for BPMH | Decision Point | tacit_candidate |
| [DEC-005](decisions/resolve-conflicting-sources.md) | Resolve Conflicting Medication Information Sources | Decision Point | tacit_candidate |
| [DEC-006](decisions/assess-adherence-pattern.md) | Assess Patient Medication Adherence Pattern | Decision Point | tacit_candidate |

### Discriminations
| ID | Title | Type | Certainty |
|----|-------|------|----------|
| [DISC-001](discriminations/recognise-clinical-rationale-for-change.md) | Recognise Clinical Rationale for Medication Change | Discrimination | tacit_candidate |
| [DISC-002](discriminations/identify-immunological-vs-non-immunological-reaction.md) | Identify Immunological vs. Non-Immunological Reaction | Discrimination | documented |

### Mental Models
| ID | Title | Type | Certainty |
|----|-------|------|----------|
| [MM-001](mentalmodels/bpmh-as-diagnostic-conversation.md) | BPMH as Diagnostic Conversation | Mental Model | tacit_candidate |

### Heuristics
| ID | Title | Type | Certainty |
|----|-------|------|----------|
| [HEUR-001](heuristics/polypharmacy-probing-rule.md) | Polypharmacy Probing Rule | Heuristic | tacit_candidate |
| [HEUR-002](heuristics/common-otc-prompt-list.md) | Common OTC Prompt List | Heuristic | documented |

### Risks
| ID | Title | Type | Certainty |
|----|-------|------|----------|
| [RISK-001](risks/unintentional-discrepancy-causes-harm.md) | Unintentional Medication Discrepancy Causes Patient Harm | Risk | documented |
| [RISK-002](risks/incomplete-bpmh-propagates-errors.md) | Incomplete BPMH Propagates Errors Through Episode of Care | Risk | documented |

### Learning Curve
| ID | Title | Type | Certainty |
|----|-------|------|----------|
| [LC-001](learningcurve/bpmh-skill-progression.md) | BPMH Skill Progression Stages | Learning Curve Observation | inferred |

### Complexity Factors
| ID | Title | Type | Certainty |
|----|-------|------|----------|
| [CX-001](complexity/polypharmacy-increases-bpmh-difficulty.md) | Polypharmacy Increases BPMH Complexity | Complexity Factor | documented |
| [CX-002](complexity/patient-communication-barriers.md) | Patient Communication Barriers | Complexity Factor | documented |
| [CX-003](complexity/time-pressure-acute-settings.md) | Time Pressure in Acute Settings | Complexity Factor | documented |

### Scenarios
| ID | Title | Type | Certainty |
|----|-------|------|----------|
| [SCN-001](scenarios/polypharmacy-elderly-admission.md) | Elderly Patient with Polypharmacy — ED Admission | Scenario | inferred |
| [SCN-002](scenarios/false-allergy-label.md) | Patient with False Penicillin Allergy Label | Scenario | inferred |
| [SCN-003](scenarios/omitted-anticoagulant.md) | Omitted Anticoagulant — High-Risk Discrepancy | Scenario | inferred |

### Identified Knowledge Gaps
| ID | Gap Title | Priority | Related Concepts | Certainty |
|----|-----------|----------|------------------|-----------|
| [GAP-005](gaps/expert-mental-model-bpmh.md) | Expert Mental Model of the Patient's Medication Ecosystem | 5 | [MM-001], [PRC-001] | tacit_candidate |
| [GAP-001](gaps/verification-source-selection-criteria.md) | Expert Criteria for Prioritising Verification Sources | 4 | [DEC-004], [PRC-002] | tacit_candidate |
| [GAP-002](gaps/conflicting-source-resolution-strategy.md) | Expert Strategy for Resolving Conflicting Medication Sources | 4 | [DEC-005], [PRC-002] | tacit_candidate |
| [GAP-003](gaps/clinical-rationale-recognition-cues.md) | Expert Cues for Recognising Clinically Obvious Medication Changes | 4 | [DISC-001], [DEC-001] | tacit_candidate |
| [GAP-004](gaps/adherence-assessment-cues.md) | Expert Cues and Probing Strategies for Detecting Non-Adherence | 4 | [DEC-006], [CON-007] | tacit_candidate |
| [GAP-006](gaps/polypharmacy-heuristics.md) | Expert Heuristics for Managing Polypharmacy in BPMH | 3 | [HEUR-001], [CX-001] | tacit_candidate |
| [GAP-007](gaps/novice-to-competent-transition.md) | Transition Triggers from Novice to Competent BPMH Practitioner | 3 | [LC-001], [NOV-001] | probed |
| [GAP-008](gaps/discharge-communication-effectiveness.md) | Expert Strategies for Effective Discharge Medication Communication | 3 | [PRC-004], [TSK-003] | tacit_candidate |

### References
| ID | Title | Type |
|----|-------|------|
| [REF-001](references/cec-med-rec.md) | NSW CEC — Medication Reconciliation | Reference |
| [REF-002](references/nsw-health-pd2022-032.md) | NSW Health PD2022_032 — Medication Handling Policy | Reference |
| [REF-003](references/acsqhc-med-safety-standard.md) | ACSQHC — Medication Safety Standard | Reference |
| [REF-004](references/who-high5s-sop.md) | WHO — Standard Implementation Protocol for Medication Reconciliation | Reference |
| [REF-005](references/health-gov-au-guiding-principles.md) | Australian Government — Guiding Principles | Reference |
| [REF-006](references/ho-2026-bpmh-review.md) | Ho et al. (2026) — BPMH Interview Guide Scoping Review | Reference |
| [REF-007](references/ncbi-med-rec-overview.md) | NCBI — Medication Reconciliation Overview | Reference |
| [REF-008](references/springer-nature-umds.md) | Springer Nature — Unintended Medication Discrepancies at Transitions of Care | Reference |