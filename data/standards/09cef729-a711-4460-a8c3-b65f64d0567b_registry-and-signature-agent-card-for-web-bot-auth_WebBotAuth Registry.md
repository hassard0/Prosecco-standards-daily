---
id: 09cef729-a711-4460-a8c3-b65f64d0567b
title: "Registry and Signature Agent card for Web bot auth"
acronym: WebBotAuth Registry
status: Draft
organization: "IETF"
tags: [Web Bot, Authentication, JSON, IANA Registry, Signature Agent, Metadata]
link: https://datatracker.ietf.org/doc/draft-meunier-webbotauth-registry/
expired: false
created_at: 2026-03-23T10:26:22.544264+00:00
updated_at: 2026-03-23T11:16:23.677522+00:00
---

# Registry and Signature Agent card for Web bot auth (WebBotAuth Registry)

**Status:** Draft | **Organization:** IETF

## Description
This document defines a JSON-based 'Signature Agent Card' format for web agents to advertise metadata including identity, purpose, and cryptographic keys. It also establishes an IANA registry for these parameters to enable extensible and interoperable discovery of agent information.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Maxime Guerreiro | Cloudflare | Author |  |
| Ulas Kirazci | Amazon | Author |  |
| Thibault Meunier | Cloudflare | Author |  |

## Resources
| Type | Label | URL |
|------|-------|-----|
| documentation | Internet-Draft (TXT) | https://www.ietf.org/archive/id/draft-meunier-webbotauth-registry-01.txt |
| documentation | Internet-Draft (HTML) | https://www.ietf.org/archive/id/draft-meunier-webbotauth-registry-01.html |
| other | Document History | https://datatracker.ietf.org/doc/draft-meunier-webbotauth-registry/history/ |
| mailing_list | Email Expansions | https://datatracker.ietf.org/doc/draft-meunier-webbotauth-registry/email/ |

## Tags
Web Bot, Authentication, JSON, IANA Registry, Signature Agent, Metadata

## Latest Summary
The "Registry and Signature Agent card for Web bot auth" is a proposed informational standard designed to formalize how automated web clients (bots) identify themselves to origin servers. Currently, bot identification is inconsistent, relying on a mix of User-Agent strings, static IP lists, or external documentation. This draft introduces the **Signature Agent Card**, a JSON-based format that allows agents to advertise metadata including identity, purpose, contact information, rate expectations, and cryptographic keys.

Key components of the standard include:
*   **Signature Agent Card Parameters**: A set of JSON fields such as `client_name`, `purpose` (e.g., search, TDM), `expected-user-agent`, and `rate-expectation`.
*   **Cryptographic Integration**: The card includes a `keys` parameter containing a JSON Web Key Set (JWKS), enabling servers to verify signed HTTP requests from the bot.
*   **Discovery Mechanisms**: The document defines how registries (lists of URLs pointing to agent cards) can be published and accessed using HTTPS or data URIs.
*   **IANA Registry**: The draft proposes the creation of an IANA registry for "Signature Agent Card Parameters" to ensure the format remains extensible and interoperable.

By providing a structured way for bots to declare their intent and operational constraints (like `robots.txt` compliance and rate control), the standard aims to improve trust and reduce the friction between bot operators and website administrators.

## What's New
The latest revision (**01**) of the draft, published in October 2025, refines the **Signature Agent Card** JSON structure and clarifies the discovery process. Notable updates include the formalization of parameters for **robots.txt compliance** (`rfc9309-compliance`) and **rate-expectation** (e.g., `avg=10rps;max=100rps`). The draft also introduces a more detailed **Discovery** section using ABNF syntax to define registry formats and supports the use of `https`, `http`, and `data` URI schemes for accessing agent cards. Discussion has been revitalized within the **Web Bot Auth Working Group** to address outstanding "TODO" items regarding signature formats and rate control specifications.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2026-04-23 | deadline | Draft Expiration Date | The current version of the Internet-Draft is scheduled to expire. |
| 2025-10-20 | draft | Draft version 01 Published | Publication of the updated Internet-Draft draft-meunier-webbotauth-registry-01. |
