# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

This is a **GitHub special profile repository**. The repo name (`mkzer`) matches the
owner's GitHub username (`mkzer/mkzer`), which means `README.md` is rendered directly on
the owner's GitHub profile page at https://github.com/mkzer.

The repository contains **only `README.md`** — there is no application code, build system,
package manager, test suite, or CI. The README *is* the deliverable. "Working in this
repository" almost always means editing the profile content in `README.md`.

Because there is nothing to build or run, there are no build/lint/test commands. Validate
changes by previewing the rendered Markdown (GitHub-flavored), not by running tooling.

## README conventions to preserve

The profile follows a consistent structure — keep it intact when editing:

- **Header**: name + one-line title (Embedded & IoT engineer), then a few status lines
  (degree, current internship, availability) prefixed with emoji.
- **Shields.io badges**: tech badges use `style=flat` with `logo=<brand>` and matching
  brand hex colors. Contact badges at the bottom link to LinkedIn/GitHub/Email. Match this
  exact format when adding badges.
- **Sections** in order, separated by `---` horizontal rules: About → Experience →
  Featured Projects → Tech Stack → Contact. Section headers use an emoji + title
  (e.g. `## 🔧 About`).
- **Projects** are numbered, each with a one-line description and a bold `**Stack:**` line.
- **Content is concrete**: prefer specific, verifiable facts (device counts, grid sizes,
  setup times, named technologies) over vague claims.

## Editing guidance

- This is a real person's public-facing profile. Treat factual details (employer, dates,
  availability, contact links, project specifics) as authoritative — do not invent,
  embellish, or alter biographical/professional facts. When the user asks for content
  changes, apply exactly what they specify and ask if a detail is unclear.
- Keep the bilingual flavor as-is (mostly English with French institution/place names).
- After editing, commit and push to the working branch per the session's git instructions.
  Changes pushed to the default branch immediately update the live GitHub profile.
