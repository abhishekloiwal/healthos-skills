# Understanding measurements

Use this route when the learner wants to understand why results disagree or what a number actually establishes. Build on `HOS-FND-02`, `HOS-FND-03`, and, for screening arithmetic, `HOS-FND-05`.

Units: ME-01 compares methods; ME-02 separates concentration from biological activity; ME-03 works through denominators. Teach the selected unit, then use its check before showing the expected answer.

## HOS-DEP-ME-01 — Before explaining a change, check what was measured

**Purpose:** Distinguish a biological change from a change in the measurement process.

A result is an observation produced by a particular method. Two numbers with the same everyday name may still measure different quantities, use different assays, or depend on different inputs. The first preventive question is therefore whether the comparison is valid; only then can the difference help judge an intervention.

The supplied discussions give three useful examples. Attia reports different testosterone results from immunoassay and mass spectrometry on the same blood draw. That is a paired measurement example, not proof that every discrepancy has the same cause. Arsenault explains that Lp(a) mass and particle concentration describe different quantities; the variable size of the particle prevents a universal exact conversion between mg/dL and nmol/L. Patrick and Attia discuss creatine use as relevant context when interpreting creatinine and considering another filtration estimate. That explanation does not dismiss an abnormal kidney result or supply a kidney-disease assessment.

For a fictional before/after comparison, reconstruct the analyte, unit, specimen, assay, date, preparation, medication or supplement context, and whether the value was measured or calculated. Preserve both original results. If the method changed, explain the comparability limit before calling a treatment successful or a disease worse. A result can be accurately reported yet insufficient for the conclusion being drawn from it.

**Source basis:** [D291](SOURCES.md#d291), E291-07, 00:39:16; [D210](SOURCES.md#d210), E210-06/07, 00:22:47–00:24:04; [D369](SOURCES.md#d369), E369-26, 01:31:48.

**Check:** A person's Lp(a) report changes from a mass unit to a particle-concentration unit and the printed number rises. What must be established before calling this a biological increase?

**Expected answer:** The quantity, units, assays and comparable original observations. A larger number in a different unit is not itself an increase; no universal exact mass-to-particle conversion should be invented.

## HOS-DEP-ME-02 — A concentration is a snapshot of a moving system

**Purpose:** Understand why the amount present does not always describe function or flow.

A pool can remain the same size while material enters and leaves it at very different rates. Rader uses this distinction when discussing HDL: the cholesterol carried in HDL particles is not a direct measurement of the rate at which cholesterol is transported through tissues and ultimately removed. Two people with equal HDL-C can therefore differ in the biology that produced that concentration. Raising the measured pool does not automatically improve the relevant function.

Brooks makes a related distinction for lactate. A blood concentration reflects production, transport, use and clearance, with sampling location and workload affecting interpretation. Liver and kidney clearance can change during hard exertion. A rise cannot be assigned entirely to production by one working muscle, and a value obtained at one protocol cannot automatically define another person's training boundary.

The shared lesson is to name the process of interest before selecting its marker. If the goal is transport, clearance, exercise capacity or clinical benefit, ask whether the chosen measurement actually measures that process, is a useful proxy, or merely correlates with it. This does not make concentration measurements useless. It makes their use more precise and prevents optimization of a visible number from replacing the underlying preventive objective.

For particle-specific cardiovascular reasoning, continue with [cardiovascular depth](CARDIOVASCULAR.md). For workload and test protocol, use [exercise depth](EXERCISE.md).

**Source basis:** [D240](SOURCES.md#d240), E240-21, 01:20:04; [D312](SOURCES.md#d312), E312-18/19, 00:52:42–00:53:46, and E312-24/27, 01:16:27/01:27:29.

**Check:** Two people have the same concentration of a substance. Does that establish equal production, equal clearance, or equal clinical risk?

**Expected answer:** None follows automatically. Different combinations of production and removal can produce the same concentration; function and clinical relevance need their own evidence and context.

## HOS-DEP-ME-03 — Keep the denominator and time horizon attached

**Purpose:** Use screening and risk numbers without answering the wrong question.

Sensitivity asks what fraction of people with a condition test positive. Specificity asks what fraction without it test negative. Positive predictive value asks a different question: among positive results, what fraction actually have the condition? The number of people without the condition matters because even a modest false-positive rate can create many positive results in a large unaffected group.

Consider a new, explicitly hypothetical exercise: 10,000 people, 1% currently having the target condition, a test with 90% sensitivity and 95% specificity. There are 100 affected people, producing 90 true positives. Of 9,900 unaffected people, 5%, or 495, test positive. Thus 90 of 585 positive results are true positives: about 15.4%. These are illustrative inputs and arithmetic, not the performance of a named test or a person's risk.

The prevalence input concerns disease present in the tested population. A lifetime or ten-year probability of developing disease is a different quantity; it cannot simply be substituted. Likewise, an annual excess risk is not a cumulative risk over an unspecified trial period. Before reusing a number, retain the population, event, denominator, comparator and interval. These distinctions make additional testing more deliberate: ask what a result would change and what follows after either result, rather than treating a positive result as a diagnosis.

**Source basis:** [W-SCREEN](SOURCES.md#w-screen), sensitivity worksheet input and confusion-matrix cells; [W-RISK](SOURCES.md#w-risk), definition of future interval risk and its suggested worksheet use, whose mismatch is explicitly resolved here; [D269](SOURCES.md#d269), items 19–20, 01:08:42–01:18:13. The numerical example above is an original teaching calculation.

**Check:** Why would substituting lifetime cancer risk for current prevalence distort the exercise? What is the positive predictive value in the fictional example?

**Expected answer:** The probability of developing disease over a future interval is not the probability it is present now in this tested population. The example gives 90/(90+495), about 15.4%, despite 90% sensitivity.
