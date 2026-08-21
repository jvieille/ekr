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

V0.1 is the first planned public Guidance release. Until an explicit release decision is made and recorded with a version-specific tag and GitHub Release, the material in `guidance/` remains Draft Guidance.

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
