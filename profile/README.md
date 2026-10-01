# Hypercerts

Hypercerts is an open protocol for describing work, evidence, evaluations, and funding on [AT Protocol](https://atproto.com/). It gives projects, evaluators, communities, and funders a shared language for recognizing valuable work and making better funding decisions.

A hypercert is a living, verifiable record of impact work: who contributed, what they did, when, and in what scope. Linked evidence, measurements, contributions, and independent evaluations enrich that record over time. Records live in AT Protocol repositories controlled by their authors, so compatible applications can reuse them without locking the information into one platform.

[Certified](https://certified.app) is an application built on the Hypercerts Protocol. It lets people publish activities, group them into projects, organize as groups, and recognize each other's work through endorsements. Hypercerts is the shared protocol, not a single application or marketplace.

## Start with the documentation

**[docs.hypercerts.org](https://docs.hypercerts.org/)** is the main entry point for the current protocol, integration guides, tools, and service references.

- [What are Hypercerts?](https://docs.hypercerts.org/core-concepts/what-is-hypercerts): the record structure and how it is used.
- [Quickstart](https://docs.hypercerts.org/getting-started/quickstart): create your first hypercert.
- [Building on Hypercerts](https://docs.hypercerts.org/getting-started/building-on-hypercerts): integration patterns for platforms and tools.
- [Core data model](https://docs.hypercerts.org/core-concepts/hypercerts-core-data-model) and [lexicon reference](https://docs.hypercerts.org/lexicons/introduction-to-lexicons): record types, schemas, and relationships.
- [Architecture overview](https://docs.hypercerts.org/architecture/overview) and [Certified services](https://docs.hypercerts.org/reference/certified-services): how the infrastructure fits together and where to connect.

On-chain anchoring and tokenization for the AT Protocol-based protocol are planned, not currently implemented. Hypercerts records are not tokens. See [Funding & Value Flow](https://docs.hypercerts.org/core-concepts/funding-and-value-flow) for the current design and status.

## Current repositories

### Protocol and infrastructure

| Repository | Purpose | Documentation |
| --- | --- | --- |
| [hypercerts-lexicon](https://github.com/hypercerts-org/hypercerts-lexicon) | Hypercerts and Certified lexicons, generated TypeScript types, and validators | [Lexicons](https://docs.hypercerts.org/lexicons/introduction-to-lexicons) |
| [ePDS](https://github.com/hypercerts-org/ePDS) | Extended Personal Data Server with email-first account creation and authentication | [ePDS](https://docs.hypercerts.org/architecture/epds) |
| [certified-group-service](https://github.com/hypercerts-org/certified-group-service) | Role-based governance and shared management of a group's AT Protocol repository | [CGS](https://docs.hypercerts.org/architecture/certified-group-service) |
| [hypercerts-relay](https://github.com/hypercerts-org/hypercerts-relay) | Relay and Jetstream infrastructure for streaming repository events | [Relay and Jetstream](https://docs.hypercerts.org/tools/hypercerts-relay) |
| [hypercerts-feed-service](https://github.com/hypercerts-org/hypercerts-feed-service) | Read-only, viewer-scoped feeds from indexed Hypercerts data | [Feed Service](https://docs.hypercerts.org/tools/hypercerts-feed-service) |

The documentation also covers [Hyperindex](https://docs.hypercerts.org/tools/hyperindex), the ecosystem indexer maintained in [gainforest/hyperindex](https://github.com/gainforest/hyperindex). The former `hypercerts-org/hyperindex` repository is archived.

### Applications and developer resources

- [certified-app](https://github.com/hypercerts-org/certified-app): the application at [certified.app](https://certified.app).
- [skills](https://github.com/hypercerts-org/skills): [agent skills](https://docs.hypercerts.org/tools/hypercerts-agent-skills) for working across the Hypercerts stack.
- [documentation](https://github.com/hypercerts-org/documentation): the source for [docs.hypercerts.org](https://docs.hypercerts.org/).
- [hypercerts-org](https://github.com/hypercerts-org/hypercerts-org): the [hypercerts.org](https://hypercerts.org) website.

<details>
  <summary><strong>Legacy repositories (v0.1)</strong></summary>

These repositories belong to the earlier blockchain-based implementation, not the current AT Protocol-based integration path. Start with the documentation above for new integrations.

- [hypercerts-protocol](https://github.com/hypercerts-org/hypercerts-protocol): smart contracts and the contracts npm package.
- [hypercerts-app](https://github.com/hypercerts-org/hypercerts-app): the original app.hypercerts.org application.
- [hypercerts-sdk](https://github.com/hypercerts-org/hypercerts-sdk): the deprecated contract SDK.
- [marketplace-sdk](https://github.com/hypercerts-org/marketplace-sdk): the marketplace SDK built on LooksRare.
- [hypercerts-indexer](https://github.com/hypercerts-org/hypercerts-indexer): the legacy contract indexer.
- [hypercerts-api](https://github.com/hypercerts-org/hypercerts-api): the legacy OpenAPI and GraphQL API.

</details>

## Get involved

- [Contributing](https://github.com/hypercerts-org/.github/blob/main/profile/CONTRIBUTING.md) and [Code of conduct](https://github.com/hypercerts-org/.github/blob/main/profile/CODE_OF_CONDUCT.md).
- [Website](https://hypercerts.org), [blog](https://hypercerts.org/blog), and [contact](https://hypercerts.org/contact).
- [Bluesky](https://bsky.app/profile/hypercerts.org), [Twitter](https://x.com/hypercerts), and [Telegram / support](https://t.me/+o4wPsJ7yEZYzNGFk).

## Supporters

The hypercerts project is supported by organizations and individuals who believe in building open, interoperable infrastructure for recognizing and coordinating around real-world work. These include: Protocol Labs, Ma Earth, GainForest, Optimism, Octant, Gitcoin, Silvi, Regen Foundation, and Funding the Commons.

Their support, through funding, collaboration, feedback, and shared experimentation, helps advance the development of hypercerts as a public-good primitive. Support does not imply endorsement of specific design decisions or applications.

We're grateful to all supporters who contribute time, resources, and trust to this ongoing effort.
