# GitHub Organization Defaults

Organization-level GitHub profile, security policy, and shared governance files.

## Overview

This repository defines the public-facing GitHub profile and shared default
health files for the Helix organization. It provides organization-level
governance that should not be duplicated across individual repositories.

## Status

Bootstrap.

## Scope

- Public organization profile content.
- Organization-level security reporting guidance.
- Shared GitHub governance files.
- Default community health files that apply when repos do not override them.

## Non-Goals

- Product implementation code.
- Repo-local architecture or operating instructions.
- Private runbooks, incident processes, or credentials.
- Documentation that belongs in `commons` or a product repository.

## Repository Layout

- `README.md` - repository orientation.
- `profile/README.md` - public GitHub organization profile.
- `SECURITY.md` - public vulnerability disclosure policy.
- `.github/CODEOWNERS` - repository ownership rules.
- `.gitignore` - local file exclusions.

## Getting Started

Read `SECURITY.md` before changing public security language. Keep public copy
clear, conservative, and appropriate for unauthenticated visitors.

## Verification

No repo-local automation exists yet. Before claiming changes are ready, inspect
the diff and run:

```sh
git diff --check
```

## Related Repositories

- `commons` - cross-repo operating guide and architecture context.
