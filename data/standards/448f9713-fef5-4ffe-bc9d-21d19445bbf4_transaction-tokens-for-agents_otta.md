---
id: 448f9713-fef5-4ffe-bc9d-21d19445bbf4
title: "Transaction Tokens For Agents"
acronym: OTTA
status: Draft
organization: "IETF"
tags: [OAuth, Security, AI AgentsContext Propagation, Transaction Tokens, Authentication]
link: https://datatracker.ietf.org/doc/draft-oauth-transaction-tokens-for-agents/
expired: false
created_at: 2026-03-23T03:00:52.231741+00:00
updated_at: 2026-03-23T03:11:38.980139+00:00
---

# Transaction Tokens For Agents (OTTA)

**Status:** Draft | **Organization:** IETF

## Description
An extension to the OAuth Transaction Tokens framework to support agent context propagation. It defines 'actor' and 'principal' fields to allow services to distinguish between the agent performing an action and the entity that initiated it.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Ashay Raut | Amazon | Author | [link](https://datatracker.ietf.org/person/asharaut@amazon.com) |
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
| documentation | Interactive HTML version | https://doc.html/draft-oauth-transaction-tokens-for-agents-04 |
| documentation | Text version | https://www.ietf.org/archive/id/draft-oauth-transaction-tokens-for-agents-04.txt |
| documentation | XML source | https://www.ietf.org/archive/id/draft-oauth-transaction-tokens-for-agents-04.xml |
| documentation | BibXML | https://datatracker.ietf.org/doc/bibxml3/draft-oauth-transaction-tokens-for-agents-04.xml |
| mailing_list | Email Expansions | https://datatracker.ietf.org/doc/draft-oauth-transaction-tokens-for-agents/email/ |

## Tags
OAuth, Security, AI AgentsContext Propagation, Transaction Tokens, Authentication

## Latest Summary
This standard specifies an extension to the **OAuth Transaction Tokens (Txn-Tokens)** framework to support context propagation for AI agents. As AI agents often operate with a degree of autonomy or across complex service graphs, traditional authorization models struggle to track whether an action was initiated by a human or the agent itself.

The draft introduces two primary context fields to the Txn-Token:
- **actor**: Identifies the AI agent performing the action.
- **principal**: Identifies the human or system entity that initiated the agent's task.

The framework supports two distinct operational modes:
1. **Principal-Initiated Flow**: Where a human invokes an agent, and the token carries both the agent's identity (as the actor) and the human's identity (as the principal).
2. **Autonomous Flow**: Where an agent operates independently (e.g., on a schedule). In this case, the 'principal' field can be omitted, and the agent's identity is derived from the OAuth client credentials.

By embedding this metadata within short-lived, signed JWTs, the standard allows downstream services in a distributed system to perform granular access control and maintain a clear audit trail of "who" (agent) is acting for "whom" (human user). additionally, it introduces an optional `agentic_ctx` claim for conveying specific operational constraints of the agent.

## What's New
The latest update (**draft-04**, February 2026) refines the protocol for how Transaction Token Services (TTS) extract and map identities from incoming OAuth 2.0 access tokens. Key recent additions include:

- **Explicit mapping rules**: Instructions for the TTS to use the `aud` claim from an access token to populate the `sub` claim of the Txn-Token, and the `clientId` (or `actor`) to populate the agent's context.
- **Autonomous Flow refinement**: Clarification that autonomous agents should use the OAuth 2.0 Client Credentials Grant, with the `sub` field from the access token's `actor` claim mapping to the Txn-Token `actor` context.
- **Agentic Context**: The introduction of the `agentic_ctx` claim, a JSON object intended to carry attributes relative to an agent's specific operational constraints for policy evaluation.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2026-08-15 | deadline | Draft Expiration Date | The current Version 04 draft is scheduled to expire unless updated or replaced. |
| 2026-02-11 | draft | Draft Version 04 Published | Release of draft-oauth-transaction-tokens-for-agents-04, updating the agent context propagation specifications. |
