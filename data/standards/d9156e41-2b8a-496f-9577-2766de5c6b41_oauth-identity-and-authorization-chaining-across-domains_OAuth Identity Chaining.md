---
id: d9156e41-2b8a-496f-9577-2766de5c6b41
title: "OAuth Identity and Authorization Chaining Across Domains"
acronym: OAuth Identity Chaining
status: Draft
organization: "IETF"
tags: [OAuth 2.0, Identity, Authorization, Security, Trust Domains, Identity Chaining]
link: https://datatracker.ietf.org/doc/html/draft-ietf-oauth-identity-chaining-05
expired: false
created_at: 2026-03-23T02:57:52.973016+00:00
updated_at: 2026-03-23T03:11:05.914869+00:00
---

# OAuth Identity and Authorization Chaining Across Domains (OAuth Identity Chaining)

**Status:** Draft | **Organization:** IETF

## Description
This specification defines a mechanism to preserve identity and authorization information across trust domains that use the OAuth 2.0 Framework. It enables secure propagation of user context and permissions through multiple interconnected domains.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Arndt Schwenkschuster | SPIRL | Author | [link](https://datatracker.ietf.org/person/arndts.ietf@gmail.com) |
| Pieter Kasselman | SPIRL | Author | [link](https://datatracker.ietf.org/person/prkasselman@gmail.com) |
| Kelley Burgin | MITRE | Author | [link](https://datatracker.ietf.org/person/kburgin@mitre.org) |
| Michael J. Jenkins | NSA | Author | [link](https://datatracker.ietf.org/person/mjjenki@cyber.nsa.gov) |
| Brian Campbell | Ping Identity | Author | [link](https://datatracker.ietf.org/person/brian.d.campbell@gmail.com) |
| PieterKas | SPIRL | GitHub Contributor | [link](https://github.com/PieterKas) |
| Aaron Parecki | okta | GitHub Contributor | [link](https://github.com/aaronpk) |
| Dean H. Saxe | Unknown | GitHub Contributor | [link](https://github.com/deansaxe) |
| Dean H. Saxe - AWS Identity | Amazon Web Services | GitHub Contributor | [link](https://github.com/dhs-aws) |
| George Fletcher | Unknown | GitHub Contributor | [link](https://github.com/gffletch) |
| Kamron Batman | Unknown | GitHub Contributor | [link](https://github.com/kamronbatman) |
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

## Resources
| Type | Label | URL |
|------|-------|-----|
| github | GitHub Repository and Issue Tracker | https://github.com/oauth-wg/oauth-identity-chaining |
| mailing_list | Web Authorization Protocol Working Group mailing list archive | https://mailarchive.ietf.org/arch/browse/oauth/ |
| working_group | OAuth (oauth) Working Group Page | https://datatracker.ietf.org/wg/oauth/about/ |
| documentation | Plain Text Version | https://www.ietf.org/archive/id/draft-ietf-oauth-identity-chaining-05.txt |

## Tags
OAuth 2.0, Identity, Authorization, Security, Trust Domains, Identity Chaining

## Latest Summary
The **OAuth Identity and Authorization Chaining Across Domains** standard is an IETF Internet-Draft (draft-ietf-oauth-identity-chaining) developed by the Web Authorization Protocol (OAuth) Working Group. Its primary objective is to define a robust mechanism for preserving identity and authorization information across different trust domains that utilize the OAuth 2.0 Framework. This is particularly relevant in complex environments where a service in one domain needs to access resources in another domain while maintaining the original context of the user or client identity.

The specification leverages existing OAuth mechanisms, specifically **Token Exchange (RFC 8693)** and **JWT Profile for OAuth 2.0 Client Authentication and Authorization Grants (RFC 7523)**, to bridge these domains. Key technical components include:
*   **Authorization Server Discovery:** Guidance on how clients find the appropriate authorization server in a foreign domain.
*   **Token Exchange Protocols:** Detailed request and response structures for exchanging tokens between domains.
*   **JWT Authorization Grants:** Using JSON Web Tokens (JWTs) as authorization grants to carry identity information across boundaries.
*   **Claims Transcription:** Defining how claims from an initial token are mapped or transcribed into a new token suitable for the target domain.
*   **Metadata:** New Authorization Server metadata parameters to indicate support for identity chaining.

The draft is currently in the 'Informational' track, meaning it aims to provide best practices and standardized patterns rather than defining a mandatory core protocol change. It is designed to solve the "broken chain" problem in microservices or federated architectures where identity context often gets lost when crossing organizational or security boundaries.

## What's New
The latest update, **version 05**, was released in July 2025. This iteration refines the processing rules for token exchanges and provides clearer examples for the **JWT Authorization Grant** flow. Significant focus has been placed on **Claims Transcription**, ensuring that when an identity moves from "Domain A" to "Domain B," the semantics of the authorization remain intact. Recent discussions in the OAuth Working Group (as of March 2026) show a broader push to finalize Best Current Practices (BCPs) for JWTs (rfc8725bis), which directly impacts how identity chaining is implemented securely. The draft has also matured its metadata section, defining how Authorization Servers should advertise their ability to participate in an identity chain.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2026-03-22 | meeting | Recent WG Activity High | Working Group activity indicates a focus on related RFCs like 8725bis, signaling ongoing maintenance of OAuth security practices. |
| 2026-01-04 | deadline | Draft Expiration Date | The current version (-05) of the Internet-Draft is scheduled to expire unless updated or replaced. |
| 2025-07-03 | draft | Draft Version 05 Released | Release of version 05 of the Internet-Draft, extending the expiration date to early 2026. |
| 2023-01-26 | other | Repository Created | Initial creation of the GitHub repository for the identity chaining draft. |
