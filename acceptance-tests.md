# Launch Narrative Engine Acceptance Tests

## Outcome acceptance

Pass when the Behavior turns one of these triggers into **approval-gated launch asset: draft page, email, post, or narrative brief**:

- raw product notes arrive
- launch asset is missing
- older post or release note can be repurposed

## Required checks

- Preview shows intensity 3/6/10, default permission mode, credit expectations, and first-24h suggestion-only behavior.
- Activity log includes behavior slug, trigger, reason, tool, credit cost, permission mode, result, and blocked actions.
- Quiet hours and spend caps pause or downgrade proactive checks.
- External writes, payments, trades, posts, and destructive actions are blocked unless explicitly approved.
- Private data is minimized and never placed in public manifests or catalog metadata.
- Stacking follows: user priority, safety urgency, manifest priority, lower credit cost, visible handoff.
- The five-layer behavior stack is present in the manifest and exercised by the fixture.
- The scale-gate verdict and kill condition are stated in README, spec, preview, manifest, and catalog metadata.

## Five-layer fixture gates

1. **Signal/input layer:** Product/release events, raw notes, changelogs, customer objections, funnel gaps, campaign goals, and market moments.
2. **Scoring/ranking layer:** Audience fit, launch urgency, conversion impact, channel readiness, claim risk, and asset completeness.
3. **Tool/action layer:** Brand voice checker, claim/link verifier, channel-specific draft generator, landing/email/social asset builder, and approval-note compiler.
4. **Policy/permission layer:** Never posts or sends externally without approval; compliance/claim gates; channel permission matrix; first-24h suggestion-only mode.
5. **Memory/calibration layer:** Winning hooks, rejected claims, user voice preferences, channel performance, approved phrases, and failed angles.

## Scale-or-kill gate

- **Verdict:** Keep and deepen: survives as Launch Narrative Engine, a product-event-to-assets system with brand, claim, and approval gates.
- **Kill condition:** Kill if it is only a generic writing assistant detached from launch/revenue signals, artifact readiness scoring, and approval-gated distribution.

## Done-condition gates

- Personality: preview/log language matches **Confident, punchy, fast** while still naming the concrete customer action and uncertainty.
- Drive: the test output is a measurable **approval-gated launch asset: draft page, email, post, or narrative brief** caused by raw product notes arrive, launch asset is missing, older post or release note can be repurposed.
- Hosted tools: any Forecry-hosted call includes tool name, 2 credits expected check cost, API-key boundary, and private-data minimization.
- Composed product: install/uninstall, intensity 3/6/10, stacking handoff, quiet hours, spend caps, approval gates, five-layer stack, scale verdict, and kill condition are visible in the fixture.

## Pack-specific pass examples

- Low intensity: Surfaces one source note, one channel recommendation, and a concise approval-safe angle.
- Medium intensity: Produces one draft artifact with target channel, source-note trace, claim caveats, cost, and approval notes.
- High intensity: Checks for reusable notes and launch gaps on cadence, but never posts externally without explicit approval.
