# Thinking Partner

A deterministic thinking partner skill for Claude Code that challenges assumptions and applies 150+ mental models to sharpen decisions, solve problems, and think more clearly.

## What It Does

Not a lecture — a sparring session. This skill turns Claude into a thinking partner that:

- **Challenges assumptions** — Surfaces hidden beliefs you're treating as facts
- **Applies mental models** — Selects and deploys the right frameworks for your situation (100+ models across 14 disciplines)
- **Detects orientation capture** — Notices when your thinking serves comfort instead of truth
- **Maintains productive tension** — Holds complexity open long enough to find real insight

## When It Triggers

- "Help me think through X"
- "Challenge my thinking"
- "What am I missing?"
- "Play devil's advocate"
- "Stress test this idea"
- "Help me decide between X and Y"
- Any named mental model: SWOT, first principles, inversion, pre-mortem, 5 Whys, etc.

## What Makes It Different

| Feature | This Skill | Others |
|---|---|---|
| **Orientation Detection** | Diagnoses 6 thinking states (GT0-GT5) with targeted interventions | Generic questioning |
| **150+ Mental Models** | Full catalog organized by discipline with key questions | Handful of models |
| **Cognitive Operations** | 7 complementary operation pairs (Decouple/Re-couple, Hold/Resolve, etc.) | None |
| **Structured Workflow** | 6-step deterministic process from diagnosis to synthesis | Freeform |
| **Anti-Patterns** | Explicit guidance on what NOT to do | None |

## Install

### As a Claude Code Plugin

```bash
/plugin marketplace add mattnowdev/thinking-partner
/plugin install thinking-partner@mattnowdev-thinking-partner
```

### Manual Install

Copy the `skills/thinking-partner` directory to `~/.claude/skills/thinking-partner`.

## Usage

Just ask Claude to think with you:

```
/thinking-partner help me decide whether to take this job offer
```

Or use natural language — the skill triggers automatically on phrases like "help me think through", "what am I missing", "stress test this", etc.

## Mental Models Included

Organized across 14 disciplines:

- **General Thinking**: First Principles, Inversion, Second-Order Thinking, Occam's Razor, and more
- **Decision-Making**: Pre-Mortem, Regret Minimization, Reversibility Test, SWOT, Decision Matrix
- **Problem-Solving**: 5 Whys, Fishbone Diagram, Constraint Analysis, Reframing
- **Systems & Complexity**: Feedback Loops, Emergence, Leverage Points, Unintended Consequences
- **Economics & Strategy**: Incentives, Network Effects, Porter's Five Forces, Scenario Planning
- **Statistics & Probability**: Bayesian Updating, Base Rate Neglect, Survivorship Bias
- **Psychology & Biases**: Confirmation Bias, Anchoring, Loss Aversion, Framing Effect
- **And more**: Physics analogies, biology/evolution, communication, creativity, game theory

See the full catalog in [`skills/thinking-partner/references/model-catalog.md`](skills/thinking-partner/references/model-catalog.md).

## License

MIT
