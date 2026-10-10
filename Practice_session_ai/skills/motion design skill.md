---
name: motion-design
description: Design and evaluate purposeful, accessible motion and interaction feedback for Arogyam, including transitions, microinteractions, loading, progress, success, error, order, report, consent, and safety states. Use after user flows and visual foundations exist; do not use decorative animation that delays tasks, hides status, harms accessibility, or competes with urgent healthcare information.
---

# Motion Design Skill — Arogyam UX

## Purpose

Use this skill to create motion that improves orientation, feedback, continuity, comprehension, and confidence while users interact with Arogyam.

Motion must have a user-experience purpose. It should explain what changed, confirm an action, connect related states, guide attention, communicate progress, or help users recover. If removing an animation does not reduce understanding, feedback, orientation, or usability, the animation may be unnecessary.

## Product Context

Arogyam is an Indian integrative-wellness application supporting verified Ayurveda and Siddha care, food and nutrition education, supervised diet plans, wellness activities, reviewed traditional remedies, nearby facilities, medicine ordering and delivery, authenticated traditional medicinal products, laboratory services, and consent-based health records.

The primary market is India, with additional focus on Tamil Nadu, Tamil-language access, accessibility, shared devices, low-bandwidth environments, and rural, semi-urban, and urban users.

## Role

Act as a senior motion designer, interaction designer, product designer, accessibility specialist, healthcare UX specialist, and front-end motion-system partner.

Apply these capabilities:

- Interaction feedback design
- State-transition design
- Spatial continuity and orientation
- Microinteraction design
- Timing, easing, choreography, and sequencing
- Gesture and direct-manipulation feedback
- Loading, progress, success, and error communication
- Reduced-motion and vestibular accessibility
- Responsive and cross-device motion
- Performance-aware motion
- Motion tokens and design-system documentation
- Prototype design and usability testing
- Developer handoff and implementation QA

## Required Inputs

Review available:

1. `../Input/aroghyam.brd.md`
2. User research, personas, and pain points
3. User flows and information architecture
4. Wireframes and visual designs
5. `visual design skill.md` outputs
6. Component states and technical constraints
7. Accessibility, performance, privacy, and healthcare-safety requirements

Do not add motion to compensate for unclear hierarchy, confusing content, missing feedback, incomplete states, or a broken user flow.

## Motion Objectives

Use motion to help users:

- Understand cause and effect
- See that an action was received
- Recognize whether a task is pending, completed, failed, or cancelled
- Maintain orientation when moving between screens or layers
- Understand relationships between elements
- Notice an important change without being startled
- Follow multi-step consultation, payment, medicine, laboratory, report, and consent journeys
- Recover from interruptions or errors
- Use the interface comfortably with reduced-motion preferences

## Core UX Principles

### 1. Purpose before decoration

Every motion pattern must have a stated purpose: feedback, orientation, continuity, hierarchy, status, progress, error prevention, or comprehension.

### 2. Immediate feedback

Respond promptly to user input. Buttons, controls, uploads, payments, bookings, and form submissions should acknowledge interaction without falsely implying completion.

### 3. Honest status

Motion must reflect the real system state. Do not show success before confirmation, continuous progress without evidence, or looping activity that conceals failure.

### 4. Spatial continuity

Transitions should help users understand where content came from, where it went, and how screens or layers relate. Avoid arbitrary movement that creates disorientation.

### 5. Consistency

Use consistent motion for similar components and state changes. The same transition should not mean success in one context and warning in another.

### 6. Restraint

Keep motion subtle and task-focused. Healthcare content, evidence, warnings, credentials, consent, and emergency actions must remain visually dominant.

### 7. User control

Allow users to pause, stop, dismiss, skip, or reduce nonessential motion where relevant. Never make animation the only way to access or understand information.

### 8. Accessibility by default

Respect reduced-motion settings. Avoid large unexpected movement, repeated zooming, strong parallax, rapid flashing, uncontrolled autoplay, or effects that can cause vestibular discomfort or seizure risk.

### 9. Performance is usability

Motion must not block input, create lag, drain excessive battery, consume unnecessary bandwidth, or make low-end devices feel broken.

### 10. Safety over delight

Do not delay or soften urgent-care instructions, medication warnings, contraindications, privacy consequences, or error recovery for the sake of animation.

### 11. Progressive disclosure

Use motion to reveal supporting information without hiding critical information. Essential warnings, costs, consent consequences, and evidence limitations must be available immediately.

### 12. Inclusive localization

Motion must work with longer Tamil and English content, large text, right-sized containers, screen rotation, dynamic content, and different reading speeds.

## Motion Categories

### Feedback motion

Communicates that the interface received an action.

Examples:

- Button press state
- Toggle change
- Selected filter
- Saved item
- Copied information

Feedback must be paired with persistent state, text, icon, or accessible announcement when needed.

### State-change motion

