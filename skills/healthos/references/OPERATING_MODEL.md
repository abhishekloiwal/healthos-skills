# Operating model

Use this page when establishing or explaining a HealthOS workspace.

## One system, six distinct layers

HealthOS keeps six kinds of information connected without collapsing them:

1. **Evidence vault:** original lab reports, clinical notes, images, exports, questionnaires, messages, and user statements.
2. **Personal ledger:** dated facts and events extracted from evidence, including corrections and provenance.
3. **Guidance library:** the frozen foundation course, current clinical guidance, and user-added sources or expert lenses.
4. **Derived views:** summaries, timelines, trend tables, dashboards, risk discussions, and other rebuildable interpretations.
5. **Action register:** proposed, adopted, paused, completed, or abandoned interventions and their review measures.
6. **Learner state:** what was offered, presented, acknowledged, practiced, assessed, or mastered.

Keeping these layers separate prevents a summary from becoming a fact, a lesson from becoming medical advice, or a suggestion from becoming an intervention the user supposedly follows.

## What “immutable” means

| Information | Lifecycle |
| --- | --- |
| Original evidence | Preserve as received. Add a corrected or newer source beside it. |
| Ledger history | Append events. A correction points to and supersedes the old event; both remain traceable. |
| Released course version | Freeze it. Improvements become an overlay, fork, or newly named release. |
| Current summary or dashboard | Replaceable. Rebuild it from evidence and the ledger. |
| Proposed action | Editable until adopted. Preserve material decisions after adoption. |
| Learner state | Append events; do not rewrite “presented” into “mastered.” |

Immutability protects provenance, not mistakes. A false record should be visibly superseded, not preserved as the current truth and not erased as if it never existed.

## Information labels

An agent should make these classes visible whenever confusion is possible:

- **Recorded evidence:** directly present in a named source or explicitly stated by the user.
- **External guidance:** a recommendation or teaching from a cited source, with jurisdiction and date when relevant.
- **Derived interpretation:** an inference, calculation, synthesis, or hypothesis produced from evidence and guidance.
- **Action state:** what was suggested versus what the user actually adopted.
- **Learner state:** exposure and understanding, never a proxy for health status.

Markdown headings, tags, separate notes, tables, or native database fields are all acceptable. The separation matters more than the storage format.

## Capability-aware setup

### Durable workspace

Use the host's native storage. A practical arrangement may have locations for sources, ledger records, guidance, views, actions, and learning, but do not force a layout if the workspace already has conventions. Keep skill installation files separate from personal data so updates cannot overwrite records.

### File-only workspace

Use ordinary Markdown and retain stable links or locators back to source files. One ledger file may work for a small record; multiple topic or year files may work better as it grows. Preserve an index that tells the next agent where truth lives.

### Chat-only session

Do not refuse solely because files or tools are absent. Work from the evidence available in the conversation, explicitly say that persistence is not guaranteed, and offer a portable Markdown block containing the source register, records, unknowns, action state, and next steps.

## One semantic model, many stores

Keep the same relationships whether the host uses SQL, Markdown, a note app, platform memory, or only the current chat:

| Concept | What must remain connected |
| --- | --- |
| Person | The owner of each private record and any identity uncertainty |
| Source | Original item, provenance, time, locator, access boundary, and correction chain |
| Observation or event | Person, time, exact reported fact, source, context, status, and supersession |
| Guidance claim | Source, author, date, population, jurisdiction, claim class, and exact scope |
| Assessment | Dated inputs, method or lens, uncertainty, conclusion, and prior version |
| Action | Proposal, decision owner, adoption state, measures, review point, and outcome |
| Course scope | Release, stable scope ID, source links, and content version |
| Learner event | Person, scope, time, event type, evidence of completion, and prior state |

The essential links are `person -> record`, `record -> source`, `correction -> superseded record`, `assessment -> input records`, `action -> rationale and measures`, and `learner event -> course scope`. Generated current views point back to these records.

### If a relational database is available

A sensible implementation has separate tables or equivalent types for people, sources, observations/events, guidance releases and claims, assessment versions, actions, course scopes, and learner events. Use stable IDs, source foreign keys, event time plus recorded time, lifecycle status, and explicit supersession links. Treat current summaries and progress dashboards as views or rebuildable projections.

The database can be authoritative for structured events without becoming authoritative over the original source. Do not force every observation into one wide table, store age as a fact that goes stale, replace original units with normalized units, or update a mistaken row in place when an audit trail matters.

### If Markdown or ordinary files are available

Use the same concepts as headings, small tables, and links. Stable textual IDs and exact source locators matter more than filenames. Split files when that improves retrieval; do not imitate a database merely for appearance.

### If platform memory is available

Store compact facts only when the platform is suitable for health data and the user agrees. Include source and date in each memory where possible. Do not assume the platform exposes versioning, deletion, privacy, or exact retrieval; keep a portable ledger export when those limits matter.

### If only chat is available

Maintain the model visibly in the conversation. Offer a Markdown handoff after material changes. Conversation context is working memory, not guaranteed durable storage.

## Identity and scope

Confirm whose record is being handled when documents for multiple people could be mixed. Preserve the source's own identifying context privately; do not infer identity from filename alone. Never merge two people's records because their names look similar.

The user controls scope. They may want a one-time explanation, an ongoing ledger, a course, or the entire operating model. Start small and expand only as useful.

## Privacy rules

- Default to local or user-controlled storage.
- Minimize copied identifiers in summaries and examples.
- Never publish a personal ledger inside this skill repository.
- Do not send records to hosted tools, accounts, or people without explicit user approval.
- Explain material privacy tradeoffs before a transfer.
- Respect deletion requests for mutable local copies while explaining any immutable backup, audit, or platform limitation that actually exists.

## A minimal setup conversation

Learn only what is needed:

- where private evidence and ongoing records may live;
- whether the agent can persist information;
- the person's jurisdiction for current clinical guidance;
- the immediate question or outcome; and
- any privacy boundary that differs from local-only handling.

Do not demand a complete medical history before helping with a bounded task. Build the ledger as evidence arrives.
