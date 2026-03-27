---
id: ab2ca2b9-0082-44f6-b672-3ac1b0ef79c1
title: "HTTP Message Signatures Directory"
acronym: HTTP-MESSAGE-SIGNATURES-DIRECTORY
status: Draft
organization: "IETF"
tags: [HTTP, Security, Digital Signatures, JWKS, Key Discovery, Cryptography]
link: https://datatracker.ietf.org/doc/draft-meunier-http-message-signatures-directory/
expired: false
created_at: 2026-03-24T00:40:48.563082+00:00
updated_at: 2026-03-24T00:48:19.840954+00:00
---

# HTTP Message Signatures Directory (HTTP-MESSAGE-SIGNATURES-DIRECTORY)

**Status:** Draft | **Organization:** IETF

## Description
A method for clients using HTTP Message Signatures to advertise their signing keys through a directory format based on JWKS. It also defines a new HTTP Method Context to facilitate in-band key discovery.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Thibault Meunier | Cloudflare | Author | [link](https://datatracker.ietf.org/person/ot-ietf@thibault.uk) |
| Sandor Major | Individual | Author | [link](https://datatracker.ietf.org/person/ietf@sandormajor.com) |
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
| Martin Thomson | mozilla | GitHub Contributor | [link](https://github.com/martinthomson) |
| Jim Schaad | Unknown | GitHub Contributor | [link](https://github.com/jimsch) |
| Vid Luther | Unknown | GitHub Contributor | [link](https://github.com/vidluther) |
| Ali | iana-org @icann @iana-internal | GitHub Contributor | [link](https://github.com/alireza83) |
| Tom Pusateri | Unknown | GitHub Contributor | [link](https://github.com/pusateri) |
| Shane Kerr | Unknown | GitHub Contributor | [link](https://github.com/shane-kerr) |
| supermariofp | Unknown | GitHub Contributor | [link](https://github.com/supermariofp) |
| Markus Stenberg | Unknown | GitHub Contributor | [link](https://github.com/fingon) |
| bacampbe | Unknown | GitHub Contributor | [link](https://github.com/bacampbe) |
| Harald Alvestrand | Unknown | GitHub Contributor | [link](https://github.com/alvestrand) |
| maybe-hello-world | SNL-UCSB | GitHub Contributor | [link](https://github.com/maybe-hello-world) |
| Tianyi Gao | School of Informatics, University of Edinburgh | GitHub Contributor | [link](https://github.com/breakertt) |
| Willem Toorop | NLnet Labs | GitHub Contributor | [link](https://github.com/wtoorop) |
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
| primary_spec | Primary Specification (HTML) | https://www.ietf.org/archive/id/draft-meunier-http-message-signatures-directory-05.html |
| primary_spec | Primary Specification (TXT) | https://www.ietf.org/archive/id/draft-meunier-http-message-signatures-directory-05.txt |
| other | Document History | https://datatracker.ietf.org/doc/draft-meunier-http-message-signatures-directory/history/ |
| other | BibXML | https://datatracker.ietf.org/doc/bibxml3/draft-meunier-http-message-signatures-directory-05.xml |

## Tags
HTTP, Security, Digital Signatures, JWKS, Key Discovery, Cryptography

## Latest Summary
The **HTTP Message Signatures Directory** standard addresses a critical deployment gap in the [RFC 9421] HTTP Message Signatures framework: the lack of a standardized, automated mechanism for verifiers to discover a signer's public key material. Currently, most implementations rely on out-of-band key distribution, which limits horizontal scalability and dynamic verification of unknown signers.

This specification introduces three primary components:
1.  **Standardized Directory Format:** A JSON Web Key Set (JWKS) based structure specifically tailored for HTTP Message Signature keys. It restricts the "alg" parameters to those registered in the IANA HTTP Message Signature Algorithms registry.
2.  **Well-Known URI Discovery:** Defines a standard location (`/.well-known/http-message-signatures-directory`) where services can host their key directories for automated fetching.
3.  **In-band Discovery via `Signature-Agent`:** A new HTTP header field (`Signature-Agent`) that allows a signer to point directly to their key directory via an HTTPS, HTTP, or even an inline `data` URI.

To ensure the integrity of the discovery process, the draft recommends that directory responses include an HTTP Message Signature. Each key in the directory should be used to sign the directory response itself, allowing the client to verify that the directory is authoritative for the keys it contains. The standard is currently under development within the **Web Bot Auth Working Group**.

## What's New
The latest update (**draft-05**, published March 2, 2026) refines the security model for binding keys to directory authorities. It specifically recommends that directory servers include an HTTP Message Signature for each key in the response. This version mandates the use of the `@authority` component with the `req` flag and requires specific signature parameters such as `created`, `expires`, `keyid` (using JWK Thumprints), and a specific `tag` (set to `http-message-signatures-directory`). Additionally, the draft includes updated examples for delegation and chaining, covering scenarios like X.509 certificate chains (`x5c`), leaf certificates with AIA fields, and external certificate URLs (`x5u`).

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2026-09-03 | deadline | Expiration Deadline for Draft -05 | The current draft version (-05) is scheduled to expire if not updated. |
| 2026-03-02 | release | Draft Version 05 Released | Release of draft-meunier-http-message-signatures-directory-05. |
| 2024-02-01 | other | RFC 9421 Published | Publication of RFC 9421 (HTTP Message Signatures), which this directory standard builds upon. |
