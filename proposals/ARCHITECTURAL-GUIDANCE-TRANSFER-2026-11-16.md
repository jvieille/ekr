# EKR — Architectural Guidance Transfer Note

**Status:** Proposal / candidate Guidance material / non-canonical  
**Date:** 16 November 2026  
**Tracking issue:** #21

This note transfers bounded architectural findings from the Article 2 investigation to the public EKR Architectural Guidance development process. It does not change the canonical Working Definition, and publication of the referenced research outputs does not itself confer Draft or Released Guidance status.

## 1. Purpose and source lineage

The initial research brief required repository-first investigation, explicit falsification and separation between established EKR principles, candidate Guidance and untested hypotheses. The investigation has now produced two published research outputs:

- **Canonical basis:** Jean Vieille, *Enterprise Knowledge Representation — Working Definition V0.1*. DOI: https://doi.org/10.5281/zenodo.21914714
- **Context:** Jean Vieille, *Beyond Data: Why Knowledge Representation Is an Enterprise Architecture Concern*. DOI: https://doi.org/10.5281/zenodo.22918368
- **Architectural proposal:** Jean Vieille, *Distributed Knowledge Representations, Shared Foundation and Semantic Interfaces*, Version 1.0, 16 November 2026. DOI: https://doi.org/10.5281/zenodo.24284087
- **Experimental evidence design:** Jean Vieille, *FCP-PILOT-01: Candidate Foundation Conformance Profile — Investigation V0.4*, 16 November 2026. DOI: https://doi.org/10.5281/zenodo.24284040
- **Repository baseline:** `guidance/ARCHITECTURAL-GUIDANCE.md`, `guidance/OPEN-QUESTIONS.md` and `guidance/CHANGELOG.md` (Working Draft V0.1; not Released Guidance).

The article states an exploratory architectural proposition; FCP-PILOT-01 provides candidate obligations and test designs. Neither is a standard or a released conformance profile.

## 2. Executive transfer decisions

| Item | Proposed transfer |
|---|---|
| Established / retain | Plural, purpose-bound, independently governed representations; distributed authority; no mandated EKR platform or universal domain model; mediation and execution remain outside EKR under the current framing. |
| Candidate Guidance | Shared participation commitments F1–F4; scoped FCPs with evidence; TBP vs TEP; A/B/C exposure patterns; accountable external correspondences and mapping-process descriptions; continuity across platform replacement. |
| Still experimental | Sufficiency of F1–F4; formal FCP conformance criteria; reproducibility across independent implementations; interpretation agreement; comparative costs/benefits of A/B/C. |
| Not endorsed | Mandatory NRO technology; one canonical serialization; mandatory central graph; universal ontology; automatic equivalence from identifiers; automatic fitness or permission to act. |

## 3. Candidate participation architecture

The foundation concerns abstract reading and governance commitments, not a universal serialization of domain knowledge. FCP obligations apply to a declared exposure scope and may be fulfilled by a documented arrangement of source systems, extensions, bindings and accountable dependencies.

Compliance is not equivalent to semantic fidelity, truth, fitness for use, permission or achieved interoperation.

### Foundation and implementation artefacts

| Item | Proposed transfer |
|---|---|
| F1 / G1–G3 | Reading constructs: representation, sign/representation element, referent, statement, relation, statement kinds and reading conventions. |
| F2 / O1–O3 | Minimal ontological distinctions and autonomy of each UOD; the same element may itself serve as a referent in another representation. |
| F3 / I1–I3 | Identifier scope, typed relations, interpretation references, explicit justification of cross-authority identity claims. |
| F4 / V1–V4 | Authority, purpose, publication scope, relevant times, provenance, revision/withdrawal and conformance evidence. |
| FCP | A specified, versioned, scoped set of required commitments, admissible evidence, evaluator and assessment rules. |
| TBP | Technology Binding Profile: how native constructs, services, adapters and complements cover applicable FCP obligations. |
| TEP | Technical Exposure Profile: technical discovery, access, operations, common exposure model and serialization when adopted. |
| DSP | Optional supplementary domain, cross-domain or global semantic commitments; may be mandatory within a particular chosen participation arrangement. |
| Semantic interface | The logical boundary by which relevant meanings, identities, qualifications and responsibilities are accessible; not necessarily a single endpoint. |

### Exposure arrangement versus coverage state

| Item | Proposed transfer |
|---|---|
| A — Native | Requirements met through the source information model/services/governance, including native extensions where necessary. |
| B — Binding / augmentation | Native content remains available; governed bindings and/or supplements supply applicable reading or accountability commitments. |
| C — Common form | Selected knowledge made consumable in an agreed technical form, materialized or generated on demand; no implied shared domain ontology. |
| Coverage per obligation | Native / Extended / Delegated / Unsupported / Not applicable (justified) — orthogonal to A/B/C. A common-form exposure can still fail F4. |

## 4. Boundary: referring, asserting, mediating and publishing

The research distinguishes:

