---
type: Concept Definition
id: CON-003
title: Medication Discrepancy
slug: medication-discrepancy
domain_ref: okf/domain/bpmh-nsw-health.md
certainty: documented
sources:
  - ref: okf/references/who-high5s-sop.md
    citation: "WHO High5s SOP"
    accessed: 2026-06-22
  - ref: okf/references/ncbi-med-rec-overview.md
    citation: "NCBI — Medication Reconciliation"
    accessed: 2026-06-22
related:
  - okf/concepts/best-possible-medication-history.md
  - okf/decisions/classify-discrepancy-intentional-vs-unintentional.md
  - okf/risks/unintentional-discrepancy-causes-harm.md
---

# Medication Discrepancy

## Definition

A **medication discrepancy** is any difference between the patient's Best Possible Medication History (what they are actually taking) and the medication orders written by the treating team.

## Classification

| Type | Definition | Example |
|---|---|---|
| **Intentional discrepancy** | A deliberate, documented change to the patient's medication regimen based on clinical judgement | Ceasing a medication due to acute kidney injury; documented with rationale |
| **Unintentional discrepancy (UMD)** | An unexplained difference that was not deliberately decided — represents a potential medication error | Omission of a chronic blood pressure medication because it was not captured in the BPMH |

## Common Types of Discrepancies

- **Omission** — a medication the patient takes is not prescribed in hospital (most common)
- **Commission** — a medication is prescribed that the patient does not actually take
- **Dose error** — incorrect dose, frequency, or route compared to the patient's actual use
- **Duplication** — the same medication (or therapeutic equivalent) prescribed under different names
- **Drug interaction** — new medication interacts with an existing medication not captured in the history

## Clinical Significance

Not all discrepancies cause harm, but unintentional discrepancies are a leading cause of adverse drug events at transitions of care. Studies show up to 40% of patients have discrepancies at discharge, and more than 50% experience UMDs at admission.

## Application

Discrepancies are identified during **[PRC-003](../procedures/compare-bpmh-to-prescribed-medicines.md)** and classified at **[DEC-001](../decisions/classify-discrepancy-intentional-vs-unintentional.md)**.

# Citations

[1] [WHO High5s SOP](https://cdn.who.int/media/docs/default-source/patient-safety/high5s/h5s-sop.pdf?sfvrsn=594d8e49_4)
[2] [NCBI — Medication Reconciliation](https://www.ncbi.nlm.nih.gov/books/NBK2648/)