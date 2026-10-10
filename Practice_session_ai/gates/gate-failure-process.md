# Gate Failure Process

When a gate fails:

1. Return `FAIL` with failed criteria and evidence.
2. Do not advance the phase or publish candidate deliverables as approved.
3. Create focused correction tasks with named owners.
4. Preserve both the failed version and reviewer comments.
5. Correct only the affected work unless dependencies require broader revision.
6. Rerun required specialist reviews.
7. Rerun the gate and record the new decision.

Use `HUMAN REVIEW REQUIRED` when evidence conflicts, authority is missing, risk is high, or the decision is clinical, legal, privacy-sensitive, financially consequential, or outside approved scope.
