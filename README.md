# Repolex Knowledge Graph of asciidoctor/asciidoctor-tabs

RDF knowledge graph data for [asciidoctor/asciidoctor-tabs](https://github.com/asciidoctor/asciidoctor-tabs), parsed by [repolex](https://repolex.ai).

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
lexq download asciidoctor/asciidoctor-tabs
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7c7965554c75fb1295488f04d836ebf2bb9b3459
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 7c7965554c75fb1295488f04d836ebf2bb9b3459.nq.gz
│   └── repolex
│       └── 7c7965554c75fb1295488f04d836ebf2bb9b3459
│           └── chunk-001.nq.gz
├── blob
│   ├── 00771c4e2142f8f2b73a3e90dcb691f61bb809b6.nq.gz
│   ├── 137a30a1adca053191b3ad5612e82f2d3378411a.nq.gz
│   ├── 16fd9194ba1529b1703784155b802f884f6ad0d7.nq.gz
│   ├── 180a1ccc011f2e3d4546dd2a83feeabd931be99b.nq.gz
│   ├── 1fa0a4fea61d8edd43c975edf9c5e382bf29b4e1.nq.gz
│   ├── 23293988e7b1e0ba8c3566811d7f5c0f027dc54a.nq.gz
│   ├── 23cd58d7e01ccb6c434c203a414606667e06007f.nq.gz
│   ├── 274041ed44257a0d118f173820cc316db17ea411.nq.gz
│   ├── 2ccbe4656c6078ded72491cf2ee9c5ec20219624.nq.gz
│   ├── 2df644bb091b6f245651cc9dc1d1de49b02090e3.nq.gz
│   ├── 37808b4ef5f382e1da9939b1e76f5390f9fea8e4.nq.gz
│   ├── 38d247200b628da9dec815e1df4e44b515aa1732.nq.gz
│   ├── 405c9b1714adae094275a125fdaea2e6b28381a3.nq.gz
│   ├── 4206970b95488f1a13957dd6ff6ab1e6f360e34c.nq.gz
│   ├── 4378a0c2d520bf8f37960ae3d551cb425cf06732.nq.gz
│   ├── 5407f0a3369a6873bf7738e6349cced168ed70e7.nq.gz
│   ├── 595713736e16ed4f5162779e9a71da8a91943cd4.nq.gz
│   ├── 6b5ada3cdd3f0b407fbea80a82c5f13361e939fc.nq.gz
│   ├── 6bd10ff5ddbfdd02ea1a75f820c8c6239df09fcd.nq.gz
│   ├── 6eeddd9865fed09f5a0eabbc5039b3d367b21bf4.nq.gz
│   ├── 70922df7b998327dd95a39945c33a5910e802b94.nq.gz
│   ├── 76d54f601ed14f314ece42c12a0b1701af31629c.nq.gz
│   ├── 7cccd50b2cd8d768a87667d7dbb6a05a50cc9a10.nq.gz
│   ├── 80f1643163518c84902bf04d3ff9bed78e03f1d6.nq.gz
│   ├── 85b17e8cb051be811af61a462625fc93e24c7529.nq.gz
│   ├── 8fe9db2dacff8acc20abceb82a0499f7ff036e10.nq.gz
│   ├── 9d241a781ff8c0f0138de2c0f3749ddad98ce750.nq.gz
│   ├── a27208c404ad9e9dac33e4db7fcd524a6ee0fd60.nq.gz
│   ├── acaaa07d57a2cc0d4283f20367969732b9b76e35.nq.gz
│   ├── b84481952d4d7e8033145ce08bac63e6657f9d39.nq.gz
│   ├── b9e8177aa9a7cdea2d36ace2d01c1bbb991e32a7.nq.gz
│   ├── c2d588e38c3678878acfa08e3528c05fb1a6ddda.nq.gz
│   ├── d0d31670c5d82bc43b5d0444a7b48b069078d579.nq.gz
│   ├── d9fdfb59bdb1cb7ad6a0ada3a1400a8465e134a9.nq.gz
│   ├── df191f56261cacfd0bb72caae80a4e8dcdcb2b8d.nq.gz
│   ├── efd6c3162f52cb77b28b0342b22b680856275d6b.nq.gz
│   ├── f419e483f630cea3aafb3af3d83c7fe9f3c865f8.nq.gz
│   ├── f4471917a8c4fd6ac7d0b32f4e7f4fea4d2c0012.nq.gz
│   ├── f8966c02475a69746e648a71fd2b353589f41675.nq.gz
│   ├── fb3aed6a56adb71eb25d47fd4c06277160f5c561.nq.gz
│   ├── fb963e22140ec3df573b0c0d404cdef3f0995056.nq.gz
│   └── fea0616de332fde9ed819cdfc59748d562fc9d00.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 7c7965554c75fb1295488f04d836ebf2bb9b3459.nq.gz
├── filetree
│   └── 7c7965554c75fb1295488f04d836ebf2bb9b3459.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 52 files
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

[asciidoctor/asciidoctor-tabs](https://github.com/asciidoctor/asciidoctor-tabs)

---
*Parsed on 2026-09-14 by [repolex](https://repolex.ai)*
