# EKR Architectural Guidance

**Status: Draft Guidance**  
**Current development target: V0.1**

This directory is the stable public workspace for the development of **EKR Architectural Guidance**.

The path is intentionally not versioned. The protected `main` branch carries the current public development state, while each **Released Guidance** version is preserved as an immutable snapshot through a version-specific Git tag and GitHub Release.

The current development target is **EKR Architectural Guidance V0.1**. It is deliberately exposed as Draft Guidance so that its scope, structure, assumptions and unresolved architectural questions can be challenged before a first release.

Nothing in this directory is **Canonical** unless explicitly identified as such. The canonical public definition of EKR remains the archived **Enterprise Knowledge Representation — Working Definition V0.1**:

https://doi.org/10.5281/zenodo.21914714

## What this area contains

- [BRIEF.md](BRIEF.md) — purpose, scope, non-goals, planned structure and development method;
- [OPEN-QUESTIONS.md](OPEN-QUESTIONS.md) — the current open-question backlog for the Guidance;
- [CHANGELOG.md](CHANGELOG.md) — lifecycle record for Draft and Released Guidance versions.

## What the Guidance is intended to do

EKR Architectural Guidance develops practical architectural guidance across the public EKR framing and its stable distinctions.

It is intended to turn those distinctions into a bounded set of:

- architectural decision questions;
- minimum expectations that can be tested and challenged;
- candidate patterns;
- evaluation criteria;
- non-normative examples and evidence.

The **shared EKR representation foundation** is one architectural requirement addressed by the Guidance. It is not the Guidance itself and is not the predetermined destination of the overall EKR roadmap.

The aim is to help assess architectural responsibilities without prescribing one product stack, one universal model or one mandatory implementation architecture.

Evaluation should distinguish the architectural responsibilities an approach actually fulfils from the labels used to describe it.

## What the Guidance is not

EKR Architectural Guidance is not, at this stage:

- a new standard;
- a certification scheme;
- a finished implementation methodology;
- a reference architecture or mandatory technology stack;
- a universal enterprise model or vocabulary;
- a new ontology or a prescribed concrete realisation of the shared EKR representation foundation;
- a replacement for established standards, information models, ontologies or platform guidance.

## Status lifecycle

Guidance material may appear here as **Draft Guidance** while it is being challenged and reviewed. Draft Guidance may change materially and is not yet an accepted EKR recommendation.

A version becomes **Released Guidance** only through an explicit versioned release decision after review. Released Guidance remains evolvable and does not automatically become Canonical.

The branch and version model is:

- `main` — current public development state;
- **Draft Guidance** — status of Guidance material under development on `main`;
- version-specific Git tag + GitHub Release — immutable snapshot of a **Released Guidance** version;
- subsequent Draft Guidance work — continues on `main` through new pull requests.

A permanent `draft` branch and copied per-version Guidance directories are therefore not required.

Release-targeted work may be grouped in a milestone. A milestone expresses intended scope and progress; it does not itself make material Released Guidance.

## Current development target — V0.1

The current V0.1 development cycle is intended to translate stable EKR distinctions into practical architectural questions that can be examined, challenged and refined through evidence and implementation experience.

The current seed defines:

- purpose and scope discipline;
- a provisional architectural structure;
- initial open questions;
- an evidence-driven development method;
- explicit separation between Draft Guidance, Released Guidance and Canonical EKR status.

It is **not** EKR Architectural Guidance V0.1 released.

## Development path

The normal development path is:

**Discussion (optional) → structured Issue → triage → PR where a repository change is needed → Draft Guidance → release review → Released Guidance**

A contribution may start directly as an Issue when prior Discussion is unnecessary, and not every Issue requires a PR.

Substantive PRs link the Issues they implement; Issues retain links to originating Discussions where applicable. Ordinary contributors normally propose changes from branches in their own forks, while maintainers may use repository branches. Both routes target the protected `main` branch through pull requests.

An actual Guidance release is fixed through an explicit versioned release decision, Git tag and GitHub Release. The corresponding milestone may then be closed after remaining items have been dispositioned.

A Discussion, Issue, pull request, milestone assignment or merged Draft Guidance change does not automatically acquire canonical EKR status. Changes that would materially affect a canonical EKR proposition follow the separate process described in the repository [Canonicality Policy](../governance/CANONICAL-POLICY.md).

Development is evidence-driven rather than calendar-driven. Draft material may change substantially as questions, counterexamples, implementation experience and references are reviewed.

## How to challenge the current Guidance

Useful contributions include those that:

- identify an important architectural decision missing from the proposed scope;
- provide a counterexample to a proposed distinction or expectation;
- show where an existing standard, information model, ontology, platform or architecture already fulfils an EKR responsibility well;
- provide implementation experience showing that a proposed requirement would be too heavy, too weak or operationally unrealistic;
- suggest primary references or evidence that should support, qualify or challenge a Guidance proposition.

See [CONTRIBUTING.md](../CONTRIBUTING.md) for contribution routes and status rules, and the repository [ROADMAP](../ROADMAP.md) for the public development sequence.
