# Repolex Knowledge Graph of samuelcolvin/aiohttp-devtools

RDF knowledge graph data for [samuelcolvin/aiohttp-devtools](https://github.com/samuelcolvin/aiohttp-devtools), parsed by [repolex](https://repolex.ai).

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
rlex download samuelcolvin/aiohttp-devtools
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5a5d4222c3fce01fea62a543d720d395ba96490b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5a5d4222c3fce01fea62a543d720d395ba96490b
│           └── chunk-001.nq.gz
├── blob
│   ├── 01981e9c9751a24f10f5605fa43288fdf3b5fbb4.nq.gz
│   ├── 09652d648b320ef22fb9bcc57cb3ed6cc3a1dbe6.nq.gz
│   ├── 0f7911bd99b687835845f73379653903ccc53f82.nq.gz
│   ├── 2447e0008ff703efb40f117672d9d38d27ef4e98.nq.gz
│   ├── 2c53e6e21e2af8314ea1ec8cf28fd1e9296abbe4.nq.gz
│   ├── 3087d528d111b2e122a86805049da5c8840a64a0.nq.gz
│   ├── 36979982708b367032730848375b2a457cf360b8.nq.gz
│   ├── 398ff08afa472330844404ccef1b7d49fcc17c5e.nq.gz
│   ├── 3a65d4dd8df2d2adf959f01709e8959ad2a7464a.nq.gz
│   ├── 414695c0dc35beebadbc8c67ddadfe4fd8ba60d0.nq.gz
│   ├── 4827ed574969fa9a070e08a8c15c3f3411c559bf.nq.gz
│   ├── 4bd9edbc8f67e10a23cfe0cccfb3f860dc4135d4.nq.gz
│   ├── 4f7bbfeb36b331da22d754567c522f077efdf405.nq.gz
│   ├── 53569f5b81675ecf4056cc414f5f7da29545c66d.nq.gz
│   ├── 72f26f596b0e59eb0fc2421f6ead617c6171fc9e.nq.gz
│   ├── 746f60c234500754150724b333264b3e67206afc.nq.gz
│   ├── 76cbddb754229e5921ed2f682fc385a49496baca.nq.gz
│   ├── 79e265cf2f93dbc3e892781a28da5ba529298589.nq.gz
│   ├── 818a6cfd2154a22a7875ed5f1a59842fa7394136.nq.gz
│   ├── 9a279892ce65983cf9aa6f771bb630244a9718a7.nq.gz
│   ├── a1b9bad453e987438216e5f5821c1390f9e9c127.nq.gz
│   ├── a22afa0e6190b3704b3a7615a1d504a99f19cc4e.nq.gz
│   ├── a378a764300460c794601c1f9d33fb4bd6488bc1.nq.gz
│   ├── a7a852c5bac8b55200f317b6ff5ddb4742df4634.nq.gz
│   ├── aa4e387807f95ffbe4105c0b82075ff47dda39f8.nq.gz
│   ├── ad3e9a25ccceb542d36db0ee09f1c9881529f07a.nq.gz
│   ├── b0d113515bc3a0fe6707b05f9f159a4305f7667f.nq.gz
│   ├── b83687f9c3d3cbf800f691053e05b1efde82f481.nq.gz
│   ├── b9fb8a6e0f4a5ce99899eb97d872c6b90f4bb678.nq.gz
│   ├── bbc40ff10552764dc45e3773c158c3ea8986c009.nq.gz
│   ├── c03671b8bb96017d28f82724ae3709ddd30a2eb2.nq.gz
│   ├── c1943d9765c4224514e6b36ab4aef02631320006.nq.gz
│   ├── ca009160a1083cc8b49d048d53165956b36529f4.nq.gz
│   ├── cac4bc813f46e6f46c43710a2c94fae360fa6e97.nq.gz
│   ├── cbde5014140498b40f29b9c975629d82aee60458.nq.gz
│   ├── d370775b7d434098a96af13db64d23afb06db9b6.nq.gz
│   ├── d396c2a7cb4a9c69d07b596337b1fffb249c0191.nq.gz
│   ├── d67a95c9f9e8d785188b8494fee1b1e49a359ce1.nq.gz
│   ├── e2b56fb3db8d5f6f8a11a0d114ed2104e5c6864a.nq.gz
│   ├── e4a12a1c20b2947b2c30ce5895e5612c24221da2.nq.gz
│   ├── e577ed31a848b46b30045a03d8de9a2ddaa6988b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eb2ecadafc5820ded4c136f5fdf7d50ff6cbf1ec.nq.gz
│   ├── ec2650439a3ce47410225902b1142c6d9d6441d4.nq.gz
│   ├── f3ae03c2f6af6218759e4cc64289b081d22a7b91.nq.gz
│   ├── f4255586d891fd175f87ab4994a2b70fee69f737.nq.gz
│   └── fe952fbc749c1adf970967a0ac262091bfb72c67.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5a5d4222c3fce01fea62a543d720d395ba96490b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 55 files
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

[samuelcolvin/aiohttp-devtools](https://github.com/samuelcolvin/aiohttp-devtools)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
