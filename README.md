# Repolex Knowledge Graph of PyMySQL/Tornado-MySQL

RDF knowledge graph data for [PyMySQL/Tornado-MySQL](https://github.com/PyMySQL/Tornado-MySQL), parsed by [repolex](https://repolex.ai).

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
rlex download PyMySQL/Tornado-MySQL
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 75d3466e4332e43b2bf853799f1122dec5da60bc
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 75d3466e4332e43b2bf853799f1122dec5da60bc
│           └── chunk-001.nq.gz
├── blob
│   ├── 00c8b4db2dd09bcfda3e84fde96ef65bfed4e632.nq.gz
│   ├── 0a420048ba0253992a8c3bc943937adcd1bcebd8.nq.gz
│   ├── 0c5534677423c6604105a19eadeba0af42830f97.nq.gz
│   ├── 1396cff8a18c8866e88821bd7d6c4f97e4f0cb37.nq.gz
│   ├── 1cf7d9131de85be7955330676437414192bd92c7.nq.gz
│   ├── 1da2755338a72b7e6d89227ef0fc395f44a00b2a.nq.gz
│   ├── 1eb3dcb4724042397ea7c92ebf26697ca8e7ae01.nq.gz
│   ├── 2bda5a96fa7e00120227c3377bdd94da2b60e77f.nq.gz
│   ├── 3df7ff487f447d35d39e27741ef09daa7b1fc911.nq.gz
│   ├── 417ea07f62df9f122ae4a19640a950588498eeb2.nq.gz
│   ├── 45fb2d99c835afd0eb22f67c4d185585da0278a0.nq.gz
│   ├── 5286ff74ba146839ef01d3241480d4e10ba21fc7.nq.gz
│   ├── 553983fb75d5a7798d114a9f8b304c73119b4671.nq.gz
│   ├── 564812e482fd47e28bcb3f3640e9d1351e7340ab.nq.gz
│   ├── 6b816dd9c9b04eb787d71d62b876104111567235.nq.gz
│   ├── 6bacf267aebc33b02239bb59954c78b3e92180f3.nq.gz
│   ├── 6edfded6a7ae7a4f0814f9dc3834a0ce201920ae.nq.gz
│   ├── 6f5d566303a5111d9dfab97236cfbe6374ba6e43.nq.gz
│   ├── 6f6e64bb25aac84593304426f30af10b242c7a58.nq.gz
│   ├── 70867f7e9bca3bab7a8fa1da948c91cd347bdbff.nq.gz
│   ├── 7a613478d43ac7b38db2bb9f1d8809c4194dd193.nq.gz
│   ├── 7fd8ecff106c1b71499cb63cb82159557d144963.nq.gz
│   ├── 852209eda13b6ff977af4964d6d65c169ddabda8.nq.gz
│   ├── 86b18e10bcdcf352909301f5542cd2ffe7c68746.nq.gz
│   ├── 94d7a11881656b10f11b7894408fd7958b7b1352.nq.gz
│   ├── 9b6f24e0da8b802fccdded6f371341ba3685c001.nq.gz
│   ├── 9f728d68b77197eb42c6d71695fdbdb96226b277.nq.gz
│   ├── a6af95837086b6ce92920fbba235bd8a89fe8a9e.nq.gz
│   ├── a6f7502a9cf2ceb5b6eccc3d58bee05a0c757d5d.nq.gz
│   ├── b50709845b8928d35b518684ed221e0758b71444.nq.gz
│   ├── b5f0f4090f95e86e8067ab4982f3804ac9f5a562.nq.gz
│   ├── c2442c6df26d945e8846531f7ece9cb4dfa5e4ac.nq.gz
│   ├── c364898973a87f7fc54d7e62c795f43dddf258d0.nq.gz
│   ├── c47db09eb9c0cd29a74da7108efdf412a5ea9ccd.nq.gz
│   ├── c8a9e4e2c0afdfba29fc1554b728cbfd2cee1ac3.nq.gz
│   ├── ca35319d6e898128d4bcfe16afd447e16a41ba66.nq.gz
│   ├── cbd1804af75a6c914168d74dced3e319b8c76228.nq.gz
│   ├── cc622e57b7443b430ac10542a2146e8701980876.nq.gz
│   ├── d288d2a853726686bfca99309d02bb669a6709f0.nq.gz
│   ├── dec002e1d8ba3021e90457147294070da50d893d.nq.gz
│   ├── e337c466503fd7ba15d964796fb1c6589ba03c26.nq.gz
│   ├── e4237c69a2d15ca2d3af56c41b1f88c72fe9413f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ef7e0b938bb112886783c6d8982c207f1629593b.nq.gz
│   ├── f41313f722c6009e0a38ab3daf716fce2ee60af4.nq.gz
│   ├── f590b9aba8512863914fdee1ad1d654a4a495835.nq.gz
│   ├── f9ebfad6d5c387f95b5a591c59b4f38c6215ec3c.nq.gz
│   ├── f9f99c8fa32de4a75ef01859eadcc4de94c5c961.nq.gz
│   ├── fc4dfdb9c7fb97cee0c3de01cb839db2114cbf85.nq.gz
│   └── ffe1e4547132fa32f30dc38a1adbf0d96037e36d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 75d3466e4332e43b2bf853799f1122dec5da60bc.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 58 files
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

[PyMySQL/Tornado-MySQL](https://github.com/PyMySQL/Tornado-MySQL)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
