# Repolex Knowledge Graph of anysphere/watcher

RDF knowledge graph data for [anysphere/watcher](https://github.com/anysphere/watcher), parsed by [repolex](https://repolex.ai).

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
rlex download anysphere/watcher
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 99cf43b739b25bbd3538506dbc4e87a202f7af84
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 99cf43b739b25bbd3538506dbc4e87a202f7af84.nq.gz
│   └── repolex
│       └── 99cf43b739b25bbd3538506dbc4e87a202f7af84
│           └── chunk-001.nq.gz
├── blob
│   ├── 0292341d7e2fcfa3a890ce03ce12208947006ba6.nq.gz
│   ├── 07ce9b58812b177f4bdf3d29291f202ff8791a46.nq.gz
│   ├── 0cccee79b250b59c890290841cbdb99f3eb02de4.nq.gz
│   ├── 0e9b84f0aaf00328289286f8a0d405174073875d.nq.gz
│   ├── 149fa6d7b24c85ccb9d84a3c5485b0f298f74683.nq.gz
│   ├── 1f0b26f62a818e763d4501584738dbdadc847d59.nq.gz
│   ├── 1fbcd45bf47b41749f66033657b69cdb0ff6a0c8.nq.gz
│   ├── 23134934ea03dbeb36baf22bcf9d64dcedf14d94.nq.gz
│   ├── 328f469965d3bc248c99e8a50752c549c631e20a.nq.gz
│   ├── 3c6a9cdd5c1de26b0eb5c5f2835409098fb601ae.nq.gz
│   ├── 3d36a5b67414038492d7937c87b21a87ef783f6d.nq.gz
│   ├── 496d56bc1c448895543933156e991831421834a6.nq.gz
│   ├── 4bda1ff6f931bc2a0411556471c8e2672a59b71c.nq.gz
│   ├── 4ca3bb66cb0970f09dff7c595818234f2157efa6.nq.gz
│   ├── 4e3ced08a03f0407a0341d72d222e81ac1764078.nq.gz
│   ├── 57ded666b3ffde3ad86994bdd45d14eab04bd2a7.nq.gz
│   ├── 58b44e9cefaa66cce75378a9694341b7f1a7e653.nq.gz
│   ├── 5b352ad645728d47e3947662ce793c5ff615da63.nq.gz
│   ├── 60490c637c4cabfc2825ec3ec970d9eab53252e7.nq.gz
│   ├── 60e4d65763ffdd50ff8b8c0bdcf657f53c2e3ca5.nq.gz
│   ├── 629dfdf6f545c7ce181b998ba3946130db8cbedf.nq.gz
│   ├── 699cded9c82ea9cef9330f6e666781537f3c88c7.nq.gz
│   ├── 6bd202542bd570d4563f4469a7bf21faa12ef4e5.nq.gz
│   ├── 6e049e6c627ca8f701b9ee43ef920fe2f6da0532.nq.gz
│   ├── 6e852c8d08fe30a73fb5741538226a82433cbc65.nq.gz
│   ├── 70c7abe311c6441ebdbae13f01a3bc7c9c5f6896.nq.gz
│   ├── 7fb9bc953e90740cb60a6401b25dc36d5a19cdfd.nq.gz
│   ├── 82a23f52fd7b12b743ce14901c974b9c3ad771ab.nq.gz
│   ├── 8afb2b1126dcc687b7ff9b631589da252c1f9c22.nq.gz
│   ├── 903ed43d66e2270b27495daaffdda29d06fb7c7e.nq.gz
│   ├── 92d4379a707c233a3d0a69df7e9ba44acb059575.nq.gz
│   ├── 9514109cf25f1f534759699bf52def8a111576d1.nq.gz
│   ├── 986690ffb2aa26f1b8becea87f097c82e52a18d3.nq.gz
│   ├── 9facac855069d61fe5f2cd2420472c668cc38e51.nq.gz
│   ├── a17fdef7b8c9611bc0b5a6c71268af1d0a5cbe3d.nq.gz
│   ├── a1df48735fd2df1609e425210134a54fc3d9bcc2.nq.gz
│   ├── a4a1722495a90eda1736eb07e876091cda4ec140.nq.gz
│   ├── abb7ae6e289d085d4806f4dd98c1aa963dce4e73.nq.gz
│   ├── ac17c15c4a7a91f5452852992e5f987d032e24a1.nq.gz
│   ├── b9f3a40b6d2d0ae4a703eccf29afc3cad0f8f92e.nq.gz
│   ├── bbcf9cfbe3a892a82559168b532c8aa4a607b5fd.nq.gz
│   ├── be07e782845b072fc632d8e7e663362fbb028876.nq.gz
│   ├── be4821e6c35edecb0c65aae471060dc1a327b9a3.nq.gz
│   ├── c478ca37ac159c5d7b5c61609966b779bbb9180a.nq.gz
│   ├── d212b9321bb8d9220ad07a1cf70bedcbdcf81e43.nq.gz
│   ├── d50c3e4931eb29a408ea29c1394a3fc977349455.nq.gz
│   ├── d673bd1a19a7f6115245a8223bf3b15462ed1de2.nq.gz
│   ├── d679782827a18745bd562aae85ab44e671673fda.nq.gz
│   ├── d75da93d70619fd9123ad852c8c2a3dc033b2616.nq.gz
│   ├── dbc9fb3dc6d180e7f7891d868db94fe974b74fac.nq.gz
│   ├── dcea917c2eb0f3de2c84c33a7278fd1c1238ce96.nq.gz
│   ├── de7a73d1e9549300408fbb56dec837720eed80d1.nq.gz
│   ├── e201942ca65b8339ab9fc97beedb5abdee0f3d6f.nq.gz
│   ├── e577319d4f88d895f0040871efeb32c522520012.nq.gz
│   ├── eabce1e06dcb7e50ff01024d0b90fd6cea5ff113.nq.gz
│   ├── ec926915ff3e5ccd117ab6c349a228a80c16576d.nq.gz
│   ├── ed3a55a7a895c2df724d1072451e7d6f241fb32c.nq.gz
│   ├── f34cd1f00702a70c21b3c7fe8362b3acc258d206.nq.gz
│   ├── f886bde8f395fb771e0f31d9f45a498f9595ecae.nq.gz
│   ├── f89e9f5dca4531b5c7cdf524252973dc2c568d6a.nq.gz
│   ├── fcf5544652e910549a85cbde221ed132c33f151e.nq.gz
│   └── fd403942f6b54652fdabb93ab6a1ac88c14f158a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 99cf43b739b25bbd3538506dbc4e87a202f7af84.nq.gz
├── filetree
│   └── 99cf43b739b25bbd3538506dbc4e87a202f7af84.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 71 files
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

[anysphere/watcher](https://github.com/anysphere/watcher)

---
*Parsed on 2026-09-30 by [repolex](https://repolex.ai)*
