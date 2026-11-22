# EKR Repository Governance

## 1. Purpose

This document defines the current public governance of the EKR repository: artefact statuses, decision rights, contribution progression, escalation, traceability and release logic.

The repository is a public development workspace. It is not the canonical Working Definition and it does not replace the separate review and release process for canonical EKR claims and publications.

This governance may evolve as the EKR development process matures. Changes are made explicitly through the repository and remain subject to the canonical-impact rules defined below; a governance edit does not by itself redefine canonical EKR.

## 2. Three distinct forms of authority

EKR repository governance distinguishes three forms of authority even when the same person may exercise more than one role.

### Public contribution authority

Anyone participating through Issues, pull requests or broader Discussions may question, challenge, propose, provide evidence or suggest alternatives. Participation gives a contribution visibility; it does not give it EKR status.

### Repository-maintainer authority

The maintainer manages repository housekeeping, navigation, labels, contribution triage, traceability and draft artefacts. The maintainer may classify contributions, request evidence, close duplicates, assign release milestones and merge changes that remain within the current public EKR boundary and do not create a new material public claim.

Repository write and merge access is reserved to maintainers authorised to exercise the corresponding repository decision rights. GitHub permission is the technical implementation of those rights; it does not independently create EKR governance authority. A contributor does not become a maintainer by submitting a pull request, and granting technical access must follow an explicit governance decision.

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

GitHub labels, milestones, branches and open/closed states support workflow and traceability. They are **not additional EKR statuses**.

## 4. Normal contribution progression

The normal public contribution path is deliberately simple:

**Issue → maintainer triage → PR when repository content must change → maintainer review and merge**

A contributor does not need to choose an EKR category, label, status or repository destination. Classification and routing are maintainer responsibilities.

A contributor who is comfortable editing repository files directly may submit a pull request instead. GitHub Discussions remain available for broader conversation, but they are not a required stage in the EKR contribution process.

```mermaid
flowchart LR
    I["Contribution Issue"] --> T[Maintainer triage]
    T --> N["Disposition without repository change"]
    T --> P["Maintainer PR<br/>when repository content must change"]
    X["Optional direct PR"] --> R[Maintainer review]
    P --> R
    R --> M[Maintainer merge]
    M --> S["Current repository state<br/>Draft Guidance where applicable"]
    S --> G["Explicit release review<br/>when a Guidance release is prepared"]
```

The stages are deliberately not automatic promotions.

- An Issue may be answered, clarified, deferred or closed without a repository change.
- An Issue may be accepted for investigation or work without accepting its conclusion.
- Not every Issue requires a PR.
- A merged pull request may update Draft Guidance or another repository artefact without changing a canonical anchor.
- A Released Guidance document does not become Canonical merely by being released.
- Canonical change follows the separate escalation path described below.

## 5. Decision rights

The table below states the **current** decision authorities. These may evolve through explicit governance changes, subject to the same canonical-impact safeguards.

| Decision class | Current authority | Rule |
|---|---|---|
| Repository housekeeping, labels and navigation | Maintainer | May be changed directly if conceptual meaning or artefact status is not altered. |
| Issue triage and contribution classification | Maintainer | May classify, label, request evidence, close duplicates, assign repository routing or disposition an Issue; this does not decide canonical truth. |
| Release-milestone assignment | Maintainer | Indicates intended release scope for tracking only; it does not guarantee inclusion or confer EKR status. |
| Draft Guidance wording | Maintainer, subject to current EKR governance | May be merged after review when it remains within the current public EKR boundary and creates no new material public claim. |
| Guidance release | Maintainer under this governance and the applicable release review | Requires an explicit versioned release decision; a milestone completion or PR merge alone is insufficient. |
| New material public claim | Separate claim review | Requires explicit review and classification before it is published as an EKR position. Text that only supports or clarifies an existing controlled position may be treated as supporting detail. |
| Canonical-impact or canonical-anchor change | Canonical steward, currently Jean Vieille | May be proposed publicly but cannot be accepted through ordinary popularity or PR merge. Accepted public-impact decisions require a public decision record; an anchor change requires a new controlled version or release. |
| Matter outside the repository's current public scope | Applicable governance outside this repository | The repository cannot make such material public or give it EKR status. It may enter the repository's scope only after the applicable publication, protection, security, intellectual-property or other governance decision has authorised public treatment. |

## 6. Issue lifecycle and disposition

Issues are the normal public entry point for EKR contributions.

The public Issue chooser provides one contribution form. Contributors are not required to classify their contribution. The maintainer applies labels and repository routing during triage.

Initial triage may result in:

- an answer or clarification;
- a request for additional evidence or context;
- maintainer-applied labels;
- assignment to a release milestone where relevant;
- preparation of a linked pull request when repository content should change;
- deferral;
- closure with a short public rationale;
- canonical-impact escalation.

The Issue remains the public record of the contribution and its disposition.

GitHub Discussions may still host broader conversations. If a Discussion later produces an actionable contribution, the maintainer may create or invite an Issue and cross-link it, but this is not required for ordinary participation.

## 7. Pull requests, branches and draft integration

Pull requests are the controlled mechanism by which repository file changes enter the protected `main` branch. They are **not a required contribution format for non-technical contributors**.

