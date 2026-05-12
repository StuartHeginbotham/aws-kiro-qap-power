---
name: "quick-action-plan"
displayName: "Quick Action Plan"
description: "Guide users through creating structured action plans for critical problems under time pressure. Produces a maturity path of 3-5 milestones that each deliver independent value."
keywords: ["quick action plan", "qap", "maturity path", "milestones", "action plan", "crisis planning"]
author: "Stuart Heginbotham"
---

# Quick Action Plan

## Overview

This power guides you through a focused dialogue to produce a **Quick Action Plan (QAP)** — a maturity path of 3-5 clearly defined milestones that each deliver partial value while progressing toward full resolution.

Use it when you have a critical problem that needs structured thinking fast, you're under time pressure, and you need to move from chaos to clarity. The entire dialogue is designed to complete in 15-20 minutes.

## Onboarding

No setup required. Activate this power by saying something like:

- "I need a quick action plan for [your problem]"
- "Help me create a QAP for [situation]"
- "I have a crisis with [topic] and need a structured plan"

The agent will guide you through each phase of the dialogue.

## How It Works

The power runs a 5-phase dialogue:

1. **Capture Issues & Possibilities** — Get everything on the table
2. **Define "Awesome"** — What does full success look like?
3. **Define Current Situation** — Where are things now, honestly?
4. **Identify Activity Streams** — Break into work streams if needed
5. **Build Maturity Milestones** — Define 3-5 progressive milestones

After each interaction, you'll be offered:
- **Clarify** — Dig deeper into the situation
- **Refine** — Improve what's been captured
- **Progress** — Move to the next phase

## Output

A markdown document saved as `qap-[topic-slug].md` containing:
- Problem statement and success criteria
- Current situation assessment
- 3-5 milestones, each with: outcome, success criteria, key actions, dependencies, and effort estimate
- Risks and mitigations
- Immediate next steps

## Available Steering Files

| File | Purpose |
|------|---------|
| `dialogue-process.md` | How the agent runs the QAP conversation phases |
| `plan-structure.md` | Output template and milestone format definitions |

## Best Practices

- Keep the dialogue under 20 minutes — this is for urgent situations
- Push for measurable success criteria, not vague outcomes
- If milestones aren't roughly equal effort, rebalance them
- Each milestone must be independently valuable — not just a stepping stone
- Maximum 5 key actions per milestone; if more, split the milestone
