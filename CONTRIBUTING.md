# Contributing to EKR

Thank you for helping challenge, test and improve Enterprise Knowledge Representation and its Architectural Guidance.

**You do not need to know Git or open a pull request to contribute.** Start with the simplest path that fits what you want to add. The maintainer takes responsibility for repository routing, classification and integration.

Contribution is open; **publication and canonical authority remain governed**.

## 1. Three contribution paths

### 1.1 Quick contribution — Discussion

Use [GitHub Discussions](https://github.com/jvieille/ekr/discussions) when you want to contribute in a few minutes without learning the repository workflow.

Good quick contributions include:

- a question about EKR material;
- a suggested reference or source;
- an error, ambiguity or terminology concern;
- a small clarification;
- an early idea or alternative;
- an observation that may deserve later investigation.

Write what you noticed or propose in ordinary language. Add a source or link when useful.

You do **not** need to decide whether the contribution should become an Issue, Proposal, Example, Guidance change or pull request. The maintainer will route it if additional structure is useful.

A Discussion may be answered or resolved there. If tracking or repository work is needed, the maintainer may create or link an Issue or prepare a pull request while preserving the Discussion as the origin of the contribution.

### 1.2 Structured contribution — one Issue form

Use the [Structured EKR contribution form](https://github.com/jvieille/ekr/issues/new/choose) when the contribution is already concrete enough to evaluate.

The form accepts, among other things:

- analysis or comparison;
- architectural proposal;
- counterexample or challenge;
- reference or evidence;
- implementation experience;
- reader aid or documentation clarification;
- another substantial contribution that needs tracked review.

A structured contributor is **not expected to create a branch or pull request**.

The maintainer performs initial triage, including classification, labels, release targeting and possible canonical-impact screening. If repository files need to change, the maintainer may prepare the linked pull request or invite a contributor who wants to edit the files directly.

### 1.3 Direct edit — optional pull request

Contributors who are comfortable with GitHub may propose a precise repository change directly by pull request.

For an external contributor, the normal technical path is:

1. fork the EKR repository to your own account;
2. create a branch in the fork;
3. commit the proposed change;
4. open a pull request to the protected main branch of jvieille/ekr.

A direct PR should link the originating Issue or Discussion when one exists. Small self-contained corrections may be proposed directly without creating a separate Issue.

This path is optional. It does not carry more scientific authority than a Discussion or structured Issue.

## 2. What happens after you contribute

The repository aims to keep contributor effort separate from maintainer integration work.

A maintainer may:

- answer or disposition a contribution without changing repository files;
- ask for clarification or evidence;
- create or link a tracking Issue when durable evaluation is needed;
- assign repository labels or a release milestone;
- prepare a pull request implementing an accepted clarification or change;
- invite the original contributor to review or comment when their input is needed;
- escalate a potential canonical-impact question through the separate canonicality process.

The original contribution should remain traceable. When a Discussion or Issue leads to a repository change, the implementation PR should link back to that source contribution where practical.

A contributor does not need to follow every technical step of integration unless they want to.

## 3. Scientific and evidence expectations

Please distinguish clearly between:

- an observation or implementation experience;
- an interpretation;
- a proposed architectural position;
- a primary or authoritative reference;
- a contributor-created illustrative extension;
- a limitation or unresolved question.

For references and evidence, provide enough information to identify the source and understand the claimed relevance. Prefer primary standards, specifications, peer-reviewed research, official project documentation or sufficiently described implementation evidence where available.

Existing standards, platforms, ontologies, information models and architectural approaches should be assessed by the responsibilities they actually fulfil. Contributions should not assume that EKR is a replacement for them.

Counterexamples are explicitly welcome. A strong counterexample may show that a current distinction is ambiguous, too broad, too narrow, too costly, insufficiently governed or already satisfied by an established approach.

## 4. Worked examples, reader aids and implementation experience

### Worked examples

Material in the examples/ area has **Example** status unless deliberately incorporated through another governed process. It is non-normative.

A worked example should state its purpose, source basis, assumptions, limitations and any contributor-created extension. See [examples/README.md](examples/README.md) and [examples/EXAMPLE-TEMPLATE.md](examples/EXAMPLE-TEMPLATE.md).

### Reader aids

Material under working-definition/reader-aids/ is explanatory repository material tied to an identified published EKR source.

A reader aid may help readers understand, navigate or interpret that source, but it must not silently introduce new EKR requirements, recommendations, architectural positions or implementation guidance. See [working-definition/reader-aids/README.md](working-definition/reader-aids/README.md).

A reader aid is a document type, not an additional EKR artefact status.

### Implementation experience

Implementation experience should state context, objective, what was observed, important constraints and limitations, and its relevance to an EKR question or architectural responsibility.

It remains non-normative unless deliberately incorporated into another governed artefact.

## 5. Status and governance boundary

The repository uses these public statuses:

**Canonical, Released Guidance, Draft Guidance, Proposal, Example, Discussion.**

A contribution does not acquire EKR authority through popularity, contributor effort, Issue acceptance or merge alone.

A maintainer may accept reviewed material into the repository within the authority defined in [GOVERNANCE.md](GOVERNANCE.md). If a contribution would materially affect a canonical EKR distinction, material public claim, public-scope boundary or canonical anchor, it is escalated under the public [Canonicality Policy](governance/CANONICAL-POLICY.md).

Contributors are not expected to determine canonical impact themselves.

## 6. Traceability without mandatory process

EKR preserves traceability, but it does not require every contribution to pass through every GitHub object.

Typical paths are:

**Quick contribution:**  
Discussion → maintainer disposition, or → Issue / PR when needed

**Structured contribution:**  
Issue → maintainer triage → PR when repository content must change

**Direct technical contribution:**  
PR → maintainer review and merge

For Guidance work, a merged PR updates the current Draft Guidance; it does not by itself create Released Guidance or alter a canonical anchor.

Where applicable, releases remain traceable to merged PRs, PRs to their source Issues or Discussions, and Issues to originating Discussions.

## 7. Pull-request review for direct editors

Pull requests are repository integration tools, not a required scientific contribution format.

For direct-edit PRs:

- link the source Issue or Discussion when one exists;
- keep the change focused;
- state important assumptions or limitations;
- use ordinary PRs when the change is ready for review;
- use GitHub Draft PRs only when the file change itself is genuinely still under construction.

Maintainers should prefer a concise review summary. Inline review threads are useful when discussion must stay attached to a specific line, but they should not be used merely to reproduce a general review conversation.

The maintainer is responsible for deciding when review comments have been adequately addressed before merge.

## 8. Notification and communication discipline

GitHub controls individual notification preferences, so the repository cannot eliminate all platform-generated notifications. EKR can, however, avoid creating unnecessary events.

The preferred practice is:

- one clear maintainer triage or synthesis comment rather than a sequence of administrative comments;
- no Issue or PR when a quick Discussion can be resolved directly;
- no Draft PR for routine documentation changes that are already ready for review;
- inline review comments only when line-level context is useful;
- mention the contributor again only when their input is actually requested;
- use **Announcements** for significant publications, releases or calls for contribution rather than routine repository activity.

## 9. Public scope and intellectual-property boundary

Only contribute material that you are authorised to disclose publicly.

Do **not** submit confidential, classified, export-controlled, proprietary, personal-data or third-party material that you do not have the right to publish.

If a useful contribution depends on information that cannot be disclosed, describe the public architectural question without exposing the protected material.

## 10. Licence of contributions

By submitting original text or documentation for inclusion in this repository, you agree that accepted material may be published under the repository licence stated in [LICENSE](LICENSE), unless a different licence is explicitly identified and accepted before inclusion.

Do not submit third-party content under incompatible terms.

## 11. Collaboration

Challenge ideas rigorously and contributors respectfully. Focus on architectural reasoning, evidence, explicit assumptions and boundary conditions. Product advocacy, personal attacks and unsupported claims do not help EKR development.
