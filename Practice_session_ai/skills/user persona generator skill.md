---
name: user-persona-generator
description: Generate evidence-based UX personas for Arogyam from completed qualitative and secondary research, including behaviours, goals, needs, barriers, trust, accessibility, safety, and service context. Use after research synthesis; use a clearly labelled proto-persona when evidence is insufficient, and never invent participant data.
---

# User Persona Generator Skill — Arogyam UX

## Purpose

Use this skill to create useful, evidence-based UX personas for Arogyam. Personas must help the team make product, content, service, accessibility, and research decisions. They must not be fictional marketing profiles decorated with unsupported demographics.

Create a research-backed **persona** only when sufficient user evidence exists. When evidence is preliminary, incomplete, or based mainly on stakeholder assumptions, create a clearly labelled **proto-persona** and list what must still be validated.

## Product Context

Arogyam is an Indian integrative-wellness application intended to support verified Ayurveda and Siddha care, evidence-based nutrition, supervised diet plans, wellness activities, reviewed traditional remedies, nearby facilities, medicine ordering and delivery, authenticated traditional medicinal products, laboratory services, and consent-based health records.

India is the primary market, with additional attention to Tamil Nadu, Siddha services, Tamil-language access, regional food practices, and rural, semi-urban, and urban contexts.

## Role

Act as a senior UX researcher, behavioural synthesist, service designer, inclusive-design specialist, healthcare UX strategist, and research-governance reviewer.

Apply these capabilities:

- Research-data synthesis
- Behavioural segmentation
- Jobs-to-be-done analysis
- Needs and pain-point analysis
- Motivation and decision-factor analysis
- Journey and service-context mapping
- Trust and mental-model analysis
- Accessibility and inclusion analysis
- Health- and digital-literacy analysis
- Risk and safety-context analysis
- Evidence traceability
- Persona validation and maintenance planning

## Required Inputs

Read, when available:

1. `../Input/aroghyam.brd.md`
2. `secondary research skill.md` outputs
3. `qualitative research skill.md` outputs
4. Interview notes, observation notes, diary studies, survey context, journey maps, research synthesis, and participant metadata supplied for this task

Do not generate a research-backed persona from the BRD alone. Business requirements describe product intent, not user reality.

## Persona, Proto-Persona, and Segment

### Research-backed persona

A synthesized archetype based on recurring behaviours, goals, needs, contexts, and decision patterns found across relevant research participants.

### Proto-persona

A provisional hypothesis based on limited evidence and assumptions. Every uncertain field must be labelled and paired with a validation question.

### User segment

A group defined by meaningful shared behaviour or context. A segment does not automatically require a named persona.

### Role profile

A description of a professional or operational actor, such as a practitioner, pharmacist, or laboratory partner. Do not mislabel a business stakeholder role as a patient persona.

Choose the smallest useful artefact. Do not create personas merely because a project template expects them.

## Core UX Principles

### 1. Evidence over imagination

Every meaningful persona attribute must be traceable to research. Do not invent names, ages, occupations, quotations, diagnoses, locations, family structures, income, caste, religion, or technology access unless these details are supported and relevant.

### 2. Behaviour over demographics

Segment primarily by:

- Goals and jobs to be done
- Current behaviours
- Decision-making patterns
- Trust and evidence needs
- Care-seeking behaviour
- Service-access context
- Digital and health literacy
- Constraints and workarounds
- Attitudes toward traditional and conventional care

Use demographics only when they materially affect behaviour, access, safety, or design decisions.

### 3. Context over stereotypes

Explain how household roles, geography, language, cost, mobility, connectivity, practitioner availability, caregiving, and service infrastructure influence behaviour. Do not use cultural stereotypes as evidence.

### 4. Needs over requested features

Translate feature requests into underlying needs.

Example:

- Feature request: “Give me automatic report interpretation.”
- Possible underlying need: “Understand whether a report requires timely professional attention.”

Do not assume the proposed feature is the safest or best solution.

### 5. Patterns with differences

Represent important recurring patterns while preserving contradictions and meaningful differences. Do not create a false average that represents nobody.

### 6. Actionability

Every persona field should influence research, information architecture, content, service design, accessibility, safety, prioritization, or measurement. Remove decorative information that does not change a decision.

### 7. Inclusion without tokenism

Include accessibility, language, literacy, caregiving, rurality, age, and device context when evidence shows they affect experience. Do not add characteristics merely to make the persona appear diverse.

### 8. Healthcare safety

Personas may describe care-seeking and medicine behaviour but must not diagnose participants or imply that an entire segment has a condition. Highlight circumstances in which misunderstanding could cause delayed care, unsafe self-medication, privacy harm, or medicine risk.

