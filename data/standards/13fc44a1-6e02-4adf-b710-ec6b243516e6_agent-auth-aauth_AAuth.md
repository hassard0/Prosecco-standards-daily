---
id: 13fc44a1-6e02-4adf-b710-ec6b243516e6
title: "Agent Auth (AAuth)"
acronym: AAuth
status: Draft
organization: "Dick Hardt Consulting"
tags: [AI Agents, Authentication, Authorization, Security, Identity]
link: https://github.com/dickhardt/AAuth/blob/main/draft-hardt-aauth.html
expired: false
created_at: 2026-03-23T02:32:13.023556+00:00
updated_at: 2026-03-23T02:50:09.439499+00:00
---

# Agent Auth (AAuth) (AAuth)

**Status:** Draft | **Organization:** Dick Hardt Consulting

## Description
AAuth (Agent Auth) is a protocol designed to enable secure authentication and authorization for autonomous AI agents. It provides a technical framework for agents to prove their identity and obtain permissions to act on behalf of users or organizations.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Dick Hardt | Dick Hardt Consulting | Author | [link](https://github.com/dickhardt) |

## Resources
| Type | Label | URL |
|------|-------|-----|
| github | AAuth GitHub Repository | https://github.com/dickhardt/AAuth |
| documentation | Specification HTML (Source) | https://github.com/dickhardt/AAuth/blob/main/draft-hardt-aauth.html |

## Tags
AI Agents, Authentication, Authorization, Security, Identity

## Latest Summary
Agent Auth (AAuth) is an emerging authentication and authorization protocol designed specifically for the era of autonomous agents and automated systems. Developed by Dick Hardt, the protocol addresses the limitations of traditional OAuth 2.0 and OpenID Connect flows, which often rely on interactive user-browser sessions that are incompatible with autonomous software agents. AAuth provides a mechanism for agents to authenticate to services and for users to delegate specific, time-limited, and context-aware authority to these agents without sharing long-lived credentials. 

The standard focuses on 'Agent-to-Agent' and 'Agent-to-Service' interactions, emphasizing security through cryptographic binding and minimized attack surfaces. Unlike previous standards that treated the "client" as a singular web or mobile app, AAuth recognizes the complex orchestration of multiple agents working on a user's behalf. Key technical components include agent discovery, capability-based authorization, and non-interactive proof of identity. The protocol aims to streamline the developer experience for building AI-driven workflows while maintaining high standards for privacy and user control over data access. At its core, it enables a user to say "allow this agent to perform X task on my behalf" in a way that the receiving service can verify and enforce programmatically.

## What's New
Recent activity in the AAuth project has focused on stabilizing the core specification draft (`draft-hardt-aauth`). Significant recent updates involve clarifying the **discovery metadata** for agents, ensuring that services can programmatically determine an agent's capabilities and security requirements. There has also been work on defining the **Request Object** structure, which allows agents to pass signed authentication requests that are tamper-proof. The community is currently discussing the integration of AAuth with existing Verifiable Credential (VC) standards to allow agents to present identity proofs without a centralized identity provider. Documentation has been expanded to include more concrete examples of JSON payloads for agent registration and token exchange flows.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2024-10-18 | milestone | Latest Specification Update | Most recent significant update to the HTML draft of the specification in the main branch. |
| 2024-07-22 | decision | Security Model Refinement | Refinement of the cryptographic requirements for agent signatures and proof-of-possession. |
| 2024-06-15 | draft | Draft Update: Agent Flows | Updates to the draft to include more detailed flows for agent-to-agent communication. |
| 2024-05-30 | draft | Initial Specification Draft | The first draft of the AAuth specification (draft-hardt-aauth-00) was added to the repository. |
| 2024-05-13 | milestone | AAuth Repository Creation | Dick Hardt created the initial AAuth repository on GitHub to house the protocol's development. |
