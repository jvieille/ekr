# EKR Architectural Guidance — Open Questions

**Status: Draft Guidance — open-question backlog**  
**Current development target: V0.1**

These questions are the current starting points for the V0.1 development cycle of EKR Architectural Guidance. They are intentionally open: the repository is seeking challenges, counterexamples, alternative formulations, implementation experience and relevant evidence.

Published research, including Article 2 and FCP-PILOT-01, may propose candidate answers or testable formulations. Publication or inclusion in Draft Guidance does **not** close these questions by itself.

The questions themselves may be revised as the work develops.

## Purpose and minimum representation

1. **What is the minimum representation information required before a cross-boundary interaction can be considered adequately governed?**

## Shared foundation and domain autonomy

2. **Which commitments must belong to the shared EKR representation foundation, and which should remain domain-specific?**

## Authority and representation construction

3. **When should knowledge remain source-resident and be projected, versus be contributed directly under EKR authority?**

4. **How should authority, provenance, version and validity be represented when multiple sources describe different aspects of the same operational reality?**

## Conformance, fitness and plurality

5. **How should conformance to an EKR foundation be distinguished from fitness of a representation for a particular operational purpose?**

6. **How should multiple viewpoints and granularities coexist without collapsing into one enterprise decomposition?**

## EKR boundary and downstream capabilities

7. **Where should EKR responsibilities stop and semantic mediation, compatibility assessment, coordination or execution begin?**

## Security, classification and sovereignty

8. **What representation-level security, classification and sovereignty controls are required beyond data access control?**

## Relationship to established approaches

9. **How can existing OPC UA, Asset Administration Shell (AAS), Unified Namespace (UNS)/DataOps, ontology, knowledge-graph and data-platform capabilities be assessed by architectural responsibility rather than by product category?**

## Evidence and examples

10. **What should worked examples or implementation cases demonstrate to provide useful evidence for the first Guidance release, and what would make such examples or cases misleading?**

## FCP sufficiency and independent assessment

11. **What is the smallest set of F1–F4-style commitments whose conformance can be assessed reproducibly across independent implementations or exposure arrangements?**

12. **What evidence, evaluator information, dependencies and uncertainty handling are required for two independent assessors to reach concordant or explainably different conformance verdicts?**

## Mapping-process governance and mediation boundary

13. **Can a mapping or mediation-process representation and its resulting correspondence assertions be interpreted and audited without treating the external mediation engine itself as part of EKR?**

14. **When a source authority endorses a mapping, what additional evidence is still required to assess semantic fidelity, scope, version and fitness independently?**

## Continuity beyond platform replacement

15. **Which identities, definitions, histories, provenance, mapping specifications and participation dependencies must survive technology replacement for interpretation and accountability to remain usable, and who is responsible for verifying that continuity?**

## DSPs and effective participation commitments

16. **When do optional Domain Semantic Profile (DSP) commitments become part of the effective contract of a particular participation arrangement, and how should their authority, versioning and withdrawal be governed?**

## Comparative value of candidate FCP discipline

17. **Does an FCP-style discipline add measurable value beyond combinations of existing semantic contracts, knowledge graphs, API standards, metadata platforms and governance mechanisms, and under what conditions?**

## How to contribute to these questions

A useful contribution may:

- propose a sharper formulation of a question;
- identify a missing question;
- provide a counterexample;
- describe an implementation constraint or case;
- show that an established approach already addresses part of the question;
- provide a primary reference or evidence source;
- explain why a proposed EKR responsibility would be too broad, too narrow or placed at the wrong architectural boundary.

Current research-transfer material is tracked in [Issue #21](https://github.com/jvieille/ekr/issues/21) and the [Architectural Guidance Transfer Note](../proposals/ARCHITECTURAL-GUIDANCE-TRANSFER-2026-11-16.md).

See the repository [CONTRIBUTING.md](../CONTRIBUTING.md) for contribution routes and status rules.
