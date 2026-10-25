# Presentation guide

Beyond the First Pull Request: Making Contribution Work Sustainable

## Audience and central claim

A contribution can be silent because the author owes a change, because no maintainer has reviewed it, or because both are blocked. A generic inactivity timer can ask the wrong person to act. Apicurio’s published lifecycle makes these states visible instead of treating every delay as contributor inactivity.

## 30-minute run of show

### 0:00 — Who owns the next action?

A contribution can be silent because the author owes a change, because no maintainer has reviewed it, or because both are blocked. A generic inactivity timer can ask the wrong person to act. Apicurio’s published lifecycle makes these states visible instead of treating every delay as contributor inactivity.

Open the waiting-on-author and waiting-on-maintainer states in the published lifecycle.

### 4:00 — Follow a review through verification

A reviewer suggestion identifies a candidate, not proof of available time. Approval and a fast check are separate from the full verification gate. Public PR #10409 records a suggested reviewer, my approval, bot comments about the remaining full suite and a later merge. The sequence illustrates responsibilities; one example does not establish a time-saving benchmark.

Follow PR #10409 from reviewer suggestion through approval, full verification and merge.

### 9:00 — Escalation when both sides are blocked

The documented process does not auto-close a PR blocked only on a maintainer. It adds an overdue signal. When both author and maintainer are blocked, the contributor timer takes precedence. That detail belongs in the discussion: an ownership-aware policy can still have contested choices and needs maintainers to keep it accurate.

Discuss the documented both-sides-blocked timer policy and its trade-off.

### 15:00 — Adapt the hand-off worksheet

The hand-off worksheet asks for current owner, evidence needed, next action and escalation if the owner is unavailable. A documented convention may be sufficient before automation is justified. The goal is a process a small team can sustain, not a claim that automation eliminates overload or proves community growth. Review waiting time and repeat participation are signals to investigate, not causal conclusions.

Use handoff.md to identify the next action and owner in a delayed contribution.

### 21:00 — Escalate without blaming the wrong person

Summarize the decision the example supports and the assumptions behind it.

Ask which handoff can be clarified without introducing another automation service.

### 26:00 — Questions and buffer

Ask what the demonstration establishes and what it leaves open. Do not add another feature if time is short.

## Setup and fallback

```sh
Read handoff.md and trace public PR #10409
```

Public PR lifecycle and Carles review on #10409 inspected. Workshop/state table prepared. Automation effectiveness and contributor-retention outcomes were not measured.

Prebuild/download dependencies. Keep a recording of an actual successful run; if unavailable, use the documented walkthrough and say it is not live execution. Never substitute fabricated success output.

## Questions to prepare

- What is the simplest alternative?
- Which failure was actually exercised?
- Which guarantee belongs to the application rather than the infrastructure?
- Which result changes with versions or workload?

## 25-minute adaptation

Use one central trace, shorten setup and reserve three minutes for questions. Move the secondary implementation example to backup.
