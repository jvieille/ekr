# Contributing to EKR

Thank you for helping challenge, test and improve Enterprise Knowledge Representation and its Architectural Guidance.

EKR development is intentionally open to questions, counterexamples, evidence, implementation experience and alternative approaches. Contribution is open; **publication and canonical authority remain governed**.

The workflow is designed to be lightweight: start at the level that matches the maturity of the contribution, and add structure only when the work needs to be tracked or changed.

## 1. Choose the natural starting point

### GitHub Discussions

Use [GitHub Discussions](https://github.com/jvieille/ekr/discussions) for:

- broad architectural questions;
- conceptual debate and alternatives;
- early challenges or counterexamples;
- questions about existing EKR material;
- exploration of references and evidence before a structured submission.

A Discussion has **Discussion** status and implies no decision or acceptance.

Starting with a Discussion is optional. If a contribution is already concrete enough to be evaluated or tracked, open an Issue directly.

### Issues

Use the [structured Issue forms](https://github.com/jvieille/ekr/issues/new/choose) for material that is ready for evaluation:

- **Architectural proposal** — a proposed requirement, distinction, pattern or decision question;
- **Counterexample / challenge** — a case that may falsify, overconstrain or expose ambiguity in current framing or Draft Guidance;
- **Implementation experience / case** — observed experience from a system, architecture, standard, project or pilot;
- **Reference / evidence** — a primary source, standard, paper, specification or other relevant evidence.

Opening or triaging an Issue does not mean its proposed conclusion has been accepted.

The forms are intentionally short. Contributors should focus on the substance of the contribution; the maintainer is responsible for repository classification, release targeting and canonical-impact triage.

If an Issue grows out of a Discussion, include the Discussion link. A maintainer may also use GitHub's **Create issue from discussion** action and add a cross-reference back to the Issue so the origin remains visible.

### Pull requests

Use a pull request for a precise change to repository text or artefacts.

For substantive changes, a PR should normally be linked to an Issue. Use:

- `Closes #123` when the PR fully resolves the Issue and should close it when merged into `main`;
- `Relates to #123` when the PR contributes to the Issue but does not resolve it completely.

A small housekeeping or typographical change may be submitted without a prior Issue; state that explicitly in the PR description.

A merged PR may change Draft Guidance or repository material. It does **not** automatically change a canonical EKR anchor or make Draft Guidance into Released Guidance.

## 2. Evidence expectations

Please distinguish clearly between:

- an observation or implementation experience;
- an interpretation;
- a proposed architectural position;
- a primary or authoritative reference;
- a limitation or unresolved question.

For references and evidence, provide enough information to assess:

- source/authoritative body;
- title and version/date where relevant;
- maturity or publication status;
- the EKR or Guidance question it affects;
- the specific relevance you claim;
- known limitations or scope conditions.

Existing standards, platforms, ontologies, information models and architectural approaches should be assessed by the responsibilities they actually fulfil. Contributions should not assume that EKR is a replacement for them.

## 3. Counterexamples are welcome

A useful challenge may show that a current distinction is ambiguous, too broad, too narrow, too costly, insufficiently governed or already satisfied by an established approach.

Please provide enough context for others to understand the boundary conditions. A strong counterexample is more useful than a generic statement of disagreement.

## 4. Implementation experience and examples

Implementation cases enter the repository with **Example** status unless explicitly promoted through another governed process. They are non-normative and do not make a technology, product or architecture an EKR reference implementation.

State the context, objectives, constraints, observed outcome and limitations. Avoid generalising from a single case without evidence.

## 5. Public scope, security and intellectual-property boundary

Only contribute material that you are authorised to disclose publicly.

Do **not** submit confidential, classified, export-controlled, proprietary, personal-data or third-party material that you do not have the right to publish. Do not use the repository to disclose unpublished implementation mechanisms or other material that has not been authorised for public release under the applicable publication, protection, security or intellectual-property process.

If a useful contribution depends on information that cannot be disclosed, describe the public architectural question without exposing the protected material.

## 6. Status and canonical impact

The repository uses these public statuses: **Canonical, Released Guidance, Draft Guidance, Proposal, Example, Discussion**.

A contribution does not acquire EKR authority through popularity, acceptance for investigation or merge alone. If review shows that a proposal would materially affect a canonical EKR distinction, material public claim, current public scope or publication boundary, or canonical anchor, the maintainer marks it for escalation under the public [Canonicality Policy](governance/CANONICAL-POLICY.md).

Contributors are not expected to determine canonical impact themselves.

## 7. Contribution lifecycle and traceability

The normal workflow is:

**Discussion (optional) → structured Issue → triage → PR where a repository change is needed → Draft Guidance / repository update → release review → versioned release**

The stages are deliberately not automatic promotions.

### 7.1 Discussion to Issue

A Discussion may remain exploratory and end without an Issue. When it becomes concrete enough to track, a structured Issue is created or linked.

Where a Discussion exists, the Issue should retain a link to it, and the Discussion should point to the tracking Issue when practical.

### 7.2 Issue triage

New structured Issues receive the `triage` label. The maintainer reviews the Issue and then removes `triage` when the initial classification is complete.

Possible outcomes include:

- keep the Issue open for clarification or further evidence;
- accept it for work and, when relevant, assign it to a release milestone;
- defer it for later consideration;
- close it with a short public rationale when no further work is planned;
- add `canonical-impact` and route it through the separate canonicality process when required.

Acceptance for work means only that the question is worth acting on; it does not make the proposed conclusion an accepted EKR position.

### 7.3 Issue to PR

When repository text or another versioned artefact must change, the PR links the Issue using the convention above. The Issue remains the primary record of the question and its disposition; the PR is the concrete implementation of the change.

Not every Issue requires a PR. Evidence may be reviewed without changing Guidance, a challenge may confirm the existing text, and an implementation case may remain non-normative Example material.

### 7.4 Draft state

Merging a reviewed PR into `main` updates the current public draft state. If the change affects Draft Guidance, it becomes part of the evolving **Draft Guidance**, not a release.

### 7.5 Release targeting

Milestones are used to group Issues and PRs that are intended to contribute to a particular Guidance release, for example **EKR Architectural Guidance V0.1**.

A milestone is a planning and traceability device. Assignment to a milestone does not itself confer EKR status or guarantee inclusion in the release.

### 7.6 Released Guidance

A Guidance version becomes **Released Guidance** only after the explicit release review defined in [GOVERNANCE.md](GOVERNANCE.md).

When a release is approved, the repository should create:

- a version-specific Git tag;
- a GitHub Release based on that tag;
- release notes identifying the material changes and merged PRs;
- a corresponding entry in the Guidance `CHANGELOG.md`;
- closure of the associated release milestone after its remaining items have been dispositioned.

This provides a traceability chain from a release to its PRs, from PRs to Issues, and, where applicable, from Issues back to originating Discussions.

## 8. Licence of contributions

By submitting original text or documentation for inclusion in this repository, you agree that accepted material may be published under the repository licence stated in [LICENSE](LICENSE), unless a different licence is explicitly identified and accepted before inclusion.

Do not submit third-party content under incompatible terms.

## 9. Collaboration

Challenge ideas rigorously and contributors respectfully. Focus on architectural reasoning, evidence, explicit assumptions and boundary conditions. Product advocacy, personal attacks and unsupported claims do not help the EKR development process.
