---
id: 2746ec5a-6edc-478a-bd67-d33c7737eca3
title: "AAuth - Agentic Authorization OAuth 2.1 Extension"
acronym: AAuth
status: Draft
organization: "IETF"
tags: [OAuth 2.1, AI Agents, Authorization, Agentic AI, Security]
link: https://www.ietf.org/archive/id/draft-patwhite-aauth-00.html
expired: false
created_at: 2026-03-23T02:26:40.189275+00:00
updated_at: 2026-03-23T02:50:04.411755+00:00
---

# AAuth - Agentic Authorization OAuth 2.1 Extension (AAuth)

**Status:** Draft | **Organization:** IETF

## Description
An OAuth 2.1 extension defining the Agent Authorization Grant for confidential AI agents to request end-user consent and obtain access tokens via polling, SSE, or WebSockets. It introduces natural-language descriptions and a 'reason' parameter specifically for agentic workflows.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Pat White | IETF | Author |  |

## Resources
| Type | Label | URL |
|------|-------|-----|
| documentation | Datatracker | https://datatracker.ietf.org/doc/draft-patwhite-aauth/ |
| other | XML Source | https://www.ietf.org/archive/id/draft-patwhite-aauth-00.xml |

## Tags
OAuth 2.1, AI Agents, Authorization, Agentic AI, Security

## Latest Summary
The **Agentic Authorization (AAuth)** extension is a proposed OAuth 2.1 protocol designed specifically for **confidential agent clients**, such as autonomous software processes or AI agents, that possess long-lived identities. While heavily inspired by the OAuth 2.0 Device Authorization Grant (RFC 8628), AAuth is optimized for "agentic" workflows where an autonomous process needs to request delegated access to a user's resources.

Key features of the standard include:
*   **Asynchronous Token Retrieval**: Unlike standard web flows that rely on redirects, AAuth allows agents to receive access tokens via HTTP polling, Server-Sent Events (SSE), or WebSockets. This supports long-running or backend processes that cannot handle browser-based UI rendering.
*   **Human-in-the-Loop Consent**: The protocol introduces a `reason` parameter, allowing the agent to provide a natural-language explanation of why it is requesting access. This "contextual authorization" is intended to be displayed to the user during the approval process.
*   **Decoupled Scope Descriptions**: The standard encourages Resource Servers (RS) to publish human-readable descriptions of scopes at a `.well-known/aauth.json` endpoint. The Authorization Server (AS) fetches these descriptions to provide users with clear information about what permissions the agent is seeking.
*   **Simplified Client Interaction**: The agent is not responsible for handling redirects or the user interface. It requests authorization, gets a `request_code`, and then waits for the token to be issued once the user completes the consent flow through a separate out-of-band channel (e.g., a mobile app or chat notification).

The draft is currently in its initial "00" state as an individual Internet-Draft, targeting the "Authorization" area of the IETF.

## What's New
The **AAuth - Agentic Authorization OAuth 2.1 Extension** is a newly introduced draft (version 00). It establishes a new OAuth grant type: `urn:ietf:params:oauth:grant-type:agent_authorization`. 

The most significant recent technical specifications include:
*   **Three Retrieval Methods**: Official support for obtaining tokens via **HTTP Polling**, **Server-Sent Events (SSE)**, and **WebSockets**, providing flexible integration for different agent architectures.
*   **Reason Parameter**: A new metadata field that agents MUST provide to explain the intent of the request to the end user.
*   **Resource Server Discovery**: A new requirement for Resource Servers to host `.well-known/aauth.json` to provide natural-language scope descriptions.
*   **Request Code Handle**: Introduction of a `request_code` returned by the Authorization Server to track the asynchronous consent process.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2025-02-13 | draft | Initial Draft Submission (v00) | The initial individual Internet-Draft (version 00) for the AAuth extension was submitted to the IETF. |
