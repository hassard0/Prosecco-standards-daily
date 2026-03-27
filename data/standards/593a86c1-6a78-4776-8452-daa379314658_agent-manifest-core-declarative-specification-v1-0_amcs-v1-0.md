---
id: 593a86c1-6a78-4776-8452-daa379314658
title: "Agent Manifest — Core Declarative Specification v1.0"
acronym: AMCS/v1.0
status: Approved
organization: "Agent Manifest Project"
tags: [autonomous agents, governance, manifest, alignment, transparency, JSON-Schema]
link: https://agent-manifest-spec.org/spec/v1.0/agent_manifest_v1.0.html
expired: false
created_at: 2026-03-23T17:58:10.652692+00:00
updated_at: 2026-03-23T19:09:45.766837+00:00
---

# Agent Manifest — Core Declarative Specification v1.0 (AMCS/v1.0)

**Status:** Approved | **Organization:** Agent Manifest Project

## Description
A machine-readable, execution-agnostic standard that establishes the minimum declaration requirements for autonomous systems. It defines mandatory structural elements such as identity, purpose, autonomy levels, and stopping authority that must be present before an agent's execution.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Hernán Alfredo Capucci | Independent Research | Author/Researcher |  |

## Resources
| Type | Label | URL |
|------|-------|-----|
| primary_spec | Primary Specification | https://agent-manifest-spec.org/spec/v1.0/agent_manifest_v1.0.html |

## Tags
autonomous agents, governance, manifest, alignment, transparency, JSON-Schema

## Latest Summary
The **Agent Manifest — Core Declarative Specification v1.0** is a machine-readable, execution-agnostic standard designed to establish governance for autonomous systems. It introduces a formal **Declaration Layer** that requires software agents to declare their identity, purpose, and operational boundaries before they are permitted to interact with external systems or users. The core philosophy of the specification is that *legitimacy must precede execution*, addressing the growing asymmetry between rapid AI deployment and the lack of structured authority frameworks.

Key components of a conformant manifest include the identification of a **Responsible Party** (the accountable entity), a defined **Autonomy Level**, and a **Stopping Authority** (the mechanism or entity capable of terminating the agent's actions). The specification also covers "Negative Scope"—explicit declarations of what an agent is *not* permitted to do—alongside audit posture and data handling commitments.

Architecturally, the standard separates the ecosystem into three distinct layers:
1. **Declaration Layer**: Where the manifest resides (the focus of this spec).
2. **Enforcement Layer**: Policy engines or regulatory frameworks that evaluate the manifest.
3. **Execution Layer**: The runtime environment where the agent actually operates.

While the specification provides a normative JSON Schema to ensure structural validity and coherence, it explicitly does not define runtime behavior, enforcement mechanisms, or safety guarantees. It serves as a foundational "governance primitive" for the AI era.

## What's New
The February 2026 release of **Version 1.0** marks the initial formalization of the Agent Manifest standard. Key highlights of this version include:

*   **Mandatory Structural Elements**: Requirements for identity, responsible party, and declared purpose.
*   **Autonomy & Control**: Formal definitions for "Autonomy Levels" and the requirement for a "Stopping Authority."
*   **Layered Architectural Model**: The introduction of the "Declaration Layer" as a distinct entity from enforcement and execution.
*   **Normative JSON Schema**: A technical foundation for developers to validate manifests for structural coherence.
*   **Negative Scope**: A new requirement for agents to explicitly declare operational boundaries and constraints.
*   **Execution-Agnostic Design**: The spec is designed to work across different AI architectures, from single agents to complex multi-agent workflows.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2026-02-01 | release | Specification Release (v1.0) | The Core Declarative Specification v1.0 is published for independent research. |
