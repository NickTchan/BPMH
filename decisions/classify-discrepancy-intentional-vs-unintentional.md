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

## Linked Discriminations

- **[DISC-001](../discriminations/recognise-clinical-rationale-for-change.md)** — Recognising when a clinical context makes a medication change obviously intentional

# Citations

[1] [WHO High5s SOP](https://cdn.who.int/media/docs/default-source/patient-safety/high5s/h5s-sop.pdf?sfvrsn=594d8e49_4)
[2] [NCBI — Medication Reconciliation](https://www.ncbi.nlm.nih.gov/books/NBK2648/)