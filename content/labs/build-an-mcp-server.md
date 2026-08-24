---
title: "Build an MCP Server"
description: "Write a Model Context Protocol server from scratch, test it against a real client, and ship it as a container."
weight: 20
draft: false
slug: "build-an-mcp-server"
level: "intermediate"
duration_min: 120
cloud: "Local, optional container registry"
est_cost_eur: 0
prerequisites: ["Node 20", "Docker", "An MCP capable client"]
repo: "https://github.com/example/mcp-server-kit"
---

**Purpose.** Intermediate lab for developers exposing an internal API to an assistant. Ends with a tested server a colleague can install.

**Contains.**
- Design first: choosing between tools, resources, and prompts for your API
- Implement three tools with proper input schemas and error shapes
- Wire the conformance harness and watch a bad schema get rejected
- Handle auth without leaking a token into the transcript
- Package as a container and as a stdio binary, then install into a client
- Failure drills: slow tool, oversized payload, partial outage
- Publishing checklist before you share it

**Primary CTA.** Publish your server and add it to the showcase.
**Links to.** /projects/mcp-server-kit/, /teardowns/retrieval-layer/, /showcase/submit/
