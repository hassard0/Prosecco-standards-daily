---
id: 45894230-2568-4421-a287-69c6d0f06bcd
title: "Agent Operation Authorization"
acronym: AOA
status: Draft
organization: "IETF"
tags: [AI Agents, Authorization, JWT, Security, Delegation, Identity]
link: https://datatracker.ietf.org/doc/draft-liu-agent-operation-authorization/02/
expired: false
created_at: 2026-03-23T03:07:18.445369+00:00
updated_at: 2026-03-23T03:10:45.640075+00:00
---

# Agent Operation Authorization (AOA)

**Status:** Draft | **Organization:** IETF

## Description
A framework that enables verifiable delegation of actions from human principals to autonomous AI agents using structured JWTs. It provides a mechanism for fine-grained authorization of agent operations to prevent unauthorized or hallucinated actions through cryptographic verification.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Dapeng Liu | Alibaba | Author | [link](https://datatracker.ietf.org/person/maxpassion@gmail.com) |
| Judy Zhu | Alibaba | Author | [link](https://datatracker.ietf.org/person/hongru.zhr@alibaba-inc.com) |
| Suresh Krishnan | Cisco Systems | Author | [link](https://datatracker.ietf.org/person/suresh.krishnan@gmail.com) |
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
| documentation | HTML Version | https://www.ietf.org/archive/id/draft-liu-agent-operation-authorization-02.html |
| documentation | Text Version | https://www.ietf.org/archive/id/draft-liu-agent-operation-authorization-02.txt |
| other | Document History | https://datatracker.ietf.org/doc/draft-liu-agent-operation-authorization/history/ |
| documentation | IETF Datatracker API Help | https://datatracker.ietf.org/api/ |

## Tags
AI Agents, Authorization, JWT, Security, Delegation, Identity

## Latest Summary
The **Agent Operation Authorization** framework is a proposed IETF standard (currently an Internet-Draft) designed to enable secure and verifiable delegation of actions from human principals to autonomous AI agents. The framework addresses the unique challenges of agentic systems, such as mitigating "hallucinations" and ensuring that AI actions remain within the boundaries of user intent. It leverages established OAuth 2.0 patterns—specifically Pushed Authorization Requests (PAR)—and JSON Web Tokens (JWT) to create a cryptographically auditable trail of authorization.

The framework operates in two primary phases:
1.  **Agent Operation Authorization Request:** The AI agent generates a structured proposal (`agent_operation_proposal`) using a Rego policy string. This proposal is submitted to an Authorization Server (AS) via a PAR-JWT. Crucially, it replaces the user's natural language input with structured data to ensure predictable policy enforcement while maintaining a reference to the original intent for auditing.
2.  **Agent Operation Authorization Token:** Once the user confirms the proposal, the AS issues a JWT access token containing specific claims such as `agent_identity`, `evidence`, and `context`. This token is used by the agent to access protected resources and provide proof of verified delegation.

Key technical components include the definition of several new JWT claims for agent-user binding and workload identification (compatible with WIMSE), and native support for agent-to-agent delegation chains. The framework is aimed at high-stakes environments like finance and healthcare where accountability is paramount.

## What's New
The latest iteration (**version -02**, released March 16, 2025) introduces a refined **Agent-to-User binding** mechanism. It specifies the use of a `agent_user_binding_proposal` claim, which allows agents to propose a workload identity—often a Workload Identity Token (WIT) from the WIMSE working group—to be cryptographically endorsed by an Authorization Server. Additionally, this version reinforces the use of **OPA (Open Policy Agent)** by standardizing the `agent_operation_proposal` field as a Rego policy string, ensuring that agent operations are governed by verifiable code-based policies rather than ambiguous natural language. The workflow has also been clarified to explicitly use **Pushed Authorization Requests (PAR)** for delivering sensitive operational strategies.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2026-03-16i | deadline | Draft Version 02 Expiration | Anticipated expiration date for the -02 version of the Internet-Draft. |
| 2025-03-16i | release | Release of draft-liu-agent-operation-authorization-02 | The updated draft specifies new JWT claims and refines the PAR-JWT structure for AI agents. |
| 2024-11-11i | draft | Initial Drafting of Authorization Structure | Approximate timestamp within drafting cycle for earliest versioning based on token expiry logic. |
