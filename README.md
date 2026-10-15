# Repolex Knowledge Graph of scikit-learn-contrib/metric-learn

RDF knowledge graph data for [scikit-learn-contrib/metric-learn](https://github.com/scikit-learn-contrib/metric-learn), parsed by [repolex](https://repolex.ai).

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
rlex download scikit-learn-contrib/metric-learn
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8eb775ea82c41829bc583629ca3fab0fd8f204fc
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8eb775ea82c41829bc583629ca3fab0fd8f204fc
│           └── chunk-001.nq.gz
├── blob
│   ├── 01d185e7dc628b17f26a48967f3073039563e906.nq.gz
│   ├── 01dfb1d7cef8658a31144c6727bc9aceeb89e15d.nq.gz
│   ├── 05035085c1be53b3d35d79a5567743525cb6eb4c.nq.gz
│   ├── 0935a109f36c46a17aa54ffe9a7afecc10da3a04.nq.gz
│   ├── 0d864db6ec4160ef479cd5bb4b10cdd6b9825bc1.nq.gz
│   ├── 10dbe0d593ff489cfdf7c39b2378f6316b9c4a3c.nq.gz
│   ├── 110b07f9f6490229aae03492ed627267f0be2108.nq.gz
│   ├── 233920773db93d4a3731f7d37d3a9f1801a12d76.nq.gz
│   ├── 246223b06186e7cf7d63c9de03081013ca5e80a2.nq.gz
│   ├── 253b9c9252bfc886dc2894ac9ab211e53455ae95.nq.gz
│   ├── 2c05b28d55a146ebb8a9d7fb66efa3f2075bb7a1.nq.gz
│   ├── 327596365973b1c1249e32e6205b0f6ee2ec6368.nq.gz
│   ├── 3429d9cc923aac23595f216466ceaa91d59ead8a.nq.gz
│   ├── 415acfcdd777febddefc4ab55e05c341dd04dc67.nq.gz
│   ├── 47bb065fbcd3a529972bedd88019d28eb765d394.nq.gz
│   ├── 47efe4b7f0b966ed0aef98ba6f92539cb6845a72.nq.gz
│   ├── 49548b83fcb02e9e8eaf269f7331168cbfb4cd7a.nq.gz
│   ├── 4993e9ef392bcc9ba21b3f3adb769057a2632e3f.nq.gz
│   ├── 4d0676b9627698b5d98b70ac8ee57545e26c603a.nq.gz
│   ├── 515a0a3322bb780c3b2aa23f09b54bde0e920e77.nq.gz
│   ├── 5472107a411626876262fdd8f31bc10881f7388e.nq.gz
│   ├── 5cf166fd0751706d115a82eee085bd4eaa634f52.nq.gz
│   ├── 6623532fac7f8daf4b6306ea12c90ddd62829d69.nq.gz
│   ├── 66eb3551caf74b4a3197d6dddc8c70143eaeaf56.nq.gz
│   ├── 69fa449dd96e2405945b2e4cff2fd0ab8b102097.nq.gz
│   ├── 6d350ae4a2f6418cd19fc7904190089070b0a92b.nq.gz
│   ├── 740852be703ff663aec3d564dea8fc3ee14e0f8d.nq.gz
│   ├── 753cf2f771463312daf967703797862d5b7bfc79.nq.gz
│   ├── 76f09778c17f8034c284a01ebddf992063afe05f.nq.gz
│   ├── 76f7c14e4753c3ae2e73c4064df898e615ab9c57.nq.gz
│   ├── 782d3ab2f48d30755eb4df81fae7587bd06da067.nq.gz
│   ├── 798d9036f4c8526204e161fde0dc0dcf738c6a8b.nq.gz
│   ├── 7b4423d32a551270d7acacbc7e164753b4d28843.nq.gz
│   ├── 824e23ace61aa58c36edeb0a4042b2cf7df3f0c2.nq.gz
│   ├── 82ae20ebbf65d3e1371a1a5fc4327948ad57f5a7.nq.gz
│   ├── 8d746890b8b8192c349b7d4f61f09da2a4203ff3.nq.gz
│   ├── 90b7c7eef43dfdc5ef6214c3cfab037e8a109ce7.nq.gz
│   ├── 92823fb1a307d658ca953f249a2e3c261acb1373.nq.gz
│   ├── 9378ac607814c1e49a1fb90dd9dd751b373ecd71.nq.gz
│   ├── 9537eec2e567dfcc86c9a2cb032d8cc78c8c9ddc.nq.gz
│   ├── 9e36845f8ae89cdb3b2706a09e8e55649f3f5938.nq.gz
│   ├── a71c5c7f113e884f246252532ba9346cca77973c.nq.gz
│   ├── a83199613510063ed9731c3d2f9bc27b14008721.nq.gz
│   ├── ad1ffd8fbb6010ce41d03f14b22cbf2bc988e553.nq.gz
│   ├── ae342735db95f970e83ecde20559d7da48dafab1.nq.gz
│   ├── ae75783821d31cf41be1ce38f2dbeeef72097d52.nq.gz
│   ├── af7fa95b14c45ee08c8473d6bb7e4d45ed1f2ab7.nq.gz
│   ├── b1e71020bc061e47a40d88cdd859b50ff05c0f0d.nq.gz
│   ├── b2f6e6d41d13b2ed71cb451aaf3574fd3b875095.nq.gz
│   ├── bc7695e32c3cacae42a8433b14a8f5131d56c60e.nq.gz
│   ├── bfedefea48704644a86f09de61b04ebc3f505257.nq.gz
│   ├── c0383792fec26d06f941f89ea0b8674507e2a3fa.nq.gz
│   ├── c472cc219fb7ca6461770e21f55b61433488f699.nq.gz
│   ├── c4c427b9ae22ca09bf19202895ad0e99b63c592e.nq.gz
│   ├── c61139573fb36105f7a642959744f77beccb817a.nq.gz
│   ├── d457b52d5debc631e6ade600bc67fa6dd9acad36.nq.gz
│   ├── de6082184722ba6758e6a3921a3fcc286879625b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9ff00155b295ccb89fa182df63dc236a39d10c8.nq.gz
│   ├── ef3c8acb026d8921f2045325d4fe662eddb39dab.nq.gz
│   ├── f01db0a445ec96b149f7c13bfbd901e4ee55b911.nq.gz
│   ├── f0c1b5bc70edebae4444f5c64fc5fe6e31bb5662.nq.gz
│   ├── f9dfd83d98c7ea7424db28b30c101c9233830328.nq.gz
│   └── fedf393d3f03924906e108c832b64a80e3c72549.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8eb775ea82c41829bc583629ca3fab0fd8f204fc.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 72 files
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

[scikit-learn-contrib/metric-learn](https://github.com/scikit-learn-contrib/metric-learn)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
