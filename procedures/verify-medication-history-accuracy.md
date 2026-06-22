---
type: Procedure
id: PRC-002
title: Verify Medication History Accuracy to Achieve BPMH
slug: verify-medication-history-accuracy
domain_ref: okf/domain/bpmh-nsw-health.md
certainty: documented
sources:
  - ref: okf/references/cec-med-rec.md
    citation: "NSW CEC — Medication Reconciliation Step 2"
    accessed: 2026-06-22
  - ref: okf/references/ho-2026-bpmh-review.md
    citation: "Ho et al. (2026) — BPMH requires at least two sources"
    accessed: 2026-06-22
  - ref: okf/references/nsw-health-pd2022-032.md
    citation: "NSW Health PD2022_032"
    accessed: 2026-06-22
related:
  - okf/tasks/obtain-bpmh-admission.md
  - okf/decisions/select-verification-sources.md
  - okf/decisions/resolve-conflicting-sources.md
  - okf/concepts/best-possible-medication-history.md
---

# Verify Medication History Accuracy to Achieve BPMH

## Purpose

To confirm the accuracy of the preliminary medication list obtained from the patient interview by cross-referencing at least one additional independent source, thereby achieving a Best Possible Medication History.

## Procedure Steps

### Step 1: Identify Available Verification Sources
- Patient's own medication list or Webster pack (dose administration aid)
- Community pharmacy dispensing records
- GP referral letter or medication list
- My Health Record (national PHR)
- Previous hospital eMR records
- Aged care facility medication chart (if applicable)
- Specialist clinic letters

### Step 2: Cross-Reference Each Medication
For each medication on the preliminary list:
- Compare name, dose, frequency, and route against the verification source(s)
- Note any discrepancies between the patient's report and the source
- If the patient reports a medication not found in any source, assess credibility (see **[DEC-005](../decisions/resolve-conflicting-sources.md)**)
- If a source lists a medication the patient does not report, assess whether the patient has ceased it, is non-adherent, or has forgotten

### Step 3: Resolve Conflicts
- When sources conflict, use clinical judgement to determine the most accurate information → **[DEC-005](../decisions/resolve-conflicting-sources.md)**
- Contact the community pharmacy or GP directly if needed to clarify
- Document the source of each verified medication

### Step 4: Finalise the BPMH
- Record the verified BPMH in the eMR or clinical record
- Ensure all medications have: name, dose, frequency, route (and indication where available)
- Document allergies and ADRs with reaction details
- Note any medications where verification was incomplete and the reason

## Decision Points

- **[DEC-004](../decisions/select-verification-sources.md)** — Which sources to prioritise for verification
- **[DEC-005](../decisions/resolve-conflicting-sources.md)** — How to resolve conflicts between sources

## Output

A verified Best Possible Medication History documented in the patient's clinical record.

# Citations

[1] [NSW CEC — Medication Reconciliation](https://cec.health.nsw.gov.au/therapeutics-safety/medicines-improvement/continuity/reconciliation)
[2] [Ho et al. (2026)](https://pmc.ncbi.nlm.nih.gov/articles/PMC12911780/)
[3] [NSW Health PD2022_032](https://www1.health.nsw.gov.au/pds/ActivePDSDocuments/PD2022_032.pdf)