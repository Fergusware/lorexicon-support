# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Lorexicon is a GM assistant for Pathfinder 2e Remaster, available as both a **Foundry VTT module** and a standalone **web application** (Lorexicon Web at https://app.fergusware.com). This **public repository** is the support and documentation hub — the actual codebase is proprietary and hosted privately. This repo handles:

- User-facing documentation (Jekyll site hosted on GitHub Pages)
- Issue tracking (bug reports, feature requests)
- Release distribution (module manifest + zip downloads)
- Community discussion

## Repository Structure

- `docs/` — Jekyll documentation site (guides, FAQ, examples, prompt inspiration)
- `docs/_layouts/`, `docs/_includes/`, `docs/css/` — Jekyll templating and styling
- `docs/examples/` — Sample creations showcasing module capabilities
- `docs/inspiration/` — Prompt idea starters organized by creation type
- `manifests/module.json` — Foundry module manifest (version, compatibility, download URLs)
- `.github/ISSUE_TEMPLATE/` — Bug report and feature request templates

## Documentation Site

Built with Jekyll using the `pages-themes/minimal@v0.2.0` remote theme. Config is in `docs/_config.yml`. Deployed via GitHub Pages at: https://support.fergusware.com/lorexicon-support/

The site automatically rebuilds and deploys whenever changes are merged to `main`. This is configured on the GitHub side (Settings > Pages), not in the repository.

## Formatting

- Prettier is the formatter (VS Code default formatter: `esbenp.prettier-vscode`)
- 2-space indentation, format-on-save for JS, JSON, Markdown, HTML, CSS
- ESLint auto-fix on save
- `docs/_layouts/default.html` is excluded from Prettier (see `.prettierignore`)

## Release Process

When updating a release:
1. Update version in `manifests/module.json` (version field, download URL)
2. Update `CHANGELOG.md` with the new version's changes
3. Commit and tag the release

The manifest download URL follows the pattern:
`https://github.com/Fergusware/lorexicon-support/releases/download/v{VERSION}/lorexicon-{VERSION}.zip`

## Module Compatibility

- Foundry VTT module: minimum v12, verified v13.351, maximum v13
- Pathfinder 2e System: minimum v6.12.4
- Lorexicon Web: any modern browser + Patreon account (no Foundry required)

## Writing Style

All user-facing text must follow the project's distinctive Renaissance Faire barker voice — theatrical, warm, and steeped in RPG metaphor while remaining clear and accurate. Use the `/copy-writer` skill when writing or editing any user-facing documentation. The skill (in `.claude/skills/copy-writer/SKILL.md`) contains the full style guide including tone rules, vocabulary mappings, structural conventions, and pitfalls to avoid.
