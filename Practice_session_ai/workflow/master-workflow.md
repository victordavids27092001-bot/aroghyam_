# Arogyam Master Workflow

## Control Flow

1. Receive the request and approved inputs.
2. Run Gate 00 to confirm scope, authority, evidence, risks, and expected outputs.
3. Identify the active Double Diamond phase.
4. Create a task contract using `task-template.md`.
5. Route bounded work using `agent-routing.md`.
6. Require agents to use relevant skills and approved inputs.
7. Save drafts in the phase `working` folder.
8. Run evidence, safety, regulatory, accessibility, and quality reviews as required.
9. Save candidate deliverables in the phase `deliverables` folder.
10. Run the corresponding transition gate.
11. If `PASS`, copy versioned deliverables to the matching `outputs` folder and continue.
12. If `CONDITIONAL PASS`, record owners, deadlines, and restrictions before continuing.
13. If `FAIL`, return only the failed criteria for revision and rerun the gate.
14. If `HUMAN REVIEW REQUIRED`, stop until the user or named reviewer approves.
15. After Gate 04, place final approved artifacts in `outputs/approved`.

## Phase Sequence

`Discover → Gate 01 → Define → Gate 02 → Develop → Gate 03 → Deliver → Gate 04`

## Manager-Controlled Pattern

The orchestrator retains ownership of the complete response and uses specialist agents for bounded work. Use a full handoff only when another role must own the next decision and the handoff is explicitly authorized.

## Stopping Conditions

Stop when:

- Required user approval is missing.
- A high-risk medical, legal, privacy, or regulatory question lacks qualified review.
- Essential source material is unavailable.
- A requested action exceeds the approved scope.
- Gate criteria fail after revision and further work needs a user decision.
