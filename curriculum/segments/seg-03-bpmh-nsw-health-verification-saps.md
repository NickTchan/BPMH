---
type: Curriculum Segment
id: SEG-003
title: BPMH NSW Health Segment 03 — Verification Source Selection and Conflict Resolution SAPs
slug: bpmh-nsw-health-seg-03-verification-saps
domain_ref: okf/domain/bpmh-nsw-health.md
certainty: inferred
sources:
  - kb_id: DEC-004
    kb_path: decisions/select-verification-sources.md
  - kb_id: DEC-005
    kb_path: decisions/resolve-conflicting-sources.md
  - kb_id: DEC-006
    kb_path: decisions/assess-adherence-pattern.md
  - kb_id: PRC-001
    kb_path: procedures/collect-medication-information.md
  - kb_id: PRC-002
    kb_path: procedures/verify-medication-history-accuracy.md
  - kb_id: HEUR-001
    kb_path: heuristics/polypharmacy-probing-rule.md
  - kb_id: HEUR-002
    kb_path: heuristics/common-otc-prompt-list.md
  - kb_id: GAP-001
    kb_path: gaps/verification-source-selection-criteria.md
  - kb_id: GAP-002
    kb_path: gaps/conflicting-source-resolution-strategy.md
  - kb_id: GAP-004
    kb_path: gaps/adherence-assessment-cues.md
related: [CUR-001, BLP-001, SEG-002, SEG-004]
generator: CurriculumArchitectAgent
generated: 2026-06-30
---

# BPMH NSW Health Segment 03 — Verification Source Selection and Conflict Resolution SAPs

## Segment Metadata

| Property | Value |
|----------|-------|
| Segment ID | SEG-003 |
| Label | Verification SAPs |
| Segment type | sap_presentation |
| 4C/ID component | Supportive Information (SAPs) |
| Task class | 1, 2 |
| Scaffolding stage | N/A |
| Modality | eLearning |
| Primary purpose | Teach systematic approaches for selecting verification sources, resolving conflicts, and assessing adherence |
| Linked tasks | [TSK-001] |
| Linked decisions | [DEC-004, DEC-005, DEC-006] |
| Linked CDA chains | Chain for [TSK-001] Steps 2, 5–6 |
| Sequence order | 3 |
| Duration estimate (hours) | 1.0 |
| LTEM target tier | 4 (Knowledge) |
| Tooling — primary | LMS module |
| Tooling — supporting | — |

## Rationale

After understanding what discrepancies are (Segment 02), learners need the systematic approaches for building a reliable BPMH in the first place. This segment teaches the SAPs for selecting verification sources [DEC-004], resolving conflicts between sources [DEC-005], and assessing adherence patterns [DEC-006]. These are non-routine problem-solving skills that vary by patient context and cannot be reduced to step-by-step procedures.

## Content Overview

This segment presents three SAPs. First, the verification source selection framework: how to choose which sources to use based on patient context (simple regimen → 2 sources; polypharmacy → 4 sources; aged care → 3 sources; time-pressured → 2 sources with follow-up) [DEC-004]. Second, the conflict resolution framework: how to determine which source to trust when they disagree, considering recency, source type, patient reliability, and clinical plausibility [DEC-005]. Third, the adherence assessment approach: how to probe for actual medication use without making patients defensive [DEC-006]. The segment also covers the polypharmacy probing heuristic [HEUR-001] and the OTC prompt list [HEUR-002].

### What the learner encounters

- Verification source selection action table by patient context [DEC-004]
- Conflict resolution framework with expert action table [DEC-005]
- Adherence assessment action table with patient signals and expert responses [DEC-006]
- Polypharmacy probing rule: ≥5 meds → ≥3 sources + OTC/complementary/PRN probe [HEUR-001]
- OTC prompt list with categories and examples [HEUR-002]
- Flagged gaps: expert criteria for source prioritisation [GAP-001], conflict resolution strategy [GAP-002], adherence cues [GAP-004]

### What the learner produces or performs

- Selects appropriate verification sources for three different patient scenarios
- Resolves a conflicting source scenario by justifying source prioritisation
- Identifies adherence red flags from patient interview transcripts

## Feedback Design

| Feedback Type | When | Focus | Source |
|---------------|------|-------|--------|
| Cognitive | After source selection exercises | Why certain sources are preferred in certain contexts; how experts weigh recency vs. reliability vs. accessibility | [DEC-004], [GAP-001] |
| Cognitive | After conflict resolution exercises | How experts assess source credibility and when to escalate to pharmacy/GP contact | [DEC-005], [GAP-002] |

## LTEM Justification

This segment targets Tier 4 (Knowledge) because the learner comprehends the SAP frameworks and heuristics before applying them in decision-making contexts. The exercises test understanding of the frameworks, not yet independent application under time pressure or with ambiguous information.

## Implementation Notes

- Use interactive scenario-based exercises where learners must select sources and justify their choices.
- Include at least one scenario where the "correct" answer is "I need to call the pharmacy" — to teach learners when verification is insufficient.
- Flag the knowledge gaps [GAP-001, GAP-002, GAP-004] explicitly so learners understand where expert tacit knowledge is still being captured.

## Source Traceability

| KB ID | Path | How used |
|-------|------|----------|
| [DEC-004] | decisions/select-verification-sources.md | Source selection framework |
| [DEC-005] | decisions/resolve-conflicting-sources.md | Conflict resolution framework |
| [DEC-006] | decisions/assess-adherence-pattern.md | Adherence assessment approach |
| [PRC-001] | procedures/collect-medication-information.md | Information collection context |
| [PRC-002] | procedures/verify-medication-history-accuracy.md | Verification context |
| [HEUR-001] | heuristics/polypharmacy-probing-rule.md | Polypharmacy probing rule |
| [HEUR-002] | heuristics/common-otc-prompt-list.md | OTC prompt list |
| [GAP-001] | gaps/verification-source-selection-criteria.md | Flagged gap |
| [GAP-002] | gaps/conflicting-source-resolution-strategy.md | Flagged gap |
| [GAP-004] | gaps/adherence-assessment-cues.md | Flagged gap |
