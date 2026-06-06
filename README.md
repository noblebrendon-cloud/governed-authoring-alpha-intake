# Governed Authoring Studio Alpha Intake Spine

## Repository Purpose

This repository documents the public alpha intake surface for Governed Authoring Studio.

It exists as a proof spine, not as a marketing site and not as the full internal system. It establishes a timestamped public record for the alpha intake layer: what the public-facing intake page said, how material could be submitted, what privacy and boundary language existed, and how the alpha status was disclosed.

## What This Repo Proves

- A public intake explanation existed.
- A submission path existed.
- Privacy and boundary framing existed.
- Alpha-stage disclosure existed.
- The intake process connected to a larger governed authoring pipeline.
- The public surface was versioned before later beta, app, or pre-seed stages.

## What This Repo Does Not Include

- Private participant materials.
- Internal prompts.
- Unpublished books.
- Trial data.
- Backend orchestration.
- Internal evaluators.
- Full Governed Authoring System implementation.

## Larger System Context

Governed Authoring Studio sits over a larger governed authoring process:

```text
raw material
-> capture
-> branch extraction
-> branch mapping
-> structural compression
-> spine discovery
-> author validation
-> governed drafting
-> audit / lineage / claim tracking
-> artifact generation
```

This repository only covers the alpha intake layer. It documents the public-facing explanation and submission path without exposing private prompts, participant materials, internal evaluators, trial data, unpublished manuscripts, or backend orchestration.

## Repository Structure

- `index.html` - Static public alpha intake explanation page.
- `README.md` - Repository purpose, proof claims, scope boundaries, and release logic.
- `CHANGELOG.md` - Version history using a simple Keep a Changelog structure.
- `CITATION.cff` - Citation metadata for the public proof spine.
- `LICENSE` - Plain-language custom public proof spine license.
- `docs/alpha-intake-method.md` - Separate method note describing the alpha intake principle, first-pass analysis, output categories, and proof-spine logic.

## Release Logic

- Commits are for ordinary edits.
- GitHub releases are for named milestone states.
- Zenodo archival should be used only for stable milestone releases.
- Releases should not include private participant material.

Planned milestone examples:

- `v0.1-alpha-intake`
- `v0.2-alpha-validation`
- `v0.3-spine-discovery-packet`
- `v0.4-beta-operator-packet`

## Suggested Deployment

GitHub Pages can serve `index.html` directly from the repository root. No build step is required.

A custom domain or subdomain can be connected later if the public text is reviewed and the page is ready to be served under that address.
