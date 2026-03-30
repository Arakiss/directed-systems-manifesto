# AGENTS.md

## Project Context

- This repository is an editorial artifact, not an application.
- The primary document is `GUIDE.md`.
- Supporting release metadata must stay aligned across `GUIDE.md`, `README.md`, and `CHANGELOG.md`.

## Release Discipline

- Treat the public release sequence as the source of truth.
- Before changing any version number, check `CHANGELOG.md` and recent git history to confirm what has actually been released or publicly prepared.
- Do not invent or skip versions because the change "feels large enough."
- If the current release line has not been shipped, new work stays under that version unless the developer explicitly decides to release it and open the next one.
- A later unreleased version must never appear in project files before the previous version has been intentionally released or explicitly superseded by the developer.

## Current Versioning Rule

- The January 2, 2026 public line is `0.1.0` / `0.1.1`.
- The current public March 2026 release is `0.2.0`.
- Do not write `0.3.0` anywhere in this repository unless the developer explicitly opens the next release line.

## Changelog and Metadata Sync

- `CHANGELOG.md` is the canonical release log.
- `GUIDE.md`, `README.md`, and any future release references must match the active unreleased or released version exactly.
- When substantial scope changes happen before release, merge them into the same unreleased entry instead of creating a fictional later version.

## Failure Prevention

- If there is any ambiguity about version state, preserve the current unreleased version and ask the developer before changing it.
- Version jumps without an explicit release decision are considered a project error.
