# EKR Repository Governance

## 1. Purpose

This document defines the public governance of the EKR repository: artefact statuses, decision rights, contribution progression, escalation and release logic.

The repository is a public development workspace. It is not the canonical Working Definition and it does not replace controlled EKR claim or publication governance.

## 2. Three distinct forms of authority

EKR launch governance distinguishes three forms of authority even when the same person may temporarily exercise more than one role.

### Public discussion authority

Anyone participating through Discussions, Issues or pull requests may question, challenge, propose, provide evidence or suggest alternatives. Participation gives a contribution visibility; it does not give it EKR status.

### Repository-maintainer authority

The maintainer manages repository housekeeping, navigation, labels, contribution triage and draft artefacts. The maintainer may classify contributions, request evidence, close duplicates and merge changes that remain within the existing controlled boundary.

### Canonical EKR authority

Canonical-impact changes follow a separate controlled path. At launch, the founding canonical steward is **Jean Vieille**. Canonical authority is not delegated to issue popularity, contributor count, maintainer preference or an ordinary pull-request merge.

## 3. Artefact status model

| Status | Meaning | Typical artefact |
|---|---|---|
| **Canonical** | Published, versioned and formally designated as a canonical EKR anchor. | Working Definition V0.1 and future explicitly designated canonical anchors. |
| **Released Guidance** | Versioned guidance accepted for public use at a stated maturity. It remains evolvable and is not a standard or certification scheme. | EKR Architectural Guidance release. |
| **Draft Guidance** | Guidance under controlled development; content may change materially. | Guidance seed and working drafts. |
| **Proposal** | Structured suggestion, alternative, pattern or change request submitted for evaluation. | Issue or proposal artefact. |
| **Example** | Non-normative illustration, implementation experience or case used to test guidance. | Contributed example or case. |
| **Discussion** | Conversation, question, challenge or exploration with no acquired EKR status. | GitHub Discussion. |

## 4. Normal public progression

The normal progression is:

**Discussion → Proposal or evidence item → triage → Draft Guidance change → review → Released Guidance**

This is not an automatic promotion pipeline.

- A Discussion may end without an issue or decision.
- An Issue may be accepted for investigation without accepting its conclusion.
- A merged pull request may update Draft Guidance or a repository artefact without changing a canonical anchor.
- A Released Guidance document does not become Canonical merely by being released.
- Canonical change follows the separate escalation path described below.

## 5. Decision rights at launch

| Decision class | Launch authority | Rule |
|---|---|---|
| Repository housekeeping, labels and navigation | Maintainer | May be changed directly if conceptual meaning or artefact status is not altered. |
| Discussion triage and issue classification | Maintainer | May classify, request evidence, close duplicates or convert/link a Discussion to an Issue; this does not decide canonical truth. |
| Draft Guidance wording | Maintainer under the current controlled EKR sources | May be merged after review when it stays within the existing boundary and creates no new material public claim. |
| New material public claim | Controlled claim review | Requires a registered claim/classification or an explicit determination that the text is supporting detail rather than a new material proposition. |
| Canonical-impact or canonical-anchor change | Founding canonical steward under controlled EKR governance | May be proposed publicly but cannot be accepted through ordinary popularity or PR merge. Accepted public-impact decisions require a public decision record; an anchor change requires a new controlled version/release. |
| Material subject to a separate publication/protection gate | Separate governance | Outside the launch repository's decision authority until the applicable gate is closed. |

## 6. Canonical-impact escalation

A contribution is escalated when it would materially alter a canonical EKR distinction, an existing material claim, the public/reserved boundary, or an existing canonical anchor.

Such a contribution may be discussed publicly, but it is not accepted canonically through ordinary repository workflow. It enters controlled review. If the resulting decision materially affects public EKR meaning, the outcome and rationale are recorded publicly in [`governance/decisions/`](governance/decisions/).

A private control document cannot silently redefine public EKR. A change to an existing canonical anchor becomes effective only through a controlled new version or release of that anchor.

See [`governance/CANONICAL-POLICY.md`](governance/CANONICAL-POLICY.md).

## 7. Guidance release logic

Draft Guidance is explicitly provisional. A version becomes Released Guidance only through an explicit, versioned release decision after review of scope, evidence, claim impact and boundary conditions.

Release does not imply standardisation, certification, universal applicability or canonical status.

## 8. Conflicts and unresolved questions

Where a contribution cannot be resolved without changing a canonical distinction, introducing a new material public claim, altering the public/reserved boundary or crossing a separate protection/publication gate, the repository does not decide the matter by vote or merge. The item is marked for controlled review and may remain open as a Proposal or Discussion until that review is complete.

## 9. Repository neutrality

Repository governance must not turn EKR into a product channel, a platform mandate, a hidden reference implementation or a vehicle for privileging one technology. Implementation experience is welcome as evidence, but it remains non-normative unless deliberately incorporated into versioned guidance under this process.
