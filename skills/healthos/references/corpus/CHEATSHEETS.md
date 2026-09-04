# HealthOS cheat sheets

These pages are navigation aids, not an authority layer. Use them to ask better questions and choose evidence. For any personal decision, retrieve the exact record and current local guidance.

## How to show a number

Never present a bare health number. Attach:

- exact metric and whether it was measured, calculated, or estimated;
- value and unit;
- collection time and relevant context;
- method, specimen, device, or protocol when relevant;
- source-provided reference interval or flag;
- clinical decision threshold and its source, population, jurisdiction, and date when used;
- personalized target and decision owner when one exists; and
- prior comparable values, without forcing a trend.

There is no single universal expert range, laboratory range, or optimal range that safely applies to every person. Keep source intervals, diagnostic thresholds, treatment thresholds, and personal targets separate.

### Label the number before using it

Use three independent labels:

| Dimension | Allowed labels |
| --- | --- |
| Observation form | directly measured, user-reported, calculated, estimated |
| Number role | source reference interval, diagnostic criterion, risk band or association, action threshold, treatment goal, named-expert preference, user-adopted target, study result |
| Claim status | current guideline, named-expert practice, guest view, heuristic, personal example, thought experiment, study result, hypothesis or experimental claim |

Also retain the population, jurisdiction, effective date, method, unit, decision owner, and any source it supersedes. Never promote a study result, creator preference, or personal example into a clinical target.

For tests, label the role as `broadly useful`, `periodic`, `conditional`, `experimental`, or `generally not recommended`. Every proposed test needs a question, possible result paths, and a decision it could change.

## Small numeric register

These are source-linked orientation values, frozen as of this release. They do not form a universal prescription. Check current local guidance and personal context before acting.

| Topic | Number | Correct use |
| --- | --- | --- |
| Adult physical activity | 150–300 minutes/week moderate aerobic activity, or 75–150 minutes vigorous, plus muscle strengthening on at least 2 days/week | Public-health range from the US Physical Activity Guidelines; adapt for ability, condition, pregnancy, and local guidance. Some activity is better than none. |
| Adult sleep | At least 7 hours regularly for healthy adults aged 18–60; 7–9 hours is a common cardiovascular-health orientation for most adults | Population guidance, not a promise that duration alone means restorative sleep. Symptoms and daytime function matter. |
| Fruit and vegetables | At least 400 g/day for people older than 10 | WHO public-health guidance; total pattern, access, tolerance, and clinical needs still matter. |
| Naturally occurring dietary fibre | At least 25 g/day for people older than 10 | WHO public-health guidance; increase and personalize with gastrointestinal and clinical context. |
| Salt | Less than 5 g salt/day, equivalent to 2 g sodium/day, for adults | WHO population guidance; individualized sodium or potassium advice can differ with disease and medication. |
| Blood pressure | Below 120/80 mm Hg is labelled optimal in the American Heart Association cardiovascular-health construct | A US prevention orientation, not by itself a diagnosis, medication threshold, or Dutch/other-jurisdiction rule. Use repeated standardized readings. |
| ApoB | Around 60 mg/dL was described by Peter Attia in 2022 as his practice “ceiling”; lower figures on the same page are a thought experiment | Named-expert practice preference, not a universal guideline or a reason to self-medicate. Decisions require total risk, harms, and a clinician. |
| Protein | Roughly 1.6–2.2 g/kg/day is Peter Attia's public 2025 recommendation for muscle-oriented optimization | Named-expert recommendation and research interpretation, not a default for every person. Adjust for goals, energy intake, pregnancy, disease, kidney context, and professional advice. |

The Attia rows are included because HealthOS uses his public prevention lens. They are deliberately few, attributed, dated, and kept apart from clinical thresholds. Bryan Johnson's contribution to the default HealthOS lens is consistent execution and measurement; his changing personal biomarkers, prescriptions, product stack, calorie intake, and advanced therapies are not transferable target ranges. See [`PREVENTIVE_LENSES.md`](PREVENTIVE_LENSES.md) and [`SOURCES.md`](SOURCES.md).

## Labs and screening

Labs answer narrower questions than panel names suggest. Screening is a separate clinical decision lane even when it uses a laboratory test.

### Lab map

| Domain | Common observations | Quick interpretation questions |
| --- | --- | --- |
| Lipids and atherogenic particles | Total cholesterol, LDL-C, HDL-C, triglycerides, non-HDL-C, apolipoprotein B, lipoprotein(a) | Is the value direct or calculated? Fasting? Same units and assay? Prior disease or therapy? Is the source discussing particle number, cholesterol mass, or inherited risk? |
| Glucose regulation | Glucose, HbA1c, oral challenge results, home or continuous readings, insulin when clinically indicated | What time window does it represent? Meal, fasting, illness, steroid, pregnancy, anaemia, red-cell, or device context? Is this screening, diagnosis, or monitoring? |
| Kidney | Creatinine, estimated filtration rate, cystatin C, urine albumin and creatinine, electrolytes | Which estimating equation and inputs? Stable state? Muscle-mass or medication context? Is urine concentration accounted for? |
| Liver and biliary | ALT, AST, alkaline phosphatase, GGT, bilirubin, albumin, coagulation measures | Pattern or isolated value? Alcohol, medication, supplement, exercise, muscle injury, infection, or imaging context? |
| Blood count | Haemoglobin, haematocrit, red-cell indices, white-cell count and differential, platelets | Persistent or transient? Lab-specific interval? Symptoms, infection, bleeding, altitude, hydration, pregnancy, medication, or ancestry context? |
| Iron and nutrients | Ferritin, transferrin measures, iron, B12, folate, vitamin D and targeted nutrients | Was deficiency risk established? Inflammation or supplementation present? Does the marker reflect stores, transport, intake, or function? |
| Thyroid and endocrine | TSH, free thyroid hormones, and condition-specific hormone tests | Time of day, illness, pregnancy, medication, supplements such as biotin, menstrual or life-stage context? Is the test appropriate for the question? |
| Inflammation and immune | CRP or high-sensitivity CRP, ESR, antibodies and condition-specific markers | Acute illness or injury? Screening or diagnostic context? Is a nonspecific marker being over-interpreted? |

