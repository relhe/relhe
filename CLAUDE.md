# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository purpose

This is a GitHub **profile README repository** (`relhe/relhe`). Its sole purpose is to render `README.md` on the owner's GitHub profile page (github.com/relhe). There is no application code, build system, test suite, or package manifest.

## Repository contents

- `README.md` — the profile page rendered on GitHub. Mixes raw HTML (centered `<p>` blocks, `<img>` tags) with Markdown headings/tables. GitHub renders both, but be aware the file is intentionally HTML-heavy for layout control.
- `assets/gh-readme-banner.png` — banner image asset (not currently referenced from README.md).
- `coverage/` — empty directory (artifact of an earlier setup; safe to ignore).

## Editing guidance

- Changes here are content edits, not code changes — there is nothing to build, lint, or test. Verify edits by previewing the rendered Markdown (e.g., GitHub's preview, or any Markdown viewer).
- External image URLs (devicons, vectorlogo.zone, github-readme-stats) are hot-linked. When adding skills/badges, follow the existing pattern: `<a href="..."><img src="..." width="40" height="40"/></a>` inside a centered `<p align="center">` block.
- The `github-readme-stats` block at the bottom uses the `buefy` theme with `hide_border=true`. Keep theme/options consistent across both stat cards if editing.
- Profile bio is in the first paragraph. Keep tone factual and current — recent commits show the bio is updated periodically (year refresh, role updates).
