---
id: fb46968c-6714-4a82-9a63-757aff85ed58
title: "Delegated Agent Authorization Protocol (DAAP)"
acronym: DAAP
status: Draft
organization: "IETF"
tags: [OAuth 2.0, AI Agents, Authorization, Decentralized Identifiers (DID), Delegated Authority, JWT]
link: https://datatracker.ietf.org/doc/html/draft-mishra-oauth-agent-grants-00
expired: false
created_at: 2026-03-23T02:53:25.825046+00:00
updated_at: 2026-03-23T03:10:53.731185+00:00
---

# Delegated Agent Authorization Protocol (DAAP) (DAAP)

**Status:** Draft | **Organization:** IETF

## Description
A model-neutral, framework-agnostic protocol for verifying that a human authorized a specific AI agent to perform actions on their behalf. It utilizes Decentralized Identifiers (DIDs) for agent identity and provides a tamper-evident audit trail for agent activities.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Sanjeev Kumar | Grantex | Author | [link](https://datatracker.ietf.org/person/mishra.sanjeev@gmail.com) |
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
| documentation | Internet-Draft Archive (Text) | https://www.ietf.org/archive/id/draft-mishra-oauth-agent-grants-00.txt |
| documentation | IETF Datatracker Document Page | https://datatracker.ietf.org/doc/draft-mishra-oauth-agent-grants/ |
| other | BibXML Reference | https://datatracker.ietf.org/doc/bibxml3/draft-mishra-oauth-agent-grants-00.xml |

## Tags
OAuth 2.0, AI Agents, Authorization, Decentralized Identifiers (DID), Delegated Authority, JWT

## Latest Summary
The Delegated Agent Authorization Protocol (DAAP) is an open, model-neutral framework designed to govern the autonomous actions of AI agents. Positioned as a specialized extension to OAuth 2.0, DAAP addresses uniquely agentic requirements such as persistent cryptographic identity, multi-agent delegation, and tamper-evident auditing. At its core, the protocol utilizes Decentralized Identifiers (DIDs) for agent identity (specifically the `did:grantex` method) and issues signed JSON Web Tokens (JWTs) as Grant Tokens. 

The protocol introduces several innovative components for AI governance:
- **Agent Identity**: Agents are identified via DIDs that resolve to identity documents containing developer info and declared scopes.
- **Hierarchical Delegation**: Supports a parent agent spawning sub-agents with reduced permission sets, featuring "cascade revocation" where revoking the primary grant nullifies all delegated tokens.
- **Auditability**: Requires a hash-chained, append-only audit trail to provide a verifiable record of agent actions for regulated environments.
- **Policy Engine**: Allows for automated authorization decisions (auto-approve/deny) to handle high-volume agent deployments while maintaining human principal control.
- **Anomaly Detection**: A runtime monitoring system to detect behavioral deviations from established agent activity baselines.

DAAP aims to provide a standardized way to verify that a specific human (the "Principal") authorized a specific AI agent to perform an action on a third-party service, with the ability to revoke that permission in real-time.

## What's New
The protocol has progressed from its initial `-00` draft to a `-01` version (as seen in the Datatracker records). Recent updates to the protocol expand its scope significantly beyond the basic grant flow. New features include **budget controls** for managing spending limits, **real-time event streaming**, and a **credential vault** for secure secret storage. Additionally, the metadata now indicates integration support for external policy backends such as **Open Policy Agent (OPA)** and **Cedar**, moving the protocol toward better enterprise policy alignment. The `-01` draft also highlights the inclusion of a multi-agent delegation model specifically designed with "cascade revocation" to handle complex AI agent swarms.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2026-08-31 | deadline | Draft 00 Expiration Date | The initial version (00) of the Internet-Draft is scheduled to expire. |
| 2026-02-27 | draft | Initial Internet-Draft Published | The initial draft 'draft-mishra-oauth-agent-grants-00' is published. |
| 2026-02-01 | milestone | Initial Agent Identity Reference Date | Approximate creation date for the example DID identity document. |
