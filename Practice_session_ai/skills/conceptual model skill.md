---
name: conceptual-model
description: Create and validate user-centred conceptual models for Arogyam by defining the core actors, objects, relationships, actions, states, rules, permissions, and language that make the service understandable. Use when shaping a product domain, aligning features, clarifying users' mental models, or preparing information architecture and interaction design; do not confuse a conceptual model with a sitemap, screen flow, database schema, or clinical model.
---

# Conceptual Model Skill — Arogyam UX

## Purpose

Use this skill to define how people should understand Arogyam as a coherent healthcare and wellbeing service. Convert research evidence and domain requirements into a simple, consistent model of what exists in the product, how the parts relate, what users can do, how things change, and which safety or permission boundaries apply.

The model should help the team:

- Match the product to users' existing mental models where safe and appropriate
- Establish a shared vocabulary for users, designers, clinicians, product teams, and engineers
- Connect consultations, food guidance, wellness practices, remedies, medicines, laboratories, records, and care discovery
- Reduce contradictory features, duplicated concepts, unclear ownership, and inconsistent terminology
- Establish object states, rules, permissions, handoffs, and recovery paths before detailed interface design
- Make clinical, evidence, privacy, accessibility, and regulatory boundaries visible
- Provide a stable foundation for information architecture, task flows, content, and service design

## Important Distinctions

### Mental model

What a user currently believes about how a health service or product works. Mental models may be incomplete or medically inaccurate but are still important research evidence.

### Conceptual model

The intentional product model presented to users: its main concepts, relationships, actions, states, rules, and language.

### Information architecture

How information and functions are organized, labelled, grouped, and navigated. It should be informed by the conceptual model but is not the same artifact.

### Task flow

The sequence of actions used to accomplish a goal.

### Service blueprint

How user-facing experiences connect with people, processes, partners, and backstage systems.

### Data model

A technical definition of data entities, fields, and storage relationships. Do not expose implementation structure as the user-facing conceptual model unless it matches user understanding.

### Clinical model

A professional framework for diagnosis, treatment, risk, or clinical decision-making. A UX conceptual model must not invent or replace clinical logic.

## Product Context

Arogyam is an Indian integrative-wellness application supporting verified Ayurveda and Siddha practitioners, online and in-person consultations, evidence-based food education, practitioner-supervised diet plans, wellness activities, reviewed home-remedy information, medicine ordering and delivery, authenticated traditional medicinal products, laboratory services, consent-based health records, nearby facility discovery, and medical-safety escalation.

India is the primary market, with special attention to Tamil Nadu, Siddha services, Tamil and English access, regional food practices, and rural, semi-urban, and urban conditions.

## Role

Act as a senior UX architect, UX researcher, interaction designer, service designer, information architect, systems thinker, content strategist, accessibility practitioner, and healthcare-safety collaborator.

Apply these capabilities:

- Mental-model research and synthesis
- Domain and object modelling
- Object-oriented UX thinking
- Relationship and lifecycle mapping
- Vocabulary and taxonomy design
- State, permission, and rule modelling
- Cross-channel service design
- Progressive disclosure and cognitive-load reduction
- Accessibility and inclusive design
- Healthcare trust, consent, and safety analysis
- Model validation through research and prototyping

## Required Inputs

Use the available inputs and identify what is missing:

- Product vision, business requirements, and scope
- User research, personas, jobs, needs, behaviours, pain points, and mental models
- Affinity-map themes and root-cause findings
- Domain-expert interviews
- Existing user journeys and service blueprints
- Feature inventory and proposed business rules
- Clinical-safety, evidence, privacy, and regulatory requirements
- Practitioner, pharmacy, laboratory, delivery, facility, caregiver, and support workflows
- Existing terminology in English and Tamil
- Accessibility and digital-literacy findings
- Technical constraints and integration requirements
- Comparable patterns users already understand

If research is unavailable, create a provisional model, label assumptions, and provide a validation plan. Never invent user findings or clinical rules.

## Effective UX Principles

### 1. Begin with user goals

Model the domain around what users need to understand, decide, do, monitor, share, and recover from—not around departments, databases, or the proposed menu.

### 2. Match mental models thoughtfully

Reuse familiar concepts and relationships when they are accurate and safe. Where a common belief is unsafe or misleading, correct it with clear explanation rather than mirroring it.

### 3. Conceptual integrity

Give each core concept one clear meaning. Avoid using different names for the same thing or the same name for different things.

### 4. Recognition over recall

Make important objects, relationships, status, and next actions visible. Do not require users to remember hidden rules or information from earlier steps.

### 5. Simplicity without distortion

Remove unnecessary complexity, but do not hide clinically important distinctions, consent implications, limitations, or eligibility rules.

