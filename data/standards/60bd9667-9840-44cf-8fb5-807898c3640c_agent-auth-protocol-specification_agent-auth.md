---
id: 60bd9667-9840-44cf-8fb5-807898c3640c
title: "Agent Auth Protocol Specification"
acronym: Agent Auth
status: Draft
organization: "Better Auth"
tags: [authentication, ai-agents, identity, mcp, authorization, autonomous-agents, identity-provider]
link: https://github.com/better-auth/agent-auth-protocol/blob/main/content/specification/v1.0-draft.mdx
expired: false
created_at: 2026-03-30T14:10:38.030255+00:00
updated_at: 2026-03-30T14:10:38.030255+00:00
---

# Agent Auth Protocol Specification (Agent Auth)

**Status:** Draft | **Organization:** Better Auth

## Description
An implementation-oriented protocol for AI agent identity, registration, and capability access. It treats runtime AI agents as first-class principals with distinct identities and lifecycles, enabling secure delegation and autonomous operations.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Paola Estefanía de Campos | Better Auth | Author |  |
| Bereket Engida | Better Auth | Author |  |
| Taesu | Unknown | GitHub Contributor | [link](https://github.com/bytaesu) |

## Resources
| Type | Label | URL |
|------|-------|-----|
| primary_spec | Primary Specification | https://github.com/better-auth/agent-auth-protocol/blob/main/content/specification/v1.0-draft.mdx |
| documentation | Implementations and SDKs | https://better-auth.com/docs/sdks |
| github | GitHub Repository | https://github.com/better-auth/agent-auth-protocol |

## Tags
authentication, ai-agents, identity, mcp, authorization, autonomous-agents, identity-provider

## Latest Summary
The Agent Auth Protocol is an emerging specification designed to provide a secure and standardized way for AI agents to authenticate themselves when interacting with web services. Moving beyond traditional API keys, the protocol focuses on dynamic, short-lived, and verifiable identity for autonomous software agents. It aims to bridge the gap between human-centric authentication systems and the high-volume, automated nature of agentic workflows.

The protocol centers on three primary entities: the **Agent** (the software performing actions), the **Provider** (the identity issuer), and the **Service** (the resource the agent wants to access). Key features of the specification include automated handshakes, granular permissions (scopes) specifically tailored for AI actions, and non-repudiation through cryptographic signatures. By establishing a common language for agent identity, the standard aims to solve security risks associated with agents storing long-lived secrets and the technical hurdles of agents navigating "bottleneck" auth screens designed for humans.

Current efforts are focused on refining the v1.0 draft, which includes defining the token structure (likely based on JWTs) and the discovery mechanism for agent-capable endpoints. The project is hosted by the 'better-auth' organization, indicating a strong tie to modern web developer tooling and TypeScript-first architectures. Open questions remain regarding universal cross-provider interoperability and the handling of delegated authority when an agent acts on behalf of a specific human user versus an organization.

## What's New
The most recent activity involves the solidification of the **v1.0-draft** specification. Key updates include a more detailed definition of the handshake flow between agents and services, ensuring that agents can autonomously negotiate sessions without human intervention. The repository has seen increased documentation around "Agent Scopes," which allow services to restrict AI agents to specific, read-only, or limited-action roles. Additionally, there is ongoing work to integrate the protocol with existing auth frameworks, making it easier for developers to support "Agent Logins" alongside traditional OAuth and password-based methods.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2025-01-10 | other | Spec Refinement | Recent internal updates to the specification content including refined definitions for agent handshakes. |
| 2024-12-15 | draft | v1.0-draft Release | First public draft of the Version 1.0 specification released for community feedback. |
| 2024-11-01 | milestone | Project Initiation | Initial conceptualization and formation of the repository under the better-auth organization. |
