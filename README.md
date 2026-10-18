# Repolex Knowledge Graph of sloria/doitlive

RDF knowledge graph data for [sloria/doitlive](https://github.com/sloria/doitlive), parsed by [repolex](https://repolex.ai).

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
rlex download sloria/doitlive
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b2e1ee834e8915dbad8b31f9f03ff533198cdf78
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b2e1ee834e8915dbad8b31f9f03ff533198cdf78
│           └── chunk-001.nq.gz
├── blob
│   ├── 01598548c9eb601d6c7135a30a94787824ced9f0.nq.gz
│   ├── 015a7f571ded34848487fe212608fae33d6509b8.nq.gz
│   ├── 0430144205b71141ff3eff1f4733bafbe665bd75.nq.gz
│   ├── 04613d6661bd6ef95bbcabad406c1e72391845c9.nq.gz
│   ├── 0681eed55b20a7e4d670d3a86b9df7b18ebd0b8f.nq.gz
│   ├── 08c0d19b3adf30d5cb83c70bd253f1b77751f3d5.nq.gz
│   ├── 097020f4ef3555eb6270ef544eed955dae2f3a41.nq.gz
│   ├── 0b9a76c368dd2dbd5e475e3db22ecdd87915577e.nq.gz
│   ├── 0ff09fffb6796444b432a4ed6fcc8132a9f3c8e0.nq.gz
│   ├── 1005e265973ba976766d336b6c043d066e663d6e.nq.gz
│   ├── 13940489fef708f0bc3b0ac295ed3de199702f06.nq.gz
│   ├── 235eaef79264cb8dd9f56dcf549f4dedbb947b46.nq.gz
│   ├── 2499942188f14a0569790f240e0d3ca38ac69a3b.nq.gz
│   ├── 27968aa7287d91cb2c7fcb113918ab265861d149.nq.gz
│   ├── 2b4476477fe314cdf9e221f94cecc0727f32d8c9.nq.gz
│   ├── 3e86daff56e93738134b0e560c631c491bae10d3.nq.gz
│   ├── 3fb149f82d557758a22718c456f579500245d038.nq.gz
│   ├── 41650843e6f4edcaef5691ccd9aaacd262082a8d.nq.gz
│   ├── 437db04f6d86515604b194b7271def8fab3578f9.nq.gz
│   ├── 4bab2023b15e914a0d80f4fe19037f52be345354.nq.gz
│   ├── 50cc8146a7657bc2326c5b8572e61945a7cb3a61.nq.gz
│   ├── 5939c96bb92ed52a16994da0365a9163d7a93b7b.nq.gz
│   ├── 5a90816b44b7d49489ccf569d1c39ef55e903fb8.nq.gz
│   ├── 5c5de04989217ace1ba9d53c940d4f0b117143b2.nq.gz
│   ├── 5d6e4b83033ad0333a7a4f31edb3460115e50f6c.nq.gz
│   ├── 602e6b8565021d694b738007cb115081d238a95b.nq.gz
│   ├── 60a962f198557cd578ca1a1a4a2fa1479ac318f4.nq.gz
│   ├── 64e249963b3af1a2c7db7c323f7add378b188fe8.nq.gz
│   ├── 66cdcbd92285a7e3ab7be3adc1298f309f99d442.nq.gz
│   ├── 72abbff05a0ce272dbaffed38b157cbad913d82f.nq.gz
│   ├── 765df719bbdebc1984ec1e3c595e9b62b0e79aff.nq.gz
│   ├── 76888fe1bf10912f9575845efabb510921743065.nq.gz
│   ├── 7d17dbf1cdaad53d779f13e1243fd7108cb56582.nq.gz
│   ├── 8078ed5541faed249f08ab83e689daed67c1757d.nq.gz
│   ├── 918189eae6279165c41cea753e188fb1344906df.nq.gz
│   ├── 94415f49d8150679c64f55319cae2998a2d9a9cd.nq.gz
│   ├── 944a1df753a486a6ec98fcf12d86ff4041d8959e.nq.gz
│   ├── 9b331bd58dd12993c217c87d6572030a766fe2fc.nq.gz
│   ├── a110e4caef5bb1ea47049d9b05f0fb44ef3b4ae4.nq.gz
│   ├── a33d5d02a959c064731ac393ef82bf9756065131.nq.gz
│   ├── a355944a8b882f6b05d8a908cdca6e25e4e821fe.nq.gz
│   ├── a6b0d71e5029c4e55815accbb8342e7af35457da.nq.gz
│   ├── a79188ce70fa296bbce58044bf7b814ac421836b.nq.gz
│   ├── ac9bff6f9d6baf7f018761ddc150ecf205c0e205.nq.gz
│   ├── b20df7cab259cfce3d02bd8da515ce65870612b7.nq.gz
│   ├── b37e891ef7f89b2b961d1c9bbbb0bb83965a1303.nq.gz
│   ├── b9f4ef3bd112b40e818b3c7c088257743d1275d2.nq.gz
│   ├── bcf2541f63714d021d769b005b2cabe3f563c948.nq.gz
│   ├── bd019c432785a53ab5cc3c64fd663266b7018ab3.nq.gz
│   ├── c1de11815cc58764ed42dcc6bbd189c23c682a02.nq.gz
│   ├── cb859a4703629dbdb8f93dae68979de3a23d09ae.nq.gz
│   ├── cefc469ba7e032231f818103333f766891c02b54.nq.gz
│   ├── d330fb36d3dfda71d0c4386f7ebb77e901805dd1.nq.gz
│   ├── d7faa4109cefe74c48face597f2e834de8c086cc.nq.gz
│   ├── d8f288bbe5dff29279eaa031579d4093c0ea13e5.nq.gz
│   ├── de827b199a0edca948269dcd2633fabf163378ce.nq.gz
│   ├── e122f914a87b277e565fc9567af1a7545ec9872b.nq.gz
│   ├── e33d9978e91c3867017573f57dc3374fe6774b66.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e889801cd3f1b6a8eed5080382d111c438a54974.nq.gz
│   ├── ea97bc0d377daa135c096b61e4dfce49f3f707b3.nq.gz
│   ├── f748bdd051994e9fa832a7bd7b4fc59ef5e99cbe.nq.gz
│   ├── f80d71102a4187a6591e8a3307e3ccf1521c6d8d.nq.gz
│   └── fa07e9e9a0a642238290e1e531c015e7134401fa.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b2e1ee834e8915dbad8b31f9f03ff533198cdf78.nq.gz
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

[sloria/doitlive](https://github.com/sloria/doitlive)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
