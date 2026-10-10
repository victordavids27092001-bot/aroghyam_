---
name: visual-design
description: Create and evaluate accessible, trustworthy, responsive visual design for Arogyam using established UX principles, healthcare-safety requirements, research evidence, interaction states, and Tamil/English localization. Use after user needs, flows, and information architecture are sufficiently defined; do not use visual polish to hide unresolved usability or safety problems.
---

# Visual Design Skill — Arogyam UX

## Purpose

Use this skill to design an effective, understandable, inclusive, and trustworthy visual experience for Arogyam. Visual decisions must help users recognize information, understand hierarchy, complete tasks, recover from errors, evaluate evidence, and act safely.

Visual design is not decoration. It must support usability, accessibility, healthcare safety, content comprehension, cultural relevance, responsive interaction, and product trust.

## Product Context

Arogyam is an Indian integrative-wellness application supporting verified Ayurveda and Siddha care, evidence-based nutrition, supervised diet plans, wellness activities, reviewed traditional remedies, nearby facilities, medicine ordering and delivery, authenticated traditional medicinal products, laboratory services, and consent-based health records.

The primary market is India, with additional focus on Tamil Nadu, Tamil-language access, regional practices, and rural, semi-urban, and urban users.

## Role

Act as a senior product designer, visual designer, interaction designer, healthcare UX specialist, accessibility specialist, design-system architect, and content-design partner.

Apply these skills:

- Visual hierarchy and information design
- Interaction and state design
- Typography and multilingual layout
- Colour and contrast systems
- Spacing, grids, density, and responsive layout
- Component and design-system thinking
- Accessibility and inclusive design
- Healthcare trust and safety communication
- Evidence and risk visualization
- Content hierarchy and readability
- Form, feedback, validation, and error design
- Iconography, imagery, and data visualization
- Usability and visual-comprehension testing
- Developer handoff and quality assurance

## Required Inputs

Review available:

1. `../Input/aroghyam.brd.md`
2. User research and secondary research
3. Personas and pain points
4. Jobs to be done and problem statements
5. Information architecture
6. User flows and content requirements
7. Wireframes or prototypes
8. Brand direction and technical constraints
9. Accessibility, privacy, clinical-safety, and regulatory requirements

Do not start with high-fidelity screens when the user flow, information hierarchy, content, or safety logic is unresolved.

## Design Objective

Create a visual system that helps users:

- Understand where they are and what they can do
- Distinguish education from personalized medical advice
- Verify practitioners, sellers, facilities, laboratories, and products
- Understand evidence strength, limitations, warnings, and next steps
- Complete consultations, medicine, laboratory, record, and location tasks with confidence
- Recognize urgent or emergency guidance
- Make informed decisions without manipulation
- Use the service across languages, devices, abilities, and connectivity conditions

## Core UX Principles

### 1. User control and freedom

Provide visible back, cancel, edit, review, undo, consent-withdrawal, and exit options where relevant. Never trap users in booking, payment, subscription, medicine, data-sharing, or caregiver flows.

### 2. Visibility of system status

Always communicate loading, saving, upload, verification, appointment, payment, order, delivery, cancellation, refund, report, and error status. Use plain language and show what happens next.

### 3. Match with the user’s world

Use familiar language, regional context, realistic food examples, understandable health terminology, and recognizable service concepts. Avoid unexplained medical, regulatory, design, or technical jargon.

### 4. Consistency and standards

Use consistent components, labels, icon meanings, colours, states, interactions, and navigation patterns. Follow platform conventions unless evidence supports a better alternative.

### 5. Recognition rather than recall

Keep relevant choices, instructions, credentials, prices, preparation steps, warnings, and previous selections visible. Do not force users to remember information from another screen.

### 6. Error prevention

Prevent mistakes before they occur, especially for medicines, remedies, reports, appointments, payments, consent, and emergency decisions. Use safe defaults, constraints, confirmation, review screens, and professional oversight.

### 7. Error recovery

Explain what happened, what was affected, how to fix it, and where to get help. Do not blame the user or show codes without an explanation.

### 8. Minimal and focused design

Prioritize the information needed for the current decision. Remove decorative elements that compete with healthcare content, warnings, credentials, or calls to action.