1. a reference to an element governed elsewhere;
2. a situated assertion, such as “physical asset EQ-4732 installed at engineering position P-101 during a specified interval”;
3. a general mediation/mapping process between conceptual constructs in distinct UODs.

A situated installation assertion need not define a reusable translation across conceptual models.

An external mediation process may connect one or several inputs to one or several outputs, with declared transformation rules and interpretive assumptions. The mapping specification is itself representable and governable under a declared UOD, as are its resulting correspondence assertions. Their authorship, authority, versions, evidence, dependencies, status, applicability and revision conditions can be exposed through EKR.

**Representing or governing the process is not performing, negotiating, validating or authorizing semantic mediation.**

A Technology Binding Profile associates native constructs with FCP reading roles and should not be equated with external semantic mediation between independently governed models. Where common-form exposure requires semantic reconciliation across UODs, that work remains separately accountable; FCP conformance of the output cannot establish correctness of the reconciliation.

NRO may illustrate one possible pattern for representing mapping processes, but it is neither required nor designated as foundation technology for EKR. Guidance text should remain technology-neutral.

## 5. Continuity beyond platform replacement

Interoperability should not be stranded in a particular source, catalog, graph or integration tool.

For each declared participation scope, architecture decisions should identify preservation, portability and retirement obligations for:

- identifiers and resolution rules;
- definitions and versions;
- governed assertions and temporal history;
- provenance, evidence and qualifications;
- mapping-process specifications and generated correspondence assertions;
- FCP/TBP/TEP dependencies.

Raw-data export is insufficient where interpretive context is lost.

Continuity remains conditional on rights, retention periods, withdrawal, sovereignty and authorized access. EKR does not itself implement migration or claim platform independence has already been achieved; it should make preservation commitments explicit and assessable.

## 6. Evaluation programme to transfer — not completed

Recommended evidence directions:

- retain T01–T08 and X01–X04 as unexecuted candidate tests;
- compare A/B/C using the same declared knowledge and consumer decisions;
- measure interpretation disagreement, unjustified cross-identity claims, missing-evidence handling, semantic fidelity, producer/consumer effort, update burden and status drift;
- add a continuity counter-test based on platform substitution;
- keep testing of FCP bindings distinct from assessment of published mediation assertions and from evaluation of the mediation algorithm or operational execution itself;
- do not treat API/schema/SHACL success as proof of semantic fidelity or fitness.

## 7. Guidance integration targets

| Guidance area | Candidate transfer |
|---|---|
| §3 Non-goals | Reaffirm that EKR can represent and govern mediation specifications/results but does not perform semantic mediation, compatibility decisions, orchestration or execution. |
| §4 Responsibility lens | Add FCP / TBP / TEP / semantic-interface distinctions if review supports them; keep source-to-FCP binding distinct from mapping across UODs. |
| §5 Authority / construction | Add situational assertions and mapping-process representations, including independent authorship and governance of derived claims. |
| §6 Shared foundation | Describe candidate F1–F4 and experimental FCP structure without claiming sufficiency or mandatory syntax. |
| §7 Multiple UODs | Recognize cross-domain UODs and contextual or mapping UODs; do not impose one UOD per domain. |
| §8 Lifecycle / validation | Separate compliance, fidelity, fitness and authorization; add continuity after platform substitution. |
| §10 Patterns and evidence | Add A/B/C arrangements, P-101 responsibilities, FCP-PILOT evidence levels and falsification tests. |

### Repository follow-up

- Track the proposal in Issue #21.
- Update `OPEN-QUESTIONS.md` with FCP sufficiency, independent conformance, mapping-process governance and post-migration semantic continuity.
- Prepare a focused Guidance PR with changelog and traceability.
- Do not close open questions merely because a research article proposes an answer.
- Review Roadmap impact separately from Guidance acceptance.
- Release Guidance only through the existing governed release process.

## 8. Decision questions and open boundaries

- What is the smallest F1–F4 commitment set whose conformance can be assessed by independent implementations?
- Which obligations require authoritative source changes versus independently governed supplements?
- Can a mapping-process representation and its resulting claims be interpreted and audited without treating the external mediation engine as part of EKR?
- Does an endorsed mapping preserve native meaning, or is independent fidelity assessment still needed?
- Which information and accountability obligations survive technology replacement, and who must verify them?
- When do optional DSP commitments become part of the effective contract of a participation arrangement?
- Does an FCP add measurable value beyond combinations of existing semantic contracts, knowledge graphs, API standards and metadata platforms?

## 9. Publication and release dependencies

Article 2 Version 1.0 and FCP-PILOT-01 Investigation V0.4 were published on 16 November 2026 with the DOI links above.

Their publication records the research outputs and makes them citable. It does **not** revise canonical EKR positions, make F1–F4 sufficient by definition, create a released FCP, or change the status of EKR Architectural Guidance.

Any Guidance changes remain subject to the repository’s Issue, pull-request and release-governance process.
