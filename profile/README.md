# Hypercerts Github Org

Hypercerts are an open, composable primitive for representing real-world work as durable, inspectable digital records that others can evaluate, fund, and build on over time.

They are designed to support collective funding and coordination across very different domains—such as open-source software, research, public-interest infrastructure, and environmental stewardship—without relying on a single platform, metric, or centralized authority.

<details>
  <summary><strong>What problem does this solve?</strong></summary>

In many domains, valuable work produces public or shared benefits, but information about that work—what was done, by whom, with what evidence, and how it was evaluated—is fragmented, ephemeral, or locked inside platforms.

This makes it difficult to:
- evaluate work in pluralistic ways,
- coordinate funding across many contributors and evaluators,
- reuse prior information rather than recreating it from scratch.

Hypercerts address this by providing a shared, open data model for describing work and its evaluation as first-class, linkable records.
</details>

<details>
  <summary><strong>What are hypercerts?</strong></summary>


At a high level, a hypercert:
- describes **an activity or scope of work**,
- links to **evidence** and contextual data,
- can be **evaluated by multiple parties over time**,
- can be **referenced by funding and ownership mechanisms**.

Hypercerts are not a marketplace or a single application. They are a protocol-level building block that can be used by many different tools, communities, and funding mechanisms.

The design emphasizes: Composability, reuse, plural evaluation, and durability of records.
</details>

<details>
  <summary><strong>Architecture (high level)</strong></summary>

Hypercerts are designed to span both social and financial layers:

- **Offchain / social data**
  - Records for activities, evidence, evaluations, and relationships
  - Designed to live in open, federated data systems (e.g. ATProto)
  - Portable identities and durable references

- **Onchain (optional)**
  - Ownership, fractionalization, and transfer
  - Anchoring records or hashes on public blockchains
  - Used when financial coordination or incentives are required

This separation allows hypercerts to be useful even without tokenization, while still supporting onchain mechanisms where appropriate.
</details>

<details>
  <summary><strong>Who is this for?</strong></summary>

Hypercerts are intended for:
- builders of funding, evaluation, or coordination tools
- evaluators, reviewers, and domain experts producing assessments or judgments
- researchers exploring new institutional or economic mechanisms
- open-source and public-interest projects seeking better funding primitives
- funders experimenting with pluralistic or retrospective allocation models

You do not need to adopt the entire stack to use hypercerts—individual components can be reused independently.

</details>

# Repositories

We are currently working on Hypercerts v0.2, an exciting next generation architecture which will bring much greater scalability and flexibility.  Here you can find both the new v0.2 repositories and the original ones.

## v0.2 Repositories

v0.2 is adding [ATProtocol](https://atproto.com/) to provide an
offchain data layer, so we have several new repositories relating to
work in that area.

- [hypercerts-lexicon](https://github.com/hypercerts-org/hypercerts-lexicon) - the ATProto lexicons (data schema) for Hypercerts v0.2.
- [atproto](https://github.com/hypercerts-org/atproto/) - a friendly fork of ATProto's main monorepo, containing Hypercerts customizations and experiments, in particular:
  - [`packages/sds`](https://github.com/hypercerts-org/atproto/tree/dev/packages/sds) - SDS (Shared Data Server) - an extended version of the PDS which supports shared access to repositories
  - [`packages/sds-demo`](https://github.com/hypercerts-org/atproto/tree/dev/packages/sds-demo) - a demo frontend for trying out the SDS
- [Quickstart scaffold app for v0.2](https://github.com/hypercerts-org/hypercerts-scaffold-atproto)
- [code](https://github.com/hypercerts-org/pdsls) for [sdsls.dev](https://sdsls.dev) - a fork of [pdsls.dev](https://pdsls.dev) which supports writing to shared repos in SDS instances

## v0.1 Repositories

- [hypercerts-protocol](https://github.com/hypercerts-org/hypercerts-protocol) - the hypercerts protocol and the contracts NPM package
- [hypercerts-org](https://github.com/hypercerts-org/hypercerts-org) - the main hypercerts.org website including documentation
- [hypercerts-app](https://github.com/hypercerts-org/hypercerts-app) - the main app.hypercerts.org application
- [hypercerts-sdk](https://github.com/hypercerts-org/hypercerts-sdk) - SDK with contract methods, helpers and other tooling to support developing on the hypercerts protocol
- [marketplace-sdk](https://github.com/hypercerts-org/marketplace-sdk) - fork our the [Looksrare SDK] to support the hypercerts marketplace (built on Looksrare)
- [hypercerts-indexer](https://github.com/hypercerts-org/hypercerts-indexer) - our custom indexer that feeds into our database for rapid access to data across the hypercerts ecosystem
- [hypercerts-api](https://github.com/hypercerts-org/hypercerts-api) - OpenAPI and GraphQL instance for querying our database and storing metadata, allowlists and images
- [ecocerts](https://github.com/hypercerts-org/ecocerts) - discussion and development of hypercerts for ecological impact

# Further Resources

**Contributing**
- [CONTRIBUTING.md](./CONTRIBUTING.md) for how to get involved
- [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) for community standards

**General information**
- Website: https://hypercerts.org  
- Documentation: https://docs.hypercerts.org
- Blog: https://hypercerts.leaflet.pub/

**Contact us**
- [Bluesky](https://bsky.app/profile/hypercerts.org)
- [Twitter](https://x.com/hypercerts)
- [Telegram Announcements](https://t.me/+YF9AYb6zCv1mNDJi)
- [Telegram Support](https://t.me/+FODiLtCV2TgwNzRi)
