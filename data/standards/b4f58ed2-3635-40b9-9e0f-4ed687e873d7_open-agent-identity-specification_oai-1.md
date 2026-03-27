---
id: b4f58ed2-3635-40b9-9e0f-4ed687e873d7
title: "Open Agent Identity Specification"
acronym: OAI-1
status: Draft
organization: "Open Agent Identity Foundation"
tags: [identity, discovery, AI agents, decentralized identity constellations, interoperability, DNS, MCP]
link: https://openagentidentity.org
expired: false
created_at: 2026-03-23T17:09:25.779765+00:00
updated_at: 2026-03-23T17:23:31.861761+00:00
---

# Open Agent Identity Specification (OAI-1)

**Status:** Draft | **Organization:** Open Agent Identity Foundation

## Description
A decentralized standard for discovering, verifying, and interacting with AI agents using DNS-rooted identity. It provides a universal identity foundation that enables interoperability between different agent protocols like MCP, A2A, and UCP.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Sierra | Sierra | Contributor |  |
| Decagon | Decagon | Contributor |  |
| Open Agent Identity Working Group | Open Agent Identity Foundation | Author |  |

## Resources
| Type | Label | URL |
|------|-------|-----|
| primary_spec | Primary Specification | https://openagentidentity.org |
| github | GitHub Repository | https://github.com/openagentidentity/spec |
| documentation | Reference Manifest | https://acme-agent.com/.well-known/agent-identity.json |
| reference_impl | Reference Implementation | https://acme-agent.com |

## Tags
identity, discovery, AI agents, decentralized identity constellations, interoperability, DNS, MCP

## Latest Summary
### Overview
The **Open Agent Identity (OAI)** specification is a decentralized protocol designed for the discovery, verification, and interaction of AI Agents. It addresses the need for a standardized identity layer in the burgeoning AI agent ecosystem, enabling agents to represent themselves securely and allowing clients to verify agent provenance before engaging in transactions or data exchange.

### Key Components and Decisions
*   **Identity & Discovery:** Agents are identified via a decentralized standard. Discovery relies on an `agent-identity.json` manifest file hosted at a `/.well-known/` path on the agent's domain.
*   **Agent Manifest:** A structured JSON object that defines the agent's version, identity (name, handle, public key), operator details (contact, privacy policy), and capabilities (tools, permissions).
*   **Protocol Compatibility:** The standard explicitly supports integration with the **Model Context Protocol (MCP)**, facilitating a bridge between identity and standardized execution of agentic tools.
*   **Security & Verification:** Identity is anchored by DNS verification and Ed25519 public keys. The protocol includes mechanisms for client authentication and authorization policies (e.g., "open" vs. "restricted").
*   **Commerce & Tools:** The specification includes a `pricing` field in the manifest to support zero-touch payments and detailed `capabilities` definitions for tool-calling.

### Open Questions and Deadlines
The current version (1.0.5) is marked as a **Draft**. While the manifest structure is maturing, details regarding the full extent of "zero-touch payments" and specific cross-chain or cross-platform payment implementations remain areas for further refinement. The specification is actively seeking feedback via its GitHub repository.

## What's New
### Recent Updates (February 2026)
The specification has recently advanced to **Version 1.0.5 (Draft)**. Key recent activities include:
*   **Improved Reference Implementation:** The release of the "Acme" interactive tutorial and reference agent (v1.0.3) providing a "learn-by-doing" environment for developers.
*   **Enhanced Manifest Features:** The `agent-identity.json` now includes detailed `capabilities` and `pricing` fields, allowing agents to advertise specific tools (e.g., `validate_manifest`, `check_dns`) and their cost structure (currently defaulting to "free" in reference models).
*   **MCP Integration:** Formalized documentation on integrating OAI with the Model Context Protocol to standardize how identified agents expose their functional tools to clients.
*   **Public Key Infrastructure:** Standardized usage of **Ed25519** public keys within the manifest for secure identity anchoring.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2026-02-03 | other | Manifest Version 2 Update | The reference manifest for the @acme agent was updated to version 2. |
| 2026-02-02 | milestone | Initial Reference Manifest Created | Reference manifest created for Acme agent implementation. |
| 2026-02-01 | release | OAI-1 Version 1.0.5 Draft Release | The current draft of OAI-1 (Version 1.0.5) is released for review. |