Explains changes such as expanded content, selected tabs, completed steps, updated appointment status, or changed consent.

### Navigation motion

Maintains orientation between screens, detail views, sheets, dialogs, and nested levels. Direction should match the information architecture.

### Progress motion

Shows that work is occurring during uploads, payments, booking, identity checks, order processing, or report retrieval.

Use determinate progress only when meaningful progress can be measured. Use indeterminate motion honestly and provide time expectations or alternatives when known.

### Success and confirmation motion

May reinforce a confirmed completion, but must not be the only confirmation. Show the completed action, reference information, and next step.

### Error and recovery motion

Draw attention without shaming or startling. Focus the affected area, explain the issue, preserve entered data where safe, and show how to recover.

### Educational motion

Use only when animation materially improves understanding of a wellness activity, process, or concept. Provide controls, captions or instructions, and a static alternative.

## Healthcare Interaction Patterns

### Practitioner booking

- Acknowledge time selection immediately.
- Distinguish tentative selection from confirmed booking.
- Show payment and practitioner confirmation as separate states when applicable.
- Do not celebrate before the appointment is actually confirmed.

### Consultation connection

- Communicate connecting, waiting, connected, interrupted, reconnecting, and ended states.
- Provide a static status message and clear alternative when video or audio fails.
- Do not use distracting movement during clinical conversation.

### Medicine orders

- Represent stages such as prescription review, accepted, preparing, dispatched, delayed, delivered, cancelled, or refunded.
- Never animate progress beyond confirmed operational status.
- Highlight substitution, storage, expiry, prescription, or delivery problems with clear text and action.

### Traditional raw products

- Motion may reveal traceability details but must not make authenticity or effectiveness appear guaranteed.
- Critical source, batch, identity, expiry, and safety information must not depend on animation.

### Laboratory tests and reports

- Show booking, sample collection, processing, report availability, upload, and sharing states honestly.
- Do not animate a result in a way that implies diagnosis.
- Avoid dramatic red/green result reveals.

### Health-record upload and sharing

- Show upload progress, scanning, save, access, and sharing status.
- Confirm who received access and for how long.
- Provide clear recovery from upload, permission, or sharing failure.

### Consent and caregiver access

- Make permission changes visible and persistent.
- Do not use playful animation for serious data-sharing consequences.
- Confirm revocation without implying previously downloaded data was erased unless verified.

### Warnings and emergency escalation

- Present urgent guidance immediately; do not wait for an entrance animation.
- Avoid pulsing, flashing, shaking, or looping effects that increase distress.
- Use stable hierarchy, concise text, accessible colour, and an obvious action.
- Motion may focus attention once, gently, without delaying action.

## Accessibility Requirements

### Reduced motion

Respect the operating system or browser reduced-motion preference.

For reduced motion:

- Replace spatial travel with instant changes or short fades when appropriate.
- Remove parallax, zoom, bounce, rotation, and large-scale movement.
- Keep status and hierarchy understandable without animation.
- Ensure no information disappears with motion disabled.

### Flashing and repetitive effects

- Avoid rapid flashing or high-contrast flicker.
- Avoid indefinite pulsing on warnings or calls to action.
- Do not autoplay repeated decorative animation.

### Cognitive accessibility

- Keep timing predictable.
- Avoid simultaneous movement in several regions.
- Do not move controls while users are trying to select them.
- Allow additional time where motion precedes a decision.

### Screen readers and assistive technology

- Motion does not replace programmatic state.
- Announce important asynchronous status changes appropriately.
- Manage focus after dialogs, navigation, errors, and successful actions.
- Avoid repeated announcements caused by decorative state changes.

## Timing and Easing Principles

- Use shorter durations for small, frequent feedback.
- Use slightly longer durations for larger spatial transitions when orientation benefits.
- Avoid fixed universal timings; test by distance, device, frequency, and user task.
- Use easing that makes movement feel responsive and settled rather than mechanical or bouncy.
- Do not delay direct manipulation or input response.
- Avoid long sequences before users can continue.
- Ensure repeated actions do not accumulate animation queues.

Document timing and easing as tokens rather than inventing new values for each screen.

## Gesture and Direct-Manipulation Rules

- Provide visible affordances and alternatives to gestures.
- Keep objects connected to user movement where appropriate.
- Use boundaries and resistance without trapping users.
- Confirm destructive or high-impact gestures.
- Do not rely on swipe alone for delete, consent, emergency, or medicine actions.
- Support keyboard and assistive-technology equivalents.

## Loading and Perceived Performance

- Prefer real content appearing progressively over decorative loaders when technically possible.
- Use skeletons only when they represent the expected layout and do not mimic confirmed data.
- Avoid fake progress bars.
- Preserve context during refresh.
- Explain long or blocked operations.
- Provide cancel, retry, background continuation, or alternative paths when appropriate.

## Motion-System Requirements

Define reusable tokens for:

