---
type: Scenario
id: SCN-003
title: Omitted Anticoagulant — High-Risk Discrepancy
slug: omitted-anticoagulant
domain_ref: okf/domain/bpmh-nsw-health.md
certainty: inferred
sources:
  - ref: okf/references/ncbi-med-rec-overview.md
    citation: "NCBI — Medication Reconciliation"
    accessed: 2026-06-22
  - ref: okf/references/who-high5s-sop.md
    citation: "WHO High5s SOP"
    accessed: 2026-06-22
related:
  - okf/risks/unintentional-discrepancy-causes-harm.md
  - okf/decisions/resolve-unintentional-discrepancy.md
  - okf/decisions/classify-discrepancy-intentional-vs-unintentional.md
---

# Omitted Anticoagulant — High-Risk Discrepancy

## Classification

`critical-incident` (potential for serious harm)

## Scenario Description

A 62-year-old patient with atrial fibrillation is admitted for a gastrointestinal bleed. The BPMH reveals the patient takes apixaban 5mg BD. The admission medication orders do not include apixaban (correctly held due to bleeding). However, the patient's other chronic medications — including metoprolol and digoxin — are also omitted from the orders, and this is not flagged.

## Expert Pathway

1. **Identify the discrepancy:** Apixaban omission is intentional (bleeding), but metoprolol and digoxin omissions are not explained
2. **Classify:** Apixaban = intentional; metoprolol and digoxin = unintentional → **[DEC-001](../decisions/classify-discrepancy-intentional-vs-unintentional.md)**
3. **Assess urgency:** Digoxin has a narrow therapeutic index; abrupt cessation can cause arrhythmia. Metoprolol cessation can cause rebound tachycardia
4. **Escalate:** Notify the prescriber immediately about the unintentional omissions → **[DEC-002](../decisions/resolve-unintentional-discrepancy.md)**
5. **Document:** Ensure the rationale for apixaban cessation is clearly documented to prevent confusion at the next transfer

## Novice Divergence Points

- **Divergence 1:** Novice sees that apixaban was correctly held and assumes all omissions are intentional
- **Divergence 2:** Novice does not recognise the clinical urgency of digoxin and metoprolol omission
- **Divergence 3:** Novice does not escalate the unintentional discrepancies promptly

## Decisions Exercised

- **[DEC-001](../decisions/classify-discrepancy-intentional-vs-unintentional.md)** — Classifying discrepancies in a complex clinical context
- **[DEC-002](../decisions/resolve-unintentional-discrepancy.md)** — Resolving high-risk unintentional omissions

## Risks Exercised

- **[RISK-001](../risks/unintentional-discrepancy-causes-harm.md)** — Unintentional discrepancy causes patient harm

# Citations

[1] [NCBI — Medication Reconciliation](https://www.ncbi.nlm.nih.gov/books/NBK2648/)
[2] [WHO High5s SOP](https://cdn.who.int/media/docs/default-source/patient-safety/high5s/h5s-sop.pdf?sfvrsn=594d8e49_4)