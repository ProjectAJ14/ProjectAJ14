# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a **GitHub profile README repository** (github.com/ProjectAJ14/ProjectAJ14). It renders as the owner's GitHub profile page. There is no application code, build system, or test suite.

## Structure

- `README.md` — The GitHub profile page content (Markdown with badges, stats, and embedded widgets)
- `charts/` — Static image assets (e.g., `bar_graph.png`) displayed in the profile
- `.github/workflows/workflow.yml` — GitHub Actions workflow that runs daily (6:30 PM UTC) to auto-update the blog post section from a Medium RSS feed using `gautamkrishnar/blog-post-workflow`

## Key Details

- The `<!-- BLOG-POST-LIST:START -->` / `<!-- BLOG-POST-LIST:END -->` markers in README.md are auto-populated by the workflow — do not manually edit content between them.
- The activity section is a manually maintained, self-reported routine. WakaTime is no longer used; do not add generated tracking markers or present estimates as measured activity.
- The owner is a full-stack engineer with 10+ years of experience, currently focused on React/TypeScript and Java/Spring Boot, with public NonStop io contributions and Flutter/Dart packages.
