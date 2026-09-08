# Guided Cloud Lab Execution

## What this skill does

This skill guides AWS, Terraform, Linux, and similar infrastructure labs one meaningful step at a time. It combines active learning with safe execution, state read-back, troubleshooting, and cleanup.

## Why it is valuable

Cloud labs can create costs, permissions, public exposure, and orphaned resources. A successful command or console screen is not enough to prove that the intended system works. This workflow makes the full engineering boundary visible.

It helps the learner:

- understand what each action changes before running it;
- distinguish local commands from cloud-side mutations;
- verify actual state instead of trusting success messages;
- recover from partial runs and existing resources;
- clean up resources and confirm the final state;
- produce an honest, public-safe lab handoff.

## Typical result

A completed lab has a defined success condition, recorded evidence, known limitations, a cost and security boundary, and verified cleanup.

See [`SKILL.md`](SKILL.md) for the workflow and boundaries.
