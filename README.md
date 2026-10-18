# Repolex Knowledge Graph of Yubico/python-fido2

RDF knowledge graph data for [Yubico/python-fido2](https://github.com/Yubico/python-fido2), parsed by [repolex](https://repolex.ai).

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
rlex download Yubico/python-fido2
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 57dfac9182be4c5ab577bfde2f66dc520d69e763
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 57dfac9182be4c5ab577bfde2f66dc520d69e763
│           └── chunk-001.nq.gz
├── blob
│   ├── 04a261de4c977d7775f2bb1f8a7a0890ca4e869f.nq.gz
│   ├── 08b65ee3e0e175bdbf76725379ed4091a53d2b9a.nq.gz
│   ├── 0a187934da6bc546370649f066b57e98b9ecd0b7.nq.gz
│   ├── 0b67a95ea495c2d060a0582bc2ad97631262d2ea.nq.gz
│   ├── 0c4e1734ead7f94a99398878020b238a40bc40d0.nq.gz
│   ├── 0c669e055c9f400e63d4debeaa79cea5ccc75499.nq.gz
│   ├── 10ec9c1ccbfba635f26f05be56f115834547ca33.nq.gz
│   ├── 1353ec1f2d9e148726c35a1279618ddfbe149756.nq.gz
│   ├── 13fa77beaefb874ba03e8fe9cead119d6f55b461.nq.gz
│   ├── 143d1ac759a7c559d6506b52cd52ba6f635a5b38.nq.gz
│   ├── 14e2f777f6c395e7e04ab4aa306bbcc4b0c1120e.nq.gz
│   ├── 156f51489ce0b18abf9c22c683954755f938dc29.nq.gz
│   ├── 165ab30171d8371caa13600354bfe934792d15b7.nq.gz
│   ├── 18405a7bd58c6a3068e95bdf5c57d0434db4cfed.nq.gz
│   ├── 19bbdb89c8589db5c9789be0ff5bf17628c16160.nq.gz
│   ├── 1cf38ef6cfe7169ec6aabb432983a564380d1f87.nq.gz
│   ├── 1eca38b5174fdd4b43612cd5e639dca5b06299d9.nq.gz
│   ├── 20967ebf58686c9bc4c562cc07e59d91952d57e6.nq.gz
│   ├── 209ad5d533f31be9d36ae97ab03a4f0a6f6b931c.nq.gz
│   ├── 2136726d7705d324a60466cd0c0507d93a0868b6.nq.gz
│   ├── 2390d8c809eea1d6587357cdad25ed4af134db32.nq.gz
│   ├── 239cdc69808b6cfe04dc9948ba472e809568db0a.nq.gz
│   ├── 23fa86aeee5a2510c39ecfef0ebdf4759a6874ce.nq.gz
│   ├── 2457a4027b74470ec40a05a731bd51dd93d4e95d.nq.gz
│   ├── 29173b4606b58027f65238d5fe5ff262908e6293.nq.gz
│   ├── 2b803e355988cc76af27b65e527e566f6da12c38.nq.gz
│   ├── 2cf1fae4d41cb9911681efc6e8f1806b0b8bc033.nq.gz
│   ├── 32bb24529f92346af26219baed295b7488b77534.nq.gz
│   ├── 32ed2b05574412be7b3f761dbc6491b438558fce.nq.gz
│   ├── 3387c9ce8ed41207ece8e8e6aafc739d8b84b2b4.nq.gz
│   ├── 34d20d3d4a211ce801c4246e1ce4cc8ace4dd0c5.nq.gz
│   ├── 3d28a5140c5e705684d03556ef128095f1ca401b.nq.gz
│   ├── 3f23b930ff51c7c78525030c8e92107e029ab19f.nq.gz
│   ├── 41d34b1def0ef7bbf5de1177353888a340742682.nq.gz
│   ├── 4618c01e85a24048cc83f7a5537a2dd3e5ef0316.nq.gz
│   ├── 46ea67faa3f4369eb3a4d5fb1743256557ee76b4.nq.gz
│   ├── 47e68dc75e27d4c6eca219c49469a4342639b5b4.nq.gz
│   ├── 489180c2ca88cb2cd340155def287a57191f8d03.nq.gz
│   ├── 4b688cfe1ac0e38d09e5e025c19c61d87ef2068b.nq.gz
│   ├── 547b986b300842d991c6bead3cb7a64167dc9a6a.nq.gz
│   ├── 5527f51abb4c9590d51500ef4bab1b82ff4a5247.nq.gz
│   ├── 55553f5932ca82c238208f774e6a1f20643d6386.nq.gz
│   ├── 55a4b9d8f198cc8b3f15324cdd04e1d06981e972.nq.gz
│   ├── 563a46e76d2990a95c2ad94ebfaa4704a0370c53.nq.gz
│   ├── 593bb01978fa2abb9e466f63fdd6ca7948cf9d0f.nq.gz
│   ├── 59552adb4230d878dc47e8632e96f8777f3796d8.nq.gz
│   ├── 5abfca42dca6eca33958f5ce5c2faa3679c7f16d.nq.gz
│   ├── 5c712ec3403866611c58eac1e7d682663e005f9a.nq.gz
│   ├── 5e37b292e658f837a9fd4e64c6c96d62c02724a6.nq.gz
│   ├── 5f0e8383240fbc5671d294beff3e28024d876dc5.nq.gz
│   ├── 61a8385070c2a0579e6fed691f2afb8f468c26c0.nq.gz
│   ├── 61f8f45d37ec470b04670de3c670c91811b018f3.nq.gz
│   ├── 621bef93152bd8fd5044a88324426bc51499d52f.nq.gz
│   ├── 628b69c347253002b8c9018897283ecebe3b2c68.nq.gz
│   ├── 6645928098bbf4f6429e326628027bda08fd037d.nq.gz
│   ├── 6d548e79b83f591156ae551899960078fe864696.nq.gz
│   ├── 6d59a7a8cb7955f1e76b2e31c991f098e3947268.nq.gz
│   ├── 6de1b69332560423ce284a55af9934574fa0e2b4.nq.gz
│   ├── 72a1bf26d18da9008b139fb4831db158a54a5023.nq.gz
│   ├── 72b4b3cf44501b3f231e65eceeb78de0c930105c.nq.gz
│   ├── 732b659898edfc17b721011b2ed87b41f9677147.nq.gz
│   ├── 7574056eab75b928f53d2f7c4b059dcc2a144649.nq.gz
│   ├── 78ed52f0b165db2d11d225fd24b56412cc51f7c2.nq.gz
│   ├── 795559ddf622b9995d91b27c2edb1a4d1ba03db3.nq.gz
│   ├── 7974c6a41db7c6f42572deaf202197dc3523a4b8.nq.gz
│   ├── 80e7eb438e816ae50ba6e3067a2431d3010254ff.nq.gz
│   ├── 81ff61461f3a3a9ba3bfa10a421fc9ae337d59b0.nq.gz
│   ├── 84ee136e4d11f75209cca829e87e4dd9843b235f.nq.gz
│   ├── 850f57d043ef9d421e422e189b62637baadcef2f.nq.gz
│   ├── 86752aa668d16277d6eccc29c5a8afe384af2b30.nq.gz
│   ├── 8713d8bd72926edb9c5ddc278b15ca498ae9bb1c.nq.gz
│   ├── 882d39f6a543c807d3385769f819f845676543a8.nq.gz
│   ├── 8855f6b8049a4dbb1303e361417c065705cd052e.nq.gz
│   ├── 8e6c4ea4fd2632b3037d0a1268bce948a7ab0c7f.nq.gz
│   ├── 96fe1352fb2a8ad5d734933f75c5320c8ee2af6a.nq.gz
│   ├── 995d0a1484a915e293da2035f633476c8801682e.nq.gz
│   ├── 9a6f6459118c23df76b038ceb23e31aabd3088d7.nq.gz
│   ├── 9b726a35476f4b7f50de64226c6a361cb214b350.nq.gz
│   ├── a00732e50164af4c1e6f8ade4992193acdc60035.nq.gz
│   ├── a46e5482e951d9a38b94779f663e52688a77c848.nq.gz
│   ├── a6c6ecb7096eb31aab2ae16793c2dc4f6f869f0f.nq.gz
│   ├── a91376b3fd796036490919311d3f638f77b1e6de.nq.gz
│   ├── a917b20d248cb40904486e32849e203d4b65081e.nq.gz
│   ├── ac8e97263664adfd88aa8c28d0805b5a50eb5b4f.nq.gz
│   ├── b4c91e20e9f3bdcc602c377ca06704416732303e.nq.gz
│   ├── babbba3a66583632f0c9686a672068a596fdfea4.nq.gz
│   ├── bc3edbad5d1a543e2bcd9e2dfdacebb27609fb0b.nq.gz
│   ├── bc78bf6bbe0b74546f77ce93625d1a3dc6859d9b.nq.gz
│   ├── c3c7ebd2bcdbeefc2b723a2d20d69ac922680f88.nq.gz
│   ├── c4721fd3e78cf1469d3f4ff63958dbe1a31abf31.nq.gz
│   ├── c4caac464e82218c3954e76084ee73604faddcb0.nq.gz
│   ├── c7194ccf49a6225cfb8eaf0004c4bf6949009ab2.nq.gz
│   ├── c8bd80e62edc6c3b4399aefaba41c24188dad1f2.nq.gz
│   ├── cf0039685e1a5d5603fb828beb50e37dbad9cb80.nq.gz
│   ├── d0afcc0c659d69e95d930d38455027a00007ce7b.nq.gz
│   ├── d381c4b8302e381a29c4291d94562ee22ae10b4f.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d6d6304d36ae6c9e524f4ab882b3f1e3dc3d0503.nq.gz
│   ├── dbf8dbba501f8d7921403d7ca20e8bab01ec4b43.nq.gz
│   ├── dc19fb3c38c2bdd8141f9edf72cb0af7a78ffb41.nq.gz
│   ├── dc7d6f73af5cf896a554874a6296c59792a6b4a7.nq.gz
│   ├── e108e21a696c6737639524153547b053689e4bf3.nq.gz
│   ├── e2e90dbe514c71a6e638553a463baca03da76da2.nq.gz
│   ├── e497aab458e86768577b05e4f39daff4c8fca902.nq.gz
│   ├── e4b2fea7a225d48293eff4a91f95040b211a5afd.nq.gz
│   ├── e4cbc71c530704e309a53decb2b10a9c35076216.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e82cf44b050bfbb2a246f26bfdda75d21b738aff.nq.gz
│   ├── ea209d2a00f01ce9e2adaacaf8728798c6527f26.nq.gz
│   ├── ec276df41fb254161cae959c265e179999778e70.nq.gz
│   ├── ef7d5f4d191c688a11b6c2c2e5ae8e7e2bd8f06a.nq.gz
│   ├── f1897a1f54008f55693332ae45b6240071450ae5.nq.gz
│   ├── f1da7a4026d57fe3eb7e4e4474289d5714864fbb.nq.gz
│   ├── f4befb89f1a2bc04456e60cceb4ef9d9467872ca.nq.gz
│   ├── f5574386e1249a2ac23c09a16a143a4109a59d14.nq.gz
│   ├── f931f72f2b08999fe123f8c26ceb23d5aa25957e.nq.gz
│   └── fbbf503d9334bffb64eed871b2bf682e4ebbd202.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 57dfac9182be4c5ab577bfde2f66dc520d69e763.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 126 files
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

[Yubico/python-fido2](https://github.com/Yubico/python-fido2)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
