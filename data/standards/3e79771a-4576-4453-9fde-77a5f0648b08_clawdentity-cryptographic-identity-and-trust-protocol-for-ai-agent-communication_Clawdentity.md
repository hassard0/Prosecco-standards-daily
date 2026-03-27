---
id: 3e79771a-4576-4453-9fde-77a5f0648b08
title: "Clawdentity: Cryptographic Identity and Trust Protocol for AI Agent Communication"
acronym: Clawdentity
status: Draft
organization: "IETF"
tags: [AI agents, identity, cryptographic trust, Ed25519, proof of possession, agent-to-agent]
link: https://www.ietf.org/archive/id/draft-ravikiran-clawdentity-protocol-00.html
expired: false
created_at: 2026-03-23T17:54:54.749502+00:00
updated_at: 2026-03-23T19:10:33.401332+00:00
---

# Clawdentity: Cryptographic Identity and Trust Protocol for AI Agent Communication (Clawdentity)

**Status:** Draft | **Organization:** IETF

## Description
A cryptographic identity and trust layer for AI agent-to-agent communication. It provides per-agent Ed25519 identity, registry-issued credentials, and bilateral trust establishment via pairing ceremonies.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Ravi Kiran Vemula | CAW | Author |  |

## Resources
| Type | Label | URL |
|------|-------|-----|
| primary_spec | Primary Specification (Internet-Draft) | https://www.ietf.org/archive/id/draft-ravikiran-clawdentity-protocol-00.html |
| other | XML Source | https://www.ietf.org/archive/id/draft-ravikiran-clawdentity-protocol-00.xml |

## Tags
AI agents, identity, cryptographic trust, Ed25519, proof of possession, agent-to-agent

## Latest Summary
Clawdentity is a cryptographic identity and trust protocol designed specifically for secure communication between AI agents. The protocol addresses vulnerabilities in current multi-agent systems that rely on shared bearer tokens, where a single leak can compromise an entire network. By introducing a per-agent Ed25519 identity model, Clawdentity ensures that every request is signed and verifiable, allowing for selective revocation of individual agents without disrupting the broader infrastructure.

The architecture is built around four primary roles: the **Registry** (a central authority for issuing credentials and managing revocation lists), the **Proxy** (an edge service that enforces trust policies and relays messages), the **Connector** (a local bridge that handles cryptographic operations for the agent), and the **Agent** itself. This separation of concerns allows AI agents to remain framework-agnostic while benefiting from robust security features like proof-of-possession (PoP).

Key technical components include the **Agent Identity Token (AIT)**—a signed JWT that binds an agent's Decentralized Identifier (DID) to its public key—and a bilateral trust establishment process known as a **pairing ceremony**. Communication is conducted over authenticated WebSocket relays, ensuring that backend services remain private and "zero-trust" principles are maintained. The protocol specifically mandates the use of Ed25519 for all signing operations and prohibits weaker algorithms, aiming for a high-security baseline for the future of agentic ecosystems.

## What's New
The protocol has recently been formalized in its first Internet-Draft (`draft-ravikiran-clawdentity-protocol-00`). Notable new features include the introduction of the **Agent Identity Token (AIT)**, which utilizes the `cnf` (confirmation) claim pattern to bind identities to specific Ed25519 keys. The protocol also establishes a mandatory **ULID** format for unique identifiers and identifies **Ed25519** as the sole required signing algorithm. Additionally, the draft outlines a new "Pairing Ceremony" for bilateral trust establishment between agents, moving away from centralized or self-certified trust models in favor of human-anchored approvals.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2026-02-21 | release | Publication of draft-ravikiran-clawdentity-protocol-00 | The initial specification for the Clawdentity protocol is published as an Internet-Draft. |
| 2026-02-21 | decision | Definition of did:cdi Identity Scheme | The identity model moves to a custom 'did:cdi' scheme using ULIDs for unique identification. |
