# EKR Architectural Guidance — Working Draft V0.1

**Status: Draft Guidance**

This is the current working draft of **EKR Architectural Guidance V0.1**. It is intentionally incomplete and will be progressively enriched through architectural discussion, structured proposals, challenges, evidence, implementation experience and reviewed pull requests.

It does not yet represent Released Guidance.

Research material may be incorporated here as **candidate Draft Guidance** while remaining explicitly experimental. Inclusion in this working draft does not change the canonical status of the **Enterprise Knowledge Representation — Working Definition V0.1**, create a certification scheme, or establish experimental results that have not been demonstrated.

## 1. Purpose

EKR Architectural Guidance develops practical architectural guidance from the stable distinctions of the **Enterprise Knowledge Representation — Working Definition V0.1**.

It is intended to help an enterprise reason about what representation capability is required for a declared operational purpose, which responsibilities must be made explicit, where authority resides, how multiple representations can coexist, and what conditions are required for governed cross-boundary use.

The Guidance develops reusable decision questions, minimum expectations, candidate patterns, evaluation criteria and examples without presenting one implementation as the EKR architecture.

## 2. Scope discipline

Architectural work should start from an operational interaction or decision need and make explicit:

- the purpose for which representation is required;
- the systems, sites, disciplines, organisations, lifecycle stages or other boundaries involved;
- the participants and viewpoints concerned;
- what representation is sufficient for that purpose;
- what is intentionally outside scope;
- the authority, provenance, validity and lifecycle conditions that matter to the intended use.

The objective is **purposeful sufficiency**, not exhaustive representation of enterprise reality.

## 3. Non-goals

EKR Architectural Guidance V0.1 is not intended to provide:

- a target architecture or mandatory technology stack;
- a universal enterprise model or vocabulary;
- a new ontology or the selection or specification of a concrete realisation of the shared EKR representation foundation;
- a certification scheme or finished conformance programme;
- a replacement for established standards, ontologies, information models or platform guidance;
- a mechanism for semantic mediation, compatibility decisions, coordination, orchestration or execution.

Where existing technologies or standards already fulfil relevant responsibilities, the Guidance should make that contribution visible rather than reinvent it.

The boundary on semantic mediation is important. EKR may represent and govern mapping specifications, correspondence assertions and other outputs produced by externally accountable mediation processes, including their authorship, authority, provenance, scope, evidence, version and status. **Representing or governing those artefacts is not the same as performing, negotiating, validating or authorising the mediation itself.** Conformance of an exposed representation does not by itself establish mapping fidelity, operational compatibility, fitness for use or permission to act.

## 4. Architecture responsibility lens

Use the responsibility sequence:

**Acquire → Transport → Structure → Represent → Persist → Expose → Govern → Secure → Exploit**

The sequence is an architectural decision lens, not a product stack. One technology may fulfil several responsibilities, and one responsibility may be distributed across several technologies or organisational actors.

Evaluation should distinguish the architectural responsibilities an approach actually fulfils from the labels used to describe it. The Guidance should help identify gaps, overlaps and unclear ownership.

### Candidate participation artefacts — under review

Current research distinguishes several architectural artefacts that may help separate abstract participation obligations from technology-specific implementation choices. These terms are **candidate Draft Guidance**, not released specifications:

- **Foundation Conformance Profile (FCP):** a versioned and scoped set of applicable representation obligations, expected evidence and assessment conditions for a declared participation scope.
- **Technology Binding Profile (TBP):** a description of how native constructs, services, extensions, adapters or accountable dependencies fulfil applicable FCP obligations.
- **Technical Exposure Profile (TEP):** agreed technical discovery, access, exposure-model and serialization choices where a common technical form is adopted.
- **Semantic interface:** the logical interpretive boundary through which selected meanings, identities, qualifications, authorities, evidence, relevant times and declared limits are accessible to consumers. It is not necessarily a single endpoint.

These responsibilities need not be implemented as separate physical documents, services or repositories. A technical exposure format does not by itself establish semantic equivalence, source authority, fidelity or fitness for use.

## 5. Authority and representation construction

Examine source-derived, EKR-authoritative and combined construction modes while preserving applicable authority, provenance, scope, version and validity.

Distinguish making source knowledge usable across boundaries from transferring ownership or authority over that knowledge.

