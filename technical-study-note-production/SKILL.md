---
name: technical-study-note-production
description: Use when turning technical work into durable notes.
version: 1.2.0
license: MIT
---

# Technical Study Note Production

## Purpose

Turn a course lesson, lab, transcript, experiment, or documentation set into a self-contained technical note that can replace re-consuming the original material.

## Source boundary

Separate original synthesis from source material. Do not republish course slides, proprietary transcripts, private meeting content, copied answer keys, or material whose license does not permit redistribution. Link to sources instead.

## Workflow

1. **Inventory sources.** Record titles, dates, URLs, files, and coverage boundaries. Name the sections or media actually inspected and identify material that was not available or reviewed; do not claim full-source coverage from an excerpt.
2. **Extract the outcome.** Identify what was built, understood, tested, or decided.
3. **Build the mental model.** Explain components, relationships, dependencies, and why the design works.
4. **Preserve operational detail.** Include commands, configuration, expected evidence, failure modes, and cleanup when they are original and shareable. For an executed lab, keep the causal path in order and explain why each major action exists, what it changes, how to read it back, and what the evidence cannot prove.
5. **Separate certainty levels.** Distinguish observed results, source-backed facts, learner interpretation, and open questions. Verify version-sensitive or operational claims against an appropriate primary source.
6. **Add retrieval structure.** Use navigation, summary, detailed explanation, key terms, verification, and recall questions.
7. **Audit the note.** Check factual claims, citations, links, anchors, embeds, placeholders, privacy, attribution, and whether a reader can use it without the original chat.

## Recommended note shape

- Title and scope
- Summary
- System or concept model
- Detailed explanation
- Commands or implementation notes
- Verification and evidence limits
- Failure modes and recovery
- Security and cost boundaries
- Sources and attribution
- Recall questions or next experiment

## Public-sharing gate

Before publishing, remove:

- personal names and contact details;
- private paths, vault links, meeting links, and account identifiers;
- credentials, tokens, cookies, keys, and raw environment files;
- participant details and copyrighted course material;
- unverified claims and invented output.

Replace environment-specific values with clear placeholders and state what must be substituted.

## AI and provenance gate

- Treat AI-generated summaries, citations, quotations, commands, and test results as unverified until checked against the source or live evidence.
- Preserve the distinction between what the source says, what was observed, and what the author inferred. Never invent a citation, quote, output, or completion state.
- Do not upload private course portals, paid materials, personal notes, or confidential work content to a model unless the owner and terms explicitly allow it.

## Completion test

A note is ready when it is accurate, source-aware, self-contained, reproducible within its stated limits, and safe for a public reader.
