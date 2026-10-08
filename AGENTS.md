# information-feed-filter Canonical Agent Rules

## Purpose

Reserved couche-1 product home for Libre AI Information Feed Filter: turn
information subscriptions into a selection that can be inspected and
understood, without unexplained recommendations.
Doctrine lives upstream: https://raw.githubusercontent.com/libre-ai/project-governance/HEAD/AGENTS.md

## Domain doctrine

- Every retained item carries the explicit rule that selected it, its source
  and its relevant dates.
- Retrieving a source is distinct from transmitting a person's private
  subscription data; destination restrictions hold at each request,
  redirects included.
- `project.v1.yaml` is the authority on project state and admission
  criteria; the README "Project status" section is generated from it —
  never edit that section by hand.
- Recovered code (`apps/radar`) is not product qualification.
- Contract shapes are canonical in `libre-ai/schemas-and-contracts`, consumed
  pinned, never redefined here.

## Commands

- Prepare the pinned composition (target `information-feed-filter`):
  https://raw.githubusercontent.com/libre-ai/project-governance/HEAD/docs/LOCAL-COMPOSITION.md
- `bun run check` from this repository's root in the composition.

## Working here

- Security > quality > performance > completeness, in that order on conflict.
- Check real state before editing: `git status --short` and the check above;
  never hide a red test.
- English for code, comments and this file.
- Never commit a machine-local absolute filesystem path, a secret or a
  personal identifier.
