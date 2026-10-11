# Repolex Knowledge Graph of jazzband/django-configurations

RDF knowledge graph data for [jazzband/django-configurations](https://github.com/jazzband/django-configurations), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-configurations
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3d0d4216ca01e83c2b34d89a026890288fb82e37
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3d0d4216ca01e83c2b34d89a026890288fb82e37
│           └── chunk-001.nq.gz
├── blob
│   ├── 087a8637212c836bb8da118600926a3d041d1b1c.nq.gz
│   ├── 0a3d76f6152ad7baf5d6270510ac67f928af3ce6.nq.gz
│   ├── 0fe4a28374f4c666021e533c260cead5c361c5b8.nq.gz
│   ├── 1170d214fa394fd1e9a6257b4735bed948ca335c.nq.gz
│   ├── 1b12da9d7beea15dafe228f0559cbb591e365bd4.nq.gz
│   ├── 1bdda2882dbe0dedf6b765f2b32876c0bf72b909.nq.gz
│   ├── 3dbec31a91ef7fa29139c1929289c20fb88a7a2a.nq.gz
│   ├── 42d5678cb362e8878aaee63bbc7c1468f9340daf.nq.gz
│   ├── 4463f6a96ff6b1aa6b2ffe093915f0b448cf2e02.nq.gz
│   ├── 47a9eb6e2ebefe6c25f4013d3c81a709bfac72c9.nq.gz
│   ├── 48e4e0d03d5ed028ffaba34b606b0b6ae5aa6a50.nq.gz
│   ├── 4c03348da48556727b7f1f9c4dbf992a0778d959.nq.gz
│   ├── 4e6a92c443efecb47ac790fb7170e4a27d8069fd.nq.gz
│   ├── 507755e0ccebde2328084faf8a8a06d224c2e617.nq.gz
│   ├── 50b7f6626379ef8e47fa6c4a0f9429bf3b214d80.nq.gz
│   ├── 53643461715dca4bb32558e485f0aabc68990123.nq.gz
│   ├── 59f15b116e8b1b24458399b424778a4c17c6699a.nq.gz
│   ├── 5f2c59df1e51d87edc85a24572b30f35aa42fbab.nq.gz
│   ├── 5f654de1e9174aa2819cf9fb298a5c0bbbf0e72f.nq.gz
│   ├── 6018ac2d87e258eeb7f8a371425619a73b0d4955.nq.gz
│   ├── 6065ed0d7b199f27d5339b1d5bb35207be2ca1f7.nq.gz
│   ├── 6152e0ae30b3b06553f9301c14beaa5099926c43.nq.gz
│   ├── 69090208f398b13f57c4950429e678c77f8dbeb7.nq.gz
│   ├── 6a974aaf905c0f1689989a5d5cae156e1258ad5e.nq.gz
│   ├── 729ca968bdb33ca86fa6b4a741a54e0017bfe338.nq.gz
│   ├── 788e31a60b78558fb0a4ad09ed989002a6f40377.nq.gz
│   ├── 7c9d3e6179e18e2eec2d1fb1e399c73f303eda90.nq.gz
│   ├── 7e02d6ad30571d1f766a7aeaac2c72ac8fec6de8.nq.gz
│   ├── 841635f6e63e7c77c505727b6ad9d35f9bd5eaa9.nq.gz
│   ├── 85e87da6bad86dc4901d55dc8d45a761a8d2bc3b.nq.gz
│   ├── 871ecc288f61bbfb521c38fbe56a193401fd1aa4.nq.gz
│   ├── 879a3b8bc4db311ac2845d99062b57c241bfa7f8.nq.gz
│   ├── 9403f8ec52537d772673d86f4b4a764d591ec7d9.nq.gz
│   ├── 957eb669736ad58c85f787bb074daaf6cda581d5.nq.gz
│   ├── 9c0d55cea8a8c4819f9baf209e02f85400cf5f80.nq.gz
│   ├── 9dc5e45c9b850d97ef5497065ed4d15761e9f59b.nq.gz
│   ├── a0c85f08537131bfde46c9939fc805e47efaa27f.nq.gz
│   ├── a2c324b88d5d032117195f85d738618fc6d45853.nq.gz
│   ├── a356910dcc2a1da32ff539ba9cc71424f37628eb.nq.gz
│   ├── aabd009c3a99a762a7939931eee58c37f3dfa5cb.nq.gz
│   ├── ab15daeff678c478b1b844f43623b250b6d43b51.nq.gz
│   ├── b1a9e9bc6c09402ce13df1c43726e1733556e3ab.nq.gz
│   ├── b23e2d51810e2259d87d6f56555ca082cbdafb58.nq.gz
│   ├── bd0656625ec233bd1de557448eb192789e7dc5b3.nq.gz
│   ├── be006de9a1ae3b9628e796c74277cd6d61e0a34a.nq.gz
│   ├── cc14c80ad6e1eac4f14631dfdcc19f9d86616f1c.nq.gz
│   ├── d999436a6106a286c71d8b94898102c5ab404694.nq.gz
│   ├── da9401b642623c83d1c646d988fe1d392bf5d87e.nq.gz
│   ├── e0d5efab56fb94577e7804603eb6f21f36977cb2.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e718ef5fdec78b93695da7720ae0a0c52e7e0e7c.nq.gz
│   ├── ea157a3053242bf3581397f9a170caf3dd59d4f3.nq.gz
│   ├── ec1d08fa999583a7ef38e1bfafbab595f8d609dc.nq.gz
│   ├── f03fe88f74bdd07e2a6db502bd4103073b524272.nq.gz
│   └── fa61273cd904003263dfa2c9287b875b441ed217.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3d0d4216ca01e83c2b34d89a026890288fb82e37.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 63 files
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

[jazzband/django-configurations](https://github.com/jazzband/django-configurations)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
