---
id: 9d2ed8fb-ae60-4ec9-b2a2-4737d7869af0
title: "OAuth Actor Profile for Delegation"
acronym: OAuth Actor Profile
status: Draft
organization: "IETF"
tags: [OAuth 2.0, Delegation, AI Agents, JWT, Token Exchange, Identity]
link: https://mcguinness.github.io/draft-mcguinness-oauth-actor-profile/draft-mcguinness-oauth-actor-profile.html
expired: false
created_at: 2026-04-01T18:49:21.573842+00:00
updated_at: 2026-04-01T18:49:21.573842+00:00
---

# OAuth Actor Profile for Delegation (OAuth Actor Profile)

**Status:** Draft | **Organization:** IETF

## Description
A common structure for the 'act' (actor) claim in OAuth 2.0 to represent delegation relationships uniformly across JWT assertion grants, access tokens, and transaction tokens. It specifically addresses multi-principal scenarios where AI agents or automated workloads act on behalf of users across organizational boundaries.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Karl McGuinness | Independent | Author | [link](https://mcguinness.github.io/) |

## Resources
| Type | Label | URL |
|------|-------|-----|
| primary_spec | Primary Specification (HTML) | https://mcguinness.github.io/draft-mcguinness-oauth-actor-profile/draft-mcguinness-oauth-actor-profile.html |
| other | RFC XML Source | https://mcguinness.github.io/draft-mcguinness-oauth-actor-profile/draft-mcguinness-oauth-actor-profile.xml |

## Tags
OAuth 2.0, Delegation, AI Agents, JWT, Token Exchange, Identity

## Latest Summary
The **OAuth Actor Profile for Delegation** is a proposed standard designed to provide a uniform structure for representing delegation relationships across various OAuth 2.0 token types. In modern deployments, human users often employ AI agents, automated workloads, or services to act on their behalf across organizational and trust-domain boundaries. while existing standards like RFC 8693 (Token Exchange) and RFC 9068 (JWT Access Tokens) provide building blocks, they lack a common profile for classifying actor entities and signaling support between authorization servers (AS) and resource servers (RS).

This specification addresses these gaps by:
*   **Standardizing the `act` (actor) claim:** Defining a consistent structure for delegation information within JWT assertion grants, access tokens, and Transaction Tokens.
*   **Introducing Machine-Readable Classification:** Defining the `sub_profile` claim to classify actor types (e.g., distinguishing between a service and a specific AI agent).
*   **Enhancing Security via Proof-of-Possession:** Specifying how key binding (DPoP) applies to both the current presenter and prior actors in a multi-step delegation chain.
*   **Establishing Discovery Mechanisms:** Defining metadata parameters that allow an AS and RS to advertise and negotiate support for this profile.
*   **Registry Updates:** Extending the OAuth Entity Profiles registry and updating metadata for actor classification to ensure interoperability across different vendor implementations.

By preserving actor semantics across token transformations, this profile enables more secure and transparent audit trails in complex, multi-principal scenarios.

## What's New
The latest activity centers on the initial publication of the **OAuth Actor Profile for Delegation** (draft-mcguinness-oauth-actor-profile). This draft introduces the `sub_profile` claim to provide machine-processable classification for actors. It also establishes critical processing rules for how Authorization Servers and Resource Servers should handle delegation chains, specifically focusing on preserving the integrity of the actor semantics when transitioning between different token formats like JWT access tokens and Transaction Tokens. Recent updates also include the definition of DPoP key binding mechanisms specifically for the "actor" in a delegation scenario.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2025-01-28 | draft | Initial Draft Release (v00) | Draft version 00 of the OAuth Actor Profile for Delegation is released, authored by Karl McGuinness. |
| 2025-01-28 | milestone | Metadata Parameter Registration | The specification registers new metadata parameters for Authorization Servers and Protected Resources to signal profile support. |
