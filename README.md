

## PDS implementations

| Implementation | Language(s) | Last Updated | ⭐ |
| --- | --- | --- | --- |
| [bluesky-social/pds](https://github.com/bluesky-social/pds) | TypeScript, Go | April, 2026 | 2,474 |
| [blacksky/rsky](https://github.com/blacksky-algorithms/rsky) | Rust | April, 2026 | 657 |
| [tranquil.farm/tranquil](https://tangled.org/tranquil.farm/tranquil-pds) | Rust | April, 2026 | 224 |
| [snarfed/arroba](https://github.com/snarfed/arroba) | Python | April, 2026 | 76 |
| [futur.blue/pegasus](https://tangled.org/futur.blue/pegasus) | OCaml | April, 2026 | 67 |
| [alice.mosphere.at/perlsky](https://tangled.org/alice.mosphere.at/perlsky) | Perl | April, 2026 | 14 |
| [threddyrex/dnproto](https://github.com/threddyrex/dnproto) | C# | April, 2026 | 11 |
| [mary.my.id/danaus](https://tangled.org/mary.my.id/danaus) | TypeScript | April, 2026 | 4 |
| [threddyrex/rustproto](https://github.com/threddyrex/rustproto) | Rust | April, 2026 | 2 |
| [julien.rbrt.fr/vow](https://tangled.org/julien.rbrt.fr/vow) | Go | April, 2026 | 2 |
| [ascorbic/cirrus](https://github.com/ascorbic/cirrus) | TypeScript | March, 2026 | 245 |
| [hailey.at/cocoon](https://tangled.org/hailey.at/cocoon) | Go | March, 2026 | 103 |
| [samuelgoto/micropod](https://github.com/samuelgoto/micropod) | JavaScript | March, 2026 | 9 |
| [chadtmiller.com/pds.js](https://tangled.org/chadtmiller.com/pds.js) | JavaScript | January, 2026 | 46 |
| [desertthunder.dev/PDSharp](https://tangled.org/desertthunder.dev/PDSharp) | F# | January, 2026 | 5 |
| [alteran-social/alteran](https://github.com/alteran-social/alteran) | TypeScript | November, 2025 | 22 |
| [DavidBuchanan314/millipds](https://github.com/DavidBuchanan314/millipds) | Python | October, 2025 | 153 |
| [quilling.dev/bluepds](https://tangled.org/quilling.dev/bluepds) | Rust | May, 2025 | 6 |
| [NetWatchInc/hexpds](https://github.com/NetWatchInc/hexpds) | Elixir | February, 2025 | 41 |
| [PassiveModding/atompds](https://github.com/PassiveModding/atompds) | C# | January, 2025 | 27 |
| [DavidBuchanan314/picopds](https://github.com/DavidBuchanan314/picopds) | Python | November, 2024 | 73 |


## Implementing a PDS

- [docs.bsky.app - AT Protocol XRPC API](https://docs.bsky.app/docs/api/at-protocol-xrpc-api)
- [event stream - atproto](https://atproto.com/specs/event-stream)
- [repository - atproto](https://atproto.com/specs/repository)
- [API hosts and Auth](https://docs.bsky.app/docs/advanced-guides/api-directory)
- [HTTP API (XRPC) - Service Proxy](https://atproto.com/specs/xrpc#service-proxying)
- [What does a PDS implementation entail?](https://github.com/bluesky-social/atproto/discussions/2350)
- [Adversarial ATProto PDS Migration](https://www.da.vidbuchanan.co.uk/blog/adversarial-pds-migration.html)
- [bluesky-social/pds](https://github.com/bluesky-social/pds)
- [multiformats](https://github.com/multiformats/multicodec/blob/master/table.csv)
- [docs.bsky.app - PDS Entryway](https://docs.bsky.app/docs/advanced-guides/entryway)
- [alice.mosphere.at/atproto-smoke - smoke tests for an atproto PDS](https://tangled.org/alice.mosphere.at/atproto-smoke)


## Self-hosting the Bluesky reference PDS

- [github/bluesky-social/pds](https://github.com/bluesky-social/pds)
- [bluesky-social/pds/ACCOUNT_MIGRATION](https://github.com/bluesky-social/pds/blob/main/ACCOUNT_MIGRATION.md)
- [bnewbold: Migrating PDS Account with 'goat'](https://whtwnd.com/bnewbold.net/3l5ii332pf32u)
- [Two-factor auth does not work (issue #99)](https://github.com/bluesky-social/pds/issues/99)
- [Two-factor auth feature request (issue #1071)](https://github.com/bluesky-social/social-app/issues/1071)
- [Can't deactivate old account via goat - do it with web instead](https://github.com/bluesky-social/atproto/issues/3149)
- [How to self-host all of Bluesky except the AppView](https://alice.bsky.sh/post/3laega7icmi2q)
- [Notes on Running a Full-Network atproto Relay (July 2024)](https://whtwnd.com/bnewbold.net/entries/Notes%20on%20Running%20a%20Full-Network%20atproto%20Relay%20(July%202024))
- [A broken relay - relayhound debugging](https://blooym.dev/blog/setting-up-at-pds#a-broken-relay)
- [self-hosting PDS not getting picked up by relay - github issue](https://github.com/bluesky-social/atproto/discussions/4258)



## AppView implementations

| Implementation | Language(s) | Last Updated |
| --- | --- | --- |
| [bluesky-social/atproto](https://github.com/bluesky-social/atproto/tree/main/packages/bsky) | TypeScript, Go | April, 2026 |
| [grainsocial/grain](https://github.com/grainsocial/grain) | TypeScript, Svelte | April, 2026 |
| [gamesgamesgamesgamesgames/happyview](https://github.com/gamesgamesgamesgamesgames/happyview) | TypeScript, Rust | April, 2026 |
| [streamplace/streamplace](https://github.com/streamplace/streamplace) | TypeScript, Go | April, 2026 |


## Implementing an AppView

- [What does an AppView implementation entail?](https://github.com/bluesky-social/atproto/discussions/2961)


## Community discussion

- [Discord: ATProto Touchers](https://discord.gg/3srmDsHSZJ) - main Discord server
- [Github: atproto discussions](https://github.com/bluesky-social/atproto/discussions)
- [Github: pds discussions](https://github.com/bluesky-social/pds/discussions)



## atproto development

- [atproto.com](https://atproto.com/)
- [atproto.com - Quick start guide to building applications on AT Protocol](https://atproto.com/guides/applications)
- [Call for Developer Projects](https://github.com/bluesky-social/atproto/discussions/3049)
- [Federation Architecture Overview - Bluesky](https://bsky.social/about/blog/5-5-2023-federation-architecture)
- [Fission Tech Talks: Bluesky and PLC](https://www.youtube.com/watch?v=m9AVUAUDC2A)
- [Bluesky and the AT Protocol: Usable Decentralized Social Media (arxiv.org)](https://arxiv.org/pdf/2402.03239)
- [plc.directory](https://plc.directory/)


## Using a did:web

- [account creation with bsky-did-web](https://github.com/afternooncurry/bsky-did-web)
- [AT Protocol DIDs](https://atproto.com/specs/did)
- [Resolving Identities | Bluesky](https://docs.bsky.app/docs/advanced-guides/resolving-identities)
- [known issue with CORS - fixing PDSls](https://github.com/notjuliet/pdsls/issues/5)
- [threddyrex.org/.well-known/did.json](https://threddyrex.org/.well-known/did.json)

## atproto apps

- [atmosphere-apps (by Ariel M. (she/her)) — Semble](https://semble.so/profile/byarielm.fyi/collections/3mfdje7uuhu2r) - list of 180+ apps (and growing)




