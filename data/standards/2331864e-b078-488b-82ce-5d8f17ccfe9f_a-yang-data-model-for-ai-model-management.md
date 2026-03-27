---
id: 2331864e-b078-488b-82ce-5d8f17ccfe9f
title: "A YANG Data Model for AI Model Management"
status: Backlog
organization: "IETF"
tags: [AI, ML, Networking, Management, YANG, Data Model, Draft]
link: https://datatracker.ietf.org/wg/netmod/documents
expired: false
created_at: 2026-03-24T22:17:20.199709+00:00
updated_at: 2026-03-25T02:59:31.736751+00:00
---

# A YANG Data Model for AI Model Management

**Status:** Backlog | **Organization:** IETF

## Description
This document defines a YANG data model for managing Artificial Intelligence (AI) models in network environments, enabling automated configuration and monitoring of AI model lifecycle.

## Resources
| Type | Label | URL |
|------|-------|-----|
| primary_spec | Document List | https://datatracker.ietf.org/wg/netmod/documents/ |
| mailing_list | Mailing List Archive | https://mailarchive.ietf.org/arch/browse/netmod/ |
| documentation | Meeting Materials | https://datatracker.ietf.org/wg/netmod/meetings/ |
| other | Group History | https://datatracker.ietf.org/wg/netmod/history/ |

## Tags
AI, ML, Networking, Management, YANG, Data Model, Draft

## Latest Summary
The "A YANG Data Model for AI Model Management" is a standardizing effort within the IETF Network Modeling (NETMOD) Working Group. Its primary objective is to define a unified YANG data model that facilitates the lifecycle management of Artificial Intelligence (AI) and Machine Learning (ML) models across networking infrastructure. This model aims to provide a structured way to discover, deploy, update, and monitor AI/ML models on network devices and controllers.

Key components of the model typically include definitions for model metadata (such as versioning, framework types, and training history), operational states, and administrative actions like model loading or offloading. By standardizing these interactions, the IETF seeks to ensure interoperability between different vendors' AI-driven networking solutions and management systems. 

Current discussions within the NETMOD group involve integrating these AI-specific modules with existing YANG versioning standards and semver (Semantic Versioning) strategies to ensure long-term stability and compatibility as AI models evolve rapidly. The work is part of a broader push to incorporate "AIOps" and automated intelligence into the management plane of modern networks.

## What's New
Recent activity in the NETMOD Working Group focuses on refining the underlying versioning mechanics that will support AI Model Management. In March 2026, there was significant movement regarding **YANG Semantic Versioning (Semver)** support within the `pyang` toolset, which is critical for managing the lifecycle of rapidly iterating AI models. Additionally, the group is processing early Operational Directorate (Opsdir) reviews for related modeling drafts, ensuring that the management frameworks remain consistent with IETF operational standards. Discussions emphasize the need for robust IANA guidance to handle the increasing complexity of new YANG module registrations.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2026-03-25 | other | Opsdir Review Activity | Early Opsdir review feedback provided for related sub-interface and VLAN model drafts within the NETMOD group. |
| 2026-03-23 | decision | Versioning and Semver Discussion | Active discussion on the NETMOD mailing list regarding proposed pyang changes for YANG module versioning and Semver integration. |
| 2026-03-23 | draft | IANA Guidance Update | New version notification for IANA YANG guidance drafts, impacting how modules like AI Model Management are registered. |
