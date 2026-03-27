---
id: 10ca6368-74ec-495c-9f68-aef5d14c050e
title: "Agent Communication Protocol"
acronym: ACP
status: Draft
organization: "IBM"
tags: [Protocol, Agents]
link: https://agentcommunicationprotocol.dev/
expired: false
created_at: 2026-03-22T18:33:31.70173+00:00
updated_at: 2026-03-23T00:38:19.580136+00:00
---

# Agent Communication Protocol (ACP)

**Status:** Draft | **Organization:** IBM

## Description
The Agent Communication Protocol (ACP) is a standardized messaging and interaction framework designed to enable interoperability between AI agents. It defines a consistent architecture and lifecycle for agent runs, complemented by SDKs for Python and TypeScript.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Bee Team | IBM | Author |  |
| Tomas Pilar | Apoco | GitHub Contributor | [link](https://github.com/pilartomas) |
| Matous Havlena | Apoco | GitHub Contributor | [link](https://github.com/matoushavlena) |
| Tomáš Weiss | Unknown | GitHub Contributor | [link](https://github.com/tomkis) |
| Jenna Winkler | Unknown | GitHub Contributor | [link](https://github.com/jenna-winkler) |
| Sandi Besen | Unknown | GitHub Contributor | [link](https://github.com/sandijean90) |
| Jan Pokorný | https://apoco.com/ | GitHub Contributor | [link](https://github.com/JanPokorny) |
| Radek Ježek | Unknown | GitHub Contributor | [link](https://github.com/jezekra1) |
| Vishal V | Unknown | GitHub Contributor | [link](https://github.com/cptnm3) |
| Ismael Faro Sertage | IBM Research | GitHub Contributor | [link](https://github.com/ismaelfaro) |
| Lukáš Janeček | Apoco | GitHub Contributor | [link](https://github.com/xjacka) |
| deanchanter | Unknown | GitHub Contributor | [link](https://github.com/deanchanter) |
| Tomáš Dvořák | Unknown | GitHub Contributor | [link](https://github.com/Tomas2D) |
| Pavel Bucka | Unknown | GitHub Contributor | [link](https://github.com/penge) |
| Mark Sturdevant | Unknown | GitHub Contributor | [link](https://github.com/markstur) |
| Jan Dušek | Unknown | GitHub Contributor | [link](https://github.com/Zycon42) |
| Kai Wedekind | IBM Deutschland GmbH | GitHub Contributor | [link](https://github.com/KaiWedekind) |
| Kate Blair | IBM | GitHub Contributor | [link](https://github.com/geneknit) |
| Gabe Goodhart | IBM | GitHub Contributor | [link](https://github.com/gabe-l-hart) |
| Anirban Basu | Unknown | GitHub Contributor | [link](https://github.com/anirbanbasu) |
| Daniel Benner | IBM | GitHub Contributor | [link](https://github.com/dbennerIBM) |
| Doc Jones | GraphQL Lead at Postman Open Technologies | GitHub Contributor | [link](https://github.com/doc-jones) |
| E B Benson  | Unknown | GitHub Contributor | [link](https://github.com/Deriverx2) |
| Emmanuel Ferdman | Unknown | GitHub Contributor | [link](https://github.com/emmanuel-ferdman) |
| Ian Molloy | IBM Research | GitHub Contributor | [link](https://github.com/imolloy) |
| Milan Gallas | Unknown | GitHub Contributor | [link](https://github.com/GALLLASMILAN) |
| Paolo Dettori | IBM | GitHub Contributor | [link](https://github.com/pdettori) |
| Titus Lim | Unknown | GitHub Contributor | [link](https://github.com/tituslhy) |

## Resources
| Type | Label | URL |
|------|-------|-----|
| github | Python SDK | https://github.com/i-am-bee/acp/tree/main/python |
| github | TypeScript SDK | https://github.com/i-am-bee/acp/tree/main/typescript |
| documentation | Documentation | https://agentcommunicationprotocol.dev/introduction/welcome |

## Tags
Protocol, Agents

## Latest Summary
The **Agent Communication Protocol (ACP)** is an emerging open-source standard designed to enable seamless interaction and interoperability between disparate AI agents and agentic systems. Developed by the "i-am-bee" community, the protocol addresses the fragmentation in the AI agent ecosystem by providing a unified communication layer. It defines how agents should discover each other, exchange messages, share state, and hand off tasks.

Key technical components of the standard include:
- **Unified Message Schema**: A standardized format for requests, responses, and event-based signaling between agents.
- **Service Discovery**: Mechanisms that allow agents to identify the capabilities and endpoints of other agents within a network.
- **Multi-Language SDKs**: Implementation support is currently provided through official Python and TypeScript/JavaScript SDKs, facilitating integration into existing AI frameworks (like LangChain or Bee Agent Framework).
- **Transport Independence**: While primarily implemented over HTTP/WebSockets in initial drafts, the protocol is designed to be transport-agnostic to support various networking environments.

The protocol aims to move the industry toward "Agentic Interoperability," where a user can orchestrate a swarm of agents built on different platforms to solve complex tasks without manual glue-code. By standardizing the interface, ACP reduces the barrier for developers to build modular, composable agent ecosystems.

## What's New
The Agent Communication Protocol has recently seen the launch of its formal documentation site (`agentcommunicationprotocol.dev`), providing structured guides for developers. Recent activity in the GitHub repositories indicates a focus on stabilizing the **Python and TypeScript SDKs**. Key updates include improved error handling for inter-agent messaging and refined schema definitions for task hand-offs. The community is currently soliciting feedback on the 'Agent Discovery' phase of the protocol to ensure it scales across decentralized environments.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2024-11-20 Daily Activity | milestone | Documentation Portal Launch | Significant documentation updates and introduction of the "Welcome" guide on the official dev portal. |
| 2024-10-23 | release | TypeScript SDK Initial Release | Public release of the official TypeScript/JavaScript SDK for ACP. |
| 2024-10-21 | release | Python SDK Initial Release | Initial commit and public release of the ACP Python SDK repository. |
