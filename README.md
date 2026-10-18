# Repolex Knowledge Graph of dbcli/vcli

RDF knowledge graph data for [dbcli/vcli](https://github.com/dbcli/vcli), parsed by [repolex](https://repolex.ai).

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
rlex download dbcli/vcli
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1e8b34141a3223d157c661f70f8beb4649b4d37b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1e8b34141a3223d157c661f70f8beb4649b4d37b
│           └── chunk-001.nq.gz
├── blob
│   ├── 01faa7cd6c8928ea2ebe561b1a024ec1b2bd66bb.nq.gz
│   ├── 0313520fed7f6829502f51f6bc2a2dbac8a0c2c9.nq.gz
│   ├── 09df2f2443e35014ef216c2568abb724f197c599.nq.gz
│   ├── 0dec23d820545480236b921655c41b8997a437d9.nq.gz
│   ├── 0ffff6bf3255815fe1a6c23278aec6d47c51b40c.nq.gz
│   ├── 1013eb4f73eb4b376b41f8e35094f1b8de9a1e9d.nq.gz
│   ├── 10939f01be01b705d43126b5a824a2017c2c46a5.nq.gz
│   ├── 109fa2f424b290d058b64116c016132d43ca4623.nq.gz
│   ├── 187f0d9d3a897866a9c439f9b5317bb86e69351f.nq.gz
│   ├── 18a84731bea9b4453a1884342c15e6bda89b370d.nq.gz
│   ├── 18ffcd83220f4c1aa9fb4a1d8ec610c703106960.nq.gz
│   ├── 21735457b4af3a774208a14b1f8c9cdf5438f38b.nq.gz
│   ├── 24317bfb31f501cc7c137b26140b689a0d70f9b1.nq.gz
│   ├── 29564d08e2097084695be52dde6dbda97320f2d7.nq.gz
│   ├── 2e4dc09ec89a8b20427437a090bc41ecc32ea862.nq.gz
│   ├── 34c3d46e0acd5f68cca029de1b970619eaae5b7b.nq.gz
│   ├── 3543d85e31ca90b7ec1a0b1d304a58d369a8ecd0.nq.gz
│   ├── 40211d14d5ac7be4fe31d76c7a5a5bbfe3b38d66.nq.gz
│   ├── 43e90838beaaf7b45a437fd8f07e8e4262b9d22a.nq.gz
│   ├── 4df77a317b86acc1e21e5025c34c1e4c4d5effe2.nq.gz
│   ├── 4ee2aa1a864aa0f83d649eee08256fb5b5474177.nq.gz
│   ├── 50657e5c5bb8b479cdaf3bb4912bd1317beed4ba.nq.gz
│   ├── 51d40c38cd6b4ec74557d5c36e991a94d2f91221.nq.gz
│   ├── 5693ae851b83141b84c3ad134a41f003c29cf44e.nq.gz
│   ├── 58dd57069ec2cdc93236ed3585d7145a843da241.nq.gz
│   ├── 5dbc3bf7eb1d158fa93d05beb6cc5abf95a917d7.nq.gz
│   ├── 65c4628a3b6fa135e8c11dd78f918835d8aa5ec8.nq.gz
│   ├── 6ca831486234c3dcaa09427c6642c3e07302014e.nq.gz
│   ├── 6f5ff21a4856e0ecb4a823a0bab45bcc5a1c68bc.nq.gz
│   ├── 7242b5060de134c3e4b7cd41fa10843d7c2e4cdb.nq.gz
│   ├── 72f254db61f77778d89def219393d027d8d08816.nq.gz
│   ├── 75e1e8bf9dbb44cf936005ba532204304533e6ae.nq.gz
│   ├── 7e427fc6f26ae72195b712d439aa2f17899f6a70.nq.gz
│   ├── 826ab49d2cb761af926022d1fe4842d1eeba5bb7.nq.gz
│   ├── 889efad53da66ea4b0ffc0cf9b575dad5418e15b.nq.gz
│   ├── 898e0092034830bf0d0c013f2c0207ff18c63150.nq.gz
│   ├── 8ae827736aeed22f2368ae7200810c237e083f96.nq.gz
│   ├── 8aed030757896eb599e31cc03c22fda6c0dcd54c.nq.gz
│   ├── 917baeb32756a6d67360a3e2728dbf3e293a5d93.nq.gz
│   ├── 92bcca6da001cf40d432a02a839aaa54fb05b933.nq.gz
│   ├── 9648d8870ec8c02a05a839c36b73c0634d8938c4.nq.gz
│   ├── 9725f0d00624d48790203cc7eb0cade35bd0da67.nq.gz
│   ├── 99854e65b691347c2aee48a18936bd8131964bf5.nq.gz
│   ├── 9da02e2a9b9c0febd9f6be323343bc0313e75595.nq.gz
│   ├── 9ec3c0ade4bed8bcec5c0d421a177920c2788478.nq.gz
│   ├── 9f3917faa2dde4c3fc40063a442495a21db535b2.nq.gz
│   ├── a6ec4d2aef6fda28f2d73888be5b1e680ff89ff6.nq.gz
│   ├── ab8f2a53136ff4f4b384f1e8283127f0279ddb6f.nq.gz
│   ├── aeb99488ac39ee4eb374f64314dbcee18bb12277.nq.gz
│   ├── af0cfd7aad5e4b9aab9dc91e6a3d8b8b3c5cd197.nq.gz
│   ├── bdf396e26ff964dd4a533847b44a677e50059657.nq.gz
│   ├── bfa8203677b13c006f39d452449ab111d97a5482.nq.gz
│   ├── d0462110132d82b6d328e5f581471ebdf4874e39.nq.gz
│   ├── d1b6174a7574a0fd1f8812702d05189cb7543a0c.nq.gz
│   ├── d516a3f6eb6ff223fa83227335dcab9769893e21.nq.gz
│   ├── d63ab1bbb97fe5cb8aa49e39351b4316363a13d4.nq.gz
│   ├── d8a48985c760eb05489042e34bbf3c0a58a069d4.nq.gz
│   ├── da70db52946afeb6f0850550d2fbcddc652f449e.nq.gz
│   ├── dc64c80d7bf98bb1cdc8dc270734fa9575c2db4e.nq.gz
│   ├── deb499a4edb4bcbd7e1701c11528dbef47e1040e.nq.gz
│   ├── dfbf35ce1d20960ef60c614c2194ecba79c9e3fe.nq.gz
│   ├── e0710bf631d9804d22e254129884d2d91d5e01d4.nq.gz
│   ├── e417892dc787e353c56727cdf0993a83249bbbb9.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7f1f66c1a5346abbdce265a02bb0d5fcb470f55.nq.gz
│   ├── ea25a915b2d7b2603bce619a4119c6f598bc300e.nq.gz
│   ├── f2a123d618d59655afda074e387560d58330bde9.nq.gz
│   ├── f78774051e8b3a2199ef6c9dffd8786ce160d98c.nq.gz
│   ├── f7ab168070af4072b9c6dab32ec2f473adc5981f.nq.gz
│   ├── f7f2c1288ab6eb0e9ac1769873031876f4221920.nq.gz
│   ├── f994ba5435e610104ff713f2379e11d1a47059bc.nq.gz
│   ├── fc37814cc064b5bae46026e519a08603e6c1c9df.nq.gz
│   ├── fd9dfad0984d0ccf12e087dfb85b76658bc780d4.nq.gz
│   └── fe17fcc1f40f997b2e5688581b1e811aa37a8e44.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1e8b34141a3223d157c661f70f8beb4649b4d37b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 82 files
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

[dbcli/vcli](https://github.com/dbcli/vcli)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
