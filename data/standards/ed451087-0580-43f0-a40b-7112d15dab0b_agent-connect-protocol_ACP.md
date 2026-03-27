---
id: ed451087-0580-43f0-a40b-7112d15dab0b
title: "Agent Connect Protocol"
acronym: ACP
status: Emerging
organization: "Agntcy"
tags: [ai agents, interoperability, protocol, communication]
link: https://spec.acp.agntcy.org/
expired: false
created_at: 2026-03-25T20:41:17.50676+00:00
updated_at: 2026-03-25T20:41:17.50676+00:00
---

# Agent Connect Protocol (ACP)

**Status:** Emerging | **Organization:** Agntcy

## Description
The Agent Connect Protocol (ACP) provides a standardized interface for AI agents to discover, connect, and communicate with each other. It defines the API structures necessary for cross-agent interoperability.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Agntcy Team | Agntcy | Author |  |

## Resources
| Type | Label | URL |
|------|-------|-----|
| primary_spec | API Reference | https://spec.acp.agntcy.org/ |
| documentation | OpenAPI Specification | https://spec.acp.agntcy.org/openapi.json |

## Tags
ai agents, interoperability, protocol, communication

## Latest Summary
The Agent Connect Protocol (ACP) is a standardized communication interface designed for the discovery, configuration, and execution of AI agents and workflows. It establishes a robust framework for managing both stateless and stateful interactions between clients and AI servers. The protocol is structured around four primary entities: Agents, Threads, Thread Runs, and Stateless Runs.

Central to ACP is the concept of 'Agents,' which are AI workflows that clients can trigger and manage. Each agent's specific capabilities, configuration requirements, and input/output schemas are defined in an ACP Descriptor. This allows for diverse agent types to coexist within a single standardized interface.

To support complex, multi-step interactions, ACP introduces 'Threads' and 'Thread Runs.' Threads serve as persistent data contexts (Thread State) that preserve continuity across multiple agent invocations. This stateful management enables advanced features such as granular debugging, history replaying, and session interruption. Every state change in a thread is tracked via 'Checkpoints' (UUIDs), allowing users to query history or resume from specific points in time. For simpler tasks, ACP supports 'Stateless Runs,' which represent one-off executions where the output is either a final result or a request for an interrupt.

The protocol utilizes a RESTful architecture, employing OpenAPI 3.1.1 for its specification. Key functionalities include searching for agents, managing thread lifecycles (creation, copying, and deletion), and retrieving detailed thread histories for context preservation. Validation and error handling are integrated into the spec through structured ErrorResponse models, ensuring predictable client-server communication.

## What's New
The Agent Connect Protocol has reached version **0.2.3**. Recent updates focus on refining the "Thread" and "Thread Run" management systems. Key capabilities now include the ability to **Copy Threads**, allowing developers to create new execution contexts from existing states and checkpoints. The specification also formalizes the **ACP Descriptor** model, which provides a standardized way for agents to describe their internal schemas for configuration, input, output, and interrupts. Additionally, the latest version utilizes **OpenAPI 3.1.1**, providing better support for complex JSON schemas and validation errors.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2024-11-20 | release | Release of ACP Version 0.2.3 | The current OpenAPI specification for Agent Connect Protocol is published under version 0.2.3. |
| 2024-11-20 | milestone | API Reference Site Launch | The protocol documentation is made available via an interactive Scalar API reference interface. |
