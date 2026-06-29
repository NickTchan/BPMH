---
type: Whole Task
id: TSK-003
title: Supply Accurate Medicines Information at Discharge
slug: supply-medicines-info-discharge
domain_ref: okf/domain/bpmh-nsw-health.md
certainty: documented
sources:
  - ref: okf/references/cec-med-rec.md
    citation: "NSW CEC — Medication Reconciliation Step 4"
    accessed: 2026-06-22
  - ref: okf/references/nsw-health-pd2022-032.md
    citation: "NSW Health PD2022_032"
    accessed: 2026-06-22
  - ref: okf/references/health-gov-au-guiding-principles.md
    citation: "Australian Government — Guiding Principles"
    accessed: 2026-06-22
related:
  - okf/procedures/supply-medicines-information.md
---

# Supply Accurate Medicines Information at Discharge

## Task Description

The process of providing the patient and the next care provider (GP, community pharmacist, aged care facility, or receiving hospital) with an accurate, current, and comprehensive medicines list, including reasons for any changes made during the hospital episode.

## Task Boundary

**Starts when:** The decision to discharge the patient is made and the discharge medication plan is finalised.

**Ends when:** The patient has received their medicines information and the receiving clinician/provider has been communicated the updated medication plan.

## Discharge Reconciliation Workflow

The discharge process involves multiple coordinated phases:

### Phase 1: Pre-Discharge BPMH Preparation
- Conduct multi-source medication verification (pharmacy records, GP lists, patient interview)
- Reconcile any discrepancies identified during the admission BPMH
- Ensure the medication history is current and complete before discharge planning begins

### Phase 2: Medication Chart Plan Review
- Review every medication on the patient's chart with a clear plan for each:
  - **Continue** — unchanged from admission or current inpatient regimen
  - **Change** — dose, frequency, route, or formulation modification
  - **Decrease** — dose reduction (e.g., tapering)
  - **Increase** — dose escalation
  - **Cease** — medication stopped entirely
- Document the rationale for each decision

### Phase 3: EMR Reconciliation Execution
- The prescriber performs the actual EMR reconciliation, opening the reconciliation screen with the medication history on one side and final outcomes on the other
- The prescriber creates the discharge summary and prescriptions based on the reconciled plan
- This step is prescriber-led; the pharmacist supports by providing the prepared BPMH and clinical input

### Phase 4: Pharmacist Double-Check
- The pharmacist reviews the discharge summary and prescriptions for completeness and accuracy
- Verify that all medication changes are correctly reflected in the discharge documentation
- Check for drug interactions, dosing errors, or omissions

### Phase 5: Stakeholder Communication Cascade
- **Patient and carers:** Provide written medicines information with clear explanations of changes
- **Residential facilities:** Communicate updated medication plans to aged care or disability facilities
- **Dispensing pharmacy:** Notify the community pharmacy for dose administration aid (Webster pack) repacks when medications have changed
- **GP and receiving clinicians:** Send the reconciled medication list via standardised discharge summary

### Telehealth/VMM Considerations
- When discharge counselling occurs via telehealth, ensure camera-on where possible to assess patient understanding
- Physical medication examination (e.g., showing the patient their actual pills) is not possible — compensate with clear verbal descriptions and follow-up hard-copy documentation
- Phone-only consultations require additional verification steps to confirm patient comprehension

## Constituent Procedures

- **[PRC-004](../procedures/supply-medicines-information.md)** — Supply accurate medicines information to the patient and next care provider

# Citations

[1] [NSW CEC — Medication Reconciliation](https://cec.health.nsw.gov.au/therapeutics-safety/medicines-improvement/continuity/reconciliation)
[2] [NSW Health PD2022_032](https://www1.health.nsw.gov.au/pds/ActivePDSDocuments/PD2022_032.pdf)
[3] [Australian Government — Guiding Principles](https://www.health.gov.au/sites/default/files/2022-11/guiding-principles-to-achieve-continuity-in-medication-management.pdf)