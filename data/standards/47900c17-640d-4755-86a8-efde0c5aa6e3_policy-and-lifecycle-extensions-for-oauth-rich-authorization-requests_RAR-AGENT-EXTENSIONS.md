---
id: 47900c17-640d-4755-86a8-efde0c5aa6e3
title: "Policy and Lifecycle Extensions for OAuth Rich Authorization Requests"
acronym: RAR-AGENT-EXTENSIONS
status: Draft
organization: "IETF"
tags: [OAuth 2.0, RAR, AI Agents, Authorization, Security, Lifecycle Management]
link: https://datatracker.ietf.org/doc/html/draft-chen-oauth-rar-agent-extensions-00
expired: false
created_at: 2026-03-23T17:06:06.780697+00:00
updated_at: 2026-03-23T17:21:56.344436+00:00
---

# Policy and Lifecycle Extensions for OAuth Rich Authorization Requests (RAR-AGENT-EXTENSIONS)

**Status:** Draft | **Organization:** IETF

## Description
Extends OAuth 2.0 Rich Authorization Requests (RAR) with policy context and lifecycle binding to support AI agent ecosystems. It introduces mechanisms to request specific security assurance levels and to bind authorization validity to the lifecycle of automated tasks.

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
| primary_spec | Primary Specification (HTML) | https://datatracker.ietf.org/doc/html/draft-chen-oauth-rar-agent-extensions-00 |
| other | Text Version | https://www.ietf.org/archive/id/draft-chen-oauth-rar-agent-extensions-00.txt |
| other | XML Version | https://www.ietf.org/archive/id/draft-chen-oauth-rar-agent-extensions-00.xml |
| working_group | OAuth Working Group | https://datatracker.ietf.org/wg/oauth/about/ |

## Tags
OAuth 2.0, RAR, AI Agents, Authorization, Security, Lifecycle Management

## Latest Summary
The **Policy and Lifecycle Extensions for OAuth Rich Authorization Requests** is a proposed extension to the Rich Authorization Requests (RAR) framework defined in RFC 9396. The standard addresses emerging security and operational challenges found in complex AI agent ecosystems and automated distributed systems. Specifically, it introduces two new optional members to the `authorization_details` object: `policy_context` and `lifecycle_binding`.

The `policy_context` member allows clients to explicitly request a specific security assurance level (e.g., financial-grade or HIPAA compliance) for an authorization decision. This is designed to prevent "policy downgrade attacks," where a high-privilege action might otherwise be granted under a low-assurance default policy. It enables Authorization Servers (AS) to execute specific evaluation rules, such as mandatory multi-factor authentication (MFA) or specialized risk analysis, based on the requested context.

The `lifecycle_binding` member addresses the risk of excessive permission lifetimes. In traditional OAuth, access tokens rely on a fixed expiration time (`exp`). This extension allows an authorization grant's validity to be tied to the status of an external entity or task (e.g., a specific data processing job). By using mechanisms like webhooks, the AS can immediately revoke a token as soon as the associated task completes, fails, or is cancelled, adhering to the principle of least privilege.

The standard also defines new Authorization Server metadata parameters (`policy_assurance_levels_supported` and `policy_compliance_frameworks_supported`) to allow clients to discover supported security levels, and introduces a new error code, `policy_requirement_not_met`, for cases where the requested context cannot be satisfied.

## What's New
The standard is currently in its very first iteration as an **Individual Internet-Draft** (version 00), published in February 2026. The most recent updates include the formal definitions for the `policy_context` and `lifecycle_binding` JSON objects. Recent work focuses on specifying how Authorization Servers should process these new fields—including cross-validation of policy levels against requested actions—and how Resource Servers should handle real-time revocation when tokens are bound to external lifecycles. The draft also introduced a new IANA registry for "OAuth Policy Compliance Frameworks."

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2026-08-08 | deadline | Draft Expiration Date | The current version of the Internet-Draft is scheduled to expire if not updated or replaced. |
| 2026-02-04 | draft | Initial Draft Published | The initial version of the Internet-Draft (00) was published by authors Meiling Chen and Li Su. |
