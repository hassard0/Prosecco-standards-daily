---
id: 4d0fa0cd-4b02-42d6-8fc8-130b2348391d
title: "SCIM Agents and Agentic Applications Extension"
acronym: SCIM Agent Extension
status: Draft
organization: "IETF"
tags: [SCIM, Identity Management, AI Agents, Agentic Applications, Workloads, Interoperability]
link: https://www.ietf.org/archive/id/draft-abbey-scim-agent-extension-00.html
expired: false
created_at: 2026-03-23T18:23:43.060539+00:00
updated_at: 2026-03-23T19:10:52.703758+00:00
---

# SCIM Agents and Agentic Applications Extension (SCIM Agent Extension)

**Status:** Draft | **Organization:** IETF

## Description
This document describes a SCIM 2.0 extension for agents and agentic applications, including extensions to core User and Group objects and new resource types. It aims to provide interoperability between identity providers and agentic constructs while reducing the need for new specialized protocols.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Macy Abbey | Okta | Author |  |
| Rafael S. Cohen | Okta | Author |  |

## Resources
| Type | Label | URL |
|------|-------|-----|
| primary_spec | Internet-Draft HTML | https://www.ietf.org/archive/id/draft-abbey-scim-agent-extension-00.html |
| other | RFC XML Source | https://www.ietf.org/archive/id/draft-abbey-scim-agent-extension-00.xml |
| working_group | SCIM Working Group | https://datatracker.ietf.org/wg/scim/about/ |

## Tags
SCIM, Identity Management, AI Agents, Agentic Applications, Workloads, Interoperability

## Latest Summary
The **SCIM Agents and Agentic Applications Extension** is a proposed extension to the System for Cross-domain Identity Management (SCIM) 2.0 protocol. Its primary objective is to enable the management of AI agents and agentic applications using existing SCIM infrastructure, thereby reducing the need for new, complex identity protocols in the AI space.

The extension introduces several key components:
*   **New Resource Types**: It defines a dedicated `Agent` resource type, distinct from traditional users or software workloads. This reflects the unique nature of agents which may exhibit unpredictable behavior due to their reliance on AI models.
*   **Schema Extensions**: It provides extensions to the `ServiceProviderConfig` to allow SCIM servers to advertise support for agents and agentic applications.
*   **Agent Attributes**: The proposed `Agent` schema includes standard identity attributes (id, name, externalId) alongside agent-specific fields such as `agentType`, `protocols` (for communication capabilities), and `applications` (to define trust boundaries).
*   **Interoperability**: The draft suggests that if a server does not yet support the dedicated agent resource, clients should link agent-related User objects using the `LinkedObject` pattern from the PAM extension (`draft-grizzle-scim-pam-ext-01`).

By leveraging SCIM, the standard aims to provide a stable path for cross-domain agent management and discovery, allowing emerging AI standards to focus on novel functionalities rather than identity plumbing.

## What's New
The extension is currently in its first iteration (**draft-00**). The most recent updates focus on defining the core `Agent` resource type and the mechanisms for SCIM Service Providers to advertise support via `ServiceProviderConfig`. 

Key recent additions include:
*   **Agent Filtering**: Guidance for service providers to implement filtering on `name` and `externalId`.
*   **Protocol Support**: Inclusion of a `protocols` multi-valued attribute to describe how an agent can be reached (supporting agent-to-agent or human-to-agent communication).
*   **Relationship Mapping**: Explicitly linking agents to "Agentic Applications" to define trust boundaries.
*   **Reference to PAM**: Integration with `draft-grizzle-scim-pam-ext` for backward compatibility when dedicated agent resources aren't available.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2025-10-16 | release | Initial Draft Publication (00) | The initial version of the Internet-Draft (draft-abbey-scim-agent-extension-00) was published. |
