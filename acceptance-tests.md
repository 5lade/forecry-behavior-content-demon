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

## Done-condition gates

- Personality: preview/log language matches **Confident, punchy, fast** while still naming the concrete customer action and uncertainty.
- Hobby/drive: the test output is a measurable **draft post/page/email with approval notes** caused by raw notes, missing launch asset, or repurposable old post.
- Hosted tools: any Forecry-hosted call includes tool name, 2 credits expected check cost, API-key boundary, and private-data minimization.
- Composed product: install/uninstall, intensity 3/6/10, stacking handoff, quiet hours, spend caps, and approval gates are visible in the fixture.

## Pack-specific pass examples

- Low intensity: Surfaces one source note and one channel recommendation, without background loops or external posting.
- Medium intensity: Produces one draft artifact with target channel, approval notes, estimated cost, and source-note trace.
- High intensity: Checks for reusable notes up to the configured cadence, but only drafts bounded assets within quiet hours/spend caps.