A cross-boundary interaction may involve different kinds of representation:

- a **reference** to an element governed elsewhere;
- a **situated assertion**, such as a time-qualified claim that a particular physical asset is installed at a functional position;
- a **mapping or mediation specification** that describes how constructs in independently governed representations are related;
- **correspondence assertions or transformed outputs** produced by an external mediation process.

A situated assertion need not define a reusable translation between conceptual models. Conversely, a mapping specification may describe one-to-one, one-to-many or many-to-many relationships across UODs without transferring the authority of either source representation to the mapping author.

Where mapping specifications or derived correspondence assertions are represented through EKR, retain identifiable authorship, authority, versions, input/output dependencies, evidence, status, applicability and revision conditions. Source endorsement of a mapping and independent assessment of its semantic fidelity remain separate judgments.

## 6. Shared EKR representation foundation

One architectural requirement established by the Working Definition is an explicit shared EKR representation foundation. The Working Definition describes four dimensions:

- shared representation grammar;
- minimal upper-level ontological commitments;
- identity and relationship principles;
- common governance invariants.

Current research explores one **candidate operationalisation** of these dimensions through four commitment families:

- **F1 — Representation grammar / reading roles:** make relevant representation, sign or representation-element, referent, statement and relation roles identifiable, without imposing one native syntax.
- **F2 — Minimal ontological distinctions:** preserve distinctions such as representation versus referent, and type / individual / property / relation where they affect interpretation, while preserving the autonomy of each UOD.
- **F3 — Identity and interpretation:** declare identifier scope, typed relation meaning, interpretation references and the basis for cross-authority identity claims rather than inferring identity from labels.
- **F4 — Governance and accountability:** identify applicable authorities, purpose, publication scope, versions, relevant times, provenance, evidence, correction, revision and withdrawal conditions.

The **F1–F4 labels and their detailed candidate obligations are experimental research inputs**, not a canonical reformulation of the Working Definition and not yet proven to be a sufficient or minimal set.

A candidate FCP may select and scope obligations from these families for a declared participation arrangement, together with expected evidence and assessment rules. FCP-PILOT-01 V0.4 is an experimental investigation of such a profile; it is not a released FCP or certification scheme.

Additional local, domain, cross-domain or community-wide semantic commitments may be expressed through optional **Domain Semantic Profiles (DSPs)** or equivalent arrangements. A DSP is optional at the level of EKR as an approach, but may become mandatory within a particular chosen participation arrangement. The Guidance does not assume that either ontology-light or ontology-rich participation is universally preferable.

Working Draft V0.1 does not select or specify a concrete foundation realisation.

## 7. Multiple viewpoints and UOD boundaries

Preserve legitimate plurality of representations, vocabularies, structures, granularities and authorities. Examine what context is needed to make different representations identifiable and relatable, and where explicit mapping or semantic mediation remains necessary.

A **Universe of Discourse (UOD)** should be treated as a declared interpretive context, not automatically as a department, information system, domain or single ontology. Several UODs may coexist within one domain, and one UOD may span several domains or systems.

Cross-representation assertions should be interpretable under a declared UOD. That UOD may belong to one referenced representation or may be maintained independently for a contextual or mapping relationship. The Guidance does not impose a one-UOD-per-domain rule and does not require a new UOD for every assertion.

## 8. Lifecycle, conformance, validation and fitness

Address version, validity, dependency, change, correction and retirement.

Keep distinct at least the following judgments:

- **conformance:** whether a representation or declared participation scope satisfies applicable structural, governance and publication commitments;
- **semantic fidelity:** whether a binding, projection or transformation preserves the relevant source meaning within its stated scope;
- **fitness for purpose:** whether authority, completeness, timing, uncertainty and other qualifications are adequate for a particular decision or use;
- **authorisation to act:** whether the participant has the rights, safeguards and operational authority required to act;
- **achieved interoperability:** whether the intended interaction actually succeeds under its technical, semantic, organisational and operational conditions.

These judgments require different evidence. Passing an API, schema or structural check does not automatically establish semantic fidelity, current truth, fitness or permission to act.

Where an FCP is used, its conformance result should identify the declared scope, profile version, evaluator, evidence inspected, dependencies and unresolved limitations. Experimental research currently uses candidate verdicts such as Pass, Fail, Indeterminate and justified Not applicable; these are not yet a released conformance scheme.

