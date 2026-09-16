# Repolex Knowledge Graph of pallets-eco/croniter

RDF knowledge graph data for [pallets-eco/croniter](https://github.com/pallets-eco/croniter), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download pallets-eco/croniter
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f453fa2ec934b3b8876f71c28eea213b96f7a46d
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── f453fa2ec934b3b8876f71c28eea213b96f7a46d.nq.gz
│   └── repolex
│       └── f453fa2ec934b3b8876f71c28eea213b96f7a46d
│           └── chunk-001.nq.gz
├── blob
│   ├── 0295f8dab4eec985c1ee75ecd06909a3d6776fcb.nq.gz
│   ├── 02f1e99c1b53041bbd621bfd43bc68586076212a.nq.gz
│   ├── 030a5e9ea10dc14d649a6802fc4a6b5cfca99313.nq.gz
│   ├── 09df199ef04cfd7b9a32a2fc88faa666f5c38c83.nq.gz
│   ├── 2608aafe3f01b3569d29e2a19e1765c807cf47df.nq.gz
│   ├── 3c29b717777d9641c65e05350be3ef1dcaf6df66.nq.gz
│   ├── 3ebc806be6be053f593463d6add8bcc528d56572.nq.gz
│   ├── 41460fc59c92f5aa8df0d0f2fb2d564129f78ea8.nq.gz
│   ├── 4e2cb5bab80261918950ef17a884cec82b429e57.nq.gz
│   ├── 4f0fa62525a05a63fa9f08800302a82e623f7f98.nq.gz
│   ├── 52e41dcde7cf58b52d1b3838e615bb730e536ccb.nq.gz
│   ├── 5de7c24809ae3ac1ae2bf1b2b10e69de191eb62f.nq.gz
│   ├── 657cc210b651adc0e9a7b436e4ac649216752ca6.nq.gz
│   ├── 821e63309c0823d05a1fe04d0f62dc9c9831970f.nq.gz
│   ├── 872fdb93af94ef51cce62160ef8e082bf2050307.nq.gz
│   ├── 91bb9c999bdd4196fe1d77e8ada78b865b35bd14.nq.gz
│   ├── 96172f1e9d45f678262bab05357c1302aeb1342b.nq.gz
│   ├── 9e0abec32e9d2ba8ba024b7d80f7f5c52f5b523c.nq.gz
│   ├── abef7b2ea1ba5198a9e9008f78dfc4cf08edc558.nq.gz
│   ├── accc9e98973d8f54b102b73e7863440d73df535b.nq.gz
│   ├── bdf40d44faef44e5a957c64d97b1d5a7856c1064.nq.gz
│   ├── bfd3b82c099f07123cfbd6f68d52558b6e2176d0.nq.gz
│   ├── c3085d890eeb62be8ec1e9843722449c8d29d6d4.nq.gz
│   ├── c78582c48cd36e9ba8d94debf7e62983ced8a193.nq.gz
│   ├── cbd920f6b3ba719f191d20703765bdeef260b138.nq.gz
│   ├── d89630a20bb71d3bf0313a0dccbf3a436e8003fe.nq.gz
│   ├── e5a5152322d37620eeb1c4d7cd4ea11bb69f9cea.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ed6bc065d45abd2ae0b43e8af5fbef211463005d.nq.gz
│   ├── f78f2a09e64d851044b1537cd5b19d481331154a.nq.gz
│   ├── f8646c4b2d60152766637428a38e934bcc0cf847.nq.gz
│   └── faecd1f60abd138ff9288bbdb47f3df92889b3b9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── f453fa2ec934b3b8876f71c28eea213b96f7a46d.nq.gz
├── filetree
│   └── f453fa2ec934b3b8876f71c28eea213b96f7a46d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 42 files
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

## Source repository

[pallets-eco/croniter](https://github.com/pallets-eco/croniter)

---
*Parsed on 2026-09-16 by [repolex](https://repolex.ai)*
