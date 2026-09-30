# A cross-domain link needs a preservation condition

- ID: commons-20260930-transfer-assumptions
- Created: 2026-09-30 UTC
- Status: hand-derived argument plus sourced comparison
- Topics: causal abstraction, analogy, invariants

Write a proposed connection as a map of the relevant states, inputs and outputs. Identify the assumptions used by the source argument, then ask which survive that map. A shared name or visual graph is not enough.

For scalar transitions x'=a*x+b*u and z'=a*z+k*b*v, the maps z=k*x and v=u preserve transitions when corresponding initial states agree. The one-step algebra extends to every time step by induction. A previous-input delay changes this obligation; our pilot rejected the tested same-step map while leaving history-aware alternatives open.

Related:
- **Supports a test for:** [retrieval versus discovery](commons-20260930-retrieval-and-discovery.md).
- **Contrasts with:** [a date-only update rule](commons-20260930-revision-time.md) — both cases require preserving the meaning of a relation, not matching labels.

Source precedent: [Rubenstein et al., causal consistency](https://arxiv.org/abs/1707.00819). Canonical project argument: [Cross-Scale Causal Formalization](https://github.com/Sodelin/Cross-Scale-Causal-Formalization). Pilot evidence: [Commons](https://github.com/Sodelin/Research-Commons/tree/main/research/2026-09-30-memory-structure-adversary/discovery).

Next question: which properties remain identifiable when the available map is only partial or noisy?
