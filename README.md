# Repolex Knowledge Graph of bcomnes/npm-run-all2

RDF knowledge graph data for [bcomnes/npm-run-all2](https://github.com/bcomnes/npm-run-all2), parsed by [repolex](https://repolex.ai).

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
lexq download bcomnes/npm-run-all2
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1ac5e39db5dfced7c8ffe287f9a1649bd16cc0b2
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 1ac5e39db5dfced7c8ffe287f9a1649bd16cc0b2.nq.gz
│   └── repolex
│       └── 1ac5e39db5dfced7c8ffe287f9a1649bd16cc0b2
│           └── chunk-001.nq.gz
├── blob
│   ├── 01e566d5539aeaa0664a8eb19b03fa524f9b6148.nq.gz
│   ├── 02b66d1cb4c183de815978fe663268716acedc88.nq.gz
│   ├── 031853ccee6c1d3bcbbdfb497f6a551b4d608313.nq.gz
│   ├── 052feb59a4c886eb8e5667c8113234ff4176eee5.nq.gz
│   ├── 05c5e3cfdb12c66f6e41efbaace0da53a6950e77.nq.gz
│   ├── 082ccc6bc632f4eefe8d1445a0e5dbe1b47ae221.nq.gz
│   ├── 0e799dfa09d1869c90e68697ff2e9dafa23986ff.nq.gz
│   ├── 17255c9706b99f56ec4e10e841f245478e762af5.nq.gz
│   ├── 1983911dab5490ad0c2310187660661ee69bd315.nq.gz
│   ├── 1b72bce153eb5b2d2bf7cb71c55b31c61293aba6.nq.gz
│   ├── 1ee7543138695d9ac3259a1b925cc616a4bab327.nq.gz
│   ├── 205021e49dd1f7342400b8e1254cc4e310fcc4a1.nq.gz
│   ├── 21cc6670be032287859e7937003d9401780b2b62.nq.gz
│   ├── 21fff99fc40acc02b8f2e85cec91f70fdbc78c2a.nq.gz
│   ├── 27231f4fbfe35eee64090acab24da6ad18f5830d.nq.gz
│   ├── 28022f8659f706d803a03938d90cd70af6e53d88.nq.gz
│   ├── 28db4ec4bdc0c2298f070d102d55384fb1243f18.nq.gz
│   ├── 29e8fe747aee5f02a5727215920522a059805bdc.nq.gz
│   ├── 2dab65ebaf75eb729d1eab62989f6ebf866c62b5.nq.gz
│   ├── 2e36bbd3059d9b379c84029a137713518f66fe98.nq.gz
│   ├── 2e88c05d7670c4f97b5ac0941b0be3aaf89422d6.nq.gz
│   ├── 30bcceb7936e8052e9942f2d7ca91e7750a3805f.nq.gz
│   ├── 37530e1a39c8d3dc173f2b32c065915d875c475a.nq.gz
│   ├── 38e0306f70cbcd8f03b6ef8551cff75ccc680112.nq.gz
│   ├── 3a44a609a263d3a32b05bd1446e8cccf29efbb13.nq.gz
│   ├── 3c45abe610907f40a6e85b1e4c2cdb27354d900d.nq.gz
│   ├── 3d2d801a9e37792a08ee534247ea0f7519c68fda.nq.gz
│   ├── 3e2fbc3180f87b7afb5973849cc8c1e5d2d842e5.nq.gz
│   ├── 44f03167d06b0375aca18842a09a27fa62a0fe7e.nq.gz
│   ├── 4df8a5365cbcdde94b4e4a92f292549f9b6c7958.nq.gz
│   ├── 5022705a564e6b49138297fa072e6b516eca15f3.nq.gz
│   ├── 522e097dba66a35b93962ee4866f226615385212.nq.gz
│   ├── 545d40ca0a496fb10b96edf43e8d13d4414535c8.nq.gz
│   ├── 5d796c16837f4b0c44bc5d23dfae7be13b589b84.nq.gz
│   ├── 5d80447242b4130b114d857a64e96ac109cadd70.nq.gz
│   ├── 5f8816262f7c43076fbc5b7e4fa7a843739e74ad.nq.gz
│   ├── 6044ca586779833238b93bb0f3b3a76255303c30.nq.gz
│   ├── 65264ca0d588050085d54575ca99ce24f0a10f52.nq.gz
│   ├── 65d001551988c1934773ec792d458bee5f19275c.nq.gz
│   ├── 668c58cd7c9f55cbf7bc91d62638f271ab74b23c.nq.gz
│   ├── 67ebe321cc431e203c46638933ac2e1ae65799a3.nq.gz
│   ├── 6ad3d86ebaad5c948a0bbb5807010a87e9e23fae.nq.gz
│   ├── 6d5b42790c6af7e188523144860e8c447784cab0.nq.gz
│   ├── 6e348d1eca14f18d538556bdbafc27764a2b4d74.nq.gz
│   ├── 73818bc376363d95f131265671c194f94aa902a9.nq.gz
│   ├── 77897d3ec07463196e4cc7110fa36ae39f0f59f9.nq.gz
│   ├── 78c07016e7540335725284a0140937cf43fbb14f.nq.gz
│   ├── 7c68eb80d94653e6933c8070a25c4410ece0f17b.nq.gz
│   ├── 80e92da4713711d56959fe70388f8ffb65b1dbcb.nq.gz
│   ├── 8204d370beb8b3ae0d39081a962010fd5346acc6.nq.gz
│   ├── 8227c5a3441c02d1a0b77e7c2f334092f7ee1124.nq.gz
│   ├── 91cca8238af4d1100404566f49362ed38656f2d8.nq.gz
│   ├── 9935885f6f048140dc7073c54631dd921493eb97.nq.gz
│   ├── a0826fc086f554343e013952cf8b605c1574b4b2.nq.gz
│   ├── a7c2bf33f604fca25a25321dbb056ec82b80f63b.nq.gz
│   ├── b2ae20fb9fb3ef718ff17324e02e0356ecd726f6.nq.gz
│   ├── b33ef43bfe9c7d796185019ac9886abcd54e3bf8.nq.gz
│   ├── b87e51de3c20f75328449dfab9e1b083ab50307f.nq.gz
│   ├── bad6c70dc6009113a18ab6cd22ae6b90e1434c8e.nq.gz
│   ├── bb12a0a7ec41d2d1b5496972769f6fad54a3c490.nq.gz
│   ├── bb45b8348748737dd9473961c4de38da59653b19.nq.gz
│   ├── bd9981b1aa30a592a20390411aba36dbac9f1dd1.nq.gz
│   ├── bf0004c6bdd23627699f2aaa1ebc4a26f2143bd0.nq.gz
│   ├── c19918a49ef55089967c549021273d2076cd7082.nq.gz
│   ├── c39e6949ed2dc6c05fce7ed3c7bfa12c38ef0ce2.nq.gz
│   ├── c92d7a32bb405cefec7abdad293f3d8920018683.nq.gz
│   ├── cdbfc977ae667791e2017b8ad2f5d306a58135ba.nq.gz
│   ├── cee4646b904c67b87312fbb59e52ffa27b7970d5.nq.gz
│   ├── d6a55933f1bf47ef02e4e20637e0c4be41b8cbb9.nq.gz
│   ├── d6aa06ad3cb9230f4cbe937d46bed198d64200c6.nq.gz
│   ├── d6e9b40c6ae5cf291245dfee864bf19aba6a80ad.nq.gz
│   ├── d8042011f33a64f9c8f24232ea9965b71ba50dea.nq.gz
│   ├── e8ebd23295fc724a7bc738011ffd0a407a48e45a.nq.gz
│   ├── ec98743bf0c28273b14c3c60c7229c8df3e0f21a.nq.gz
│   ├── f313222da3c96cc611e05f305492ae1e7195a18c.nq.gz
│   ├── f3535c3f431d41aa18d1a3441d6a115617ceeee8.nq.gz
│   ├── f58f72c540370d84200d78d0bc35a4f05fa04f8c.nq.gz
│   ├── fa7eaf7f5cbef827264cb9b4c2f03abc298956b3.nq.gz
│   └── fc22202c7ada0e91753c93b4afb100030db2c75b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 1ac5e39db5dfced7c8ffe287f9a1649bd16cc0b2.nq.gz
├── filetree
│   └── 1ac5e39db5dfced7c8ffe287f9a1649bd16cc0b2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 89 files
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

[bcomnes/npm-run-all2](https://github.com/bcomnes/npm-run-all2)

---
*Parsed on 2026-09-17 by [repolex](https://repolex.ai)*
