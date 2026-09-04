# Prevention priority review

Use this page when the user asks for an LRA, longevity-risk assessment, long-range risk review, prevention priorities, or a gap analysis. HealthOS calls its original workflow the **prevention priority review** so it does not imply affiliation with a commercial assessment.

The review is a dated, derived view. It is not a diagnosis, actuarial prediction, composite health score, or ledger fact. It ranks prevention work, not the probability that an event will occur.

## Keep two outputs

### Input coverage

For each material input, record:

- status: known, partial, pending, unknown, or not applicable;
- exact source and date;
- confidence and material ambiguity;
- whether the information may be stale; and
- the next question or evidence that could change a decision.

Missing information is not a negative finding. A low-ranked domain with poor coverage is a low-confidence placement, not reassurance.

### Ranked review

For each priority, show:

- why it matters to lifespan, function, or quality of life;
- personal signals and their dates;
- counterevidence or protective factors;
- current controls and whether they are actually active;
- uncertainty and missing inputs;
- the highest-value next evidence or action;
- residual concern after current controls; and
- confidence in the placement.

Finish with a short narrative that connects the priorities without pretending they can be reduced to one number.

## Domains to cover

Use the smallest sufficient evidence, but do not omit a domain that could materially alter priority:

1. **Immediate safety and active disease:** urgent symptoms, unstable conditions, treatment complications, and major current functional change.
2. **Cardiovascular and metabolic health:** atherosclerotic disease, blood pressure, atherogenic particles, glucose regulation, kidney and liver context, nicotine, family history, prior events, and treatment response.
3. **Cancer risk and early detection:** personal and family history, inherited-risk evidence, exposures, symptoms, screening eligibility, prior findings, and whether follow-up was completed.
4. **Brain and neurological health:** cognition, cerebrovascular and metabolic risk, sleep, hearing, head injury, family phenotype, neurological symptoms, and relevant genetics with their limits.
5. **Physical reserve, bone, and falls:** cardiorespiratory fitness, strength, power, muscle and bone status, balance, mobility, falls, fractures, and the trajectory of meaningful tasks.
6. **Musculoskeletal function:** pain, injury, surgery, movement limits, training tolerance, and risks that could erode activity or independence.
7. **Emotional and social health:** mood, anxiety, substance use, compulsion, relationships, support, purpose, treatment, safety, and trajectory.
8. **Preventable injury and exposure:** driving and road risk, occupation, environment, alcohol or other impairment, infectious exposure, sun, air, and other material hazards.
9. **Care and prevention reliability:** medication reconciliation, vaccination, screening follow-up, access, adherence, clinician ownership, and gaps between plans and completed care.

Sleep, nutrition, exercise, medications, supplements, and environment often affect several domains. Treat them as cross-cutting controls and exposures rather than forcing them into only one box.

## Ranking logic

Use qualitative judgment based on:

- strength and directness of the personal evidence;
- plausible consequence for survival, independence, or lived well-being;
- personal likelihood, kept separate from potential consequence;
- modifiability and time sensitivity;
- time horizon and cumulative exposure;
- current mitigation and adherence;
- uncertainty and the cost of being wrong; and
- whether new evidence or action would change a decision.

Use language such as `highest current work priority`, `important but currently controlled`, `unresolved`, `watch`, or `low-confidence placement`. Never invent event probabilities, biological-age reductions, expected years lost, or decimal scores.

A major data gap can rank highly when resolving it is likely to change care. Novelty alone does not create priority.

## Review flow

1. Triage urgent issues before routine prevention.
2. Establish the person's goals, jurisdiction, age or life stage, relevant anatomy, and meaningful future functions.
3. Retrieve exact active records, prior review, family history, interventions, and source documents.
4. Refresh the coverage map; keep unknowns visible.
5. Apply the default HealthOS position and any user-selected lens from [`corpus/PREVENTIVE_LENSES.md`](corpus/PREVENTIVE_LENSES.md).
6. Check current local guidance for diagnosis, treatment, screening, vaccination, contraindications, and urgency.
7. Rank work priorities, state why, and identify the smallest decision-relevant next step for each leading item.
8. Compare with the previous review. Explain material changes, improved controls, worsening evidence, and unchanged gaps.
9. If persistence exists, save a new dated version only for an initial baseline or material revision. Otherwise offer a portable Markdown version.
10. Return a receipt. If nothing meaningful changed, say `no material change` rather than manufacturing churn.

Do not schedule a refresh unless the user asks and the host can actually schedule it.

## Preventive-care register

For each relevant preventive service, keep:

- service or risk question;
- current guideline source, jurisdiction, and review date;
- eligibility and personal modifiers;
- last completed evidence and result;
- next review or decision point;
- clinician or owner responsible for follow-up;
- status: not assessed, not currently eligible, due, planned, completed, follow-up pending, or declined; and
- uncertainty or missing records.

Screening is a pathway, not a checkbox. A positive screen is not a diagnosis, and a completed test is not closed until required communication, diagnostic follow-up, and the next interval are clear. New symptoms leave the routine screening lane and require appropriate evaluation.

## Compact output template

```markdown
# Prevention priority review — YYYY-MM-DD

Context: [person, jurisdiction, goals, evidence cutoff]
Change since prior review: [material change or no material change]

## 1. [Priority]
Why here: [work-priority rationale]
Personal evidence: [dated record references]
Protective factors/current controls: [...]
Unknowns: [...]
Next decision: [...]
Confidence: [high/moderate/low and why]

## Coverage gaps that could change the ranking
- [...]

## Prevention register changes
- [...]

## Short narrative
[What matters most now, what is controlled, and what should not be overclaimed.]
```

The template is optional. Preserve the information and distinctions even when the host uses another format.
