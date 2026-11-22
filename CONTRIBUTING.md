# Contributing to EKR

Thank you for helping challenge, test and improve Enterprise Knowledge Representation and its Architectural Guidance.

**You do not need to know Git or open a pull request to contribute.** The normal contribution path is a single GitHub Issue. The maintainer takes responsibility for classification and repository integration.

Contribution is open; **publication and canonical authority remain governed**.

## 1. Open an Issue

Open a [GitHub Issue](https://github.com/jvieille/ekr/issues/new) for any contribution you want EKR to consider.

This includes questions, corrections, references, analyses, comparisons, architectural proposals, counterexamples, implementation experience, reader aids and documentation clarifications.

There is no specialised contribution form and no contributor-side classification. You do **not** need to decide which category, status, label or repository artefact your contribution belongs to.

A useful contribution can be very simple:

- explain what you noticed, question or propose;
- add a source, link or example when useful;
- mention important context or limitations if they matter.

The maintainer handles labels, classification, release targeting, canonical-impact screening and any required repository change.

## 2. What happens after you contribute

The maintainer may:

- answer or disposition the Issue without changing repository files;
- ask for clarification or evidence;
- add labels or a release milestone;
- prepare a pull request implementing an accepted clarification or change;
- invite the contributor to review the resulting interpretation or text when useful;
- escalate a potential canonical-impact question through the separate canonicality process.

The Issue remains the public record of the contribution and its disposition.

A contributor does not need to follow the technical integration steps unless they want to.

## 3. Direct edit — optional pull request

Contributors who are comfortable with GitHub may propose a precise repository change directly by pull request.

For an external contributor, the usual technical path is:

1. fork the EKR repository;
2. create a branch;
3. commit the proposed change;
4. open a pull request to the protected `main` branch.

A direct PR should link the relevant Issue when one exists. A small self-contained technical or editorial correction may be proposed directly without creating a separate Issue.

This path is optional. It does not carry more scientific authority than an Issue contribution.

## 4. Scientific and evidence expectations

Please distinguish clearly, where relevant, between:

- observation or implementation experience;
- interpretation;
- proposed architectural position;
- primary or authoritative reference;
- contributor-created illustrative extension;
- limitation or unresolved question.

For references and evidence, provide enough information to identify the source and understand the claimed relevance. Prefer primary standards, specifications, peer-reviewed research, official project documentation or sufficiently described implementation evidence where available.

Existing standards, platforms, ontologies, information models and architectural approaches should be assessed by the responsibilities they actually fulfil. Contributions should not assume that EKR is a replacement for them.

Counterexamples are explicitly welcome.

## 5. Worked examples, reader aids and implementation experience

Material in `examples/` has **Example** status unless deliberately incorporated through another governed process. It is non-normative.

Reader aids under `working-definition/reader-aids/` are explanatory material tied to an identified published EKR source. They must not silently introduce new EKR requirements, recommendations, architectural positions or implementation guidance.

Implementation experience should state enough context, constraints and limitations to understand what was observed and how broadly it may apply.

## 6. Status and governance boundary

The repository uses these public statuses:

**Canonical, Released Guidance, Draft Guidance, Proposal, Example, Discussion.**

A contribution does not acquire EKR authority through popularity, contributor effort, Issue acceptance or merge alone.

A maintainer may accept reviewed material into the repository within the authority defined in [GOVERNANCE.md](GOVERNANCE.md). If a contribution would materially affect a canonical EKR distinction, material public claim, public-scope boundary or canonical anchor, it is escalated under the public [Canonicality Policy](governance/CANONICAL-POLICY.md).

Contributors are not expected to determine canonical impact themselves.

## 7. Traceability without unnecessary workflow

The normal path is:

**Issue → maintainer triage → PR when repository content must change → maintainer review and merge**

A direct technical PR may enter at the PR stage.

For Guidance work, a merged PR updates the current Draft Guidance; it does not by itself create Released Guidance or alter a canonical anchor.

The repository preserves links between an Issue and any resulting PR so that the contribution and its disposition remain traceable.

GitHub Discussions remain available for broader conversation, but they are not a required stage in the contribution process.

## 8. Pull-request review for direct editors

Pull requests are repository integration tools, not a required scientific contribution format.

For direct-edit PRs:

- link the source Issue when one exists;
- keep the change focused;
- state important assumptions or limitations;
- use ordinary PRs when the change is ready for review;
- use GitHub Draft PRs only when the file change itself is genuinely unfinished.

Maintainers should prefer concise review. Inline review threads are useful when line-level context matters, but they should not be used merely to reproduce a general review conversation.

The maintainer is responsible for deciding when review points have been adequately addressed before merge.

## 9. Notification and communication discipline

GitHub controls individual notification preferences, so the repository cannot eliminate all platform-generated notifications. EKR can avoid creating unnecessary events.

Preferred practice:

- use one clear maintainer triage or synthesis comment rather than a sequence of administrative comments;
- create a PR only when repository content actually needs to change;
- avoid Draft PRs for routine documentation changes that are already ready for review;
- use inline review comments only when line-level context is useful;
- mention contributors again only when their input is actually requested;
- use **Announcements** for significant publications, releases or calls for contribution rather than routine repository activity.

## 10. Public scope and intellectual-property boundary

Only contribute material that you are authorised to disclose publicly.

Do **not** submit confidential, classified, export-controlled, proprietary, personal-data or third-party material that you do not have the right to publish.

If a useful contribution depends on information that cannot be disclosed, describe the public architectural question without exposing the protected material.

## 11. Licence and collaboration

By submitting original text or documentation for inclusion in this repository, you agree that accepted material may be published under the repository licence stated in [LICENSE](LICENSE), unless a different licence is explicitly identified and accepted before inclusion.

Challenge ideas rigorously and contributors respectfully. Focus on architectural reasoning, evidence, explicit assumptions and boundary conditions.
