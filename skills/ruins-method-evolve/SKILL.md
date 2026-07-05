# ruins-method-evolve

Use this skill when repeated paper findings should become a forward-only RUINS
method improvement.

## Inputs

- `trigger_paper`: paper that exposed the gap
- `finding`: repeated gap, new ruin condition, scope drift, source-custody gap,
  or register gap
- `change_type`: `Extension`, `Refinement`, or `Reversal`

## Required Reads

Before amending the method, read:

1. `docs/rubric-amendments.md`
2. `docs/capability-expansion.md`
3. `docs/capability-promotion-packet.md`
4. `QUALITY_RUBRIC.md`
5. The triggering paper's `reviews/ROLE_REVIEW.md` and `reviews/SCORECARD.md`
6. Any prior paper that shows the same gap

## Evolution Protocol

1. Classify the change:
   - **Extension:** adds a new evidence surface, capability, register, or scoring
     cue.
   - **Refinement:** tightens an existing rule while preserving old meaning.
   - **Reversal:** rejects an old rule and requires an explicit migration note.
2. Prefer additive changes. RUINS scores are archival records.
3. Update `docs/capability-expansion.md` when the gap is a reusable case
   capability.
4. Use the promotion packet criteria before moving a capability to active or
   core.
5. Update `docs/rubric-amendments.md` when the scoring or package standard
   changes.
6. Update `QUALITY_RUBRIC.md` only when future scoring should change.
7. Do not retroactively rewrite old scorecards. Add a new review file if an old
   paper is revisited.

## Required Evidence

An amendment needs at least one of:

- two papers exposing the same gap,
- one paper that cannot be scored honestly without a new distinction,
- a P2/P3 role finding that names the recurring failure mode,
- a sibling-boundary problem that would otherwise cause scope drift.

## Output Checklist

- [ ] Change classified as Extension, Refinement, or Reversal
- [ ] Trigger paper and finding named
- [ ] Old rule preservation stated
- [ ] Capability map updated if reusable
- [ ] Promotion packet criteria satisfied for active/core state changes
- [ ] Amendment log updated if scoring or process changed
- [ ] Rubric version bumped if scoring semantics changed
