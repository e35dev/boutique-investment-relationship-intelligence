# Boutique Investment Relationship Intelligence

Repository: `customer/boutique-investment-relationship-intelligence`

Help boutique investment firms understand, prioritize, and act on their relationship network so founders, investor relations leads, and analysts can turn scattered context into better outreach, coverage, and follow-through.

This repository is maintained against the product direction below. The maintainers use this document, `VISION.md`, and `CONTRIBUTING.md` as the standard for accepting or closing work.

## Who It Serves
- Founders at boutique investment firms who need high-leverage relationship context before conversations and fundraising or deal-development moments.
- Investor relations leads who manage ongoing investor, allocator, LP, and strategic contact engagement.
- Analysts who research people, firms, interactions, and relationship signals to prepare the team for timely action.

## Product Workflows
- Capture relationship context from notes, meetings, emails, contact records, and analyst research into a unified relationship view.
- Search or open a person, firm, or opportunity and immediately see relevant history, key connections, recent touchpoints, open follow-ups, and relationship strength signals.
- Prepare for an upcoming meeting by generating a concise relationship brief with participants, prior interactions, known interests, risks, and suggested next actions.
- Prioritize outreach by identifying warm paths, neglected important relationships, upcoming moments to re-engage, and contacts tied to active firm goals.
- Log a new interaction or update relationship notes after a call, then convert important items into assigned follow-ups without losing context.
- Review a portfolio or pipeline of strategic relationships to spot coverage gaps, stale relationships, and high-value contacts needing attention.

## Intended End State

A working product experience where a boutique investment team can maintain a trusted relationship map, inspect any contact or firm, prepare for meetings, prioritize outreach, and manage follow-ups from relationship intelligence rather than scattered memory.

## Product Taste
- Professional, restrained, and information-dense enough for finance users.
- Fast to scan before meetings, with clear hierarchy between people, firms, touchpoints, and next actions.
- Trustworthy and polished, avoiding gimmicky CRM energy.
- Customer-facing language should describe relationship intelligence, preparation, priorities, and follow-through.

## Accept Work That
- Merge clean PRs that pass CI, match the Vision Model, and improve an accepted workflow or quality bar.
- Prefer small coherent changes that can ship immediately over broad speculative rewrites.
- Treat product taste and user workflow fit as first-class acceptance criteria.
- Summarize merged work as product progress, not as raw PR activity.

## Close Work That
- Close PRs that are incomplete, off-vision, overlapping, stale, or likely to create product drift.
- Do not leave requested-change queues by default. Close with clear resubmission guidance.
- Close technically correct PRs when they solve the wrong problem or move the product away from the captured vision.
- If a PR is promising but messy, explain the clean smaller PR that should be submitted next.

## Repo Labels

| Label | Multiplier | Meaning |
| --- | ---: | --- |
| `episode-ingest` | 3 | Improves importing, uploading, syncing, or assigning podcast episode source tracks and speakers. |
| `contextual-visuals` | 2 | Improves context-aware b-roll, title moments, callouts, references, social context, or visual moments. |
| `product-polish` | 1.5 | Improves Boutique Investment Relationship Intelligence's feel, usability, clarity, or taste fit. |
| `bugfix` | 1 | Fixes broken behavior that blocks Boutique Investment Relationship Intelligence's captured product direction. |
| `infrastructure` | 0.5 | Improves checks, deployment, or repo operations without directly advancing product behavior. |
| `off-vision` | 0 | Technically plausible work that does not help Boutique Investment Relationship Intelligence converge on the captured vision. |

## Verification
- Run or preserve `typecheck` before submitting product work.
- Run or preserve `lint` before submitting product work.
- Run or preserve `test` before submitting product work.
- Run or preserve `preview-build` before submitting product work.