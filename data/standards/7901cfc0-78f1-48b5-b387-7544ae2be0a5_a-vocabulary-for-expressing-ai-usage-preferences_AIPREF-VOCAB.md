---
id: 7901cfc0-78f1-48b5-b387-7544ae2be0a5
title: "A Vocabulary For Expressing AI Usage Preferences"
acronym: AIPREF-VOCAB
status: Draft
organization: "IETF"
tags: [AI usage preferences, vocabulary, digital assets, opt-out, AI training, data rights, AI Usage Preferences, Opt-Out, Digital Assets, Vocabulary, IETF Draft]
link: https://datatracker.ietf.org/doc/draft-ietf-aipref-vocab/
expired: false
created_at: 2026-03-24T00:39:52.343871+00:00
updated_at: 2026-03-24T00:47:26.113995+00:00
---

# A Vocabulary For Expressing AI Usage Preferences (AIPREF-VOCAB)

**Status:** Draft | **Organization:** IETF

## Description
This document defines a vocabulary for expressing preferences regarding how digital assets are used by automated processing systems. It allows for the declaration of restrictions or permissions for use of digital assets by AI systems.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Paul Keller | Open Future | Author | [link](https://datatracker.ietf.org/person/paul@openfuture.eu) |
| Martin Thomson | Low Entropy | Author | [link](https://datatracker.ietf.org/person/mt@lowentropy.net) |

## Resources
| Type | Label | URL |
|------|-------|-----|
| primary_spec | Primary Specification (HTML) | https://www.ietf.org/archive/id/draft-ietf-aipref-vocab-05.html |
| mailing_list | Mailing list discussion | https://mailarchive.ietf.org/arch/browse/ai-control/?q=draft-ietf-aipref-vocab |
| working_group | Working Group Page (aipref) | https://datatracker.ietf.org/wg/aipref/about/ |
| other | Primary Specification (TXT) | https://www.ietf.org/archive/id/draft-ietf-aipref-vocab-05.txt |

## Tags
AI usage preferences, vocabulary, digital assets, opt-out, AI training, data rights, AI Usage Preferences, Opt-Out, Digital Assets, Vocabulary, IETF Draft

## Latest Summary
This standard defines a formal vocabulary for expressing human or organizational preferences regarding the use of digital assets by automated processing systems, specifically AI and foundation models. The draft-ietf-aipref-vocab specification provides a structured way for creators and rightsholders to declare restrictions or permissions for their content, addressing the growing need for "opt-out" mechanisms in the age of generative AI. 

The vocabulary is organized into usage categories, such as "Foundation Model Production" and "Search." It allows users to specify an "Effect" (either `allow` or `deny`) for specific types of automated processing. A key aspect of the proposal is its extensibility, allowing for future categories as AI technology evolves. The document also describes a "More Specific Instructions" mechanism, where a general preference can be overridden by a more targeted one (e.g., denying search globally but allowing it for a specific crawler). 

Beyond the vocabulary itself, the standard outlines how these preferences should be combined and processed. It includes a section on an exemplary serialization format using text-based labels and a processing algorithm to handle conflicting or overlapping instructions. The goal is to create a machine-readable standard that can be embedded in various protocols (like HTTP headers or robots.txt-style files) to ensure that AI scrapers and builders respect the intent of content creators. Discussion within the IETF "ai-control" working group currently focuses on the robustness of these declarations, particularly how "unknown" instructions should be handled and the specific constraints on "verbatim" content usage in generative search results.

## What's New
The latest update, **Version 05 (published December 1, 2025)**, focuses on refining the "Foundation Model Production" and "Search" categories. Recent discussions in March 2026 have centered on Section 4.2, specifically the **"Verbatim" constraint**, which aims to define how generative search engines can or cannot display original content in summaries. Additionally, the working group is wrestling with **"Unknown-Ignores" logic**, debating whether systems should default to ignoring preferences they don't recognize or if that creates a legal/compliance loophole for content creators. Proposals for "More Specific Instructions" are also being fine-tuned to ensure that global 'deny' settings can be selectively overridden by trusted agents.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2026-06-04 | deadline | Draft Expiration Date | The current Version 05 draft is set to expire unless replaced or updated. |
| 2026-03-12 | milestone | Generative Search Clarification | Clarification sought regarding the "Verbatim" constraint in Section 4.2 for generative search engines. |
| 2026-03-09 | decision | Compliance Robustness Debate | Mailing list debate regarding the robustness of the "Unknown-Ignores" principle and potential compliance gaps. |
| 2026-03-06 | meeting | Community Feedback on Draft 05 | Discussion on the mailing list regarding minor suggestions for the vocabulary and generative search constraints. |
| 2025-12-01 | draft | Draft Version 05 Published | Release of Version 05 of the Internet-Draft "A Vocabulary For Expressing AI Usage Preferences". |
