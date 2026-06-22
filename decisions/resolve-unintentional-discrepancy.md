---
type: Decision Point
id: DEC-002
title: Resolve Unintentional Medication Discrepancy
slug: resolve-unintentional-discrepancy
domain_ref: okf/domain/bpmh-nsw-health.md
certainty: documented
sources:
  - ref: okf/references/who-high5s-sop.md
    citation: "WHO High5s SOP — resolving discrepancies"
    accessed: 2026-06-22
  - ref: okf/references/ncbi-med-rec-overview.md
    citation: "NCBI — Medication Reconciliation"
    accessed: 2026-06-22
related:
  - okf/procedures/compare-bpmh-to-prescribed-medicines.md
  - okf/decisions/classify-discrepancy-intentional-vs-unintentional.md
  - okf/risks/unintentional-discrepancy-causes-harm.md
---

# Resolve Unintentional Medication Discrepancy

## Context

This decision occurs after an unintentional discrepancy has been identified and classified at **[DEC-001](../decisions/classify-discrepancy-intentional-vs-unintentional.md)**.

## Cue

A medication discrepancy has been classified as unintentional — there is no documented or clinically obvious rationale for the difference between the BPMH and the current orders.

## Threshold

The clinician must determine: **What action is needed to correct this discrepancy and prevent harm?**

## Competing Considerations

| Consideration | Direction |
|---|---|
| **Clinical urgency** | Is the omitted medication time-critical (e.g., anti-epileptic, insulin)? |
| **Risk of harm** | Would restarting/ceasing the medication cause harm in the current clinical context? |
| **Prescriber authority** | Only the prescriber can change medication orders — the pharmacist/nurse must communicate, not act unilaterally |
| **Patient preference** | The patient may have intentionally stopped a medication but not informed anyone |

## Action Table

| Discrepancy Type | Action |
|---|---|
| **Omission** (patient takes it, not prescribed) | Notify prescriber; recommend adding to orders if clinically appropriate |
| **Commission** (prescribed, patient doesn't take it) | Notify prescriber; recommend ceasing or investigating why it was prescribed |
| **Dose error** | Notify prescriber; recommend correcting to match BPMH or document rationale for different dose |
| **Duplication** | Notify prescriber; recommend ceasing one of the duplicate agents |

## Risks

- **[RISK-001](../risks/unintentional-discrepancy-causes-harm.md)** — Unintentional discrepancy leads to adverse drug event

# Citations

[1] [WHO High5s SOP](https://cdn.who.int/media/docs/default-source/patient-safety/high5s/h5s-sop.pdf?sfvrsn=594d8e49_4)
[2] [NCBI — Medication Reconciliation](https://www.ncbi.nlm.nih.gov/books/NBK2648/)