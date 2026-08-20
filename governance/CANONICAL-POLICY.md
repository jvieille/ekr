# Public EKR Canonicality Policy

## 1. Purpose

This policy explains how public repository contributions may influence EKR without turning GitHub activity into an alternative canonical authority.

It is a **public governance policy**. Non-public review material used to assess claims, boundaries and publication decisions is not reproduced here.

## 2. Current canonical public anchor

The current canonical public EKR anchor is:

**Jean Vieille, _Enterprise Knowledge Representation — Working Definition V0.1_, 14 August 2026.**  
Version DOI: https://doi.org/10.5281/zenodo.21914714

The English V0.1 archived at that DOI is canonical. This repository may describe, discuss and develop material derived from it, but it is not an editable replacement for that publication.

## 3. Public artefact statuses

The repository distinguishes:

- **Canonical** — published, versioned and formally designated canonical EKR anchor;
- **Released Guidance** — versioned guidance accepted for public use at a stated maturity;
- **Draft Guidance** — controlled working guidance that may change materially;
- **Proposal** — structured suggestion or change request submitted for evaluation;
- **Example** — non-normative case or illustration;
- **Discussion** — question, challenge or exploration with no acquired EKR status.

A status is attached to an artefact or decision. It is not conferred by popularity, contributor identity or maintainer preference.

## 4. What is a canonical-impact change?

A proposal is treated as canonical-impact when accepting it would materially change the public meaning or boundary of EKR, including a material change to:

- a canonical EKR distinction;
- an existing material public claim;
- the current public scope or publication boundary; or
- an existing canonical anchor.

A proposal may also trigger separate claim review when it introduces a materially new public proposition rather than supporting or clarifying an already controlled position.

## 5. Public proposal, separate acceptance path

Canonical-impact proposals may be raised and debated publicly. They cannot be accepted canonically through:

- issue popularity;
- contributor count;
- maintainer preference;
- an ordinary pull-request merge; or
- release of a Guidance document alone.

Under the current governance, canonical-impact acceptance is the responsibility of the **canonical steward, currently Jean Vieille**.

## 6. Public decision records

If a controlled decision is accepted and materially affects public EKR meaning or status, a public record is added under [`governance/decisions/`](decisions/).

A public decision record identifies, as applicable:

- the proposal or question;
- the decision;
- the public rationale;
- the affected canonical/public artefact;
- the effective version or release.

The record need not publish confidential or non-public review material, protected implementation detail, or information that cannot lawfully be disclosed.

## 7. When a canonical change becomes effective

Non-public control or review material cannot silently redefine public EKR.

A change to an existing canonical anchor becomes effective only when the affected canonical artefact is deliberately issued as a new controlled version or release. Until then, the currently published anchor remains authoritative.

## 8. Relationship to Guidance

Released Guidance may interpret and operationalise canonical EKR distinctions at a stated maturity. Guidance remains evolvable and is not automatically Canonical.

If Guidance development reveals a need to alter a canonical proposition, that question is escalated through this policy rather than being resolved implicitly inside the Guidance text.

## 9. Public-scope boundary

The public repository does not override separate decisions or controls governing publication, protection, confidentiality, security or intellectual property. Public discussion may identify an architectural question without authorising disclosure of protected or unpublished implementation material.
