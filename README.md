# AI-Agent Skills Portfolio

Reusable, public-safe Markdown skills and workflows for Hermes, Claude, GPT-based agents, and other compatible AI-agent tools. The methods are tool-agnostic unless a section explicitly identifies a platform-specific integration.

This portfolio is organized around capabilities rather than isolated recipes. Each umbrella skill combines related methods so users get one coherent workflow instead of a collection of overlapping instructions.

## Portfolio overview

| Skill | Main benefit | Best for |
|---|---|---|
| [Cloud Engineering Learning Mentor](cloud-engineering-learning-mentor/) | Turns passive study into explainable understanding and practical proof | Cloud learners and mentors |
| [Guided Cloud Lab Execution](guided-cloud-lab-execution/) | Makes infrastructure practice safer, more deliberate, and verifiable | AWS, Terraform, and Linux learners |
| [Technical Study Note Production](technical-study-note-production/) | Converts lessons and experiments into durable knowledge | Students, engineers, and educators |
| [Second-Brain Knowledge Organization](second-brain-knowledge-organization/) | Organizes sources, understanding, projects, and outputs into a retrievable system | Obsidian users, knowledge workers, and AI-agent users |
| [Technical Documentation and Visuals](technical-documentation-and-visuals/) | Makes systems easier to understand, review, and operate | Technical writers and engineers |
| [Verified Software and Portfolio Delivery](verified-software-and-portfolio-delivery/) | Turns work into credible, tested, public evidence | Developers and job seekers |
| [Secure AI-Agent Workflows for Hermes and Other Agent Tools](secure-ai-agent-workflows/) | Adds structure, security, and verification to agent-assisted work | AI users, developers, and platform teams |
| [Bounded Job Search and Candidate Triage](bounded-job-search-and-candidate-triage/) | Turns job-board browsing into a focused, evidence-based shortlist | Job seekers, mentors, and career tools |

## Why these skills belong together

The portfolio describes a complete technical growth loop:

```text
Learn a concept
    ↓
Practice it in a controlled lab
    ↓
Explain and document what happened
    ↓
Verify the artifact and publish it safely
    ↓
Use automation without exposing sensitive information
```

## Detailed benefits

### Cloud Engineering Learning Mentor

This skill helps a learner understand where a topic fits, build the right mental model, and connect theory to a small proof. Its main benefit is reducing passive course consumption: the learner must explain, test, and apply the concept. It is useful for AWS, Linux, networking, Python automation, Terraform, troubleshooting, and entry-level cloud interview preparation.

### Guided Cloud Lab Execution

This skill turns a lab into an evidence-driven engineering exercise. It makes prerequisites, side effects, verification, cost, and cleanup visible before anything is changed. The benefit is learning how to operate infrastructure responsibly rather than merely copying commands that happen to work once.

### Technical Study Note Production

This skill creates notes that remain useful after the lesson ends. It separates source material from original synthesis, records evidence boundaries, and organizes concepts, implementation details, failures, and recall questions. The benefit is a searchable technical knowledge base that supports future work instead of a transcript archive.

### Second-Brain Knowledge Organization

This skill helps a person design and maintain a second brain that moves from source material to evidence, durable understanding, questions, projects, and useful outputs. It covers lifecycle-based organization, note types, naming, safe restructuring, and the boundary between reusable agent instructions, private memory, and personal vault data.

### Technical Documentation and Visuals

This skill helps explain a system to someone who was not present during its creation. It combines precise writing with diagrams that show components, trust boundaries, dependencies, and flows. The benefit is better handoffs, design reviews, troubleshooting, onboarding, and technical communication.

### Verified Software and Portfolio Delivery

This skill provides a path from idea to public proof: define the artifact, inspect the repository, implement narrowly, test, scan, document, and verify the remote result. The benefit is a portfolio that demonstrates real engineering judgment instead of a collection of unverified code samples.

### Secure AI-Agent Workflows

This skill treats security and verification as part of agent design. It covers reusable skill architecture, tool boundaries, untrusted outputs, least-privilege credentials, public-safe exports, and leak response. The benefit is using AI automation productively without treating convenience as permission to expose secrets or make unreviewed changes.

### Bounded Job Search and Candidate Triage

This skill turns multi-board job searching into a finite research workflow. It deduplicates listings, applies explicit feasibility gates, separates strong matches from stretch roles, and records the evidence behind each recommendation. The benefit is a shortlist that is more honest and actionable, while keeping applications, credentials, documents, and outreach under the candidate's control.

## Tool compatibility

The cloud, lab, study, documentation, and delivery workflows are tool-agnostic: they can be adapted to normal engineering work, ChatGPT, Claude, Gemini, local agents, Hermes, or no AI tool at all. The secure agent-workflow skill uses a generic method but is written with Hermes-style skills and other skill-based agent tools in mind.

## How to use the portfolio

1. Start with the umbrella closest to your goal.
2. Read its purpose, scope, workflow, and completion test.
3. Adapt examples to your environment with placeholders replaced locally.
4. Add provider-specific references only when the general method is clear.
5. Verify results and record limitations instead of claiming more than the evidence supports.

## Design principles

- Prefer one reusable umbrella over many overlapping recipes.
- Teach the reason for an action, then verify the result.
- Treat cleanup, provenance, and security as part of done.
- Use placeholders and generic examples in public material.
- Do not treat a successful command as proof without reading state back.

## Public-safety statement

This repository is a deliberately sanitized public edition. It contains no private Hermes profile, session history, memory, vault path, cloud account identifier, credential, personal contact data, or private automation configuration. Examples use placeholders such as `YOUR_ACCOUNT_ID` and `/path/to/project`.

The skills are educational workflows, not a guarantee of security or correctness for every environment. Review commands, costs, permissions, and provider documentation before running them.

## Provenance

These documents are a curated public portfolio derived from personal learning and workflow development. They are rewritten for generic use rather than copied from a private runtime. Any third-party concepts or tooling remain subject to their original licenses and documentation.

## License

The original prose in this repository is released under the MIT License. See [LICENSE](LICENSE). Referenced tools, names, and documentation remain owned by their respective authors.
