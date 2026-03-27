---
id: cd7f9193-ec29-46c8-b350-0a546fd25425
title: "Agent Protocol"
acronym: Agent Protocol
status: Emerging
organization: "LangChain"
tags: [ai agents, interoperability, orchestration, task management]
link: https://github.com/langchain-ai/agent-protocol
expired: false
created_at: 2026-03-23T23:03:28.001456+00:00
updated_at: 2026-03-24T00:47:43.721881+00:00
---

# Agent Protocol (Agent Protocol)

**Status:** Emerging | **Organization:** LangChain

## Description
A standardized communication protocol for interacting with AI agents, designed to provide a consistent interface for managing agent tasks, steps, and artifacts. It enables interoperability between different agent frameworks and client applications.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Harrison Chase | LangChain | Author |  |
| Erick Friis | LangChain | Contributor |  |
| Nuno Campos | witanlabs | GitHub Contributor | [link](https://github.com/nfcampos) |
| Ben Ryder | Cisco | GitHub Contributor | [link](https://github.com/beryder) |
| John Kennedy | langchain-ai | GitHub Contributor | [link](https://github.com/jkennedyvz) |
| David Duong | Unknown | GitHub Contributor | [link](https://github.com/dqbd) |
| ccurme | Unknown | GitHub Contributor | [link](https://github.com/ccurme) |
| William FH | LangChain | GitHub Contributor | [link](https://github.com/hinthornw) |
| Adil Hafeez | Unknown | GitHub Contributor | [link](https://github.com/adilhafeez) |
| Rohith Ramakrishnan | Intuit | GitHub Contributor | [link](https://github.com/MadaraUchiha-314) |

## Resources
| Type | Label | URL |
|------|-------|-----|
| github | GitHub Repository | https://github.com/langchain-ai/agent-protocol |
| primary_spec | Main Specification | https://github.com/langchain-ai/agent-protocol/blob/main/README.md |

## Tags
ai agents, interoperability, orchestration, task management

## Latest Summary
The **Agent Protocol** is an open-source communication standard designed to provide a unified interface for interacting with AI agents. Developed and maintained by the LangChain team and the e2b community, the protocol defines a single API specification (using OpenAPI) that agents must implement. This standardization allows developers to write tools, benchmarks, and clients that work with any compliant agent framework (such as Auto-GPT, BabyAGI, or custom implementations) without rewriting integration logic for each system.

The core of the protocol focuses on **task-based interactions**. A client initiates a `Task`, and the agent performs one or more `Steps` to complete it. The protocol supports essential features for agentic workflows, including the ability to upload and download files (artifacts), manage task state (status tracking), and handle multi-step reasoning loops. By decoupling the agent's internal logic from its external interface, the protocol aims to foster an ecosystem where testing (benchmarking) and monitoring become agent-agnostic.

Implementation of the protocol is simplified through SDKs provided in Python and JavaScript/TypeScript. These SDKs act as wrappers that handle the API routing, allowing developers to focus solely on the `task_handler` and `step_handler` logic within their specific agent framework. The protocol is currently being adopted by major agent projects and benchmarking suites like the Auto-GPT Forge and the Agent Benchmarks Foundation.

## What's New
The Agent Protocol is gaining traction as the standard for agent benchmarking. Recent updates focus on enhancing the **Python and TypeScript SDKs** to make it easier for developers to wrap existing agents. There is an increased focus on supporting **artifact management**, allowing agents more robust methods to handle file uploads and downloads during task execution. The community is also working on tighter integration with the **Auto-GPT Forge**, positioning the protocol as the default communication layer for agent development within that ecosystem. Additionally, discussions are ongoing regarding the extension of the protocol to better support streaming responses and asynchronous event hooks.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2024-03-12 | milestone | Framework Compatibility Update | Integration support for popular frameworks like Auto-GPT and BabyAGI was improved to ensure full protocol compliance. |
| 2023-11-06 | release | SDK and Documentation Expansion | Significant updates to the SDKs and documentation to improve developer onboarding and framework compatibility. |
| 2023-09-01 | draft | Specification V1 Foundations | The core OpenAPI specification was stabilized, providing the foundation for Python and TypeScript SDKs. |
| 2023-08-16 | milestone | Initial Repository Creation | The project was initiated with the first commits to the Agent Protocol repository, establishing the basic OpenAPI specification. |
