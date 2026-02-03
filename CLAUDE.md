# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a **GitHub Pages static site** serving as a personal landing page at `xt3362.com`. It is a pure HTML/CSS site with no build system, no dependencies, and no framework.

## Key Details

- **No build step** — edit HTML/CSS directly; changes deploy automatically via GitHub Pages on push to `main`
- **Jekyll is disabled** via `.nojekyll` file — do not add Jekyll-specific files
- **Custom domain** configured in `CNAME` (`xt3362.com`)
- **Language**: Japanese (`lang="ja"`)

## Architecture

- `index.html` — Self-contained landing page (inline CSS, no external stylesheets or JS)
- `robots.txt` / `sitemap.xml` — SEO configuration referencing `xt3362.com`
- `CNAME` — GitHub Pages custom domain config
- `.nojekyll` — Disables Jekyll processing
- `public/` — Currently empty directory

The site links to a sub-project at `https://xt3362.com/pub.my-chords/` which is referenced in the sitemap but hosted separately.

## Development

No install or build commands needed. Open `index.html` in a browser to preview. Deploy by pushing to `main`.
