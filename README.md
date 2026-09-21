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
│   │   ├── 12d25c21cd819a08a4777b7646e16cc604be0405
│   │   │   └── chunk-001.nq.gz
│   │   ├── 39b4375f1b5f332ca1166945fcc0c8bd1ec32a7f
│   │   │   └── chunk-001.nq.gz
│   │   ├── 61cc6eb2b2c493c0744af546dbe4d3b6cc4dbdc1
│   │   │   └── chunk-001.nq.gz
│   │   ├── 7672466c8c78a20a6876cdeb1bbeecd4d6e0c9e3
│   │   │   └── chunk-001.nq.gz
│   │   ├── 8f273c6986f63c0bff4be100d5db8738e57a6507
│   │   │   └── chunk-001.nq.gz
│   │   ├── c37bfb92fff9626d8b960106416eec99c537f6b7
│   │   │   └── chunk-001.nq.gz
│   │   ├── da473d9e6dd6b8ca12a6b73715f84d155c3bd705
│   │   │   └── chunk-001.nq.gz
│   │   └── f453fa2ec934b3b8876f71c28eea213b96f7a46d
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 12d25c21cd819a08a4777b7646e16cc604be0405.nq.gz
│   │   ├── 39b4375f1b5f332ca1166945fcc0c8bd1ec32a7f.nq.gz
│   │   ├── 61cc6eb2b2c493c0744af546dbe4d3b6cc4dbdc1.nq.gz
│   │   ├── 7672466c8c78a20a6876cdeb1bbeecd4d6e0c9e3.nq.gz
│   │   ├── 8f273c6986f63c0bff4be100d5db8738e57a6507.nq.gz
│   │   ├── c37bfb92fff9626d8b960106416eec99c537f6b7.nq.gz
│   │   ├── da473d9e6dd6b8ca12a6b73715f84d155c3bd705.nq.gz
│   │   └── f453fa2ec934b3b8876f71c28eea213b96f7a46d.nq.gz
│   └── repolex
│       ├── 12d25c21cd819a08a4777b7646e16cc604be0405
│       │   └── chunk-001.nq.gz
│       ├── 39b4375f1b5f332ca1166945fcc0c8bd1ec32a7f
│       │   └── chunk-001.nq.gz
│       ├── 61cc6eb2b2c493c0744af546dbe4d3b6cc4dbdc1
│       │   └── chunk-001.nq.gz
│       ├── 7672466c8c78a20a6876cdeb1bbeecd4d6e0c9e3
│       │   └── chunk-001.nq.gz
│       ├── 8f273c6986f63c0bff4be100d5db8738e57a6507
│       │   └── chunk-001.nq.gz
│       ├── c37bfb92fff9626d8b960106416eec99c537f6b7
│       │   └── chunk-001.nq.gz
│       ├── da473d9e6dd6b8ca12a6b73715f84d155c3bd705
│       │   └── chunk-001.nq.gz
│       └── f453fa2ec934b3b8876f71c28eea213b96f7a46d
│           └── chunk-001.nq.gz
├── blob
│   ├── 025fbaf832d56323b6daf0406310f294bb229dd0.nq.gz
│   ├── 0295f8dab4eec985c1ee75ecd06909a3d6776fcb.nq.gz
│   ├── 02f1e99c1b53041bbd621bfd43bc68586076212a.nq.gz
│   ├── 030a5e9ea10dc14d649a6802fc4a6b5cfca99313.nq.gz
│   ├── 09df199ef04cfd7b9a32a2fc88faa666f5c38c83.nq.gz
│   ├── 111cfe11ee421ea3dd189bbbc5fabb4c39462ff3.nq.gz
│   ├── 1174d5979c1802d5c12193ba3c6999346c7b7ea7.nq.gz
│   ├── 13fbce7cdf1d4d25e6d832a16c82d50b9db6cc8a.nq.gz
│   ├── 1a371ed66297c5cf76f3f363f936dd914fbca1ee.nq.gz
│   ├── 22fd6a9f5eb50e9886cd9b587143349f41f1c8c7.nq.gz
│   ├── 2608aafe3f01b3569d29e2a19e1765c807cf47df.nq.gz
│   ├── 2616fa3580b1b1b9e735b72fc91c67de28129d88.nq.gz
│   ├── 26e4776175666e8c161e52c1b2ec03dfd8f25df9.nq.gz
│   ├── 328ab5aa98a4468e60a34b5c02c35ca433a4aa45.nq.gz
│   ├── 3732790887334602101e1912bf753077126542ea.nq.gz
│   ├── 39304807fbc7bd47cb8a72ff873c076b694e4fbe.nq.gz
│   ├── 3c29b717777d9641c65e05350be3ef1dcaf6df66.nq.gz
│   ├── 3e78762b13f7c5fcd4737dff36b72832b2405240.nq.gz
│   ├── 3ebc806be6be053f593463d6add8bcc528d56572.nq.gz
│   ├── 4049fb36fa69fdf7b705f563aafb2d31604d0eec.nq.gz
│   ├── 40db86151fda87a658aeab0f3826e485f34acd01.nq.gz
│   ├── 41460fc59c92f5aa8df0d0f2fb2d564129f78ea8.nq.gz
│   ├── 476470a3766e1d2cdc70b91b9e8d03122debe694.nq.gz
│   ├── 47f6a102e8186c9a6f64e6f4d2ccc39a74fac3b7.nq.gz
│   ├── 4e2cb5bab80261918950ef17a884cec82b429e57.nq.gz
│   ├── 4f0fa62525a05a63fa9f08800302a82e623f7f98.nq.gz
│   ├── 52e41dcde7cf58b52d1b3838e615bb730e536ccb.nq.gz
│   ├── 53368db4946c30daa62bf6593b9ef691a934b0a8.nq.gz
│   ├── 54dbeb09ccc97a55602b8a14269e25b8a1d77293.nq.gz
│   ├── 59c49f6515b3e511d038e69f8c8d925051497af1.nq.gz
│   ├── 5a383d0140ed52ee506855e5ffbcafd3fedee405.nq.gz
│   ├── 5d75381b9a1c9c73e4db0945eee285526b3434f4.nq.gz
│   ├── 5de7c24809ae3ac1ae2bf1b2b10e69de191eb62f.nq.gz
│   ├── 657cc210b651adc0e9a7b436e4ac649216752ca6.nq.gz
│   ├── 676360cbc12cb301828ade0e042682683bf3b500.nq.gz
│   ├── 6aafe6fbb766fbf2c9aeb3826635de1e5f2c1d2f.nq.gz
│   ├── 6bccdda8fd0d37432ee87276899ce9e330d26e15.nq.gz
│   ├── 76cd4704cd0cd82312c182dd42e0b864df0d9305.nq.gz
│   ├── 7bf50728c15d8576dc5aa299014c9296d02ac456.nq.gz
│   ├── 821e63309c0823d05a1fe04d0f62dc9c9831970f.nq.gz
│   ├── 872fdb93af94ef51cce62160ef8e082bf2050307.nq.gz
│   ├── 894d373d902f02f44a14345b60e5221465ad5993.nq.gz
│   ├── 8b61332ef9e912af8217ce4b1914926773880100.nq.gz
│   ├── 8d7fb90b29aad548bf91b558175aeba8438a8807.nq.gz
│   ├── 8f7ca78b3a9e9bbe623cb8baa139055193cb97c0.nq.gz
│   ├── 91bb9c999bdd4196fe1d77e8ada78b865b35bd14.nq.gz
│   ├── 91c08410f79a167fcbcc4f19d5948e292013fe8e.nq.gz
│   ├── 9312500841cc10e281e2a34ee1525dfd61ca03fe.nq.gz
│   ├── 9580b1b1502b06974a4619dee9ba6fad07ab1d08.nq.gz
│   ├── 96172f1e9d45f678262bab05357c1302aeb1342b.nq.gz
│   ├── 97620317c9835da99958d7dd987a8f69ddf96530.nq.gz
│   ├── 9a3850594611b9cf2a5c2ffe8b410e8dfaaf79cc.nq.gz
│   ├── 9e0abec32e9d2ba8ba024b7d80f7f5c52f5b523c.nq.gz
│   ├── 9f333306cdebb8b2ed5ccbd49d780be5fff03c8f.nq.gz
│   ├── a4ad2649a500b689c4a8d061c908086fcaf2940a.nq.gz
│   ├── a8e94d7004a4cbe45662f819303a3293ac6ca890.nq.gz
│   ├── a9d6649e87f3cc515d61d76e40655bf16e34b4b3.nq.gz
│   ├── aa3b40a22f0bf6059a6f7de49ee00ae44bc46b4c.nq.gz
│   ├── abef7b2ea1ba5198a9e9008f78dfc4cf08edc558.nq.gz
│   ├── accc9e98973d8f54b102b73e7863440d73df535b.nq.gz
│   ├── ad53f0c6b37943a5363bc16cccf5493efcab421d.nq.gz
│   ├── b52f2b046b43cbaa2b2ab7a658d8111c2e3b8dcc.nq.gz
│   ├── bdf40d44faef44e5a957c64d97b1d5a7856c1064.nq.gz
│   ├── beb588ec9e12ee27850f2d10dc349f46cbe520d5.nq.gz
│   ├── bfd3b82c099f07123cfbd6f68d52558b6e2176d0.nq.gz
│   ├── c179dcd73285b8c6b6841374bac8a7010659d73d.nq.gz
│   ├── c3085d890eeb62be8ec1e9843722449c8d29d6d4.nq.gz
│   ├── c6b802ca7404742636eb11a4a116e4e15b212107.nq.gz
│   ├── c78582c48cd36e9ba8d94debf7e62983ced8a193.nq.gz
│   ├── c820a142220e9095d60194a4101ae3798af334fc.nq.gz
│   ├── c8cddbb41853aa83b90097eaedeeee1981b92fd2.nq.gz
│   ├── cb9fb2f53f4e9f0218c3a65ce0a3646288740cc7.nq.gz
│   ├── cbd920f6b3ba719f191d20703765bdeef260b138.nq.gz
│   ├── cc913626df7b933f74907b505419b2243e1f6288.nq.gz
│   ├── ce1b1dd23a3dd94d67817ba60beb48173ac4cca9.nq.gz
│   ├── d34876b5ace1ea6e7886009ea801d5b23893b2cb.nq.gz
│   ├── d6743b37a742baaef80c06af446ff05d09181a15.nq.gz
│   ├── d7faaf0645c9edbfd2fb751cfbe87b70239d03f0.nq.gz
│   ├── d89630a20bb71d3bf0313a0dccbf3a436e8003fe.nq.gz
│   ├── e440db734501cac6ea4902de86bd88fda9b23b0a.nq.gz
│   ├── e5a5152322d37620eeb1c4d7cd4ea11bb69f9cea.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ed6bc065d45abd2ae0b43e8af5fbef211463005d.nq.gz
│   ├── ef3d081ae85aece080074ba031aa7f8d9c117062.nq.gz
│   ├── f2668f1f7d231230ff63030b310fd2f4a8362d79.nq.gz
│   ├── f6bee051cfba620a8f6cf34962d731368647f7bc.nq.gz
│   ├── f78f2a09e64d851044b1537cd5b19d481331154a.nq.gz
│   ├── f7de8d3eb5a9cdfe059f982bc02c9ecd9cdee030.nq.gz
│   ├── f8646c4b2d60152766637428a38e934bcc0cf847.nq.gz
│   ├── f98a91cfa2ca9ee66377e717d18322f84e8b49df.nq.gz
│   ├── faecd1f60abd138ff9288bbdb47f3df92889b3b9.nq.gz
│   ├── fc68e919af41b01afc08739b3aee2f34c2a9ed9c.nq.gz
│   ├── fcec0ad4b6d0975412eb0f0523365c093761d0f8.nq.gz
│   ├── fec25450d5ce47f6f6b769b385a2c51c611355cb.nq.gz
│   └── fefc3fe3f0ec1b9306c86824eb7263ef52106912.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   ├── 12d25c21cd819a08a4777b7646e16cc604be0405.nq.gz
│   ├── 39b4375f1b5f332ca1166945fcc0c8bd1ec32a7f.nq.gz
│   ├── 61cc6eb2b2c493c0744af546dbe4d3b6cc4dbdc1.nq.gz
│   ├── 7672466c8c78a20a6876cdeb1bbeecd4d6e0c9e3.nq.gz
│   ├── 8f273c6986f63c0bff4be100d5db8738e57a6507.nq.gz
│   ├── c37bfb92fff9626d8b960106416eec99c537f6b7.nq.gz
│   ├── da473d9e6dd6b8ca12a6b73715f84d155c3bd705.nq.gz
│   └── f453fa2ec934b3b8876f71c28eea213b96f7a46d.nq.gz
├── filetree
│   ├── 12d25c21cd819a08a4777b7646e16cc604be0405.nq.gz
│   ├── 39b4375f1b5f332ca1166945fcc0c8bd1ec32a7f.nq.gz
│   ├── 61cc6eb2b2c493c0744af546dbe4d3b6cc4dbdc1.nq.gz
│   ├── 7672466c8c78a20a6876cdeb1bbeecd4d6e0c9e3.nq.gz
│   ├── 8f273c6986f63c0bff4be100d5db8738e57a6507.nq.gz
│   ├── c37bfb92fff9626d8b960106416eec99c537f6b7.nq.gz
│   ├── da473d9e6dd6b8ca12a6b73715f84d155c3bd705.nq.gz
│   └── f453fa2ec934b3b8876f71c28eea213b96f7a46d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

29 directories, 140 files
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
*Parsed on 2026-09-21 by [repolex](https://repolex.ai)*
