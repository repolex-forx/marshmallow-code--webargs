# Repolex Knowledge Graph of marshmallow-code/webargs

RDF knowledge graph data for [marshmallow-code/webargs](https://github.com/marshmallow-code/webargs), parsed by [repolex](https://repolex.ai).

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
rlex download marshmallow-code/webargs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dd2bc377182b1094ff9330b29eba26e7a04da3d5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── dd2bc377182b1094ff9330b29eba26e7a04da3d5
│           └── chunk-001.nq.gz
├── blob
│   ├── 07915928124d50893f698841463a81f50b659b36.nq.gz
│   ├── 0ad42adc89230afc291782b0c482b1b32e92a5c6.nq.gz
│   ├── 0d7bf0fc7c4069ff5d981bfd6120263cb44412a9.nq.gz
│   ├── 0dd41b0b4d68139ece412b960348a502647957fd.nq.gz
│   ├── 1005e265973ba976766d336b6c043d066e663d6e.nq.gz
│   ├── 11be089157c4b0b30a712c0b2592f38a852e1ed7.nq.gz
│   ├── 12ab1ac261ee640252ea20bc8689bdd7f06a53da.nq.gz
│   ├── 17ef95bb96fdbfbd4e6f13ef76800921890f77fe.nq.gz
│   ├── 1907ba5e30053f5669bc35cc35fba6beb6d5db75.nq.gz
│   ├── 1b0c73d83f3721c60d828c5cfa1e56c95d59a1fb.nq.gz
│   ├── 1c05ef3eb56b232ecf7a1b56121f4aa78d95e3ff.nq.gz
│   ├── 1c7c96b89989248a564484f290a00d221b3c38e9.nq.gz
│   ├── 2008720553c3e6ab1ce6e32a63614264e1b09fc9.nq.gz
│   ├── 249a81252515358e54961045537a5b09120fd6a2.nq.gz
│   ├── 278c4fa1b5a5e893db37aece739df6021828df54.nq.gz
│   ├── 2998730f68ea8f9d0e4fa2e1285107335e140aec.nq.gz
│   ├── 2b4476477fe314cdf9e221f94cecc0727f32d8c9.nq.gz
│   ├── 2bc89551bb2530eb08b81edd3a6b56ff95d8ac81.nq.gz
│   ├── 2d67ca415127f3b3f7119acd65b602da7a85bcaf.nq.gz
│   ├── 3b15fa9ed9b2bc16942b20aa7938c764a65c308b.nq.gz
│   ├── 43d0b4115a7fcc5835f2b0f04e6f7ade72900c39.nq.gz
│   ├── 4839a61af0aad904e3a8185b443de7742975ad43.nq.gz
│   ├── 4d0125f7d59b55ae2cbf11c7508bb8051e1f11b5.nq.gz
│   ├── 50ea24fc7d848f6a93e654e292227fcb7f33030b.nq.gz
│   ├── 526b0777334d6eeb2fe5629d87ca12b1555b9b81.nq.gz
│   ├── 5335ee70a38e5e57c6dce5c6c6b0527d455d0d29.nq.gz
│   ├── 55d1dac882dd023618a5d45aebef06a41cf6e35d.nq.gz
│   ├── 565b0521d0c2cdbfe493d19765b04d5c119fa7eb.nq.gz
│   ├── 56c27365aa45be81ee052ca12a6aae5d7e48a8c0.nq.gz
│   ├── 62746f0d05d54d67249d2a735deb496263e3b97c.nq.gz
│   ├── 67ddcccf69f632d7d37747921a8fbeb05a72277f.nq.gz
│   ├── 6c1a43aacf5dae8205cc9dc29a28e385273d20bf.nq.gz
│   ├── 6c78568560c6e985784f6dbe53c22084f7335d1b.nq.gz
│   ├── 6e9e8c421b6a10252bff4be2ac29d3d762142a70.nq.gz
│   ├── 73b6059e967317382381e860392166a5213a8f64.nq.gz
│   ├── 7633e1cfd41c9a6c59b9edd13e03ea6c6ec77110.nq.gz
│   ├── 774e1b9a21d7aad7e11cb92d3b483988113bc85e.nq.gz
│   ├── 7be539d1f10f7d42eb51e2b59d4402aff4d80d41.nq.gz
│   ├── 7c8b6f22c1c1828bb39bebc9422897ecbd2a922f.nq.gz
│   ├── 7e291a183b32af5a783ba6f1ed17d195aa21a576.nq.gz
│   ├── 80361b5b020a76f11201fe82e60962376c6478e5.nq.gz
│   ├── 80b9c9c5b5ae39fedddeef9f1257b0ba47b4dc2c.nq.gz
│   ├── 866cde44a585bd10bf4bc3c288aec12e9f93fa55.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8e3cef9821fe66cd24847b26e808945f680d0ae0.nq.gz
│   ├── 905ce181025076e9f64340eb7dee180c82d3a788.nq.gz
│   ├── 92ec2bb600a1e1f3ad8666d355b485b696332790.nq.gz
│   ├── 96a4516e69837e413a8edb8b1720b25e93da3622.nq.gz
│   ├── 979baf571d0cca9ac1f86e949aad2214d99a5e06.nq.gz
│   ├── 984e208bf6b2e31dfc53b1fc7c542b194caf3adb.nq.gz
│   ├── 9924c4a7c3da2862862c498a8596b7bd834a5d62.nq.gz
│   ├── 9b62eb6209c6b0d01b0c3db1416f3d5f927e5ca8.nq.gz
│   ├── a2bf7af71e9f5f1db4c6e65c548f9a5a2b6d27cf.nq.gz
│   ├── a3714e7c73bf68aeb0f57bf297a3145f3184fdad.nq.gz
│   ├── a3a56410a84425a9f3a54a046ee88da76347112c.nq.gz
│   ├── ac13df4cab795ab3fdde12693bca0f311acfc259.nq.gz
│   ├── ae5104a69266f0cd4249bc933b56532fe13a7982.nq.gz
│   ├── b20df7cab259cfce3d02bd8da515ce65870612b7.nq.gz
│   ├── b2465ca616914f900037893218e12ebb8713b830.nq.gz
│   ├── b2dbfc185f4efd23a61d68ccf74bdcd63d1a7254.nq.gz
│   ├── b382e5041044147ee50dbfbe935d8a9654790f7a.nq.gz
│   ├── b93c34a5d30880e3c47cff02adeedc8dbac08b2f.nq.gz
│   ├── cc3719a6a30a5f022c439a7a2069e6353f938d2e.nq.gz
│   ├── de9b82bb1ad07fcda0c14c8a07480ed6cc871023.nq.gz
│   ├── df3849a6ea07e41c2a50c8c46396cca58483c885.nq.gz
│   ├── e16d0379b3237a663647997738542f8f0dc0866e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ee92eaddeecf525b39ca987d3d0713d755578d4a.nq.gz
│   ├── f10a2e4a9c5468a750e665591e0a34b70ff4ad5d.nq.gz
│   ├── f40ce91be5fa3ae6afbf5457462f0d87000e4f1b.nq.gz
│   ├── f487ea23ed88f02bccd44e87f7f51fe6691c4eb8.nq.gz
│   ├── f496114feb4eb74adcb109a1f107f58528699c6a.nq.gz
│   ├── f8810057ddef6e0cbefcb06b95ec502ee368c053.nq.gz
│   ├── fb8577cc102728fda76a5d0b59597dff718b3d7c.nq.gz
│   └── fd3fedb4246a388d84078f5c9df34ba936a709a4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── dd2bc377182b1094ff9330b29eba26e7a04da3d5.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 83 files
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

[marshmallow-code/webargs](https://github.com/marshmallow-code/webargs)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
