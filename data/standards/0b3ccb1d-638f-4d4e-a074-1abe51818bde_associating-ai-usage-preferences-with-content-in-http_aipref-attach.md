---
id: 0b3ccb1d-638f-4d4e-a074-1abe51818bde
title: "Associating AI Usage Preferences with Content in HTTP"
acronym: AIPREF-ATTACH
status: Draft
organization: "IETF"
tags: [HTTP, AI Governance, Content Preferences, Robots.txt, Web Scraping]
link: https://datatracker.ietf.org/doc/draft-ietf-aipref-attach/
expired: false
created_at: 2026-03-23T23:08:18.288742+00:00
updated_at: 2026-03-24T00:48:01.092121+00:00
---

# Associating AI Usage Preferences with Content in HTTP (AIPREF-ATTACH)

**Status:** Draft | **Organization:** IETF

## Description
This specification defines methods for content creators to signal preferences regarding how automated AI systems consume their content via HTTP. It updates RFC 9309 to allow for the inclusion of usage preferences during content acquisition.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Gary Illyes | Google | Author | [link](https://datatracker.ietf.org/person/synack@garyillyes.com) |
| Martin Thomson | Mozilla | Author | [link](https://datatracker.ietf.org/person/mt@lowentropy.net) |
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
| primary_spec | Primary Specification (HTML) | https://www.ietf.org/archive/id/draft-ietf-aipref-attach-04.html |
| mailing_list | Mailing list discussion | https://mailarchive.ietf.org/arch/browse/ai-control/?q=draft-ietf-aipref-attach |
| working_group | AIPREF Working Group | https://datatracker.ietf.org/wg/aipref/about/ |
| other | Document History | https://datatracker.ietf.org/doc/draft-ietf-aipref-attach/history/ |

## Tags
HTTP, AI Governance, Content Preferences, Robots.txt, Web Scraping

## Latest Summary
The "Associating AI Usage Preferences with Content in HTTP" standard (draft-ietf-aipref-attach) defines a mechanism for content creators to signal their preferences regarding how automated systems, specifically AI models and scrapers, consume their content. This is achieved by including usage preferences directly within HTTP acquisition processes, effectively updating RFC 9309 (Robots Exclusion Protocol) to support more granular AI-specific signals.

The primary goal is to provide a standardized, machine-readable way for stakeholders to express constraints on AI training, verbatim reproduction, and generative search usage. By attaching these preferences to HTTP responses, the standard aims to move beyond the limitations of `robots.txt`, which is often fetched separately and may not cover specific resource-level requirements. The draft is being developed within the IETF **AIPREF (AI Preferences)** Working Group. Key technical areas of focus include the statefulness of HTTP headers during `PUT` or `PATCH` operations and resolving potential priority conflicts when preferences differ between HTTP headers and a site's `robots.txt` file. Many current discussions revolve around clarifying the "Verbatim" constraint in Section 4.2, specifically concerning its application in generative search engines.

## What's New
The standard has recently advanced to **version 04** of the Internet-Draft (released February 2025). Most recent activity in March 2026 focused on implementation nuances. Key updates include intense debate on the **"Verbatim" constraint** in Section 4.2 to ensure it clearly distinguishes between AI training and real-time generative search. Additionally, the working group is addressing technical edge cases regarding **HTTP Header Statefulness**, specifically how preferences should behave during `PUT` and `PATCH` requests. There is also new guidance being drafted on **conflict resolution**, establishing that specific HTTP headers should generally take precedence over broad `robots.txt` rules for individual resources.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2026-03-13 | other | PUT/PATCH Semantic Discussion | A technical inquiry is raised by 'happypants' regarding the semantics of headers during state-changing HTTP methods. |
| 2026-03-12 | other | Verbatim Constraint Clarification | Max Gendler initiates a clarification request regarding generative search and verbatim content constraints. |
| 2026-03-03 | decision | Header vs. Robots.txt Resolution | John Mueller (Google) and Martin Thomson dive into the specifics of how scrapers should prioritize conflicting signals. |
| 2026-03-02 | meeting | Priority Conflict Discussion | Martin Thomson provides input on resolving priority conflicts between HTTP headers and robots.txt. |
| 2025-02-18 | release | Draft Version 04 Published | Generation of Version 04 of the Internet-Draft. |
