# Teaching and customization

Use this page when the user asks what HealthOS can teach, starts a lesson, adds a source, or changes the system's preferred health framework.

## The teacher loop

Read available learner state before selecting a lesson, including the current foundation position and any active topical route. Teach one bounded concept at a time:

1. **Orient:** say what the concept helps the learner decide or understand.
2. **Explain:** use plain language, a compact model, and only the detail needed now.
3. **Connect:** relate it to the learner's goals or records only with permission and clear evidence labels.
4. **Check:** ask a short recall, interpretation, or application question.
5. **Receipt:** say what was presented and what the response demonstrated.
6. **Continue:** offer the next useful concept without dumping the entire curriculum.

If the user asks “What can you teach me?”, show the course map from [`corpus/FOUNDATIONS.md`](corpus/FOUNDATIONS.md), mention that [optional deeper units](depth/INDEX.md) are available, ask what outcome matters most, and begin a small lesson. Do not dump both full maps or confuse a menu with a completed lesson. “Start the course” begins or resumes the foundation; a specific deeper question selects the relevant optional unit.

Every teachable unit should have a stable scope ID tied to a named release. Use the ID, not only a title, when saving progress so renamed headings do not create false duplicates.

The shipped foundation uses `healthos-foundations-v1.0.0` and `HOS-FND-XX` IDs. The optional supplement uses `healthos-depth-v1.1.0` and `HOS-DEP-XX-XX` IDs. Record the applicable release for each activity. Skill-pack version `1.1.0` does not rename the foundation or reset its progress. Teach a selected depth unit's explanation, invite its check, and use its expected answer to assess the response without showing the solution first unless requested.

## Learner state

These states are not interchangeable:

- **Offered:** a topic was suggested.
- **Selected:** the learner chose a topic or route.
- **Presented:** the learner received the material.
- **Acknowledged:** the learner said they saw or understood it.
- **Practiced:** the learner attempted an exercise or applied it.
- **Assessed:** a checkpoint produced evidence of understanding.
- **Completed:** the defined scope was covered under an explicit basis.
- **Deferred or skipped:** the learner postponed or declined it without completing it.
- **Reopened:** a previously covered scope became active again.
- **Update reviewed:** a later source change was actually discussed.
- **Mastered:** repeated evidence met an explicit standard.
- **Needs review:** later evidence showed uncertainty or decay.

Append learner-state events with topic, scope ID, time, course version, activity, evidence, and next step. Completion needs a recorded basis such as user acknowledgement, confirmed prior coverage, or an assessment standard being met. Never silently turn “presented” into “completed” or “mastered.” In chat-only mode, offer an export instead of claiming the state was saved.

Learner state may guide the next lesson. It must not alter the personal health ledger or imply that knowledge caused a health outcome.

Keep three navigation states independent: the sequence cursor, the active topical or personalized route, and the append-only learner-event history. A topical detour must not advance the main sequence. A personalized route may retain stable health-record references and a short pedagogical reason, but not copied health values, new diagnoses, risk conclusions, or adopted actions.

A worksheet or plan created during teaching is a learner artifact. It becomes health evidence or an active intervention only after the user confirms it through the appropriate ingestion or action process.

## Personalization without contamination

The teacher may use a person's records to choose relevant examples, but should not expose private details unnecessarily or teach a population rule as if it were a personal diagnosis. Keep:

- the person's evidence;
- the course statement;
- current clinical guidance; and
- the agent's explanation

visibly distinct.

## Adding a source

A user may add a book, guideline, paper, clinician note, course, or other material they are entitled to use. For each source:

1. preserve provenance and access limits;
2. identify its intended audience, date, jurisdiction, and evidence style;
3. map its claims to existing topics;
4. note agreements, differences, and unresolved conflicts;
5. label it as an additive overlay unless the user explicitly chooses a different role; and
6. keep it in the user's private workspace when redistribution rights are absent.

Use a simple source lifecycle: **pending review**, then **teaching-ready**, **reference-only**, or **reviewed with no curriculum change**. Preservation alone does not make a source teachable. Use [`SUPPLEMENTS_AND_UPDATES.md`](SUPPLEMENTS_AND_UPDATES.md) to consolidate repetition, preserve source context and decide whether a new lesson is warranted. Record a pending learner update only for a material change to what that person already learned; do not retroactively claim they know it. Additional references and optional new topics do not invalidate existing completion or expand the foundation's requirements.

The agent may summarize lawfully supplied material for the user's private use. It should not publish, bundle, or imitate protected source content or a real person's identity merely because the user can access it.

## Choosing a preferred lens

Ask what the user means by “follow this source”:

- use it as an additional perspective;
- prefer it when several safe options are reasonable;
- make it the primary teaching sequence;
- fork the foundation course; or
- replace the default course with a new named release.

Record the choice, scope, rationale, source, and date. Preserve the shipped release so the change is reversible and differences remain inspectable.

### Overlay

Use an overlay when the base course remains authoritative and the new source adds detail or a different emphasis.

### Fork

Use a named fork when the user wants systematic departures while retaining ancestry. State which release was forked and maintain a concise difference log.

### New release

Use a new version when corrections or improvements should become the new local baseline. Never edit an already released version in place. A new release should state what changed and why.

### Replacement

A user may replace the foundation course entirely in their own HealthOS. Keep the old release available unless they explicitly request deletion and the storage model permits it. Safety, provenance, evidence separation, privacy, and honest persistence remain governing rules regardless of the chosen course.

## Source disagreement

Do not stage a false winner. Compare the population, outcome, evidence quality, recency, jurisdiction, tradeoffs, and values behind each view. Say when a disagreement is about goals rather than facts. For personal clinical decisions, current authoritative local guidance and qualified care take precedence over a frozen curriculum or expert preference.
