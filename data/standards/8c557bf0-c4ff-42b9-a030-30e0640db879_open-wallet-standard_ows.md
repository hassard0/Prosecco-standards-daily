---
id: 8c557bf0-c4ff-42b9-a030-30e0640db879
title: "Open Wallet Standard"
acronym: OWS
status: Approved
organization: "MoonPay"
tags: [wallet standard, AI agents, crypto wallets engine, cross-chain, local storage, key management]
link: https://openwallet.sh/
expired: false
created_at: 2026-03-24T18:33:58.847464+00:00
updated_at: 2026-03-24T18:33:58.847464+00:00
---

# Open Wallet Standard (OWS)

**Status:** Approved | **Organization:** MoonPay

## Description
An open standard for secure local wallet storage and agent access that unifies how AI agents, CLIs, and scripts interact with crypto wallets across multiple chains. It provides a unified local storage format and interface for creating, signing, and managing wallets securely.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Neeraj Prasad | Unknown | GitHub Contributor | [link](https://github.com/njdawn) |
| Kevin Arifin | Unknown | GitHub Contributor | [link](https://github.com/kevarifin14) |
| Sam Blackshear | Mysten Labs | GitHub Contributor | [link](https://github.com/sblackshear) |
| Cursor Agent | Unknown | GitHub Contributor | [link](https://github.com/cursoragent) |
| Shalev Keren | sodot-rs | GitHub Contributor | [link](https://github.com/Shalevos) |
| Matan Hamilis | sodot-rs | GitHub Contributor | [link](https://github.com/MatanHamilis) |

## Resources
| Type | Label | URL |
|------|-------|-----|
| other | Homepage | https://openwallet.sh/ |
| primary_spec | Specification Documentation | https://docs.openwallet.sh/ |
| github | Core GitHub Repository | https://github.com/open-wallet-standard/core |

## Tags
wallet standard, AI agents, crypto wallets engine, cross-chain, local storage, key management

## Latest Summary
The **Open Wallet Standard (OWS)** is an open-source technical specification designed to unify how AI agents, CLI tools, and automated scripts interact with cryptographic wallets. The primary goal is to eliminate the security risks associated with fragmented key management—where keys are often scattered across environment variables or proprietary cloud APIs—by providing a standardized local storage format and a unified interface for creating, signing, and managing wallets across multiple blockchain networks.

The architecture of OWS centers on several core pillars:
- **Unified Interface**: A single local storage format that supports multiple chains and tools.
- **Agent Access Layer**: Enables delegated access for AI agents through Model Context Protocol (MCP) servers, REST APIs, and dedicated SDKs.
- **Policy Engine**: A security layer that evaluates sign requests against pre-defined rules (gated signing) before execution.
- **Secure Local Storage**: An encrypted keystore format that keeps sensitive material at rest with in-process hardening during active use.

The standard utilizes **Chain Agnostic Improvement Proposals (CAIP)** identifiers (such as CAIP-2 for chains and CAIP-10 for accounts) to ensure interoperability. Its technical design covers the entire wallet lifecycle, from creation and derivation (supporting BIP-44 paths) to signing transactions and messages, and eventually migration or recovery. OWS identifies itself as a multi-chain solution, supporting ecosystems including Ethereum (EIP-155), Solana, Bitcoin (BIP-122), Cosmos, TRON, TON, and others.

## What's New
The Open Wallet Standard has recently launched **Version 1.0.0**, establishing a stable baseline for local wallet storage and agent access. Recent updates include the publication of the full technical specification across seven key domains, including Storage Format (01), Policy Engine (03), and Agent Access Layers (04). The ecosystem has also seen the introduction of the **OWS CLI** and SDKs for **Node.js** and **Python**, allowing developers to implement policy-gated signing and multi-chain address generation via a single command. Additionally, the standard now features a robust marquee of ecosystem contributors and supporters, ranging from major payment providers like PayPal and Ripple to blockchain foundations like Solana, Ethereum, and TON.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2025-02-14 | release | OWS v1.0.0 Release | Version 1.0.0 of the Open Wallet Standard and its core SDK/CLI was released to the public. |
| 2025-02-13 | milestone | Initial GitHub Repository Launch | The openwallet-standard/core repository was created on GitHub, marking the public availability of the project codebase. |
