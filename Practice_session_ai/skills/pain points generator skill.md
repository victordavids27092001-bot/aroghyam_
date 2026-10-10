---
name: pain-points-generator
description: Identify, structure, and prioritize evidence-backed UX pain points for Arogyam from user research, journeys, service evidence, and operational constraints. Use after discovery evidence exists; do not invent pain points, confuse feature requests with needs, or treat business assumptions as user findings.
---

# Pain Points Generator Skill — Arogyam UX

## Purpose

Use this skill during UX discovery and synthesis to identify the real difficulties users experience, explain why they occur, show their consequences, and determine which ones deserve further research or attention.

A pain point must be grounded in evidence. Do not report anticipated issues from the BRD, stakeholder opinions, or general market knowledge as user pain points unless relevant research supports them.

## Product Context

Arogyam is an Indian integrative-wellness application covering verified Ayurveda and Siddha care, food and nutrition education, supervised diet plans, wellness activities, reviewed remedies, facility discovery, medicine ordering and delivery, authenticated traditional medicinal products, laboratory services, and consent-based health records.

The primary market is India, with additional attention to Tamil Nadu, Tamil-language access, Siddha services, and rural, semi-urban, and urban contexts.

## Role

Act as a senior UX researcher, service designer, healthcare journey analyst, accessibility specialist, and research-synthesis lead.

Apply these capabilities:

- Qualitative research synthesis
- Behaviour and journey analysis
- Root-cause analysis
- Jobs-to-be-done and need analysis
- Service-blueprint thinking
- Accessibility and inclusion analysis
- Trust and mental-model analysis
- Healthcare safety and privacy analysis
- Evidence traceability
- Severity and prioritization assessment
- Problem-statement writing

## Required Inputs

Use available evidence from:

- `../Input/aroghyam.brd.md` as context only
- `secondary research skill.md` outputs
- `qualitative research skill.md` outputs
- `user persona generator skill.md` outputs
- Interview transcripts and notes
- Contextual observations
- Diary studies
- Current-state journeys
- Competitor and service research
- Support, complaint, analytics, or operational evidence

Do not create validated pain points from the BRD or personas alone. Trace persona statements back to the underlying research.

## What Counts as a UX Pain Point

A UX pain point is a recurring or consequential difficulty that prevents or complicates a user’s goal within a specific context.

A useful pain point explains:

1. Who experiences it
2. What they are trying to accomplish
3. Where and when it occurs
4. What observable difficulty happens
5. Why it happens
6. What workaround the user attempts
7. What consequence results
8. What evidence supports it

## What Is Not Automatically a Pain Point

- A stakeholder opinion
- A requested feature
- A business objective
- A general market trend
- A demographic characteristic
- A diagnosis
- A usability preference
- A competitor feature Arogyam lacks
- A researcher’s assumption
- A low conversion number without evidence explaining why

## UX Principles

### Evidence before assertion

Every pain point must link to participant codes, observations, journey evidence, support data, or a verified source. If evidence is absent, label it as an assumption or research question.

### Behaviour before opinion

Prioritize what users did, attempted, avoided, misunderstood, or worked around. Use opinions as context rather than proof of behaviour.

### Cause before solution

Do not stop at symptoms. Investigate the underlying information, trust, service, operational, accessibility, cultural, safety, or technical cause.

### Need before feature

Translate “I want a reminder” into the underlying need, such as remembering a time-sensitive care action. Do not assume the requested feature is the correct solution.

### Context matters

Specify geography, language, device, connectivity, household role, care setting, service availability, and journey stage when they affect the problem.

### Safety changes priority

A rare problem may be critical if it could cause delayed emergency care, medicine misuse, privacy harm, incorrect treatment, or exclusion from necessary services.

### Inclusion without stereotypes

Do not assume older adults lack digital ability, rural users lack health literacy, or traditional-medicine users reject conventional care. Report only supported patterns.

### Preserve contradictions

Different users may experience opposite problems. Do not combine them into a false average.

## Pain-Point Categories

Classify pain points only when helpful:

### Functional

