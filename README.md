# Repolex Knowledge Graph of dropbox/rust-brotli

RDF knowledge graph data for [dropbox/rust-brotli](https://github.com/dropbox/rust-brotli), parsed by [repolex](https://repolex.ai).

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
rlex download dropbox/rust-brotli
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 21de815f394796ef6ad2b312b7a00da2efa7b226
│   │   │   └── chunk-001.nq.gz
│   │   ├── 9651aa3ebfd23be83ca14d914fba2d7c12b32d2f
│   │   │   └── chunk-001.nq.gz
│   │   └── a51b65e75f68e3485be12bc816118e523e95647d
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 21de815f394796ef6ad2b312b7a00da2efa7b226.nq.gz
│   └── repolex
│       └── 21de815f394796ef6ad2b312b7a00da2efa7b226
│           └── chunk-001.nq.gz
└── blob
    ├── 00a83454e60a79245959ae34bbdf8010aec63c8c.nq.gz
    ├── 035121644e504cb8fbbc5e408d2f99fd6701a1dc.nq.gz
    ├── 03bfd3811de1f2cf6d8a38fab61b14d314740300.nq.gz
    ├── 050e4476ffde16c8bc97dad19b81f7a65ffeaa61.nq.gz
    ├── 0654ca1528e8d6af5f097a866500f2e2c5bf6be9.nq.gz
    ├── 07152197db668cd60dcc8141fc9d81e8d34c350e.nq.gz
    ├── 0851cd3cb90471504ec6469eabed6c7170cc6819.nq.gz
    ├── 089d700e392c8dd21ec117880f4efa00f49fbfc6.nq.gz
    ├── 092754589e7f7578dbc7dce8bf19de55c5cab94c.nq.gz
    ├── 0941d53684a142062238e6ca1e2b781ad15a62f3.nq.gz
    ├── 0999be777954d2b883a6e51b1fcc7aa502f11a6f.nq.gz
    ├── 0cc105a6d22b69895b131baf1a90bea1a0cd95a9.nq.gz
    ├── 0d758c9c7bc06c1e307f05d92d896aaf0a8a6d2c.nq.gz
    ├── 0f83d28d21da773f35d99efb35cb5f12b1864e7a.nq.gz
    ├── 1044dbc250e456a2f0f53eef53e34bc090cb25cd.nq.gz
    ├── 1072b69b4fa079b36330958f87f0bc15c343db65.nq.gz
    ├── 15045ea9b12e57ee3d18fd2dd1caf67b76137377.nq.gz
    ├── 152f9ed5aa2d840c4a115d34ac0271262ca416ef.nq.gz
    ├── 17bb347215fa2296e66e5509cdf088198192dfc1.nq.gz
    ├── 17fa9d70334b89489f016f1c1b1201e9d5414f9b.nq.gz
    ├── 18159f6003e855606ac74de537ad96c6973f45c9.nq.gz
    ├── 18709323b27647b319047c805d2bd8bb61d573b8.nq.gz
    ├── 1c3838cada30eb800ddeba7a72d0d4717094e377.nq.gz
    ├── 1c8a0e7976207fb9f03ed7e260950b62b8b9d396.nq.gz
    ├── 1f3f57e7f806d2fb9ed5b04817eab9eef1741280.nq.gz
    ├── 1fa07c783aaef706752718d2408dcc170d6a8685.nq.gz
    ├── 215e7d33d4d5f1591b7221e6ce902af29dcd2f5c.nq.gz
    ├── 23eba767ddf06c6ca4cce5aaa6f75cd19cae057c.nq.gz
    ├── 265849aa58d00c70d1233d9148cf9dc913d9ad16.nq.gz
    ├── 284dcd82188b46160076b4ff9d9c5a2172e864b4.nq.gz
    ├── 2c7484a13d1388834ab7e447c7cfe6e859b58f31.nq.gz
    ├── 2d18e664f88c706b46761c087b40dac95668490e.nq.gz
    ├── 2d4c3819baac33f11c2e93e93c1a78f688376135.nq.gz
    ├── 2de71ec6c5829cca4fc140d873eec7e067873a4c.nq.gz
    ├── 2ed134ebc9b194b4da63f8891888cf7929b200e4.nq.gz
    ├── 33b7cdd2dbaeddce1e35aa1a13f63d71154dc42f.nq.gz
    ├── 33e3a98e06889f59227f3444fa4cd905169f7f14.nq.gz
    ├── 352510b9eefe10362b257f008bfbf1d3d0578b45.nq.gz
    ├── 3754a9b09b939c80bda8066d25f59326f40d5cdc.nq.gz
    ├── 37d86e253e9d812e7749cab674b9ee55f23083c0.nq.gz
    ├── 3825ccbdba00e633d75b0050d8b687e21a249254.nq.gz
    ├── 3a5890db755a997b460335fbc5fb2f4118cbe900.nq.gz
    ├── 3a7621100f1e18d80cd82d1f86589dbeeca6c655.nq.gz
    ├── 3a852a418cd2f5740e8f8b913556e78227d69311.nq.gz
    ├── 3f9cf8651c95f006109c6d04e15fe3e26e477fe1.nq.gz
    ├── 401a9ba72c32fc9a7b2f40cb70dc270a50e78842.nq.gz
    ├── 4025e9ee3ddcf4ba051b2e6cf290ff69a43e1812.nq.gz
    ├── 40efb3c113eed183d35b0db57fea058d52a94bae.nq.gz
    ├── 43796b4e7b4c59d8c5f64f37c3818527b32b2189.nq.gz
    ├── 45a362b31d4b4a2c5bb0326bed50db8741d12386.nq.gz
    ├── 46e7ddb9978eee68b9b6aa1cffa8639fd1d168e0.nq.gz
    ├── 47408cd685dc7256fa95f1abdb47a072138a041d.nq.gz
    ├── 47edf83883bddec413880f5cc9d5390dc2b4cdcf.nq.gz
    ├── 4962bd231119a809982dd5e8cf2e4795f1470993.nq.gz
    ├── 4b21b2a0905522c4754ab57fef8954f446d39de5.nq.gz
    ├── 4b439f68e3584e626bcea94ced09fffeb3255d20.nq.gz
    ├── 4d1ebaef52ed29cdd6669f05e8a7e997e91cfe46.nq.gz
    ├── 4e19756bdd7fb9f3f036edda7f486119cfd3eb54.nq.gz
    ├── 4eea8a5d9aa9713fa3bf7f3e74ea37f3c1f0848d.nq.gz
    ├── 500c0709ca24338426091ca19777e13a1920ebdf.nq.gz
    ├── 511730ff6768868b692185f21c6b2f3d41356c51.nq.gz
    ├── 512693b8f32cdf894aea52dbf65ca38a3bbc5c7c.nq.gz
    ├── 52129451881308f2178fcd7b74b49e47e0ea12de.nq.gz
    ├── 524e34198448e64a47cfb1ec9c5a2f2e5aac73c3.nq.gz
    ├── 556f8c827b8e4a02ad5cab77dca2bcb3e226b0b3.nq.gz
    ├── 563222efea1df813b778f9c97c1e2da0df80c6dd.nq.gz
    ├── 5671929447275ffc99d21ebc0677b3419a620eb2.nq.gz
    ├── 56bb8cf3354baa5bc3610050ace9793595320546.nq.gz
    ├── 5738ff07347aa90a84ff007e673faa192a138d21.nq.gz
    ├── 57cda16d2f90171b8083c4cf0f73792d1c5f158b.nq.gz
    ├── 5ba5e0c0e6e65b883b3b7b9caaf5bdc0c029eddc.nq.gz
    ├── 5ba70db413d38d26df956e1670deb105f23dd027.nq.gz
    ├── 5d4462fbe4ac3c48213f90b9695200134684506b.nq.gz
    ├── 5d9ce61c13d47658be14e715eb7c2f1abe3d7127.nq.gz
    ├── 5dffe130b98206c67b78bc3388efb2fa5bbae7ef.nq.gz
    ├── 60dadd443779d1ee1ec2d297e8fc9665083dfb3b.nq.gz
    ├── 637e435a8d9c6373e7776036e0a9504eabaf217d.nq.gz
    ├── 66090ae29cd5f1ecb6a4ccbe61aedaf226f67c65.nq.gz
    ├── 6738e851c25b1c5e927d4ac93cf53326574b95d9.nq.gz
    ├── 6c4c8b812e95fecb77a2bd8294eb5118a391c587.nq.gz
    ├── 6e6a6dec01ab4b00a7e0d91417aa03d133c4610f.nq.gz
    ├── 6f83c126d1279edc0f57695d184a1c48b447824d.nq.gz
    ├── 703365523b944b721362a0fdf7a8255b313e9dd6.nq.gz
    ├── 71d18fdfe504da25676c1ae60763dd7bd5a33e6f.nq.gz
    ├── 73c89f832e220662689d8446741b6eb85c10debb.nq.gz
    ├── 746c3961683d33da05e4004f4e079d53ad117f8c.nq.gz
    ├── 74d0be10a7ded87c29f81b65a8637ce52e2d0c88.nq.gz
    ├── 76eb19e45f26b7a05aa6d1c928e7dbe97e081d0b.nq.gz
    ├── 76f88034c62dd6f50c430a4890962f3f0d7dbfc5.nq.gz
    ├── 77d85b35352ebba81fbf1943a652e1b2d66735e5.nq.gz
    ├── 7813681f5b41c028345ca62a2be376bae70b7f61.nq.gz
    ├── 787b0e446bed16123374a1d8140bb53d080a66bc.nq.gz
    ├── 79f25bae0590857d3a75783333f7c956a4f5735c.nq.gz
    ├── 79f2bd16bc0cfca97824d9c2f3046b699c09ce51.nq.gz
    ├── 7b681843233d1af08bc8c3fb90a323f856b6d54b.nq.gz
    ├── 7c729a4c3f2972d5183c0619c230822dad7811f8.nq.gz
    ├── 7d3e1a818c6d67bc137fb95866a239a997c85fdf.nq.gz
    ├── 7e08758afdf8e49496ea8e9c398a6c7becf7b687.nq.gz
    ├── 7f3bda311caffbf937e9f7a27392069aa0ce5410.nq.gz
    ├── 80e18e472087954cfbc831324d7957cc993617fe.nq.gz
    ├── 816786f9fbcd4d6bc11339654bcba2573d02b32b.nq.gz
    ├── 81f0388bf825cf858828b03ba404b8202f303e18.nq.gz
    ├── 8275ea02f38fc9cf4fa95767188e9857f846d868.nq.gz
    ├── 828b9ea02c9d93fa29b3ad698c669d731a47d8c0.nq.gz
    ├── 842e7995c39db5cb06e968ab2ad958cbaee150ca.nq.gz
    ├── 844771f94ff1462d9b0881649bcdbde6cfc7049c.nq.gz
    ├── 84f606f03773fcfdd2d2d115cce07a9b854c698b.nq.gz
    ├── 851c75cc5e74cf97d145360755d116d2409881f2.nq.gz
    ├── 86b94da8f6d8c72efa72e0e928ff9c90bac2db5a.nq.gz
    ├── 86fe9dabe6b25360d19ad4721c365582f0a99cc3.nq.gz
    ├── 8834f3275a80e77f03dd99010f43b5024255b515.nq.gz
    ├── 88dc7b60fe2afeeedd1ba1bb5d4229b17b29b041.nq.gz
    ├── 8a58e6938dd0625eb86fc9909273c05a0b87b429.nq.gz
    ├── 8ac28ae4a1b001bcc300d5ceb9c205640794f965.nq.gz
    ├── 8b8bbd06023f4888594ad509c6f2cf6af163f3e5.nq.gz
    ├── 8c1778296e926b84b29dbcb91805bbe7c49beee7.nq.gz
    ├── 8e3d6c02b51f8e89d063917b59411284a63a4533.nq.gz
    ├── 8f439dc7ced9e5a7386d33b0614f4f03d8df4997.nq.gz
    ├── 8fac0345cf82c2639ad62d7c6e7293aeb9d8c2e9.nq.gz
    ├── 92455afd1188f80f37ef6798f5582de3fb6127b0.nq.gz
    ├── 92989101b1f7473c06fe5092bb82439d7322d0a7.nq.gz
    ├── 937f9963af9586683992307b17d16e5ac9dc4111.nq.gz
    ├── 948f9ca9f14f82a760b722a0a481aa6325eff8c3.nq.gz
    ├── 9560afc0acd191ca81d855868144c45aee3e2d30.nq.gz
    ├── 95723dc37ad9c77bab7aabf6779c4985b19ab456.nq.gz
    ├── 963674519bcf52fdc131c0716503f99f6f9f04c1.nq.gz
    ├── 96d5e081605ec6d382cfdf8b4ce5b37c7b28f58c.nq.gz
    ├── 984bd76bc5b18da956518443f386f79ce8d1f703.nq.gz
    ├── 985df3471aa61d7e7d1576ad0c57df3e26681884.nq.gz
    ├── 9870b5fdc7539c0f60b6770a7d632cdc24b250a9.nq.gz
    ├── 98c9dcca28ece4dfb96567a3e0f8150390c38af3.nq.gz
    ├── 99784fec6fb32475c7539c7abcde020aeaff8ef0.nq.gz
    ├── 9adaf65f42146623a188f6e726a1185d6cc49133.nq.gz
    ├── 9c214bba61b2b48c9b9cd775da5f4f1e465e4a76.nq.gz
    ├── 9c8249b1649c5c049d78c26d072b5006921d158b.nq.gz
    ├── 9c870c84e9f861fab846c947b1a190a9f1eec888.nq.gz
    ├── 9ccc27718f5751f1569c3057c86a6eb70fd3cec3.nq.gz
    ├── 9e09c29154048c543e1e902b5fefafb9c5eddc89.nq.gz
    ├── 9e44b3af6aee3a0aa5c1db388cf8c5f3ba9f2741.nq.gz
    ├── 9f3af2e0697cb4250ebc6a185a3a64a9a7a1c38b.nq.gz
    ├── 9f5046057cc82c42034fa77dc0e457aa599a7d52.nq.gz
    ├── a22badc8912e09194e65afa96bc519f5b3092fc6.nq.gz
    ├── a28c8c9ff2ea657a1bb4627a1d7832ebac7df3c9.nq.gz
    ├── a7778b5a8e9eab3f9b6031e28e312a28734b7b59.nq.gz
    ├── a96b99fa6cd4a399f038db9203a9fe535c95dc66.nq.gz
    ├── ab3868f558929be43567bfd41d2e2baca30f9967.nq.gz
    ├── abe28460162d492e5a50ec7b63a66a15ee1fdce7.nq.gz
    ├── ae60db8f353e6d0c7236869d63d9524d87ea5b14.nq.gz
    ├── aeb2b754fa88a3406fdc96c327220a65bad392c7.nq.gz
    ├── af7517132c43afe001b0ad813b06e4df39b68a39.nq.gz
    ├── b0955c5cc7f7ae758eb76e96a907028223d1a209.nq.gz
    ├── b18c976dabfb7f42a99a052e3dfba6196a6fa23e.nq.gz
    ├── b2acab252cef52a02092ec4d578b5e91ec6804c6.nq.gz
    ├── b307b27e657ffbe4a8f8025a2f64b910b70c6b06.nq.gz
    ├── b81cb9b55aaf947fb5dfa4e11e47ad1aa70ef056.nq.gz
    ├── ba5858fb1d0ae19794260e9e32da6dff85c5171b.nq.gz
    ├── bb86acdfc9b189690fa6b64058a3a79c7a423ad5.nq.gz
    ├── bdc0025c7df146f24290f9374d0c849015f9fa5a.nq.gz
    ├── bf163f307f8d32fd54554c22b75d98aa51b7ff3b.nq.gz
    ├── c183df6a308637ea8e1bbb578785c74bec7f8599.nq.gz
    ├── c4d1d2365ebb85e9eaa3f2e1ff48bc6adadf324d.nq.gz
    ├── c587b4bbebadda0d1c98f277afa68da86cbcfd19.nq.gz
    ├── c731795894b41d55a20218111c1dc6ad1eec09d6.nq.gz
    ├── c7930257dfef505fd996e1d6f22f2f35149990d0.nq.gz
    ├── caa41718cb20530713fa29098bed86e019eebd32.nq.gz
    ├── cb5162799a63fa909827f3df65f956e37fd98ade.nq.gz
    ├── cd496ba72eb37e83a44958358d1f89a8a28cbc15.nq.gz
    ├── cdeb78978d206caa0af37d53dce5a0ae38a04391.nq.gz
    ├── ce52f649301fdad0b15c839e36e39080a53743dc.nq.gz
    ├── cee94a8beaf72d76d4e5099ab667152d6dd5f06a.nq.gz
    ├── d159bcdcb463f479ec81f4327558be73eb10b0c9.nq.gz
    ├── d2c3ca44751dd3e957b27a1c3e8f253c0fc399cc.nq.gz
    ├── d49fa6a03f214eee7b906eb6d1952868a8459ca8.nq.gz
    ├── d4fda5438e8d9afedc03281e6f2ad0c67f0c61e2.nq.gz
    ├── d6608793db6dcf1efc412ee18773c86db8dc148b.nq.gz
    ├── d9006e2e157957cd553378f92e43ae8d328edd23.nq.gz
    ├── d9792748202425b198b7051f8e5066cec4d0da69.nq.gz
    ├── d9a12a749ef7d6b312bb06629749114a23708714.nq.gz
    ├── dc605430c160a47bebb8e5be8ee1f8027089762e.nq.gz
    ├── dd619c0a57149e2aff75844a60f3ca5fbf2b8df8.nq.gz
    ├── df1d8ba650fce031be1bc2b65c02f0b3dc1cd8a2.nq.gz
    ├── e136a792a1a4cfae18581449863d6a4c915112f1.nq.gz
    ├── e3205a0fdeb71b812712d1d15f6608efd4e1e0d4.nq.gz
    ├── e440e5c842586965a7fb77deda2eca68612b1f53.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── ea1add3454f1b35ac135933ef7359a6e00d443e8.nq.gz
    ├── eb98e8e73acbe78c6b40bf156a00fdeb6ab02768.nq.gz
    ├── ec98b2184edaa3a5a3e48ae8f7c96a755510ca62.nq.gz
    ├── ed0cae39052a6f914efa76688b1c6f063ad42e4f.nq.gz
    ├── eda86997c4d7022044c441f2d8e875e10a2260cc.nq.gz
    ├── ee3fccd55186390d9dfd1456cb9836c27d87439a.nq.gz
    ├── f00b5440fd893841f4e9f363bf635f604a937747.nq.gz
    ├── f11c82a4cb6cc2e8f3bdf52b5cdeaad4d5bb214e.nq.gz
    ├── f1f10bd6c9800d7cc2be711c2a93a9f00015a712.nq.gz
    └── f8fa5a235408d5c6f2c2844e44cd98c1fa666ac8.nq.gz

10 directories, 200 files
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

[dropbox/rust-brotli](https://github.com/dropbox/rust-brotli)

---
*Parsed on 2026-11-23 by [repolex](https://repolex.ai)*
