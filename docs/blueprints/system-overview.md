# System Overview — SoylentAquamarine GitHub Profile

## Purpose

The `SoylentAquamarine` repository is a GitHub profile README — a special repository that GitHub renders as the public-facing profile page at `github.com/SoylentAquamarine`. It serves as a project index and personal introduction for Stephen Pleasants, an ops professional who tinkers with code.

## Tech Stack

- **Single file**: `README.md`
- **Rendering**: GitHub's built-in Markdown renderer (CommonMark with GitHub extensions)
- **Deployment**: Automatic — GitHub renders the file on every push, no build step required
- **Dependencies**: None

## Content Structure

| Section | Contents |
|---|---|
| Header | Personal intro ("ops professional who tinkers with code") |
| Javascript Guitar | Link to repo + description + live site link |
| ClamBakeSanta | Link to repo + description + live site link + RSS link |
| Footer | "More projects on the way." |

## Project Listings (Current)

1. **Javascript Guitar** — Guitar fretboard visualizer, originally built in the 1990s. Live at GitHub Pages.
2. **ClamBakeSanta** — Daily haiku bot. Demonstrates plugin-based automation on 100% free infrastructure. Live site + RSS feed.

## Deployment

GitHub automatically detects a repository with the same name as the account username (`SoylentAquamarine/SoylentAquamarine`) and renders its `README.md` as the profile page. No CI/CD, no build system, no configuration required.

## Maintenance

- Add a new project entry when a new public repo launches.
- Keep live site links current — GitHub Pages URLs can change if repos are renamed.
- Update descriptions if project scope changes significantly.
- The projects table in the parent `CLAUDE.md` (`C:\Claude\git\CLAUDE.md`) should stay in sync with this file.
