---
type: Risk
id: RISK-001
title: Unintentional Medication Discrepancy Causes Patient Harm
slug: unintentional-discrepancy-causes-harm
domain_ref: okf/domain/bpmh-nsw-health.md
certainty: documented
sources:
  - ref: okf/references/who-high5s-sop.md
    citation: "WHO High5s SOP — medication errors at transitions"
    accessed: 2026-06-22
  - ref: okf/references/ncbi-med-rec-overview.md
    citation: "NCBI — Medication Reconciliation"
    accessed: 2026-06-22
  - ref: okf/references/springer-nature-umds.md
    citation: "Springer Nature — UMDs in hospitalised patients"
    accessed: 2026-06-22
related:
  - okf/decisions/resolve-unintentional-discrepancy.md
  - okf/procedures/compare-bpmh-to-prescribed-medicines.md
---

# Unintentional Medication Discrepancy Causes Patient Harm

## Description

An unintentional medication discrepancy (UMD) that is not identified and resolved leads to the patient receiving incorrect medication therapy, resulting in an adverse drug event.

## Where It Manifests

- **[PRC-003](../procedures/compare-bpmh-to-prescribed-medicines.md)** — Failure to identify a discrepancy during comparison
- **[DEC-001](../decisions/classify-discrepancy-intentional-vs-unintentional.md)** — Misclassifying an unintentional discrepancy as intentional

## Early Warning Signs

- Patient reports taking a medication that is not on the admission orders
- A high-risk medication (narrow therapeutic index, anticoagulant, anti-epileptic, insulin) is omitted from orders
- The patient has multiple prescribers and no single source captures all medications
- The patient is unable to participate in the interview (cognitive impairment, language barrier, acute illness)

## Novice Vulnerability

Novices are particularly susceptible to this risk because they:
- May not recognise the clinical significance of omitting certain medications
- May accept the prescriber's orders without comparing against the BPMH
- May not know which medication classes are high-risk for omission harm

## Impact

- Adverse drug events
- Hospital readmission
- Increased length of stay
- Mortality in severe cases (e.g., omission of anti-epileptics leading to seizures)

## Mitigation

- Systematic comparison of BPMH against all medication orders
- Pharmacist-led reconciliation (shown to reduce errors by 70%)
- High-risk medication flagging protocols

# Citations

[1] [WHO High5s SOP](https://cdn.who.int/media/docs/default-source/patient-safety/high5s/h5s-sop.pdf?sfvrsn=594d8e49_4)
[2] [NCBI — Medication Reconciliation](https://www.ncbi.nlm.nih.gov/books/NBK2648/)