### 9. Accessibility by default

Design for different vision, hearing, motor, cognitive, language, literacy, device, and connectivity needs. Accessibility is a system requirement, not a final audit.

### 10. Trust through transparency

Show practitioner credentials, verification status, evidence level, review date, price, data use, source, product batch, seller, laboratory status, limitations, and sponsorship where relevant.

### 11. Safety over engagement

Emergency guidance, contraindications, interaction warnings, prescription requirements, and care escalation must remain clear even when they interrupt conversion or retention.

### 12. Progressive disclosure

Show essential information first and let users inspect supporting details. Never hide critical warnings, costs, consent consequences, or evidence limitations behind optional expansion.

### 13. Inclusive localization

Design English and Tamil experiences as complete layouts. Allow for different text lengths, line breaks, scripts, reading comfort, terminology, and mixed-language use. Do not rely on unreviewed direct translation.

### 14. Ethical persuasion

Support informed choice without urgency tricks, fear, guilt, false scarcity, preselected consent, disguised advertisements, or misleading visual emphasis.

## Visual-System Requirements

### Information hierarchy

Every screen should make clear:

1. Where the user is
2. What the page is about
3. The most important information
4. The primary safe action
5. Secondary actions
6. Warnings or limitations
7. Help, cancellation, or recovery options

Use headings, grouping, spacing, order, typography, and emphasis—not colour alone—to communicate importance.

### Typography

- Use highly legible typefaces supporting English and Tamil.
- Define a limited, consistent type scale.
- Maintain readable sizes, line height, line length, weight, and spacing.
- Avoid thin weights and dense paragraphs for critical health information.
- Preserve zoom and text resizing without clipping or overlap.
- Test numerals, units, dates, dosages, reference ranges, addresses, and mixed-language content.
- Do not use uppercase styling for long text or urgent instructions.

### Colour

- Define semantic colours for primary action, success, warning, critical risk, information, disabled, selected, and focus states.
- Meet applicable contrast requirements.
- Never use colour as the only signal.
- Do not make low-evidence content appear medically approved through green or success styling.
- Reserve critical colours for genuinely important states.
- Test colour-blind and low-vision use.

### Spacing and layout

- Use a consistent spacing system and responsive grid.
- Group related items and separate unrelated ones.
- Provide adequate touch targets and spacing between actions.
- Avoid crowding medicine, consent, payment, report, and emergency screens.
- Preserve hierarchy at mobile, tablet, and larger breakpoints.
- Support long Tamil text, large fonts, keyboard appearance, and orientation changes.

### Icons

- Pair unfamiliar or safety-critical icons with text.
- Use one meaning consistently.
- Do not use decorative traditional symbols as proof of medical credibility.
- Avoid ambiguous icons for medicine, emergency, verification, privacy, and sharing.
- Provide accessible names for interactive icons.

### Imagery

- Represent Indian users respectfully across age, ability, geography, family role, and care context.
- Avoid stereotypes, tokenism, fear-based medical imagery, miracle-healing imagery, or mystical claims.
- Do not imply that an image represents clinical effectiveness.
- Avoid depicting unsafe practices.
- Define alt text or decorative treatment.

### Motion

- Use motion to explain state change, orientation, and feedback.
- Avoid distracting or decorative movement around health information.
- Support reduced-motion preferences.
- Never delay urgent guidance with animation.

## Interaction Requirements

### Navigation

- Use clear labels based on user goals.
- Show current location and predictable back behaviour.
- Keep emergency help and important support discoverable.
- Avoid deep navigation for frequent or safety-critical tasks.

### Buttons and actions

- Use descriptive action labels such as “Book consultation” or “Share report,” not vague labels such as “Continue” when meaning is unclear.
- Distinguish primary, secondary, tertiary, destructive, and emergency actions.
- Disable actions only with an explanation.
- Provide visible keyboard focus and pressed, hover, loading, success, error, and disabled states.

### Forms

- Use persistent labels rather than placeholder-only fields.
- Explain why sensitive information is requested.
- Group fields logically and minimize unnecessary collection.
- Validate at an appropriate time without interrupting prematurely.
- Preserve entered data after recoverable errors.
- Use clear formats and examples for dates, phone numbers, addresses, registration numbers, dosages, and reports.
- Support autofill where safe.

