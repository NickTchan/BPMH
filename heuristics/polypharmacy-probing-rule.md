---
type: Heuristic
id: HEUR-001
title: Polypharmacy Probing Rule
slug: polypharmacy-probing-rule
domain_ref: okf/domain/bpmh-nsw-health.md
certainty: tacit_candidate
sources:
  - ref: okf/references/ncbi-med-rec-overview.md
    citation: "NCBI — Medication Reconciliation"
    accessed: 2026-06-22
related:
  - okf/concepts/polypharmacy.md
  - okf/procedures/collect-medication-information.md
  - okf/gaps/polypharmacy-heuristics.md
---

# Polypharmacy Probing Rule

## Description

When a patient reports taking **5 or more medications**, the expert automatically increases the thoroughness of their verification process.

## Rule

**"If ≥5 medications reported, use ≥3 verification sources and specifically probe for OTC, complementary, and PRN medications."**

## Rationale

Polypharmacy patients are at significantly higher risk of unintentional discrepancies. The more medications a patient takes, the more likely they are to forget some, to take them incorrectly, or to have conflicting information across sources.

## Exception Conditions

- If the patient brings their actual medication containers or a Webster pack, fewer additional sources may be needed
- If the patient is from an aged care facility with a current medication chart, the chart may serve as a reliable single source

## Origin

Inferred from evidence that >50% of hospitalised patients experience UMDs and that polypharmacy is a key risk factor for discrepancies [REF: NCBI; Springer Nature].

# Citations

[1] [NCBI — Medication Reconciliation](https://www.ncbi.nlm.nih.gov/books/NBK2648/)