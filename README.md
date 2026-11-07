# Repolex Knowledge Graph of ansible-collections/netapp.azure

RDF knowledge graph data for [ansible-collections/netapp.azure](https://github.com/ansible-collections/netapp.azure), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/netapp.azure
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 825651a2e8b0830607ee11321f9934d3ce6b996b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 825651a2e8b0830607ee11321f9934d3ce6b996b
│           └── chunk-001.nq.gz
├── blob
│   ├── 0342115bb9ff6262f5e1f492d2ff57f8c05f602f.nq.gz
│   ├── 0415a40396384b525db97c48ceaf6e631f408bbd.nq.gz
│   ├── 044018d2c8bb262c573c4a56be59a3d59679df08.nq.gz
│   ├── 05dcdd6dd56dfec41b7350c24b62ae6eacb47a64.nq.gz
│   ├── 0972cd2e8e58d51f20c6b0d23d8f89154c7ac076.nq.gz
│   ├── 0b89f6365e85a6ad4e186b50b12fa25d8dbb49a3.nq.gz
│   ├── 0d140b4a04eea7eb1d9ce12e5a2a23bcaac3c91f.nq.gz
│   ├── 11852e2a501dea137e40ebe19cc046c49e71d280.nq.gz
│   ├── 13d3bba294a85182036611570b1da7dd0d36a408.nq.gz
│   ├── 16632708888127811db598db2fe9f2a2a601b02e.nq.gz
│   ├── 18e9cc2a211e07953d6f8dba635f9e6e54abd91e.nq.gz
│   ├── 212f1086176fa4622e2995af16da3e47a887c7ee.nq.gz
│   ├── 2889546f8bfeffd0c33025d851a7a6d1ccd16e59.nq.gz
│   ├── 2b09e21ceb53a776ff87b20e41a7197da3117392.nq.gz
│   ├── 37408fb675479a0a7c6ae9b6232bb5f37a2c8bc2.nq.gz
│   ├── 3a0c0dc68de2602797fbeace0374c776a947ecab.nq.gz
│   ├── 3f764c1c9f8f8c49e5979d76b4d448e1b8d56962.nq.gz
│   ├── 487787ee7a6db70c1b031a18ef1dea4b7daf9902.nq.gz
│   ├── 48f5726d896a9b8c3a3ad29721a26ffb8c5b457b.nq.gz
│   ├── 49467db708dddd0e0c221c297816269f2d03fcfa.nq.gz
│   ├── 4badbc6ae23eb61763f603f76abd0ac5c15da26f.nq.gz
│   ├── 50e2e7d36d2dba468bb94a2dc0741c65ab2a83a4.nq.gz
│   ├── 5567f189bc7ba8d1b8b471fd3c5ed94f16c298f3.nq.gz
│   ├── 621d52529c5d67bd137b5b3afeccc3ad08dad04b.nq.gz
│   ├── 67b15df45e698f4f9d02394f880ceaeba0d0b668.nq.gz
│   ├── 68e9d285d498c198a86256f0f8fe42496a4e86c1.nq.gz
│   ├── 6b4b660a0627a7e4d86ac70d8e522d86796d52f0.nq.gz
│   ├── 71085dedf820ef4f7753ccf96037fed72f2f2cec.nq.gz
│   ├── 720ce523da0ab8be027760b57ae11df4342c2f5d.nq.gz
│   ├── 73a20cf8c240972154f2e3f34bbd7079373da0d3.nq.gz
│   ├── 759eafa2defd19902f1875a841e2e73d29d6d476.nq.gz
│   ├── 781042d6f19c6fd2ff2e9acbfcd4b153e52246b6.nq.gz
│   ├── 7fc5d9faefee66eecad0e977655ed23413e37331.nq.gz
│   ├── 83c7f812e5fec5d423f5b7b5cddbf3c0047d9732.nq.gz
│   ├── 87c49d0520beb13d786719566dbb805b4f94769a.nq.gz
│   ├── 8edb80eed0af943c06a5597c26c2811bdb17adf1.nq.gz
│   ├── 91c8eefd627016b6aeb5bd97715b9dedef11068c.nq.gz
│   ├── 924232e4ccc1aec972d51e9de28146f25144a53f.nq.gz
│   ├── 94a9ed024d3859793618152ea559a168bbcbb5e2.nq.gz
│   ├── 95e1952f98900b4df1c48cb62ead4302afb9f639.nq.gz
│   ├── 9bbae4ae7029e51222ddfb0c69877e1595d067fd.nq.gz
│   ├── 9d099a03f989cd00cb9bb0f3ba223160ba761453.nq.gz
│   ├── 9ee758c0126cbca2c31026b9c6dea0c0b204c355.nq.gz
│   ├── 9fa627e48db298229400594f0990936428c8b29f.nq.gz
│   ├── a2f16d6b0a2aeb56127beda83ceb4dad2e6fae91.nq.gz
│   ├── c09ade0dfd03dc5c575dafbb5d1b499be346f07a.nq.gz
│   ├── c1c1cf5c209e86ff3bb211167a97b03d0f80c0f7.nq.gz
│   ├── c5b2a4262fa6c5078446e74f392186917cc6a4c3.nq.gz
│   ├── c619dbcd9f78696a50d177edee2ac51d78942f9b.nq.gz
│   ├── cbd239e0e95487e9e6ae12470c7b08c49ef42798.nq.gz
│   ├── e150ea10d4fe14375d67bc57c9aabb5ccdb6ee56.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e75cf1e2b6f6dd4b0096524ce686eb49d1cdcf3c.nq.gz
│   ├── e9adbdb9bad9f7a617e1bfb975de9670f08b3c3a.nq.gz
│   ├── ed35f3dddd0c651dfd9cb9a4f632a5436123d114.nq.gz
│   ├── eea54a872dfa91a88ab2b3beb3136ee4de8f2ad6.nq.gz
│   ├── f0c1f6a388d5f58667fd27d4d0250fbc60eed02f.nq.gz
│   ├── f60ee6782280b043f8014305cffb9b0d2c4d184d.nq.gz
│   ├── fb83c464ef059768d66ba7b43205fe142b99671a.nq.gz
│   ├── fc18835a2db3068fdf557286b1e4235350774667.nq.gz
│   ├── fc582847bb03dce72b29af631f5e68ae6a87aa1a.nq.gz
│   └── fcd0312f6df78b3c7106aaa8c95242f1e2a7e70b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 825651a2e8b0830607ee11321f9934d3ce6b996b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 70 files
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

[ansible-collections/netapp.azure](https://github.com/ansible-collections/netapp.azure)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
