# Research-derived opportunity repository

## Core thesis
The strongest opportunities are control-plane products for systems becoming more autonomous, distributed, and dependent on volatile external services. The recurring unmet needs are verification, provenance, continuity, authorization, calibrated uncertainty, and durable evidence.

## Prioritization method
Ideas were prioritized using five criteria: severity of the observed pain, strength of demand signal, technical defensibility, implementation feasibility, and clarity of a paying customer. Scores are directional integers from 1 to 10. Any statement labeled as an inference is derived from multiple signals rather than directly established by the inputs.

## Recommended build sequence
1. Build dependency continuity controls because the first version can be narrowly scoped to artifact mirroring, integrity verification, and restore testing.
2. Build agent-change verification next because it can integrate into existing code-review workflows and demonstrate measurable reductions in review risk.
3. Add runtime exploit containment as a security-focused product with a high-value incident-response expansion.
4. Explore service withdrawal orchestration after validating demand with organizations operating multiple external dependencies.
5. Treat autonomous transaction controls as a later-stage opportunity beginning with non-custodial authorization and simulation.

## Portfolio risks
The main cross-cutting risks are permission constraints, false positives, integration complexity, unstable external interfaces, privacy exposure, and the possibility that customers view monitoring as optional until a serious incident occurs.