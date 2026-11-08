# Repolex Knowledge Graph of canonical/sdcore-nms-operator

RDF knowledge graph data for [canonical/sdcore-nms-operator](https://github.com/canonical/sdcore-nms-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/sdcore-nms-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a9099d2d81cde5b2de130bd8f6fdaa87f2a2e0e5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a9099d2d81cde5b2de130bd8f6fdaa87f2a2e0e5
│           └── chunk-001.nq.gz
├── blob
│   ├── 0285be58c2ea2320bfbb96532b23dcb3c2d21035.nq.gz
│   ├── 08fc98c81de89a195dcdfa7f3ab8b057f3975d1f.nq.gz
│   ├── 0b680d508757e960bfc1e7190cc29509514d1562.nq.gz
│   ├── 0ff992b299b3f0224c0a4575fb68ea04de62af99.nq.gz
│   ├── 13af703428e23ce7d56cf7a1bc7061b64a8f6a18.nq.gz
│   ├── 144c297a9a1292c16d3b61eeee6ca79e6dacc85c.nq.gz
│   ├── 1941bd0ace02b80af780e30178f3a640db4a295a.nq.gz
│   ├── 2055a28de90818ffa33b0a2ff4e1fdbd93eb1473.nq.gz
│   ├── 2cc094b354f05ad16d6c8f278e3d89fa62de896c.nq.gz
│   ├── 358b7b9a478651113568082c8ccee4ff4849aa65.nq.gz
│   ├── 3ab012b337a7d5dc40ef21055a0408d823bcf6a5.nq.gz
│   ├── 3bcd8a9f726c1e7ff32172d0ed5d95ab6436a34c.nq.gz
│   ├── 3d1ee82bb15cda2373fa444176e6c8df2667e74d.nq.gz
│   ├── 432f1a406398cb9b8e52de6ce919d2f4e3cf21a4.nq.gz
│   ├── 4550e40993069d60306266e8b1d5cb5cb83ba07b.nq.gz
│   ├── 46fdfb6ff31d8f845aa61ec8d9c441011982757c.nq.gz
│   ├── 4d394c33b8ea132a10ef09db97c9509d10e14fd1.nq.gz
│   ├── 5411236d6b63bc4bd54f36ff39cc6f7912a44507.nq.gz
│   ├── 5baa983a6c37c7c1f04424229cadcec44510410a.nq.gz
│   ├── 5ebce5818229b20aef673e981ea336980db9a233.nq.gz
│   ├── 5faf27527766a80e7aa58926fd010470db11edba.nq.gz
│   ├── 6063f72f417271a6cba967b4e767ccd955d209b3.nq.gz
│   ├── 65d3e5b3bc02bc530cd144b6b740e2ffd00fd426.nq.gz
│   ├── 6c9be400a34577b14bc62b0a9ceb6e10133235a2.nq.gz
│   ├── 6f84f81c2f19782e260b1dc914381e9690236c74.nq.gz
│   ├── 7538ef05e4086044948d4e76270d7405933ea3e9.nq.gz
│   ├── 7bbbdf45bed96dd74d8c9566653b60262bd9277d.nq.gz
│   ├── 7c248863f67903e028c4b315cda2ba583ca47cf1.nq.gz
│   ├── 8063d088600079d1ba46081a628065632082f463.nq.gz
│   ├── 8d771e187ba4b2ced1b643c804548e5c014bab70.nq.gz
│   ├── 969fdf64049c08e6fb3a25472c78b46435794d5e.nq.gz
│   ├── 9c99462ea2c4601f706c3a1bfc72d0749c50885a.nq.gz
│   ├── 9ca56a8830a92c94a3be6a6aeb3dfe77d9cd869b.nq.gz
│   ├── a314dc6123caf20744c34655f8d71871acd6e676.nq.gz
│   ├── a42913efc34f8cfb93f463fbfdc9dc5da3bc7de6.nq.gz
│   ├── a81c4625c094f11963e67c498ab3809ecb84c1f2.nq.gz
│   ├── b06b27293ed3ba881095d7c9001a689953e51f89.nq.gz
│   ├── b47aa0959e46a7d583ffb9917b672bbf5891583b.nq.gz
│   ├── b675045340b57621e8a8acd7eb674545f0d27f66.nq.gz
│   ├── b702be99c78f9e2d3d4348a9cb4090d848eedb94.nq.gz
│   ├── bbe77cb69558e274639017d0079c3ebd6bc948a5.nq.gz
│   ├── bd86319882cbb278da4f306b71d2fe18cb08adb6.nq.gz
│   ├── c0916584740515da722515cba9aceb1c01577da1.nq.gz
│   ├── ce00d86dcb2dfacf7f22041e14347f146331d689.nq.gz
│   ├── cefa45bef9d361d130ef72a910788bb89b0990bd.nq.gz
│   ├── cf77cc99a548a477b8cebaaff7b21b29a547897f.nq.gz
│   ├── d242377efcdfd5427de179302d2ac6fa073dfd52.nq.gz
│   ├── d54e174965cd46628cb383227260a3687f776d53.nq.gz
│   ├── d557ec668f3172e1c7d12435a5f6429a52d09f90.nq.gz
│   ├── e28f840b24edc0c918f7f06d004f23a07ad80abf.nq.gz
│   ├── e2e3c2227797837db8bb8e0b6cf695afdee2fec7.nq.gz
│   ├── e562eb624ef043abf6a27b84241b93e3d4645296.nq.gz
│   ├── e5827dbf157425cfb9f028f2b5c7ba7c53fea718.nq.gz
│   ├── ece834ebefaac7d3e5063a5fbcd9aac9ec68b067.nq.gz
│   ├── ed67d9f62e5efc1621f0c0e8ae8ee293fdde7856.nq.gz
│   └── f0571dc2b05049fc3780efcdffbafae38febe7a8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a9099d2d81cde5b2de130bd8f6fdaa87f2a2e0e5.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 64 files
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

[canonical/sdcore-nms-operator](https://github.com/canonical/sdcore-nms-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
