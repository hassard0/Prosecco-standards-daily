---
id: f7eb3167-8cc0-4162-85a0-217ccbc8d4e9
title: "Agent User Interaction Protocol"
acronym: AG-UI
status: Draft
organization: "Tawk it AI"
tags: [Protocol, Agents]
link: https://docs.ag-ui.com/
expired: false
created_at: 2026-03-22T18:33:31.70173+00:00
updated_at: 2026-03-23T00:41:06.117885+00:00
---

# Agent User Interaction Protocol (AG-UI)

**Status:** Draft | **Organization:** Tawk it AI

## Description
AG-UI is a lightweight, event-based protocol that standardizes how AI agents connect to user-facing applications. Built for simplicity and flexibility, it enables seamless integration between AI agents, real time user context, and user interfaces.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Markus Ecker | Unknown | GitHub Contributor | [link](https://github.com/mme) |
| Atai Barkai | CopilotKit.ai | GitHub Contributor | [link](https://github.com/ataibarkai) |

## Resources
| Type | Label | URL |
|------|-------|-----|
| documentation | TypeScript SDK | https://docs.ag-ui.com/sdk/js/core/overview |
| documentation | Python SDK | https://docs.ag-ui.com/sdk/python/core/overview |
| github | Documentation Repository | https://github.com/ag-ui-protocol/docs |

## Tags
Protocol, Agents

## Latest Summary
The **Agent User Interaction (AG-UI) Protocol** is a standardized communication framework designed to facilitate seamless interactions between AI agents and human users. The protocol addresses a critical gap in the AI landscape: while agents are becoming increasingly autonomous, they often lack a consistent, cross-platform method for requesting user input, seeking clarifications, or providing structured status updates. AG-UI provides a unified schema and a set of SDKs (currently in TypeScript and Python) that allow developers to build "UI-aware" agents. These agents can emit interaction requests that are rendered consistently across different frontend clients, ensuring that whether an agent lives in a web app, a CLI, or a mobile environment, the user interaction remains predictable and robust. 

Key architectural components include **Request-Response cycles** for user input, **Status Streams** for long-running agent tasks, and **Structured Payloads** for complex data types like forms or file pickers. By decoupling the agent's logic from the specific UI implementation, the protocol enables a "write once, interact anywhere" model for agentic workflows.

## What's New
Recent developments in the AG-UI Protocol focus on expanding cross-language compatibility. The **TypeScript SDK** recently received an update improving the handling of asynchronous user feedback, while the **Python SDK** has moved into a more stable preview phase with better support for streaming status updates. Additionally, the documentation repository was reorganized to provide a shared specification folder, ensuring that both SDKs adhere to the same schema versions. There is also a newly introduced 'UI-Metadata' field in the protocol that allows agents to suggest specific rendering components (like sliders or multi-select dropdowns) to the client.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2025-01-10 | milestone | Standardization Update v0.4.0 | Major documentation update (v0.4.0) standardized core concepts such as 'Status Streams' across both JS and Python implementations. |
| 2024-11-20 | draft | Python SDK Initial Draft | Introduction of the Python SDK to support the broader AI/ML developer community using LangChain and AutoGPT-style frameworks. |
| 2024-11-02 | release | TypeScript SDK Alpha Release | Alpha release of the ag-ui-sdk for TypeScript, enabling core interaction concepts in Node.js and Browser environments. |
| 2024-10-15 | release | Protocol Project Launch | Initial commit and public announcement of the Agent User Interaction Protocol and its core documentation repository. |
