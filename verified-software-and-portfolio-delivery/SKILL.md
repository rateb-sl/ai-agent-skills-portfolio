---
name: verified-software-and-portfolio-delivery
description: Use when moving technical work from plan to proof.
version: 1.0.0
license: MIT
---

# Verified Software and Portfolio Delivery

## Purpose

Move a technical idea from a bounded plan to a tested, documented, reviewable, and—when appropriate—public artifact.

## Workflow

1. **Define the artifact.** State the problem, audience, acceptance criteria, non-goals, and risk boundary.
2. **Inspect before changing.** Confirm repository, branch, existing conventions, and relevant dependencies.
3. **Implement narrowly.** Keep the change focused and preserve a clear diff.
4. **Test proportionally.** Run syntax checks, unit tests, integration checks, security scans, and manual verification appropriate to the artifact.
5. **Document honestly.** Explain what works, how it was tested, limitations, costs, and cleanup.
6. **Review for public safety.** Remove secrets, personal data, private URLs, copied material, generated noise, and environment-specific identifiers.
7. **Publish deliberately.** Use the intended visibility, license, and attribution. Do not publish unfinished or unverified work.
8. **Read back remotely.** Confirm the repository visibility, expected files, commit, README links, and CI status after publication.

## Portfolio quality gate

A public artifact should:

- demonstrate an understandable problem and solution;
- contain original or properly licensed work;
- be reproducible within stated prerequisites;
- include verification and failure boundaries;
- avoid secrets, personal data, private infrastructure, and unsupported claims;
- make cleanup and cost implications visible.

## GitHub hygiene

- Use a real `.gitignore` for secrets, state, keys, logs, and local files.
- Enable secret scanning, push protection, Dependabot, and CI checks where available.
- Scan the complete Git history before public release.
- Never bypass a security alert without understanding and documenting it.
- Use short-lived, least-privilege credentials outside the repository.

## Completion test

Delivery is complete only when local checks pass, the public tree is sanitized, remote files and visibility are verified, and the README accurately describes the result.