This is a topic map, not a default order set. More testing can produce incidental findings and harm. Choose a test only when its result could change a decision.

### Screening lane

Maintain a current, jurisdiction-specific review of:

- cardiovascular and metabolic risk assessment;
- cancer screening by age, anatomy, risk, family history, prior findings, and local program;
- blood pressure and other routine primary-care measurements;
- immunizations;
- infectious-disease screening based on pregnancy, exposure, travel, behaviour, occupation, and local guidance;
- bone health and fracture risk;
- vision, hearing, oral health, and functional risk;
- mental health, substance use, safety, and social needs; and
- reproductive, pregnancy, and sexual health where relevant.

For each item show: eligible population, personal modifiers, last evidence, result, next review, source guideline, and uncertainty. A symptom bypasses the routine screening lane and needs appropriate evaluation.

## Exercise and metrics

Choose measures that match the person's goals and can be repeated safely.

| Quality | Useful observations | What commonly goes wrong |
| --- | --- | --- |
| Movement exposure | Time active, step count, sedentary time, activity bouts | Treating steps as fitness; comparing devices without checking definitions |
| Aerobic capacity | Standardized field test, pace or power at a set effort, clinical exercise test, estimated or measured cardiorespiratory fitness | Mixing measured and estimated values; ignoring protocol, terrain, temperature, altitude, medication, or illness |
| Strength | Standardized load, repetition, dynamometer, or task test | Technique and range change; unsafe maximal tests; comparing unlike movements |
| Muscular endurance | Repetitions or time under a fixed protocol | Calling fatigue, pain, or motivation a pure muscle measure |
| Power | Jump, stair, sit-to-stand speed, or supervised power test | Ignoring landing risk, skill, body mass, and device algorithm |
| Balance and coordination | Single-leg, gait, reach, or clinician-selected assessment | Using a risky test without support; overlooking vision, vestibular, neurological, or medication context |
| Mobility | Task-specific range and movement quality | Treating more range as always better; failing to link it to function or symptoms |
| Recovery and tolerance | Symptoms, sleep, perceived exertion, heart-rate response, readiness pattern | Letting one wearable score override pain, illness, or function |
| Body composition | Weight, waist, imaging, bioimpedance, or performance context | Moralizing the metric; comparing methods as if interchangeable; ignoring hydration and measurement error |

Record the protocol, unit, conditions, safety adaptations, and why the measure matters. Separate public activity guidance from an individualized training prescription.

## Nutrition and metrics

Start with the goal, then choose the least burdensome observations that can test it.

| Domain | Possible observations | Interpretation guardrail |
| --- | --- | --- |
| Overall pattern | Meal pattern, food groups, preparation, beverages, degree of processing | A few logged days may not represent ordinary intake |
| Adequacy and diversity | Energy context, protein sources, fibre-rich foods, fruits and vegetables, fats, micronutrient risks | Needs vary with body size, age, pregnancy, activity, disease, culture, and goal |
| Cardiometabolic response | Hunger, energy, weight or waist context, blood pressure, lipids, glucose measures | Do not attribute a biomarker change to diet without considering medication, illness, activity, sleep, and measurement conditions |
| Performance and recovery | Training intake, hydration, symptoms, recovery, strength or endurance response | A performance strategy is not automatically best for long-term health or another sport |
| Gastrointestinal response | Symptoms, stool pattern, timing, suspected triggers, diagnoses | Restrictive diets can mask problems or create deficiency; persistent or alarming symptoms need clinical review |
| Alcohol and stimulants | Type, amount, timing, pattern, purpose, sleep and symptom response | Self-report and serving size are uncertain; risk is not captured by weekly average alone |
| Sustainability | Cost, access, enjoyment, culture, preparation time, social fit | A theoretically strong plan that cannot be maintained is not working |

Do not prescribe a universal calorie, protein, carbohydrate, fat, sodium, fibre, or supplement target from this frozen page. Retrieve current authoritative guidance, then personalize for the person's clinical state, goals, total diet, and professional plan. Preserve the exact target, unit, source, date, and decision owner in the action record.

## Fast answer check

Before answering from a cheat sheet, ask:

1. Do I have the exact personal evidence and unit?
2. Is the comparison truly compatible?
3. Am I using a reference interval, diagnosis rule, action threshold, or preference?
4. Is the guidance current for this person's jurisdiction and context?
5. Have I separated recorded fact, interpretation, and proposed action?
