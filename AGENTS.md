# Agent Guide

## Mission

Maintain Helix organization-level GitHub defaults with public-facing clarity and
security discipline.

## Read This First

1. Read `README.md`.
2. Read `SECURITY.md` before changing vulnerability reporting language.
3. Check `git status --short --branch`.

## Repository Boundaries

This repository owns the public organization profile, organization-level
security policy, and shared GitHub governance defaults.

It does not own product code, repo-local architecture, private incident
runbooks, secrets, credentials, or implementation guidance that belongs in
another repository.

## Expected Inputs And Outputs

Inputs are governance decisions and public organization copy. Outputs are
public GitHub profile and security documents that can be read by unauthenticated
visitors.

## Local Commands

No repo-local commands exist yet.

## Verification

Inspect the final diff and run:

```sh
git diff --check
```

For public copy, verify that it does not expose private architecture, internal
processes, credentials, or unreviewed legal commitments.

## Secrets And Sensitive Data

Never commit secrets, credentials, private keys, customer data, sensitive logs,
or private incident details. Keep security contact language public and
operationally accurate.

## Cross-Repo Work

Use `commons` for broad cross-repo operating guidance. Use repo-local
`AGENTS.md` files for instructions that apply only to a single repository.

## Commit Policy

Use Conventional Commits. Commit only at a meaningful milestone and do not push
unless explicitly asked.

## When To Update This File

Update this file when organization-level GitHub governance, public security
handling, or default health-file ownership changes.
