# Ask which target is identifiable before reconstructing everything

- ID: commons-20260930-identification
- Created: 2026-09-30 UTC
- Status: reuse of an existing hand-derived result; no new theorem or Lean verification
- Topics: identification, partial observation, research triage

An existing [Commons argument](https://github.com/Sodelin/Research-Commons/blob/437462ace5fa237246f2dbc6e6767a9874d74214/notes/2026-09-30-commons-builder-cross-scale-argument.md) states: a target q can be decoded from observations O exactly when q is constant on every set of models sharing the same observations. This statement is relative to the declared model class and observation map.

**Valid reuse:** with theta in {-1,+1} and observation theta squared, the target theta squared is identifiable. Complete reconstruction of theta is unnecessary for that target.

**Invalid reuse:** the target sign(theta) is not identifiable from that same observation. Both compatible models must remain; a similar-looking shadow supplies no missing sign information. Likewise, the source's two causal models share an observational distribution but disagree after an intervention.

**Important correction:** deciding an action is a different target. A [published correction](https://github.com/Sodelin/Research-Commons/blob/437462ace5fa237246f2dbc6e6767a9874d74214/notes/2026-09-30-commons-builder-decision-certificate-correction.md) shows why pairwise compatibility may miss a whole-set decision obstruction. Retain the deterministic-action and loss assumptions.

Related:
- **Provides a check for:** [discovery candidates](commons-20260930-retrieval-and-discovery.md) — specify the target and compatible alternatives.
- **Requires:** [transfer assumptions](commons-20260930-transfer-assumptions.md) when applying a result across model classes.
- **Uses a correction recorded by:** [revision time](commons-20260930-revision-time.md).

Next action: first look for an existing result addressing the actual target. Request a new proof only if a concrete unresolved obligation remains. These examples check use of the existing result; they establish no diagnostic or real-world causal model.
