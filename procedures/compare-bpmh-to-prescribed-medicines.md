---
type: Procedure
id: PRC-003
title: Compare BPMH Against Prescribed Medicines
slug: compare-bpmh-to-prescribed-medicines
domain_ref: okf/domain/bpmh-nsw-health.md
certainty: documented
sources:
  - ref: okf/references/cec-med-rec.md
    citation: "NSW CEC — Medication Reconciliation Step 3"
    accessed: 2026-06-22
  - ref: okf/references/acsqhc-med-safety-standard.md
    citation: "ACSQHC — Medication Safety Standard"
    accessed: 2026-06-22
  - ref: okf/references/who-high5s-sop.md
    citation: "WHO High5s SOP"
    accessed: 2026-06-22
related:
  - okf/tasks/reconcile-medicines-transfer.md
  - okf/decisions/classify-discrepancy-intentional-vs-unintentional.md
  - okf/decisions/resolve-unintentional-discrepancy.md
  - okf/concepts/medication-discrepancy.md
---

# Compare BPMH Against Prescribed Medicines

## Purpose

To systematically compare the verified Best Possible Medication History against the medication orders written by the treating team, identifying all discrepancies for classification and resolution.

## Procedure Steps

### Step 1: Obtain the Current Medication Orders
- Access the patient's current medication chart (eMR or paper)
- Ensure all active orders are visible

### Step 2: Perform Line-by-Line Comparison
For each medication on the BPMH:
- Check if it appears in the current orders
- If present, compare: name, dose, frequency, route
- If absent, flag as a potential **omission discrepancy**

For each medication in the current orders:
- Check if it appears on the BPMH
- If absent from BPMH but present in orders, flag as a potential **commission discrepancy** (new medication or patient unaware)

### Step 3: Document All Discrepancies
- Record each identified discrepancy
- Do not yet classify as intentional or unintentional — this is a separate decision → **[DEC-001](../decisions/classify-discrepancy-intentional-vs-unintentional.md)**

### Step 4: Communicate Findings
- Present discrepancies to the prescribing clinician
- Collaborate to classify and resolve each discrepancy

## Decision Points

- **[DEC-001](../decisions/classify-discrepancy-intentional-vs-unintentional.md)** — Classify each discrepancy
- **[DEC-002](../decisions/resolve-unintentional-discrepancy.md)** — Determine action for unintentional discrepancies

## Output

A documented list of all identified discrepancies, classified and with resolution actions.

# Citations

[1] [NSW CEC — Medication Reconciliation](https://cec.health.nsw.gov.au/therapeutics-safety/medicines-improvement/continuity/reconciliation)
[2] [ACSQHC — Medication Safety Standard](https://www.safetyandquality.gov.au/national-standards/nsqhs-standards/medication-safety-standard)
[3] [WHO High5s SOP](https://cdn.who.int/media/docs/default-source/patient-safety/high5s/h5s-sop.pdf?sfvrsn=594d8e49_4)