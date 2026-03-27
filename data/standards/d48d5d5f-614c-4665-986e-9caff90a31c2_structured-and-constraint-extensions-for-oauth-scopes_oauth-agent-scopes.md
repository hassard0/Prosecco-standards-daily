---
id: d48d5d5f-614c-4665-986e-9caff90a31c2
title: "Structured and Constraint Extensions for OAuth Scopes"
acronym: OAuth Agent Scopes
status: Draft
organization: "IETF"
tags: [OAuth 2.0, AI Agents, Authorization, Security, Scopes, Fine-grained Access Control]
link: https://datatracker.ietf.org/doc/html/draft-chen-oauth-scope-agent-extensions
expired: false
created_at: 2026-03-23T17:05:41.137529+00:00
updated_at: 2026-03-23T17:22:12.926391+00:00
---

# Structured and Constraint Extensions for OAuth Scopes (OAuth Agent Scopes)

**Status:** Draft | **Organization:** IETF

## Description
Defines a structured format for OAuth 2.0 scopes to support fine-grained permissions for AI Agent skills and modular capability units. It introduces a colon-separated syntax for specifying resource types, actions, targets, and constraints.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Jia Chen | China Mobile | Author | [link](https://datatracker.ietf.org/person/chenjia@chinamobile.com) |
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
| primary_spec | Primary Specification (HTML) | https://datatracker.ietf.org/doc/html/draft-chen-oauth-scope-agent-extensions-00 |
| documentation | Plain Text Version | https://www.ietf.org/archive/id/draft-chen-oauth-scope-agent-extensions-00.txt |
| documentation | XML Version | https://www.ietf.org/archive/id/draft-chen-oauth-scope-agent-extensions-00.xml |
| other | IETF Datatracker Page | https://datatracker.ietf.org/doc/draft-chen-oauth-scope-agent-extensions/ |

## Tags
OAuth 2.0, AI Agents, Authorization, Security, Scopes, Fine-grained Access Control

## Latest Summary
The **Structured and Constraint Extensions for OAuth Scopes** is an Internet-Draft aimed at addressing the limitations of simple, space-delimited OAuth 2.0 scope strings, particularly within AI Agent ecosystems. As AI Agents increasingly use "Modular Capability Units" (or "Skills"), there is a growing need for a standardized, machine-readable way to request and grant fine-grained permissions for specific operations like file system access, network requests, and command-line execution.

The core of the proposal is a colon-separated syntax for scope values: `[resource_type]:[action]:[target][:constraints]`. This structure allows for precise authorization. For example, instead of a broad "read" permission, a client can request `fs:read:/docs/report.pdf`, where `fs` is the resource type, `read` is the action, and the file path is the target. The draft also introduces the concept of "constraints" to further limit the scope (e.g., time-bound access or rate limits).

The specification maps these interactions to standard OAuth 2.0 roles. The AI Agent acts as the **Client**, the end-user as the **Resource Owner**, and a trusted entity (often the agent platform) as the **Authorization Server**. The **Resource Server** is split into two roles: a management server for module installation and a user resource server for controlling access to local tools and data during execution. By formalizing this structure, the draft aims to enhance security and user control over third-party modular skills while maintaining backward compatibility with existing OAuth token flows. Currently, the draft is an individual submission and has not yet been adopted by a formal IETF working group.

## What's New
The version **-00** draft was recently published, introducing the `[resource_type]:[action]:[target][:constraints]` syntax. Key updates include:
- **Defined Resource Types**: Introduces standard identifiers for `fs` (file system), `cmd` (command execution), `net` (network), `tool` (API invocation), and `scheduler`.
- **Structured Scope Negotiation**: Outlines a modified OAuth flow where the Authorization Server (AS) fetches module metadata to tailor the requested scopes before presenting them to the user.
- **Support for Constraints**: Adds an optional `:constraints` field to scope tokens to allow for key-value pairs that further restrict permissions.
- **Forward Compatibility**: Explicitly includes a `:reserve` segment for future extensions and mandates that implementations handle unknown actions gracefully.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2026-09-02 | deadline | Draft Expiration Date | The current version of the Internet-Draft (-00) is set to expire. |
| 2026-03-01 | draft | Draft Date Reference | The document header lists an internal date of March 2026, suggesting a planned update or a forward-dated draft cycle. |
| 2025-03-01 | release | Initial Draft Published | Initial version (-00) of the Internet-Draft is published by authors from China Mobile. |
