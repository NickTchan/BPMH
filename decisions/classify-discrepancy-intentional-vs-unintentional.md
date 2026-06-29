---
type: Decision Point
id: DEC-001
title: Classify Discrepancy as Intentional or Unintentional
slug: classify-discrepancy-intentional-vs-unintentional
domain_ref: okf/domain/bpmh-nsw-health.md
certainty: documented
sources:
  - ref: okf/references/who-high5s-sop.md
    citation: "WHO High5s SOP — discrepancy classification"
    accessed: 2026-06-22
  - ref: okf/references/ncbi-med-rec-overview.md
    citation: "NCBI — Medication Reconciliation"
    accessed: 2026-06-22
related:
  - okf/procedures/compare-bpmh-to-prescribed-medicines.md
  - okf/decisions/resolve-unintentional-discrepancy.md
  - okf/concepts/medication-discrepancy.md
  - okf/discriminations/recognise-clinical-rationale-for-change.md
---

# Classify Discrepancy as Intentional or Unintentional

## Context

This decision occurs during **[PRC-003](../procedures/compare-bpmh-to-prescribed-medicines.md)** when a discrepancy is identified between the BPMH and the current medication orders.

## Cue

A medication appears on the BPMH but not in the current orders (or vice versa), or there is a difference in dose, frequency, or route.

## Threshold

The clinician must determine: **Was this difference a deliberate clinical decision, or did it occur by oversight?**

## Competing Considerations

| Consideration | Direction |
|---|---|
| **Patient safety** | Err on the side of caution — if uncertain, treat as unintentional and investigate |
| **Clinical appropriateness** | Some changes are clinically obvious (e.g., ceasing metformin in acute kidney injury) and likely intentional |
| **Documentation quality** | If the prescriber documented a rationale, the discrepancy is likely intentional |
| **Time pressure** | In urgent settings, clinicians may make intentional changes without documenting rationale immediately |
| **Prescriber intent** | The prescriber may have intended a change but communicated it poorly or not at all |

## Action Table

| Condition | Action |
|---|---|
| Clear clinical rationale documented | Classify as **intentional**; ensure rationale is recorded |
| Clinically obvious change (e.g., holding anticoagulant pre-surgery) | Classify as **intentional**; confirm with prescriber if uncertain |
| No rationale, no obvious clinical reason | Classify as **unintentional**; escalate to prescriber for resolution → **[DEC-002](../decisions/resolve-unintentional-discrepancy.md)** |
| Uncertain | Discuss with prescriber; do not assume |

## Expert Red Flags for Unintentional Discrepancy

The following cues suggest a discrepancy is likely unintentional and warrants investigation:

- **No documentation in medication chart or progress notes** — If a medication change cannot be found documented anywhere, it may not have been a deliberate decision
- **Clinical indication does not match the patient's presentation or diagnosis** — A medication prescribed for a condition the patient does not have suggests an error
- **Abnormal starting dose for a newly initiated medication** — A dose that falls outside standard prescribing ranges for a new medication may indicate a prescribing error
- **Suspicion of wrong-patient dispensing** — In rare cases, a medication may have been dispensed to or charted for the wrong patient entirely

### Investigation Pathways

When a red flag is identified:
1. **Review progress notes** — Look for prescriber documentation (handwritten notes in paper-chart environments, or EMR progress entries)
2. **Consult the prescriber directly** — Ask about the rationale for the change
3. **Inquire with nursing or care coordination staff** — Ward nurses or specialist coordinators (e.g., transplant coordinator) may have contextual knowledge about the medication decision

## Linked Discriminations

- **[DISC-001](../discriminations/recognise-clinical-rationale-for-change.md)** — Recognise when a medication change has a clear clinical rationale

# Citations

[1] [WHO High5s SOP](https://cdn.who.int/media/docs/default-source/patient-safety/high5s/h5s-sop.pdf?sfvrsn=594d8e49_4)
[2] [NCBI — Medication Reconciliation](https://www.ncbi.nlm.nih.gov/books/NBK2648/)