### Continuity beyond platform replacement

For a declared participation scope, architecture decisions should identify which interpretation and accountability commitments must remain accessible or recoverable when a source, catalog, graph, integration tool or exposure platform is replaced or retired.

Potential preservation obligations include:

- identifiers and resolution rules;
- definitions and applicable versions;
- governed assertions and temporal history;
- provenance, evidence and qualifications;
- mapping-process specifications and generated correspondence assertions;
- dependencies on FCP, TBP, TEP or equivalent artefacts.

Raw-data export is not sufficient when the interpretive context required for responsible use is lost. Continuity remains subject to legitimate retention, withdrawal, sovereignty, access and security conditions. EKR does not itself perform migration; it makes the required preservation commitments and verification responsibilities explicit.

## 9. Security, classification and sovereignty

Address representation-level concerns that may remain even when data-access controls already exist, including:

- disclosure and permitted use;
- classification and compartmentalisation;
- provenance and authority;
- auditability;
- reversibility and source-resident authority;
- cross-organisational or sovereign-control constraints where relevant.

Security and sovereignty should be treated as representation and governance concerns, not only transport or storage concerns.

Where representations, bindings, supplements or common-form exposures depend on restricted source material, applicable access and disclosure restrictions must remain visible and enforceable. A projection or reformatted exposure must not silently broaden authority or permitted use.

## 10. Patterns, evidence and examples

Develop non-normative candidate patterns and cases that test the Guidance against real architecture situations. Each pattern or example should state its context, assumptions, evidence, limitations and status.

### Candidate participation arrangements — experimental

Article 2 and FCP-PILOT-01 propose three non-exclusive participation arrangements:

- **A — Native participation:** applicable representation obligations are met through native source models, services and governance, including source-side extensions where needed.
- **B — Binding and governed augmentation:** native representations remain in place and authoritative for their claims; technology bindings and separately governed supplements provide additional reading or accountability commitments.
- **C — Common-form exposure:** selected knowledge is made consumable in an agreed technical form, materialized or generated on demand, with declared transformations and technical exposure rules.

A/B/C describe **exposure arrangements**, not levels of conformance. They may coexist.

Per-obligation coverage states such as **Native / Extended / Delegated / Unsupported / justified Not applicable** are orthogonal to A/B/C. A common-form exposure can still fail an applicable governance obligation.

These arrangements remain candidate patterns until comparative evidence demonstrates where they are useful, proportionate and reproducible.

### Current evidence status

The current public research inputs are:

- Jean Vieille, *Distributed Knowledge Representations, Shared Foundation and Semantic Interfaces*, Version 1.0, 16 November 2026. DOI: https://doi.org/10.5281/zenodo.24284087
- Jean Vieille, *FCP-PILOT-01: Candidate Foundation Conformance Profile — Investigation V0.4*, 16 November 2026. DOI: https://doi.org/10.5281/zenodo.24284040
- [Architectural Guidance Transfer Note](../proposals/ARCHITECTURAL-GUIDANCE-TRANSFER-2026-11-16.md), tracked by [Issue #21](https://github.com/jvieille/ekr/issues/21).

FCP-PILOT-01 defines candidate rules G1–V4, proposed tests T01–T08 and counter-cases X01–X04. These tests have **not** been presented as completed independent E2 implementation evidence.

The proposed evidence programme should test, among other things:

- independent interpretation of selected constructs;
- preservation of native meaning in bindings or common-form exposures;
- accountability of cross-representation assertions;
- rejection of unsupported conclusions, including unknown-as-absent or identity-from-label inference;
- reproducibility of conformance verdicts;
- continuity of interpretation and accountability after platform replacement;
- comparative effort, maintenance burden and benefits across A/B/C arrangements.

The P-101 case is one bounded example: engineering, maintenance and operations retain different representational responsibilities for a functional position, successive physical assets and operational observations. Missing evidence must not automatically be converted into a negative fact, and valid-time, record-time and publication-time roles may differ.

## Open questions and contributions

The current investigation backlog is maintained in [OPEN-QUESTIONS.md](OPEN-QUESTIONS.md). The questions remain open even where published research proposes candidate answers.

Contribution routes and the governed development and release process are described in [CONTRIBUTING.md](../CONTRIBUTING.md).
