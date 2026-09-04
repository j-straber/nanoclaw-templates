# Source-Backed Decision Team

Turn a current product decision into a concise, evidence-backed brief.

## What it does

This template helps product leaders and teams evaluate a decision that depends on current information. It clarifies the decision, researches the facts that matter, compares realistic options, and returns a recommendation with sources, tradeoffs, uncertainty, and one practical next action.

## Use it for

- Evaluating a framework, vendor, or platform change
- Preparing an evidence-backed build-versus-buy decision
- Comparing current product capabilities or support status
- Deciding whether to prioritize, delay, or de-risk an initiative
- Preparing a concise brief before a meeting or decision review

## What you receive

Each brief includes:

1. A recommendation and confidence level
2. The most important reasons
3. The evidence and sources used
4. Tradeoffs, risks, and counterarguments
5. Important unknowns
6. One concrete next action

## Example prompt

> Should our 25-person product team upgrade from Framework X to Framework Y this quarter? Compare current support status, breaking-change risk, migration effort, and cost. Cite primary sources and identify missing evidence.

## Guardrails

The agent distinguishes evidence from assumptions, never invents sources or citations, and does not take external actions without explicit confirmation.

## Research tools

This template uses Tavily Search and Extract for current web evidence, connected keyless (no API key) out of the box. That keyless connection is the zero-setup default — it works immediately for demos and first runs, with no account or configuration required. It contains no API keys, secrets, provider configuration, or author-controlled credentials.

Tavily's keyless access draws from a shared, free-tier-capped allowance used by everyone without a key, so it can run dry. For dependable ongoing use, a user-provided Tavily key is recommended: create one at [app.tavily.com](https://app.tavily.com) (free tier available) and connect it through the credentials proxy as your own, separate, operator-owned MCP server — never embedded in this template. If the shared allowance is exhausted before you've done that, the agent will say so plainly rather than inventing evidence, and will point you to this upgrade.