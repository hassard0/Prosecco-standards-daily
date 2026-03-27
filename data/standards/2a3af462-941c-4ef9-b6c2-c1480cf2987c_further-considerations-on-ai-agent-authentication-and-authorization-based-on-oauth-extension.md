---
id: 2a3af462-941c-4ef9-b6c2-c1480cf2987c
title: "Further considerations on AI Agent Authentication and Authorization Based on OAuth Extension"
status: Draft
organization: "IETF"
tags: [AI Agents, Authentication, Authorization, OAuth Extension, Agent Communication Network]
link: https://datatracker.ietf.org/doc/draft-yao-agent-auth-considerations/
expired: false
created_at: 2026-03-23T11:40:56.005366+00:00
updated_at: 2026-03-23T13:35:32.278103+00:00
---

# Further considerations on AI Agent Authentication and Authorization Based on OAuth Extension

**Status:** Draft | **Organization:** IETF

## Description
This document proposes extensions to the OAuth model and new workflows designed for AI agent authentication and authorization to support scalable and trustable Agent Communication Networks (ACN). It addresses the specific requirements for verifying identities and permissions of autonomous AI agents within vertical industries.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Kehan Yao | China Mobile | Author | [link](https://datatracker.ietf.org/person/yaokehan@chinamobile.com) |
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
| documentation | Document Text (TXT) | https://www.ietf.org/archive/id/draft-yao-agent-auth-considerations-01.txt |
| documentation | Document HTML (HTML) | https://www.ietf.org/archive/id/draft-yao-agent-auth-considerations-01.html |
| other | Document History | https://datatracker.ietf.org/doc/draft-yao-agent-auth-considerations/history/ |
| documentation | Document XML | https://www.ietf.org/archive/id/draft-yao-agent-auth-considerations-01.xml |

## Tags
AI Agents, Authentication, Authorization, OAuth Extension, Agent Communication Network

## Latest Summary
This informational document, "Further considerations on AI Agent Authentication and Authorization Based on OAuth Extension," addresses the evolving security requirements of the Agent Communication Network (ACN). As AI agents—both physical (robots) and virtual (software assistants)—become integral to internet infrastructure, the standard OAuth models require extensions to handle the unique delegated authority of these entities.

The primary focus of the document is extending the OAuth 2.0/2.1 framework to support three distinct operational modes for AI agents:
1. **On-Behalf-Of (OBO) User(s):** Where an agent requires user authorization to access protected resources (e.g., a travel assistant accessing a bank account).
2. **On-Behalf-Of (OBO) Itself:** Where the agent acts as a first-class entity with its own independent identity and identification.
3. **On-Behalf-Of (OBO) Other Agent(s):** Where an agent represents another agent that may lack specific capabilities to perform a task.

A significant architectural addition is the integration of **API Proxy Servers**, specifically referencing the **Model Context Protocol (MCP)**. Instead of agents communicating directly with numerous resource owners—which is deemed inefficient in the AI era—the API Proxy Server acts as a middlebox. It aggregates authorization grants and handles API calls on behalf of the agent, simplifying the workflow when multiple resource owners and different privilege levels are involved.

The document also introduces the **Agent Identifier (AID)** as an independent ID for AI agents and explores concepts like "Task-wise Domains" (temporary domains for specific jobs) versus "Application Domains" (durable domains). Security considerations highlighted include agent impersonation during discovery, excessive attribute disclosure, and the risks of token replay in multi-agent environments.

## What's New
The latest update (version 01) introduces a more detailed architectural model incorporating **API Proxy Servers** (such as MCP servers) to centralize resource requests. It formally categorizes AI agents into **Physical** and **Virtual** types and defines distinct ownership roles: OBO User, OBO Itself, and OBO Other Agents. New additions also include the technical distinction between **Task-wise Domains** (temporary) and **Application Domains** (permanent) for resource management. The workflow for agents acting on behalf of users has been refined to show how multiple authorization grants are gathered by a proxy and returned to the agent in a single consolidated process.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2026-04-23 | deadline | Draft Expiration Date | The current draft (version 01) is scheduled to expire if not updated or replaced. |
| 2025-10-20 | release | Draft Version 01 Published | Publication of the draft 'Further considerations on AI Agent Authentication and Authorization Based on OAuth Extension' (version 01). |
