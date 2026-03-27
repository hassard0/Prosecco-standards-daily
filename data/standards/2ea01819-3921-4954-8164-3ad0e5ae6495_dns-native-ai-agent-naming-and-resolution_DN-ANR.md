---
id: 2ea01819-3921-4954-8164-3ad0e5ae6495
title: "DNS-Native AI Agent Naming and Resolution"
acronym: DN-ANR
status: Draft
organization: "IETF"
tags: [AI Agents, DNS, Naming Resolution, DNSSEC, FQDN]
link: https://datatracker.ietf.org/doc/draft-cui-dns-native-agent-naming-resolution/
expired: false
created_at: 2026-03-23T17:09:00.110899+00:00
updated_at: 2026-03-23T17:21:36.430707+00:00
---

# DNS-Native AI Agent Naming and Resolution (DN-ANR)

**Status:** Draft | **Organization:** IETF

## Description
DN-ANR specifies a system for using Fully Qualified Domain Names (FQDNs) as stable identifiers for AI agents, allowing them to resolve to verifiable endpoints via DNSSEC. It provides minimal indexing capabilities to be used by upper-layer discovery systems without carrying heavy semantic metadata in DNS.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Yong Cui | Tsinghua University | Author | [link](https://datatracker.ietf.org/person/cuiyong@tsinghua.edu.cn) |
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
| primary_spec | Primary Specification (HTML) | https://www.ietf.org/archive/id/draft-cui-dns-native-agent-naming-resolution-01.html |
| other | Primary Specification (TXT) | https://www.ietf.org/archive/id/draft-cui-dns-native-agent-naming-resolution-01.txt |
| other | Document History | https://datatracker.ietf.org/doc/draft-cui-dns-native-agent-naming-resolution/history/ |

## Tags
AI Agents, DNS, Naming Resolution, DNSSEC, FQDN

## Latest Summary
The **DNS-Native AI Agent Naming and Resolution (DN-ANR)** standard establishes a lightweight, DNS-based infrastructure for identifying and connecting to AI agents. The specification aims to provide a stable naming convention using Fully Qualified Domain Names (FQDNs), enabling secure resolution to verifiable endpoints while maintaining strict separation from higher-level discovery or semantic matching systems.

Key technical components include the use of **SVCB (Service Binding)** and **HTTPS Resource Records** for protocol negotiation and version distribution. DN-ANR mandates minimal data in the DNS to avoid "heavy" metadata, focusing instead on cryptographic integrity—ideally through **DNSSEC**. It supports a multi-layered architecture where a discovery layer identifies candidate FQDNs, the resolution layer (defined by this standard) provides connection material, and the connection layer executes session logic (e.g., A2A or MCP protocols).

Current design principles emphasize a "DNS-First" approach, where DNS is the authoritative source and HTTPS serves only as a fallback mirror via a standardized `agent-dns.json` file. The standard also addresses performance through address hints and TTL guidance to ensure deterministic and efficient agent-to-agent communication. Security is a primary focus, featuring optional but recommended signature-based mechanisms and integrity digests to prevent unauthorized redirection or spoofing of agent endpoints.

## What's New
The latest update (**draft-cui-dns-native-agent-naming-resolution-01**, released March 2, 2026) introduces several significant refinements to the resolution architecture. Most notably, it adds a detailed **HTTPS Fallback Mechanism** utilizing an `agent-dns.json` file and a specific JSON schema to support environments where DNS queries might be restricted or require mirroring. 

The update also expands the **Security section**, providing a more robust specification for **Signature-based Security** and public key requirements. New technical details for **SVCB Private Parameters** and ALPN (Application-Layer Protocol Negotiation) usage have been added to better handle version-specific protocol resolution. Additionally, the draft now includes an **Implementation Checklist** for both Agent Publishers and Client Developers to facilitate easier adoption of the standard.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2026-09-03 | deadline | Draft Expiration Deadline | Scheduled expiration date for the -01 version of the Internet-Draft unless updated or replaced. |
| 2026-03-02 | release | Release of draft-cui-dns-native-agent-naming-resolution-01 | Revised version of the draft submitted to the IETF Domain Name System Working Group, introducing SVCB record refinements and the HTTPS fallback mechanism. |
| 2025-10-01 | release | Release of draft-01-00 | Initial registration and draft-00 of the DNS-Native AI Agent Naming and Resolution specification. |
