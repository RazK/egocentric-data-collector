# Egocentric Data Collector

This repository contains a polished static proposal website for GitHub Pages.

## GitHub Pages setup

1. Open the repository on GitHub.
2. Go to Settings > Pages.
3. Under Source, choose Deploy from a branch.
4. Select the main branch and the / (root) folder.
5. Save the changes.

The published site will be available at:
https://razk.github.io/egocentric-data-collector/

## Files

- index.html — proposal content and semantic page structure
- styles.css — layout, typography, responsive behavior and print styling
- assets/ — images used by the proposal
- docs/references/ — client-provided reference documents (e.g. the hardware spec), linked from the proposal
- docs/public/ — reserved for future public-facing proposal artifacts
- docs/private/ — internal research and working notes, not linked from the site (see `docs/private/README.md`)

Note: this is a public repository served in full by GitHub Pages, so
`docs/private/` is excluded from search indexing via `robots.txt` but is
still reachable by direct URL. It contains only placeholders and plain
reference links, not sensitive analysis — treat that as the actual
privacy boundary until there's a reason to move real findings to a
private repo.
