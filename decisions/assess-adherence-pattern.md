---
type: Decision Point
id: DEC-006
title: Assess Patient Medication Adherence Pattern
slug: assess-adherence-pattern
domain_ref: okf/domain/bpmh-nsw-health.md
certainty: tacit_candidate
sources:
  - ref: okf/references/ho-2026-bpmh-review.md
    citation: "Ho et al. (2026) — adherence documentation requirements"
    accessed: 2026-06-22
related:
  - okf/procedures/collect-medication-information.md
  - okf/concepts/medication-adherence.md
  - okf/gaps/adherence-assessment-cues.md
---

# Assess Patient Medication Adherence Pattern

## Context

This decision occurs during **[PRC-001](../procedures/collect-medication-information.md)** when the clinician is gathering information about each medication.

## Cue

The patient's responses to questions about their medications may suggest non-adherence: vague answers, uncertainty about dose or frequency, or statements like *"I take it when I need it"* for a medication that should be taken regularly.

## Threshold

The clinician must determine: **Is the patient actually taking this medication as prescribed, and if not, what is their actual pattern of use?**

## Competing Considerations

| Consideration | Direction |
|---|---|
| **Non-judgemental approach** | Patients may feel embarrassed about non-adherence; the interview must be supportive |
| **Clinical accuracy** | The BPMH must reflect actual use, not prescribed use |
| **Time** | Thorough adherence probing takes time, which may be limited in acute settings |

## Action Table

| Patient Signal | Expert Action |
|---|---|
| Patient unsure of dose/frequency | Probe gently: *"Can you show me how you take it?"* or *"When did you last take it?"* |
| Patient says "I skip it sometimes" | Document actual pattern: *"Takes metformin 500mg BD most days, skips on weekends"* |
| Patient has stopped medication without telling GP | Document as ceased; flag for prescriber review |
| Patient takes medication differently than prescribed | Document actual use pattern, not the prescribed regimen |

## Gap Note

Sources emphasise the importance of documenting adherence but do not articulate the **specific cues** experts use to detect non-adherence or the **probing strategies** they employ. This is tacit knowledge.

# Citations

[1] [Ho et al. (2026)](https://pmc.ncbi.nlm.nih.gov/articles/PMC12911780/)