---
type: Procedure
id: PRC-009
title: eMR BPMH Documentation Workflow
slug: emr-bpmh-documentation
domain_ref: okf/domain/bpmh-nsw-health.md
certainty: documented
sources:
  - ref: okf/references/cec-med-rec.md
    citation: "NSW CEC - Medication Reconciliation documentation requirements"
    accessed: 2026-06-22
  - ref: okf/references/ho-2026-bpmh-review.md
    citation: "Ho et al. (2026) - eMR workflow guidance"
    accessed: 2026-06-22
related:
  - okf/procedures/compare-bpmh-to-prescribed-medicines.md
  - okf/procedures/collect-medication-information.md
---

# eMR BPMH Documentation Workflow

## Purpose

To provide a step-by-step workflow for documenting BPMH findings in the NSW Health electronic Medical Record (eMR/PowerChart) system.

## Prerequisites

- BPMH interview completed ([PRC-001](../procedures/collect-medication-information.md))
- Comparison against prescribed medicines performed ([PRC-003](../procedures/compare-bpmh-to-prescribed-medicines.md))
- All discrepancies identified and documented

## Documentation Steps

### Step 1: Complete the BPMH Form

- Complete the BPMH form (paper or electronic) with all medications gathered from the patient/caregiver interview and verification sources
- Include: name, dose, frequency, route, formulation, indication (where available)
- Record allergies and adverse drug reactions with specific reaction descriptions
- Note adherence patterns and any reported barriers

### Step 2: Compare Against eMR Orders

- Open the patient's current medication orders in PowerChart
- Perform line-by-line comparison between the completed BPMH and the eMR orders
- Flag all discrepancies (omissions, dose differences, formulation changes, timing mismatches)

### Step 3: Notify the Medical Team

- Present all discrepancies to the prescribing clinician
- Do not resolve discrepancies independently - this requires prescriber input
- Document the notification in the patient's record

### Step 4: Sign, Date, and Time

- Sign the completed BPMH form with your name and professional title
- Record the date and time of completion
- This creates an auditable record of when the BPMH was performed

### Step 5: File in Patient Record

- File the completed BPMH form in the patient's medical record (electronic or paper as per local workflow)
- Ensure the form is accessible to the treating team

## Role Division

- **Pharmacist:** Prepare the BPMH through multi-source verification and patient interview; document findings; support the prescriber with clinical input
- **Prescriber:** Execute the eMR reconciliation; create discharge summary and prescriptions
- **Pharmacist post-step:** Double-check discharge summary and prescriptions for completeness and accuracy

> **Note:** Role division may vary by Local Health District (LHD) and eMR system configuration. Always confirm local workflow expectations.

# Citations

[1] [NSW CEC - Medication Reconciliation](https://cec.health.nsw.gov.au/therapeutics-safety/medicines-improvement/continuity/reconciliation)
[2] [Ho et al. (2026)](https://pmc.ncbi.nlm.nih.gov/articles/PMC12911780/)
