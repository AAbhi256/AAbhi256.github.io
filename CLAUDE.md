# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

Personal GitHub Pages site for Abhinav Angirekula. A minimal Jekyll site with no external themes, no plugins, and no build tooling beyond what GitHub Pages provides automatically.

## Development

To preview locally (requires Jekyll):
```
jekyll serve
```

Otherwise, push to `main` and GitHub Pages builds and deploys automatically.

## Architecture

**Single layout:** `_layouts/default.html` is the only template. All pages use `layout: default` in their front matter. All styling is inline CSS within this file — there are no separate stylesheets.

**Content pages** (root-level `.md` files):
- `index.md` — About/home page with CV PDF embed
- `ml.md` — Machine Learning writeups
- `qc.md` — Quantum Computing writeups
- `xr.md` — Game Dev/XR content

**Config:** `_config.yml` sets `permalink: pretty` (URLs without `.html` extensions) and basic site metadata.

## Style conventions

- All CSS lives inline in `_layouts/default.html`; keep it that way
- No external themes, frameworks, or stylesheets — intentionally custom
- `color-scheme: light` is forced; avoid dark mode divergence
