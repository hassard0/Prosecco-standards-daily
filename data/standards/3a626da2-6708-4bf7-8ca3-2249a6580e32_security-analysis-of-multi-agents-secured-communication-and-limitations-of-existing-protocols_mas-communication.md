---
id: 3a626da2-6708-4bf7-8ca3-2249a6580e32
title: "Security Analysis of Multi-agents Secured Communication and Limitations of Existing Protocols"
acronym: MAS-Communication
status: Draft
organization: "IETF"
tags: [multi-agent systems, AI agent security, communication protocols, context integrity, agent orchestration]
link: https://datatracker.ietf.org/doc/draft-zhang-dmsc-mas-communication/
expired: false
created_at: 2026-03-24T00:38:16.846728+00:00
updated_at: 2026-03-24T00:49:03.528562+00:00
---

# Security Analysis of Multi-agents Secured Communication and Limitations of Existing Protocols (MAS-Communication)

**Status:** Draft | **Organization:** IETF

## Description
An analysis of security risks in multi-agent systems (MAS) communication patterns, identifying gaps in existing protocols like TLS and HTTP regarding agent-native semantics. It aims to establish a problem statement for IETF standardization to address dynamic identity, context integrity, and intermediary trust in agentic workflows.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Haodi | China Telecom | Author | [link](https://datatracker.ietf.org/person/zhanghaodi@chinatelecom.cn) |
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
| Martin Thomson | mozilla | GitHub Contributor | [link](https://github.com/martinthomson) |
| Jim Schaad | Unknown | GitHub Contributor | [link](https://github.com/jimsch) |
| Vid Luther | Unknown | GitHub Contributor | [link](https://github.com/vidluther) |
| Ali | iana-org @icann @iana-internal | GitHub Contributor | [link](https://github.com/alireza83) |
| Tom Pusateri | Unknown | GitHub Contributor | [link](https://github.com/pusateri) |
| Shane Kerr | Unknown | GitHub Contributor | [link](https://github.com/shane-kerr) |
| supermariofp | Unknown | GitHub Contributor | [link](https://github.com/supermariofp) |
| Markus Stenberg | Unknown | GitHub Contributor | [link](https://github.com/fingon) |
| bacampbe | Unknown | GitHub Contributor | [link](https://github.com/bacampbe) |
| Harald Alvestrand | Unknown | GitHub Contributor | [link](https://github.com/alvestrand) |
| maybe-hello-world | SNL-UCSB | GitHub Contributor | [link](https://github.com/maybe-hello-world) |
| Tianyi Gao | School of Informatics, University of Edinburgh | GitHub Contributor | [link](https://github.com/breakertt) |
| Willem Toorop | NLnet Labs | GitHub Contributor | [link](https://github.com/wtoorop) |
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
| primary_spec | Primary Specification (I-D) | https://www.ietf.org/archive/id/draft-zhang-dmsc-mas-communication-00.html |
| documentation | Plain Text Version | https://www.ietf.org/archive/id/draft-zhang-dmsc-mas-communication-00.txt |
| other | Document History | https://datatracker.ietf.org/doc/draft-zhang-dmsc-mas-communication/history/ |

## Tags
multi-agent systems, AI agent security, communication protocols, context integrity, agent orchestration

## Latest Summary
The "Security Analysis of Multi-agents Secured Communication and Limitations of Existing Protocols" is a proposed Internet-Draft within the IETF's Dynamic Multi-agent Secured Collaboration (DMSC) framework. It provides a comprehensive analysis of the security risks inherent in Multi-agent Systems (MAS) across various interaction patterns, including sequential workflows, hierarchical planning (orchestrated), and decentralized meshes. The document argues that existing Internet protocols such as TLS, HTTP/gRPC, and MQTT, as well as developer frameworks like AutoGen and the A2A protocol, are insufficient for MAS because they lack "agent-native" design.

Key security risks identified include dynamic identity ambiguity (short-lived agents that don't map to traditional host-based identities), context poisoning (lack of cryptographic integrity for evolving conversational states across multiple hops), and over-privileged intermediaries (orchestrators and brokers acting as single points of failure). Furthermore, the document highlights a major gap in "computation-aware" communication, noting that current protocols cannot express or negotiate the resource-heavy costs associated with AI inference, leaving agents vulnerable to computational Denial of Service (DoS) attacks. This draft serves as a foundational problem statement and gap analysis intended to guide future IETF standardization efforts for secure, distributed AI agent communications.

## What's New
The initial version (-00) of this Internet-Draft was published on January 16, 2026. This new document formalizes the security requirements for the emerging DMSC (Dynamic Multi-agent Secured Collaboration) field. It specifically introduces a classification of MAS communication risks based on topology (Workflow, Hierarchical, and Mesh) and provides a pointed critique of standard protocols (TLS, HTTP, MQTT) for their inability to handle the computational asymmetry and semantic context integrity required by autonomous AI agents. Notably, it mentions the "A2A" protocol and "AutoGen" framework as current technologies with significant structural security gaps.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2026-07-20 | deadline | Draft Expiration Deadline | Scheduled expiration date for the -00 version of the Internet-Draft unless replaced or updated. |
| 2026-01-16 | release | First Draft Published | Initial submission of draft-zhang-dmsc-mas-communication-00 to the IETF Datatracker. |
| 2026-01-16 | milestone | DMSC Working Group Association | The document is officially associated with the Dynamic Multi-agent Secured Collaboration (DMSC) framework/working group. |
