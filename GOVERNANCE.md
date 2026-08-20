# EKR Repository Governance

## 1. Purpose

This document defines the current public governance of the EKR repository: artefact statuses, decision rights, contribution progression, escalation and release logic.

The repository is a public development workspace. It is not the canonical Working Definition and it does not replace the separate review and release process for canonical EKR claims and publications.

This governance may evolve as the EKR development process matures. Changes are made explicitly through the repository and remain subject to the canonical-impact rules defined below; a governance edit does not by itself redefine canonical EKR.

## 2. Three distinct forms of authority

EKR repository governance distinguishes three forms of authority even when the same person may exercise more than one role.

### Public discussion authority

Anyone participating through Discussions, Issues or pull requests may question, challenge, propose, provide evidence or suggest alternatives. Participation gives a contribution visibility; it does not give it EKR status.

### Repository-maintainer authority

The maintainer manages repository housekeeping, navigation, labels, contribution triage and draft artefacts. The maintainer may classify contributions, request evidence, close duplicates and merge changes that remain within the current public EKR boundary and do not create a new material public claim.

### Canonical EKR authority

Canonical-impact changes follow a separate governed path. Under the current governance, the canonical steward is **Jean Vieille**. Canonical authority is not delegated to issue popularity, contributor count, maintainer preference or an ordinary pull-request merge.

## 3. Artefact status model

| Status | Meaning | Typical artefact |
|---|---|---|
| **Canonical** | Published, versioned and formally designated as a canonical EKR anchor. | Working Definition V0.1 and future explicitly designated canonical anchors. |
| **Released Guidance** | Versioned guidance accepted for public use at a stated maturity. It remains evolvable and is not a standard or certification scheme. | EKR Architectural Guidance release. |
| **Draft Guidance** | Guidance under governed development; content may change materially. | Guidance seed and working drafts. |
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

## 5. Decision rights

The table below states the **current** decision authorities. These may evolve through explicit governance changes, subject to the same canonical-impact safeguards.

| Decision class | Current authority | Rule |
|---|---|---|
| Repository housekeeping, labels and navigation | Maintainer | May be changed directly if conceptual meaning or artefact status is not altered. |
| Discussion triage and issue classification | Maintainer | May classify, request evidence, close duplicates or convert/link a Discussion to an Issue; this does not decide canonical truth. |
| Draft Guidance wording | Maintainer, subject to current EKR governance | May be merged after review when it remains within the current public EKR boundary and creates no new material public claim. |
| New material public claim | Separate claim review | Requires explicit review and classification before it is published as an EKR position. Text that only supports or clarifies an existing controlled position may be treated as supporting detail. |
| Canonical-impact or canonical-anchor change | Canonical steward, currently Jean Vieille | May be proposed publicly but cannot be accepted through ordinary popularity or PR merge. Accepted public-impact decisions require a public decision record; an anchor change requires a new controlled version or release. |
| Matter outside the repository's current public scope | Applicable governance outside this repository | The repository cannot make such material public or give it EKR status. It may enter the repository's scope only after the applicable publication, protection, security, intellectual-property or other governance decision has authorised public treatment. |

## 6. Canonical-impact escalation

A contribution is escalated when it would materially alter a canonical EKR distinction, an existing material public claim, the current public scope or publication boundary, or an existing canonical anchor.

Such a contribution may be discussed publicly, but it is not accepted canonically through ordinary repository workflow. It enters separate review. If the resulting decision materially affects public EKR meaning, the outcome and rationale are recorded publicly in [`governance/decisions/`](governance/decisions/).

Non-public control or review material cannot silently redefine public EKR. A change to an existing canonical anchor becomes effective only through a controlled new version or release of that anchor.

See [`governance/CANONICAL-POLICY.md`](governance/CANONICAL-POLICY.md).

## 7. Guidance release logic

Draft Guidance is explicitly provisional. A version becomes Released Guidance only through an explicit, versioned release decision after review of scope, evidence, claim impact and boundary conditions.

Release does not imply standardisation, certification, universal applicability or canonical status.

## 8. Conflicts and unresolved questions

Where a contribution cannot be resolved without changing a canonical distinction, introducing a new material public claim, altering the current public scope or publication boundary, or deciding whether non-public material may be released, the repository does not decide the matter by vote or merge. The item is referred to the applicable review or governance process and may remain open as a Proposal or Discussion until that process is complete.

## 9. Repository neutrality

Repository governance must not turn EKR into a product channel, a platform mandate, a hidden reference implementation or a vehicle for privileging one technology. Implementation experience is welcome as evidence, but it remains non-normative unless deliberately incorporated into versioned guidance under this process.
