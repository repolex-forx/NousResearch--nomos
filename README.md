# Repolex Knowledge Graph of NousResearch/nomos

RDF knowledge graph data for [NousResearch/nomos](https://github.com/NousResearch/nomos), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/nomos
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f7008a065072d11088878e2f499776a5ae4b5c95
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── f7008a065072d11088878e2f499776a5ae4b5c95.nq.gz
│   └── repolex
│       └── f7008a065072d11088878e2f499776a5ae4b5c95
│           └── chunk-001.nq.gz
├── blob
│   ├── 00883f0ef85883081af5d96ad14068f90e3fae7d.nq.gz
│   ├── 01fcf06608ffece02cf294fecafcd4c5152669d4.nq.gz
│   ├── 0259e4661e3bdc823c766af6e20229add9e1afe1.nq.gz
│   ├── 030ee4a175c21739e43e63b5ed25ba776a6597ef.nq.gz
│   ├── 031de61866b51390a2b22691c228070bd33e3859.nq.gz
│   ├── 03fa4d27f3c4e814eb919be69b0631405f0c473f.nq.gz
│   ├── 0536ec5a94f487939fdfb2a2088674e91b8c8638.nq.gz
│   ├── 0a7a7c86dcf8f8401ac2668bb8bbb815ae284412.nq.gz
│   ├── 0b55bbb7271aaba23776fc30e27a786e60d83735.nq.gz
│   ├── 0cb292f0ed354eea1ec387c494bc111c4ecf9647.nq.gz
│   ├── 0e6c68512dd6d0fa27a1f5cf988f1603ad6583e8.nq.gz
│   ├── 110026e229da56f71f9e43b6f936818b60bbe0e2.nq.gz
│   ├── 194d88d90acb813d5f26a9fb31b112e5ed154e7b.nq.gz
│   ├── 1a69bc0c8caa51a40a72fba02cd57c6085001a4b.nq.gz
│   ├── 1b85593047f18785cae505fc532b4da3c5cc2c66.nq.gz
│   ├── 1c621ad8a7d50d44b22dc7c59fe8d7243726b132.nq.gz
│   ├── 1ef325f1b111266a6b26e0196871bd78baa8c2f3.nq.gz
│   ├── 1fb06aaea5d5bdb6f6d055bc711f1e8460af42b0.nq.gz
│   ├── 1fbf956ba776a5ac8ef0cf746cb8f10146fb72f7.nq.gz
│   ├── 22314384447ab337e1b306734b1d8e0b94e086bd.nq.gz
│   ├── 232c5bb09c76c1f65accb3455701f6c1e66a17bb.nq.gz
│   ├── 236d7a4bfcf9fd8d42eeddb74fadfee997cfb43b.nq.gz
│   ├── 27ff81fe8a5f334df9aa29282e27b0cca5092c9e.nq.gz
│   ├── 28480a0e8385948f0909e08d8290c63492801834.nq.gz
│   ├── 2c1ac946e131eeed8e7337429b3c228e16f04a11.nq.gz
│   ├── 2d8b551b6cc5137d45333123d1cccf81e43c6dff.nq.gz
│   ├── 2ea36bb55866f2481b86e9a60b9fae6dd9232914.nq.gz
│   ├── 2f377887f1be19da388a32dd73b30894645c6e9d.nq.gz
│   ├── 3d4a68a6bf618a8ff88b3ef59c3fdd1810aaf85f.nq.gz
│   ├── 3f5715fae75028ebf427b32db34e080184d14498.nq.gz
│   ├── 3fe8bb2ebaa5dd460dac08ba2e39094b00766ce2.nq.gz
│   ├── 47297c26706210a974e7499f132a1c65545f066f.nq.gz
│   ├── 47a366d03790f4ecd09e06559356e2f3915c35b1.nq.gz
│   ├── 48850890b76cf8347b666e7a84f7218321b15bc5.nq.gz
│   ├── 4be31d5127a793c16793681dc45fc5dc7a3c44a2.nq.gz
│   ├── 4d9cf1cbbde314d645725674571f4522bed3ee00.nq.gz
│   ├── 4e4d012fcdbb02375038d7b4e8f49ab01a455f03.nq.gz
│   ├── 512e7743f1143f5bbfe62f5330cfb9ed5964702f.nq.gz
│   ├── 55102a84d7bfdffa64bd3df70c7017d10d637d28.nq.gz
│   ├── 57ca3064a03c0c8d49fcbb42075dc4e42b7cc7b1.nq.gz
│   ├── 58fff881c252990b9a80af9d7d28d6ea8ad05280.nq.gz
│   ├── 62077463c382389a72f8aa63c837abb8d6ae0db2.nq.gz
│   ├── 63d6682971672a2f88a8f182b0aba3f5eb75e952.nq.gz
│   ├── 65665c24f1d59c61d29b984dbc50149ea8f00fac.nq.gz
│   ├── 66db334b500c39280c6c5cbde3c951c8d394225f.nq.gz
│   ├── 67b916c0c6ca6b518819131229104c4cd119a50a.nq.gz
│   ├── 683a013435549860d1966d090361f1cfd40a8580.nq.gz
│   ├── 687909c996389d21e8ee3b1c4b8ed8d66c6bd800.nq.gz
│   ├── 6d12ad2b7c24a5c6f800f02c5dfadf0656b42a2d.nq.gz
│   ├── 6dd8cdd8eb517dc3595cf216ca12436846369799.nq.gz
│   ├── 6e5972b370b4c7035c4e82408285430cbf8df108.nq.gz
│   ├── 702a90bdce5ed4d8b2b1b674e7db939e59157eff.nq.gz
│   ├── 7201c629cd004f87bcbf98b4f092ed2db370328c.nq.gz
│   ├── 7430de302dbb195d5f26bb1dfbee7d6f927b971a.nq.gz
│   ├── 75410e73319c72cd3e991a501c5455eb78f38375.nq.gz
│   ├── 777e5dce0a82e9d8db47d09a13ccfa339011af61.nq.gz
│   ├── 7ffc382174a29435cabd17e5c7ffe0f36e8d90e6.nq.gz
│   ├── 804d61726af7a763d6f76967026e109acaf67d8f.nq.gz
│   ├── 83e654437d72be290365911b7f30befa8ee54229.nq.gz
│   ├── 859dcf32125d984fd8a76a04023bad53c96412e1.nq.gz
│   ├── 89cfb76e3cc2de0383b7cb978a59975775636bf6.nq.gz
│   ├── 8cb94780f8806142f459c0dcbe7ae99137cfb265.nq.gz
│   ├── 9181df3cabec104526bdfcc81dceb19fd8cdfc30.nq.gz
│   ├── 953b974d300a80135a41b1b73fc31ad4eaaa1dfb.nq.gz
│   ├── 986bf8203f881f8a6bc9154e1374ea531d524eb6.nq.gz
│   ├── 990cd3510a089a15759acb2867298c79b1d640d6.nq.gz
│   ├── 9bf42398f1b60bb780ecc9b95fab94fbcccc1e9a.nq.gz
│   ├── a4078f008cc5d26848710de1af440121d3846141.nq.gz
│   ├── a4ed1564f56e11351f84170ae71ea692b50c3858.nq.gz
│   ├── a775d85fe3c0f4cd2bfab73b1ba047141a51651f.nq.gz
│   ├── af9c3cd67920e37f4f69bc8e7314212d00c9f053.nq.gz
│   ├── b03432a7285bfb8edde5750bb02428a6b5df1461.nq.gz
│   ├── b046eecf66797d36164a8de651c28e1a3d841e2b.nq.gz
│   ├── b07b09c08afea8b660864f4a603c3c186f2b4026.nq.gz
│   ├── b23881b47d47cfd4c71e9511a31c77002809ecab.nq.gz
│   ├── b620ad8765eead8ec75d852d8b876701959c353c.nq.gz
│   ├── ba622cf69075cf43d582bd7d615e5581bd5a9d9d.nq.gz
│   ├── bb4029fba86915dd219dac030cecf8228cb43d60.nq.gz
│   ├── bd9d05984ba0205cc59840288002f2df0196cfcd.nq.gz
│   ├── bdd2698d81f122e935e2eb310c8130b0402c7f46.nq.gz
│   ├── be97fcef45e86f7e5e5058efccd514fd8fe47311.nq.gz
│   ├── bed5e195f6892b28cef6f44697d50c81b9f5bbf5.nq.gz
│   ├── c0538d700f9ba85fcb3112043b40d61987e86f9f.nq.gz
│   ├── c3af44b0022aa6b5011d74c008e635b0065bcd58.nq.gz
│   ├── c4f98d691bea5f0b71c765f3416a8f7f1a198059.nq.gz
│   ├── c516f52f3f873b5f13c360048a7a7e5e0ec4890e.nq.gz
│   ├── c6df8c82a3dfce5fdcf85f2b4200ce7d53f4ce96.nq.gz
│   ├── c77eecd115eef2be4ee52bb26e587c2bfb53cffb.nq.gz
│   ├── c9c91fa853d33772273d238bfbc65e5481901cf1.nq.gz
│   ├── cd42e279e3687f82d0bd72d09298ec8e966128c1.nq.gz
│   ├── ce5402017f07b3de9feb78c130f8b1fb6e00b26a.nq.gz
│   ├── d1a20d8c08cb9cc90f55ee19b3a2543c75e8e86e.nq.gz
│   ├── d2f535fe71c6bbd441185ba14c864d24946c842e.nq.gz
│   ├── dc3931e9765e25dc664c48c0c55be261b1dd0445.nq.gz
│   ├── df20494d89f37359ac41060f1dc64f53216477b6.nq.gz
│   ├── df572bde3d6e3af234618accffd1a2bc4ff066d9.nq.gz
│   ├── e2f48a8ea8e4fffb6ddd8c69aea423b122bb6038.nq.gz
│   ├── e30d9c074287fc702f3d7a4fa53cf0dcf9ac0616.nq.gz
│   ├── e5b726dc3c33c61df1f9f0a834594f11697019d5.nq.gz
│   ├── e7021f03edb889386deb606bed14159fd80bb32f.nq.gz
│   ├── e7c687eb26bde236f46652ba52771cb6b86ad4a7.nq.gz
│   ├── ebd8cd7163688a7fca8ed49098e808fb10bf438a.nq.gz
│   ├── ee52e8b11517e2c84f1957a2d41bd981ef20d854.nq.gz
│   ├── ef27d5e4608bc8a2a3e5688b2a038024ddd8f38b.nq.gz
│   ├── f5273087f490f7c88eed6506e45ba635af99ea9c.nq.gz
│   ├── fa5a4a822282128a1831e4fd72f545aeb5470e3b.nq.gz
│   ├── fb89eff961b5d2619ece696c08e571fbf0b90323.nq.gz
│   └── fca561c59a99f5696c3d04f1ffa09c70106f7771.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── f7008a065072d11088878e2f499776a5ae4b5c95.nq.gz
├── filetree
│   └── f7008a065072d11088878e2f499776a5ae4b5c95.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 118 files
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

[NousResearch/nomos](https://github.com/NousResearch/nomos)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