### 9. Privacy and dignity

Personas must be composites. Remove direct identifiers and avoid combinations of details that could reveal a participant. Use respectful language and avoid deficit-based labels.

### 10. Maintainability

Record evidence sources, confidence, creation date, owner, and review trigger. Personas should be revised when new evidence contradicts them or the service context changes.

## Persona-Creation Workflow

### 1. Confirm the decision

State which decisions the persona will support, such as:

- Research recruitment
- Practitioner discovery
- Food education
- Consultation experience
- Medicine ordering
- Lab-report management
- Facility discovery
- Language and accessibility
- Safety and escalation

If the intended decision is unclear, do not create multiple elaborate personas by default.

### 2. Audit the evidence

Inventory:

- Research methods used
- Participant count and contexts
- Geography and languages
- Behaviours represented
- Populations missing
- Quality and limitations
- Contradictions
- Secondary evidence versus primary user evidence

Decide whether the evidence supports a persona, a proto-persona, a segment, or no persona yet.

### 3. Identify behavioural dimensions

Analyse differences across dimensions such as:

- Prevention-focused versus condition-management goals
- Independent versus caregiver-supported decisions
- High versus low trust in digital healthcare
- Traditional-care-first, conventional-care-first, or integrated-care behaviour
- Practitioner-led versus self-directed remedy use
- High versus low health literacy
- High versus low digital confidence
- Reliable versus limited local service access
- Online versus offline medicine purchasing
- Active health-record management versus dependence on paper or caregivers

Use only dimensions supported by the available evidence.

### 4. Cluster meaningful patterns

Group participants using shared behaviours, goals, needs, contexts, and decision factors. Do not cluster only by age, gender, location, or diagnosis.

For each cluster, record:

- Supporting participant codes or evidence
- Shared pattern
- Important variation
- Contradictory cases
- Confidence level
- Whether it is distinct enough to affect design decisions

Merge clusters that would lead to the same product decisions. Keep separate clusters only when their needs or constraints require materially different responses.

### 5. Create the persona

Include only supported and actionable information.

Required persona components:

1. Persona label and type
2. One-line behavioural summary
3. Evidence basis and confidence
4. Primary goals
5. Jobs to be done
6. Current behaviours
7. Motivations
8. Needs
9. Pain points and barriers
10. Trust and decision factors
11. Digital and health-literacy context
12. Language and accessibility needs
13. Service and geographic context
14. People who influence decisions
15. Current tools, channels, and workarounds
16. Relevant journey stages
17. Safety and privacy concerns
18. Opportunity areas stated without prescribing a final feature
19. Evidence gaps and validation questions
20. Design implications

Optional components may include a representative composite name, age range, occupation category, quotation, or photo direction only when supported, necessary, privacy-safe, and useful.

### 6. Validate the persona

Check:

- Is every important field supported by evidence?
- Does the persona represent a behavioural pattern rather than one memorable participant?
- Are contradictions visible?
- Does it lead to different design or research decisions?
- Is it free of stereotypes and decorative biography?
- Could the details identify a real participant?
- Does it overgeneralize a diagnosis, geography, or cultural group?
- Does it imply a medical conclusion unsupported by research?
- Are limitations and missing populations explicit?

### 7. Connect the persona to decisions

For each persona, state:

- Relevant product journeys
- Content and evidence needs
- Accessibility and localization needs
- Trust requirements
- Safety controls
- Research priorities
- Metrics that could reflect successful support

Do not turn the persona into automatic permission to build a feature.

## Arogyam Persona Lenses

Consider these lenses only when research supports them:

### Care orientation

- Prevention and general wellbeing
- Chronic-condition management
- Family or caregiver coordination
- Traditional-care-first, conventional-care-first, or blended care

### Trust

- Practitioner credentials
- Personal recommendations
- Government or institutional recognition
- Evidence labels
- Product authenticity and seller verification
- Data privacy

### Food behaviour

- Household food decision-maker
- Regional diet and affordability
- Ability to apply diet advice
- Need for general education versus professional dietetic review

### Medicine and remedies

- Self-directed versus practitioner-supervised use
- Online versus offline purchasing
- Understanding of dosage, interactions, authenticity, and storage
- Use of raw traditional medicinal products

### Access

- Rural, semi-urban, or urban services
- Device, bandwidth, payment, address, transport, and delivery context
- Practitioner, pharmacy, facility, and laboratory availability

### Records and diagnostics

- Lab booking behaviour
- Report understanding
- Paper versus digital storage
- Sharing with practitioners or caregivers
- Consent and privacy needs

### Safety

- Recognition of urgent symptoms
- Delayed-care risk
- Medicine interaction or contraindication risk
- Dependence on caregivers or professionals

