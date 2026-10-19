# Repolex Knowledge Graph of msiemens/tinydb

RDF knowledge graph data for [msiemens/tinydb](https://github.com/msiemens/tinydb), parsed by [repolex](https://repolex.ai).

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
rlex download msiemens/tinydb
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── edff96aeb2616402e9489d46e90a592c05565621
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── edff96aeb2616402e9489d46e90a592c05565621
│           └── chunk-001.nq.gz
├── blob
│   ├── 086d12abbf335a9e98fa9782fc4d9b5cd908fc61.nq.gz
│   ├── 0cd2b7eb41e4b4fa327d8b77502301526f059934.nq.gz
│   ├── 1fe622eb2da931362cecac811ef0f4a7ba123bfa.nq.gz
│   ├── 248c9153a4d4bd1c46b466e8d4858c2fa9c2f0c7.nq.gz
│   ├── 2b1a33dce95ea6eed73b9a1332dcd605bdf2355e.nq.gz
│   ├── 2e22d6c8d430284e92ae6652df5fd3a3db39488d.nq.gz
│   ├── 316191657ca6b51604e5ab522c0c78e07c893b3a.nq.gz
│   ├── 39ee08b160ac769808c82a04f3f7ccbd19af7510.nq.gz
│   ├── 3a6f814f6ac61cea8684c373a413ff5aa9f7ae0c.nq.gz
│   ├── 3f6c6ab480ecde40954f54523ed74b203fe1538e.nq.gz
│   ├── 43cad4e23e394ef702943fb181be5b67d4a67207.nq.gz
│   ├── 45e8707db03d886e6ec161802ec3d96694a4a5a7.nq.gz
│   ├── 472b7ee602d1e3f052b9897b3f3c2b173c5030d1.nq.gz
│   ├── 4a8941dd4d37353a7001784f847e105567fe1008.nq.gz
│   ├── 4c046324dfd171c61bd640815402fcd743922162.nq.gz
│   ├── 59337a1c15ca931e33a2822994dea314b5cc8ad9.nq.gz
│   ├── 611d35661f933a4469c941e6c97578c22673b4ab.nq.gz
│   ├── 66b6e4c2f3b55b25afd9716f9d3c5afb47b15d4e.nq.gz
│   ├── 6c862dc24297ff490ce628d5e6a8b22561d582ff.nq.gz
│   ├── 6e433a18ac0dba7eb0a6bfe779bbda397cf353d3.nq.gz
│   ├── 76470aa9da52323d4919325bea652492f4ae097e.nq.gz
│   ├── 7e422a1f96e0686a79e15be8859ce68433c09ad7.nq.gz
│   ├── 7e9b30593f12bc9d6ab90c6a50b5a67482b13e13.nq.gz
│   ├── 8275a28942e3ec2b850cdaae2e4e45514656291d.nq.gz
│   ├── 83d46c9905a3030f9390dd222899e44809a8922f.nq.gz
│   ├── 8daab7ee6efe3b6f3c2a2594b711e7a9026eb5e2.nq.gz
│   ├── 90b3902af1cbc6e630d0daa9e1943772b9abd533.nq.gz
│   ├── 914ce3a987431f24aac5b6d34f0694c4f8d2d269.nq.gz
│   ├── 92c07e1872d5f0817dea8ee2760998451d8d79a8.nq.gz
│   ├── 99c3eaf2505aa0da13eee34d9e0f664d9a2c8b0e.nq.gz
│   ├── 9d61f5cb29a5b2442f86b577720035d74f4380ec.nq.gz
│   ├── 9d717fad2b66c4601d781b0e785fd2844d25f0b3.nq.gz
│   ├── 9f0f1c485a41a50b6238c015c352a3e0b6b66098.nq.gz
│   ├── 9f588220b533b40db8bf0d87f5696fb4de6e4b7a.nq.gz
│   ├── 9ff866fec5df4ecec470a226e56813e5706d0e7d.nq.gz
│   ├── a542e273aca4a07bd255ddaa013d61b294e73874.nq.gz
│   ├── a94005e2de89044761e610edbad211fc957e0bf1.nq.gz
│   ├── acef56594171cd688edb388f06c69ab521092249.nq.gz
│   ├── adc735f8ab99154692d38940f66418c41dfeedab.nq.gz
│   ├── b3292bdff8ed5429eedd7f409839979d408beb6a.nq.gz
│   ├── b6c94a915f2f7c0349b7bd08ed2d8937e073f1b2.nq.gz
│   ├── ba6a6c2263a1553b794865505170b87b2d7abe79.nq.gz
│   ├── bb439ccd2e21f39c66c68f8b86cbb4d6a343cfd3.nq.gz
│   ├── c30f461b8f8ed3dad61614d7cf466d0cc37b80ad.nq.gz
│   ├── c6a151b325b25cf78938a717b8dd1b86ef5ab382.nq.gz
│   ├── c982ac35d60b8452d8705598e47cf2548cbc2479.nq.gz
│   ├── d189a4868e68847795baac7be822214f8516ba91.nq.gz
│   ├── e106c5d37429e64708f910daaaf44e360d9f601e.nq.gz
│   ├── e47d102ed8758b09adfe2cece0e668bad41c1202.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6c6f5fb1e361646fd5921a5f9459e2308977b14.nq.gz
│   ├── e939eb444d660266d8fe7c87f26fcc99f39f18c8.nq.gz
│   ├── e93c25b187bb4e0cebf896b2c18c562ebfa3cf7e.nq.gz
│   ├── ea28d1a94665b134dc2c9d1affc976a2f521773f.nq.gz
│   ├── efcb12ccf504706116c4ad8fa0a43afe0741273f.nq.gz
│   ├── f3bfe1598e9d0b28909488deed1c8dc7f302c79b.nq.gz
│   ├── f99b774dde2ec1af6751b38dc5dce6367160bd90.nq.gz
│   └── fb4444c0db2988ea556caffd9dedf1daa11e8dba.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── edff96aeb2616402e9489d46e90a592c05565621.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 66 files
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

[msiemens/tinydb](https://github.com/msiemens/tinydb)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
