---
type: Risk
id: RISK-002
title: Incomplete BPMH Propagates Errors Through Episode of Care
slug: incomplete-bpmh-propagates-errors
domain_ref: okf/domain/bpmh-nsw-health.md
certainty: documented
sources:
  - ref: okf/references/cec-med-rec.md
    citation: "NSW CEC — Medication Reconciliation"
    accessed: 2026-06-22
  - ref: okf/references/acsqhc-med-safety-standard.md
    citation: "ACSQHC — Medication Safety Standard"
    accessed: 2026-06-22
related:
  - okf/procedures/collect-medication-information.md
  - okf/procedures/verify-medication-history-accuracy.md
---

# Incomplete BPMH Propagates Errors Through Episode of Care

## Description

If the BPMH is incomplete or inaccurate, every subsequent prescribing decision during the hospital episode is based on flawed information, compounding the risk of harm.

## Where It Manifests

- **[PRC-001](../procedures/collect-medication-information.md)** — Incomplete patient interview
- **[PRC-002](../procedures/verify-medication-history-accuracy.md)** — Inadequate verification

## Early Warning Signs

- BPMH obtained from a single source only
- Patient interview conducted without a structured guide
- OTC and complementary medications not specifically probed
- Allergy information incomplete or vague

## Novice Vulnerability

Novices may consider the BPMH "complete" after a brief interview, not recognising that patients routinely omit OTC medications, complementary products, and medications they take irregularly.

## Impact

- Drug–drug interactions missed
- Duplicate therapy prescribed
- Chronic medications omitted
- Allergic reactions triggered

## Mitigation

- Use of structured interview guides (CEC BPMH Interview Guide)
- Mandatory multi-source verification
- Pharmacist review of all BPMHs for high-risk patients

# Citations

[1] [NSW CEC — Medication Reconciliation](https://cec.health.nsw.gov.au/therapeutics-safety/medicines-improvement/continuity/reconciliation)
[2] [ACSQHC — Medication Safety Standard](https://www.safetyandquality.gov.au/national-standards/nsqhs-standards/medication-safety-standard)