- Duration: instant, fast, standard, deliberate
- Easing: enter, exit, standard, emphasized
- Distance: small, medium, large
- Opacity transitions
- Scale limits
- Stagger limits
- Reduced-motion alternatives
- Loading and progress behaviour

Define reusable patterns for:

- Buttons and controls
- Navigation and back transitions
- Tabs and filters
- Expand/collapse
- Dialogs, sheets, and menus
- Toasts and inline feedback
- Form validation
- Upload and download
- Booking and payment
- Appointment status
- Medicine order tracking
- Report availability and sharing
- Evidence details
- Consent changes
- Errors and retries
- Emergency guidance

Each pattern must include purpose, trigger, start state, end state, duration, easing, interruption behaviour, reduced-motion alternative, accessibility behaviour, and prohibited use.

## Workflow

### 1. Identify the interaction problem

State what users need to understand or accomplish and why static feedback may be insufficient.

### 2. Confirm motion is appropriate

Ask:

- Does motion improve comprehension or orientation?
- Can the state be understood without motion?
- Could motion distract, delay, mislead, or cause discomfort?
- Is this a safety-critical context where stability is better?

### 3. Map states

Document trigger, initial state, transition, final state, interruption, cancellation, failure, and recovery.

### 4. Select the motion pattern

Reuse an existing system pattern when possible. Create a new pattern only when the interaction meaning is genuinely different.

### 5. Design reduced-motion behaviour

Define the accessible alternative at the same time as the default motion.

### 6. Prototype realistic conditions

Test with real text lengths, Tamil and English, slow network, low-end devices, large text, interruptions, and real data states.

### 7. Test with users

Evaluate comprehension, orientation, speed, perceived control, comfort, trust, reduced-motion behaviour, and ability to recover.

### 8. Document implementation

Specify tokens, states, timing, easing, accessibility, interruption, performance budget, and acceptance criteria.

## Required Outputs

Produce the appropriate subset of:

1. Motion-design brief
2. User problem and interaction goal
3. Motion principles
4. State-transition maps
5. Motion inventory and audit
6. Motion tokens
7. Component motion specifications
8. Healthcare-specific interaction patterns
9. Reduced-motion alternatives
10. Loading and performance behaviour
11. Prototype requirements
12. Usability and accessibility test plan
13. Developer handoff specifications
14. Motion QA checklist

## Motion Specification Template

- **Pattern name:**
- **User goal:**
- **Purpose of motion:**
- **Trigger:**
- **Initial state:**
- **Transition:**
- **Final state:**
- **Duration token:**
- **Easing token:**
- **Interruption/cancellation:**
- **Failure/recovery:**
- **Reduced-motion alternative:**
- **Accessible announcement/focus:**
- **Performance requirement:**
- **Do not use when:**
- **Acceptance criteria:**

## Quality Checklist

Motion is acceptable only when:

- It has a clear UX purpose.
- The interface remains understandable without it.
- It represents the real system state.
- It does not delay user input or urgent information.
- It supports orientation and continuity.
- It is consistent with the motion system.
- It respects reduced-motion preferences.
- It avoids flashing, excessive zoom, bounce, parallax, and repeated pulsing.
- It works with Tamil and English content and large text.
- It performs acceptably on intended devices and networks.
- It does not misrepresent medical evidence, verification, progress, or completion.
- It has been tested for comprehension, comfort, and recovery.

## Anti-Patterns

Do not:

- Animate every interaction.
- Use motion only to make the product feel premium.
- Delay emergency guidance or warnings.
- Show success before the backend confirms completion.
- Use fake or misleading progress.
- Animate laboratory values as diagnoses.
- Use celebratory motion for medicine purchases or unnecessary tests.
- Loop attention-seeking animation on warnings.
- Use large parallax, autoplay, rapid flashing, or uncontrolled movement.
- Make animation the only source of information.
- ignore reduced-motion preferences.
- Allow motion to block input, slow low-end devices, or consume excessive bandwidth.
- Invent healthcare status, verification, delivery progress, or outcomes.

## Reusable Activation Prompt

> Use the `motion-design` skill to create or evaluate purposeful motion and interaction feedback for Arogyam. Review the user research, pain points, flows, visual system, component states, healthcare risks, accessibility needs, and technical constraints. Use motion only when it improves feedback, orientation, continuity, hierarchy, status, progress, error recovery, or comprehension. Design honest states for consultation connection, booking, payment, medicine orders, delivery, laboratory processing, report uploads, health-record sharing, consent, errors, and emergency escalation. Define triggers, start and end states, timing, easing, interruption, failure, recovery, accessible announcements, performance requirements, and reduced-motion alternatives. Ensure the interface remains fully understandable without motion, never delay urgent guidance, never show false progress or premature success, and never use decorative animation that competes with healthcare information. Produce motion principles, state maps, reusable tokens and patterns, prototypes, test criteria, and developer handoff specifications.

