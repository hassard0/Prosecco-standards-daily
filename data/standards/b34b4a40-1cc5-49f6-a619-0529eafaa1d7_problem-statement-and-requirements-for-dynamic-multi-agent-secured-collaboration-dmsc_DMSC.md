---
id: b34b4a40-1cc5-49f6-a619-0529eafaa1d7
title: "Problem Statement and Requirements for Dynamic Multi-agent Secured Collaboration (DMSC)"
acronym: DMSC
status: Draft
organization: "IETF"
tags: [AI Agents, Multi-agent Systems, Security, Interoperability, Orchestration, Gateway]
link: https://datatracker.ietf.org/doc/draft-song-dmsc-problem-statement/
expired: false
created_at: 2026-03-24T00:23:51.116333+00:00
updated_at: 2026-03-24T00:48:55.466546+00:00
---

# Problem Statement and Requirements for Dynamic Multi-agent Secured Collaboration (DMSC) (DMSC)

**Status:** Draft | **Organization:** IETF

## Description
A framework that leverages a centralized gateway layer to offload secured communication, cross-domain connectivity, and multi-tenant policy enforcement for LLM-based AI agents. It aims to enable developers to focus on core agent functionality while ensuring consistent security and interoperability across heterogeneous environments.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Enge Song | Alibaba | Author | [link](https://datatracker.ietf.org/person/enge.seg@alibaba-inc.com) |
| Yang Song | Alibaba | Author | [link](https://datatracker.ietf.org/person/song288954@alibaba-inc.com) |
| Shaokai Zhang | Alibaba | Author | [link](https://datatracker.ietf.org/person/shaokai.zsk@alibaba-inc.com) |
| Xing Li | CERNET | Author | [link](https://datatracker.ietf.org/person/xing@cernet.edu.cn) |
| Jiangu Zhao | Alibaba | Author | [link](https://datatracker.ietf.org/person/jiangu.zjg@alibaba-inc.com) |
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
| primary_spec | Primary Specification (IETF Datatracker) | https://datatracker.ietf.org/doc/draft-song-dmsc-problem-statement/ |
| documentation | Text Version | https://www.ietf.org/archive/id/draft-song-dmsc-problem-statement-00.txt |
| documentation | HTML Version | https://www.ietf.org/archive/id/draft-song-dmsc-problem-statement-00.html |

## Tags
AI Agents, Multi-agent Systems, Security, Interoperability, Orchestration, Gateway

## Latest Summary
The **Dynamic Multi-agent Secured Collaboration (DMSC)** is a proposed IETF standard (currently an individual Internet-Draft) designed to address the challenges of LLM-based AI agent systems. Currently, autonomous agents must individually handle complex communication protocols, service discovery, and security encryption, leading to "code bloat" and inconsistent security implementations. DMSC proposes a centralized infrastructure layer (a gateway) to offload these non-core functions, allowing developers to focus strictly on agent business logic.

Key components of the DMSC proposal include a centralized gateway that manages secured transport (TLS termination, certificate rotation), cross-domain connectivity (bridging public clouds and private data centers), and multi-tenant policy enforcement. A significant feature is "Dynamic Collaboration Assistance," which provides capability-based routing—automatically matching a task to the most appropriate agent based on expertise and real-time load. The standard emphasizes non-intrusive integration using standard protocols like HTTP/gRPC and transparent traffic interception (e.g., via eBPF or iptables) to ensure agents do not require specific SDKs or heavy code modifications. Adopting this framework aims to improve scalability, security consistency, and operational efficiency in heterogeneous, multi-tenant environments.

## What's New
The DMSC standard is in its earliest stage with the release of **draft-song-dmsc-problem-statement-00** on March 2, 2026. This newly introduced document identifies four primary problem areas in current AI agent frameworks: the tight coupling of collaboration and communication logic, security fragmentation (inconsistent TLS/cert management), inefficient multi-tenant management, and a lack of dynamic assistance for task delegation. The draft introduces formal requirements for "non-intrusive" integration and "end-to-end security offloading," moving the burden of encryption and certificate lifecycle management from the agent to the infra layer.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2026-09-03 | deadline | Draft Expiration Date | The standard expiration date for the initial -00 draft version unless updated or replaced. |
| 2026-03-02 | draft | Initial Draft Release (-00) | The initial version of the Problem Statement and Requirements for DMSC (version 00) was published as an Internet-Draft. |
