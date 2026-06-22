---
type: Complexity Factor
id: CX-001
title: Polypharmacy Increases BPMH Complexity
slug: polypharmacy-increases-bpmh-difficulty
domain_ref: okf/domain/bpmh-nsw-health.md
certainty: documented
sources:
  - ref: okf/references/ncbi-med-rec-overview.md
    citation: "NCBI — Medication Reconciliation"
    accessed: 2026-06-22
  - ref: okf/references/health-gov-au-guiding-principles.md
    citation: "Australian Government — Guiding Principles"
    accessed: 2026-06-22
related:
  - okf/concepts/polypharmacy.md
  - okf/heuristics/polypharmacy-probing-rule.md
  - okf/risks/incomplete-bpmh-propagates-errors.md
---

# Polypharmacy Increases BPMH Complexity

## Description

Patients taking multiple medications (≥5) present significantly greater challenges for obtaining an accurate BPMH. The complexity increases non-linearly with the number of medications.

## Why It Makes the Domain Difficult

| Factor | Impact |
|---|---|
| **Memory load** | Patients cannot reliably recall all medications when taking ≥5 |
| **Multiple prescribers** | Each prescriber may only know their own medications, fragmenting the record |
| **Multiple pharmacies** | Patients may use different pharmacies for different medications |
| **Drug interactions** | More medications = more potential interactions to identify |
| **Adherence complexity** | Complex regimens lead to variable adherence patterns that are hard to capture |
| **Verification time** | Each additional medication requires verification against sources |

## Expert Adaptation

Experts adapt by:
- Using the polypharmacy probing heuristic ([HEUR-001](../heuristics/polypharmacy-probing-rule.md))
- Prioritising pharmacy dispensing records over patient recall for prescription medications
- Using the patient's medication containers or Webster pack as a primary verification source
- Focusing extra attention on high-risk medication classes

## Novice Vulnerability

Novices tend to apply the same interview approach regardless of medication count, missing the need for increased verification rigour with polypharmacy patients.

## Instructional Implications

CSP agents should design progressive practice scenarios that start with simple regimens (1–3 medications) and advance to complex polypharmacy cases (10+ medications), with explicit instruction on how the approach changes.

# Citations

[1] [NCBI — Medication Reconciliation](https://www.ncbi.nlm.nih.gov/books/NBK2648/)
[2] [Australian Government — Guiding Principles](https://www.health.gov.au/sites/default/files/2022-11/guiding-principles-to-achieve-continuity-in-medication-management.pdf)