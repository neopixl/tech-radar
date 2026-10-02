---
title: "Agent Skills"
ring: adopt
quadrant: agentic
tags: [ai, agentic, skills, standard]
---

Agent Skills is an open standard for packaging instructions, scripts and resources that AI agents load on demand. A skill is a folder containing a `SKILL.md` file: YAML front-matter with a `name` and a `description` (what the skill does and when to use it), followed by Markdown instructions. Optional `scripts/`, `references/` and `assets/` folders hold supporting files. Anthropic published it as an open standard in December 2025, and it is now supported by many agents, including Claude Code, OpenAI Codex, Gemini CLI, GitHub Copilot and Cursor.

We use this standard for our skills, and the same front-matter conventions for our agent definitions. This keeps our workflows (code generation, reviews, audits, project management) portable between tools.

#### Should be used in a new project if:

* You are writing reusable instructions or workflows for AI agents.
* The same workflow should work in more than one agent or IDE.

#### Should not be used in a new project if:

* The instruction is a one-off that belongs in the project's own instructions file instead.

### Docs

* [Agent Skills](https://agentskills.io)
