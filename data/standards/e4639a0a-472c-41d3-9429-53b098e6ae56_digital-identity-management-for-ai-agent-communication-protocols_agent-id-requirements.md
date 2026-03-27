---
id: e4639a0a-472c-41d3-9429-53b098e6ae56
title: "Digital Identity Management for AI Agent Communication Protocols"
acronym: Agent ID Requirements
status: Draft
organization: "IETF"
tags: [AI Agents, Digital Identity, Communication Protocols, Identity Management, Interoperability]
link: https://www.ietf.org/archive/id/draft-yl-agent-id-requirements-00.html
expired: false
created_at: 2026-03-23T02:55:19.142642+00:00
updated_at: 2026-03-23T03:10:56.727216+00:00
---

# Digital Identity Management for AI Agent Communication Protocols (Agent ID Requirements)

**Status:** Draft | **Organization:** IETF

## Description
A specification defining the requirements for digital identity management within AI agent communication protocols. It aims to establish a secure, interoperable foundation for connecting agents with users, tools, and other entities in future networks.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Kehan Yao | China Mobile | Author |  |
| Peng Liu | China Mobile | Author |  |

## Resources
| Type | Label | URL |
|------|-------|-----|
| documentation | Datatracker | https://datatracker.ietf.org/doc/draft-yl-agent-id-requirements/ |
| other | XML Source | https://www.ietf.org/archive/id/draft-yl-agent-id-requirements-00.xml |

## Tags
AI Agents, Digital Identity, Communication Protocols, Identity Management, Interoperability

## Latest Summary
The **Digital Identity Management for AI Agent Communication Protocols** is a proposed standard aimed at establishing a universal, secure, and interoperable framework for identifying AI agents. As AI agents transition from software assistants to "embodied AI" (such as humanoid robots and autonomous vehicles), there is a critical need for a standardized way to distinguish these entities in a digital context. The draft defines an AI Agent Digital Identity as a representation containing three primary components: a unique identifier, specific attributes (skills and capabilities), and key credentials for security.

Key functional requirements outlined in the documentation include:
*   **Global Uniqueness:** Agents must possess a globally unique identifier for dynamic location and identification across different network domains.
*   **User Binding:** Because agents often act on behalf of humans, their identity must support links to an associated user to facilitate authorization.
*   **Skill and Capability Mapping:** The standard seeks to define multi-modal capabilities (voice, text, video) and specific "skills" that can be verified and utilized during agent-to-agent or agent-to-human communication.
*   **Security Frameworks:** The standard addresses complex authorization models, including "On-Behalf-Of" (OBO) scenarios where an agent might need to prove delegation from a human user or another agent.
*   **Discovery Mechanisms:** Requirements for registration and synchronization across intra-domain and inter-domain repositories to allow agents to find and interact with one another autonomously.

The initiative bridges existing definitions from the ITU-T and 3GPP, seeking to create a cross-industry foundation for the "new citizens" of future networks. This protocol is intended to replace or augment current GUI-based human-machine interactions with autonomous, intent-based communication.

## What's New
The most recent development is the publication of **draft-yl-agent-id-requirements-00** on July 1, 2025. This document marks the formal introduction of requirements for AI agent digital identity within the IETF framework. Specifically, it introduces the concept of "User Binding," ensuring that AI agents can be legally and technically linked to their human owners. It also proposes a three-tier authorization model: **Agent Authorization** (self-representation), **Delegation Authorization** (acting for a user), and **User Authorization** (step-up verification where the agent facilitates direct user consent). These updates aim to address security gaps in autonomous agent-to-agent transactions that current identity protocols do not fully cover.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2025-07-01 | draft | Initial Internet-Draft Submission | The initial draft 'draft-yl-agent-id-requirements-00' is submitted to the IETF by authors from China Mobile. |
| 2024-01-01 | other | Market Growth Projections for Embodied AI | GGII predicts the global humanoid robot market will reach $1.017 billion, signaling the need for agent communication standards. |
