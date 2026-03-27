---
id: ab8885e0-80dc-4cf8-b56d-b903a5316513
title: "Brokered Agent Network for DNS AI Discovery (BANDAID)"
acronym: BANDAID
status: Draft
organization: "IETF"
tags: [DNS, AI Agents, Service Discovery, Agent-to-Agent, SVCB, DNS-SD, BANDAID]
link: https://datatracker.ietf.org/doc/draft-mozleywilliams-dnsop-bandaid/
expired: false
created_at: 2026-03-23T17:57:27.679148+00:00
updated_at: 2026-03-23T19:10:28.965683+00:00
---

# Brokered Agent Network for DNS AI Discovery (BANDAID) (BANDAID)

**Status:** Draft | **Organization:** IETF

## Description
A method for utilizing the Domain Name System (DNS) to facilitate scalable and interoperable discovery, trust signaling, and metadata exchange between AI agents. It defines a structured DNS namespace and Service Binding (SVCB) record usage model to support capability advertisement without requiring new DNS protocol values.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Jim Mozley | IETF | Author |  |
| Nic Williams | IETF | Author |  |
| Behcet Sarikaya | IETF | Author |  |
| Roland Schott | IETF | Author |  |

## Resources
| Type | Label | URL |
|------|-------|-----|
| primary_spec | Primary Specification (HTML) | https://www.ietf.org/archive/id/draft-mozleywilliams-dnsop-bandaid-00.html |
| other | Primary Specification (TXT) | https://www.ietf.org/archive/id/draft-mozleywilliams-dnsop-bandaid-00.txt |
| other | Document History | https://datatracker.ietf.org/doc/draft-mozleywilliams-dnsop-bandaid/history/ |
| other | Replacement Document: DNS for AI Discovery | https://datatracker.ietf.org/doc/draft-mozleywilliams-dnsop-dnsaid/ |

## Tags
DNS, AI Agents, Service Discovery, Agent-to-Agent, SVCB, DNS-SD, BANDAID

## Latest Summary
The **Brokered Agent Network for DNS AI Discovery (BANDAID)** is a proposed IETF standard designed to facilitate the discovery, trust signaling, and metadata exchange between AI agents using the existing Domain Name System (DNS) infrastructure. The specification addresses the emerging need for a scalable, interoperable method for AI agents to locate one another and verify authorization without requiring centralized registries or proprietary directories.

BANDAID operates by defining a structured DNS namespace, typically a leaf zone convention such as `_agents.example.com`. Within this zone, it utilizes **Service Binding (SVCB)** records to encode application-specific metadata and operational parameters. By leveraging SVCB records, agents can retrieve critical information about a peer's capabilities and connection endpoints prior to establishing a session. The framework heavily relies on established DNS security protocols, including **DNSSEC** for integrity and **DANE** for binding identities to certificates.

A key component of the proposal is **Domain Control Validation (DCV)**, which establishes a best practice for proving that an agent is authorized to act on behalf of a specific domain. The architecture is designed to be "DNS-native," meaning it introduces no changes to the structure of DNS messages and requires no new operation codes or resource record types. This approach ensures immediate compatibility with existing internet infrastructure while providing a decentralized and sovereign method for cross-organizational agent discovery. The draft also provides implementation guidance for AI operators, consumers, and developers, emphasizing performance optimizations like aggressive caching and prefetching.

## What's New
The standard has recently undergone a significant rebranding and evolution. While the original proposal was introduced as **BANDAID**, the latest activity (January 2025) shows a transition to a new document title: **DNS for AI Discovery (DNS-AID)**. 

The updated draft, `draft-mozleywilliams-dnsop-dnsaid-01`, clarifies that the mechanism's primary role is to indicate which access protocols should be used and the format of agent information, rather than defining the information's internal structure. This shift narrows the scope to focus specifically on the discovery mechanism. Recent discussions also touch upon the relationship between this discovery method and other emerging AI protocols, ensuring that the DNS-based discovery layer remains strictly separated from the application-layer agent communication protocols.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2026-04-19 | deadline | Document Expiration Date | The initial BANDAID -00 draft is set to expire according to IETF's six-month validity rule. |
| 2025-01-20 | milestone | Rebranded to DNS-AID | The standard is rebranded and updated as "DNS for AI Discovery (DNS-AID)" (draft-mozleywilliams-dnsop-dnsaid-01). |
| 2024-10-16 | release | Initial Draft Released | The initial draft of the BANDAID specification (draft-mozleywilliams-dnsop-bandaid-00) is released. |