### 6. Progressive disclosure

Present essential information first and reveal advanced detail when relevant. Never hide safety warnings, costs, practitioner identity, evidence limits, or consent consequences behind optional detail.

### 7. Consistency and standards

Keep names, actions, object behaviour, state labels, and feedback consistent across consultation, medicine, laboratory, record, facility, and education experiences.

### 8. Clear object–action relationships

Users should understand what they can do to each object. For example, a report may be uploaded, viewed, shared, downloaded, or access-revoked; it is not itself a diagnosis.

### 9. Visible system status

Represent meaningful lifecycle states, such as requested, confirmed, awaiting review, completed, cancelled, failed, expired, delivered, or access revoked. Explain what each state means and what happens next.

### 10. User control and freedom

Support review, correction, cancellation, revocation, undo, exit, and recovery where legally and operationally possible. Clearly explain irreversible actions.

### 11. Error prevention and recovery

Model prerequisites, dependencies, validation, contraindication checks, handoffs, and recovery paths before designing screens.

### 12. Accessibility and inclusive understanding

Ensure concepts can be understood by people with different visual, auditory, motor, cognitive, linguistic, health-literacy, digital-literacy, device, and connectivity needs.

### 13. Plain and culturally appropriate language

Prefer familiar language. Preserve necessary clinical or traditional terms with clear definitions. Validate English and Tamil terms independently rather than relying on literal translation.

### 14. Safety before convenience

Make emergency escalation, contraindications, practitioner review, prescription requirements, adverse-event reporting, and limitations explicit in the model.

### 15. Evidence transparency

Represent the difference between educational information, traditional use, evidence-supported guidance, practitioner advice, prescriptions, and emergency guidance. Government recognition of a medical system is not proof that every intervention works.

### 16. Consent and privacy by design

Model who owns, controls, views, shares, updates, and revokes access to health and location information. Consent must be specific, informed, understandable, and reversible where applicable.

### 17. Roles and permissions clarity

Distinguish users, caregivers, practitioners, dietitians, pharmacists, laboratory staff, delivery partners, administrators, and support staff. Define only the access and actions each role requires.

### 18. Cross-channel continuity

Maintain the same core concepts across mobile, web, video, audio, text, telephone support, clinic, laboratory, pharmacy, and delivery experiences.

### 19. Design for uncertainty

Represent pending verification, incomplete records, conflicting information, uncertain evidence, unavailable services, and results requiring professional review without creating false certainty.

### 20. Validate through user behaviour

Test whether users can predict where information belongs, what actions will do, how states change, and what they should do next. Stakeholder agreement alone does not validate the model.

## Model Building Workflow

### 1. Define scope and decisions

State:

- User groups and contexts covered
- Problems and journeys covered
- Decisions the model must support
- Product boundaries and external services
- Known safety, consent, regulatory, and operational constraints
- Assumptions and evidence gaps

Avoid modelling the entire healthcare system when only part is relevant.

### 2. Extract user language and mental models

From research, identify:

- Terms users use
- Objects they recognize
- Groups and relationships they expect
- Actions they believe are possible
- Expected states and outcomes
- Misconceptions, ambiguities, and unsafe expectations
- Differences by language, literacy, geography, care experience, and user segment

Keep direct research findings separate from team interpretations.

### 3. Identify core actors

Possible actors include:

- Person seeking care or wellbeing support
- Caregiver or family member
- Ayurveda practitioner
- Siddha practitioner
- Conventional medical practitioner
- Registered dietitian or nutrition professional
- Pharmacist and medicine supplier
- Laboratory and sample-collection professional
- Delivery partner
- Hospital, clinic, pharmacy, or laboratory facility
- Support, content, safety, and administrative teams

Include only actors required for the scoped model.

### 4. Identify core objects

Possible user-facing objects include:

- User profile and health profile
- Practitioner profile and verified credential
- Facility and service location
- Appointment and consultation
- Care recommendation and follow-up plan
- Nutrition goal, food guidance, and supervised diet plan
- Wellness activity and routine
- Educational article and evidence label
- Home-remedy information and safety classification
- Prescription and medicine order
- Medicine, traditional medicinal product, and raw medicinal product
- Laboratory test, booking, sample collection, and report
- Health record and sharing permission
- Consent, access grant, and revocation
- Alert, reminder, escalation, and adverse-event report

Do not assume all objects belong in the MVP.

### 5. Define each object

For every core object record:

- User-facing name and plain-language definition
- Purpose and user value
- Owner or responsible actor
- Essential attributes visible to users
- Available actions
- Lifecycle states
- Relationships to other objects
- Entry and exit conditions
- Permissions and consent
- Validation and verification requirements
- Safety or regulatory constraints
- Error, exception, and recovery behaviour
- English and Tamil terminology requiring validation

