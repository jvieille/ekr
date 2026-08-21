# EKR Architectural Guidance V0.1 — Initial Public Seed

**Status: Draft Guidance — initial public seed**

This directory is the starting point for the open development of **EKR Architectural Guidance V0.1**.

It is deliberately a **seed**, not a released guidance document. Its purpose is to make the intended scope, structure and unresolved architectural questions visible early enough to be challenged by practitioners, researchers and other contributors.

Nothing in this directory is **Canonical** unless explicitly identified as such. The canonical public definition of EKR remains the archived **Enterprise Knowledge Representation — Working Definition V0.1**:

https://doi.org/10.5281/zenodo.21914714

## What this seed contains

- [BRIEF.md](BRIEF.md) — purpose, scope, non-goals, planned structure and development method;
- [OPEN-QUESTIONS.md](OPEN-QUESTIONS.md) — the initial questions the Guidance is intended to investigate;
- [CHANGELOG.md](CHANGELOG.md) — lifecycle record for the seed and later Guidance development.

## What the Guidance is intended to do

The first EKR Architectural Guidance is intended to turn stable EKR distinctions into a bounded set of:

- architectural decision questions;
- minimum expectations that can be tested and challenged;
- candidate patterns;
- evaluation criteria;
- non-normative examples and evidence.

The aim is to help assess architectural responsibilities without prescribing one product stack, one universal model or one mandatory implementation architecture.

## What this seed is not

This seed is not:

- **Released Guidance**;
- a reference architecture;
- a mandatory technology stack;
- a new ontology or a prescribed concrete realisation of the shared EKR representation foundation;
- a certification or conformance scheme;
- a substitute for established standards, information models, ontologies or platform guidance.

## Development path

The normal development path is:

**Discussion (optional) → structured Issue → triage → PR where a repository change is needed → Draft Guidance → release review → Released Guidance**

A contribution may start directly as an Issue when prior Discussion is unnecessary, and not every Issue requires a PR. Substantive PRs link the Issues they implement; Issues retain links to originating Discussions where applicable. Release-targeted work may be grouped in a milestone, while the actual Guidance release is fixed through an explicit versioned release decision, Git tag and GitHub Release.

A Discussion, Issue, pull request, milestone assignment or merged Draft Guidance change does not automatically acquire canonical EKR status. Changes that would materially affect a canonical EKR proposition follow the separate process described in the repository [Canonicality Policy](../../governance/CANONICAL-POLICY.md).

Development is evidence-driven rather than calendar-driven. Draft material may change substantially as questions, counterexamples, implementation experience and references are reviewed.

## How to challenge the seed

The most useful contributions at this stage are those that:

- identify an important architectural decision missing from the proposed scope;
- provide a counterexample to a proposed distinction or expectation;
- show where an existing standard, information model, ontology, platform or architecture already fulfils an EKR responsibility well;
- provide implementation experience showing that a proposed requirement would be too heavy, too weak or operationally unrealistic;
- suggest primary references or evidence that should support, qualify or challenge a Guidance proposition.

See [CONTRIBUTING.md](../../CONTRIBUTING.md) for the repository contribution rules and status model.
