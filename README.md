# Repolex Knowledge Graph of scverse/scvi-tools

RDF knowledge graph data for [scverse/scvi-tools](https://github.com/scverse/scvi-tools), parsed by [repolex](https://repolex.ai).

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
rlex download scverse/scvi-tools
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a83b4d09c20c6e1ab32633138014e9b9755cc488
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a83b4d09c20c6e1ab32633138014e9b9755cc488
│           └── chunk-001.nq.gz
└── blob
    ├── 0010d959e95765d3a27069584436b8ecaf229ec3.nq.gz
    ├── 019587f5754767a0c964a7c7fff519eb2082a94e.nq.gz
    ├── 01d782d7a902b1d182fb08297e654ada337566a3.nq.gz
    ├── 0221293b4ac676106e90081b9dc2b5491c2b58c5.nq.gz
    ├── 02a5d80309d9152551d84f7584e14257eb50f869.nq.gz
    ├── 03ade252231a6d258ecc41961759f012494759e6.nq.gz
    ├── 03b668d89e44e38e9f8ce50df33e452b4516097a.nq.gz
    ├── 0431123ebcce180205fd45e0090922e416a26e11.nq.gz
    ├── 04cdfab65a8407548bd947fdf19c2d2d3b94ea96.nq.gz
    ├── 058da9ea627e926ceeae4f5d35be41aed14b256b.nq.gz
    ├── 06c064109ec5b264d59657eb13f42b1ec5ddeb20.nq.gz
    ├── 07d521a792f7bc87cc891e8658bff134c1d68d45.nq.gz
    ├── 0897c37dd74add040c03d9fbdcaeedd2df5fd4fe.nq.gz
    ├── 090cd7311d707471e2f10b904a1b43178752dc69.nq.gz
    ├── 0958a43120a0c4c9b84c0fab4b45b44eb875089d.nq.gz
    ├── 09ab91aeaaaeda9d8b17916925877c9d1f328352.nq.gz
    ├── 0a0965d43a18477ba7de1c4cbd7298c079c09374.nq.gz
    ├── 0a1d641d268cc1644cda02237619c15fd86b153e.nq.gz
    ├── 0a390d88370dae323ebb11b065a765423df9b2e3.nq.gz
    ├── 0a58d6522529e54e9448ad3e4f0e4b9ad2b56a1d.nq.gz
    ├── 0ae6ac0fe97977061372383d94b3a2145bb420eb.nq.gz
    ├── 0c0ccc7381f327719da613b1791fc4b4aa3f7ce3.nq.gz
    ├── 0d3f38c57e09b720363dd17764d96422db6e9e77.nq.gz
    ├── 0d8401196abd2007aa0e56acc183f4881d471327.nq.gz
    ├── 0e1a4fccae39e2eb30b1eb99c5ef3d2d1884e7cc.nq.gz
    ├── 0e83ab5bf598f1d4ac46f2f69882cb7b79c08b63.nq.gz
    ├── 0f419d3a6d38a9b164bf310a4c20d80b3d2c61e2.nq.gz
    ├── 0f87573585bee1a35b18e481ad4f84269e388979.nq.gz
    ├── 0f89a1b04e9642b4b3644c9050ae434798f6663c.nq.gz
    ├── 0fa23f221e4b3e76f3f7993fa5093a3032e9129c.nq.gz
    ├── 0fa467258ae513f1701ca92fc0678094d97647b2.nq.gz
    ├── 0faf36691586a0186d0d50b1d7b1fd311fc11c72.nq.gz
    ├── 0fb87e23b62fe1296b13aa8d1fb1852168eeaefb.nq.gz
    ├── 0fde13968ba3afc143e382817050575bdf0a7367.nq.gz
    ├── 111816f878f4b3b2fb366984210a3bbc8500d360.nq.gz
    ├── 1405812f4ac11a00e3593bb02685caff741ef702.nq.gz
    ├── 140bc4a83456d9a31a777ef7c6c81d601e0ca4c4.nq.gz
    ├── 145b4bc848cc4a5425ecd8f6790646c758899d9a.nq.gz
    ├── 14feaa6663e52d510da6645217d2c1ff1c9ef552.nq.gz
    ├── 152523511c45ddfdb7de6d24c708b08b7c2cd1f2.nq.gz
    ├── 153293f677d4ac00e64de25b96590a27a08ee6d7.nq.gz
    ├── 1551a980a221cdf98424557172a5dcd128ad5abc.nq.gz
    ├── 15bf778dbed74d4ac42eee81123bcb495d3b0505.nq.gz
    ├── 165bc98ea4e6ee9f86e8d50fc420db1e6f9d1991.nq.gz
    ├── 1698af8c69a278e2b14861f464b9291aff3e2cd9.nq.gz
    ├── 18444a404cc5888bbf9cb5a15346b70d1d44900d.nq.gz
    ├── 1a1082fa548558e101d284efa2c04f23458dc1f5.nq.gz
    ├── 1a6699ebd3dfe8b07a7756d1f76e79d34c9e7741.nq.gz
    ├── 1a88087219e5c831477c468893a41cc3f271f7da.nq.gz
    ├── 1b5c5a5253ba644c7c02d26d0fe77f3ef4296138.nq.gz
    ├── 1c1dd4e4ad831ccafc064ee40fffafa838a6826f.nq.gz
    ├── 1c4178a27a70cd4c452add8eed50168bb31ac2f4.nq.gz
    ├── 1d161131f8e6af42f655f9e1a2d70a87d051cf17.nq.gz
    ├── 200b8c64b736508fe9d1e9aeecfc67fbbc6b294a.nq.gz
    ├── 21ab9611b9e3984df30c7167a6684d4333dcfb00.nq.gz
    ├── 21f9a161fd5f4c13b2f6e07d820e8306f4118e67.nq.gz
    ├── 224e02c6b78ea9834e611eea181b285d9e4be1b5.nq.gz
    ├── 227882c6822ddabde34b6c9f9c1dc18aea7778f6.nq.gz
    ├── 22c195d0dd984f6fef5f0f81870f6035899ebebe.nq.gz
    ├── 22e7f3681dcc8ed05e3e2878bb33aa63c9708456.nq.gz
    ├── 244e45c6a7b554e2e270c059c254eb3805f12b1f.nq.gz
    ├── 2461a5b0e88d6bd20b0ba98610730e772d104b3e.nq.gz
    ├── 253a11d847201ea0640f32b8e2ccc4dfe8a8bfd0.nq.gz
    ├── 2788e53b461f192eece0a67fd9417f66fbb797cf.nq.gz
    ├── 285ce7df0b69841bf21f32fc237f48b00c50ee8a.nq.gz
    ├── 28746a0e35b03b25be7a32136cd20845bbea6282.nq.gz
    ├── 2880b001bab67aa23c72367cda39be6cd7bf28d2.nq.gz
    ├── 28ce77133db7112776b2358734686932f5aeb5bf.nq.gz
    ├── 2986f960dd58f15f1eed1be55d5213976f98deab.nq.gz
    ├── 2a1dbd78d6608d8c27126a55a451066c816b17f9.nq.gz
    ├── 2b6e232429d5d93d0c7d4ef96de222fb0cc37958.nq.gz
    ├── 2be588868537d906d7d4fdf4667fa829393ad096.nq.gz
    ├── 2bf48f8c9fe72033638248af5d1fc458dd6235bc.nq.gz
    ├── 2c760442303cf955e6683e812955112f71d54396.nq.gz
    ├── 2e482a08071cc205b09fa7a6abac97c08ba8abef.nq.gz
    ├── 2e921058b230e2080eb592384db407d3119f90fd.nq.gz
    ├── 2f23c08889d9682dbd79e69f34aedb1498df0a87.nq.gz
    ├── 2faf885ab792105dc71aa2c449c699e6c5cdf11a.nq.gz
    ├── 301f52dadbf24cca996ae8fc95cc23184fa87519.nq.gz
    ├── 306b28ba3f87ca43dd0d0a8e886958f5a3a1f21b.nq.gz
    ├── 30a4ad0d5b7bcdfb36c5c6220744fc71aa7179e7.nq.gz
    ├── 30dbff6a9d84631e1748153b529b9c988bf32556.nq.gz
    ├── 3179d5538d2a17ebda2afb26f695b2ed459fc627.nq.gz
    ├── 31b0d4cbfb5108430c0ff637136495a5c6fc606c.nq.gz
    ├── 32a9d6e33c31e2e1d18c60615de11a0d55a27ce8.nq.gz
    ├── 337bb9ca1dc2285fb2077dd558d0a5c00862cec7.nq.gz
    ├── 33b935724b22cbbaa76ca7e139a55d53aaf6db15.nq.gz
    ├── 33e38f9248b3f036695b735c7c4a0a587125c587.nq.gz
    ├── 3481679988977fee2f46ae9e6a55d6db38f0a4d4.nq.gz
    ├── 351a4f3d9b41353f17c8cde238376e4538d85094.nq.gz
    ├── 35ddc44a87703bea6b19052c9c83a4001de9c50f.nq.gz
    ├── 384112d245b75de0c8b69e7ed04374ec36dcf136.nq.gz
    ├── 38f37ef5502d7921a043c58d0a1204870d681f31.nq.gz
    ├── 398ed25a8c004b1283bb5aef202f4197727513c6.nq.gz
    ├── 3a6f8c95c5335b489441a7263378f45b0468db48.nq.gz
    ├── 3b207cc97d276d966a9af4c11e2db679a7cad12c.nq.gz
    ├── 3cbbc8db6dfea478dfdca9dc250cebbc0692b618.nq.gz
    ├── 3e2bcebbe913c7ce53df475732a5f8f9c71c8b8a.nq.gz
    ├── 3e7a9796f0e59b6eb3c5a41d976df74e1a8f0845.nq.gz
    ├── 40089f6303a4c93a4d368689c09195c576ab1a54.nq.gz
    ├── 40256772aafc528ac05e44a6a6ecfa224387f862.nq.gz
    ├── 4080ce5a9233f89d4334bf3ea3044a585424e560.nq.gz
    ├── 41dea4a1134e01593aaff135cd85ee56b7ad32f6.nq.gz
    ├── 422e2b56201aef14e763eea92e2d18d0ce50c606.nq.gz
    ├── 438666a3f000c1ce421b4e2fac44eed63a0165fc.nq.gz
    ├── 4433af3b89242cb767774f6c76b0bb1b35033077.nq.gz
    ├── 446a564122a9c17878d7aafe1407cc48438931dd.nq.gz
    ├── 44ef53b89aefba4d93dab83a5ea96c3d365f3954.nq.gz
    ├── 49655aefbf212405a72d5b5773104c0c2ad251bb.nq.gz
    ├── 4a40273b03208bbc14b342acc92047392ab5cd96.nq.gz
    ├── 4a78ac81ea40ef49a91137388523fc93734a07b1.nq.gz
    ├── 4d5a2a7997d0c06e2320df3c4a0cb1141c67630f.nq.gz
    ├── 4e7bdaa94f04f57ce5b9bed4c5a2d742d2eb595e.nq.gz
    ├── 4f53ff9e5d885b42e3db599e8904eb45a042a261.nq.gz
    ├── 50030028fe4e70bd0dc4ce043785c3a2760d22e4.nq.gz
    ├── 5045e20e198fe4ef42c88de395e3bc5df147950d.nq.gz
    ├── 5068e9f98855709fc001726f6627d3d2a3413ece.nq.gz
    ├── 50a59ef55d6fbc728b6985af30f55db682146f01.nq.gz
    ├── 517716ed31429ee0269bc39176d7741d22d35896.nq.gz
    ├── 517c84b46af712d3d7a875f231be833b9ddc8c2d.nq.gz
    ├── 51801b4bdec0b5b85bedca7cf24bbaec09a25833.nq.gz
    ├── 5302cc459fdc6b75446f810c0b3140a1626640d5.nq.gz
    ├── 544b8952020c1aa238056f593aff8637cb7bbbcc.nq.gz
    ├── 5641dc29e06980152e34e4a6fc824a7ee0cb0592.nq.gz
    ├── 575c74f88c9fcbc1baf55f239391c82ec4b26b71.nq.gz
    ├── 577a9a353dea98dc3d48b6d58b6c35a50c6df3fa.nq.gz
    ├── 58269fb232eb638f1dadca2f9860b08ec6e59a2e.nq.gz
    ├── 58976596d8064dfa70026fcd04ba4214d9ba3861.nq.gz
    ├── 5999cb411649c0f242f80c8c05646331876ad1cf.nq.gz
    ├── 59c29a7fd1202801bc66471568759610695111cc.nq.gz
    ├── 5a9ae689abd721c57f468a0480555987edf71041.nq.gz
    ├── 5ba553062af5458e7c2c27ddfc237f6219de7364.nq.gz
    ├── 5c29af94ba65e537b5bdba4c8518009998d1aaca.nq.gz
    ├── 5c3c13492d6df4242f6816753019f2dd045bc05b.nq.gz
    ├── 5c8b3abf5f4bcabbca49252d02ccb7370107442f.nq.gz
    ├── 5f579bcb537afce28d299bd569bbad55e5a05fa0.nq.gz
    ├── 5f69d8ac31f77f8574b04fe55eb3fdd21f146183.nq.gz
    ├── 60250fbed2bc535f4eef68724871a3895d6c8cf3.nq.gz
    ├── 6057d9da7a19f79c98be5e07dc7a408014fe486a.nq.gz
    ├── 60a2964b1b58af64b9e9fae03148db067943faf1.nq.gz
    ├── 61278463eea5b7eb92e0e201600a9e2c3d8a889e.nq.gz
    ├── 614687ba7cf5a1c8ffb962dac1f7d1cf7edb696f.nq.gz
    ├── 623698b582b291100d021c2f61c9912f29b8062d.nq.gz
    ├── 625825b6486dccd8b4ecdee26e336c1655d0c64d.nq.gz
    ├── 64ca515106997ec4c3b3f6ddb4e2dde2cd815423.nq.gz
    ├── 650748dd45f920316410b68d6c48e479e7129746.nq.gz
    ├── 650b008c7cb09e9a30482f0f981e1fe1d2048892.nq.gz
    ├── 65247621b2cfbec7a6476280dc6b01b92e481f28.nq.gz
    ├── 669a957f096ad5c7012c77bab0406f30a9f10e3f.nq.gz
    ├── 6778c908a5a382fcdf86373dc672846ee5aac8a8.nq.gz
    ├── 67c6aac99baac07e103941bf513ab2014afde851.nq.gz
    ├── 687ca91e1a6b717df6b7d8a4a334d879702ba11d.nq.gz
    ├── 6a0c3ddb6871fb663a60d09f03eb9f481d63126e.nq.gz
    ├── 6a8838a5fb72c1c91b77c0553062e48ef2b67b59.nq.gz
    ├── 6be1f2f34f351cfee033d4a72ddf1d7a31ea9432.nq.gz
    ├── 6c1352744c568b9c5e424e4466be6baec2e22c09.nq.gz
    ├── 6c475459fcb3dc6c5a89fce729e17ec015bfcefd.nq.gz
    ├── 6c4cb13cac97e5e8b2c0404bd3f83bcd4235f578.nq.gz
    ├── 6cb438e6411b8260082711ba30571c1a84d3f2c2.nq.gz
    ├── 6d6ea37e3750391c1748738e068ed2b9b3efa4c2.nq.gz
    ├── 6d763ee67d38dd4d5a47719d31e98c9a17422ed6.nq.gz
    ├── 6d9a771d77def10174c28ce2e0537e8f4eafc997.nq.gz
    ├── 6ddcd282dd9b1c7e129861c2edce8f69777a7413.nq.gz
    ├── 6ded5bddccba74827b65cebfe9c2a4932add4438.nq.gz
    ├── 6e1d443b5a571ec9f488306ca52a03bea45dcb80.nq.gz
    ├── 6e42876d50028180c8c77401c8c8c6cec9dd7982.nq.gz
    ├── 6e7d5526e4a2ce622040ce94eb4f2d7acc1d6b0a.nq.gz
    ├── 701ad061ef8b0dc57a1ca3ab105aa4d273ee5d1b.nq.gz
    ├── 715255d4c9178af96b08a919215a07874a4def58.nq.gz
    ├── 7190f7c6110d70f206d65797c14b1388b6c4d0de.nq.gz
    ├── 7286086ca7f18164847f3d61626be090f488d731.nq.gz
    ├── 738e3ad0fae654e4a1235483f449613e483bc221.nq.gz
    ├── 73fdbd2a694b188d1c9413b109910e94e4a9c5b1.nq.gz
    ├── 745aedd7b3a53c8bc248b36b7dacfc7651b71c32.nq.gz
    ├── 7491aa1c2768f703f6cff313af960ec45f92e9a5.nq.gz
    ├── 74b4aa528ae009f51e277133d64708bfc9052bf2.nq.gz
    ├── 753f4cb0a6abaca91d0527d65957549bdf9b114f.nq.gz
    ├── 762ac67b56ce763c4088483b328bdce1b4e6b97e.nq.gz
    ├── 76ec16b46b54659561a9f0bdb9015b96ff2a3dd8.nq.gz
    ├── 78991d168f6c03a80dd335a1d5a9477e10c6a3cc.nq.gz
    ├── 78d128e47dc9b30bfb62959ab72ebfa4c697ee34.nq.gz
    ├── 78e36f2071117cde530a8597c4fb8998efc0028b.nq.gz
    ├── 793cb3c3ff84dc15c7608e832fe1f8b5923fed07.nq.gz
    ├── 79a2c81a0c932374cfb65e51e092b6fb9152fac5.nq.gz
    ├── 7a532f6757c7328381f293dcf550819c16253bd9.nq.gz
    ├── 7a67fe415858f20fa079eef88254d5d3494762ae.nq.gz
    ├── 7a78435cfb78bcfe855e382e387027338a8ab722.nq.gz
    ├── 7ace7f8f042daace81c26aebcd6ce11ffafef114.nq.gz
    ├── 7b5ee4221fe980d3ecd3461eff79f3e3c79d2b5e.nq.gz
    ├── 7c0cede7ffe0a7bac4daf9cd406061b52f1a1719.nq.gz
    ├── 7c89609fb9e119e04f69fa2b7f1735f37bf0c649.nq.gz
    ├── 7ccd5cc4baf4b2e7c325d996997515bc1731f64f.nq.gz
    ├── 7e2bb9b75c98d2815ef177415a03a1ceda09aff1.nq.gz
    ├── 7e67c1cb29434c503bedf50fa701ceee250fbe62.nq.gz
    ├── 7f6ecd6f45dc266d341e4e62817f5c12e47c0948.nq.gz
    ├── 7fc350337cc4e83bb9b0d30665a88c38ad968ef2.nq.gz
    ├── 8017b12440a6c42429defef161dd8a04c63433d9.nq.gz
    └── 80281094af3c569a74971b579aacb8a45be40168.nq.gz

7 directories, 200 files
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

[scverse/scvi-tools](https://github.com/scverse/scvi-tools)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