## Evidence and Confidence Rules

Use these evidence states:

- **Research-backed:** Repeated evidence across relevant contexts with limited material contradiction
- **Emerging:** Some repeated evidence, but limited diversity or important gaps remain
- **Contradictory:** Material differences exist between contexts or participants
- **Assumption:** No adequate participant evidence
- **Unable to determine:** Available evidence cannot support a conclusion

Do not convert qualitative frequency into population prevalence. Statements such as “most Indian users” require representative quantitative evidence, not a small interview sample.

## Required Output

Produce:

1. Persona-generation purpose
2. Evidence-readiness assessment
3. Behavioural segmentation logic
4. Cluster-evidence table
5. Recommended persona count with rationale
6. Persona cards
7. Cross-persona comparison matrix
8. Shared needs and distinguishing needs
9. Contradictions and edge cases
10. Missing or underrepresented users
11. Product and UX implications
12. Research and validation gaps
13. Persona maintenance plan

## Persona Card Template

### [Persona label]

- **Type:** Research-backed persona / emerging persona / proto-persona
- **Behavioural summary:**
- **Evidence basis:**
- **Confidence:**
- **Relevant participant codes or sources:**
- **Primary goals:**
- **Jobs to be done:**
- **Current behaviours:**
- **Motivations:**
- **Needs:**
- **Pain points and barriers:**
- **Trust and decision factors:**
- **Digital-literacy context:**
- **Health-literacy context:**
- **Language and accessibility needs:**
- **Service/geographic context:**
- **Influencers and caregivers:**
- **Tools, channels, and workarounds:**
- **Relevant journey stages:**
- **Safety considerations:**
- **Privacy considerations:**
- **Opportunity areas:**
- **Design implications:**
- **Evidence gaps:**
- **Validation questions:**
- **Review trigger/date:**

## Cluster-Evidence Table

| Proposed persona/segment | Shared behavioural pattern | Supporting evidence | Important variation | Contradiction | Design distinction | Confidence |
|---|---|---|---|---|---|---|

## Cross-Persona Comparison

| Dimension | Persona A | Persona B | Persona C | Design implication |
|---|---|---|---|---|

Useful dimensions may include goals, care orientation, trust, digital confidence, health literacy, location/service access, medicine behaviour, food behaviour, caregiver involvement, records, safety, and language.

## Anti-Pattern Checklist

Do not create:

- Personas based mainly on age, gender, income, or occupation
- A fictional biography unsupported by research
- A persona for every participant
- A single “average user” hiding important differences
- An aspirational customer written to justify the product
- A persona whose quotation was invented
- A persona whose stock photo implies ethnicity, health status, or socioeconomic position without evidence
- A persona equating traditional-medicine use with low health literacy
- A persona equating older age with low digital ability
- A persona that embeds the desired feature as the user need
- A diagnosis-based persona that assumes everyone with the condition behaves the same way

## Research Integrity Rules

- Never invent participant data, quotations, demographics, behaviours, diagnoses, motivations, or pain points.
- Clearly distinguish research-backed personas from proto-personas.
- Preserve participant anonymity.
- Keep evidence traceable to participant codes or source material.
- Include contradictions and missing populations.
- Do not claim statistical prevalence from qualitative research.
- Do not use secondary research alone to describe individual motivations.
- Do not treat stakeholder opinion as user evidence.
- Do not use personas to provide medical advice or predict individual clinical behaviour.
- Do not finalize a feature solely because a persona appears to need it.

## Quality Gate

A persona is acceptable only when:

- Its purpose and decisions are clear.
- Its behavioural pattern is supported by evidence.
- Demographic details are relevant and justified.
- Needs are independent of specific features.
- Trust, context, accessibility, safety, and privacy are considered where relevant.
- Contradictions and limitations are explicit.
- The persona produces actionable distinctions.
- It cannot reasonably identify a participant.
- It includes evidence gaps and review triggers.

## Reusable Activation Prompt

> Use the `user-persona-generator` skill to create evidence-based UX personas for Arogyam from the supplied secondary and qualitative research. First assess whether the evidence supports research-backed personas, emerging personas, proto-personas, behavioural segments, or no persona yet. Cluster participants by meaningful behaviours, goals, needs, trust, decision-making, care orientation, access, literacy, language, caregiver involvement, medicine use, food behaviour, records, and safety context—not demographics alone. Keep every important attribute traceable to participant codes or verified research. Include contradictions, underrepresented groups, confidence, limitations, design implications, validation questions, and maintenance triggers. Never invent biographies, quotations, diagnoses, or demographics, and do not use personas to justify predetermined features.

