# EKR Architectural Guidance V0.1 — Development Brief

**Status: Draft Guidance — seed brief**

## 1. Purpose

EKR Architectural Guidance V0.1 is intended to translate the stable distinctions of the **Enterprise Knowledge Representation — Working Definition V0.1** into practical architectural questions that can be examined, challenged and refined through evidence and implementation experience.

The Guidance should help an enterprise reason about what representation capability is required for a declared operational purpose, which responsibilities must be made explicit, where authority resides, how multiple representations can coexist, and what conditions are required for governed cross-boundary use.

It should develop reusable decision questions, minimum expectations, candidate patterns, evaluation criteria and examples without presenting one implementation as the EKR architecture.

## 2. Scope discipline

The Guidance starts from an operational interaction or decision need. It should make explicit:

- the purpose for which representation is required;
- the systems, sites, disciplines, organisations, lifecycle stages or other boundaries involved;
- the participants and viewpoints concerned;
- what representation is sufficient for that purpose;
- what is intentionally outside scope;
- the authority, provenance, validity and lifecycle conditions that matter to the intended use.

The objective is **purposeful sufficiency**, not exhaustive representation of enterprise reality.

## 3. Non-goals

Guidance V0.1 is not intended to be:

- a target architecture or mandatory technology stack;
- a universal enterprise model or vocabulary;
- a new ontology or the selection or specification of a concrete realisation of the shared EKR representation foundation;
- a certification scheme or finished conformance programme;
- a replacement for established standards, ontologies, information models or platform guidance;
- a mechanism for semantic mediation, compatibility decisions, coordination, orchestration or execution.

Where existing technologies or standards already fulfil relevant responsibilities, the Guidance should make that contribution visible rather than reinvent it.

## 4. Planned structure

The initial structure is deliberately provisional. It organises the questions to be developed; it does not imply that the answers are already fixed.

### 4.1 Purpose and scope discipline

Start from an operational interaction or decision need. Define purpose, purposeful sufficiency, explicit limits and the criteria by which a representation should later be judged useful.

### 4.2 Architecture responsibility lens

Use the responsibility sequence:

**Acquire → Transport → Structure → Represent → Persist → Expose → Govern → Secure → Exploit**

The sequence is an architectural decision lens, not a product stack. One technology may fulfil several responsibilities, and one responsibility may be distributed across several technologies or organisational actors. The Guidance should help identify gaps, overlaps and unclear ownership.

### 4.3 Authority and representation construction

Examine source-derived, EKR-authoritative and combined construction modes while preserving applicable authority, provenance, scope, version and validity.

The Guidance should help distinguish making source knowledge usable across boundaries from transferring ownership or authority over that knowledge.

### 4.4 Shared EKR representation foundation

One architectural requirement established by the Working Definition is an explicit shared EKR representation foundation. The Guidance should examine its four dimensions:

- shared representation grammar;
- minimal upper-level ontological commitments;
- identity and relationship principles;
- common governance invariants.

The Guidance should clarify the requirements and decision criteria applicable to this shared foundation, including the minimum commitments required for a declared interoperability scope, without turning it into one universal domain vocabulary or detailed enterprise decomposition. Guidance V0.1 does not select or specify a concrete foundation realisation.

### 4.5 Multiple viewpoints and UOD boundaries

Preserve legitimate plurality of representations, vocabularies, structures, granularities and authorities. Examine what context is needed to make different representations identifiable and relatable, and where explicit mapping or semantic mediation remains necessary.

### 4.6 Lifecycle, conformance, validation and fitness

Address version, validity, dependency, change, correction and retirement. Keep distinct:

- whether a representation satisfies the applicable structural, governance and publication constraints; and
- whether that admissible representation is actually fit for its declared operational purpose and assurance level.

### 4.7 Security, classification and sovereignty

Address representation-level concerns that may remain even when data-access controls already exist, including:

- disclosure and permitted use;
- classification and compartmentalisation;
- provenance and authority;
- auditability;
- reversibility and source-resident authority;
- cross-organisational or sovereign-control constraints where relevant.

The Guidance should treat security and sovereignty as representation and governance concerns, not only transport or storage concerns.

### 4.8 Patterns, evidence and examples

Develop non-normative candidate patterns and cases that test the Guidance against real architecture situations. Each pattern or example should state its context, assumptions, evidence, limitations and status.

Examples illustrate or test Guidance; they do not become normative merely by being published in the repository.

## 5. Initial development questions

The initial question set is maintained in [OPEN-QUESTIONS.md](OPEN-QUESTIONS.md). These questions define the first investigation backlog; they are not assumptions that contributors are expected to confirm.

Contributors are explicitly encouraged to challenge the questions themselves, including their wording, scope and missing concerns.

## 6. Development and release method

Guidance V0.1 will be developed through a visible, governed loop:

1. architectural questions, challenges, alternatives and implementation experience are discussed;
2. sufficiently structured proposals, counterexamples, cases or evidence are recorded for review;
3. contributions are triaged for relevance, evidence and status impact;
4. accepted work may change Draft Guidance;
5. Draft Guidance is reviewed against the canonical Working Definition, relevant evidence and the repository governance rules;
6. a version becomes **Released Guidance** only through an explicit versioned release decision.

A Guidance release does not by itself change the canonical EKR definition. Any material canonical-impact proposal follows the separate canonicality process.

## 7. Evidence principle

The Guidance should prefer primary standards, specifications, research and sufficiently described implementation experience where they are available. Evidence should be used to support, qualify or challenge propositions, not merely to accumulate references.

Existing approaches should be assessed according to the responsibilities they actually fulfil and the scope in which they fulfil them, rather than being treated as competing product categories.

## 8. Seed acceptance test

This seed is adequate for public discussion when a reader who has only read the Working Definition can understand:

- what Guidance V0.1 is intended to decide;
- what it is explicitly not deciding;
- how its initial sections are organised;
- what questions remain open;
- how those questions can be challenged;
- that the material remains Draft Guidance rather than an accepted EKR recommendation.