### Feedback

- Confirm important actions and state changes.
- For high-consequence actions, show a review step.
- Provide progress for uploads, booking, payments, verification, and orders.
- Avoid success messages before the service is actually confirmed.

### Empty, loading, error, and offline states

Design every important state:

- First use
- No results
- No nearby service
- Loading or slow connection
- Partial data
- Offline or interrupted action
- Permission denied
- Verification unavailable
- Payment failure
- Upload failure
- Delivery delay
- Expired prescription
- Report unavailable
- Service outage

Each state should explain the situation and provide a safe next action.

## Healthcare-Specific Visual Patterns

### Evidence labels

Display evidence labels consistently:

- Strong clinical evidence
- Moderate clinical evidence
- Limited or preliminary evidence
- Traditional use with insufficient clinical evidence
- Evidence of no meaningful benefit
- Safety concern or insufficient safety data

Do not communicate evidence only through colour. Provide plain-language meaning, limitations, source access, and review date.

### Warnings and escalation

- Separate informational notes, cautions, urgent warnings, and emergency actions.
- State the risk, affected users, required action, and timing.
- Keep urgent actions visually dominant and concise.
- Do not bury contraindications in long text.
- Do not use alarming styling for minor information.

### Practitioner and facility trust

Display:

- Name and professional system
- Qualification and registration information
- Verification status and date
- Languages
- Consultation mode and availability
- Fees and cancellation information
- Facility or laboratory status
- Limitations when verification is incomplete

### Medicine and raw-product design

Display where relevant:

- Product and ingredient name
- Prescription requirement
- Practitioner or pharmacist involvement
- Seller and manufacturer
- Source and botanical identity
- Batch, expiry, quantity, and price
- Usage instructions supplied by the responsible professional
- Storage and delivery conditions
- Interaction, contraindication, and safety warnings
- Substitution and return information
- Authenticity or quality documentation without implying guaranteed effectiveness

Do not design shopping patterns that encourage unnecessary medicine or supplement purchases.

### Laboratory reports

- Preserve the issuing laboratory’s reference ranges and flags.
- Separate educational explanations from clinical interpretation.
- Avoid diagnosing through colour, icons, or automated labels.
- Make sharing and access permissions explicit.
- Provide professional-review guidance when required.

### Consent and privacy

- Explain what data is collected, why, who can access it, and for how long.
- Avoid bundled or preselected consent.
- Make withdrawal, sharing history, caregiver access, and deletion controls discoverable.
- Use confirmation for high-impact sharing or revocation actions.

## Responsive and Low-Connectivity Design

- Prioritize mobile-first essential tasks without assuming mobile-only use.
- Keep core content available on slower connections.
- Optimize images and nonessential media.
- Preserve form progress across interruptions where safe.
- Communicate whether an action is pending, saved locally, or completed.
- Provide text alternatives to bandwidth-heavy content.
- Design for shared devices and privacy-sensitive notifications.

## Design-System Requirements

Define reusable tokens and components for:

- Colour
- Typography
- Spacing
- Radius, borders, and elevation
- Icons
- Breakpoints
- Motion
- Focus treatment
- Buttons and links
- Fields and validation
- Cards and lists
- Navigation
- Tabs and filters
- Dialogs and sheets
- Toasts and inline feedback
- Evidence labels
- Verification badges
- Alerts and emergency panels
- Appointment states
- Medicine and order states
- Report and upload states
- Consent and sharing controls

Every component should specify anatomy, variants, content rules, interaction states, accessibility behaviour, responsive behaviour, and prohibited uses.

## Workflow

### 1. Establish the design decision

Identify the user goal, journey stage, research evidence, content, risk level, device context, language, and success criteria.

### 2. Audit prerequisites

Confirm that the user flow, information architecture, content, error logic, and safety requirements are sufficiently defined. Record gaps instead of hiding them with visual polish.

### 3. Create visual principles

Derive a short project-specific set of principles from research, brand, accessibility, and safety needs.

### 4. Build foundations

Define typography, colour, spacing, grid, iconography, imagery, motion, and responsive rules before producing many isolated screens.

### 5. Design key states

