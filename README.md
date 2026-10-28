# Repolex Knowledge Graph of Kozea/passman

RDF knowledge graph data for [Kozea/passman](https://github.com/Kozea/passman), parsed by [repolex](https://repolex.ai).

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
rlex download Kozea/passman
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 565bf2a023d10609f6ed143d9517f4b5a8ddafd9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 565bf2a023d10609f6ed143d9517f4b5a8ddafd9
│           └── chunk-001.nq.gz
├── blob
│   ├── 1062922ce3bd214bf5ef540816ed6e6d94b31db3.nq.gz
│   ├── 13a9a5cf2a7fa371d61a91e72f26d72efe2b6a3c.nq.gz
│   ├── 13e84b70770e9bd1ab9ef55f055358cd38ea7a4e.nq.gz
│   ├── 1f0045b46a40e356676061b19c3b803d9985c8de.nq.gz
│   ├── 27cf97517fda2dd35bcd1fd48c548927b2e7f34d.nq.gz
│   ├── 2c0156303a8df3ffdc9de87765bf801bf6bea4a5.nq.gz
│   ├── 3093490cf3c4bddd627c0b6b224568440785e9b6.nq.gz
│   ├── 32100e410e75f50a61ff96396b51cf05fd437ca5.nq.gz
│   ├── 387d7485963e7fa3b74a7a3d1c500b66ae1388bb.nq.gz
│   ├── 3e666242bdb66d89603eb61611281e8a202232c9.nq.gz
│   ├── 4ad4fd072bf9f22ae4f0d0198f2ea61505c94507.nq.gz
│   ├── 52e82792963ec5c9699113173354fcf560c40a10.nq.gz
│   ├── 5f5ebc9b0182a8b9e407c55139c646e8e903a50c.nq.gz
│   ├── 61d003c1585bd9ce607e4ce67d66d129ec41a4de.nq.gz
│   ├── 6bd2eeb700beac43a503fb40996ba31aebc0f82f.nq.gz
│   ├── 76a83e662e64bbbfbcdf992b3179261cfe3a0909.nq.gz
│   ├── 7c42128c39027f4c0f039ce7e47b665daf566212.nq.gz
│   ├── 89d60276085b7f3c15d9198b338e4356eafcf0d9.nq.gz
│   ├── 8b56e575807f6fe4285b4852010d61e9a38316a8.nq.gz
│   ├── 98e4f9c44effe479ed38c66ba922e7bcc672916f.nq.gz
│   ├── 9932d81cf320ba2fc00fc1ae0bf2db5a370f58db.nq.gz
│   ├── a1e28a5142aac74de5d0c6c601d4056e3558b599.nq.gz
│   ├── a228d2091b8ea08c178bd409661ec666a5284595.nq.gz
│   ├── aa6e70afb2bccda43a4c3958e567dcf5730cc027.nq.gz
│   ├── b1a1e0279cf7418bbce37265fa7cf6c60e3b811d.nq.gz
│   ├── b807a9b1dc600b347515bf305a468935fce3f732.nq.gz
│   ├── bc56c598ca4e5bf11e1bd979aeaba97d849bdc58.nq.gz
│   ├── be8c8d03c78ec07d2b96da237474274983f3932e.nq.gz
│   ├── c351d615dc680a5d5dc61d59d3884df4de885222.nq.gz
│   ├── c8c5f4fd35e7c66c51f9e781a04dda83f82742ce.nq.gz
│   ├── cb30dafed09739bebc5b42fe1c03ed046a060dd4.nq.gz
│   ├── db46d3f2de1fbbcf5c3ee6846cde5a582590be4c.nq.gz
│   ├── de7c861fe839c5a112cccb722c335d1c82103528.nq.gz
│   ├── e068997f99ffa008654ab68d5327798f46a1da5e.nq.gz
│   ├── e3ab0926df4e4a0fb7a968feab575c9eacc5a1a8.nq.gz
│   ├── e4354d89080cf0f2fd371a563f776f5f172e433f.nq.gz
│   ├── e4daae9c9c9f0b059ae6a305858881c6f4eb0228.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7a40db6651aa0e79131c049dd7b5c9e55987eba.nq.gz
│   ├── eaf0661fdb43f1626c00323144979a851ebd04af.nq.gz
│   ├── f3270f2aeb334bdd63d38fe6f903a88d63962b42.nq.gz
│   ├── f5c39675958b04b2500805758e7bc13438056cfc.nq.gz
│   └── f84830bd4803f180e35f3fe5bf71c94db2bf2bc7.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 565bf2a023d10609f6ed143d9517f4b5a8ddafd9.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 51 files
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

[Kozea/passman](https://github.com/Kozea/passman)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
