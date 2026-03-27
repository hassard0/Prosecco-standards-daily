---
id: b2067b9d-2d7b-435f-b89a-b80424911214
title: "Agent Message Protocol"
acronym: AMP
status: Draft
organization: "AMP"
tags: [AI Agents, Data Economy, Protocol, Validator, Interoperability]
link: https://github.com/AMProtocol/AMP/blob/main/validator/spec/v0.3.md
expired: false
created_at: 2026-03-23T18:24:29.953449+00:00
updated_at: 2026-03-23T19:09:50.439028+00:00
---

# Agent Message Protocol (AMP)

**Status:** Draft | **Organization:** AMP

## Description
AMP is an open protocol and registry designed for the AI agent data economy. It provides a specification for validators to ensure the integrity and interoperability of data exchanged between AI agents.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| AMProtocol Team | AMP | Author |  |
| BrandonWeber-Nymbl | Unknown | GitHub Contributor | [link](https://github.com/BrandonWeber-Nymbl) |

## Resources
| Type | Label | URL |
|------|-------|-----|
| primary_spec | Primary Specification (v0.3) | https://github.com/AMProtocol/AMP/blob/main/validator/spec/v0.3.md |
| github | GitHub Repository | https://github.com/AMProtocol/AMP |

## Tags
AI Agents, Data Economy, Protocol, Validator, Interoperability

## Latest Summary
The **Agent Message Protocol (AMP)** is an open standard designed to facilitate seamless communication and interoperability between autonomous AI agents and validator nodes. Developed by the AMProtocol community, it establishes a structured format for agents to exchange data, execute tasks, and verify actions within a decentralized or distributed environment. By providing a common interface, AMP aims to prevent ecosystem fragmentation and ensure that different agentic systems can collaborate regardless of their underlying architecture.

The core of the protocol (v0.3) defines how messages are structured, signed, and validated. Key components include a validator specification that ensures messages adhere to safety and business logic rules before being committed or acted upon. It addresses critical challenges in AI agent interactions, such as identity verification, message integrity, and standardized task handoffs. The protocol is currently in an active developmental phase, with the community focused on refining the validator logic and expanding the feature set for complex multi-agent workflows.

## What's New
The latest update, **version 0.3**, focuses heavily on the **Validator Specification**. This version introduces more rigorous schema validation for agent-to-agent messages, ensuring that all communications are cryptographically signed and formatted according to strict protocol rules. Significant improvements have been made to the `validator/spec` directory in the official repository, providing developers with a clearer roadmap for implementing validator nodes. Recent community activity has also centered on improving the project's documentation and establishing a more robust CI/CD pipeline for the protocol's reference implementation. Efforts are now shifting toward defining "Plugin" architectures that allow the protocol to be extended for specific industry use cases like DeFi and supply chain management.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2024-11-04 | release | AMP v0.3 Specification Release | Current stable draft released, introducing refined validator specifications and improved schema enforcement. |
| 2024-09-10 | draft | AMP v0.2 Draft Published | Major updates to the validator logic and message envelope structure. |
| 2024-07-22 | release | AMP v0.1 Release | Release of the initial version 0.1 of the Agent Message Protocol specification. |
| 2024-05-15 | milestone | AMP Project Inception | Initial conceptualization and gathering of community interest for a standardized agent communication layer. |
