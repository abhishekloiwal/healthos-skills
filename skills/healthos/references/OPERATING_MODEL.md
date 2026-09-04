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
