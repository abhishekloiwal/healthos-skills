# HealthOS skill pack

HealthOS is a portable way for an AI agent to help one person organize health evidence, learn health concepts, answer questions, and turn decisions into measured actions.

Version **1.1.0** adds **46 optional deeper teaching units across 12 topics**. The original twelve-lesson foundation and its preventive stance remain the default. Use the [depth map](skills/healthos/references/depth/INDEX.md) for questions such as liver fat versus fibrosis, conflicting lab results, training differences, sleep, or emotional health. See the [change note](CHANGELOG.md) for the release scope.

It is intentionally just Markdown. There is no application to run, no database to adopt, and no required command-line tool. An agent can use the method in a durable workspace, a folder of notes, or a single chat. The agent chooses an implementation that fits its capabilities and must be honest about what it can persist.

## Install

With the open-source Skills CLI:

```sh
npx skills add abhishekloiwal/healthos-skills --skill healthos
```

To use it for one session without installing:

```sh
npx skills use abhishekloiwal/healthos-skills@healthos
```

No CLI is required. Point any capable agent at this repository and ask it to read [`skills/healthos/SKILL.md`](skills/healthos/SKILL.md). In a chat-only tool, upload or paste that file and only the referenced pages needed for the task.

The deeper units and their source registry live inside the installable skill, so a fresh download includes them. Existing installations need to refresh their skill files to receive the update. The lessons do not depend on a separate local corpus archive; private health records and learner progress stay outside the installed pack.

## What it gives an agent

- a storage-neutral operating model for a private personal health system;
- an append-and-supersede ledger method that preserves original evidence;
- guidance for ingesting labs, clinical documents, wearable exports, notes, and other sources;
- a prevention-priority review compatible with requests for an “LRA,” without inventing a risk score;
- a safe answer and action workflow;
- a teacher with explicit learner-state rules;
- an original, versioned HealthOS foundations course, source lenses, and quick-reference pages;
- optional source-linked depth units with checks and expected answers, selected by topic without losing the main course position;
- one semantic record model that can live in SQL, Markdown, platform memory, or chat;
- a clean way to add, prefer, fork, or replace guidance without silently rewriting history; and
- an optional agent persona that the user may adopt or ignore.

Personal records never belong in this public repository. Installed skill files are guidance, not a place to store a person's ledger.

## Start with a plain request

- “Set up a HealthOS for me.”
- “Ingest these three lab PDFs and preserve the exact evidence.”
- “What do you know about my cardiovascular health, and what is still unknown?”
- “Run my LRA and rank the prevention work that matters now.”
- “What can you teach me? Start with lipids.”
- “Go deeper on liver fat versus fibrosis, then resume my main course.”
- “Review this new podcast and add only what improves the curriculum.”
- “Turn this goal into a measured action plan.”
- “Use this source as my preferred lens, but keep the shipped course recoverable.”

## The three kinds of permanence

HealthOS does not call everything immutable:

- Source evidence and released course versions are immutable.
- The personal ledger evolves by adding records and superseding mistakes, never by silently erasing history.
- Generated summaries, dashboards, and current views are replaceable because they can be rebuilt from evidence.

Read [`skills/healthos/references/OPERATING_MODEL.md`](skills/healthos/references/OPERATING_MODEL.md) for the full distinction.

## Scope and safety

HealthOS is an evidence and decision-support method, not a medical device or a substitute for a qualified clinician. Current local clinical guidance controls diagnosis, treatment, screening eligibility, and urgency. An agent should surface uncertainty and seek timely professional or emergency help when the situation may be urgent.

This is an independent, original project. Its preventive approach includes clearly attributed synthesis of work by Peter Attia and Bryan Johnson, alongside public-health and clinical sources. Neither person nor their companies are affiliated with or endorse this project. Each teaching release identifies its sources and scope. Personal health records and original source documents or recordings are kept outside the pack.

## Repository map

- [`AGENTS.md`](AGENTS.md): entry point when an agent is given the whole repository.
- [`skills/healthos/SKILL.md`](skills/healthos/SKILL.md): installable skill and task router.
- [`skills/healthos/references/`](skills/healthos/references/): operating guidance.
- [`skills/healthos/references/PREVENTION_REVIEW.md`](skills/healthos/references/PREVENTION_REVIEW.md): the LRA-compatible prevention review.
- [`skills/healthos/references/corpus/`](skills/healthos/references/corpus/): the original frozen course, source lenses, and cheat sheets.
- [`skills/healthos/references/depth/INDEX.md`](skills/healthos/references/depth/INDEX.md): optional deeper units and their source registry.
- [`skills/healthos/references/SUPPLEMENTS_AND_UPDATES.md`](skills/healthos/references/SUPPLEMENTS_AND_UPDATES.md): review and distillation workflow for future additions.

## License

The original material in this repository is available under [CC BY 4.0](LICENSE.md). That license does not grant rights to anyone else's records, publications, courses, brands, or other source material.