When an accepted Issue requires a repository change, the maintainer may prepare the implementation PR and link it back to the Issue. A contributor who is comfortable editing files directly may instead submit the PR themselves.

External contributors who choose the direct-edit path normally work in a branch of their own fork and open a pull request against `jvieille/ekr:main`. Maintainers may work in a non-`main` branch in the repository or in a fork.

`main` is the protected **current public development state** of the repository. It is not synonymous with **Released Guidance**, and a permanent draft branch is not required. Draft/Released/Canonical are artefact statuses, not branch names.

GitHub workflow states such as Draft pull request, Open, Merged or Closed are repository workflow states. They must not be confused with EKR artefact statuses such as Draft Guidance or Released Guidance.

A substantive PR should link the source Issue when one exists. Small self-contained corrections may be proposed directly.

Maintainer review should be proportionate to the change. Inline review conversations may be used when line-level context is useful, but contributors are not required to master GitHub review-state mechanics in order to contribute scientifically. The maintainer is responsible for ensuring substantive review points are addressed before merge.

A maintainer merge into `main` is a governed acceptance of that change into the current repository state. If it changes Draft Guidance, it changes the draft, not the release status. Merge authority therefore carries repository decision authority only within the scope assigned to the maintainer under this governance; it does not by itself authorise a Guidance release, a new material public claim or a canonical change.

## 8. Release planning and traceability

Milestones may be used to group Issues and PRs intended for a particular Guidance release. A milestone expresses intended release scope and provides progress visibility; it is not a release decision and does not change artefact status.

The intended release chain is:

**Released Guidance → Git tag / GitHub Release → merged PRs → source Issues, where applicable**

```mermaid
flowchart LR
    R[Released Guidance V0.x] --> T["Version-specific Git tag<br/>and GitHub Release"]
    T --> P[Merged pull requests]
    P --> I["Source Issues<br/>where applicable"]
```

To preserve that chain:

- release-targeted Issues and PRs should be associated with the relevant milestone where practical;
- substantive PRs should link the Issue that motivated the change where one exists;
- Guidance release notes should identify the merged PRs included in the released version;
- the Guidance changelog should record each versioned release and point to the corresponding release record.

A direct technical PR may have no prior Issue when the change is small and self-contained; the PR itself then provides the contribution record.

## 9. Canonical-impact escalation

A contribution is escalated when it would materially alter a canonical EKR distinction, an existing material public claim, the current public scope or publication boundary, or an existing canonical anchor.

Such a contribution may be discussed publicly, but it is not accepted canonically through ordinary repository workflow. It enters separate review. If the resulting decision materially affects public EKR meaning, the outcome and rationale are recorded publicly in [`governance/decisions/`](governance/decisions/).

Non-public control or review material cannot silently redefine public EKR. A change to an existing canonical anchor becomes effective only through a controlled new version or release of that anchor.

```mermaid
flowchart LR
    C[Issue or PR] --> CI[canonical-impact]
    CI --> CR[Separate canonical review]
    CR --> DR["Public decision record<br/>when public meaning is affected"]
    DR --> CA["New canonical anchor/version<br/>when required"]
```

See [`governance/CANONICAL-POLICY.md`](governance/CANONICAL-POLICY.md).

## 10. Guidance release logic

Draft Guidance is explicitly provisional. The current draft may evolve on `main` through reviewed pull requests. A version becomes **Released Guidance** only through an explicit release decision after review of:

- the intended version scope and unresolved items;
- the relevant evidence, implementation experience and challenges;
- linked Issues and merged PRs;
- claim and canonical impact;
- public-scope and boundary conditions;
- version metadata and changelog accuracy.

When approved, the release is fixed to a version-specific Git tag and published as a GitHub Release with release notes. The corresponding Guidance changelog entry records the release and its status. The associated milestone may then be closed after any remaining items have been explicitly moved, deferred or otherwise dispositioned. New work then continues on `main` through new pull requests while the tagged release remains immutable.

```mermaid
flowchart TD
    B["Maintainer or contributor<br/>change branch"] --> P[Pull request to main]
    P --> M[Maintainer review and merge]
    M --> MAIN["main<br/>current public development state"]
    MAIN --> D[Draft Guidance evolves]
    MAIN --> RR[Explicit release preparation and review]
    RR --> TAG[Version-specific Git tag]
    TAG --> REL["GitHub Release<br/>Released Guidance V0.x"]
    REL -. subsequent work through new PRs .-> MAIN
```

Release does not imply standardisation, certification, universal applicability or canonical status.

## 11. Conflicts and unresolved questions

Where a contribution cannot be resolved without changing a canonical distinction, introducing a new material public claim, altering the current public scope or publication boundary, or deciding whether non-public material may be released, the repository does not decide the matter by vote or merge. The item is referred to the applicable review or governance process and may remain open as an Issue or broader Discussion until that process is complete.

## 12. Repository neutrality

Repository governance must not turn EKR into a product channel, a platform mandate, a hidden reference implementation or a vehicle for privileging one technology. Implementation experience is welcome as evidence, but it remains non-normative unless deliberately incorporated into versioned guidance under this process.
