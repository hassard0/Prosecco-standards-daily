---
id: fd971cf8-8dca-432b-b351-1d00dd41909b
title: "OAuth 2.0 Extension: On-Behalf-Of User Authorization for AI Agents"
acronym: OAuth 2.0 AI Agent Extension
status: Draft
organization: "IETF"
tags: [OAuth 2.0, AI Agents, Authorization, Delegation, Identity]
link: https://datatracker.ietf.org/doc/draft-oauth-ai-agents-on-behalf-of-user/
expired: false
created_at: 2026-03-23T02:17:27.670653+00:00
updated_at: 2026-03-23T02:39:55.16376+00:00
---

# OAuth 2.0 Extension: On-Behalf-Of User Authorization for AI Agents (OAuth 2.0 AI Agent Extension)

**Status:** Draft | **Organization:** IETF

## Description
This specification extends the OAuth 2.0 Authorization Framework to enable AI agents to securely obtain access tokens for acting on behalf of users. It introduces parameters to identify the specific agent requiring delegation and ensures secure delegation with explicit user consent and enhanced auditability.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Thilina | Independent | Author | [link](https://datatracker.ietf.org/person/thilinasenarath97@gmail.com) |
| Ayesha Dissanayaka | Independent | Author | [link](https://datatracker.ietf.org/person/ayshsandu@gmail.com) |
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
| documentation | Document Status Page | https://datatracker.ietf.org/doc/draft-oauth-ai-agents-on-behalf-of-user/ |
| documentation | Plain Text Version | https://www.ietf.org/archive/id/draft-oauth-ai-agents-on-behalf-of-user-02.txt |
| documentation | HTML Version | https://www.ietf.org/archive/id/draft-oauth-ai-agents-on-behalf-of-user-02.html |
| documentation | XML Version | https://www.ietf.org/archive/id/draft-oauth-ai-agents-on-behalf-of-user-02.xml |
| other | Document History | https://datatracker.ietf.org/doc/draft-oauth-ai-agents-on-behalf-of-user/history/ |
| mailing_list | Email Expansions | https://datatracker.ietf.org/doc/draft-oauth-ai-agents-on-behalf-of-user/email/ |

## Tags
OAuth 2.0, AI Agents, Authorization, Delegation, Identity

## Latest Summary
This specification extends the OAuth 2.0 Authorization Framework ([RFC6749](https://datatracker.ietf.org/doc/html/rfc6749)) to address the specific needs of AI agents acting on behalf of users. While standard OAuth flows and Token Exchange ([RFC8693](https://datatracker.ietf.org/doc/html/rfc8693)) exist, they often lack mechanisms for explicit user consent via the front channel or fail to distinguish the agent as a unique identity during token exchange.

The extension modifies the **Authorization Code Grant** flow by introducing two primary parameters:
1.  **`requested_actor`**: Used at the authorization endpoint to identify the specific AI agent requiring delegation. This allows the Authorization Server to present a consent screen that explicitly names the agent to the user.
2.  **`actor_token`**: Used at the token endpoint to authenticate the agent when the client exchanges the authorization code for an access token.

The resulting access token is a JSON Web Token (JWT) that captures the full delegation chain, including the user (subject), the client application, and the AI agent (actor). This structure enhances auditability and transparency for resource servers, such as Model Context Protocol (MCP) servers, which can then validate the entire delegation path before granting access to protected resources. The flow is designed to be triggered dynamically by a Resource Server challenge (e.g., a 401 Unauthorized response), ensuring consent is obtained at the moment access is required.

## What's New
The latest update (**version -02**, released August 26, 2025) refines the protocol flow for AI agent delegation. Key changes include clearer definitions for the **`requested_actor`** and **`actor_token`** parameters. The draft now provides a more detailed sequence for the **Resource Server Challenge**, explaining how a resource server can signal a need for user-delegated authorization via the `WWW-Authenticate` header. Additionally, the update improves the description of the access token structure to ensure it properly documents the delegation chain from the user to the agent via a client application, specifically targeting use cases like **Model Context Protocol (MCP)** servers.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2026-02-27 | deadline | Draft Expiration Date | The current iteration of the Internet-Draft is set to expire unless updated or replaced. |
| 2025-08-26 | release | Release of draft-oauth-ai-agents-on-behalf-of-user-02 | Updated version of the draft submitted to the IETF OAuth Working Group, refining the protocol steps and terminology. |