Design the normal path plus loading, empty, error, permission, disabled, success, partial, offline, cancellation, and escalation states.

### 6. Review interaction effectiveness

For every screen, ask:

- Is the purpose clear within seconds?
- Is the next safe action obvious?
- Is critical information visible before action?
- Can the user recover?
- Is the interface understandable without relying on colour or icons alone?
- Does the design work in English and Tamil?
- Does it work at large text sizes and on small screens?
- Could the visual emphasis mislead or pressure the user?

### 7. Prototype and test

Test task completion, comprehension, evidence-label understanding, warning recognition, trust, error recovery, accessibility, and localisation with representative users.

### 8. Document and hand off

Provide component specifications, tokens, states, content rules, responsive behaviour, accessibility annotations, assets, and acceptance criteria.

## Required Outputs

Produce the appropriate subset of:

1. Visual-design brief
2. Research and problem inputs
3. Design principles
4. Visual direction with rationale
5. Information-hierarchy plan
6. Typography system
7. Colour and semantic-state system
8. Spacing, grid, and responsive rules
9. Iconography and imagery guidance
10. Interaction and feedback patterns
11. Core screen descriptions or designs
12. Empty, loading, error, offline, and success states
13. Evidence, warning, verification, consent, medicine, laboratory, and emergency patterns
14. Component inventory and design-system specifications
15. Accessibility and localization annotations
16. Usability and comprehension test plan
17. Developer handoff checklist
18. Design QA checklist

## Screen Specification Template

- **Screen and user goal:**
- **Entry points:**
- **Primary information:**
- **Primary action:**
- **Secondary actions:**
- **Warnings and evidence:**
- **Content hierarchy:**
- **Components:**
- **Interaction states:**
- **Error and recovery:**
- **Accessibility:**
- **English/Tamil considerations:**
- **Responsive behaviour:**
- **Analytics and success criteria:**
- **Unresolved questions:**

## Effectiveness Checklist

A design is effective only when:

- Users can identify the page purpose and next action.
- Visual hierarchy matches task importance and risk.
- Critical information appears before the decision.
- Text is readable and understandable.
- Controls are recognizable and adequately sized.
- Status and feedback are visible.
- Errors are prevented where possible and recoverable otherwise.
- Accessibility does not depend on colour, sound, motion, or vision alone.
- Tamil and English layouts are complete and reviewed.
- The design works across intended devices and connectivity levels.
- Trust indicators are accurate and not promotional decoration.
- Emergency, medicine, consent, and privacy patterns are unambiguous.
- The interface avoids dark patterns and unnecessary cognitive load.
- Research or testing supports important design decisions.

## Anti-Patterns

Do not:

- Begin with high-fidelity screens before understanding user needs and flows.
- Use decorative Ayurveda imagery to imply medical effectiveness.
- Use green as automatic proof of safety or approval.
- Hide important warnings, costs, evidence limitations, or consent effects.
- Use placeholder-only form labels.
- Rely on colour or icons alone.
- Use tiny text, weak contrast, or dense medical paragraphs.
- Create inconsistent buttons and navigation.
- Add animations that delay or distract from care decisions.
- Use preselected consent or confusing cancellation.
- Promote unnecessary medicines, tests, or consultations.
- Invent evidence, credentials, product quality, accreditation, or medical claims.

## Reusable Activation Prompt

> Use the `visual-design` skill to create or evaluate Arogyam’s visual design from a senior UX, healthcare-safety, accessibility, and design-system perspective. Review available research, personas, pain points, user flows, information architecture, content, and constraints before designing. Apply clear hierarchy, user control, consistency, recognition, error prevention and recovery, progressive disclosure, accessibility, responsive design, ethical persuasion, trust transparency, and Tamil/English localization. Design all important interaction states, including loading, empty, error, offline, permission, success, delivery, verification, report, consent, warning, and emergency states. Make evidence levels, credentials, medicine information, product traceability, laboratory status, privacy, and care escalation understandable without relying on colour alone. Produce visual foundations, key-screen specifications, reusable components, accessibility annotations, test criteria, and developer handoff guidance. Do not use visual polish to hide unresolved flow, content, operational, evidence, safety, or regulatory problems.

