---
id: 4a5a2634-8462-44d8-8a33-22be7b0dd97d
title: "Considerations for AI Agent Communication and Networking in Enterprise"
acronym: draft-han-agent-comm-enterprise
status: Draft
organization: "IETF"
tags: [AI Agents, Enterprise Networking, Semantic Routing, Agent Discovery, Multi-Agent Cooperation]
link: https://datatracker.ietf.org/doc/draft-han-agent-comm-enterprise/
expired: false
created_at: 2026-03-23T02:11:49.356001+00:00
updated_at: 2026-03-23T02:50:54.300403+00:00
---

# Considerations for AI Agent Communication and Networking in Enterprise (draft-han-agent-comm-enterprise)

**Status:** Draft | **Organization:** IETF

## Description
This document investigates key technologies for AI agent communication in enterprise scenarios, including identification, registration, capability discovery, and secure collaboration. It proposes an agent identifier and semantic routing mechanism to facilitate trusted access and efficient cooperation among heterogeneous agents.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Mengyao Han | China Unicom | Author | [link](https://datatracker.ietf.org/person/hanmy12@chinaunicom.cn) |
| Han Zhengxin | China Unicom | Author | [link](https://datatracker.ietf.org/person/hanzx21@chinaunicom.cn) |
| Tao He | China Unicom | Author | [link](https://datatracker.ietf.org/person/het21@chinaunicom.cn) |
| Ran Pang | China Unicom | Author | [link](https://datatracker.ietf.org/person/pangran@chinaunicom.cn) |
| Henrik Levkowetz | Unknown | GitHub Contributor | [link](https://github.com/levkowetz) |
| Robert Sparks | ietf @ietf-tools @ietf-llc | GitHub Contributor | [link](https://github.com/rjsparks) |
| Ole Laursen | IOLA | GitHub Contributor | [link](https://github.com/OleLaursen) |
| Jennifer Richards | ietf-tools | GitHub Contributor | [link](https://github.com/jennifer-richards) |
| Nicolas Giard | ietf @ietf-tools @ietf-llc @requarks | GitHub Contributor | [link](https://github.com/NGPixel) |
| Lars Eggert | IETF @Mozilla | GitHub Contributor | [link](https://github.com/larseggert) |
| Pasi Eronen | reaktor | GitHub Contributor | [link](https://github.com/pasieronen) |
| Ryan Cross | Unknown | GitHub Contributor | [link](https://github.com/rpcross) |
| Bill Fenner | Unknown | GitHub Contributor | [link](https://github.com/fenner) |
| Emilio A. | Z1 | GitHub Contributor | [link](https://github.com/emiliosanchez) |
| Emilio Jiménez | www.yaco.es | GitHub Contributor | [link](https://github.com/ejimenez) |
| Russ Housley | Unknown | GitHub Contributor | [link](https://github.com/russhousley) |
| Paul Selkirk | Unknown | GitHub Contributor | [link](https://github.com/pselkirk) |
| Adam Roach | Unknown | GitHub Contributor | [link](https://github.com/adamroach) |
| Tero Kivinen | Unknown | GitHub Contributor | [link](https://github.com/kivinen) |
| Kesara Rathnayake | ietf-tools | GitHub Contributor | [link](https://github.com/kesara) |
| Matthew Holloway | http://twitter.com/hollowaynz | GitHub Contributor | [link](https://github.com/holloway) |
| Peter Yee | Unknown | GitHub Contributor | [link](https://github.com/Spectre17) |
| Jim Fenton | Altmode Networks | GitHub Contributor | [link](https://github.com/jimfenton) |
| Rich Salz | Akamai Technologies | GitHub Contributor | [link](https://github.com/richsalz) |
| Eric Vyncke | Unknown | GitHub Contributor | [link](https://github.com/evyncke) |
| Suresh Krishnan | Unknown | GitHub Contributor | [link](https://github.com/sureshkrishnan) |
| Jean Mahoney | rfc-editor @ietf | GitHub Contributor | [link](https://github.com/ajeanmahoney) |
| Joel Halpern | Ericsson | GitHub Contributor | [link](https://github.com/JoelHalpern) |
| Sangho Na | Unknown | GitHub Contributor | [link](https://github.com/microamp) |
| Rudi Matz | Unknown | GitHub Contributor | [link](https://github.com/rudimatz) |
| Mark Donnelly | Unknown | GitHub Contributor | [link](https://github.com/meadmaker) |
| Valery Smyslov | Unknown | GitHub Contributor | [link](https://github.com/smyslov) |
| Jacobo Tarragón | Unknown | GitHub Contributor | [link](https://github.com/jminuscula) |
| Jim Schaad | Unknown | GitHub Contributor | [link](https://github.com/jimsch) |
| Martin Thomson | mozilla | GitHub Contributor | [link](https://github.com/martinthomson) |
| Vid Luther | Unknown | GitHub Contributor | [link](https://github.com/vidluther) |
| Ali | iana-org @icann @iana-internal | GitHub Contributor | [link](https://github.com/alireza83) |
| Tom Pusateri | Unknown | GitHub Contributor | [link](https://github.com/pusateri) |
| Shane Kerr | Unknown | GitHub Contributor | [link](https://github.com/shane-kerr) |
| supermariofp | Unknown | GitHub Contributor | [link](https://github.com/supermariofp) |
| Markus Stenberg | Unknown | GitHub Contributor | [link](https://github.com/fingon) |
| bacampbe | Unknown | GitHub Contributor | [link](https://github.com/bacampbe) |
| Harald Alvestrand | Unknown | GitHub Contributor | [link](https://github.com/alvestrand) |
| maybe-hello-world | SNL-UCSB | GitHub Contributor | [link](https://github.com/maybe-hello-world) |
| Willem Toorop | NLnet Labs | GitHub Contributor | [link](https://github.com/wtoorop) |
| Tianyi Gao | School of Informatics, University of Edinburgh | GitHub Contributor | [link](https://github.com/breakertt) |
| sftcd | Unknown | GitHub Contributor | [link](https://github.com/sftcd) |
| Pete Resnick | Unknown | GitHub Contributor | [link](https://github.com/peteresnick) |
| Mat Ford | Unknown | GitHub Contributor | [link](https://github.com/madofo) |
| Mark Nottingham | Unknown | GitHub Contributor | [link](https://github.com/mnot) |
| Liubov Kurafeeva | Unknown | GitHub Contributor | [link](https://github.com/nectostr) |
| John L | Unknown | GitHub Contributor | [link](https://github.com/jrlevine) |
| Ian Williams | aws | GitHub Contributor | [link](https://github.com/aph3rson) |
| lushancool | Unknown | GitHub Contributor | [link](https://github.com/lushancool) |
| Dapeng(Max) Liu | w3ctag | GitHub Contributor | [link](https://github.com/maxpassion) |
| gnocuil | Unknown | GitHub Contributor | [link](https://github.com/gnocuil) |
| Benson Muite | Unknown | GitHub Contributor | [link](https://github.com/bkmgit) |
| Warren Kumari | Unknown | GitHub Contributor | [link](https://github.com/wkumari) |
| Tim Wicinski | Unknown | GitHub Contributor | [link](https://github.com/moonshiner) |
| Spike^ekipS | Unknown | GitHub Contributor | [link](https://github.com/spikeekips) |
| Seonghyeon Cho | marqvision | GitHub Contributor | [link](https://github.com/sh-cho) |
| Richard Barnes | Unknown | GitHub Contributor | [link](https://github.com/bifurcation) |
| PriyankaN | Association Management Solutions, LLC | GitHub Contributor | [link](https://github.com/PriyankaGitCom) |

## Resources
| Type | Label | URL |
|------|-------|-----|
| documentation | Interactive HTML version | https://datatracker.ietf.org/doc/html/draft-han-agent-comm-enterprise-00 |
| documentation | Plain Text Archive | https://www.ietf.org/archive/id/draft-han-agent-comm-enterprise-00.txt |
| other | Document History | https://datatracker.ietf.org/doc/draft-han-agent-comm-enterprise/history/ |
| other | BibXML Reference | https://datatracker.ietf.org/doc/bibxml3/draft-han-agent-comm-enterprise-00.xml |

## Tags
AI Agents, Enterprise Networking, Semantic Routing, Agent Discovery, Multi-Agent Cooperation

## Latest Summary
This Internet-Draft, authored by representatives from China Unicom, provides a comprehensive framework for AI agent communication and networking within enterprise and campus environments. As AI evolves toward autonomous and collaborative agents, the document identifies critical infrastructure gaps, specifically the heterogeneity of agent protocols (e.g., ACP, A2A, ANP) and the limitations of traditional IP addressing for massive-scale (million-level) agent connections. 

The proposed solution centers on an **Agent Gateway** architecture, which serves as a hybrid device combining traditional communication gateway reliability with AI cognitive decision-making. Key technical pillars include the introduction of a globally unique **Agent Identifier (ID)** based on IPv6 and a **semantic/agent-aware routing** mechanism. This allows the network to route traffic based on agent skills, intent, and task objectives rather than just physical locations. Additionally, the draft explores "Token-aware Routing" to prioritize critical tokens in AI interactions, aimed at reducing first-packet latency and ensuring deterministic Quality of Service (QoS) for real-time enterprise applications like robotics and emergency response.

## What's New
The version 00 draft introduces the concept of an **Agent Private Network** architecture. Its most significant recent contributions include the proposal for **IPv6-based Agent Identifiers** to replace traditional IP addresses for identity, and **Token-aware Routing**, which classifies and prioritizes specific tokens within an AI data stream to decrease response latency. It also formalizes the requirements for an **Agent Gateway**, positioning it as a four-layer stack consisting of Application Service, Orchestration & Control, Agent Connectivity, and Network Communication layers. Recent updates also link this draft to a broader family of work on "Agent-to-Agent" (A2A) collaboration requirements for campus-level scaling.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2026-09-16 | deadline | Draft Expiration Date | Scheduled expiration date for the initial version of the draft. |
| 2026-03-15 | release | Initial Draft Released (v00) | Initial submission of "Considerations for AI Agent Communication and Networking in Enterprise" (version 00). |
| 2026-01-30 | draft | Agent Gateway Intercomm Framework Published | Draft proposing the Agent Gateway Intercommunication Framework published. |
| 2025-11-27 | draft | A2A Requirements Draft Updated | Detailed requirements for Agent-to-Agent (A2A) collaboration in enterprise released. |
| 2025-11-06 | draft | Networking Scenarios Draft Published | Reference document regarding agents networking scenarios in enterprise published. |
| 2025-11-03 | draft | Foundation Framework Draft Published | Reference document "Agents Networking Framework for Enterprise and Broadband" published. |
