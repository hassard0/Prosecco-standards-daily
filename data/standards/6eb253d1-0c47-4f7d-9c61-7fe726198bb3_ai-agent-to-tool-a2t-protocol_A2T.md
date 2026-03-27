---
id: 6eb253d1-0c47-4f7d-9c61-7fe726198bb3
title: "AI Agent to Tool (A2T) Protocol"
acronym: A2T
status: Draft
organization: "IETF"
tags: [AI Agent, Tool Use, API Integration, Interoperability, LLM]
link: https://datatracker.ietf.org/doc/draft-rosenberg-aiproto-a2t/
expired: false
created_at: 2026-03-23T02:40:50.243768+00:00
updated_at: 2026-03-23T02:50:48.153812+00:00
---

# AI Agent to Tool (A2T) Protocol (A2T)

**Status:** Draft | **Organization:** IETF

## Description
This protocol facilitates the integration of third-party APIs into AI Agents through two primary features: tool enumeration and tool invocation. It standardizes how enterprise AI agents discover available tools' capabilities and perform inter-domain invocations at run-time.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Jonathan Rosenberg | jdrosen.net | Author | [link](https://datatracker.ietf.org/person/jdrosen@jdrosen.net) |
| Pat White | Traego | Author | [link](https://datatracker.ietf.org/person/pat.white@traego.com) |
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
| documentation | Datatracker Status Page | https://datatracker.ietf.org/doc/draft-rosenberg-aiproto-a2t/ |
| documentation | Text Version | https://www.ietf.org/archive/id/draft-rosenberg-aiproto-a2t-00.txt |
| documentation | HTML Version | https://www.ietf.org/archive/id/draft-rosenberg-aiproto-a2t-00.html |
| other | Document History | https://datatracker.ietf.org/doc/draft-rosenberg-aiproto-a2t/history/ |
| mailing_list | Email Expansions | https://datatracker.ietf.org/doc/draft-rosenberg-aiproto-a2t/email/ |

## Tags
AI Agent, Tool Use, API Integration, Interoperability, LLM

## Latest Summary
The AI Agent to Tool (A2T) Protocol is an emerging IETF specification designed to standardize how AI agents interact with third-party APIs (tools). Its primary goal is to reduce the high cost and complexity of integrating disparate B2B SaaS APIs into enterprise AI agents by providing a unified interface for tool discovery and execution.

The protocol comprises two core functional pillars:
1.  **Enumeration API**: This allows AI agent platforms to programmatically discover available tools, their descriptions, and their required parameters. This functionality is critical at 'design time,' where human developers (AI Agent Designers) curate the specific 'skills' or 'operating procedures' an agent should follow.
2.  **Invocation API**: This facilitates the 'run-time' execution of tools across different security and network domains. It standardizes how an agent executor sends requests and receives formatted responses from a tool provider.

A2T distinguishes itself by focusing on the 'curation' and 'sculpting' of tools within enterprise workflows, which often require strict operating procedures to prevent LLM hallucinations. While it shares some conceptual space with the Model Context Protocol (MCP), A2T is tailored specifically for inter-domain, enterprise-grade tool integration where detailed human-in-the-loop design is necessary. The draft defines an OpenAPI-based specification for these exchanges, ensuring compatibility with modern web development practices.

## What's New
The **AI Agent to Tool (A2T) Protocol** was debuted as an official IETF Internet-Draft on **November 6, 2024**. This first version (`-00`) introduces the fundamental concepts of Tool Signatures, Enumeration Endpoints, and Invocation Endpoints. 

Recent activity highlights a focus on the protocol's relationship with existing frameworks like the Model Context Protocol (MCP), clarifying that A2T is specialized for enterprise "operating procedures." Key definitions established in this update include the roles of the "AI Agent Designer" and the "AI Agent Platform," alongside a technical overview of how tool versions and pagination should be handled at the API level. The draft is currently designated as an informational document within the IETF Network Working Group.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2025-05-10 | deadline | Draft Expiration Date | The initial draft is scheduled to expire if not updated or replaced. |
| 2024-11-06 | release | First Internet-Draft Released | The initial version of the Internet-Draft (draft-rosenberg-aiproto-a2t-00) was officially published. |
