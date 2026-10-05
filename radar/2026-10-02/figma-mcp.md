---
title: "Figma MCP"
ring: adopt
quadrant: agentic
tags: [ai, mcp, design, design-to-code]
---

The Figma MCP server gives AI agents access to Figma files through the Model Context Protocol. Agents can read design context (layout, components, variables, styles) to generate code that matches the design. They can also write to the canvas, creating and editing frames, components, variables and auto layout. Figma recommends the remote server, which doesn't require the desktop app.

#### Should be used in a new project if:

* The designs live in Figma and you want agents such as Claude Code to implement screens from them.
* The project has a design system in Figma whose tokens and components should be reused in code.

#### Should not be used in a new project if:

* The designs are not in Figma (see Penpot MCP).
* Your Figma plan or the client's organisation settings don't allow MCP access.

### Docs

* [Figma MCP server developer docs](https://developers.figma.com/docs/figma-mcp-server/)
* [Guide to the Figma MCP server](https://help.figma.com/hc/en-us/articles/32132100833559-Guide-to-the-Figma-MCP-server)
