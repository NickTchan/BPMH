---
type: Decision Point
id: DEC-003
title: Distinguish Drug Allergy from Side Effect or Intolerance
slug: distinguish-allergy-from-side-effect
domain_ref: okf/domain/bpmh-nsw-health.md
certainty: documented
sources:
  - ref: okf/references/ho-2026-bpmh-review.md
    citation: "Ho et al. (2026) — BPMH interview asks about allergies"
    accessed: 2026-06-22
  - ref: okf/references/cec-med-rec.md
    citation: "NSW CEC — ADRs must be documented in BPMH"
    accessed: 2026-06-22
related:
  - okf/procedures/collect-medication-information.md
  - okf/concepts/adverse-drug-reaction.md
  - okf/discriminations/identify-immunological-vs-non-immunological-reaction.md
---

# Distinguish Drug Allergy from Side Effect or Intolerance

## Context

This decision occurs during **[PRC-001](../procedures/collect-medication-information.md)** when the patient reports an "allergy" to a medication.

## Cue

The patient states: *"I'm allergic to [medication]."*

## Threshold

The clinician must determine: **Is this a true immunological allergy, or is it a side effect, intolerance, or contraindication?**

## Competing Considerations

| Consideration | Direction |
|---|---|
| **Patient safety** | If uncertain, document as allergy and avoid the medication until clarified |
| **Antimicrobial stewardship** | False allergy labels (especially penicillin) lead to use of broader-spectrum antibiotics with worse outcomes |
| **Time pressure** | Full allergy clarification may not be possible during the initial BPMH interview |
| **Documentation burden** | The reaction description must be specific enough for future clinicians to interpret |

## Action Table

| Patient Description | Classification | Action |
|---|---|---|
| Anaphylaxis, angioedema, Stevens-Johnson syndrome, blistering rash | **True allergy** (severe) | Document as allergy with reaction; avoid medication; flag prominently |
| Hives, itching, rash | **True allergy** (non-severe) | Document as allergy with reaction; avoid medication |
| Nausea, vomiting, headache, diarrhoea | **Side effect / intolerance** | Document as intolerance, not allergy; medication may still be appropriate |
| "It upsets my stomach" | **Side effect / intolerance** | Document as intolerance |
| Patient unsure or cannot describe reaction | **Unclear** | Document as "allergy — reaction unknown"; flag for clarification |

## Linked Discriminations

- **[DISC-002](../discriminations/identify-immunological-vs-non-immunological-reaction.md)** — Identifying immunological reaction descriptors from patient narrative

# Citations

[1] [Ho et al. (2026)](https://pmc.ncbi.nlm.nih.gov/articles/PMC12911780/)
[2] [NSW CEC — Medication Reconciliation](https://cec.health.nsw.gov.au/therapeutics-safety/medicines-improvement/continuity/reconciliation)