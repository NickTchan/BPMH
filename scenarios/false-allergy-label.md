---
type: Scenario
id: SCN-002
title: Patient with False Penicillin Allergy Label
slug: false-allergy-label
domain_ref: okf/domain/bpmh-nsw-health.md
certainty: inferred
sources:
  - ref: okf/references/ho-2026-bpmh-review.md
    citation: "Ho et al. (2026) — BPMH interview allergy questions"
    accessed: 2026-06-22
  - ref: okf/references/cec-med-rec.md
    citation: "NSW CEC — ADR documentation"
    accessed: 2026-06-22
related:
  - okf/decisions/distinguish-allergy-from-side-effect.md
  - okf/discriminations/identify-immunological-vs-non-immunological-reaction.md
  - okf/concepts/adverse-drug-reaction.md
---

# Patient with False Penicillin Allergy Label

## Classification

`routine` (common presentation with significant downstream impact)

## Scenario Description

A 45-year-old patient is admitted for elective surgery. During the BPMH interview, they state: *"I'm allergic to penicillin."* When asked what happens, they reply: *"It made me feel sick to my stomach."* The eMR shows a penicillin allergy flag from a previous admission 5 years ago, with no reaction details documented.

## Expert Pathway

1. **Probe for reaction details:** *"Can you tell me more about what happened? Was it a rash, swelling, or just nausea?"*
2. **Classify:** Nausea is a side effect, not an immunological allergy → **[DEC-003](../decisions/distinguish-allergy-from-side-effect.md)**
3. **Document accurately:** Record as "penicillin — intolerance (nausea), not allergy"
4. **Flag for delabeling:** Note that the allergy flag in eMR should be updated to prevent future inappropriate antibiotic avoidance
5. **Communicate:** Inform the surgical team that penicillin-class antibiotics are not contraindicated

## Novice Divergence Points

- **Divergence 1:** Novice accepts "allergic to penicillin" at face value and documents it as an allergy without probing
- **Divergence 2:** Novice does not recognise the clinical significance of a false allergy label (broader-spectrum antibiotics, increased cost, resistance risk)
- **Divergence 3:** Novice does not distinguish between the patient's current report and the outdated eMR flag

## Decisions Exercised

- **[DEC-003](../decisions/distinguish-allergy-from-side-effect.md)** — Distinguishing allergy from side effect

## Discriminations Exercised

- **[DISC-002](../discriminations/identify-immunological-vs-non-immunological-reaction.md)** — Identifying non-immunological reaction from patient narrative

# Citations

[1] [Ho et al. (2026)](https://pmc.ncbi.nlm.nih.gov/articles/PMC12911780/)
[2] [NSW CEC — Medication Reconciliation](https://cec.health.nsw.gov.au/therapeutics-safety/medicines-improvement/continuity/reconciliation)