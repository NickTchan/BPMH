---
type: Scenario
id: SCN-001
title: Elderly Patient with Polypharmacy — ED Admission
slug: polypharmacy-elderly-admission
domain_ref: okf/domain/bpmh-nsw-health.md
certainty: inferred
sources:
  - ref: okf/references/ncbi-med-rec-overview.md
    citation: "NCBI — Medication Reconciliation"
    accessed: 2026-06-22
  - ref: okf/references/health-gov-au-guiding-principles.md
    citation: "Australian Government — Guiding Principles"
    accessed: 2026-06-22
related:
  - okf/complexity/polypharmacy-increases-bpmh-difficulty.md
  - okf/complexity/patient-communication-barriers.md
  - okf/decisions/select-verification-sources.md
  - okf/decisions/resolve-conflicting-sources.md
---

# Elderly Patient with Polypharmacy — ED Admission

## Classification

`routine` (common presentation)

## Scenario Description

A 78-year-old patient presents to the Emergency Department via ambulance with a fall and suspected fractured neck of femur. The patient has mild cognitive impairment and lives alone. They report taking "a lot of tablets" but cannot name them specifically. The ambulance handover sheet lists no medications. The patient's daughter (who helps with medications) is contactable by phone but not present.

## Expert Pathway

1. **Recognise complexity cues:** Elderly + cognitive impairment + polypharmacy + lives alone = high-risk BPMH scenario
2. **Initial rapid assessment:** Check eMR for previous admission medication lists; check My Health Record
3. **Contact collateral source:** Call the daughter to obtain medication information
4. **Contact pharmacy:** Identify the patient's pharmacy from any available records; call to obtain dispensing history
5. **Cross-reference:** Compare daughter's report, pharmacy records, and eMR history
6. **Identify discrepancies:** Note any medications in pharmacy records not mentioned by the daughter (possible non-adherence or recent changes)
7. **Document:** Record the verified BPMH with source annotations; flag any medications where verification was incomplete

## Novice Divergence Points

- **Divergence 1:** Novice accepts the patient's vague report ("a lot of tablets") as sufficient and proceeds without collateral sources
- **Divergence 2:** Novice does not recognise the need to contact the daughter or pharmacy, relying only on eMR history
- **Divergence 3:** Novice does not flag incomplete verifications, presenting the BPMH as complete when it is not

## Decisions Exercised

- **[DEC-004](../decisions/select-verification-sources.md)** — Selecting appropriate verification sources for a cognitively impaired patient
- **[DEC-005](../decisions/resolve-conflicting-sources.md)** — Resolving conflicts between daughter's report and pharmacy records

## Complexity Factors Exercised

- **[CX-001](../complexity/polypharmacy-increases-bpmh-difficulty.md)** — Polypharmacy
- **[CX-002](../complexity/patient-communication-barriers.md)** — Cognitive impairment

# Citations

[1] [NCBI — Medication Reconciliation](https://www.ncbi.nlm.nih.gov/books/NBK2648/)
[2] [Australian Government — Guiding Principles](https://www.health.gov.au/sites/default/files/2022-11/guiding-principles-to-achieve-continuity-in-medication-management.pdf)