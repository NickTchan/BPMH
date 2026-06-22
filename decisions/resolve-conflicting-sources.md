---
type: Decision Point
id: DEC-005
title: Resolve Conflicting Medication Information Sources
slug: resolve-conflicting-sources
domain_ref: okf/domain/bpmh-nsw-health.md
certainty: tacit_candidate
sources:
  - ref: okf/references/ho-2026-bpmh-review.md
    citation: "Ho et al. (2026) — BPMH verification process"
    accessed: 2026-06-22
  - ref: okf/references/who-high5s-sop.md
    citation: "WHO High5s SOP"
    accessed: 2026-06-22
related:
  - okf/procedures/verify-medication-history-accuracy.md
  - okf/gaps/conflicting-source-resolution-strategy.md
---

# Resolve Conflicting Medication Information Sources

## Context

This decision occurs during **[PRC-002](../procedures/verify-medication-history-accuracy.md)** when two or more verification sources provide conflicting information about a medication.

## Cue

The patient reports taking Medication X at Dose A, but the pharmacy record shows Dose B, and the GP letter shows the medication was ceased 3 months ago.

## Threshold

The clinician must determine: **Which source most accurately reflects what the patient is actually taking right now?**

## Competing Considerations

| Consideration | Direction |
|---|---|
| **Recency** | The most recent source is generally more reliable, but not always (e.g., a recent prescription may not have been filled) |
| **Source type** | Dispensing records confirm the medication was supplied; prescription records only confirm it was prescribed |
| **Patient reliability** | Some patients are highly reliable; others have cognitive impairment or poor recall |
| **Clinical plausibility** | Does the patient's reported regimen make clinical sense given their diagnoses? |
| **Practical constraints** | Contacting the pharmacy or GP takes time; is the information needed urgently? |

## Action Table

| Conflict Scenario | Expert Action |
|---|---|
| Patient report vs. pharmacy dispensing record | Contact pharmacy to confirm most recent dispense; ask patient to show medication containers if available |
| GP letter vs. pharmacy record | Pharmacy record is more reliable for what was actually dispensed; GP letter may reflect intended but not filled prescriptions |
| Multiple pharmacy records conflict | Contact the most recently used pharmacy; ask the patient which pharmacy they currently use |
| Patient reports medication not in any source | Assess clinical plausibility; ask patient to show containers; consider that the medication may be from a different prescriber or jurisdiction |

## Gap Note

Sources describe the need to resolve conflicts but do not articulate the **expert's decision framework** for prioritising sources or the **heuristics** used to assess source reliability. This is tacit knowledge.

# Citations

[1] [Ho et al. (2026)](https://pmc.ncbi.nlm.nih.gov/articles/PMC12911780/)
[2] [WHO High5s SOP](https://cdn.who.int/media/docs/default-source/patient-safety/high5s/h5s-sop.pdf?sfvrsn=594d8e49_4)