# Quick Action Plan (QAP) — Kiro Power

A Kiro Power that guides you through a focused dialogue to produce a **Quick Action Plan** — a maturity path of 3-5 clearly defined milestones that each deliver independent value while progressing toward full resolution.

## What It Does

Use this when you have a critical problem that needs structured thinking fast. The entire dialogue completes in 15-20 minutes and produces a concrete, actionable plan.

The power runs a 5-phase dialogue:

1. **Capture Issues & Possibilities** — Get everything on the table
2. **Define "Awesome"** — What does full success look like?
3. **Define Current Situation** — Where are things now, honestly?
4. **Identify Activity Streams** — Break into work streams if needed
5. **Build Maturity Milestones** — Define 3-5 progressive milestones

## Usage

Activate by saying something like:

- "I need a quick action plan for [your problem]"
- "Help me create a QAP for [situation]"
- "I have a crisis with [topic] and need a structured plan"

## Output

A markdown document (`qap-[topic-slug].md`) containing:

- Problem statement and success criteria
- Current situation assessment
- 3-5 milestones with outcomes, success criteria, key actions, dependencies, and effort estimates
- Risks and mitigations
- Immediate next steps

## Project Structure

```
├── POWER.md                      # Power definition and metadata
├── steering/
│   ├── dialogue-process.md       # Conversation phase instructions
│   └── plan-structure.md         # Output template and milestone format
├── .gitignore
└── README.md
```

## Author

Stuart Heginbotham