The user cannot complete or understand a task.

### Informational

The information is missing, unclear, inconsistent, overly technical, or difficult to evaluate.

### Trust and credibility

The user cannot judge a practitioner, seller, facility, medicine, raw product, laboratory, claim, or platform.

### Access

Language, disability, distance, cost, connectivity, device, payment, service availability, or caregiver dependence prevents access.

### Emotional

The journey creates anxiety, stigma, fear, uncertainty, shame, or loss of control.

### Service and operational

Handoffs, appointments, fulfilment, delivery, refunds, support, partner coordination, or follow-up fail.

### Safety

The experience could contribute to unsafe self-medication, delayed care, missed contraindications, unnecessary tests, or medicine harm.

### Privacy and control

The user cannot understand or control collection, access, sharing, retention, caregiver access, or deletion of health information.

## Arogyam Areas to Examine

Look for evidence within these journeys:

- Finding and verifying Ayurveda or Siddha practitioners
- Choosing online versus in-person care
- Understanding food-as-medicine information
- Following a culturally and financially realistic diet plan
- Evaluating home-remedy safety and evidence
- Recognizing when conventional, urgent, or emergency care is needed
- Obtaining and understanding a prescription
- Ordering and receiving medicines
- Handling substitutions, storage, delays, returns, and adverse effects
- Assessing traditional raw-product identity, source, batch, expiry, and authenticity
- Finding nearby clinics, hospitals, pharmacies, and laboratories
- Booking and preparing for laboratory tests
- Understanding, storing, and sharing laboratory reports
- Managing consent, privacy, caregivers, and health records
- Using the service in Tamil, with low bandwidth, or with accessibility needs

These are investigation areas, not predetermined pain points.

## Workflow

### 1. Define the decision and evidence set

State which product or research decision the analysis must support. List the research sources, participant contexts, methods, date range, and limitations.

### 2. Extract difficulty signals

Identify:

- Failed or abandoned tasks
- Repeated questions
- Confusion and misunderstanding
- Delays and additional effort
- Workarounds
- Repeated information entry
- Dependence on another person
- Trust breakdowns
- Emotional distress
- Safety or privacy risks
- Differences between expected and actual service

Keep each signal connected to its original evidence.

### 3. Separate symptom, pain point, and root cause

Example:

- **Symptom:** A user abandons practitioner booking.
- **Pain point:** The user cannot confidently choose a practitioner.
- **Possible root cause:** Credentials, registration status, language, fees, and treatment approach are unclear.
- **Consequence:** The user delays care or relies on informal recommendations.
- **Evidence gap:** Which trust information matters most still needs validation.

Do not state a root cause as fact unless the evidence supports it.

### 4. Cluster related evidence

Group signals by user goal, journey stage, underlying cause, and consequence. Do not group evidence merely because it mentions the same screen or feature.

For each cluster, record:

- Supporting participant codes or sources
- Contexts represented
- Important variation
- Contradictory evidence
- Confidence

### 5. Write the pain-point statement

Use this format:

> **[User/context] struggles to [goal] when [situation] because [evidence-backed cause], resulting in [user or service consequence].**

Good example:

> Tamil-speaking caregivers with limited access to verified local information struggle to compare Siddha practitioners because credentials, languages, consultation modes, and current availability are fragmented, resulting in repeated calls and reliance on informal recommendations.

Use this only as a format example, not as a validated Arogyam finding.

### 6. Assess impact

Evaluate:

- Goal blockage
- Frequency within the evidence set
- Time and effort
- Emotional impact
- Financial impact
- Accessibility and exclusion
- Trust impact
- Health or medication safety
- Privacy impact
- Operational impact
- Recoverability

Do not use frequency alone. A high-severity safety issue may outrank a common inconvenience.

### 7. Prioritize transparently

Use four separate judgements:

- **Evidence confidence:** strength and diversity of supporting evidence
- **User impact:** consequence for the user’s goal and experience
- **Safety/access criticality:** potential harm or exclusion
- **Strategic relevance:** relationship to Arogyam’s purpose and scope

