# Repolex Knowledge Graph of sphinx-doc/sphinxcontrib-websupport

RDF knowledge graph data for [sphinx-doc/sphinxcontrib-websupport](https://github.com/sphinx-doc/sphinxcontrib-websupport), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download sphinx-doc/sphinxcontrib-websupport
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 25dab08ff48c21a470f4b0658c2a85da17b4ad9b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 25dab08ff48c21a470f4b0658c2a85da17b4ad9b
│           └── chunk-001.nq.gz
├── blob
│   ├── 03c941a44300de8960c359cb7926fa2282680157.nq.gz
│   ├── 0ac0558e255ebff241287a34f64cae829ca510dd.nq.gz
│   ├── 10cef947b5c9825090a209f2e6a9f0409e20de24.nq.gz
│   ├── 10e035b6d4af098bbd151c327b936b10483f5d39.nq.gz
│   ├── 1211300c26c4b84ad8c8df6cbd379832afd2a393.nq.gz
│   ├── 138fd219ce8f1cd67e31ac91a626475dba963e89.nq.gz
│   ├── 13e094ecd850b701eb5c971ae40814442c023877.nq.gz
│   ├── 14fd214c4d38231afd7c765f4d38bc99919ea383.nq.gz
│   ├── 15e27edb12ac25701ac0ac21b97b52bb4e45415e.nq.gz
│   ├── 1b3bdad2ceffae91cee61b32f3295f9bbe646e48.nq.gz
│   ├── 1b425ee0f5a566047934d3f1ea1d9868b0508de6.nq.gz
│   ├── 1fa2d11c530b5900f3fdd28b15851a990924a6e0.nq.gz
│   ├── 20b51820d8f2d384afa6f38b6947b9f15074a3e3.nq.gz
│   ├── 20e1b2b05c1ace2b80a2c52ba08f4be7230302c9.nq.gz
│   ├── 2271cde5467a8060df8ac38b64f19873d30d54d8.nq.gz
│   ├── 276cc56ba3f5b5b5b7bb94d8e3881f042025f739.nq.gz
│   ├── 28bbb706cff8179c52375c3a513352181d2e8407.nq.gz
│   ├── 29d0bd9f583ee0f7fdc7d7df6de3e82d4f3b1117.nq.gz
│   ├── 2a940a7da7c14e6a36901e83306849ba7efad4d4.nq.gz
│   ├── 2cfd115fee684197a035b5445e8f87bd952f6b6f.nq.gz
│   ├── 36a9dca03d7e75530f5e8d1652ed0daae58877d9.nq.gz
│   ├── 3aabd4ee4d7496f25dba31d1992fac1c9bf372af.nq.gz
│   ├── 3b4999ebf2ee4d35d8bbe05dc6636c3f64b2dfa8.nq.gz
│   ├── 3fea824f8b77523a42655a169da8fb5913f84fbe.nq.gz
│   ├── 477339013f762124702489003dd62691e2728f78.nq.gz
│   ├── 47a31bc9d657ef5ba89d1889963b30ab32f1ebd5.nq.gz
│   ├── 4ab292b42342426d14d209368b34cd7d87535f1f.nq.gz
│   ├── 4b7dd2a5ac321d8dca7fcecd8e6507f3da934aa8.nq.gz
│   ├── 4c623e99bdd9b00340d2af70075c31c835504efb.nq.gz
│   ├── 4d91bcf57de866a901a89a2a68c0f36af1114841.nq.gz
│   ├── 4eb0351ae7f2be1e0ca8e2faa47ec9ed62260c46.nq.gz
│   ├── 55bc6f61c88b46460d0eb254d3b75890ca2cc180.nq.gz
│   ├── 56be6d8ceef014ecd4a3ca797a132e31fa591b0b.nq.gz
│   ├── 5756c8cad8854722893dc70b9eb4bb0400343a39.nq.gz
│   ├── 5a209bed43bee25587e9ec86409eb69ff7732a69.nq.gz
│   ├── 5aebc43c9021d4a44aee7e87eca024ba7234b229.nq.gz
│   ├── 5df3139b4bb1f5eeda1ccd2e083f95135649c038.nq.gz
│   ├── 61faf8cab23993bd3e1560bff0668bd628642330.nq.gz
│   ├── 627dcfb9b54e3d8191bfc65363fdd899a20b892d.nq.gz
│   ├── 6346313ee8d0ce7a1bafe5fd8ddae2f047e17475.nq.gz
│   ├── 666528d390c4e31b746ebe1f705727fc44cc088c.nq.gz
│   ├── 694f15ed9bc8b602f00ed4f6d0b08a8d4c57a102.nq.gz
│   ├── 6bf34d3bda5156f48ed473d1419c1be1a75941bf.nq.gz
│   ├── 6e71008d07e01a75d07450cedb762e267b8e9ad8.nq.gz
│   ├── 700f61344ffd981b9b0ea47b4e64d932262d2636.nq.gz
│   ├── 714dabe8dcf3f5a8541b3ae022a63aeb72e1221b.nq.gz
│   ├── 72ddb807ceb85fbbed58134e2f5b946b3fb27f78.nq.gz
│   ├── 77f245a6fc54b001da55494becf5deae908ca1ec.nq.gz
│   ├── 786c1baa13ce05064a63c1825416e17e2b687c65.nq.gz
│   ├── 7c137e03951ee98b94c106adb22fae893d56570d.nq.gz
│   ├── 7e9bc15a961ae39759152cb0e499f12277d7c7d5.nq.gz
│   ├── 821816a99a9bbff8fade32870114c016bf3156a4.nq.gz
│   ├── 84318bd50ccb39778ad3602c37ef45478a862ca3.nq.gz
│   ├── 85a93bc5479e39291c6e105d5d80a0a5ca6bef9c.nq.gz
│   ├── 8a246ed987fb768e4d3788acdc8765ee17f4930b.nq.gz
│   ├── 8ef415f32bda81bb986fa2f1da986739e7b83b89.nq.gz
│   ├── 8f02686552ab65ce74f3e0b6d60404df3e3b6852.nq.gz
│   ├── 9427981d68bafc98147764c56182fee63acaa6c8.nq.gz
│   ├── 96b1f8ef38a5e17ef64d97814a154efc180240ad.nq.gz
│   ├── 9c14f0ea3c581b1366b31b85bb2ac428c54a6dea.nq.gz
│   ├── 9e1ec356949dd66f4644efc4986e5962cccf2508.nq.gz
│   ├── a8776737994f97e13ce37b867c555df0f1fd5eb0.nq.gz
│   ├── a8a2bd76abc460e7766cd03691e3f8703cc4c8b0.nq.gz
│   ├── a97e86d66af1ad396be5ece749bfe35b452aefec.nq.gz
│   ├── acee3b68efbbfb9de3bfa73fce2531380f4bd820.nq.gz
│   ├── af640a3bca3ff335af13471ba04b533bcd4156f9.nq.gz
│   ├── b48c32ff911061f69b9dfaec284648b585f3e07f.nq.gz
│   ├── c21de5b5eaec52da46c46675e36f8e0659c274fa.nq.gz
│   ├── c6025eb1e170b9871488d9985adfb29e9c6d4980.nq.gz
│   ├── c725b9d80e1e860c4096e4b969ad3f5b85353321.nq.gz
│   ├── cacbd855df4ffdb1c9acd5dbd22fad2fce51b532.nq.gz
│   ├── cdd1c6062e362df5fb05847a768060cfbccbf854.nq.gz
│   ├── dc5e0b0da67e4a7a68cc96d2b052c8308e62b335.nq.gz
│   ├── dcdd12a384e538fec0c6fc3a602d3f4b6d6e6af7.nq.gz
│   ├── dfbc0cbd512bdeefcb1984c99d8e577efb77f006.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e921a966cb71196095ac30c14af927646c1481e7.nq.gz
│   ├── e95cd82b8dd8b322482a6d73784c2de7c7f9e0e1.nq.gz
│   ├── ea1ec0800a90762d7d6ee058bc413027e8ea2a20.nq.gz
│   ├── ede3745d58d401a1814dd9f5020d48abf8694397.nq.gz
│   ├── edfdc1ca6bbfbaadf7c248f566d441ed378965b0.nq.gz
│   ├── f2adf88d310d3aa560fae70f4d2aa9d2e3a1a3fe.nq.gz
│   ├── f515f220769655c7c1ca76a0aeee3ec68728e5bf.nq.gz
│   ├── f7756d8f22a1fdb678ce2ec06b4aece2c83d4bea.nq.gz
│   ├── fb7b97d9f0186856f2083060610a727ed0a989c4.nq.gz
│   ├── fd9896fbf4e1c3480eb60b6107b26afd61eafda9.nq.gz
│   └── fda6cd29ede1be6168ce8b5e02d099ea9055ccfb.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 25dab08ff48c21a470f4b0658c2a85da17b4ad9b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 95 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[sphinx-doc/sphinxcontrib-websupport](https://github.com/sphinx-doc/sphinxcontrib-websupport)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
