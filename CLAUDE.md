# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a GitHub Pages site for `arun4by4.github.io`, using the [Jekyll Cayman theme](https://github.com/pages-themes/cayman). Content is authored in Markdown and automatically built by GitHub Pages on every push to `main`.

## Site Configuration

- **Theme:** `jekyll-theme-cayman` (set in `_config.yml`)
- **Entry point:** `index.md` — the main page content
- **Build:** Handled automatically by GitHub Pages (no local build step required)

## Local Development

To preview locally with Jekyll:

```bash
gem install bundler jekyll
jekyll serve
```

Then open `http://localhost:4000`.

## Deployment

Push to `main` — GitHub Pages rebuilds the site automatically. No CI/CD configuration needed.
