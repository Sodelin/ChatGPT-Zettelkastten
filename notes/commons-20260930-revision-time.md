# Recording time and revision authority are different

- ID: commons-20260930-revision-time
- Created: 2026-09-30 UTC
- Status: tested finite counterexample; broader protocol proposal
- Topics: time, corrections, provenance

A later file may quote an earlier superseded claim. Selecting the latest timestamp therefore need not select the current conclusion. Preserve explicit correction links and distinguish an event's effective date from the date somebody recorded it.

Related:
- **Limited by:** evidence for the correction; a supersedes field does not make the new claim true.
- **Analogous to:** [transfer assumptions](commons-20260930-transfer-assumptions.md) — typed relations must preserve their meaning, not merely create reachability.

Evidence: [Commons fixture and resolver counterexample](https://github.com/Sodelin/Research-Commons/tree/main/research/2026-09-30-memory-structure-adversary). [LongMemEval](https://arxiv.org/abs/2410.10813) independently studies temporal reasoning and knowledge updates.

Use ordinary Git history for file changes. A current timeline view should link to canonical records rather than duplicate their conclusions. This prototype adds no automatic timeline generator or polling process.

Next test: let a claim change twice and compare retrieval correctness and maintenance edits under the peer audit's longer-history protocol.
