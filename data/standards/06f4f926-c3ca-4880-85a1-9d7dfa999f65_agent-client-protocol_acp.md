---
id: 06f4f926-c3ca-4880-85a1-9d7dfa999f65
title: "Agent Client Protocol"
acronym: ACP
status: Draft
organization: "Zed"
tags: [Protocol, Agents]
link: https://agentclientprotocol.com/
expired: false
created_at: 2026-03-22T18:33:31.70173+00:00
updated_at: 2026-03-23T00:36:10.7655+00:00
---

# Agent Client Protocol (ACP)

**Status:** Draft | **Organization:** Zed

## Description
The Agent Client Protocol (ACP) is a standardized communication protocol designed to connect AI agents with various client interfaces. It provides a common architecture for session management, initialization, and registry discovery between agents and clients.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Zed Industries | Zed | Author |  |

## Resources
| Type | Label | URL |
|------|-------|-----|
| documentation | Architecture Documentation | https://agentclientprotocol.com/get-started/architecture |
| documentation | ACP Registry | https://agentclientprotocol.com/get-started/registry |
| documentation | Protocol Overview | https://agentclientprotocol.com/protocol/overview |

## Tags
Protocol, Agents

## Latest Summary
The Agent Client Protocol (ACP) is an open standard designed to facilitate seamless communication between AI agents and the applications (clients) they interact with. Often compared to how the Language Server Protocol (LSP) revolutionized code editors, ACP aims to eliminate the need for custom integrations by providing a universal interface for agent-based interactions. The architecture is built on a client-server model where 'agents' act as servers that expose specific capabilities, and 'clients' (such as IDEs, chat interfaces, or CLI tools) consume these capabilities.

Key architectural components include a **JSON-RPC** based messaging system, ensuring lightweight and scalable communication. The protocol defines a standardized set of lifecycle events, capability discovery mechanisms, and execution flows. A significant part of the ecosystem is the **ACP Registry**, a centralized or federated directory that allows developers to discover, share, and install ACP-compatible agents easily. This registry functions similarly to package managers like npm or PyPI but is tailored for autonomous AI agents.

The protocol focuses on several key areas: 
- **Tool Discovery:** Allowing agents to broadcast their available functions and tools to the client.
- **Resource Management:** Managing the context and data access shared between the client and the agent.
- **Security and Permissions:** Ensuring that agent actions, especially those involving file system access or API calls, are performed within defined boundaries.

By standardizing these interactions, ACP enables developers to build an agent once and deploy it across any ACP-compliant host, significantly reducing the fragmentation in the burgeoning AI agent ecosystem.

## What's New
The Agent Client Protocol (ACP) has recently introduced its core **Architecture** and **Registry** frameworks. The most significant recent development is the establishment of a standardized **JSON-RPC** interface that allows clients (like the Zed editor) to communicate with external AI agents regardless of their underlying language (Python, TypeScript, etc.). Additionally, the **ACP Registry** is now live, providing a centralized hub where developers can register and discover agents. Recent documentation updates emphasize the "LSP for Agents" philosophy, focusing on providing a universal way for agents to describe their tools and capabilities to host applications. Implementation guides for building ACP-compliant agents are now the primary focus for the community developers.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2024-11-20 | release | Initial Launch of ACP | Official launch and announcement of the Agent Client Protocol (ACP) by the Zed team. |
| 2024-11-20 | draft | Architecture Specification Release | Release of the core architecture documentation detailing JSON-RPC implementation and client-server roles. |
| 2024-11-20 | release | ACP Registry Launch | Launch of the ACP Registry for hosting and discovering compatible AI agents. |
