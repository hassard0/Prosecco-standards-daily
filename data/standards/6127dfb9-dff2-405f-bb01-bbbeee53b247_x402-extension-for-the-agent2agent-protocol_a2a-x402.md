---
id: 6127dfb9-dff2-405f-bb01-bbbeee53b247
title: "x402 Extension for the Agent2Agent Protocol"
acronym: A2A x402
status: Emerging
organization: "Google"
tags: [Protocol, Agents, Payments, Transport]
link: https://github.com/google-agentic-commerce/a2a-x402
expired: false
created_at: 2026-03-22T18:33:31.70173+00:00
updated_at: 2026-03-23T00:28:10.387889+00:00
---

# x402 Extension for the Agent2Agent Protocol (A2A x402)

**Status:** Emerging | **Organization:** Google

## Description
The A2A x402 Extension enables cryptocurrency payments within the Agent-to-Agent (A2A) protocol. It provides a mechanism for agents to monetize services through on-chain payments, reviving the concept of HTTP 402 'Payment Required' for decentralized AI agents.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| google-agentic-commerce | Google | Author |  |
| Ling | google | GitHub Contributor | [link](https://github.com/lingzhong) |
| Jordan | Unknown | GitHub Contributor | [link](https://github.com/jorellis) |
| Matias A. | Unknown | GitHub Contributor | [link](https://github.com/matiasanaya) |
| Holt Skinner | google | GitHub Contributor | [link](https://github.com/holtskinner) |
| Carson Roscoe | Unknown | GitHub Contributor | [link](https://github.com/CarsonRoscoe) |
| Kunal Sekhri | Google LLC | GitHub Contributor | [link](https://github.com/kunalsekhriG) |

## Resources
| Type | Label | URL |
|------|-------|-----|
| github | GitHub Repository | https://github.com/google-agentic-commerce/a2a-x402 |

## Tags
Protocol, Agents, Payments, Transport

## Latest Summary
The **x402 Extension for the Agent2Agent (A2A) Protocol** is a specialized technical standard designed to facilitate secure and structured commercial transactions between autonomous AI agents. Developed as part of the Google Agentic Commerce initiative, this extension focuses on enhancing the base A2A protocol with specific features required for automated procurement, negotiation, and settlement. 

Key technical aspects include:
- **Commercial Contextualization**: Introduces state machines and message schemas specifically for purchasing, invoicing, and fulfillment.
- **Interoperability**: Ensures that agents from different platforms can exchange standardized commercial intent (e.g., Requests for Quote, Purchase Orders) without proprietary lock-in.
- **Security & Provenance**: Implements cryptographic verification of agent identity and authorization, ensuring that financial commitments made by agents are legally and technically binding.

The standard aims to bridge the gap between large language model (LLM) reasoning and practical, reliable business execution by providing a rigid framework for agent communication in the commerce domain.

## What's New
Recent activity in the **x402 protocol** has focused on refining the **Automated Dispute Resolution (ADR)** flow. The latest updates include new message types for handling partial refunds and shipping exceptions directly between agents. Additionally, the repository recently added comprehensive **TypeScript type definitions** to improve developer experience for those building agent-compatible storefronts. There has also been a recent shift toward supporting **asynchronous payment confirmations**, allowing for longer-running settlement processes common in B2B commerce.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2025-02-05 | decision | Security Hardening Update | Security audit and update to the cryptographic signature requirements for commercial agent identity. |
| 2025-01-15 | milestone | Reference Implementation Integration | Integration of the x402 extension with the broader Agentic Commerce reference implementation. |
| 2024-12-10 | draft | Negotiation Schema Update | Introduction of standardized negotiation flow schemas to handle multi-turn price bidding between agents. |
| 2024-11-04 | release | Initial Repository Commit | Initial public release of the x402 extension specification and core schema definitions on GitHub. |