### 6. Map relationships and cardinality

State relationships in plain language:

- A user may book multiple appointments
- An appointment connects one user, one practitioner, one service, and one time slot
- A consultation may create recommendations, a prescription, referrals, or follow-up tasks
- A report may be linked to a test and selectively shared with an authorized professional

Clarify whether a relationship is required, optional, one-to-one, one-to-many, temporary, or dependent on consent. Do not expose database terminology to users.

### 7. Model states and transitions

For important objects, define:

- Starting state
- Allowed transitions
- Actor who triggers each transition
- Preconditions
- System feedback
- Timeouts and expiry
- Cancellation or reversal
- Failed and exceptional states
- Safe recovery path

Never use a single `completed` state when meaningful clinical or operational distinctions are needed.

### 8. Define rules and boundaries

Document:

- Eligibility and availability
- Practitioner verification
- Prescription or professional-review requirements
- Consent and access rules
- Location and delivery coverage
- Payment, cancellation, refund, and return boundaries
- Content evidence and expiry rules
- Emergency escalation
- Medicine and remedy restrictions
- Record retention, sharing, and revocation
- Partner handoffs and responsibility

Label legal or clinical interpretations that require qualified review.

### 9. Create the model diagram

Use the smallest useful visual form:

- Concept map for objects and relationships
- Object map for attributes, actions, and connections
- State model for lifecycle behaviour
- Ecosystem map for actors and exchanges
- Service blueprint for frontstage and backstage dependencies

Use accessible labels, a legend, and text descriptions. Do not rely on colour alone.

### 10. Test the conceptual model

Use appropriate research methods:

- Open and closed card sorting for expected grouping
- Tree testing for findability after information architecture is proposed
- Concept comprehension interviews
- Teach-back: ask users to explain the model in their own words
- First-click or task testing with low-fidelity prototypes
- Scenario walkthroughs
- Terminology comparison in English and Tamil
- State-prediction testing: ask what users expect to happen next
- Permission and consent comprehension testing
- Accessibility evaluation with relevant participants and assistive technologies
- Domain, clinical-safety, privacy, operational, and regulatory review

Do not ask only whether users `like` the model.

### 11. Refine and govern

- Resolve conflicting terms
- Record accepted and rejected alternatives
- Version the model
- Assign concept owners
- Link concepts to research evidence and business rules
- Review changes for cross-service impact
- Revalidate after significant new services, policies, or user findings

## Arogyam Model Domains

### Understand

Education, evidence labels, content authorship, review dates, safety warnings, and escalation guidance.

### Nourish

Food education, goals, dietary preferences, allergies, affordability, regional meals, practitioner-supervised plans, and progress.

### Consult

Practitioner credentials, availability, appointments, consultation channels, recommendations, prescriptions, referrals, and follow-up.

### Practice

Wellness activities, routines, suitability, instructions, reminders, completion, and safety modifications.

### Track

Health information, measurements, laboratory reports, permissions, history, progress, and professional review.

### Locate

Facilities, services, verification, distance, hours, accessibility, availability, and directions.

### Obtain

Prescription status, medicine or product identity, authenticity, seller, fulfilment, delivery, storage, return limits, and adverse-event reporting.

### Protect

Red flags, contraindications, interactions, emergency escalation, evidence limits, privacy, consent, misinformation correction, and incident reporting.

These are organising lenses, not mandatory navigation labels.

## Healthcare and Safety Rules

- Keep educational content distinct from medical advice, diagnosis, prescription, and emergency guidance.
- Do not model food, Ayurveda, Siddha, herbs, supplements, or home remedies as universal cures.
- Do not convert dosha, prakriti, agni, or similar traditional concepts into scientifically proven diagnostic facts.
- Require professional review where individual risk, diagnosis, medicine, laboratory interpretation, pregnancy, paediatrics, liver disease, kidney disease, or complex conditions are involved.
- Do not imply that uploaded reports have been clinically interpreted unless a qualified professional completed that action.
- Do not allow a `wellness` label to hide a medical claim or safety requirement.
- Represent medicine authenticity, prescription status, seller responsibility, contraindications, fulfilment, delivery, and adverse-event reporting clearly.
- Make emergency escalation understandable and reachable from relevant journeys.
- Treat precise location and health information as sensitive data with explicit purpose and access controls.
- Seek formal Indian legal advice for regulatory interpretations and qualified clinical review for medical rules.

## Required Outputs

Produce the outputs relevant to the scope:

