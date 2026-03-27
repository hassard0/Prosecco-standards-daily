---
id: 676ddc74-cc15-41d1-9daa-fac75edc5ff6
title: "OAuth Client ID Metadata Document"
acronym: CIMD
status: Draft
organization: "IETF"
tags: [OAuth, Identity, Metadata, Authentication, Web Architecture]
link: https://datatracker.ietf.org/doc/draft-ietf-oauth-client-id-metadata-document/
expired: false
created_at: 2026-03-24T17:06:14.337343+00:00
updated_at: 2026-03-24T17:08:30.658167+00:00
---

# OAuth Client ID Metadata Document (CIMD)

**Status:** Draft | **Organization:** IETF

## Description
This specification defines a mechanism through which an OAuth client can identify itself to authorization servers by using a URL as a client_id. The URL refers to a document containing client metadata, allowing authorization servers to fetch metadata as needed without prior manual registration.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Aaron Parecki | IndieAuth | Author | [link](https://datatracker.ietf.org/person/aaron@parecki.com) |
| Emelia Smith | BrandedCode | Author | [link](https://datatracker.ietf.org/person/emelia@brandedcode.com) |
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
| primary_spec | Primary Specification (HTML) | https://www.ietf.org/archive/id/draft-ietf-oauth-client-id-metadata-document-01.html |
| primary_spec | Primary Specification (TXT) | https://www.ietf.org/archive/id/draft-ietf-oauth-client-id-metadata-document-01.txt |
| mailing_list | Mailing list discussion | https://mailarchive.ietf.org/arch/browse/oauth/?q=draft-ietf-oauth-client-id-metadata-document |
| working_group | OAuth Working Group | https://datatracker.ietf.org/wg/oauth/about/ |
| primary_spec | MCP Reference | https://modelcontextprotocol.io/specification/2025-11-25/basic/authorization |

## Tags
OAuth, Identity, Metadata, Authentication, Web Architecture

## Latest Summary
The **OAuth Client ID Metadata Document** (CIMD) defines a mechanism for OAuth 2.0 clients to identify themselves to authorization servers (AS) without the need for prior dynamic or manual registration. This is achieved by using a stable HTTPS URL as the `client_id` in OAuth flows. The AS fetches a JSON document from this URL to discover necessary metadata, such as the application name, logo, and registered redirect URIs.

This approach is particularly beneficial for clients interacting with multiple authorization servers with which they have no pre-existing relationship. By publishing their own registration information, clients can bypass the administrative overhead of individual registrations and the lifecycle management of inactive client records.

Key technical requirements include:
*   **Client ID Requirements:** Must be an HTTPS URL containing a path, but no fragments, user info, or double-dot segments.
*   **Metadata Document:** A JSON document that must contain a `client_id` matching its own URL. It utilizes parameters from the IANA OAuth Dynamic Client Registration Metadata registry.
*   **Security Restrictions:** To prevent security risks, symmetric shared secrets are prohibited. Supported authentication methods typically include `none` or asymmetric cryptography.
*   **AS Support Signaling:** Authorization servers signal support for this mechanism via a new metadata property: `client_id_metadata_document_supported`.
*   **Development Facilitation:** The specification recommends the use of "Client ID Metadata Document Services" to help developers host metadata documents during local development.

The standard addresses security considerations such as Server-Side Request Forgery (SSRF) during the discovery process, caching limitations to prevent stale data, and domain-based trust.

## What's New
The most recent update is the release of **draft-ietf-oauth-client-id-metadata-document-01** (March 2026). This revision refines the requirements for client identifiers, specifically mandating the HTTPS scheme and restricting certain URL components like fragments and query strings. It introduces a new Authorization Server metadata property, `client_id_metadata_document_supported`, and provides guidance on "Client ID Metadata Document Services" to assist developers with localhost testing. Recent mailing list activity in March 2026 indicates ongoing technical review and alignment with other OAuth security considerations.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2026-09-03 | deadline | Draft Expiration Date | The current draft-01 is scheduled to expire. |
| 2026-03-22 | milestone | Weekly GitHub Activity Digest | Summary of activity regarding the draft is captured in the weekly GitHub digest for the OAuth Working Group. |
| 2026-03-05 | meeting | Initial Mailing List Discussion on Draft-01 | Working group members discuss the I-D Action and specific metadata properties on the mailing list. |
| 2026-03-02 | release | Release of draft-ietf-oauth-client-id-metadata-document-01 | Draft version 01 of the OAuth Client ID Metadata Document is released. |
