---
id: 80e101b2-e888-4e29-9b52-4aa3b7f7f6ab
title: "Cross App Access (Identity Assertion Authorization Grant)"
acronym: XAA
status: Draft
organization: "IETF"
tags: [Agents, Security, OAuth 2.0, Authorization Grant, Token Exchange]
link: https://datatracker.ietf.org/doc/draft-parecki-oauth-identity-assertion-authz-grant/
expired: false
created_at: 2026-03-22T18:33:31.70173+00:00
updated_at: 2026-03-22T23:50:11.636278+00:00
---

# Cross App Access (Identity Assertion Authorization Grant) (XAA)

**Status:** Draft | **Organization:** IETF

## Description
Cross App Access (XAA) lets enterprises enable secure agent-to-app and app-to-app access with centralized IT oversight. Instead of scattered integrations and repeated logins, admins decide what connects, enforce security policies, and see exactly what's being accessed. This makes cross-app and cross-agent integrations seamless and scalable across the enterprise.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Aaron Parecki | Okta | Author | [link](https://datatracker.ietf.org/person/aaron@parecki.com) |
| Karl McGuinness | Okta | Author | [link](https://datatracker.ietf.org/person/public@karlmcguinness.com) |
| Brian Campbell | Ping Identity | Author | [link](https://datatracker.ietf.org/person/brian.d.campbell@gmail.com) |

## Resources
| Type | Label | URL |
|------|-------|-----|
| mailing_list | Mailing list discussion | https://mailarchive.ietf.org/arch/browse/oauth/?q=draft-parecki-oauth-identity-assertion-authz-grant |
| working_group | OAuth Working Group | https://datatracker.ietf.org/wg/oauth/about/ |
| other | Document History | https://datatracker.ietf.org/doc/draft-parecki-oauth-identity-assertion-authz-grant/history/ |
| documentation | Plain Text version | https://www.ietf.org/archive/id/draft-parecki-oauth-identity-assertion-authz-grant-05.txt |

## Tags
Agents, Security, OAuth 2.0, Authorization Grant, Token Exchange

## Latest Summary
The **Identity Assertion Authorization Grant** (often referred to in discussions as ID-JAG) is an OAuth 2.0 extension designed to facilitate cross-app access in enterprise environments. Specifically, it enables an application that has already authenticated a user via an Identity Provider (IdP) to obtain an access token for a third-party API (Resource Server) without requiring the user to re-authenticate or interact with a browser again. 

The mechanism leverages two existing standards: **Token Exchange ([RFC 8693](https://tools.ietf.org/html/rfc8693))** and the **JWT Profile for OAuth 2.0 Authorization Grants ([RFC 7523](https://tools.ietf.org/html/rfc7523))**. In this flow, an application takes its initial identity assertion (like an OIDC ID Token) and exchanges it at the IdP for a specialized 'Identity Assertion Authorization Grant' JWT. This new JWT is then presented to the third-party Authorization Server to obtain the final access token.

Key architectural benefits include providing a seamless user experience across different applications and services within a common enterprise umbrella while maintaining strong security boundaries between different trust domains. Current working group discussions are focused on refining security considerations, such as preventing delegation chain splicing and clarifying rules for cases where the client and the API share the same IdP.

## What's New
The standard has recently transitioned from an individual submission to an official OAuth Working Group item, now designated as `draft-ietf-oauth-identity-assertion-authz-grant-02`. Recent activity in February and March 2026 includes intensive technical debates on the OAuth mailing list regarding **Delegation Chain Splicing**—a security risk where malicious actors might attempt to combine unrelated tokens in a Token Exchange flow. There is also ongoing feedback concerning the "same IdP prohibition," where developers are seeking clarification on how the grant should behave when the application and the target API are managed by the same identity provider. Version 05 of the draft was published in July 2025, providing updated processing rules for error responses and Identity Assertion JWTs.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2026-03-12 | decision | Security Consideration Discussion | Experts discuss potential security risks involving delegation chain splicing in the context of RFC 8693. |
| 2026-03-02 | milestone | I-D Action: draft-ietf-oauth-identity-assertion-authz-grant-02 | The draft is formally adopted or updated within the IETF OAuth Working Group as a working group item. |
| 2026-02-17 | meeting | Discussion on IdP Prohibitions | Working group members discuss application-to-application delegation and same-IdP prohibitions. |
| 2025-07-02 | release | Draft Version 05 Published | Release of the version 05 of the individual draft. |
| 2025-01-03 | deadline | Draft Expiration Date | Document draft-parecki-oauth-identity-assertion-authz-grant-05 is scheduled to expire. |
