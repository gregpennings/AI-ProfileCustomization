# CR-NNNN: <short title>

**System(s) affected:** <hostname(s) / system(s)>
**User-affecting:** <customers / Greg / Greg's device / none - internal only>
**Classification:** <Standard / Normal / Emergency>
**Status:** <Proposed / Approved / Executed / Rolled Back / Closed>
**Date proposed:** YYYY-MM-DD

*(Standard: skip straight to documenting and executing - no approval gate needed. Emergency: skip straight to Execution log and backfill everything above it once stability is restored.)*

## Plan

<exact commands or script that will run>

## Risk assessment

- **Reversibility:** <easily reversible / reversible with effort / not reversible>
- **Blast radius:** <this machine only / affects other devices / affects accounts or data / affects customers>
- **Severity if it fails:** <cosmetic / annoying / breaks something needed>

## Rollback / backout plan

<exact steps or commands to reverse the change if it fails or causes problems>

## Pre-change test (baseline)

<command(s) to capture current state, and what they show right now>

## Dry-run

<result of validating the plan against a non-prod or simulated target before it touches anything live; if no non-prod target exists, a clearly marked simulated walkthrough of what the plan should do>

## Smoke test (planned)

<minimal, fast check to run immediately after execution - enough to catch an
obvious failure before moving on>

## Post-change test (planned)

<fuller check that the change actually achieved its goal>

## Time estimate

<gut-feel estimate, with reasoning if it's not obvious>

---

## APPROVAL

<Standard: "Pre-approved - this change type was designated Standard on <date, CR ref>. No approval gate required.">
<Normal: "Waiting for explicit approval before execution.">
<Emergency: "Executed without a real-time approval gate due to [system stability / interactivity compromised]. Documented after the fact.">

---

## Execution log

*(filled in after execution)*

**Actual start:**
**Actual end:**
**Actual duration:** (vs. estimate: - )

```
<raw output / transcript of what actually happened>
```

## Plan vs. actual

<did execution match the plan? note any deviations and why>

## Smoke test results

<actual output of the smoke test - pass/fail>

## Dry-run vs. smoke test (success metric)

<how closely did the dry-run's predicted outcome match the actual smoke test result? note any gap and why>

## Post-test results

<actual output of the post-change test - pass/fail>

## Outcome

<Success / Partial / Failed / Rolled back>

## Rollback (if used)

**Rollback approval:** <Standard: pre-approved / Normal: approved by Greg at <time> / Emergency: executed to restore stability, documented after>

<rollback execution details, if different from the planned rollback above>

## Reclassification (Normal tier only)

<if successful: eligible to become Standard going forward? y/n - note if Greg approved>
