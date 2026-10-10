# Arogyam AI Orchestration Rules

## Mission

Support the design of Arogyam, an evidence-informed Indian integrative-wellness application, through a controlled Double Diamond workflow.

## Operating Model

- The orchestrator owns task planning, routing, synthesis, status, and final handoffs.
- Specialist agents perform bounded work and do not approve their own outputs.
- Skills define reusable methods; agents define responsibility and judgement.
- Inputs are source material. Do not silently edit or overwrite them.
- Draft work belongs in the active phase's `working` folder.
- Candidate deliverables belong in the active phase's `deliverables` folder.
- Only gate-approved artifacts belong in `outputs/approved`.
- Do not enter the next phase without the required gate approval.

## Evidence and Healthcare Rules

- Never invent users, interviews, quotations, studies, statistics, regulations, services, prices, or results.
- Separate facts, user evidence, expert opinion, clinical evidence, assumptions, interpretations, and recommendations.
- Open and verify authoritative sources before using clinical, numerical, regulatory, or time-sensitive claims.
- Traditional use, popularity, biological plausibility, and government recognition are not proof of clinical benefit.
- Do not diagnose from questionnaires or research data.
- Do not recommend stopping prescribed medicine or delaying vaccination, testing, emergency care, or necessary treatment.
- Route individualized high-risk healthcare guidance to qualified professionals.
- Escalate emergency, adverse-event, interaction, pregnancy, paediatric, liver, kidney, privacy, and delayed-care concerns.
- Formal legal conclusions require qualified Indian legal review.

## UX Rules

- Begin with verified user needs and context, not preferred features.
- Include accessibility, Tamil and English, health literacy, digital literacy, rural and urban access, caregiver use, low connectivity, and shared-device privacy.
- Preserve contradictory findings, minority experiences, and safety-critical signals.
- Trace every important recommendation to evidence.
- Test comprehension, task completion, error recovery, trust, consent, and safety—not only visual appeal.

## Gate Behaviour

Each gate returns exactly one status:

- `PASS`
- `CONDITIONAL PASS`
- `FAIL`
- `HUMAN REVIEW REQUIRED`

When human approval is required, stop and wait. Do not infer approval from silence.

## Change Control

- Preserve existing user files and unrelated changes.
- Record material assumptions and workflow changes.
- When new evidence affects an approved artifact, flag downstream items for re-review.
- Never overwrite approved outputs; create a new version and archive the old one.
