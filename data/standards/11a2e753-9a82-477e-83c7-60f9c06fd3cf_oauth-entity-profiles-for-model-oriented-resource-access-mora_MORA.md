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
The **OAuth Entity Profiles for Model-Oriented Resource Access (MORA)** is an emerging security standard designed to address the unique authorization challenges posed by Large Language Models (LLMs) and AI agents. As AI agents increasingly act on behalf of users to access web resources, traditional OAuth flows struggle with the "delegation's delegation" problem. MORA introduces specific entity profiles (Client, Resource Server, and Authorization Server) to standardize how AI models request, receive, and prove authorization for resource access.

The core objective is to provide a structured framework where AI models can be identified and constrained through fine-grained access tokens. This prevents "confused deputy" attacks and ensures that when an AI agent accesses a user's data (e.g., email or calendar), it does so within a verifiable and limited scope. The standard is currently in the early draft stages, with active development focused on defining the interactions between the AI "Consumer" and the data "Provider."

Key technical components include:
- **Entity Identification:** Distinct ways to identify the AI model vs. the application using it.
- **Model-Specific Scopes:** Tailoring OAuth scopes to be interpretable by or restrictive to automated agents.
- **Token Bindings:** Ensuring access tokens are cryptographically bound to the specific AI entity performing the task.

## What's New
Recent activity in the MORA standard development focuses on refining the **Entity Profiles** to better distinguish between the "Primary Client" (the application the user interacts with) and the "AI Agent" (the model performing the processing). Recent updates to the GitHub repository (as of late 2024) include expanded sections on **Proof of Possession (PoP)** tokens to ensure that AI agents cannot reuse intercepted tokens. There is also increased focus on defining "Inference Scopes," which limit the AI's ability to only perform specific actions, such as "summarization only" or "read-only analysis," preventing the model from taking unauthorized destructive actions.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2024-10-25 | draft | Security Considerations Update | Recent commits focusing on alignment with existing OAuth 2.1 best practices and security considerations. |
| 2024-07-22 | draft | Refinement of Entity Interactions | Refinement of the 'Client' and 'Resource Server' interactions specifically for LLM-based agents. |
| 2024-03-18 | draft | Specification Draft Update | Updates to the draft to include preliminary definitions for AI entity profiles. |
| 2024-03-12 | milestone | Repository Initialization | Initial commit and creation of the repository for the MORA draft specification by Sreyanth. |
