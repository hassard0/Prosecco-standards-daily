---
id: 2204a9a1-dde9-4330-ab82-64035af40443
title: "OAuth2.0 Extention for AI Agent: Authorization on Target"
acronym: OAuth2-AI-Agent
status: Draft
organization: "IETF"
tags: [OAuth 2.0, AI Agent, Authorization, Security, Identity]
link: https://datatracker.ietf.org/doc/draft-song-oauth-ai-agent-authorization/
expired: false
created_at: 2026-03-23T03:08:26.59094+00:00
updated_at: 2026-03-23T03:11:14.81513+00:00
---

# OAuth2.0 Extention for AI Agent: Authorization on Target (OAuth2-AI-Agent)

**Status:** Draft | **Organization:** IETF

## Description
An extension to the OAuth 2.0 protocol that introduces a target_id field for granular authorization of AI agents. It aims to support precise permission management and enhance traceability for virtual or physical AI components in a network.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Yurong Song | Huawei | Author | [link](https://datatracker.ietf.org/person/songyurong1@huawei.com) |
| LUN LI | Huawei | Author | [link](https://datatracker.ietf.org/person/lilun20@huawei.com) |
| Faye Liu | Individual | Author | [link](https://datatracker.ietf.org/person/feyerliu@gmail.com) |
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
| documentation | Current Draft (HTML) | https://www.ietf.org/archive/id/draft-song-oauth-ai-agent-authorization-00.html |
| documentation | Current Draft (TXT) | https://www.ietf.org/archive/id/draft-song-oauth-ai-agent-authorization-00.txt |
| other | Document History | https://datatracker.ietf.org/doc/draft-song-oauth-ai-agent-authorization/history/ |
| mailing_list | Email Expansions | https://datatracker.ietf.org/doc/draft-song-oauth-ai-agent-authorization/email/ |

## Tags
OAuth 2.0, AI Agent, Authorization, Security, Identity

## Latest Summary
The **OAuth 2.0 Extension for AI Agent: Authorization on Target** is an IETF Internet-Draft that proposes a granular authorization mechanism specifically for AI agents and AI models. It addresses the unique characteristics of AI agents, such as autonomy and long-lived identities, which are not fully covered by standard OAuth 2.0 workflows. The core of the proposal is the introduction of a **Target**—a specific module, virtual agent, or physical model within a client that requires authorization.

The extension introduces an optional field, `target_id`, into the OAuth 2.0 protocol flow. This allows a client to explicitly identify which specific AI component is requesting access to a resource. This granularity is intended to enhance security by preventing unauthorized or malicious behavior from specific AI components without disrupting the entire client's operation. It also supports regulatory compliance (like GDPR) by ensuring resource owners know exactly which AI entity is utilizing their data. 

The draft specifies extensions for:
* **Client Registration:** Including AI agent/model identities and capabilities in the client profile.
* **Authorization Requests:** Enabling the client to select the correct "target" based on task requirements or resource availability.
* **Access Token Requests:** Including the `target_id` in the token request and a corresponding `tar` claim in the issued access token to finalize the granular permission.

## What's New
The standard is currently in its first iteration (**version -00**), published on **July 3, 2025**. This release introduces the foundational concepts of a "Target" (AI agent/model) and the the `target_id` parameter. Key recent updates in this draft include the definition of two specific use cases: virtual AI agents (models as software modules) and physical AI agents (models hosted on agent hardware). It also introduces the `tar` claim for access tokens, allowing Authorization Servers to specify the authorized target in the final credential.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2026-01-04 | deadline | Draft Expiration Date | The initial Internet-Draft (-00) is set to expire. |
| 2025-07-03 | release | Publication of draft-song-oauth-ai-agent-authorization-00 | Initial version of the draft (-00) is published. |
