# Secure AI-Agent Workflows for Hermes and Other Agent Tools

## Compatibility

The security principles are tool-agnostic and apply to Hermes, Claude, GPT-based agents, Gemini, local agents, MCP-enabled tools, and other systems that use prompts, tools, or reusable workflows. The included `SKILL.md` format is especially suitable for Hermes and other skill-based agent systems, but it is not limited to Hermes.

## What this skill does

This skill designs AI-agent workflows that are reusable, inspectable, security-conscious, and verified. It covers skill authoring, delegated work, tool integrations, untrusted outputs, credential boundaries, and public-safe exports.

## Why it is valuable

Agent automation can accelerate work, but it can also amplify mistakes. A reusable workflow needs clear scope, least-privilege access, human approval for sensitive actions, and independent verification.

It helps teams:

- avoid creating many overlapping agent instructions;
- separate generic methods from private user state;
- treat fetched pages and tool output as untrusted data;
- keep credentials out of chat, repositories, and memory;
- design safe recovery when a leak may have occurred;
- publish useful workflows without publishing the private environment they came from.

## Typical result

An agent workflow has clear inputs, outputs, boundaries, verification steps, attribution, and a public-safe export that can be tested with synthetic values.

See [`SKILL.md`](SKILL.md) for the workflow and credential rules.
