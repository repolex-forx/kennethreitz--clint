# Repolex Knowledge Graph of kennethreitz/clint

RDF knowledge graph data for [kennethreitz/clint](https://github.com/kennethreitz/clint), parsed by [repolex](https://repolex.ai).

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
lexq download kennethreitz/clint
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2bd5aef5bc3612b55a0ecb3c3ac47a38dfbf642c
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 2bd5aef5bc3612b55a0ecb3c3ac47a38dfbf642c.nq.gz
│   └── repolex
│       └── 2bd5aef5bc3612b55a0ecb3c3ac47a38dfbf642c
│           └── chunk-001.nq.gz
├── blob
│   ├── 01b236d08f3b3a37e9f7c13007a7cc67c34073fc.nq.gz
│   ├── 033dc32a0b1ce4801551591ffc72acbcc8c237b4.nq.gz
│   ├── 09dedbd9bd41d0706ffcb158022d3e0e2c243c79.nq.gz
│   ├── 0e225487795df038d0b6cf396bfcdf7f2b4975eb.nq.gz
│   ├── 0e940be000350f64327d53952210e9372d8c41a4.nq.gz
│   ├── 0ec65d0e2393fe675648f46032adc3e480a8ef52.nq.gz
│   ├── 12d3deeaa4dc6542ac18b08cd96834ef989a7c41.nq.gz
│   ├── 147a3e0349d74a120ce32becf924302c38e75eb7.nq.gz
│   ├── 1c6df309edc8fd9c5aaa21d4a7fb867dd73ba8ec.nq.gz
│   ├── 1e6ae1aeeab4a929f63613d7ad70a92dc6747e3d.nq.gz
│   ├── 1f1e5a5fed05e80cca92883218187f404794503f.nq.gz
│   ├── 22055eca078ee5be4ebb207873aba8a3552c3b00.nq.gz
│   ├── 24c96a5523e85a4bc85c6c57a2790f7589510c68.nq.gz
│   ├── 307a1f0d658343ab2579dffd080f035a94a7e87f.nq.gz
│   ├── 33f47449c11d241e36c83d7f95d819bbe56e2c8f.nq.gz
│   ├── 39f2a6893fe8b515735db11814657d8fc2d1ef9b.nq.gz
│   ├── 406373175435cbf46f809f95156f0fbb67dc9432.nq.gz
│   ├── 434dd6aa5dfbef1671b8edd67f0ac052dce05470.nq.gz
│   ├── 43d5e635f4cc37bd888f6377a652df99f4b257f5.nq.gz
│   ├── 46b9651f2cce85bad848dde7c6a8189265efb530.nq.gz
│   ├── 489a9175bbea0ba3c1d9aa29f5dc883fcebb1a09.nq.gz
│   ├── 51aaa34bf8ee1e705f9e35b09bb1ef79a000ae23.nq.gz
│   ├── 533aa3e359baccde6efd3c0f681c411566804521.nq.gz
│   ├── 542b462515db7875ea5813c33181870ae06edff7.nq.gz
│   ├── 5b0303f5a3be2bed7cb3e07ecbc10ea5d02fa996.nq.gz
│   ├── 639cb8c4489494a9cf01a504f3712d65261d5a69.nq.gz
│   ├── 6ccba4aa21f72837a5c948ff1e0301b2412323c3.nq.gz
│   ├── 6d564bab4311e3c52e24ac95211f0b7078c079eb.nq.gz
│   ├── 7029ff84cbff11fdc8f595ebbbc812f922f6d9fd.nq.gz
│   ├── 7411343790bb2e61266c16f0b4e6de5fe5513051.nq.gz
│   ├── 7751bc316bb99d8d9afa18db59c8fb4a83d72816.nq.gz
│   ├── 78100b352215507f5908143adce8e84c4e1cde6c.nq.gz
│   ├── 7995e972f8152155068209b46e194a5dac74e420.nq.gz
│   ├── 79d09c59086111053dbe3aa2a32702eb7b4a0294.nq.gz
│   ├── 7c45983e7a5ed0ccf2103f394247d7b7a460f47e.nq.gz
│   ├── 81f4d30592d3b4270b2f52a135769c1b3df2c36b.nq.gz
│   ├── 84e544cf93e4afb8e3d753021449139036d742b1.nq.gz
│   ├── 8648482a31052b02bd012a64314c2d82f55716f3.nq.gz
│   ├── 8b306e136c78205bfcb775f0255859c28c8a89cd.nq.gz
│   ├── 94c592fcd3245c2ddf29e1ae291571e538f6090f.nq.gz
│   ├── 94f9554c076f573ffbac92d6f75358e40403ac7c.nq.gz
│   ├── 95585f3f73416509aa045b2acbf1973cc80bc3ea.nq.gz
│   ├── 9962351e4cc18fdaee0d8e22eff9e90e254498c3.nq.gz
│   ├── a8d5a6249de4d34d5ae72fb6244f5d38fed8eb64.nq.gz
│   ├── ab49ee9140a26833ec3ff492d1d0c6f0e6733f03.nq.gz
│   ├── b251a66ee7987bcd7739223d888438b97c98b2c0.nq.gz
│   ├── b499a0fe7bda124ab26c8ca61c3ea883f4c04048.nq.gz
│   ├── b61e2c113ac3b84587cbf0a582e4fc2bb5461d60.nq.gz
│   ├── bb107571e2f1158ba8abce89592a9dcd8905612c.nq.gz
│   ├── bb2064ca20721d31d974202bcfe3638050da081a.nq.gz
│   ├── bf54ee8ef64d09c655361c0359a32220aa930311.nq.gz
│   ├── c6809943bf3ba404d10ff2b070cf414d6ca34a4e.nq.gz
│   ├── d03e7d1f52bfb1b4de8ea6d0638ded55f0f4e50e.nq.gz
│   ├── d13622a5c9984b47d4c4e4eda2665b27de8cacb4.nq.gz
│   ├── d8dd1f4332e95afeb38f425688193996790706ec.nq.gz
│   ├── dad0b52094689cfde68c87886bfa5a57016a9807.nq.gz
│   ├── de7ba28149f79e51b3a62168d517afde1d589cc8.nq.gz
│   ├── df00c30915b154fa498b50a224ace90567c06333.nq.gz
│   ├── e2f6f13d7a5cce73245933e7e60bc941b1dee2fa.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e80b0ca1ab64050d8da699bbc3007e8549b85fe0.nq.gz
│   ├── ed377163f128baed49603ff98b4b25487b75b24e.nq.gz
│   ├── ed4d613ea34c582dcbb4bc8197d0e23151ee0dd8.nq.gz
│   ├── f0a4ebaf6b1d1fa17ed35d5a741f2cc3d58295ef.nq.gz
│   ├── f1659006afc958e0e9e611d16ff4e677b923df68.nq.gz
│   ├── f4ddbcdf97dfa3f6ab2ca37d204bb87bc7dae19b.nq.gz
│   ├── f5638ad86047a514ad1b3b13663f0d909c0abc4f.nq.gz
│   ├── f7ede903eef200c33acd96513932694ccb4b99d8.nq.gz
│   ├── fc93c67042f4e201cb9a0af22dac0f72d007a4a1.nq.gz
│   └── fe2141c565e6976b6a2a5b73f318ad7c6dc3d58b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 2bd5aef5bc3612b55a0ecb3c3ac47a38dfbf642c.nq.gz
├── filetree
│   └── 2bd5aef5bc3612b55a0ecb3c3ac47a38dfbf642c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 80 files
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

[kennethreitz/clint](https://github.com/kennethreitz/clint)

---
*Parsed on 2026-04-13 by [repolex](https://repolex.ai)*
