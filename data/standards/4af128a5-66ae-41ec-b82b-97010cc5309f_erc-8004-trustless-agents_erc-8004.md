---
id: 4af128a5-66ae-41ec-b82b-97010cc5309f
title: "ERC-8004: Trustless Agents"
acronym: ERC-8004
status: Draft
organization: "Ethereum"
tags: [AI Agents, Trustless Systems Distributed Registry, ERC-721, Reputation Systems, Validation Registry, A2A, MCP]
link: https://eips.ethereum.org/EIPS/eip-8004
expired: false
created_at: 2026-03-26T01:43:37.947523+00:00
updated_at: 2026-03-26T01:43:37.947523+00:00
---

# ERC-8004: Trustless Agents (ERC-8004)

**Status:** Draft | **Organization:** Ethereum

## Description
A trustless protocol for discovering, choosing, and interacting with AI agents across organizational boundaries using blockchain-based registries. It establishes trust through pluggable models including reputation systems, stake-secured validation, and zero-knowledge proofs.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| Marco De Rossi | MetaMask | Author | [link](https://github.com/MarcoMetaMask) |
| Davide Crapis | Ethereum Foundation | Author | [link](mailto:davide@ethereum.org) |
| Jordan Ellis | Google | Author | [link](mailto:jordanellis@google.com) |
| Erik Reppel | Coinbase | Author | [link](mailto:erik.reppel@coinbase.com) |
| eth-bot | Unknown | GitHub Contributor | [link](https://github.com/eth-bot) |
| Gavin John | caltech | GitHub Contributor | [link](https://github.com/Pandapip1) |
| Greg Colvin | Unknown | GitHub Contributor | [link](https://github.com/gcolvin) |
| Alex Beregszaszi | ethereum @ipsilon @spearbit @ethereumjs | GitHub Contributor | [link](https://github.com/axic) |
| William Entriken | paypal.me/fulldecent | GitHub Contributor | [link](https://github.com/fulldecent) |
| lightclient | Unknown | GitHub Contributor | [link](https://github.com/lightclient) |
| Nick Johnson | True Names Ltd (ENS) | GitHub Contributor | [link](https://github.com/Arachnid) |
| Tim Beiko | Unknown | GitHub Contributor | [link](https://github.com/timbeiko) |
| Etan Kissling | Unknown | GitHub Contributor | [link](https://github.com/etan-status) |
| Sam Wilson | ethereum | GitHub Contributor | [link](https://github.com/SamWilsn) |
| Toni Wahrstätter | Ethereum | GitHub Contributor | [link](https://github.com/nerolation) |
| Yoichi Hirai | Flamingo Ponderado Unipessoal LDA | GitHub Contributor | [link](https://github.com/pirapira) |
| Alita Moore | Wovenmind | GitHub Contributor | [link](https://github.com/alita-moore) |
| Nick Mudge | Perfect Abstractions LLC | GitHub Contributor | [link](https://github.com/mudgen) |
| xinbenlv | d3servelabs | GitHub Contributor | [link](https://github.com/xinbenlv) |
| Andrei Maiboroda | ethereum @ipsilon | GitHub Contributor | [link](https://github.com/gumb0) |
| cdetrio | Unknown | GitHub Contributor | [link](https://github.com/cdetrio) |
| Paweł Bylica | Unknown | GitHub Contributor | [link](https://github.com/chfast) |
| Alex Stokes | Unknown | GitHub Contributor | [link](https://github.com/ralexstokes) |
| James Ray | Unknown | GitHub Contributor | [link](https://github.com/jamesray1) |
| wanderer | Unknown | GitHub Contributor | [link](https://github.com/wanderer) |
| Jan Turk | FraxFinance | GitHub Contributor | [link](https://github.com/ThunderDeliverer) |
| Pooja Ranjan | echinstitute @wiepteam @AvarchLLC | GitHub Contributor | [link](https://github.com/poojaranjan) |
| Mikhail Kalinin | Unknown | GitHub Contributor | [link](https://github.com/mkalinin) |
| Nick Savers | Unknown | GitHub Contributor | [link](https://github.com/nicksavers) |
| Wei Tang | bitarray | GitHub Contributor | [link](https://github.com/sorpaas) |
| Martin HS | Unknown | GitHub Contributor | [link](https://github.com/holiman) |
| pdobacz | Unknown | GitHub Contributor | [link](https://github.com/pdobacz) |
| Francisco Giordano | Unknown | GitHub Contributor | [link](https://github.com/frangio) |
| Jacques Dafflon | Unknown | GitHub Contributor | [link](https://github.com/0xjac) |
| Danno Ferrin | Unknown | GitHub Contributor | [link](https://github.com/shemnon) |
| Charles Cooper | Unknown | GitHub Contributor | [link](https://github.com/charles-cooper) |
| anderselowsson | Unknown | GitHub Contributor | [link](https://github.com/anderselowsson) |
| vbuterin | Unknown | GitHub Contributor | [link](https://github.com/vbuterin) |
| Felix Lange | Unknown | GitHub Contributor | [link](https://github.com/fjl) |
| 5chdn | Unknown | GitHub Contributor | [link](https://github.com/5chdn) |
| chriseth | Unknown | GitHub Contributor | [link](https://github.com/chriseth) |
| SirSpudlington | Unknown | GitHub Contributor | [link](https://github.com/SirSpudlington) |
| Hudson Jameson | Unknown | GitHub Contributor | [link](https://github.com/Souptacular) |
| Erik Marks | Unknown | GitHub Contributor | [link](https://github.com/rekmarks) |
| Ben {chmark} Adams | IllyriadGames | GitHub Contributor | [link](https://github.com/benaadams) |
| Hadrien Croubois | Unknown | GitHub Contributor | [link](https://github.com/Amxx) |
| Ronan Sandford | etherplay | GitHub Contributor | [link](https://github.com/wighawag) |
| Guillaume Ballet | ethereum | GitHub Contributor | [link](https://github.com/gballet) |
| Alberto Cuesta Cañada | Unknown | GitHub Contributor | [link](https://github.com/alcueca) |
| Andrew Cooke | NVIDIA | GitHub Contributor | [link](https://github.com/AC0DEM0NK3Y) |
| EmojiDao | Unknown | GitHub Contributor | [link](https://github.com/emojidao) |
| William Morriss | Unknown | GitHub Contributor | [link](https://github.com/wjmelements) |
| Witek | enjin | GitHub Contributor | [link](https://github.com/coinfork) |
| ligi | ethereum | GitHub Contributor | [link](https://github.com/ligi) |
| Alex Forshtat | eth-infinitism | GitHub Contributor | [link](https://github.com/forshtat) |
| g11tech | G11 Tech Labs | GitHub Contributor | [link](https://github.com/g11tech) |
| Carl Beekhuizen | ethereum | GitHub Contributor | [link](https://github.com/CarlBeek) |
| nixo | Ethereum Foundation | GitHub Contributor | [link](https://github.com/nixorokish) |
| Marius van der Wijden | Unknown | GitHub Contributor | [link](https://github.com/MariusVanDerWijden) |
| Fabian Vogelsteller | LUKSO | GitHub Contributor | [link](https://github.com/frozeman) |
| Ryan Ghods | Unknown | GitHub Contributor | [link](https://github.com/ryanio) |
| Ansgar Dietrichs | Unknown | GitHub Contributor | [link](https://github.com/adietrichs) |
| Dexaran | Unknown | GitHub Contributor | [link](https://github.com/Dexaran) |

## Resources
| Type | Label | URL |
|------|-------|-----|
| primary_spec | Primary Specification | https://eips.ethereum.org/EIPS/eip-8004 |
| mailing_list | Discussion Thread | https://ethereum-magicians.org/t/erc-8004-trustless-agents/25098 |
| github | Source Code | https://github.com/ethereum/EIPs/blob/master/EIPS/eip-8004.md |

## Tags
AI Agents, Trustless Systems Distributed Registry, ERC-721, Reputation Systems, Validation Registry, A2A, MCP

## Latest Summary
ERC-8004 defines a standardized trust layer for decentralized autonomous agents, extending existing communication protocols like Agent-to-Agent (A2A) and Model Context Protocol (MCP). The standard addresses the critical gap in cross-organizational agent discovery and trust, enabling an open-ended agent economy where participants can interact without pre-existing relationships.

The proposal revolves around three primary on-chain registries that can be deployed as singletons on Ethereum Layer 1 or Layer 2 networks:
1.  **Identity Registry**: Utilizes ERC-721 (NFTs) with URIStorage to provide agents with portable, censorship-resistant handles. This allows agents to be browsable and transferable using standard NFT infrastructure.
2.  **Reputation Registry**: Establishes a standard interface for posting and retrieving feedback signals. It supports both on-chain composability for simple metrics and off-chain aggregation for complex scoring algorithms, facilitating specialized services like auditor networks and insurance pools.
3.  **Validation Registry**: Provides generic hooks for recording independent validation checks. These checks vary by "value at risk" and can include stake-secured re-execution, Zero-Knowledge Machine Learning (zkML) proofs, or Trusted Execution Environment (TEE) oracles.

The architecture is designed to be "pluggable and tiered," allowing developers to select security models proportional to the task's stakes (e.g., ordering food vs. medical diagnosis). While payments are considered orthogonal to the core protocol, the specification notes that systems like x402 payments can be integrated to enrich reputation signals.

## What's New
ERC-8004 is currently in the **Draft** stage. Recent activity focuses on establishing the initial three-registry architecture (Identity, Reputation, and Validation). The authors have recently integrated feedback from a broad range of stakeholders, including representatives from Consensys, Google, Coinbase, and the Ethereum Foundation. Key recent refinements include the decision to base the Identity Registry on the **ERC-721** standard to ensure immediate compatibility with the existing NFT ecosystem and the definition of a colon-separated global identifier format (`namespace:chainId:registry`). The team has also announced upcoming collaborations with the **Linux Foundation** and the **A2A (Agent-to-Agent)** community to finalize the specifications for cross-boundary agent discovery.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2025-08-28 | milestone | Discussion Update | The discussion thread is updated to reflect ongoing refinement with A2A ecosystem stakeholders. |
| 2025-08-14 | meeting | Discussion Thread Opened | The proposal is introduced to the Fellowship of Ethereum Magicians for public discussion and technical feedback. |
| 2025-08-13 | draft | Initial EIP Creation | The EIP-8004 draft is officially created by authors from MetaMask, Ethereum Foundation, Google, and Coinbase. |
