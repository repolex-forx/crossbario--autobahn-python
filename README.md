# Repolex Knowledge Graph of crossbario/autobahn-python

RDF knowledge graph data for [crossbario/autobahn-python](https://github.com/crossbario/autobahn-python), parsed by [repolex](https://repolex.ai).

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
rlex download crossbario/autobahn-python
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 657d0fa16edf8907aa1284ad84e23d6af37432ff
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 657d0fa16edf8907aa1284ad84e23d6af37432ff
│           └── chunk-001.nq.gz
└── blob
    ├── 00320e3244381c2565efeba676829acfedda7d6f.nq.gz
    ├── 01a24c3faa3c27bf74420aeba22e0193238bad04.nq.gz
    ├── 01b883e2fcc890892c65495ce5f8168c872cd6d7.nq.gz
    ├── 01e4b97663d9fc6bc666d8efbb18b10412a5b90f.nq.gz
    ├── 01ecafcda4fee46e02d95b076a0c75957cdca146.nq.gz
    ├── 026e2a990f24bf9228f616da25ac7af7e25a8608.nq.gz
    ├── 0296e52b3fb5ff0d7d6b2bbb7ed59f977afa579e.nq.gz
    ├── 03256e58d3d219caa355b9cc21c72de53285f74a.nq.gz
    ├── 03feb2679e19ee1659938080545146da134cd514.nq.gz
    ├── 0441ab7651753b85047e864755baab07c6ab6cd1.nq.gz
    ├── 047294778027564c3f3a681c219b2d6ac85589bc.nq.gz
    ├── 0492f37f3093047c98c506f79a3f3cc119929279.nq.gz
    ├── 04964a6720d50d9fff7c74204b9484769130f241.nq.gz
    ├── 051235047e197277f31ea56d446a47dd7225fb11.nq.gz
    ├── 0547342ebe9824293da42ce569ecf61babd88632.nq.gz
    ├── 057216a5ce498b4329fbecd12e2007a738ef46fe.nq.gz
    ├── 058c975f579ce89929413cf4573c081acfb62ab8.nq.gz
    ├── 05af6e1365fe4b31daa14dde3979df04e92ad948.nq.gz
    ├── 05afabb693c5106e3586cce48a0fc337c9786f10.nq.gz
    ├── 06a4e9f4d0703aadb362b0d1d7109863b9567450.nq.gz
    ├── 078cfad3bc4d3e4051cd445b6801a3c4dd901810.nq.gz
    ├── 07cf04358fbd7599ef1bf73647881f33a842216b.nq.gz
    ├── 07dd7065bf701995348211e31b16cc2a3f4f3d4a.nq.gz
    ├── 07e84d048eeaae5d729c67dd5b5342e3a7afe553.nq.gz
    ├── 081538d750428c7f7965639158b1caf556197b93.nq.gz
    ├── 08354a954cd4183e654e267b43995f2fba898020.nq.gz
    ├── 084accfd4f1497e7db0f9752785db2aaa84d25e5.nq.gz
    ├── 088c643952fc363d0cbec044123fc1b8adbbc0d1.nq.gz
    ├── 08c32153d9b3df9dbaa7fd779348d1fe071cef22.nq.gz
    ├── 08c56ba7b2df2dd71f127ddf528b49ce713c4922.nq.gz
    ├── 0933e8816a473672c66717582c70f01b13b5406a.nq.gz
    ├── 09cbddff00cac8c1786d17892e72f2748ee06da3.nq.gz
    ├── 0a47eee0a238abd2b75f9a24655764808f459968.nq.gz
    ├── 0a774dc5d12bdab2a4f78cca4b53c31d624e6414.nq.gz
    ├── 0a8cb2b627b71be2253d376eba0178679b7de8c7.nq.gz
    ├── 0ad5d13cfec2b088a157a2d12a7747d6d57e3f20.nq.gz
    ├── 0afbf8eb9b7d09aa0e7c16a43f1117ad0b492622.nq.gz
    ├── 0b09716b6da4d3e6238ad294e2746b3983074afd.nq.gz
    ├── 0b880e1a6a501e9e46616adf1a1dbd63c06babd7.nq.gz
    ├── 0c3057ba016077c81b04b3d34dc41b809b6cf8b2.nq.gz
    ├── 0c37cd777fd36c1e4e9d6abf624a7dcf2d6dd735.nq.gz
    ├── 0c43fc5bd8cfbf97ccc6ab9bac77ac1fe356d22c.nq.gz
    ├── 0c4c309bf4e8a2ef6187e76f122451a8ddd18d59.nq.gz
    ├── 0cc94bff24fe3bf5a696784dcde4b84ba3e0575f.nq.gz
    ├── 0cea6e91265d4b2e346b8686b2207a718da101bd.nq.gz
    ├── 0cf30c2f78d297cf72d208fc3a6ba892b3bd4213.nq.gz
    ├── 0d4fe05bb2f300d2f4bc10c7761198eea1df782f.nq.gz
    ├── 0ec479d208e6c0640d804b05425a574f822b2a11.nq.gz
    ├── 108893a8f86b9425492e4a17dd94218c37395081.nq.gz
    ├── 1104edf8060a21a45d9476fa49fa2d01136603e0.nq.gz
    ├── 1134a9fc0b1023ac1796d10a1923f63999fc5383.nq.gz
    ├── 1148541fa23726667a5d7dab6d128f6f651c9369.nq.gz
    ├── 118fe2da2c8d40db641b7b3cfec689ba9f8fdccf.nq.gz
    ├── 11ae8e9cc6a8e940632716f06486f3cac300fcb7.nq.gz
    ├── 125f9f72686b9890e6675b808daa60d9884972d9.nq.gz
    ├── 12a8edec1047715e241465a90f519453eb2a50af.nq.gz
    ├── 136f4d1863bd383732d1595f29d8ca8095de7560.nq.gz
    ├── 13d091a7c01b870b4200782ea9b2eb2a2016cd00.nq.gz
    ├── 13e76d4bb561cc7f8629f62d8d2043a122d4c1f0.nq.gz
    ├── 13fdbb3f5d64032de23a9ead51c776e13e192575.nq.gz
    ├── 1488eef5088227d8a42c42ef192f08002fcd46a1.nq.gz
    ├── 151f39f9a32fa2fe8f6de58d4f4e3170f66c802a.nq.gz
    ├── 153465455c0db9fe29aa8c183fbe6a0c349b89c7.nq.gz
    ├── 153de00f503ea3159f68974bf1e8309bf9764639.nq.gz
    ├── 15a2882164936e1b78361c302a5ab42cb700553e.nq.gz
    ├── 161d90a59ca0b6fff14d300ebb6118769126dfed.nq.gz
    ├── 169277799ff04913e0b8cfd05a145a926cea0111.nq.gz
    ├── 16956a818cdec6b1bd0c692ea084e12e8d4f5329.nq.gz
    ├── 1702b6d0b88057ab9292d34a414f7aea492ada7e.nq.gz
    ├── 170e520fa57b4ca3b6be1c30ccadbe0fb756f336.nq.gz
    ├── 1731a77116eae22ad552aa67292922eab6bb5f21.nq.gz
    ├── 17a47f9094402bafe42875867f35c98c8fe114de.nq.gz
    ├── 17f46031ca62251abdf611c3f010721e8c39433a.nq.gz
    ├── 1880e94b334b4930c545a13798beab946e8a88f9.nq.gz
    ├── 193c49894044b4eb9cc0139517b7ce50a894498a.nq.gz
    ├── 1a15fbd4edd9549efcbd7e12f897889330506663.nq.gz
    ├── 1b86c4ffd1845c644fed4f91b951fd82fddafaf9.nq.gz
    ├── 1c552588130bd5ad11e1e5233a98130d12a4d3a2.nq.gz
    ├── 1cc7e6df67d1c283ce55174866aebab5f63cc9f7.nq.gz
    ├── 1cd6cf21b7a0d04756f71718e730916f6c9aa74b.nq.gz
    ├── 1d5e974861de15069a5f47a4c9af2bce64c5d77f.nq.gz
    ├── 1d8ba34adfbc8ecbcb7d88d6e96723cfd4d838fd.nq.gz
    ├── 1da211611105084731ae0078dd99544c4b33ef07.nq.gz
    ├── 1ee4877efb44a62d8f7dc5b77d15dcb3d48d13e8.nq.gz
    ├── 21165d26770d5264cf04504f15807d5b4725e287.nq.gz
    ├── 21e83fbc0af859e5fa96eefd0b420731f1371c3f.nq.gz
    ├── 21f2bfec6881a0a84ae2ace59035ae3017b06466.nq.gz
    ├── 21f92f0193111e3a28f9c2c901145eba74860633.nq.gz
    ├── 2235a8280e92a26b4f447aeac84f782507126cf8.nq.gz
    ├── 22890b40a56a12450caba8f43eb3f36478f96866.nq.gz
    ├── 22bcd8b9b3cb59e944f3c357649193cb1a1c1483.nq.gz
    ├── 230c5b008775f7e5d7e5b848227c5bb140838985.nq.gz
    ├── 23446ef643b621dfa0c7000426c3fc2b6528b6b2.nq.gz
    ├── 2370f14814a62cb8da835a489f13606dd000ee25.nq.gz
    ├── 23e4663a1220c89d1285f0e815b7f5a42f005c59.nq.gz
    ├── 2441f6b6fddf64b084c7fdfc1ae1e3186e0ee613.nq.gz
    ├── 24ffbc51bb841af1f41ac9eb60866d33c9f55f3b.nq.gz
    ├── 259d7a020157ff54694aa3819d8444092aaa5028.nq.gz
    ├── 25b15fb5fbaa823c559229fa9fa268d08e00a416.nq.gz
    ├── 25c5b6ee5db5d6ca675808efc2e21656267bc566.nq.gz
    ├── 25f0d37d497afaf076abc009c4cbf81d4ec3403b.nq.gz
    ├── 26cfb3d6bc9cb0e8a50f19ddbf2243ce77929288.nq.gz
    ├── 27487738cbfff1a0571551a86832da080db8ae3d.nq.gz
    ├── 276838ec0550f439c2d8b192e1ea83c5126bccb0.nq.gz
    ├── 2854a4b78331b60ded86ac8d46b1205ab7f1cc5e.nq.gz
    ├── 287c563844dd198f551f025c43e04fb90d2f57b8.nq.gz
    ├── 28a400e89b24110438232cc0fce58e8bca0ce738.nq.gz
    ├── 28a84df45c2debb434bd7e95b7f066423c0aa2c0.nq.gz
    ├── 29f878f4eca53a6297805b4820e249eb5e6dbd35.nq.gz
    ├── 2a861e954792febcde430b8bc9855b70ee350d9a.nq.gz
    ├── 2a8eb2d9d08a5b65a9ba1f4a7b0f70f2df2db168.nq.gz
    ├── 2aa665cb432a883c1a0cbffee8225dab973bbc8a.nq.gz
    ├── 2aac29313d55b076f7708cab7d4fe8edd574ae16.nq.gz
    ├── 2bec1fe69204f035c06c0720cd11d9480e7d52f0.nq.gz
    ├── 2bf2615b8019c0651bd2d3e46f243df2c1a4cc0f.nq.gz
    ├── 2c3b12c257587bb9c0168875b7dacd840c4a15cc.nq.gz
    ├── 2c6a55ee1381df9ad0e4016b74e3544cafef11c0.nq.gz
    ├── 2cce39203bcc5a0741a0cda105fbf8263c2d3b3e.nq.gz
    ├── 2cfb395a1fdd56a6aab5ba9c55973361c40fac11.nq.gz
    ├── 2d5d78804d41545b50b9bdd5b6fe20c2eac90928.nq.gz
    ├── 2dc50558a2892f3d49e490b07396970a10ea485f.nq.gz
    ├── 2de42a1b5f57cbe0e6f194941b59bb3bf7cef562.nq.gz
    ├── 2ed299eeccdaacd16c4861108d3efb1d05ef0c95.nq.gz
    ├── 2f450238d839b779b33f53f735c4ebaa06c34649.nq.gz
    ├── 3019917db8dbc04158548582e46b27f493f3515b.nq.gz
    ├── 31025ef7b446221985d81db8c21e04799fb72490.nq.gz
    ├── 3142ca79ecfae06505904481bf6c44b4cbb66b88.nq.gz
    ├── 32471c113a113a0c0981e18653d4dc1c1ce50f56.nq.gz
    ├── 3276bf4a1ee0c617a47a2af401c33a1332066093.nq.gz
    ├── 3346dd86055819c0fe846fc05accd8ef9c879944.nq.gz
    ├── 34f81d487e5e12644882d9eb9d04f250fdf4e7d5.nq.gz
    ├── 3595909baf59270285009632baea22a3fd82a688.nq.gz
    ├── 369ee8fad1dcb3f962c794687a6d20c1c32fd15a.nq.gz
    ├── 37843eedfa4c7357febaae907728bc9ba7889d22.nq.gz
    ├── 3789a16e4c2462f6904258999622fa84312e4ca0.nq.gz
    ├── 3970f1780dcff404af659e870cc87bc087fb711c.nq.gz
    ├── 3aa8715c9989283895f77616330417c3f7720acd.nq.gz
    ├── 3b57ebe331badcf272a885b4380ca2a3fcabe536.nq.gz
    ├── 3cd8f40e07bd97fa7826fbde54564dbc0941ac9b.nq.gz
    ├── 3cf05627525a6bfda2b9a2867ff641ea7b0e9cbc.nq.gz
    ├── 3d5efe8c5c0216ece0aa9693bfe78e97bf7725a1.nq.gz
    ├── 3def2f286a400a3b22c86cf1e65511c88a99fb07.nq.gz
    ├── 3e1b35fc380fc2b6df48703c62932c2daa7cb331.nq.gz
    ├── 3e1f3b80b01fdc5d6d5ec112a046bfeaeae2a83d.nq.gz
    ├── 3ea4048b46b94cb6801d5996336d74f53d879c85.nq.gz
    ├── 3fa3c7abb5f76cddfb214763a23c71b05713a78f.nq.gz
    ├── 3fceedc44ef9ec93cf7874001115d06cd52c83f4.nq.gz
    ├── 404bb84e668fe9727cba59d2760854bbb49ebbb3.nq.gz
    ├── 40aed5c7e9af9c813f7f56cd4cf948adf63c251b.nq.gz
    ├── 419d0bceddc3ca24bd8a96c79ca43417a70688fe.nq.gz
    ├── 41fbc09aba6df4724cdf444c345048df880cae91.nq.gz
    ├── 4232a6c4fbb67dc62efcd9066f5151f12fc9a406.nq.gz
    ├── 4277fe0d81f710f4abb3f6e575ec47de4b143c7d.nq.gz
    ├── 42924e0c20b936cf86ceabe4f6f311356748c1aa.nq.gz
    ├── 42fa1ee35d760c1387e4bec7392bea140838f3de.nq.gz
    ├── 433fe4416c33579a9b9903930aa0da03c64f6be9.nq.gz
    ├── 43d5482cbafe1bb0afdd9f079bfd33d070c793db.nq.gz
    ├── 43de65b8bca0f354a2ba6bf923b1fbe821870ef4.nq.gz
    ├── 44d1a1a9ebd7cde2accc237ecb646c0719a7a335.nq.gz
    ├── 4706eb3fbf11b31eecef9c5a87c36d6abf88ea1f.nq.gz
    ├── 4750eec8470242729e4cf2c2f44347f44434438b.nq.gz
    ├── 47fade74e45dbb48851d68881916392546ee0e3b.nq.gz
    ├── 488e110a835a2a660b77420606474971c7ee66b4.nq.gz
    ├── 48c29a5d33ef9e4e0fdda58bc43c01d2414dc319.nq.gz
    ├── 497e81f93a3ee220f4e4167f4e70bb710c017334.nq.gz
    ├── 49c78a3d9a7969b9f5c4794e0b8f0abc580f57bd.nq.gz
    ├── 4a0967546b0bc28e4e0605d34a0a93795c1ba7e0.nq.gz
    ├── 4a348c2bb8bf84723359cd60108364a711710942.nq.gz
    ├── 4ad876502feac341ed50827bbb12f7c9c136e4e7.nq.gz
    ├── 4b2796d15a4a8dca19c5cc758ae559d9ee3c86d1.nq.gz
    ├── 4b62797d7aeb1c06622af605a1dfc682176bc875.nq.gz
    ├── 4c389c16fc57536a7401c16a0317464e843106af.nq.gz
    ├── 4ced2341eef2bedac0852223c68ef190b47ecd74.nq.gz
    ├── 4d1640c5a9dabe74f6958b37fd995902bfb7a0f9.nq.gz
    ├── 4d9a61bb0642edd33c127df0dd4f4ae4e3f87734.nq.gz
    ├── 4dec89a2e398656f05a26c35605aaa32428061d3.nq.gz
    ├── 4e4cae70f31b48714b2013d2c9149b10b59e83ed.nq.gz
    ├── 4e89c911d418152d13a048c6274d74b1d0065610.nq.gz
    ├── 4eddd120c7e2ed37c6c45be50e02ae57a59b3797.nq.gz
    ├── 4f81b886fe511cdb570adb9c0c399fe3730ed718.nq.gz
    ├── 503c4d12f174aee54e48775260e1f1ecf88c9071.nq.gz
    ├── 50d61cc030952217616da90854d33d4840f74671.nq.gz
    ├── 517eae18ee19aeeccacd1ace01615c15faa4947b.nq.gz
    ├── 51e9b79a740f4dae4bd8e9a9d2e141cc6aa6b07e.nq.gz
    ├── 5296e0a041a0b7f7daa9272611b782628e7f604c.nq.gz
    ├── 52ef291cbc9eeb059ab439f27fe02239a39a5554.nq.gz
    ├── 532b792a782f5c275d82527c4038523b0111625d.nq.gz
    ├── 53b322e6838e56c975bd63e83876849905ead6c6.nq.gz
    ├── 5498e6bf97086d26504f12695dce32fbaaad1abd.nq.gz
    ├── 5668ad70f6dc814d60f8393d90729538851981bc.nq.gz
    ├── 56e1f23dca404893b8bf970dcd57b9efd958de23.nq.gz
    ├── 571de7dfc2be795f4fc7a31746b55adf56a21c99.nq.gz
    ├── 57440dcd19279b622efa58f61e429ea97ebb097b.nq.gz
    ├── 57b8656fa96cf9189b8fbcfd24f278e024c080d8.nq.gz
    ├── 57d0b24d618d29c32051d41136e4199f51f98663.nq.gz
    ├── 585f99aadfbbba680ddca37d8673207994df2ac8.nq.gz
    ├── 58a1954fa6f5fd2b97365120278d5539213b82d1.nq.gz
    └── 58d4d84aaa7312a9c4abe985132ef58159934cdc.nq.gz

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

[crossbario/autobahn-python](https://github.com/crossbario/autobahn-python)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
