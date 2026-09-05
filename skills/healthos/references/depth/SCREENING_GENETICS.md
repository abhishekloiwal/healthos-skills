# Screening and genetic-test interpretation

Purpose: judge what a detection method can establish and how its result connects to a useful decision.
Prerequisites: `HOS-FND-02`, `HOS-FND-03`, `HOS-FND-05`, and `HOS-FND-09`.
Scope: five optional units on liquid-biopsy use cases, outcomes, follow-up pathways, assay coverage, and genetic utility.

| Unit | Question |
|---|---|
| `HOS-DEP-SG-01` | Why does a liquid biopsy need a defined use case? |
| `HOS-DEP-SG-02` | What separates early detection from demonstrated benefit? |
| `HOS-DEP-SG-03` | Why is follow-up part of a screening test's value? |
| `HOS-DEP-SG-04` | What does a negative genetic test actually exclude? |
| `HOS-DEP-SG-05` | How do genetic effect size and actionability differ? |

## HOS-DEP-SG-01 — Separate three questions hidden inside liquid biopsy

**Purpose:** prevent evidence from one cancer-testing application being transferred automatically to another.

Liquid biopsy describes a way of obtaining a biological signal, not a single clinical purpose. The discussions separate three applications: identifying mutations in an already diagnosed cancer to help select therapy, looking for residual disease after treatment, and screening someone without a known cancer. The starting information and the required evidence differ in each case.

After a tumor has been removed, investigators can sequence it and search blood for its particular mutations. This tumor-informed approach has a known template. Testing an undiagnosed person lacks that template and must distinguish a sparse cancer signal from background biology while also helping locate its source. Evidence that a test detects a known tumor's mutations therefore does not establish its performance as a population screen.

Performance also depends on the cancers included. A pooled sensitivity can look impressive if advanced cancers are overrepresented, although screening is especially interested in earlier disease. Cancer type and stage influence how much detectable material reaches blood. Methylation patterns may help identify tissue of origin, while mutation-based approaches answer other questions. Before accepting a headline detection rate, identify the use case, whether the tumor was known, and the distribution of cancer types and stages. Those details define the claim the test has actually supported.

