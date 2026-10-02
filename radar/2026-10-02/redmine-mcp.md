---
title: "Redmine MCP"
ring: adopt
quadrant: agentic
tags: [ai, mcp, project-management, issue-tracking]
---

A Redmine MCP server connects AI agents to Redmine through its REST API. Agents can search and read issues, create and update tickets, add comments and log time, from the same session where the work is done.

#### Should be used in a new project if:

* The project is managed in Redmine and you want agents to read ticket context, or to keep tickets and time entries up to date.

#### Should not be used in a new project if:

* The project is not tracked in Redmine.
* The agent would need to be given write access that the project's process doesn't allow.

### Docs

* [Redmine REST API](https://www.redmine.org/projects/redmine/wiki/Rest_api)
* [Model Context Protocol](https://modelcontextprotocol.io)
