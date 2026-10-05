---
title: "Claude Code"
ring: adopt
quadrant: agentic
tags: [ai, agentic, coding-agent, cli, mcp]
---

Claude Code is Anthropic's agentic coding tool. It runs in the terminal, in IDEs (VS Code, JetBrains), in a desktop app and on the web. It reads the codebase, edits files, runs commands and tests, and works with Git, all from natural-language instructions. It can be extended with MCP servers, skills, subagents, hooks and plugins, so teams can share their own workflows and conventions.

#### Should be used in a new project if:

* You want an agent that can implement, refactor, review and document code across iOS, Android, React Native and backend projects.
* The project defines its conventions (architecture, lint rules, review checklists) in project instructions, skills or plugins, so the agent follows them.
* You want to connect the agent to design and project tools through MCP (Figma, Penpot, Redmine).

#### Should not be used in a new project if:

* The client contract or security policy forbids sending source code to a third-party AI service.
* Nobody is available to review the agent's changes. Generated code is reviewed like any other contribution.

### Docs

* [Claude Code overview](https://code.claude.com/docs/en/overview)
