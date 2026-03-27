---
id: 3733ff10-b4db-4091-bbb4-10a596a3e9ab
title: "Agora Protocol for Two-Party JSON Exchanges"
acronym: Agora Protocol
status: Draft
organization: "Agora Protocol"
tags: [JSON, communication protocol, stateless, stateful, HTTPS, two-party exchange]
link: https://agoraprotocol.org/docs/protocol/specification
expired: false
created_at: 2026-03-23T23:04:34.74888+00:00
updated_at: 2026-03-24T00:47:48.083899+00:00
---

# Agora Protocol for Two-Party JSON Exchanges (Agora Protocol)

**Status:** Draft | **Organization:** Agora Protocol

## Description
A lightweight JSON-based framework for two-party exchanges supporting single-round and multi-round stateful conversations. It includes optional protocol document references via SHA1 hashes to impose domain-specific data constraints.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Samuele Marro | Agora Protocol | Author |  |
| Shayekh Islam | Unknown | GitHub Contributor | [link](https://github.com/ShayekhBinIslam) |

## Resources
| Type | Label | URL |
|------|-------|-----|
| primary_spec | Agora Protocol Specification | https://agoraprotocol.org/docs/protocol/specification |
| github | Agora Protocol Python Implementation | https://github.com/agora-protocol/python |
| discord | Agora Protocol Discord | https://discord.gg/MXmfhwQ4FB |
| documentation | Getting Started Guides | https://agoraprotocol.org/docs/getting-started |
| documentation | Python Reference | https://agoraprotocol.org/docs/python/common/core |

## Tags
JSON, communication protocol, stateless, stateful, HTTPS, two-party exchange

## Latest Summary
The **Agora Protocol** is a lightweight, JSON-based framework designed for structured two-party data exchanges between a client and a server. Structured similarly to an IETF RFC, the protocol provides a consistent JSON envelope for requests and responses, accommodating both stateless (single-round) and stateful (multi-round) conversations. A key feature of the protocol is the use of "Protocol Documents"—text files identified by unique SHA1 hashes—which allow developers to impose domain-specific constraints and structures on message bodies.

The protocol aims for simplicity and extensibility while maintaining a clear separation between transport-level and application-level concerns. It explicitly requires all exchanges to occur over **HTTPS** using HTTP `POST` methods with `application/json` content types to ensure confidentiality. While it handles the structure and error conventions of messages, it remains agnostic toward authentication, authorization, and advanced privacy mechanisms, leaving those to the implementer. The project also maintains a reference implementation in Python and a community Discord server for developers.

## What's New
The Agora Protocol is currently at **Version 0.2**, functioning as a Proposed Standard. Recent updates emphasize the transition to a more professional, RFC-style structure (referencing RFC 2119 and RFC 8174) for its normative language. Key technical focuses in the latest draft include the refinement of 'Conversation identifiers' for state management and the strictly enforced use of SHA1 hashes for 'Protocol Documents.' 

The project has also expanded its ecosystem with a specialized **Python implementation** and a growing community presence on Discord, which now hosts over 170 members. The documentation has been updated with a 'Beginner-Friendly' version alongside the formal technical standard to lower the barrier for new implementers.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2025-03-24 | draft | Agora Protocol v0.2 Documentation Active | The current documentation reflects version 0.2 of the protocol specification and Docusaurus site. |
| 2025-03-23 | release | Discord Infrastructure Release Channel Active | Stable version hash and build number 514705 referenced in the project's community environment data. |
| 2025-01-01 | milestone | Copyright and Initial Documentation Year | Copyright notice established for the protocol by Samuele Marro. |
