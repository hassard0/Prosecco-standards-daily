---
id: e8d35071-696b-417f-b61f-f91bda91a32a
title: "Model Context Protocol"
acronym: MCP
status: Approved
organization: "Linux Foundation"
tags: [Protocol]
link: https://modelcontextprotocol.io/
expired: false
created_at: 2026-03-22T18:33:31.70173+00:00
updated_at: 2026-03-23T00:48:53.578589+00:00
---

# Model Context Protocol (MCP)

**Status:** Approved | **Organization:** Linux Foundation

## Description
Model Context Protocol (MCP) is an open protocol that enables seamless integration between LLM applications and external data sources and tools. Whether you're building an AI-powered IDE, enhancing a chat interface, or creating custom AI workflows, MCP provides a standardized way to connect LLMs with the context they need.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Anthropic | Anthropic | Author |  |

## Resources
| Type | Label | URL |
|------|-------|-----|
| github | GitHub Repository | https://github.com/modelcontextprotocol |
| blog | Official Blog | https://blog.modelcontextprotocol.io |
| documentation | Specification (2025-11-25) | https://modelcontextprotocol.io/specification/2025-11-25 |
| documentation | MCP Extensions Overview | https://modelcontextprotocol.io/extensions/overview |
| other | Model Context Protocol Registry | https://modelcontextprotocol.io/registry/about |
| working_group | Model Context Protocol Enhancements (SEPs) | https://modelcontextprotocol.io/seps |

## Tags
Protocol

## Latest Summary
The **Model Context Protocol (MCP)** is an open-standard communication protocol designed to provide a universal interface for integrating AI models with external data sources and tools. By creating a standardized way for "clients" (like AI-powered IDEs or chat interfaces) to interact with "servers" (which host specific datasets or local tools), MCP reduces the need for custom integrations.

The protocol has evolved from its initial focus on local tool wiring into a robust production-ready standard supported by a formal governance process under **LF Projects, LLC**. Key components of the specification include **Resources** (data provided to the model), **Tools** (executable functions), and **Prompts** (pre-defined templates). A significant recent architectural shift has introduced **MCP Extensions**, which allow developers to layer domain-specific conventions (e.g., healthcare or finance) and custom UI/authentication flows on top of the core protocol without destabilizing the base standard. 

Governance is managed through **Working Groups** and a formal **Specification Enhancement Proposal (SEP)** process. Current discussions within the community are heavily focused on "Risk Vocabulary," using tool annotations to help models and users understand the potential impact—such as destructive actions or external environment reach—before execution occurs.

## What's New
The Model Context Protocol has recently introduced **MCP Extensions**, a framework designed to support domain-specific conventions and custom UI elements without altering the baseline protocol. This ensures core stability while enabling specialization in fields like finance or healthcare. Additionally, the community is actively processing **five independent Specification Enhancement Proposals (SEPs)** related to **Tool Annotations**. These proposals aim to establish a "Risk Vocabulary" that identifies whether a tool's action is read-only, idempotent, or potentially destructive. The project has also finalized its transition to a formal governance model under LF Projects, LLC, moving beyond its roots as a local utility into a production-standard for agentic AI workflows.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2026-03-16 | decision | Tool Annotations Risk Framework Discussion | Maintainers detail the use of tool annotations to describe risks (e.g., destructive vs. read-only) and evaluate five new SEPs. |
| 2026-03-11 | milestone | MCP Extensions Announced | The project introduces the 'Extensions' framework to allow specialized capabilities without modifying the core protocol. |
| 2026-03-09 | milestone | 2026 MCP Roadmap Published | Lead Maintainer David Soria Parra outlines the project's shift toward production-ready workflows and formal governance. |
| 2025-11-25 | release | Specification Release 2025-11-25 | Release of the current stable version of the Model Context Protocol specification. |