Do not create a precise numerical score unless the scoring definitions and evidence support it. Show uncertainty rather than manufacturing accuracy.

### 8. Convert gaps into research questions

When cause, prevalence, affected segment, or consequence is unclear, define the next research question instead of forcing a conclusion.

### 9. Create opportunity statements

Write opportunities without embedding a final feature:

> How might we help [user/context] achieve [need] while respecting [constraint or safety requirement]?

## Evidence-Confidence Labels

- **Strong qualitative support:** repeated, specific evidence across relevant contexts with limited contradiction
- **Moderate qualitative support:** repeated evidence but limited diversity or notable gaps
- **Early signal:** potentially important evidence from few or narrow contexts
- **Contradictory:** materially different patterns exist
- **Assumption:** no adequate user evidence
- **Unable to determine:** evidence does not support a conclusion

These labels do not establish population prevalence.

## Severity Levels

- **Critical:** May contribute to serious healthcare, medication, privacy, or emergency harm; requires immediate review
- **High:** Blocks an important goal or excludes a meaningful user group
- **Medium:** Causes substantial confusion, delay, effort, or loss of trust
- **Low:** Creates limited friction with a clear recovery path

Severity and evidence confidence must be recorded separately. A critical early signal still requires attention and validation.

## Required Outputs

Produce:

1. Analysis purpose and evidence set
2. Research limitations
3. Raw difficulty-signal inventory
4. Pain-point clusters
5. Evidence-backed pain-point statements
6. Symptom-versus-root-cause analysis
7. Journey-stage mapping
8. Affected user and context mapping
9. Severity and confidence assessment
10. Accessibility, safety, privacy, and trust impact
11. Workarounds and current alternatives
12. Contradictions and edge cases
13. Prioritized pain-point matrix
14. Research gaps
15. “How might we” opportunity questions
16. Discover-to-Define handoff

## Pain-Point Table

| ID | Pain-point statement | User/context | Journey stage | Evidence | Root cause status | Consequence | Workaround | Confidence | Severity | Safety/access impact | Research gap |
|---|---|---|---|---|---|---|---|---|---|---|---|

## Prioritization Matrix

| Pain point | Evidence confidence | User impact | Safety/access criticality | Strategic relevance | Priority recommendation | Rationale |
|---|---|---|---|---|---|---|

## Quality Checklist

Before accepting a pain point, verify:

- Is it supported by evidence?
- Is the user and context clear?
- Does it describe a problem rather than a missing feature?
- Is the journey stage identifiable?
- Are symptom and root cause separated?
- Is the consequence visible?
- Are workarounds captured?
- Are contradictions included?
- Are severity and confidence separate?
- Are accessibility, trust, safety, and privacy considered?
- Is the wording respectful and free of stereotypes?
- Is the problem within or adjacent to Arogyam’s scope?

## Research Integrity Rules

- Never invent participants, observations, quotations, problems, causes, severity, or frequency.
- Do not treat persona content as evidence unless it links back to research.
- Do not convert stakeholder opinion into a user pain point.
- Do not claim prevalence from qualitative research.
- Do not hide contradictory evidence.
- Do not diagnose users or provide treatment recommendations.
- Do not confuse dissatisfaction with medical harm.
- Do not use pain points to justify a predetermined feature.
- Label assumptions and evidence gaps explicitly.

## Reusable Activation Prompt

> Use the `pain-points-generator` skill to identify and prioritize evidence-backed UX pain points for Arogyam from the supplied research. Review interview notes, observations, journeys, personas, secondary research, support evidence, and operational constraints. Extract difficulty signals, then separate symptoms, pain points, possible root causes, workarounds, and consequences. Cluster evidence by user goal and journey context, preserve contradictions, and keep every pain point traceable to participant codes or verified sources. Assess evidence confidence separately from severity, including healthcare safety, medication risk, privacy, accessibility, trust, emotional, financial, and operational impact. Convert uncertain areas into research questions and validated problems into solution-neutral “How might we” opportunities. Never invent findings, claim prevalence from qualitative data, or treat a requested feature as the underlying need.

