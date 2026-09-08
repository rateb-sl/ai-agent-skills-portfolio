---
name: technical-documentation-and-visuals
description: Use when explaining systems clearly with text or diagrams.
version: 1.0.0
license: MIT
---

# Technical Documentation and Visuals

## Purpose

Make complex technical systems understandable through precise language, useful diagrams, and evidence-linked explanations.

## Documentation workflow

1. Identify the audience and the decision the document should support.
2. State the problem before describing the solution.
3. Introduce the smallest useful mental model.
4. Organize components by responsibility and dependency.
5. Show the implementation beside the design decision it realizes.
6. State assumptions, security boundaries, cost implications, and limitations.
7. Link claims to official or primary sources where accuracy matters.
8. Review the document as a new reader: can they understand the system without private context?

## Diagram rules

A useful architecture diagram should show:

- actors and trust boundaries;
- major components and their responsibilities;
- direction of important data or control flows;
- protocols or interfaces when relevant;
- failure, monitoring, and cleanup paths when they affect the design.

Do not decorate a diagram at the expense of meaning. Every visual element should explain a relationship, boundary, or decision.

## Clarity rules

- Prefer concrete nouns and active verbs.
- Define acronyms at first use.
- Keep one idea per paragraph or diagram group.
- Distinguish observed evidence from assumptions.
- Avoid invented metrics, output, or production claims.
- Use generic names and placeholders in public examples.

## Completion test

The artifact is ready when a technically literate reader can identify the problem, explain the design, follow the important flow, understand the evidence, and see the main risks without private conversation context.
