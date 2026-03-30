---
id: 11a2e753-9a82-477e-83c7-60f9c06fd3cf
title: "OAuth Entity Profiles for Model-Oriented Resource Access (MORA)"
acronym: MORA
status: Draft
organization: "Anthropic"
tags: [OAuth, AI Identity, Model Access Control, MORA, Authentication]
link: https://github.com/Sreyanth/draft-mora-oauth-entity-profiles
expired: false
created_at: 2026-03-23T02:24:36.186988+00:00
updated_at: 2026-03-23T02:35:41.488418+00:00
---

# OAuth Entity Profiles for Model-Oriented Resource Access (MORA) (MORA)

**Status:** Draft | **Organization:** Anthropic

## Description
OAuth Entity Profiles for Model-Oriented Resource Access (MORA) establishes a framework for identifying and authenticating different entities (like AI models and developers) within an OAuth flow. It specifically addresses how AI models can be uniquely identified and authorized to access resources.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Sreyanth Reddy Mamilla | Anthropic | Author |  |
| Sreyanth | Microsoft | GitHub Contributor | [link](https://github.com/Sreyanth) |

## Resources
| Type | Label | URL |
|------|-------|-----|
| github | GitHub Repository | https://github.com/Sreyanth/draft-mora-oauth-entity-profiles |

## Tags
OAuth, AI Identity, Model Access Control, MORA, Authentication

## Latest Summary
The **OAuth Entity Profiles for Model-Oriented Resource Access (MORA)** is an emerging security standard designed to simplify and standardize how AI models and agents access protected resources. As generative AI and LLM-based agents become increasingly integrated into software ecosystems, there is a growing need for a fine-grained authorization framework that can handle the unique lifecycle and identity requirements of these entities.

MORA defines specific OAuth 2.0 entity profiles to facilitate "Model-Oriented Resource Access." The core objective is to move beyond generic service-to-service authentication by providing mechanisms that allow resource servers to understand whether a request is being made by a model, on behalf of a user, or as part of an autonomous agentic workflow. This involves defining new metadata and claims that describe the model's identity, its provider, and the specific constraints of the task it is performing.

Key components of the standard typically include:
- **Entity Profiles**: Standardized sets of claims for models and agents.
- **Contextual Scoping**: Mechanisms to limit a model's access to only the data necessary for a specific prompt or execution context.
- **Delegation Patterns**: Clarifying how users delegate authority to AI models while maintaining auditability and control.

By standardizing these profiles, MORA aims to improve interoperability between different AI platforms, toolchains, and resource providers, ensuring that security posture is maintained even as AI agents scale in complexity.

## What's New
The most recent activity involves the refinement of **Entity Identity claims** within the OAuth token structure. Recent discussions and updates have focused on distinguishing between the 'Model' (the compute artifact) and the 'Agent' (the logic orchestrating the model). There is a new emphasis on **Attestation-based identity**, exploring how hardware-backed or provider-signed tokens can verify that a request truly originated from a specific AI model version. Additionally, the latest draft revisions include expanded guidance on using **Rich Authorization Requests (RAR)** to express the complex, multidimensional permissions often required by LLM agents.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2024-10-21 | draft | Version 01 Update | The specification was updated to version -01, incorporating feedback regarding model identity and resource scoping. |
| 2024-07-01 | meeting | OAuth Working Group Presentation | The draft was presented and discussed within the OAuth Working Group to gather early feedback on AI-specific security requirements. |
| 2024-06-11 | draft | First Internet-Draft Publication | The initial draft of the MORA specification (draft-mora-oauth-entity-profiles-00) was published to the IETF. |
