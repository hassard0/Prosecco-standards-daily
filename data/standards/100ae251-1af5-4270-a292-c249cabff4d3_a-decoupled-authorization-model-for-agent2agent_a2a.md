---
id: 100ae251-1af5-4270-a292-c249cabff4d3
title: "A Decoupled Authorization Model for Agent2Agent"
acronym: A2A
status: Draft
organization: "IETF"
tags: [AI Agents, Authorization, Agent2Agent, Security, Just-in-Time Permissions]
link: https://datatracker.ietf.org/doc/draft-chen-agent-decoupled-authorization-model/00/
expired: false
created_at: 2026-03-23T03:09:27.654146+00:00
updated_at: 2026-03-23T03:10:37.204354+00:00
---

# A Decoupled Authorization Model for Agent2Agent (A2A)

**Status:** Draft | **Organization:** IETF

## Description
This document proposes a framework for dynamic, intent-based authorization for AI Agents. It enables fine-grained, Just-in-Time (JIT) permissions based on an agent's specific intent and behavioral trustworthiness rather than long-lived identities.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Meiling Chen | China Mobile | Author | [link](https://datatracker.ietf.org/person/chenmeiling90@hotmail.com) |
| Li Su | China Mobile | Author | [link](https://datatracker.ietf.org/person/suli@chinamobile.com) |
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
| other | Document History | https://datatracker.ietf.org/doc/draft-chen-agent-decoupled-authorization-model/history/ |
| documentation | Text Format | https://www.ietf.org/archive/id/draft-chen-agent-decoupled-authorization-model-00.txt |
| documentation | HTML Format | https://www.ietf.org/archive/id/draft-chen-agent-decoupled-authorization-model-00.html |
| other | BibXML | https://datatracker.ietf.org/doc/bibxml3/draft-chen-agent-decoupled-authorization-model-00.xml |

## Tags
AI Agents, Authorization, Agent2Agent, Security, Just-in-Time Permissions

## Latest Summary
The **A Decoupled Authorization Model for Agent2Agent** proposal introduces a security framework specifically designed for the unique lifecycle and operational patterns of AI Agents. Traditional authorization models (like RBAC) often rely on long-lived identities and static roles, which the authors argue are ill-suited for AI agents that are frequently ephemeral, autonomous, and multi-step in their task execution.

The core of the standard is the separation of authorization logic from business logic. It defines two primary logical components:
1.  **Authorization Execution Point (AEP):** A gateway that intercepts agent requests, validates foundational credentials (like OAuth 2.0 tokens), and assembles a context-rich query for a decision.
2.  **Authorization Decision Point (ADP):** The "brain" of the system that evaluates the AEP's query against declarative policies to return a real-time "Allow" or "Deny" decision.

Key innovations include **Intent-Based Authorization**, where permissions are granted based on the specific goal the agent is attempting to achieve (e.g., a specific flight query) rather than broad administrative scopes. It also addresses the need for **Just-in-Time (JIT) permissions** and **Continuous Trust Attestation**, moving away from "one-time" authentication at the start of a session. The document specifically analyzes OAuth 2.0, noting that while it provides a strong foundation for delegation, it lacks the fine-grained policy language and context-specific decision-making required for complex AI agent ecosystems. Currently, the specification is in its initial "00" draft phase, with several sections like the "Input Contract" and "Security Considerations" marked for future development (TBD).

## What's New
The standard is a newly introduced **Internet-Draft (version -00)** as of February 2026. The most significant recent activity is the formalization of the problem statement regarding AI Agent security, specifically identifying "Scale and Complexity Explosion" and "Identity Lifecycle Mismatch" as critical gaps in current IETF standards like OAuth 2.0. The authors from China Mobile have established the architectural split between the **Authorization Execution Point (AEP)** and the **Authorization Decision Point (ADP)**. Current work is focused on defining the "Input Contract," which will be the standardized data format used between these two points to enable intent-based decisions.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2026-08-18 | deadline | Draft Expiration Date | The initial version of the draft (-00) is scheduled to expire. |
| 2026-02-14 | release | Initial Draft Released | The first version of the Internet-Draft (-00) is officially released. |
| 2025-02-13 | milestone | Draft Registration Date | The BibXML data records the initial publication date for the -00 draft. |
