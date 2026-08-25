# Working Definition Reader Aids

This directory contains contributor-authored reading aids tied to the canonical **Enterprise Knowledge Representation — Working Definition V0.1**.

A **reader aid** is a non-canonical explanatory artefact whose purpose is to help readers understand, navigate or interpret a specific published EKR source without introducing new EKR requirements, recommendations, architectural positions or implementation guidance.

Typical reader aids may include:

- glossaries;
- reading guides;
- terminology or concept maps;
- FAQs tied to the source text;
- cross-reference or navigation aids.

A reader aid is not Architectural Guidance. If material develops recommendations, design rules, architectural decisions, implementation patterns or other positions that remain meaningful independently of the source being explained, it belongs in Guidance or another appropriate repository path.

Reader aids are **not a separate EKR artefact status**. They are explanatory repository material and do not become Canonical, Released Guidance or Draft Guidance through publication or merge.

The canonical public definition remains the English V0.1 archived at its DOI:

**Jean Vieille. _Enterprise Knowledge Representation — Working Definition V0.1_. Version 0.1, 14 August 2026.**  
https://doi.org/10.5281/zenodo.21914714

## Content expectations

A reader aid should:

- identify its author;
- state clearly that it is non-canonical;
- identify the published EKR source on which it is based;
- distinguish plain-language explanation from canonical wording;
- keep substantive statements traceable to the source it explains, except for clearly identified pedagogical explanations that do not extend the source's meaning;
- avoid introducing a competing definition or silently changing EKR boundaries;
- avoid recommendations, implementation guidance or new architectural positions.

A useful boundary test is: **if a statement would still function as an independent EKR recommendation after removing the source document from view, it probably does not belong in a reader aid.**

## Contributing a reader aid

A new reader aid should normally begin with a **Reader aid / documentation clarification** Issue so that its purpose, authorship, source basis and interpretation boundary can be reviewed before repository publication.

Once sufficiently defined, submit the reader aid through a pull request linked to that Issue, normally using `Closes #<issue>` when the PR fully implements it.

Small corrections to an existing reader aid may be proposed directly by pull request when their scope is self-evident and they do not change the interpretation boundary.

## Available reader aids

No reader aid has been published in this directory yet.
