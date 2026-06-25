<!-- builderloops:contributing -->
## How to contribute to this repository

This product is built one step at a time by an automated maintainer that turns the product vision into a working product through your contributions. Read this before opening a pull request.

### Work the one active step
At any moment there is exactly **one** open issue labeled `bl:active-step`. That issue is the only work being accepted right now. It describes what to build and a clear **Acceptance** (definition of done). Find it in this repo's Issues filtered by the `bl:active-step` label.

### Open a pull request that completes that step
- Your PR must fully satisfy the active step's Acceptance, and reference it (for example, "Closes #<number>").
- Keep it focused: do that step and nothing unrelated.

### Your PR is run, not just read
Every PR is checked out and executed in a sandbox: it must build, the existing tests must still pass, and the repo's acceptance checks (see `.builderloops/verify.json` if present) must pass. A PR that does not build, breaks tests, or fails acceptance is closed automatically. Make sure it genuinely works.

### What gets merged, what gets closed
- The best PR that completes the active step and passes review and execution is merged. When it merges, the step closes and the maintainer opens the next step.
- PRs that do something other than the active step are closed, even if the work is good. Wait until that work becomes the active step.
- A PR is merged only when it clearly completes the step and its benefit outweighs the added complexity; otherwise it is closed with a specific reason.

### Labels
Labels applied at merge are economic scoring signals, not decoration. The maintainer applies one only when a PR delivers working product behavior in that area.
<!-- /builderloops:contributing -->

# Contributing

This repo is curated by its maintainers for **Boutique Investment Relationship Intelligence**. A technically working change is not enough: it must move this product toward the captured vision and fit the taste rules for this repo.

## What To Build
- Capture relationship context from notes, meetings, emails, contact records, and analyst research into a unified relationship view.
- Search or open a person, firm, or opportunity and immediately see relevant history, key connections, recent touchpoints, open follow-ups, and relationship strength signals.
- Prepare for an upcoming meeting by generating a concise relationship brief with participants, prior interactions, known interests, risks, and suggested next actions.
- Prioritize outreach by identifying warm paths, neglected important relationships, upcoming moments to re-engage, and contacts tied to active firm goals.
- Log a new interaction or update relationship notes after a call, then convert important items into assigned follow-ups without losing context.
- Review a portfolio or pipeline of strategic relationships to spot coverage gaps, stale relationships, and high-value contacts needing attention.

## What To Avoid
- Do not expose internal development, review, repository, or maintainer mechanics in the customer experience.
- Do not make the product feel like a generic sales CRM or a marketing landing page.
- Do not require users to understand technical infrastructure before they can get value.
- Do not overfit the interface around a final brand name because the product category is clearer than the name.

## Pull Request Standard

Submit one focused product improvement at a time. The maintainers prefer small, complete, verifiable changes over broad speculative rewrites.

A PR should include:
- the user-facing improvement
- the workflow or taste rule it advances
- verification performed
- screenshots or preview notes when the change affects UI

## Maintainer Policy

The default policy is merge or close. If work is not mergeable now, maintainers close it with guidance for a cleaner future submission instead of leaving long requested-change queues open.

Maintainers merge work that:
- Merge clean PRs that pass CI, match the Vision Model, and improve an accepted workflow or quality bar.
- Prefer small coherent changes that can ship immediately over broad speculative rewrites.
- Treat product taste and user workflow fit as first-class acceptance criteria.
- Summarize merged work as product progress, not as raw PR activity.

Maintainers close work that:
- Close PRs that are incomplete, off-vision, overlapping, stale, or likely to create product drift.
- Do not leave requested-change queues by default. Close with clear resubmission guidance.
- Close technically correct PRs when they solve the wrong problem or move the product away from the captured vision.
- If a PR is promising but messy, explain the clean smaller PR that should be submitted next.

## Labels

Use labels that match this repo. They are part of the maintainer policy and should not be treated as generic tags.

| Label | Multiplier | Meaning |
| --- | ---: | --- |
| `episode-ingest` | 3 | Improves importing, uploading, syncing, or assigning podcast episode source tracks and speakers. |
| `contextual-visuals` | 2 | Improves context-aware b-roll, title moments, callouts, references, social context, or visual moments. |
| `product-polish` | 1.5 | Improves Boutique Investment Relationship Intelligence's feel, usability, clarity, or taste fit. |
| `bugfix` | 1 | Fixes broken behavior that blocks Boutique Investment Relationship Intelligence's captured product direction. |
| `infrastructure` | 0.5 | Improves checks, deployment, or repo operations without directly advancing product behavior. |
| `off-vision` | 0 | Technically plausible work that does not help Boutique Investment Relationship Intelligence converge on the captured vision. |

## Branches

Target `main` unless the maintainers explicitly publish another branch policy for this repo.

## Checks
- Keep `typecheck` passing or explain why it does not apply.
- Keep `lint` passing or explain why it does not apply.
- Keep `test` passing or explain why it does not apply.
- Keep `preview-build` passing or explain why it does not apply.