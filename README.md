# Enterprise Knowledge Representation (EKR)

**Public development workspace for Enterprise Knowledge Representation and EKR Architectural Guidance.**

This repository supports open discussion, structured proposals, challenges, implementation experience, evidence, examples, reader aids and the governed development of EKR Architectural Guidance.

## Canonical public definition

The canonical public anchor for EKR is:

**Jean Vieille, _Enterprise Knowledge Representation — Working Definition V0.1_ (14 August 2026).**  
DOI: https://doi.org/10.5281/zenodo.21914714

The English V0.1 archived at that DOI is the canonical text. This GitHub repository is **not** an editable replacement for the Working Definition and does not silently redefine it.

## What EKR is

EKR is a technology-independent enterprise-capability framing concerned with how purposeful representations of selected operational knowledge are created, related, governed and evolved across enterprise boundaries.

EKR is not defined by one product, platform, database, ontology, knowledge graph, Unified Namespace architecture or universal enterprise model. Existing technologies, standards, information models and semantic approaches may contribute to an EKR architecture according to the responsibilities they fulfil.

## Published research

Published research develops and challenges the EKR framing without automatically changing canonical EKR positions or conferring Guidance status.

- **Article 1 — _Beyond Data: Why Knowledge Representation Is an Enterprise Architecture Concern_** (2026). DOI: https://doi.org/10.5281/zenodo.22918368
- **Article 2 — _Distributed Knowledge Representations, Shared Foundation and Semantic Interfaces_**, Version 1.0 (16 November 2026). DOI: https://doi.org/10.5281/zenodo.24284087
- **FCP-PILOT-01 — _Candidate Foundation Conformance Profile — Investigation V0.4_** (16 November 2026). Experimental, non-normative research note. DOI: https://doi.org/10.5281/zenodo.24284040

Article 2 and FCP-PILOT-01 introduce candidate architectural material for public review. Their publication does not itself revise the Working Definition, create a released FCP, or make their proposals Draft or Released Guidance.

## Purpose of this repository

The repository exists to make EKR development visible, challengeable and evidence-driven while keeping the status and role of every contribution explicit.

It provides routes to:

- ask questions, flag errors, suggest references or propose small clarifications without learning Git;
- submit structured scientific and practitioner contributions for maintainer review;
- contribute worked examples and non-canonical reader aids;
- optionally propose direct file changes through pull requests;
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

Status belongs to artefacts and decisions, not to people, popularity or contributor count. Reader aids are a document type, not an additional EKR status.

## How to participate

You do **not** need to know Git, create a branch or open a pull request to contribute to EKR.

### 1. Quick contribution — a few minutes

Use [GitHub Discussions](https://github.com/jvieille/ekr/discussions) to:

- ask a question;
- suggest a reference;
- flag an error or ambiguity;
- propose a small clarification;
- share an early idea.

Write the contribution in ordinary language and add a link or source when useful. The maintainer will route it if more structure is needed.

### 2. Structured contribution — no branch or PR required

For a concrete analysis, counterexample, architectural proposal, evidence item, implementation experience or reader aid, use the single [Structured EKR contribution form](https://github.com/jvieille/ekr/issues/new/choose).

The maintainer is responsible for classification, labels, release targeting, canonical-impact screening and—when repository files need to change—preparing or coordinating the linked pull request.

### 3. Direct edit — optional technical path

If you are comfortable with GitHub and want to edit repository files directly, you may open a pull request. This is an **optional contributor path**, not a prerequisite for scientific or industrial participation.

For the detailed contribution rules, see [CONTRIBUTING.md](CONTRIBUTING.md). Repository decision rights remain defined in [GOVERNANCE.md](GOVERNANCE.md) and the public [Canonicality Policy](governance/CANONICAL-POLICY.md).

## Current development path

The Working Definition V0.1 is published and remains canonical. An initial [EKR Architectural Guidance Working Draft V0.1](guidance/ARCHITECTURAL-GUIDANCE.md) is live in the repository with **Draft Guidance** status and is open to challenge and improvement.

Article 2 and FCP-PILOT-01 now provide new candidate research material for that development cycle. Their transfer into Guidance is tracked through the proposal process rather than assumed from publication.

The near-term sequence is described in [ROADMAP.md](ROADMAP.md).

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