**Source basis:** [D213](SOURCES.md#d213), items 13–18 and 21, `01:13:11`, `01:15:12`, `01:18:39`, `01:22:12`, `01:24:27`–`01:26:54`, `01:28:35`, and `01:37:23`–`01:38:44`; [D290](SOURCES.md#d290), item 4, `00:31:49`.

**Check:** Why would accurate detection of residual tumor DNA after surgery not, by itself, validate screening healthy people with the same technology?

**Expected answer:** Residual-disease testing can use a known tumor template and a different pretest context. Screening must detect unknown cancers, manage background signals, and establish performance in its own population and stages.

## HOS-DEP-SG-02 — Ask whether earlier detection changes the outcome

**Purpose:** distinguish analytical success, stage at diagnosis, and evidence that screening helps people live better or longer.

A test can detect a cancer earlier on the calendar without proving that the detection changes its course. Diehn offers a concrete concern for circulating tumor DNA: some tumors classified as early stage may already have invisible disease elsewhere. Detecting their blood signal does not establish that a local procedure can eradicate all disease. An increase in early-stage diagnoses is therefore not the same endpoint as fewer cancer deaths.

Aravanis discusses a complementary idea: a reduction in late-stage diagnoses could provide an earlier signal that screening is changing the disease trajectory. In the episode, that is a proposed surrogate endpoint while longer outcome follow-up remains necessary. He favors offering testing sooner; Diehn puts greater emphasis on demonstrating cancer-specific mortality benefit. Their different thresholds for adoption should remain distinguishable from the results already observed.

Interpret performance in the tested population as well. A high specificity can coexist with a substantial proportion of false positive results when disease is uncommon. The reported positive predictive value in one screening cohort cannot be carried unchanged into another population. Useful appraisal asks what was detected, in whom, what happened after detection, and which outcome improved. Detection, localization, stage shift, treatment opportunity, and survival each answer a different part of that chain.

**Source basis:** [D213](SOURCES.md#d213), items 6 and 18–20, `00:41:28`, `01:28:35`, `01:32:35`, and `01:35:18`; [D290](SOURCES.md#d290), items 14 and 17–19, `01:14:12`–`01:18:32`, `01:31:45`, `01:35:08`, and `01:39:07`.

**Check:** A new screen finds more early-stage cancers. What additional evidence would establish that this represents benefit rather than detection alone?

**Expected answer:** Evidence that the testing-and-follow-up pathway changes consequential outcomes, with appropriate comparison and harms assessed. Stage shift can be informative but is not automatically proof of reduced mortality.

## HOS-DEP-SG-03 — Evaluate the pathway after the signal

**Purpose:** understand how confirmation, localization, and management determine the usefulness and burden of screening.

An abnormal screening result begins a sequence. It may need repeat measurement, more specific imaging, tissue sampling, or observation over time. A result that cannot be localized or interpreted can create uncertainty without identifying a useful next action. Flaherty describes this problem for a positive cancer blood test before a lesion becomes visible: the follow-up network is part of whether the test can help.

The prostate discussion illustrates how changing the sequence can change the balance of benefit and harm. PSA comes from prostate tissue and is not cancer-specific. In Attia's described pathway, a concerning pattern leads to refinement with imaging and prostate-volume information, then selective biopsy and grade-aware management rather than an automatic jump from one elevated value to treatment. The specific thresholds and eligibility remain clinical questions; the transferable concept is that each step should resolve a defined uncertainty.

Whole-body MRI provides a second example. In the clinic cases discussed, suspicious breast findings eventually proved benign after further imaging and biopsy. Avoiding ionizing radiation did not remove the physical or emotional burdens of those follow-ups. Assess the entire chain: what counts as positive, how confirmation works, who interprets discordance, and whether low-risk findings can be monitored reliably. A more sensitive first step is not automatically a better complete pathway.

**Source basis:** [D267](SOURCES.md#d267), items 22 and 24, `01:28:46`–`01:38:37` and `01:34:19`–`01:35:32`; [D388](SOURCES.md#d388), items 2–5, 10–11, 13, and 16–17, `00:00:00` (single substantive transcript block); [D61](SOURCES.md#d61), items 18–19, `01:43:43` and `01:45:35`.

**Check:** What would be missing from an evaluation that compares two screening tests only by their sensitivity?

**Expected answer:** Specificity and predictive value, confirmation and localization, follow-up harms, management of uncertain or low-risk findings, and evidence that the completed pathway improves meaningful outcomes.

## HOS-DEP-SG-04 — A negative genetic result has the boundaries of its assay

**Purpose:** interpret a negative result without confusing a limited search with exclusion of inherited or ordinary disease risk.

Genetic tests do not all inspect the same territory. A consumer genotyping array samples selected variants. A disease panel examines a defined set of genes or relevant changes with its own coverage limits. Exome and genome sequencing search more broadly but still require interpretation of what was found. The product name alone does not tell us which clinical question it can answer.

Attia uses consumer BRCA testing to illustrate the consequence. A product that examines a small selection of pathogenic variants can return a negative result while leaving other clinically important variants untested. That result cannot be read as a negative comprehensive hereditary-cancer assessment. Even an appropriately selected clinical test has a bounded negative meaning: it found no reportable pathogenic variant within its tested scope.

Hereditary testing also addresses a different question from whether cancer can occur at all. An inherited predisposition and somatic changes acquired by cells during life are different contributors. A negative inherited-risk result does not remove the possibility of acquired cancer, nor does it erase relevant family history or observed phenotype. Choose the assay around the question, then preserve its scope alongside the result. Broader sequencing can be appropriate for unresolved complex presentations, but more findings may add uncertain interpretation rather than a clearer answer.

**Source basis:** [D392](SOURCES.md#d392), items 3, 5, 12, 14, and 20–24, `00:08:45`, `00:14:22`, `00:25:22`, `00:29:07`, `00:45:05`, `00:47:18`, `00:48:03`, `00:50:14`, `00:52:36`, and `00:54:25`.

**Check:** A consumer hereditary-cancer screen is negative. Which two forms of reassurance would exceed that result's scope?

**Expected answer:** Claiming that all clinically important hereditary variants were excluded, or that ordinary cancer risk was excluded. Both assay coverage and the distinction between inherited and acquired changes matter.

## HOS-DEP-SG-05 — Separate genetic effect from a useful decision

**Purpose:** decide what kind of value a genetic finding might provide before treating it as a clinical instruction.

A genetic finding has at least two distinct dimensions: how strongly it changes a biological outcome and whether knowing it changes a useful decision. A large effect can have limited established intervention options. A narrower medication-related finding can be actionable even when it says little about a person's overall disease risk. Effect size and actionability should therefore be assessed separately.

The episode contrasts several uses. A result supporting familial hypercholesterolemia can clarify a suspected inherited condition and inform testing of relatives. Pharmacogenetic testing can address a specific medication-response or safety question. By contrast, a common low-effect variant does not automatically explain symptoms or justify a diet or supplement protocol. When blood pressure or a lipid phenotype can be measured directly, inferring it from DNA may add less than observing it.

Value can also be nonclinical: planning, curiosity, or understanding family relationships. That value must be weighed before testing against uncertainty, unwanted findings, and emotional impact. Most common-disease genetic findings shift probability rather than determine an outcome. Define what a positive, negative, or uncertain result would change, including the possibility that nothing clinical changes. This keeps a true genetic fact from becoming an unsupported personal prediction or an automatic action.

**Source basis:** [D392](SOURCES.md#d392), items 2, 4, 6–9, 17–19, and 25, `00:04:50`, `00:10:54`, `00:14:39`, `00:16:13`, `00:17:03`, `00:20:08`, `00:36:16`, `00:42:24`, `00:44:00`, and `00:54:48`–`00:57:07`.

**Check:** How could one genetic result have a large effect but limited actionability, while another has narrower biological scope but greater practical utility?

**Expected answer:** A strong disease association may lack an established preventive intervention, whereas a medication-specific finding may alter a concrete treatment or safety decision. Utility depends on the question and consequence, not effect size alone.
