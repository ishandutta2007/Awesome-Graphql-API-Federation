# Awesome-Graphql-API-Federation

## Top GraphQL API Federation Tools Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Supergraph Composition, Federated Gateways & Cross-Service Schema Governance*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **GraphQL API Federation**. These tools compose multiple GraphQL and REST services into a unified supergraph, enabling clients to query data across teams and systems through a single endpoint — with schema governance, query planning, and observability built in.



**Examples** include Salesforce MuleSoft DataGraph, Apollo Federation, Hasura Cloud, WunderGraph Cosmo, GraphQL Hive, StepZen, Grafbase, Inigo, Hygraph, and Tyk GraphQL (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom router logic, and transparent federation governance — ideal for platform teams prioritizing data sovereignty, developers building supergraphs, and organizations avoiding per-query pricing.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Salesforce MuleSoft DataGraph](https://www.mulesoft.com/)**  

  Unified GraphQL schema layer over existing APIs, allowing developers to consume data from multiple services in a single request. Features object type merging and SaaS-hosted runtime .



- **[Apollo Federation](https://www.apollographql.com/)**  

  The original federation specification with Apollo Router and GraphOS platform for schema registry, composition checks, and managed gateway. Supports Federation v1 and v2 .



- **[Hasura Cloud](https://hasura.io/)**  

  Multi-protocol data federation that connects databases, REST APIs, and GraphQL services into a unified graph. Can act as a supergraph gateway or as a subgraph within Apollo Federation .



- **[WunderGraph Cosmo](https://wundergraph.com/)**  

  Open-source GraphQL federation platform with Apache 2.0 licensing. Includes schema registry, composition checks, analytics, and a high-performance Go router supporting Federation v1 and v2. Production users include eBay (100% of federated traffic) and SoundCloud .



- **[GraphQL Hive](https://the-guild.dev/graphql/hive)**  

  The Guild's schema registry and analytics platform for federation, MIT-licensed. Acquired Grafbase in February 2026, integrating its Rust router into Hive Router. SOC-2 Type II certified .



- **[StepZen](https://stepzen.com/)**  

  GraphQL API builder that connects REST, database, and GraphQL backends into a unified endpoint. Now part of IBM. Features CLI-driven schema generation and directive-based data source connection .



- **[Grafbase](https://grafbase.com/)**  

  Enterprise federation platform with Rust-powered gateway, schema registry, and management API. Acquired by The Guild in February 2026 and being integrated into Hive Platform .



- **[Inigo](https://inigo.io/)**  

  GraphQL API management platform providing visibility and control over production APIs. Features schema-based RBAC, performance monitoring, rate limiting, and query protection. Agent runs as middleware, sidecar, or proxy .



- **[Hygraph](https://hygraph.com/)**  

  Federated content platform that can incorporate remote data sources (including GraphQL APIs) into its schema for unified content delivery .



- **[Tyk GraphQL](https://tyk.io/)**  

  API gateway with native GraphQL support including query validation, schema validation, introspection headers, and the ability to persist GraphQL queries as REST endpoints .



## Open-Source GitHub Projects



- **[WunderGraph Cosmo](https://github.com/wundergraph/cosmo)**  

  Apache 2.0 licensed GraphQL federation platform. Includes schema registry, composition validation, analytics, and a Go-based router supporting Apollo Federation v1 and v2. Ships OpenTelemetry and Prometheus natively. Helm chart available for Kubernetes deployment. 748+ GitHub stars .



- **[GraphQL Hive](https://github.com/kamilkisiela/graphql-hive)**  

  MIT-licensed schema registry and analytics platform for GraphQL federation. Features schema policies, breaking change detection, and usage analytics. ClickHouse-powered for billions of requests. Self-hostable since October 2022 .



- **[Hive Router](https://github.com/graphql-hive/router)**  

  High-performance Rust-based GraphQL Federation gateway, open-sourced as part of The Guild's Hive Platform. Production-ready alternative to Apollo Router with full Federation compatibility .



- **[Apollo Router](https://github.com/apollographql/router)**  

  The Apollo Federation gateway, configurable and extensible for self-hosted deployments. Supports Federation v1 and v2 supergraphs.



- **[Apollo Federation Gateway](https://github.com/apollographql/federation)**  

  The original federation reference implementation and gateway for composing multiple GraphQL services .



- **[Hasura GraphQL Engine](https://github.com/hasura/graphql-engine)**  

  Open-source GraphQL engine that can federate databases, REST APIs, and remote GraphQL schemas. Supports acting as an Apollo Federation v1 subgraph or as a multi-protocol supergraph gateway .



- **[GraphQL Mesh](https://github.com/ardatan/graphql-mesh)**  

  The Guild's library for using GraphQL to query any data source (REST, SOAP, gRPC, databases). Can compose multiple sources into a unified GraphQL schema .



- **[GoRouTer](https://github.com/StevenACoffman/gorouter)**  

  Apollo Federation v2 query planning and execution package for Go. Implements supergraph routing with entity fetch specs, parallel fetch execution, and projection trimming .



- **[GraphQL Yoga](https://github.com/dotansimha/graphql-yoga)**  

  The Guild's GraphQL server with federation support, plugin architecture, and subscription handling.



### Additional Strong Open-Source Options



- **[Envelop](https://github.com/dotansimha/envelop)** — Lightweight library for building, sharing, and extending GraphQL execution layers. Compatible with federation plugins .

- **[GraphQL Scalars](https://github.com/graphql-hive/graphql-scalars)** — Library of custom GraphQL scalars for precise type-safe schemas, useful in federated subgraphs .

- **[GraphQL JIT](https://github.com/zalando-incubator/graphql-jit)** — GraphQL execution using a JIT compiler for performance-critical federation gateways .

- **Composite Schema Specification** — Emerging vendor-neutral standard under the GraphQL Foundation to standardize federation across implementations .



**Frameworks for building custom systems**: Combine **WunderGraph Cosmo** or **GraphQL Hive** for schema registry and governance, **Hive Router** or **Apollo Router** for the federation gateway, **Hasura** or **GraphQL Mesh** for multi-protocol subgraph composition, and **Inigo** for production API security to build a complete self-hosted GraphQL federation stack.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- GraphQL federation tools must comply with data protection regulations (GDPR, CCPA), API security best practices, and schema governance requirements.

- Self-hosted open-source solutions require proper security hardening, router scaling, and subgraph maintenance.



---



**Made for platform engineers, API architects, GraphQL developers, and teams building federated supergraph platforms.**  

Let's make GraphQL API federation more open, composable, and data-sovereign.
