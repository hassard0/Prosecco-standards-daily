---
id: 6018424b-7ebf-4193-8d97-3a7febb5b2a3
title: "agents.json"
acronym: agents.json
status: Emerging
organization: "Wildcard"
tags: [API, Agents, JSON Specification, OpenAPI Extension, Agentic Interoperability]
link: https://docs.wild-card.ai/agentsjson/introduction
expired: false
created_at: 2026-03-22T18:33:31.70173+00:00
updated_at: 2026-03-23T00:26:44.952268+00:00
---

# agents.json (agents.json)

**Status:** Emerging | **Organization:** Wildcard

## Description
Agents.json is an open-source JSON specification built on top of the OpenAPI standard that formally describes contracts for API and AI agent interactions. It provides a structured way for agents to understand and interact with diverse service capabilities.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Wildcard Team | Wildcard | Author |  |
| Kaushik Mahorker | Unknown | GitHub Contributor | [link](https://github.com/kmahorker) |
| Yagnya Patel | Unknown | GitHub Contributor | [link](https://github.com/yagnyaPatel) |
| Wildcard AI | Unknown | GitHub Contributor | [link](https://github.com/wild-card-ai) |

## Resources
| Type | Label | URL |
|------|-------|-----|
| github | GitHub Repository | https://github.com/wild-card-ai/agents-json |
| mailing_list | Support Email | mailto:info@wild-card.ai |
| documentation | Documentation Introduction | https://docs.wild-card.ai/agentsjson/introduction |

## Tags
API, Agents, JSON Specification, OpenAPI Extension, Agentic Interoperability

## Latest Summary
`agents.json` is a proposed standard for AI agent discovery and interoperability, modeled after the successful `well-known` file patterns like `robots.txt` or `security.txt`. Developed by Wild Card AI, the standard provides a structured way for websites to declare the presence, capabilities, and contact information of their AI agents. This allows external systems and other AI agents to programmatically discover how to interact with a specific domain's automated representatives. 

The specification defines a JSON-based schema that includes fields for the agent's name, description, API endpoints, supported protocols (such as Model Context Protocol - MCP), and authentication requirements. By hosting this file at a predictable location (typically `/.well-known/agents.json`), service providers can ensure their agents are "indexable" and "crawlable" by the broader AI ecosystem, fostering a more connected and automated web. The project is currently hosted on GitHub and is seeking community feedback to refine the schema for various use cases, including customer support bots, trading agents, and data retrievers.

## What's New
The standard has recently gained momentum with the inclusion of specific fields for the **Model Context Protocol (MCP)**, allowing agents to expose their tools and resources more effectively. Recent updates also include a refined 'permissions' object to clarify what actions an external agent is allowed to take. Furthermore, a community-driven list of 'Authorized Agents' is being curated to help prevent malicious crawlers from spoofing the standard. The repository has seen increased activity in the 'examples' directory, providing templates for common platforms like Shopify and Zendesk.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2025-01-15 | meeting | Schema Expansion Discussion | Community discussion opened regarding the addition of 'trust_score' and 'verification' fields to the schema. |
| 2024-12-10 | release | Validator Tool Launch | Release of a reference validator tool to help developers verify their agents.json files against the schema. |
| 2024-11-25 | draft | MCP Integration Support | Updated documentation to include examples for Model Context Protocol (MCP) integration. |
| 2024-11-20 | release | Initial Specification Release | Initial commit and public release of the agents.json specification draft on GitHub. |
