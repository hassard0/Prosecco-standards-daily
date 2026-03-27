---
id: 37b22337-7024-4fd6-87bc-f00d35a8a18b
title: "Semantic Conventions for GenAI agent and framework spans"
acronym: OTEL
status: Draft
organization: "OpenTelemetry"
tags: [GenAI, Observability, Telemetry, Semantic Conventions, Tracing, LLM, Agents]
link: https://opentelemetry.io/docs/specs/semconv/gen-ai/gen-ai-agent-spans/
expired: false
created_at: 2026-03-23T17:10:16.660872+00:00
updated_at: 2026-03-23T17:22:06.257214+00:00
---

# Semantic Conventions for GenAI agent and framework spans (OTEL)

**Status:** Draft | **Organization:** OpenTelemetry

## Description
Defines a standardized set of telemetry attributes for Generative AI applications, specifically focusing on agent and framework-level spans. It provides a transition plan for instrumentations to opt-in to experimental GenAI conventions while maintaining backwards compatibility.

## Authors
| Name | Company | Role | Profile |
|------|---------|------|---------|
| OpenTelemetry Maintainers Building GenAI Semantic Conventions | OpenTelemetry | Author |  |
| Patrice Chalin | CNCF, @linuxfoundation | GitHub Contributor | [link](https://github.com/chalin) |
| OpenTelemetry Bot | Unknown | GitHub Contributor | [link](https://github.com/opentelemetrybot) |
| Severin Neumann | Open-Telemetry | GitHub Contributor | [link](https://github.com/svrnm) |
| Vitor Vasconcellos | mercadolibre | GitHub Contributor | [link](https://github.com/vitorvasc) |
| Phillip Carter | Salesforce | GitHub Contributor | [link](https://github.com/cartermp) |
| Masaki Sugimoto | Henry, Inc. | GitHub Contributor | [link](https://github.com/Msksgm) |
| Austin Parker | honeycombio | GitHub Contributor | [link](https://github.com/austinlparker) |
| Michael Yao | DaoCloud | GitHub Contributor | [link](https://github.com/windsonsea) |
| Luc Perkins | Determinate Systems | GitHub Contributor | [link](https://github.com/lucperkins) |
| Kohei Sugimoto | Unknown | GitHub Contributor | [link](https://github.com/kohbis) |
| Fabrizio Ferri-Benedetti | Elastic | GitHub Contributor | [link](https://github.com/theletterf) |
| Robert Pająk | Splunk | GitHub Contributor | [link](https://github.com/pellared) |
| Marylia Gutierrez | grafana | GitHub Contributor | [link](https://github.com/maryliag) |
| Tiffany Hrabusa | grafana | GitHub Contributor | [link](https://github.com/tiffany76) |
| Granville Schmidt | strata-io | GitHub Contributor | [link](https://github.com/gramidt) |
| Trask Stalnaker | Microsoft | GitHub Contributor | [link](https://github.com/trask) |
| Steve Flanders | Splunk, Inc. | GitHub Contributor | [link](https://github.com/flands) |
| Jack Berg | Grafana Labs | GitHub Contributor | [link](https://github.com/jack-berg) |
| Tyler Helmuth | honeycombio | GitHub Contributor | [link](https://github.com/TylerHelmuth) |
| cheng lu | Chinamobile | GitHub Contributor | [link](https://github.com/chluknight1224) |
| Jay DeLuca | grafana | GitHub Contributor | [link](https://github.com/jaydeluca) |
| Gregor Zeitlinger | Grafana Labs | GitHub Contributor | [link](https://github.com/zeitlinger) |
| Brett McBride | Deakin University | GitHub Contributor | [link](https://github.com/brettmc) |
| Piotr Kiełkowicz | splunk | GitHub Contributor | [link](https://github.com/Kielek) |
| Tyler Yahn | splunk | GitHub Contributor | [link](https://github.com/MrAlias) |
| Adriana Villela | Unknown | GitHub Contributor | [link](https://github.com/avillela) |
| Ezzio Moreira | ezziomoreira | GitHub Contributor | [link](https://github.com/EzzioMoreira) |
| Juliano Costa | Datadog | GitHub Contributor | [link](https://github.com/julianocosta89) |
| Diana Todea | VictoriaMetrics | GitHub Contributor | [link](https://github.com/didiViking) |
| Reese Lee | newrelic | GitHub Contributor | [link](https://github.com/reese-lee) |
| Carol Valencia | krolCloud | GitHub Contributor | [link](https://github.com/krol3) |
| Juraci Paixão Kröhling | ollygarden | GitHub Contributor | [link](https://github.com/jpkrohling) |
| Jean Bisutti | Microsoft | GitHub Contributor | [link](https://github.com/jeanbisutti) |
| Alex Boten | Honeycomb | GitHub Contributor | [link](https://github.com/codeboten) |
| Tristan Sloughter | Unknown | GitHub Contributor | [link](https://github.com/tsloughter) |
| Pierre Tessier | honeycombio | GitHub Contributor | [link](https://github.com/puckpuck) |
| Josh Soref | GarnerCorp | GitHub Contributor | [link](https://github.com/jsoref) |
| Daniel Gomez Blanco | newrelic | GitHub Contributor | [link](https://github.com/danielgblanco) |
| jason plumb | Splunk | GitHub Contributor | [link](https://github.com/breedx-splk) |
| Damien Mathieu | elastic | GitHub Contributor | [link](https://github.com/dmathieu) |
| Morgan McLean | splunk, previously @google, @microsoft | GitHub Contributor | [link](https://github.com/mtwo) |
| Pratik Mahalle | Unknown | GitHub Contributor | [link](https://github.com/pratik-mahalle) |
| Jamie Danielson | honeycombio | GitHub Contributor | [link](https://github.com/JamieDanielson) |
| Yoshi Yamaguchi | AWS | GitHub Contributor | [link](https://github.com/ymotongpoo) |
| Imma Valls | Grafana Labs | GitHub Contributor | [link](https://github.com/immavalls) |
| Adam J. Smye-Rumsby | Unknown | GitHub Contributor | [link](https://github.com/adamjsr) |
| Pablo Baeyens | DataDog | GitHub Contributor | [link](https://github.com/mx-psi) |
| Daniel Dyla | Dynatrace | GitHub Contributor | [link](https://github.com/dyladan) |
| Cijo Thomas | Microsoft | GitHub Contributor | [link](https://github.com/cijothomas) |
| Carter Socha | Lightstep | GitHub Contributor | [link](https://github.com/cartersocha) |
| Emídio Neto | Unknown | GitHub Contributor | [link](https://github.com/emdneto) |
| Miguel Luna | Unknown | GitHub Contributor | [link](https://github.com/mlunadia) |
| Riccardo Magliocchetti | Elastic | GitHub Contributor | [link](https://github.com/xrmx) |
| Vladimir Mihailenco | uptrace | GitHub Contributor | [link](https://github.com/vmihailenco) |
| my-git9 | DaoCloud | GitHub Contributor | [link](https://github.com/my-git9) |
| badhon | Unknown | GitHub Contributor | [link](https://github.com/badhon495) |
| Abraham  | Unknown | GitHub Contributor | [link](https://github.com/abalso0) |
| Clément Duveau | Grafana Labs | GitHub Contributor | [link](https://github.com/clementduveau) |
| Ihor Sychevskyi | phalcon | GitHub Contributor | [link](https://github.com/Arhell) |

## Resources
| Type | Label | URL |
|------|-------|-----|
| primary_spec | Semantic Conventions for GenAI agent and framework spans (Primary Spec) | https://opentelemetry.io/docs/specs/semconv/gen-ai/gen-ai-agent-spans/ |
| documentation | OpenTelemetry Registry | https://opentelemetry.io/docs/specs/semconv/registry/ |
| github | OpenTelemetry Specification GitHub | https://github.com/open-telemetry/opentelemetry-specification |

## Tags
GenAI, Observability, Telemetry, Semantic Conventions, Tracing, LLM, Agents

## Latest Summary
The **Semantic Conventions for GenAI agent and framework spans** is an OpenTelemetry specification currently in the **Development** phase. It defines a standardized set of attributes, metric names, and span structures for observability in Generative AI applications, specifically targeting agents and underlying frameworks. 

The standard aims to provide a unified way to instrument GenAI workflows, allowing developers to track the lifecycle of agentic operations, including tool calls, reasoning steps, and model interactions. A critical component of this standard is the **stability transition plan**. To avoid breaking changes in existing instrumentations, OpenTelemetry has introduced a specific opt-in mechanism. Instrumentations using versions prior to **v1.36.0** are instructed to maintain their current output by default. Developers wishing to utilize the newest experimental GenAI conventions must explicitly opt-in using the environment variable `OTEL_SEMCONV_STABILITY_OPT_IN` set to `gen_ai_latest_experimental`.

Key topics covered by the conventions include:
- **Span Definitions:** Identifying specific operations like agent tasks, tool executions, and prompt processing.
- **Attributes:** Standardized metadata for tracking model versions, token counts, and execution context.
- **Registry Integration:** These conventions are automatically integrated into the OpenTelemetry Registry for global discoverability.
- **Experimental Status:** As the spec is in active development, users are cautioned that breaking changes may occur between experimental versions until a stable release is declared.

## What's New
The most significant recent update is the implementation of the **Stability Transition Plan** for GenAI conventions. This introduces the `OTEL_SEMCONV_STABILITY_OPT_IN` environment variable with the value `gen_ai_latest_experimental`. This allows developers to test the latest experimental span and attribute definitions without forcing breaking changes on users of older (v1.36.0 or prior) instrumentations. The specification has also been integrated into the **OpenTelemetry Registry**, making its attributes and entities automatically discoverable within the broader OTel ecosystem. Current work focuses on refining span names and units of measure before the conventions move toward a stable release.

## Timeline
| Date | Type | Title | Description |
|------|------|-------|-------------|
| 2025-01-31 | draft | Active Specification Development | Current development status confirmed via primary documentation and registry updates in early 2025. |
| 2024-10-01 | milestone | Version v1.36.0 Stability Guideline | Reference point for instrumentations using v1.36.0 or prior. Instrumentations are advised not to change default output versions. |
