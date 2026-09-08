---
name: guided-cloud-lab-execution
description: Use when guiding safe, evidence-based cloud labs.
version: 1.0.0
license: MIT
---

# Guided Cloud Lab Execution

## Purpose

Guide AWS, Terraform, Linux, and similar infrastructure labs one meaningful step at a time. The goal is understanding plus verified state, not unexplained copy-paste.

## Lab contract

Every lab should define:

- objective and success condition;
- execution location and target environment;
- prerequisites and cost boundary;
- resources or files that may change;
- read-only checks and mutation steps;
- cleanup requirements;
- evidence expected at each gate.

## Workflow

1. **Preflight.** Confirm the working directory, tool versions, intended region or emulator, authentication status without printing identity values, and the expected resource scope.
2. **Plan dependencies.** Order steps so prerequisites exist before dependent resources.
3. **Explain the next action.** State the engineering problem, whether the action is read-only or mutating, and what success will look like.
4. **Let the learner act.** Give one small command or console action. Do not take over unless explicitly delegated.
5. **Read state back.** Use `describe`, `list`, `get`, Terraform state/plan, or an independent application check. A trailing success message is not evidence.
6. **Record limits.** Say what the check proves and what it does not prove.
7. **Recover carefully.** If a resource already exists, audit and read it back before reusing, updating, or removing it.
8. **Clean up.** Destroy lab resources and verify their absence or intended terminal state. Include versioned objects, logs, mappings, policies, and orphaned resources where relevant.
9. **Handoff.** Produce a public-safe README only from original work, with commands, architecture, verification, limitations, cost, and cleanup.

## Command hygiene

- Use fresh-shell-safe blocks that define their variables.
- Label local commands versus cloud commands.
- Validate shell, JSON, and Python syntax before remote mutation.
- Never use real secrets as placeholders.
- Never print credentials, private keys, full tokens, account identifiers, or unnecessary resource identifiers.
- Use explicit regions and narrow resource names.

## Terraform-specific rules

- Check `pwd` before diagnosing a missing file.
- Keep `.env`, state files, and provider credentials out of Git.
- Review the plan and resource count before apply.
- Verify with state and an independent provider read-back.
- Treat `destroy` and final state verification as part of completion.

## Completion test

The lab is complete only when the success condition is demonstrated, evidence is recorded, costs and permissions are understood, and cleanup has been independently verified.
