---
id: 222c9073-d40b-42d0-8280-8596559f0e19
title: "Attenuating Authorization Tokens for Agentic Delegation Chains"
acronym: AAT
status: Draft
organization: "IETF"
tags: [OAuth, AI Agents, JWT, Authorization, Delegation, Security]
link: https://datatracker.ietf.org/doc/draft-niyikiza-oauth-attenuating-agent-tokens/
expired: false
created_at: 2026-03-23T17:02:48.715367+00:00
updated_at: 2026-03-23T17:21:26.401849+00:00
---

# Attenuating Authorization Tokens for Agentic Delegation Chains (AAT)

**Status:** Draft | **Organization:** IETF

## Description
Defines Attenuating Authorization Tokens (AATs), a JWT-based credential format for secure delegation in AI agent systems. It allows agents to derive more restrictive tokens offline to cryptographically enforce tool-invocation constraints across delegation chains.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Niki Aimable | Tenuo | Author | [link](https://datatracker.ietf.org/person/niki@tenuo.ai) |
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
| primary_spec | Primary Specification (HTML) | https://www.ietf.org/archive/id/draft-niyikiza-oauth-attenuating-agent-tokens-00.html |
| primary_spec | Primary Specification (TXT) | https://www.ietf.org/archive/id/draft-niyikiza-oauth-attenuating-agent-tokens-00.txt |
| other | Document History | https://datatracker.ietf.org/doc/draft-niyikiza-oauth-attenuating-agent-tokens/history/ |

## Tags
OAuth, AI Agents, JWT, Authorization, Delegation, Security

## Latest Summary
The **Attenuating Authorization Tokens (AATs) for Agentic Delegation Chains** standard introduces a new JWT-based credential format designed to solve the "confused deputy" problem in AI agent ecosystems. As AI agents increasingly delegate tasks to sub-agents, traditional OAuth tokens often lack the granularity to restrict specific tool usage or argument values, leading to security risks like prompt injection or unauthorized API calls.

AATs function as capability-based tokens that support offline, monotonic attenuation. This means a token holder (e.g., an orchestrating agent) can derive a new, more restricted token for a downstream agent without contacting a central authorization server. The core security invariant ensures that permissions can only be narrowed or maintained, never expanded. These tokens extend **RFC 9396 (Rich Authorization Requests)** by adding delegation-chain semantics and a typed constraint vocabulary for tool-level restrictions.

The specification defines a rigorous chain verification algorithm that allows an enforcement point (the tool's provider) to verify the entire delegation path cryptographically, relying only on the root token's trust anchor. Key features include support for both JWT and CWT (CBOR Web Token) formats, proof-of-possession (PoP) requirements to prevent token theft, and a registry for argument constraints (such as path containment or value ranges). This approach addresses the latency and availability issues inherent in existing mechanisms like RFC 8693 (Token Exchange), which require synchronous round-trips to an authorization server for every delegation step.

## What's New
The standard is currently in its **initial draft phase (-00)**, as of March 2026. This release introduces the foundational concepts of **Attenuating Authorization Tokens (AATs)**, including the cryptographic derivation mechanism and the chain verification algorithm. 

Key technical components introduced in this draft include:
*   **Monotonic Attenuation:** A mechanism allowing offline derivation of restricted tokens.
*   **RFC 9396 Extensions:** Integration with Rich Authorization Requests (RAR) to describe tool-level capabilities.
*   **Constraint Vocabulary:** A new typed system for restricting tool arguments (e.g., `path_containment`).
*   **PoP JWT Support:** Mandatory Proof-of-Possession to ensure tokens are used only by intended agents.
*   **CWT Profile:** A normative Appendix defining the CBOR/CWT representation for resource-constrained environments.
*   **Reference Implementation:** Announcement of a reference implementation and formal verification efforts to validate the protocol's security properties.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2026-09-17 | deadline | Draft Expiration Date | The initial version of the draft (-00) is scheduled to expire. |
| 2026-03-16 | release | Initial Internet-Draft Publication | The initial draft (-00) of 'Attenuating Authorization Tokens for Agentic Delegation Chains' is published. |
| 2026-03-16 | milestone | Submission to OAuth Working Group | The draft is officially submitted to the Web Authorization Protocol (OAuth) working group. |
