# Hypercerts

**Open infrastructure for funding valuable work.**

Hypercerts is an open protocol to connect projects with those who review them, vouch for them, and back them, creating the trust it takes to fund what matters.

Projects publish their work, updates, and evidence as records they control. Others add endorsements, evaluations, and funding records, each attributed to whoever provided it. Built on [AT Protocol](https://atproto.com/), these records can be reused across compatible applications, so the next funding decision can build on what is already known instead of starting from scratch.

A hypercert, or activity claim, describes planned, ongoing, or completed work: who contributed, what they did, when, and where. It is the publisher's account of the work, not proof of impact on its own. Evidence and independent assessments help others judge it over time.

## Start with the documentation

**[docs.hypercerts.org](https://docs.hypercerts.org/)** explains the protocol and the stack in four sections:

- [Guide](https://docs.hypercerts.org/guide): how work, evidence, assessments, trust, and funding connect across applications.
- [Client Integration](https://docs.hypercerts.org/client-integration): where your application fits, account setup, and what you can build with today.
- [Reference](https://docs.hypercerts.org/reference): lexicons, services and tooling, and the API and SDK as they are released.
- [Changes](https://docs.hypercerts.org/changes): protocol releases and component versions.

New to the project? Start with [hypercerts.org](https://hypercerts.org) for the high-level story, then follow the Guide. For schemas and connection details, see the [lexicon inventory](https://docs.hypercerts.org/reference/lexicon-inventory) and [services overview](https://docs.hypercerts.org/reference/services).

## Certified accounts

[certified.app](https://certified.app) is where people create and manage their Certified account: their profile, connected applications, groups, and endorsements. The account is an AT Protocol account, independent of any one application. Your application sits beside certified.app as another client of the same account. See [certified.app in the reference](https://docs.hypercerts.org/reference/services/certified-app).

## Current repositories

### Protocol and infrastructure

| Repository | Purpose | Documentation |
| --- | --- | --- |
| [hypercerts-lexicon](https://github.com/hypercerts-org/hypercerts-lexicon) | Hypercerts and Certified lexicons, generated TypeScript types, and validators | [Lexicons](https://docs.hypercerts.org/lexicons/introduction-to-lexicons) |
| [ePDS](https://github.com/hypercerts-org/ePDS) | Software behind the running Certified PDSs and email sign-in today | [Certified PDSs](https://docs.hypercerts.org/reference/services/certified-pdss) |
| [certified-group-service](https://github.com/hypercerts-org/certified-group-service) | Role-based governance and shared management of a group's AT Protocol repository | [CGS](https://docs.hypercerts.org/reference/services/certified-group-service) |
| [hypercerts-relay](https://github.com/hypercerts-org/hypercerts-relay) | Relay and Jetstream infrastructure for streaming repository events | [Relay and Jetstream](https://docs.hypercerts.org/reference/services/relay) |
| [happyview](https://github.com/hypercerts-org/happyview) | Lexicon-driven AppView underpinning the indexer and Hypercerts API, under development | [Indexer and Hypercerts API](https://docs.hypercerts.org/reference/services/indexer) |
| [orglabeler](https://github.com/hypercerts-org/orglabeler) | Signed quality labels for Certified organization data | [Labelers](https://docs.hypercerts.org/reference/services/labelers) |
| [hypercerts-feed-service](https://github.com/hypercerts-org/hypercerts-feed-service) | Read-only, viewer-scoped feeds from indexed Hypercerts data | [Feed Service](https://docs.hypercerts.org/reference/services/feed-service) |

The [Hypercerts API](https://docs.hypercerts.org/reference/xrpc-api), [SDK](https://docs.hypercerts.org/reference/sdk), and [Entryway](https://docs.hypercerts.org/reference/services/entryway) are under development. Their reference pages describe their status and what to use today; they are not released integration dependencies.

### Applications and documentation

- [certified-app](https://github.com/hypercerts-org/certified-app): Certified account, profile, group, endorsement, and connected-application management.
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
