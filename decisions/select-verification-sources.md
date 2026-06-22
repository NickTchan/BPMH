---
type: Decision Point
id: DEC-004
title: Select Verification Sources for BPMH
slug: select-verification-sources
domain_ref: okf/domain/bpmh-nsw-health.md
certainty: tacit_candidate
sources:
  - ref: okf/references/ho-2026-bpmh-review.md
    citation: "Ho et al. (2026) — BPMH requires at least two sources"
    accessed: 2026-06-22
  - ref: okf/references/cec-med-rec.md
    citation: "NSW CEC — verification sources listed"
    accessed: 2026-06-22
related:
  - okf/procedures/collect-medication-information.md
  - okf/procedures/verify-medication-history-accuracy.md
  - okf/gaps/verification-source-selection-criteria.md
---

# Select Verification Sources for BPMH

## Context

This decision occurs during **[PRC-001](../procedures/collect-medication-information.md)** and **[PRC-002](../procedures/verify-medication-history-accuracy.md)** when the clinician must choose which additional sources to use to verify the patient's medication history.

## Cue

The patient interview is complete. The clinician must now verify the reported medications against at least one additional source.

## Threshold

The minimum requirement is **at least two sources**, one being the patient/carer interview [REF: Ho et al., 2026]. However, the expert must decide **which** sources to prioritise based on availability, reliability, and the specific patient context.

## Competing Considerations

| Consideration | Direction |
|---|---|
| **Source reliability** | Pharmacy dispensing records are generally more reliable than patient recall for prescription medications |
| **Source currency** | My Health Record may be outdated if the patient's GP has not updated it recently |
| **Source completeness** | A single pharmacy record may not capture medications dispensed from multiple pharmacies |
| **Time available** | In ED, time pressure may limit verification to the most accessible source |
| **Patient complexity** | Polypharmacy patients may require more sources to achieve confidence |

## Action Table

| Patient Context | Preferred Verification Sources |
|---|---|
| Simple regimen (1–3 medications), reliable patient | Patient interview + one pharmacy record or GP letter |
| Polypharmacy (≥5 medications) | Patient interview + pharmacy record + GP letter + My Health Record |
| Aged care resident | Patient/carer interview + facility medication chart + pharmacy record |
| Patient unable to participate (unconscious, cognitively impaired) | Carer interview + pharmacy record + GP letter + My Health Record + previous hospital records |
| Time-pressured (ED) | Patient interview + most immediately accessible source (eMR history or My Health Record); follow up with additional sources when time permits |

## Gap Note

Sources list available verification sources but do not articulate **how the expert decides which source to prioritise** in different contexts. This is likely tacit knowledge developed through experience.

# Citations

[1] [Ho et al. (2026)](https://pmc.ncbi.nlm.nih.gov/articles/PMC12911780/)
[2] [NSW CEC — Medication Reconciliation](https://cec.health.nsw.gov.au/therapeutics-safety/medicines-improvement/continuity/reconciliation)