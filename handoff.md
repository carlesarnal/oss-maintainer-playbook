# Make the next action visible

| State | Next owner | Required evidence |
|---|---|---|
| Ready for review | Maintainer | Scope, test evidence, reviewer availability |
| Changes requested | Contributor | Specific actionable request |
| Approved, verification pending | CI and maintainer | Current commit, valid approval, full checks |
| Checks failed | Explicitly assigned | Failure diagnosis; distinguish infrastructure from patch |
| Waiting on maintainer | Maintainer | Overdue signal and escalation path |
| Both sides blocked | Explicit policy | Which action actually unblocks progress? |

## Worked trace

PR #10409: a reviewer was suggested; Carles approved on October 7, 2026; bot
comments distinguished the fast check from full verification; the PR merged later
that day. This illustrates states, not an experimentally measured time saving.

## Exercise

Choose a delayed contribution. Write its current owner, next action, evidence
needed and fallback if the owner is unavailable. Decide how the contributor can
see this without interpreting three dashboards. Record one improvement and who
will maintain it. Avoid promising review capacity the team does not possess.
