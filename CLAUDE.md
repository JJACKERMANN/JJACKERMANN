# CLAUDE.md

This file provides guidance for AI assistants working in this repository.

## Repository Overview

**Repository:** `jjackermann/jjackermann`  
**Type:** GitHub Profile README repository

This is a special GitHub repository whose name matches the GitHub username. The `README.md` at the root of this repo is automatically rendered on the public GitHub profile page at `https://github.com/jjackermann`.

## Repository Structure

```
/
├── README.md       # GitHub profile page content (rendered publicly)
└── CLAUDE.md       # This file — AI assistant guidance
```

This is intentionally minimal. The primary artifact is `README.md`.

## Purpose

The sole purpose of this repository is to maintain the GitHub profile README. Content displayed here is public-facing and represents the owner's personal or professional brand on GitHub.

## Development Conventions

### README.md

- Written in GitHub Flavored Markdown (GFM)
- Rendered directly on the GitHub profile — no build step required
- Supports GitHub-specific Markdown features: badges, shields, HTML `<img>` tags, `<details>`/`<summary>` collapsibles, and GitHub Actions-generated SVGs
- Keep content concise and visually clean — profile pages are scanned quickly
- Test appearance by previewing Markdown locally or checking the live profile after pushing

### Branch Strategy

- `main` — production branch; merged content appears live on the GitHub profile immediately
- Feature branches should follow the pattern `claude/<description>` for AI-assisted changes

### Commit Style

- Use short, present-tense commit messages (e.g., `Update bio section`, `Add GitHub stats badge`)
- No ticket prefixes required for this repo

## Working with This Repo

### Making Changes

1. Edit `README.md` directly — no build process, no dependencies, no install step
2. Commit and push to trigger live update on the GitHub profile

### Viewing Changes

After pushing to `main`, visit `https://github.com/jjackermann` to see the rendered profile.

For preview before pushing, use any local Markdown renderer (VS Code preview, `grip`, etc.).

## AI Assistant Guidelines

- **Only modify `README.md` and `CLAUDE.md`** unless explicitly asked to add new files
- **Do not introduce tooling** (package managers, build systems, linters) unless the owner requests it
- **Keep the profile authentic** — avoid generic filler content; ask the owner for specifics (bio, projects, links) when creating or heavily editing the README
- **Respect existing tone and style** when making edits — match voice and formatting conventions already present
- When asked to "update the profile," always read the current `README.md` first before making changes
- Do not commit or push without being asked — changes to a profile README are immediately public
