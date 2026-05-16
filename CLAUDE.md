# CLAUDE.md

GitHub profile README repository for `tarcisiopgs`.

## Repository Purpose

This repository powers the public GitHub profile page. The primary artifact is
`README.md`.

## Project Structure

```text
.
└── README.md
```

## Editing Guidelines

- Keep the README concise and profile-oriented.
- Preserve useful badges and public contact links unless the user asks to
  change them.
- Avoid adding generated assets, package manager files, or build tooling unless
  the repository gains a real build step.
- Prefer direct Markdown edits over introducing templates or scripts.

## Validation

There is no automated test suite or build command in this repository.

After changing `README.md`:

- Review Markdown rendering mentally for headings, tables, badges, and links.
- Run `git diff --check` to catch whitespace issues before committing.
