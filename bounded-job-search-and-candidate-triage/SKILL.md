---
name: bounded-job-search-and-candidate-triage
description: Use when researching and triaging job opportunities safely.
version: 1.0.0
license: MIT
---

# Bounded Job Search and Candidate Triage

## Purpose

Run a focused, evidence-based job search across multiple boards without turning the process into an endless browsing session or an unsafe application automation system.

This is a **research and triage workflow**. It does not submit applications, message recruiters, handle credentials, or make decisions on behalf of the candidate.

## Why it is valuable

Job boards produce duplicated, stale, incomplete, and sometimes misleading listings. A bounded process helps a candidate spend time on roles that are recent, feasible, relevant, and supported by visible evidence.

It helps with:

- focused searches across several job boards;
- deduplication across sources;
- explicit hard-gate rejection;
- honest skills-fit bands;
- evidence-based ranking;
- clear separation between research and application;
- safe handoff to the candidate for final review.

## Inputs

Use only the minimum information needed for the search:

- target locations and work model;
- role families and priority order;
- must-have exclusions;
- experience and skills the candidate can truthfully support;
- salary, language, authorization, mobility, or schedule boundaries;
- optional list of already-submitted job URLs supplied by the candidate.

Do not request passwords, cookies, private tracker files, application portals, or personal documents merely to research listings.

## Bounded search contract

Set a finite budget before searching. A safe default is:

- up to 8 distinct queries across enabled sources;
- up to 30 unique listings inspected;
- no repeated query that produces no new evidence;
- prioritize listings posted within the last 14 days;
- stop when the budget is reached or the source stops producing trustworthy evidence.

If a source requires login, 2FA, or a CAPTCHA, ask the user to complete it manually. Never guess credentials or bypass the restriction.

## Workflow

1. **Define the search lane.** Set role families, geography, work model, freshness window, and hard exclusions.
2. **Build a query matrix.** Start with the highest-priority role family, then use a small number of approved adjacent searches.
3. **Collect visible evidence.** Capture exact title, company, location, work model, posting age, salary when visible, language, mobility requirements, description, source, and direct URL.
4. **Check prior submissions.** Exclude only roles the candidate explicitly identifies as submitted. Treat drafts or saved documents as unsubmitted unless the candidate confirms otherwise.
5. **Deduplicate.** Match by canonical URL first, then normalized company and role identity.
6. **Apply hard gates.** Reject clearly infeasible geography, authorization, language, mobility, compensation, stale/closed status, or materially incompatible scope.
7. **Assign a fit band.** Use `Strong`, `Good`, or `Potential/Stretch`. State approximate evidence coverage and missing requirements; do not present a stretch role as ready to apply.
8. **Assign an evidence lane.** Use `Verified live listing`, `Needs live verification`, or `Source evidence incomplete`.
9. **Return a shortlist.** Separate recommended, review, stretch, and rejected roles. Include the reason and next manual verification step for each retained role.
10. **Hand off safely.** Let the candidate decide whether to tailor documents or apply. Never submit, send outreach, or mutate an application tracker automatically.

## Evidence record

Each retained listing should contain:

- queue: `Recommended`, `Review`, or `Potential/Stretch`;
- exact title and company;
- direct listing URL;
- location and work model;
- posting age or an explicit unknown label;
- source board;
- fit band and concrete matching evidence;
- missing requirements or risks;
- live-status label;
- next verification step.

A search result snippet, aggregator preview, or stale cached page is not proof that a listing is active.

## Safety boundaries

- Never submit applications automatically.
- Never send messages or outreach automatically.
- Never fabricate experience, qualifications, salary, authorization, or work history.
- Never store credentials, cookies, personal documents, or private tracker exports in the skill.
- Do not create candidate documents from a listing alone; use candidate-approved source material.
- Keep personal data local and minimize what is shared with an AI tool.

## Completion test

A search is complete when the finite budget is respected, sources and blockers are reported, duplicates are removed, hard gates are applied, every retained role has visible evidence and a caveat, and the candidate—not the automation—controls the application decision.