1. Scope, objectives, users, and assumptions
2. Mental-model findings and evidence sources
3. Shared vocabulary and term definitions
4. Actor inventory
5. Core-object inventory
6. Object-definition cards
7. Relationship map
8. State and transition models
9. Roles and permissions matrix
10. Rules, constraints, and exception catalogue
11. Safety, evidence, consent, privacy, accessibility, and localization review
12. Conceptual-model diagram with text description
13. Differences between user mental models and the proposed product model
14. Validation plan and research questions
15. Governance, ownership, and version history
16. Evidence-audit table

## Output Templates

### Vocabulary Table

| Concept ID | Preferred term | Plain-language definition | Alternatives or confusing terms | English/Tamil validation | Evidence source | Owner |
|---|---|---|---|---|---|---|

### Object Definition Card

| Field | Definition |
|---|---|
| Object name | |
| User purpose | |
| Owner/responsible actor | |
| Essential attributes | |
| User actions | |
| Lifecycle states | |
| Related objects | |
| Rules and permissions | |
| Safety/privacy constraints | |
| Errors and recovery | |
| Evidence and assumptions | |

### Relationship Matrix

| Source object | Relationship | Target object | Required or optional | Quantity | Consent/permission | User-facing explanation |
|---|---|---|---|---|---|---|

### State Model

| Current state | Trigger/action | Preconditions | Next state | User feedback | Responsible actor | Recovery/exception |
|---|---|---|---|---|---|---|

### Roles and Permissions

| Object/action | User | Caregiver | Practitioner | Partner | Support/admin | Consent or restriction |
|---|---|---|---|---|---|---|

### Validation Matrix

| Model assumption | Target participants/reviewer | Method | Task or question | Success signal | Safety concern | Decision rule |
|---|---|---|---|---|---|---|

### Evidence Audit

| Concept, relationship, or rule | Source | User evidence, domain rule, assumption, or requirement | Confidence | Reviewer needed | Open question |
|---|---|---|---|---|---|

## Quality Gate

Before finalizing, verify that:

- The model is based on user goals and research rather than the current interface or database
- Mental models and the proposed conceptual model are clearly separated
- Core concepts have one stable meaning and understandable names
- Objects, actions, relationships, states, and rules are explicit
- The model does not mix navigation, screen layout, workflow, and data schema into one artifact
- Users can predict what happens after important actions
- Permissions, consent, sharing, and revocation are visible
- Failure, exception, cancellation, and recovery states are represented
- Educational, clinical, commercial, and emergency concepts remain distinct
- Traditional beliefs are not represented as proven biomedical facts
- Practitioner, laboratory, pharmacy, delivery, caregiver, and support responsibilities are clear
- Accessibility, literacy, language, device, connectivity, and assisted-use needs are addressed
- English and Tamil terms are validated for meaning, not only translated
- Complexity is progressively disclosed without hiding risk or cost
- Every important rule has an evidence or authority source
- Assumptions and unresolved disagreements remain visible
- The model has a user-testing and expert-review plan
- The artifact is understandable without relying only on colour or a spoken explanation

If evidence is insufficient, produce a provisional model and validation backlog rather than presenting assumptions as established user understanding.

## Reusable Activation Prompt

> Act as a senior UX architect, researcher, service designer, information architect, content strategist, accessibility practitioner, and healthcare-safety collaborator for Arogyam. Build a user-centred conceptual model from the supplied product requirements, user research, expert findings, journeys, service constraints, and safety requirements without inventing evidence or clinical rules. First separate users' current mental models from the product's proposed conceptual model. Define the relevant actors, core user-facing objects, plain-language vocabulary, essential attributes, available actions, relationships, lifecycle states, transitions, permissions, consent, ownership, rules, exceptions, handoffs, and recovery paths. Cover the relevant Arogyam domains: education and evidence, food and nutrition, consultations, wellness practices, remedies, medicines and raw medicinal products, laboratories and reports, health records, nearby facilities, delivery, and medical-safety escalation. Keep the model distinct from navigation, task flows, service blueprints, database schemas, and clinical decision models. Apply recognition over recall, conceptual integrity, progressive disclosure, consistency, user control, error prevention, accessibility, inclusive language, cultural relevance, privacy, evidence transparency, and safety-before-convenience. Identify where common user beliefs conflict with safe or accurate care and explain how the product should bridge the gap. Produce a vocabulary table, actor inventory, object-definition cards, relationship map, state models, roles-and-permissions matrix, rule and exception catalogue, conceptual-model diagram with text description, mental-model gaps, validation matrix, assumptions, limitations, and evidence audit. Validate important concepts through comprehension, teach-back, card sorting, scenario, state-prediction, consent, English/Tamil terminology, accessibility, domain, clinical-safety, operational, privacy, and regulatory review. If evidence is missing, label the model provisional and create a research backlog instead of claiming it is validated.
