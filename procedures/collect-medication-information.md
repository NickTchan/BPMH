---
type: Procedure
id: PRC-001
title: Collect Medication Information for BPMH
slug: collect-medication-information
domain_ref: okf/domain/bpmh-nsw-health.md
certainty: documented
sources:
  - ref: okf/references/cec-med-rec.md
    citation: "NSW CEC — Medication Reconciliation Step 1"
    accessed: 2026-06-22
  - ref: okf/references/ho-2026-bpmh-review.md
    citation: "Ho et al. (2026) — BPMH Interview Guide questions"
    accessed: 2026-06-22
  - ref: okf/references/who-high5s-sop.md
    citation: "WHO High5s SOP — Step 1: BPMH"
    accessed: 2026-06-22
related:
  - okf/tasks/obtain-bpmh-admission.md
  - okf/decisions/select-verification-sources.md
  - okf/decisions/distinguish-allergy-from-side-effect.md
  - okf/concepts/best-possible-medication-history.md
---

# Collect Medication Information for BPMH

## Purpose

To gather a comprehensive list of all medicines the patient is currently taking, using a systematic interview process and initial source review.

## Procedure Steps

### Step 1: Prepare for the Interview
- Review available clinical notes (admission notes, past medical history, chief complaint)
- Identify any existing medication lists in the eMR or paper chart
- Note the patient's presenting condition and any factors that may affect their ability to participate (cognitive status, language, acuity)

### Step 2: Conduct the Patient/Carer Interview
Use open-ended questions and a systematic process (per the CEC BPMH Interview Guide):

1. **Pharmacy identification:** *"What is the name and location of the pharmacies you use?"*
2. **Non-pharmacy medications:** *"Are you taking medications that are not dispensed for you or not from your pharmacy?"*
3. **Allergies and ADRs:** *"Do you have any allergies to medications or food?"* → If yes, probe for reaction details → **[DEC-003](../decisions/distinguish-allergy-from-side-effect.md)**
4. **Regular medications:** For each medication the patient takes regularly and "as needed":
   - Name of medication
   - Dose (how many)
   - Frequency (how often)
   - Timing (when)
   - Last dose taken
   - Indication (what do you take it for)
5. **OTC medications:** *"Do you take any medications that you buy without a prescription?"*
6. **Prompted recall:** *"To make sure I have not missed anything, do you take any of the following: daily aspirin, pain medicine, sleep aids...?"*
7. **Complementary medicines:** *"Do you take any natural health products or complementary medicines? For example: vitamins, minerals, supplements, homeopathic or naturopathic medicine?"*
8. **Alcohol use:** *"How often do you drink alcohol in a week? What type?"*
9. **Support systems:** *"Is there anyone who helps you with your medications?"*
10. **Adherence barriers:** *"Is there anything that makes taking your medications difficult?"*

### Step 3: Record the Information
- Document each medication with: name, dose, frequency, route, indication (where available)
- Record allergies and adverse drug reactions with reaction details
- Note any reported adherence issues or recent medication changes

## Decision Points

- **[DEC-004](../decisions/select-verification-sources.md)** — Which additional sources to use for verification
- **[DEC-003](../decisions/distinguish-allergy-from-side-effect.md)** — Distinguish reported allergy from side effect

## Output

A preliminary medication list ready for verification (Step 2 of the BPMH process).

# Citations

[1] [NSW CEC — Medication Reconciliation](https://cec.health.nsw.gov.au/therapeutics-safety/medicines-improvement/continuity/reconciliation)
[2] [Ho et al. (2026)](https://pmc.ncbi.nlm.nih.gov/articles/PMC12911780/)
[3] [WHO High5s SOP](https://cdn.who.int/media/docs/default-source/patient-safety/high5s/h5s-sop.pdf?sfvrsn=594d8e49_4)