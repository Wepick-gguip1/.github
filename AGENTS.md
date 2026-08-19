# W-Gain `.github` repository instructions

## Purpose

This repository is the public governance and community-default source for the W-Gain organization. Keep changes broadly applicable and avoid project-specific implementation details.

## Working rules

- Preserve the distinction between organization-wide defaults and repository-specific rules.
- Do not claim that this repository's `AGENTS.md` is inherited by other repositories.
- Use `W-Gain` for the organization name and `https://github.com/W-Gain` for links.
- Never add credentials, private hostnames, personal contact details, or deployment secrets.
- Keep public guidance concise, actionable, and suitable for both human and AI contributors.
- Do not change organization permissions, repository settings, secrets, or deployments as part of a documentation-only task.

## Validation

- Parse every changed YAML file before proposing a merge.
- Check Markdown links and verify that referenced repositories exist.
- Review the final diff for accidental private data and stale organization names.

## Code review rules

- Flag any policy change that lets an AI agent approve its own work, access production secrets, or bypass required checks.
- Flag templates that require labels, projects, or teams that are not guaranteed to exist in every repository.
- Require a clear migration note when changing a default that may affect existing repositories.
