---
name: second-brain-knowledge-organization
description: Use when building a second-brain knowledge system.
version: 1.0.0
author: Hermes Agent
license: MIT
platforms: [macos, linux, windows]
metadata:
  hermes:
    tags: [second-brain, knowledge-management, obsidian, markdown, organization]
    category: knowledge-management
    related_skills: [technical-study-note-production, secure-ai-agent-workflows]
---

# Second-Brain Knowledge Organization

## Purpose

Design and maintain a knowledge system that helps a person capture information, understand it, retrieve it later, and turn it into useful decisions or outputs. The method is tool-agnostic, with concrete examples for Obsidian and Markdown-based vaults.

This is an organization and operating-system skill. It does not replace a skill for writing an individual study note, operating Obsidian plugins, or migrating an entire vault.

## Core model

Use this flow:

```text
source → evidence → durable topic note → question, project, or output
```

A source is what was received. Evidence is what can be cited or observed. A durable topic note explains the idea in the user's own structure. Questions, projects, and outputs are applications of that knowledge.

Do not treat a collection of files as a second brain merely because it is large. A useful system makes important knowledge findable, connected, current, and actionable.

## Design principles

- Organize primarily by lifecycle and retrieval purpose, not by an ever-growing list of subjects.
- Keep raw captures separate from synthesized knowledge.
- Prefer one canonical home for each note or concept.
- Search before creating a folder, note, tag, or dashboard.
- Use links to express relationships; use folders to express broad operational boundaries.
- Keep the visible workspace small and place low-frequency support material in a collapsed system area when the tool allows it.
- Capture enough context that a future reader can understand why the note exists.
- Record uncertainty, provenance, and evidence boundaries instead of presenting every statement as equally certain.
- Improve the system incrementally. Do not reorganize the entire history without a verified destination and link plan.

## Suggested lifecycle areas

Adapt the names to the host system rather than copying them mechanically:

- **Inbox:** unprocessed captures and quick thoughts.
- **Sources:** transcripts, articles, books, imports, and other original material.
- **Learning or Knowledge:** synthesized, durable concepts and study notes.
- **Questions:** unresolved ideas, decisions, and thinking prompts.
- **Projects:** work with a defined outcome and active next actions.
- **Writing or Outputs:** drafts and finished work derived from notes.
- **Dashboards:** indexes, maps, navigation, and operational views.
- **Archive:** inactive material retained for reference.

A small vault may combine some areas. A larger vault may put dashboards, inboxes, sources, and archive under one support wrapper so the main sidebar shows only active work.

## Note types

### Source note

Preserve provenance, capture date, source location, and coverage boundaries. Summarize or quote only within the source's permissions. Do not confuse a transcript with understanding.

### Durable topic note

Explain one coherent idea. Include a short summary, the mental model, important relationships, practical implications, source links, uncertainty, and a next question or application when useful.

### Project note

State the outcome, constraints, decisions, current status, next action, dependencies, and evidence. Link to the relevant topic and source notes instead of duplicating their content.

### Question note

State the question precisely, why it matters, current hypotheses, evidence, and what would resolve it. Do not force an answer merely to make the note appear complete.

### Dashboard or map

Provide navigation and status. A dashboard is an index, not the canonical home of every piece of content. Keep links and paths accurate after moves.

## Naming rules

Use a stable naming standard and apply it when creating new material:

- Put the clear title first; put a date last.
- Use `Title - YYYY-MM-DD.md` for time-bound notes.
- Use `Title.md` without a date for evergreen concepts, dashboards, templates, and maps.
- Use a numbered prefix only when sequence matters, such as course modules: `Module 4-2. Topic - YYYY-MM-DD.md`.
- Keep dates in a parent date path when the container already expresses the date; do not repeat the date in the package name.
- Use descriptive folder names that communicate lifecycle or purpose.
- Do not use `Final`, `New`, `V2`, `Copy`, or `Misc` as organizational shortcuts.
- If the destination is unclear, place the item in the inbox rather than inventing a permanent structure.

The exact emoji, language, and top-level labels are local conventions. Consistency and retrievability matter more than a universal folder taxonomy.

## Processing workflow

1. **Capture.** Put new material in the inbox or source area with enough provenance to find the origin again.
2. **Classify.** Decide whether it is a source, durable concept, question, project, or output. Do not create a new type for every exception.
3. **Search.** Look for an existing canonical note, folder, or related concept before creating anything.
4. **Extract.** Record the useful idea, decision, observation, or evidence rather than preserving an unprocessed information dump.
5. **Connect.** Add links to the source, related topics, active projects, and resulting outputs where those relationships are real.
6. **Apply.** Turn important knowledge into an experiment, decision, checklist, project action, or draft.
7. **Review.** Periodically inspect orphaned inbox items, stale dashboards, broken links, duplicate concepts, and notes that no longer represent current understanding.

## Safe restructuring

Before moving or renaming notes or folders:

1. Identify the exact scope and intended destination.
2. Search for wiki links, Markdown links, frontmatter references, dashboard targets, plugin paths, and literal path references.
3. Check destination collisions and ambiguous duplicates.
4. Rewrite references before the move when the tool does not update them automatically.
5. Move one verified unit at a time for high-risk restructures.
6. Read back representative notes and confirm the old path has no remaining references.
7. Do not delete uncertain material; move it to a clearly named review or archive area.

A filesystem move is not complete until navigation and references still resolve.

## AI-agent and Hermes boundary

Use the knowledge system as context, not as an excuse to duplicate private state everywhere.

### Put in a reusable skill

- generic folder and note-type principles;
- naming rules;
- search-before-create behavior;
- safe move and link-rewrite procedures;
- evidence and provenance expectations;
- tool compatibility and limitations.

### Keep in private memory or local configuration

- the user's actual vault path;
- personal folder names and dashboards;
- current projects, preferences, and unfinished work;
- private source material and personal relationships;
- credentials, tokens, cookies, account identifiers, and plugin secrets.

A skill may say “use the configured vault” or “follow the user's naming standard.” It should not publish a person's real path or private vault contents. Memory should contain compact, stable preferences that apply across sessions; task-specific notes belong in the vault or session record.

When an agent works in a vault, it should read the local operating instructions and canonical naming standard first, search before creating, preserve literal names, and report exactly what was changed. It should never infer that a note is complete merely because a file exists.

## Quality and privacy gates

Before considering the system healthy, verify:

- each important note has a clear role and canonical location;
- source provenance is preserved;
- durable notes contain synthesis rather than only copied material;
- names follow the local standard;
- dashboards and links resolve;
- duplicate folders have not been created accidentally;
- private paths, credentials, personal data, and restricted source material are not exposed;
- restructuring has a rollback or recovery path.

For public sharing, create a generic derivative. Exclude the private vault, personal memory, session history, private automation, and account-specific configuration. Replace environment values with placeholders and scan the complete export and Git history.

## Example

A new course transcript could become:

```text
Inbox/                 temporary capture
Sources/               original transcript and course link
Learning/Networking/   durable note: DNS resolution model
Questions/             unresolved question about caching behavior
Projects/              lab that tests the model
Writing/               public explanation derived from the note
```

The transcript remains the source. The durable note carries the understanding. The project supplies evidence, and the writing output is a derived artifact rather than a second copy of the transcript.

## Completion test

A second-brain system is ready for daily use when a new capture has an obvious temporary home, an existing concept can be found before duplication, important notes show provenance and relationships, active work is visible, and an agent can operate without exposing or confusing private state with reusable instructions.
