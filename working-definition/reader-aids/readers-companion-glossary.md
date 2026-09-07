# Enterprise Knowledge Representation (EKR) — Reader’s Companion & Glossary

**Author:** Bill Bosler  
**Companion to:** Jean Vieille, _Enterprise Knowledge Representation — Working Definition V0.1_ (14 August 2026)  
**Nature:** Contributor-authored explanatory aid — non-canonical  
**Canonical source:** [EKR Working Definition V0.1](../README.md) · DOI: 10.5281/zenodo.21914714

## Purpose and source boundary

This companion is intended to make the four-page Working Definition easier to read while preserving its terminology, distinctions and publication boundary.

It is an explanatory aid, not part of the canonical EKR definition. Definitions and summaries below are grounded in the public Working Definition V0.1. Where a short plain-language explanation or interpretation is added, it is identified as a **Reader aid**.

No attempt is made here to redefine EKR, reconcile it with outside frameworks, or establish additional canonical terminology. Where precision matters, the canonical English Working Definition V0.1 controls.

## How to use this companion

Start with the [Acronym Quick Reference](#1-acronym-quick-reference), then use the [Concept Glossary](#3-concept-glossary) while reading the Working Definition. Each glossary entry identifies the page or pages of the Working Definition where the concept is used.

## 1. Acronym Quick Reference

| Acronym / term | Expansion | Why it matters in the Working Definition |
|---|---|---|
| [AAS](#asset-administration-shell-aas) | Asset Administration Shell | Industrial digital-twin / asset information-model approach referenced as an example of formal structures and reusable domain models. |
| [AI](#artificial-intelligence-ai) | Artificial Intelligence | AI assistants and identified AI agents may consume or contribute governed representations. |
| CC BY 4.0 | Creative Commons Attribution 4.0 International | Licence applied to the Working Definition. |
| CESMII | Clean Energy Smart Manufacturing Innovation Institute | Contemporary industrial interoperability and smart-manufacturing reference point. |
| DataOps | Data Operations | Architecture/practices for making operational data usable; part of the existing landscape, not EKR itself. |
| DOI | Digital Object Identifier | Persistent identifier for the published Working Definition. |
| [EKG](#enterprise-knowledge-graph-ekg) | Enterprise Knowledge Graph | Existing enterprise formal-semantic approach referenced in the landscape. |
| EKGF | Enterprise Knowledge Graph Forum | Forum/method associated with OMG Enterprise Knowledge Graph work. |
| EKR | Enterprise Knowledge Representation | Proposed technology-independent enterprise-capability framing. |
| IDTA | Industrial Digital Twin Association | Publisher of the cited Asset Administration Shell specification. |
| IEC | International Electrotechnical Commission | Standards organization appearing in ISO/IEC references. |
| IEEE | Institute of Electrical and Electronics Engineers | Standards organization appearing in ISO/IEC/IEEE 42010. |
| ISO | International Organization for Standardization | Standards organization cited in the references. |
| OMG | Object Management Group | Standards organization whose Enterprise Knowledge Graph work is cited. |
| [OPC UA](#opc-unified-architecture-opc-ua) | OPC Unified Architecture | Industrial interoperability and information-model technology used as an example of formal source structures. |
| OWL | Web Ontology Language | W3C ontology language cited as a precedent for formal ontology concerns. |
| PROV-O | PROV Ontology | W3C provenance ontology cited as a precedent for provenance concerns. |
| TLO | Top-Level Ontology | Appears through ISO/IEC 21838-1. |
| [UNS](#unified-namespace-uns) | Unified Namespace | Industrial data architecture referenced as part of the landscape; EKR is not defined as a UNS. |
| [UOD](#universe-of-discourse-uod) | Universe of Discourse | A governed semantic domain that may retain its own ontology, vocabulary, conventions, authorities and pragmatic assumptions. |
| W3C | World Wide Web Consortium | Standards body responsible for the cited OWL and PROV-O recommendations. |

## 2. Core EKR vocabulary — how the terms fit together

The Working Definition becomes easier to follow if the following conceptual map and distinctions are kept in mind:

- **Operational reality** — what actually exists or happens in enterprise operation.
- **Observation** — evidence about that reality, such as a value, event, state or record.
- **Operational knowledge** — the identities, distinctions, relationships, rules, operational capabilities, responsibilities, constraints, provenance and experience needed to interpret and act.
- **Representation** — an explicit construction that makes selected knowledge usable by others.
- **Interaction** — an exchange or coordinated action through which participants affect, transform, request, provide, constrain or interpret something in operational reality.
- **An EKR** — one particular, partial, purpose-specific representation.
- **The EKR capability** — the broader enterprise capability that creates, relates, governs, validates, evaluates, exposes and evolves many EKRs.
- **The EKR Service** — the logical architectural expression of that capability; not necessarily one product, database or repository.
- **Shared EKR representation foundation** — the common formal and governance basis used across participating representations.
- **Identity and relationship principles** — the shared foundation element concerned with coherent identity and relationships across participating representations.
- **UOD** — a governed semantic domain that can retain its own domain meaning while conforming to the shared foundation.
- **Semantic mediation and downstream mechanisms** — mechanisms outside intrinsic EKR that address remaining differences in meaning and support inference, composition, routing or execution.

**One-sentence mental model:** EKR does not try to put all enterprise knowledge into one model; it makes the selected knowledge needed for a purpose explicit, governed, traceable and usable across boundaries.

## 3. Concept Glossary

### Asset Administration Shell (AAS)

An industrial asset information-model approach cited as an example of formal structures and reusable domain models that can coexist with source-specific authority.

**Where in the Working Definition:** pp. 2, 4  
**Reader aid:** AAS can contribute to an EKR architecture; AAS is not synonymous with EKR.

### Artificial Intelligence (AI)

The Working Definition treats AI assistants and identified AI agents as possible users and contributors of governed representations. AI contribution does not remove validation, accountability or governance requirements.

**Where in the Working Definition:** pp. 2–3  
**Reader aid:** AI is a participant in the architecture, not the authority by default.

### Creative Commons Attribution 4.0 International (CC BY 4.0)

The licence under which the Working Definition is published. It permits reuse and adaptation with attribution, subject to the licence terms.

**Where in the Working Definition:** pp. 1, 4  
**Reader aid:** This is publication metadata rather than an EKR architectural concept.

### CESMII

A contemporary smart-manufacturing reference point used to show that reusable industrial information models, contextualised manufacturing information, common interfaces and portable applications already address parts of the landscape.

**Where in the Working Definition:** pp. 1, 3–4  
**Reader aid:** The Working Definition positions EKR alongside and across existing approaches rather than claiming that they are deficient.

### DataOps

One of the existing enterprise/industrial approaches used to make operational information usable. The Working Definition does not define DataOps in detail.

**Where in the Working Definition:** pp. 1, 3  
**Reader aid:** DataOps may contribute transport, contextualisation, persistence or exposure; EKR addresses the representation and governance framing across such mechanisms.

### Digital Object Identifier (DOI)

The persistent publication identifier assigned to this version of the Working Definition.

**Where in the Working Definition:** p. 1  
**Reader aid:** Version DOI: `10.5281/zenodo.21914714`.

### Enterprise Knowledge Graph (EKG)

A knowledge-graph approach for enterprise identity, meaning, provenance and governance referenced as an important existing formal-semantic path.

**Where in the Working Definition:** pp. 1, 4  
**Reader aid:** EKG is an important existing approach in the EKR landscape. EKR itself is a technology-independent enterprise-capability framing and is not defined by a knowledge-graph implementation.

### Enterprise Knowledge Graph Forum (EKGF)

The forum and principles/method referenced in connection with OMG Enterprise Knowledge Graph work.

**Where in the Working Definition:** pp. 1, 4  
**Reader aid:** The Working Definition cites EKGF as established related work.

### Enterprise Knowledge Representation (EKR)

The enterprise capability to create, relate, govern and evolve purposeful representations of selected operational knowledge so that people, applications, equipment, organisations and agents have a structured and governed foundation from which semantic and operational interoperability can be progressively established across boundaries.

**Where in the Working Definition:** p. 2  
**Reader aid:** The distinction among **an EKR**, **the EKR capability**, and **the EKR Service** is critical; the three expressions are not interchangeable.

### An Enterprise Knowledge Representation — “an EKR”

A particular explicit, partial and purpose-specific representation that is maintained as operational reality and enterprise needs evolve.

**Where in the Working Definition:** p. 2  
**Reader aid:** Think of this as one governed representation built for a defined purpose, not the whole enterprise model.

### The EKR capability

The broader enterprise capability that creates, relates, governs, validates, evaluates, exposes and evolves multiple purposeful representations.

**Where in the Working Definition:** p. 2  
**Reader aid:** This is the enterprise-level ability, not a single representation or software product.

### The EKR Service

The logical architectural expression of the EKR capability. It may be realised by several components, teams and authoritative sources and does not imply one repository, product, database or deployment.

**Where in the Working Definition:** p. 2  
**Reader aid:** “Service” is logical architecture, not necessarily a software service or central server.

### Shared EKR representation foundation

The common basis required by EKR, combining:

1. shared representation grammar;
2. minimal upper-level ontological commitments;
3. identity and relationship principles; and
4. common governance invariants.

**Where in the Working Definition:** pp. 2–3  
**Reader aid:** It is not a universal enterprise vocabulary or ontology.

### Shared representation grammar

The common formal constructions through which participating EKR representations can be structured. The Working Definition explicitly states that shared grammar does not, by itself, translate meaning across UODs.

**Where in the Working Definition:** p. 2  
**Reader aid:** Common formal constructs and structure are not the same as common meaning.

### Minimal upper-level ontological commitments

The small set of high-level conceptual commitments included in the shared foundation so that representations have a compatible formal basis.

**Where in the Working Definition:** p. 2  
**Reader aid:** This is deliberately not the same as imposing one detailed domain ontology on everyone.

### Common governance invariants

The governance rules or conditions that remain common across representations participating in the shared foundation.

**Where in the Working Definition:** p. 2  
**Reader aid:** The Working Definition names this as one of the foundation’s four elements but does not enumerate the invariants.

### Identity and relationship principles

The shared principles used to keep represented identities and relationships coherent enough to be related across participating representations and domains.

**Where in the Working Definition:** p. 2  
**Reader aid:** Identity and relationship principles are one of the four elements of the shared EKR representation foundation. This explanation does not prescribe a particular identifier scheme, relationship model, ontology or implementation mechanism.

### Universe of Discourse (UOD)

A governed semantic domain that may retain its own domain ontologies, vocabulary, modelling conventions, authorities and pragmatic assumptions while conforming to the shared EKR representation foundation.

**Where in the Working Definition:** pp. 2–3  
**Reader aid:** A UOD defines a governed scope within which terms and representations receive meaning.

### Pragmatic assumptions

Assumptions within a semantic domain about how concepts, relationships, granularities, conditions or patterns are interpreted or used.

**Where in the Working Definition:** p. 2  
**Reader aid:** The Working Definition uses the term without defining it separately; this explanation is intended only to make the UOD description easier to read.

### EKR Foundation Conformance Profile

A named and versioned specification of the complete shared EKR representation foundation for a declared interoperability scope.

**Where in the Working Definition:** pp. 2–3  
**Reader aid:** Participants using the same profile share the foundation required for native foundation-level interoperability, but not automatically the same domain meaning.

### EKR Domain Semantic Profile

An optional semantic specialisation built on a specified Foundation Conformance Profile, adding agreed domain/reference ontologies, controlled vocabularies and semantic constraints.

**Where in the Working Definition:** p. 3  
**Reader aid:** Foundation Profile = common foundation; Domain Semantic Profile = optional stronger shared domain semantics.

### Representation conformance and validation

Assessment of whether a representation, mapping, projection or publication satisfies the applicable Foundation Conformance Profile, optional Domain Semantic Profile, UOD rules and publication constraints.

**Where in the Working Definition:** p. 3  
**Reader aid:** Conformance asks: “Is it admissible under the applicable rules?”

### Representation fitness and quality evaluation

Assessment of whether an admissible governed representation is actually adequate for its declared purpose and required assurance, considering factors such as usefulness, fidelity, clarity, authority, evidence, timeliness, maintainability, reuse and cost.

**Where in the Working Definition:** p. 3  
**Reader aid:** Fitness asks: “Is it good enough for this actual purpose?” Conformance and fitness are deliberately different.

### Authority

The Working Definition treats authority as distributed: different sources or governed domains may remain authoritative for different knowledge. Exposing or projecting knowledge through EKR does not transfer that authority.

**Where in the Working Definition:** pp. 1–3  
**Reader aid:** Authority concerns who or what has the governed right or recognised competence to assert, maintain or approve represented knowledge within a scope.

### Provenance

Information that preserves where a representation, assertion, observation or contribution came from and supports traceability of responsibility and evidence.

**Where in the Working Definition:** pp. 1–3  
**Reader aid:** Provenance is a recurring governance requirement throughout the Working Definition.

### Purposeful representation

A representation whose selected scope is justified by a declared operational or business purpose.

**Where in the Working Definition:** pp. 1–3  
**Reader aid:** EKR intentionally rejects modelling everything merely because it can be modelled.

### Partiality

The intentional decision to represent only what the declared purpose requires, rather than reproducing everything known or observable.

**Where in the Working Definition:** p. 2  
**Reader aid:** Partial does not mean incomplete in a defective sense; it means purpose-bounded.

### Plurality / plural representations

The recognition that several legitimate representations of the same operational reality may coexist for different teams, purposes, viewpoints, vocabularies, structures and granularities.

**Where in the Working Definition:** p. 2  
**Reader aid:** This leads to the stated goal of **“coherence without semantic uniformity.”**

### Coherence without semantic uniformity

The objective that different legitimate representations remain relatable and governable without forcing every domain to use the same vocabulary, model or meaning.

**Where in the Working Definition:** p. 2  
**Reader aid:** Coordinated difference, not one universal enterprise language.

### Operational knowledge

Identities, distinctions, relationships, rules, operational capabilities, responsibilities, constraints, provenance and experience that allow participants to understand and act in enterprise operation.

**Where in the Working Definition:** p. 1  
**Reader aid:** This is broader than raw data or a data schema.

### Operational reality

The enterprise reality of what exists, happens, constrains or is affected in enterprise operation. The Working Definition distinguishes operational reality from observations and representations, which provide evidence about or explicit constructions concerning that reality.

**Where in the Working Definition:** pp. 1–2  
**Reader aid:** A pump is part of operational reality; its database record, graph, model and digital twin are representations.

### Observation

Evidence about operational reality, such as a reported value, event, state or record. The Working Definition uses the example of the value `85`, which needs identity, unit, time, source and operational context to be useful across boundaries.

**Where in the Working Definition:** pp. 1, 3  
**Reader aid:** Observations provide evidence about operational reality; representations make selected knowledge explicit and usable, including the knowledge needed to interpret observations.

### Representation

An explicit construction through which selected knowledge is made usable for interaction. It is neither operational reality nor knowledge itself.

**Where in the Working Definition:** p. 1  
**Reader aid:** Examples include models, messages, graphs, digital twins, documents and source-system structures.

### Interaction

An exchange or coordinated action among enterprise participants through which they affect, transform, request, provide, constrain, interpret or otherwise act upon operational reality.

**Where in the Working Definition:** pp. 1–3  
**Reader aid:** Interactions are the operational reason representations matter in EKR: selected knowledge is made usable so that participants can understand, coordinate and act across boundaries.

### Interoperability

The ability that EKR prepares for progressively across boundaries. The Working Definition distinguishes semantic and operational interoperability and states that EKR provides a governed foundation but does not guarantee either.

**Where in the Working Definition:** pp. 2–3  
**Reader aid:** EKR creates readiness; interoperability still depends on participants, meanings, mappings, authority and downstream mechanisms.

### Semantic interoperability

The ability of participants to interpret information consistently enough for the intended cross-boundary use.

**Where in the Working Definition:** pp. 2–3  
**Reader aid:** The Working Definition does not provide a standalone formal definition; it positions EKR as a foundation from which semantic interoperability may be progressively established.

### Operational interoperability

The ability of participants to coordinate compatible operational interactions under the relevant conditions and authority.

**Where in the Working Definition:** pp. 2–3  
**Reader aid:** This is a plain-language interpretation of the Working Definition’s distinction between semantic interpretation and the ability to coordinate compatible operational action.

### Semantic mediation

Purpose- and context-dependent mechanisms that establish correspondences between representations when UODs do not share sufficient domain meaning. EKR preserves the governed representations needed for mediation, but semantic mediation itself remains a downstream capability rather than an intrinsic EKR function.

**Where in the Working Definition:** p. 3  
**Reader aid:** Mediation bridges remaining differences in meaning and use when common structure alone is insufficient.

### Mapping / governed mapping

An explicit governed correspondence required, for example, when participants use different Foundation Conformance Profiles.

**Where in the Working Definition:** p. 3  
**Reader aid:** The Working Definition mentions mapping but does not specify its detailed mechanism.

### Projection / exposing source knowledge

Making selected source knowledge available through EKR while preserving its original authority, provenance, scope and version.

**Where in the Working Definition:** p. 2  
**Reader aid:** Copying or exposing knowledge does not make EKR the original authority for it.

### Composable participation

Support for discovery, onboarding, substitution and compatibility assessment through governed descriptions of what participants provide, require, consume, produce, transform or affect, together with relevant conditions and authority.

**Where in the Working Definition:** p. 3  
**Reader aid:** EKR supports readiness for composition; composition and execution remain downstream.

### Downstream capabilities

Capabilities that may use governed EKR representations but are not intrinsic EKR functions: semantic mediation, inference and other reasoning, negotiation, composition, routing, orchestration and execution.

**Where in the Working Definition:** p. 3  
**Reader aid:** This boundary is essential to the Working Definition.

### Representation readiness

The Working Definition’s summary of what EKR creates: a structured, governed and evolvable basis on which interoperability, composability and later reasoning or coordination mechanisms can operate.

**Where in the Working Definition:** p. 3  
**Reader aid:** This is one of the simplest phrases for remembering EKR’s architectural role.

### OPC Unified Architecture (OPC UA)

An industrial interoperability and information-model technology cited as an example of formal structures and source models that may participate in an EKR architecture.

**Where in the Working Definition:** pp. 2, 4  
**Reader aid:** An OPC UA model may remain authoritative within its declared scope; EKR does not replace it.

### Unified Namespace (UNS)

An industrial architecture cited among existing approaches for making operational information usable. EKR is explicitly not defined by one UNS architecture.

**Where in the Working Definition:** pp. 1, 3  
**Reader aid:** UNS can move, organise and expose data; EKR focuses on the governed representation capability across boundaries.

### Web Ontology Language (OWL)

A W3C formal ontology language cited as precedent for formal ontology concerns.

**Where in the Working Definition:** pp. 2, 4  
**Reader aid:** It is a reference technology, not the definition of EKR.

### PROV-O

The W3C PROV Ontology, cited as a precedent for formal provenance representation.

**Where in the Working Definition:** pp. 2, 4  
**Reader aid:** It supports the Working Definition’s emphasis on provenance.

### Top-Level Ontology (TLO)

A high-level ontology category referenced through ISO/IEC 21838-1.

**Where in the Working Definition:** p. 4  
**Reader aid:** It is related to the concept of minimal upper-level ontological commitments, but the Working Definition does not equate the two.

### Object Management Group (OMG)

Standards organization whose Enterprise Knowledge Graph work is cited as a contemporary reference point.

**Where in the Working Definition:** pp. 1, 3–4

### Industrial Digital Twin Association (IDTA)

Organization responsible for the cited Asset Administration Shell specification.

**Where in the Working Definition:** p. 4

### International Organization for Standardization (ISO)

Standards organization cited in architecture-description and top-level-ontology references.

**Where in the Working Definition:** p. 4

### International Electrotechnical Commission (IEC)

Standards organization appearing in the cited ISO/IEC standards.

**Where in the Working Definition:** p. 4

### Institute of Electrical and Electronics Engineers (IEEE)

Standards organization appearing in ISO/IEC/IEEE 42010:2022.

**Where in the Working Definition:** p. 4

### World Wide Web Consortium (W3C)

Standards organization responsible for the cited OWL and PROV-O recommendations.

**Where in the Working Definition:** p. 4

## 4. Distinctions that prevent misreading

| Term A | Meaning | Do not confuse with | Meaning |
|---|---|---|---|
| An EKR | one particular purpose-specific representation | The EKR capability | the enterprise ability that manages many representations |
| EKR capability | the enterprise capability | EKR Service | the logical architectural expression of that capability |
| Shared foundation | common grammar + upper-level commitments + identity/relationship principles + governance invariants | Domain Semantic Profile | optional additional shared domain semantics |
| Conformance | does it satisfy the applicable formal/governance rules? | Fitness | is it adequate for the actual purpose and risk? |
| Representation | explicit construction concerning reality | Operational reality | the thing, situation or process that actually exists or occurs |
| Observation | evidence about reality | Representation | the structure that helps make selected knowledge and evidence interpretable and usable |
| Coherence | representations can coexist, be related and governed | Uniformity | everyone is forced into the same vocabulary/model — which EKR does not require |
| EKR readiness | makes selected knowledge explicit and governed for use | Downstream action | mediation, inference, composition, routing, orchestration and execution remain separate capabilities |

## 5. Four-page reading guide

### Page 1 — Why EKR is being proposed

Existing technologies already address pieces of the problem. The Working Definition focuses on the cross-boundary representation problem: data access alone does not preserve enough identity, meaning, authority, purpose and context for distant participants.

### Page 2 — What EKR is

This is the heart of the Working Definition. Keep the three meanings separate: **an EKR**, **the EKR capability**, and **the EKR Service**. Then focus on purposeful partiality, plurality, distributed authority, and the four-part shared foundation.

### Page 3 — How it is governed and what it enables

Foundation Conformance Profiles make the abstract shared foundation concrete. Domain Semantic Profiles optionally add stronger shared domain meaning. Conformance is not fitness. EKR prepares semantic and operational interoperability and composable participation, while mediation, inference, composition and execution remain downstream.

### Page 4 — Reference base

The references show established bodies of work on which the Working Definition builds: knowledge representation, architecture viewpoints, OWL, provenance, top-level ontologies, OPC UA, AAS, OMG/EKGF and CESMII.

## 6. Twelve terms to learn first

1. EKR
2. an EKR
3. EKR capability
4. EKR Service
5. representation
6. operational knowledge
7. interaction
8. authority
9. UOD
10. shared EKR representation foundation
11. conformance vs. fitness
12. representation readiness

---

Prepared by **Bill Bosler** as a reader’s companion to _Enterprise Knowledge Representation — Working Definition V0.1_. This document is explanatory and non-canonical. Where precision matters, the canonical English V0.1 controls.

**Submission note:** This reviewed version follows the repository reader-aid boundary specified by Jean Vieille: it explains and organizes concepts already present in the Working Definition and does not add PAIPW-specific requirements, architectural recommendations, implementation patterns or design guidance.
