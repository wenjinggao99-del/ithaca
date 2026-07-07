# Ithaca

> Skills built on the journey toward Odysseus.

A small collection of [Agent Skills](https://agentskills.io) — reusable,
version-controlled instruction sets that teach an AI agent to do a task
the way I would, so I only have to figure it out once.

Built with Claude Code. Each skill follows the open Agent Skills standard
(a folder with a `SKILL.md`), so they also run in other agents that adopt
the spec.

## The idea

Every time I solve a problem manually, I distill the workflow — steps,
quality checks, and the triggers for when it applies — into a skill.
The next time the situation appears, the agent already knows what to do.
Individual learning becomes permanent capability.

## Skills

| Skill | Named after | What it does |
|---|---|---|
| **Ariadne** | the thread through the labyrinth | Translates a job description into what the job actually is: concrete daily work, the real problem behind the vacancy, and a personal fit analysis |
| **Cassandra** | the prophet nobody believed | Prophesies how an interview could fail — the hardest questions, the weak spots, the traps — and arms you with countermeasures |

## Install (Claude Code)

```bash
git clone https://github.com/<me>/ithaca
cp -r ithaca/skills/* ~/.claude/skills/
```

Then just talk naturally — paste a JD and Ariadne wakes up — or invoke
directly with `/ariadne` or `/cassandra`.

## Why "Ithaca"

Ithaca is the island Odysseus spends the whole epic trying to reach.
These skills were built as deliberate practice in agentic methodology:
translating fuzzy requirements into structured, validated, reusable
instructions. The destination gave the repo its name.
