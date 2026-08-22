# Enterprise Knowledge Representation (EKR)

**Public development workspace for Enterprise Knowledge Representation and EKR Architectural Guidance.**

This repository supports open discussion, structured proposals, challenges, implementation experience, evidence, examples and the governed development of EKR Architectural Guidance.

## Canonical public definition

The canonical public anchor for EKR is:

**Jean Vieille, _Enterprise Knowledge Representation — Working Definition V0.1_ (14 August 2026).**  
DOI: https://doi.org/10.5281/zenodo.21914714

The English V0.1 archived at that DOI is the canonical text. This GitHub repository is **not** an editable replacement for the Working Definition and does not silently redefine it.

## What EKR is

EKR is a technology-independent enterprise-capability framing concerned with how purposeful representations of selected operational knowledge are created, related, governed and evolved across enterprise boundaries.

EKR is not defined by one product, platform, database, ontology, knowledge graph, Unified Namespace architecture or universal enterprise model. Existing technologies, standards, information models and semantic approaches may contribute to an EKR architecture according to the responsibilities they fulfil.

## Purpose of this repository

The repository exists to make EKR development visible, challengeable and evidence-driven while keeping the status of every contribution explicit.

It provides routes to:

- discuss architectural questions and alternatives;
- submit structured proposals and counterexamples;
- contribute implementation experience and cases;
- submit references and evidence;
- develop and review Draft Guidance;
- publish versioned guidance when it reaches an accepted maturity;
- record public decisions that materially affect canonical EKR propositions.

A contribution does **not** become **Released Guidance** or **Canonical** merely by being posted, discussed, accepted for investigation or merged. A maintainer may accept a reviewed change into **Draft Guidance** through the governed pull-request workflow.

## Public status model

| Status | Meaning |
|---|---|
| **Canonical** | Published, versioned and formally designated as a canonical EKR anchor. Changes require separate canonical governance, not an ordinary pull request. |
| **Released Guidance** | Versioned EKR guidance accepted for public use at a stated maturity. It remains evolvable and is not a standard or certification scheme. |
| **Draft Guidance** | Guidance under controlled development. It may change materially and is not yet an accepted EKR recommendation. |
| **Proposal** | A structured suggestion, alternative, pattern or change request submitted for evaluation. |
| **Example** | A non-normative illustration, implementation experience or case used to test guidance. |
| **Discussion** | A conversation, question, challenge or exploration with no acquired EKR status. |

Status belongs to artefacts and decisions, not to people, popularity or contributor count.

## How to participate

- **Discuss** broad questions, alternatives and early challenges in [GitHub Discussions](https://github.com/jvieille/ekr/discussions). Discussion is optional when a contribution is already concrete.
- **Submit** structured proposals, counterexamples, implementation experience or references/evidence through the [structured Issue forms](https://github.com/jvieille/ekr/issues/new/choose).
- **Propose precise text changes** through pull requests, normally linked to the Issue they implement.
- **Follow the contribution lifecycle** in [CONTRIBUTING.md](CONTRIBUTING.md), including the traceability path from Discussions to Issues, PRs and versioned releases.
- Read [GOVERNANCE.md](GOVERNANCE.md) and the public [Canonicality Policy](governance/CANONICAL-POLICY.md) to understand decision rights and status transitions.

## Current development path

The Working Definition V0.1 is published. An initial [EKR Architectural Guidance Working Draft V0.1](guidance/ARCHITECTURAL-GUIDANCE.md) is live in the repository with **Draft Guidance** status and is open to challenge and improvement. The near-term sequence is described in [ROADMAP.md](ROADMAP.md).

The protected `main` branch carries the current public development state. Draft/Released/Canonical are artefact statuses rather than branch names: versioned Guidance releases are fixed by Git tags and GitHub Releases, while new draft work continues through pull requests to `main`.

## Boundaries

This repository is intentionally neutral and limited in scope. It does not constitute:

- a product or commercial offer;
- a reference implementation;
- a mandatory technology stack;
- a universal ontology or enterprise model;
- a certification or conformance scheme;
- an automatic source of canonical EKR changes.

Material that has not been authorised for public release under applicable publication, protection, confidentiality, security or intellectual-property controls is outside the current scope of this repository.

## Licence

Unless otherwise stated, original documentation and text published in this repository are made available under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** licence. See [LICENSE](LICENSE) for scope and exclusions.
