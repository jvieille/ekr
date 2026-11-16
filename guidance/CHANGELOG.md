# EKR Architectural Guidance — Changelog

This changelog records the public lifecycle of **EKR Architectural Guidance** across Draft and Released Guidance versions.

The working files remain at the stable `guidance/` path. Version history is preserved through Git history and, for each Released Guidance version, a version-specific Git tag and GitHub Release. Guidance directories are **not copied or renamed for each release**.

Unless an entry is explicitly identified as **Released Guidance**, it describes Draft Guidance development.

## Traceability convention

For substantive Guidance changes:

- Draft changes should be implemented through linked pull requests where repository text changes;
- PRs should link the Issues they implement;
- Issues should retain links to originating Discussions where applicable;
- release-targeted Issues and PRs may be grouped under the corresponding Guidance milestone;
- each **Released Guidance** entry should identify the version-specific Git tag / GitHub Release and summarise the material changes included.

The intended traceability chain is:

**Released Guidance → Git tag / GitHub Release → merged PRs → linked Issues → originating Discussions, where applicable**

## Current development target

**Target: EKR Architectural Guidance V0.1**  
**Status: Draft Guidance**

The current public artefact is **EKR Architectural Guidance — Working Draft V0.1**. It will remain Draft Guidance until an explicit release decision is made and recorded with a version-specific tag and GitHub Release.

## 20 August 2026 — Initial public seed

**Status: Draft Guidance**

Created the initial public seed with:

- a development brief defining purpose, scope, non-goals and planned structure;
- an initial set of open architectural questions;
- an explicit evidence-driven development and release method;
- safeguards distinguishing Draft Guidance, Released Guidance and Canonical EKR status.

This entry does **not** represent a Guidance V0.1 release.

## 21 August 2026 — Stable Guidance workspace layout

**Status: Draft Guidance**

Simplified the repository layout so that EKR Architectural Guidance develops at the stable `guidance/` path rather than in a version-named subdirectory.

Released versions will be preserved through version-specific Git tags and GitHub Releases. Subsequent Draft Guidance work will continue at the same stable path on `main`, avoiding copied per-release directories.

## 22 August 2026 — Working Draft V0.1 established

**Status: Draft Guidance**

Replaced the launch-stage development brief with the living **EKR Architectural Guidance — Working Draft V0.1**.

The initial seed remains part of the project history, but it is no longer treated as a separate operational maturity state. The working draft is the document that will now be progressively enriched through Discussions, Issues, evidence, implementation experience and reviewed pull requests until a release decision is made.

## 16 November 2026 — Article 2 / FCP-PILOT research transfer

**Status: Draft Guidance development**

Integrated candidate architectural material from:

- Jean Vieille, *Distributed Knowledge Representations, Shared Foundation and Semantic Interfaces*, Version 1.0. DOI: https://doi.org/10.5281/zenodo.24284087
- Jean Vieille, *FCP-PILOT-01: Candidate Foundation Conformance Profile — Investigation V0.4*. DOI: https://doi.org/10.5281/zenodo.24284040
- [Architectural Proposal Issue #21](https://github.com/jvieille/ekr/issues/21)
- [Architectural Guidance Transfer Note](../proposals/ARCHITECTURAL-GUIDANCE-TRANSFER-2026-11-16.md)

The working draft now includes:

- FCP / TBP / TEP / semantic-interface distinctions as candidate architectural vocabulary;
- F1–F4 as an experimental operationalisation of the Working Definition’s four shared-foundation dimensions, without claiming sufficiency or canonical status;
- explicit distinction between situated assertions, externally governed mapping specifications and semantic mediation;
- candidate A/B/C participation arrangements and orthogonal coverage states;
- stronger separation among conformance, semantic fidelity, fitness, authorisation and achieved interoperability;
- continuity considerations across source or exposure-platform replacement;
- additional open questions on FCP sufficiency, independent assessment, mapping-process governance, DSP commitments and continuity.

The research status remains explicit: FCP-PILOT-01 V0.4 does not report completed independent E2 implementation tests, and this Draft Guidance update does not create a released FCP, certification scheme or canonical EKR change.
