# EKR Reference Landscape — Candidate Register

**Version:** RL V0.1 (22 November 2026)  
**Status:** Living, non-normative research index. **Not** Draft Guidance, Released Guidance, a canonical EKR statement, a conformance assessment, or an endorsement.

This register resides within the existing [References and Evidence](../README.md) area of the public EKR repository, and operates under its [contribution](../../CONTRIBUTING.md) and [governance](../../GOVERNANCE.md) rules.

## Purpose

Maintain discoverable references to scientific work, standards, models, ontologies, enterprise/data architectures, specifications, platforms, industrial patterns and engineering methods relevant to EKR, **whether or not they have been studied**.

The first release deliberately captures *candidate* references. Analysis, comparison and architectural decisions are separate and traceable activities.

## Files

- `references.yaml`: machine-readable, manually maintained source of truth.
- `LAUNCH-BRIEF.md`: remit, boundaries and coordination.
- Future `analyses/`: focused source-grounded reference analyses (RA).
- Future `convergence/`: cross-reference architectural comparisons (AC).
- Guidance proposals and decisions stay in the repository's existing governed paths, not in this index.

## Core record conventions

| Field | Meaning |
| --- | --- |
| `id` | Immutable RL identifier; never reused. |
| `name` | Human-readable reference designation, not necessarily a formal title. |
| `kind` | Standard family, individual part/amendment, research, ontology, architecture, specification, product, etc. |
| `area` | Primary navigation bucket only. Multi-area coverage is captured by `dimensions`. |
| `dimensions` | Preliminary research tags; **not evidence of implemented capabilities**. |
| `priority` | Editorial/research interest: `high`, `normal`, or `watch`. |
| `knowledge_state` | `identified`, `source_located`, `documented`, `analysed`, or `compared`. |
| `source_state` | `publisher_page_checked`, `catalogue_page_checked`, `vendor_page_checked`, `locator_unverified`, or `locator_pending`. |
| `source_url` | Pointer to a source. A vendor landing page is **not** implementation evidence. |
| `parent_id` | Optional parent family or amended specification; no implied equivalence. |
| `relationships` | Optional typed relationships to other RL IDs, with a source URL supporting the relationship; distinguish vendor assertions from independently demonstrated dependencies. |
| `note` | Scope caveat or research reminder; not a finding. |

Dates, editions and specific claims must be independently checked before being treated as validated. A checked publisher catalogue page does not imply full-text standard review. A checked vendor page only establishes what the vendor publicly states, **not** independent proof of product capabilities. A record must never be promoted to an EKR position merely because it appears in this register.

## Adding and maintaining references

1. Search for an existing reference under alternative names; avoid duplicates.
2. Create an ID and minimal record even if its source is not yet known. Mark missing sources `locator_pending`.
3. Prefer authoritative primary sources; retain stable DOI or publisher references where available.
4. Register a family and each material edition/part/amendment separately where their scope or lifecycle matters.
5. Keep source verification, investigation progress and research priority **independent**.
6. Store detailed findings as RA or AC analyses with explicit evidence and unresolved questions.
7. Route proposals to the existing structured Issue → PR governance; do **not** silently revise EKR Working Definition or Guidance.
8. Regularly review high-priority versions and broken links; avoid claiming an item is current unless freshly checked.

## Research guardrails

- Distinguish author claims, standards text, interpretations, demonstrated operation and unverified hypotheses.
- Assess each approach against **its own aims first**, then compare with EKR.
- Separate representation, mediation, interoperability, composition, execution and authority.
- Maintain the difference between preparation for interoperability, evaluated compatibility and demonstrated cooperation.
- Do not force all references into a single ontology or into an EKR-specific responsibility model.
- Do not publish confidential or uncleared NRO/SPE/neuromorphic-routing material. Internal candidate references can be tracked outside this public repository pending a release/IP decision.

## Immediate investigation candidates

- **ISO/IEC 11179 × ANSI/ISA-95.00.07**: item mapping, identity, aliasing, equivalence and governance, using the P-101 / EQ-4732 example as a test case.
- **OPC UA / Companion Specifications × CESMII i3X × FCP-PILOT**: what can be exposed, verified and independently reproduced.
- **BFO / IOF and plural ontological commitment**: costs and limits of shared commitments.
- **Enterprise AI / event-driven composition**: context, authority, matching, composition and execution.

The landscape is an open research resource. No comparison result, profile, binding or certification is implied by the presence of these topics.
