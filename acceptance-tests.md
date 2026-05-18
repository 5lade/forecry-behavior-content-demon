# Content Engine Acceptance Tests

## Outcome acceptance

Pass when the Behavior turns one of these triggers into **draft post/page/email with approval notes**:

- raw notes arrive
- launch asset missing
- old post can be repurposed

## Required checks

- Preview shows intensity 3/6/10, default permission mode, credit expectations, and first-24h suggestion-only behavior.
- Activity log includes behavior slug, trigger, reason, tool, credit cost, permission mode, result, and blocked actions.
- Quiet hours and spend caps pause or downgrade proactive checks.
- External writes, payments, trades, and destructive actions are blocked unless explicitly approved.
- Private data is minimized and never placed in public manifests or catalog metadata.
- Stacking follows: user priority, safety urgency, manifest priority, lower credit cost, visible handoff.

## Pack-specific pass examples

- Low intensity: one safe suggestion is produced without background loops.
- Medium intensity: a draft artifact is produced with a concise reason and estimated cost.
- High intensity: proactive checks remain bounded by budget, quiet hours, and approval gates.
