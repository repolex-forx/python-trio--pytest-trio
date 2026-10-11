# Repolex Knowledge Graph of python-trio/pytest-trio

RDF knowledge graph data for [python-trio/pytest-trio](https://github.com/python-trio/pytest-trio), parsed by [repolex](https://repolex.ai).

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
rlex download python-trio/pytest-trio
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f0168502bc3340f22b8b80ed388efa1a26883aa8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f0168502bc3340f22b8b80ed388efa1a26883aa8
│           └── chunk-001.nq.gz
├── blob
│   ├── 0a6c4d649ee97e0535817c94b63639e77969a0ad.nq.gz
│   ├── 0c136148c7e66ac5f21686b0640621c405a264b3.nq.gz
│   ├── 0d3b1a315c262ae92c9d3b8a17719c7589dfd66f.nq.gz
│   ├── 1a281f8dc2269d2f80d9bf8bf34fe1dcc61a2423.nq.gz
│   ├── 22c803a5eecd622e70838b0b963f8968d094a45c.nq.gz
│   ├── 2333e2dab70d32923ff4393af1ccd5dc89925e4f.nq.gz
│   ├── 27646ae83402e3501b33682a465e183f79b7541e.nq.gz
│   ├── 33bf1470f476f3cf372d23b114f6ce08081a8c7f.nq.gz
│   ├── 351e8c1b9f20e4eaff1f8a33afb744283d139967.nq.gz
│   ├── 361e062ab0e88ed75fd9e4d93d51746119a8b6c0.nq.gz
│   ├── 3703f730d53e3176ecf70904b084b3892bb837ae.nq.gz
│   ├── 3bc517c28b5eaab640d4910f6474a319f1e97b3a.nq.gz
│   ├── 4850310fc80bcc95fb45e89b19dbb0f8f3609544.nq.gz
│   ├── 49db040e3da420dc6fa781978356a2189e8d0d67.nq.gz
│   ├── 4df2975a96fea77aa8d0a3d24caf8b535e5354d4.nq.gz
│   ├── 503ad5e11ab4dbfd0c53c4780191a1c14c983b4d.nq.gz
│   ├── 50404a561799df3777338f88d1428b83d710c56d.nq.gz
│   ├── 51f3442917839f8e0f0cccb52b3c10968ad0779e.nq.gz
│   ├── 54c531cafc82fa7bc7c4b62b77451083f59dffd8.nq.gz
│   ├── 5611320583c1c41139aab1b3a9d2a58220cae6f6.nq.gz
│   ├── 5fa2f81c34e093b7b461f6c88dc3ec49dcdd3970.nq.gz
│   ├── 66154836b45eeb6f2c3da1c4e089628cd91db93b.nq.gz
│   ├── 67ed440cf19869097c028304134b0f780c6f2958.nq.gz
│   ├── 69c1f10319db41b6677a720fcbf44939c7afbdf2.nq.gz
│   ├── 6cb3501f973c4f32869f8271fcb5eca9e5605fb7.nq.gz
│   ├── 73a394c3c3496cc4229cfca564ac202c8f39b280.nq.gz
│   ├── 79d6635912138beca759d25c2662b1299a41a88d.nq.gz
│   ├── 888fbaa67e6ee52b73da4d168d0f0b6070373241.nq.gz
│   ├── 9505eb2f2dfd14480d947f2072e1bdc4899a50e9.nq.gz
│   ├── 9dc7de425ce21a93cfa1f0c8df2964ac76169d23.nq.gz
│   ├── a1809585776ffc487b170057a806bf0e676bf26e.nq.gz
│   ├── aeacf0a17fa53395e0b53d46a556d0a66554c391.nq.gz
│   ├── afc90e2323a0bb08ef0c580ce3122ac6471578a9.nq.gz
│   ├── b38f1a56edac686f29b4e1c99c1fa8fe0f488f04.nq.gz
│   ├── b8bb97185926d7daed314609753173945ed4ff1a.nq.gz
│   ├── c02178aa5a1753b63335dbbf7221b3b7bbd65a0a.nq.gz
│   ├── c6060a43cd42298927a7f384d040cf10fb7e1446.nq.gz
│   ├── c6481d5f740462ec9fd3edcb32aa56806e316c77.nq.gz
│   ├── cb95a96c4b96a5718ebf6e9d02c1ddfb8c8f3732.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d8590e8cbd819abff871807b2e787395b5da4208.nq.gz
│   ├── e4793e34f6b1d0de8fa0d0088772adc080e416ab.nq.gz
│   ├── e54506b988193bb714d4f4bfc6a03e31bad4917b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea8f5a583ef4a38ea7da42540e47f44fb6185034.nq.gz
│   ├── efe32cb5f3783cc434c11672fd3ea88f63497a51.nq.gz
│   ├── f20319d2f452105174061a2f1322956af439f982.nq.gz
│   ├── f48700bd305ff82cb5ff747b049ee79a8e90f87f.nq.gz
│   ├── f95538f5398f26055d0fcff347cbb91f59fb35aa.nq.gz
│   ├── fd29f82ee663e5fcc5cb87ae76753b175b263dfc.nq.gz
│   ├── fe23cd16071aaab10a783cf10fe7d5b802cc071f.nq.gz
│   └── ff432abc99290d71ba457964733772fe1cec20d5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f0168502bc3340f22b8b80ed388efa1a26883aa8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 60 files
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

[python-trio/pytest-trio](https://github.com/python-trio/pytest-trio)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
