# Hypercerts

**Open infrastructure for funding valuable work.**

Hypercerts is an open protocol to connect projects with those who review them, vouch for them, and back them, creating the trust it takes to fund what matters.

Projects publish their work, updates, and evidence as records they control. Others add endorsements, evaluations, and funding records, each attributed to whoever provided it. Built on [AT Protocol](https://atproto.com/), these records can be reused across compatible applications, so the next funding decision can build on what is already known instead of starting from scratch.

A hypercert describes planned, ongoing, or completed work: who contributed, what they did, when, and where. Evidence and independent assessments build a fuller picture over time. Hypercerts is shared infrastructure, not a marketplace or a single application, and individual components can be used independently.

## Learn more and build

- [Website](https://hypercerts.org): why Hypercerts matters and how it is used.
- [Documentation](https://docs.hypercerts.org/): the Guide, Client Integration, Reference, and Changes, including maintained components and their repositories.
- [Start the Guide](https://docs.hypercerts.org/guide): how work, evidence, trust, and funding connect.
- [Get in touch](https://hypercerts.org/contact): bring a project, funding program, or integration idea.

## Get involved

- [Contributing](https://github.com/hypercerts-org/.github/blob/main/profile/CONTRIBUTING.md): how to help with code, evaluation, documentation, and feedback.
- [Code of conduct](https://github.com/hypercerts-org/.github/blob/main/profile/CODE_OF_CONDUCT.md): our community standards.
- [Blog](https://hypercerts.org/blog): project updates and ideas.
- [Bluesky](https://bsky.app/profile/hypercerts.org), [Twitter](https://x.com/hypercerts), [Telegram](https://t.me/+YF9AYb6zCv1mNDJi), and [Telegram Support](https://t.me/+FODiLtCV2TgwNzRi).

## Supporters

The hypercerts project is supported by organizations and individuals who believe in building open, interoperable infrastructure for recognizing and coordinating around real-world work. These include: Protocol Labs, Ma Earth, GainForest, Optimism, Octant, Gitcoin, Silvi, Regen Foundation, and Funding the Commons.

Their support, through funding, collaboration, feedback, and shared experimentation, helps advance the development of hypercerts as a public-good primitive. Support does not imply endorsement of specific design decisions or applications.

We're grateful to all supporters who contribute time, resources, and trust to this ongoing effort.

## Legacy

These repositories are no longer maintained. All are archived except hypercerts-api and hypercerts-indexer, which hold the code behind the v1 API that still runs at api.hypercerts.org. Hypercerts has reached v2, and the v1 app has been retired: see [hypercerts.org/v1-retired](https://hypercerts.org/v1-retired).

**Hypercerts v1**

- [hypercerts-protocol](https://github.com/hypercerts-org/hypercerts-protocol): the v1 minting and marketplace contracts, with their deployment addresses and audits.
- [protocol-periphery](https://github.com/hypercerts-org/protocol-periphery): periphery contracts for the v1 protocol.
- [marketplace-sdk](https://github.com/hypercerts-org/marketplace-sdk): TypeScript SDK for the v1 marketplace contracts, forked from LooksRare's.
- [hypercerts-sdk](https://github.com/hypercerts-org/hypercerts-sdk): the v1 SDK, `@hypercerts-org/sdk` up to version 2, and an early AT Protocol SDK.
- [hypercerts-api](https://github.com/hypercerts-org/hypercerts-api): the v1 API.
- [hypercerts-indexer](https://github.com/hypercerts-org/hypercerts-indexer): the indexer behind the v1 API.
- [hypercerts-chainsauce](https://github.com/hypercerts-org/hypercerts-chainsauce): fork of chainsauce, used by the v1 indexer.
- [hypercerts-template](https://github.com/hypercerts-org/hypercerts-template): a starter for building a hypercerts platform, forked from VoiceDeck.
- [hyperboards-v1](https://github.com/hypercerts-org/hyperboards-v1): the first Hyperboards. The current one is at [hyperboards.org](https://www.hyperboards.org).
- [hypercerts-attestor-registry](https://github.com/hypercerts-org/hypercerts-attestor-registry): a public registry of trusted attestors.
- [hypercerts](https://github.com/hypercerts-org/hypercerts): the original monorepo. [hypercerts-v1](https://github.com/hypercerts-org/hypercerts-v1) is a backup copy of it.

**Early AT Protocol work**

- [hyperindex](https://github.com/hypercerts-org/hyperindex): a Go AT Protocol indexer with a GraphQL API, formerly Hypergoat.
- [hypercerts-scaffold-atproto](https://github.com/hypercerts-org/hypercerts-scaffold-atproto): a Next.js scaffold for hypercerts on AT Protocol.
