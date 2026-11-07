# Repolex Knowledge Graph of allenai/maniflow-tb

RDF knowledge graph data for [allenai/maniflow-tb](https://github.com/allenai/maniflow-tb), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/maniflow-tb
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c04eab7fd7ee3b5e5240baac8808eb90f4d491b2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c04eab7fd7ee3b5e5240baac8808eb90f4d491b2
│           └── chunk-001.nq.gz
├── blob
│   ├── 0b32d52b4aec38ad4a25b07bfde562f92cbbbdff.nq.gz
│   ├── 0dfe02ad0c193e54450e8461e77b2b2e8e5787ba.nq.gz
│   ├── 0f19a6eb7d28e6c6c0d3a6f64c01d2630579dd0c.nq.gz
│   ├── 0f2f24ea0a08c789c03460d77811b98f666faefd.nq.gz
│   ├── 1118b2d43ff27907d31a802cf4c54fe17738f0ab.nq.gz
│   ├── 134d81a956bd9de3e11b793cb03c3025f3677b45.nq.gz
│   ├── 14309bb4610c6632c776ad4db46658bdd812762d.nq.gz
│   ├── 19efeb9bf751fd23460e7ddc05ccf52464023624.nq.gz
│   ├── 2af9d6b6a2f8a8d6bad5c05343d6bfba4c757cd3.nq.gz
│   ├── 2b8432fb7989c3765ca4809595b4145255ec595e.nq.gz
│   ├── 2e04a7522d3c8c0d452d3b1c30fc5dde3d4d97cb.nq.gz
│   ├── 3b39eea0816a0cc6f9019dd5455b7a83190f73ed.nq.gz
│   ├── 3c868ea1009c77bc099a55e6b6146925b33bb06b.nq.gz
│   ├── 3e0568cbda5c6eebee969eacc3476931e1a2d2d5.nq.gz
│   ├── 4645b25dc3c8456df1d160ccc6e0770c543543bc.nq.gz
│   ├── 51472161913c16d84967931d8a74db44cf4c28e9.nq.gz
│   ├── 5371610c39d43675a7188aab9c6657b06eba00ea.nq.gz
│   ├── 57bc88a15a0ee8266c259b2667e64608d3f7e292.nq.gz
│   ├── 62f322b183cffe0badfb81eb3807e1236a3fc52c.nq.gz
│   ├── 63e03781577d9b6119b25dd2fa6a3e212d5598d1.nq.gz
│   ├── 64586e1b90d1d3000e108ab263f379c5c520ddf7.nq.gz
│   ├── 6897a047fc2741f7e434bcdaa78f6a14c473fec9.nq.gz
│   ├── 6b13fb08a62b4adcbd2ec69eda79f0fc5a1c9b1a.nq.gz
│   ├── 6cf435caf7d11707f70006fe514f3f1a0a2c6981.nq.gz
│   ├── 7640258966108fe270fb4394deb97d6d6383d540.nq.gz
│   ├── 78bc0a15c617d462cc6c126709035c786bb24a56.nq.gz
│   ├── 79004f4508790cfc2f0ea54cc3415ba3f38f5342.nq.gz
│   ├── 7cee5129f096dae2a5106973f9ba37f2bb0968dd.nq.gz
│   ├── 7f38be3c92f719cee493c189aa8f6918d4fd3376.nq.gz
│   ├── 8075fa861605e8857831461c12ec8bc14744a722.nq.gz
│   ├── 85a5dca02a555d54f6ec8fa58068bbe7fd91d503.nq.gz
│   ├── 87f52b9c53d654b19ab1ca744a0e9d15b5fd36a6.nq.gz
│   ├── 88491d591cca592a45cc56d0b9c98e22c2a5c6ea.nq.gz
│   ├── 899a6ee2b957a6af13ff13d60f0f6029d5968d7c.nq.gz
│   ├── 8d2c7b09e937b8fb0ff842143b837049c8212d4a.nq.gz
│   ├── ab1b85fb08dff5a331d6981ad7fb12f55d2eb1cd.nq.gz
│   ├── ab4da85174dcc7da97bc27264858965628773296.nq.gz
│   ├── ad1d9a35e7f4a83df005170fc619699940b46891.nq.gz
│   ├── adaf21229823f1eccf3f9d233b34d4693b048d15.nq.gz
│   ├── b0e67c94d9de5131bb5a30facff46d0cd193fee9.nq.gz
│   ├── b2221c24ed09951fc52b7515a3c7368ccc1c37c7.nq.gz
│   ├── b59ff2569d124c771472a11569da3213274a670f.nq.gz
│   ├── b66cc0960132e19c0f1f5e648802a618b6fd00f9.nq.gz
│   ├── c690f7ba14e9b6ec5f5bfaab310abaf867505b96.nq.gz
│   ├── c975df989f953a11c6d72d623436644d1584cd5f.nq.gz
│   ├── cdebaac6bebf5bb22aa2f573f4de4851ddcff313.nq.gz
│   ├── d990044504b7ef3996b8cae2552d295ac968ed16.nq.gz
│   ├── dd9167e401df8880052bf77582d91148d25783b5.nq.gz
│   ├── e11a8f0f0d43b51cb3ccdc8d90d365815d4fdccf.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8a41d7355f8baed470157cb9b9048282d76d76f.nq.gz
│   ├── f4d909734d712836393d451c4740a989782adba0.nq.gz
│   └── f8f35355778234c1e45da041c5bc8369dde10033.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c04eab7fd7ee3b5e5240baac8808eb90f4d491b2.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 60 files
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

[allenai/maniflow-tb](https://github.com/allenai/maniflow-tb)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
