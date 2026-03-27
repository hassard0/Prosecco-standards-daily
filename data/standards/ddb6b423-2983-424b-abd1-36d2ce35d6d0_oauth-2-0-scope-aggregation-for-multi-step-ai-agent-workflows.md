---
id: ddb6b423-2983-424b-abd1-36d2ce35d6d0
title: "OAuth 2.0 Scope Aggregation for Multi-Step AI Agent Workflows"
status: Draft
organization: "IETF"
tags: [OAuth 2.0, AI Agents, Authorization, Scope Aggregation, Workflows]
link: https://datatracker.ietf.org/doc/html/draft-jia-oauth-scope-aggregation
expired: false
created_at: 2026-03-23T18:21:05.011743+00:00
updated_at: 2026-03-23T19:10:42.429709+00:00
---

# OAuth 2.0 Scope Aggregation for Multi-Step AI Agent Workflows

**Status:** Draft | **Organization:** IETF

## Description
An OAuth 2.0 authorization pattern that allows AI agents to aggregate multiple required scopes into a single authorization procedure. This approach reduces repeated user consent prompts and improves efficiency in multi-step AI agent workflows across different resources.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Yukuan Jia | Huawei | Author | [link](https://datatracker.ietf.org/person/jiayukuan@huawei.com) |
| Shuping Peng | Huawei | Author | [link](https://datatracker.ietf.org/person/pengshuping@huawei.com) |
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
| primary_spec | Primary Specification (HTML) | https://datatracker.ietf.org/doc/html/draft-jia-oauth-scope-aggregation-00 |
| documentation | Text Version | https://www.ietf.org/archive/id/draft-jia-oauth-scope-aggregation-00.txt |
| documentation | XML Version | https://www.ietf.org/archive/id/draft-jia-oauth-scope-aggregation-00.xml |
| working_group | Web Authorization Protocol (oauth) Working Group | https://datatracker.ietf.org/wg/oauth/about/ |

## Tags
OAuth 2.0, AI Agents, Authorization, Scope Aggregation, Workflows

## Latest Summary
The **OAuth 2.0 Scope Aggregation for Multi-Step AI Agent Workflows** is emerging as a standards-track proposal within the IETF Web Authorization Protocol (OAuth) working group. It addresses a specific efficiency gap in AI agent operations: when an agent executes a plan requiring access to multiple protected resources, traditional OAuth flows often trigger individual authorization challenges for each resource. This leads to "user fatigue" through repeated consent prompts and increased network latency.

The specification introduces a proactive authorization pattern. By aggregating all required scopes across an entire workflow into a single authorization request, the AI agent can obtain one comprehensive access token (or a set of tokens) up-front. A key technical contribution of this draft is the extension of **Resource Metadata** with a new `security` member. This allows resource servers to advertise their required OAuth scopes and authorization server (AS) metadata. With this information, an AI agent can perform "Scope Aggregation" by calculating the minimal set of permissions needed across its planned steps before execution begins.

Key architectural concepts include **Authorization Domains**, which are logical groupings of scopes authorizable by a single trust anchor. The draft also emphasizes backward compatibility, allowing agents to fall back to reactive "step-up" authorization if the proactive aggregation metadata is unavailable. While improving efficiency, the standard notes security risks such as "Residual Privilege" (excessive permissions if a workflow is partially executed) and "User Blind Signing" (users consenting to long lists of scopes they may not fully understand).

## What's New
The specification is in its earliest stage (version 00). The most significant recent development is the formal definition of the `security` member in JSON-based resource metadata. This member includes `type` (e.g., "oauth2"), `scopes`, and `as_metadata` (AS discovery URL). The draft specifically highlights its role in filling gaps in existing protocols like the **Model Context Protocol (MCP)**, which currently lacks a standardized way to advertise per-tool scope requirements, often resulting in reactive, manual authorization triggers.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2026-08-14 | deadline | Draft Expiration Date | The initial draft (version 00) is scheduled to expire unless updated or replaced. |
| 2026-02-10 | release | Initial Draft Publication (00) | The initial version of the Internet-Draft (draft-jia-oauth-scope-aggregation-00) is published. |
