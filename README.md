# Repolex Knowledge Graph of oven-sh/homebrew-bun

RDF knowledge graph data for [oven-sh/homebrew-bun](https://github.com/oven-sh/homebrew-bun), parsed by [repolex](https://repolex.ai).

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
rlex download oven-sh/homebrew-bun
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f698c7817c8bf40904fa009be1ca362a0d937ed4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f698c7817c8bf40904fa009be1ca362a0d937ed4
│           └── chunk-001.nq.gz
├── blob
│   ├── 0069c922287fa1e7ee82fa70fbdefc710f0e8bed.nq.gz
│   ├── 00accd03e6b631d67305f333029694e8d4764b8b.nq.gz
│   ├── 02d6ecf98e31cd9e68b6c0de579d23b039f1ff99.nq.gz
│   ├── 03d01847030707411e5f73c2cbef2969fb2f6520.nq.gz
│   ├── 05b24ef4e10824c0149e56139a680990f7b44fe3.nq.gz
│   ├── 0737063af26c0e6a7742deff41b7bb63e5037bb2.nq.gz
│   ├── 082c6fafd6b9c9ac55ef48fbd066564865cb36ac.nq.gz
│   ├── 091166eabce6ad441d684247bf1dd7971e0ddf9e.nq.gz
│   ├── 0b2edf4ff4105f4b8eac18a46eed95cc7b54bac4.nq.gz
│   ├── 0e6eccd373c645b187ceb0732164a7fbe19e6d6c.nq.gz
│   ├── 0f246a5ecb8aa82ae13afa53f7f6e232715e9a8d.nq.gz
│   ├── 101fcdf22a1dbd51223ab5d9b232d4777677cf8a.nq.gz
│   ├── 15411a417174227ab53058cbb817efb43934a26d.nq.gz
│   ├── 183da87f2f46f9e8ada530db4537bc93c4c54c77.nq.gz
│   ├── 1848885cd5716f80b5712b43ec4c4a5214cecd49.nq.gz
│   ├── 1aa7eeaa637656f590b5ad9bf67057a81f463b70.nq.gz
│   ├── 1afe375726bce9a9993d94f9672bfed7bffa9ce2.nq.gz
│   ├── 1db69a314419922b9d3b93904669aa140bbdfbe2.nq.gz
│   ├── 22120b1093c26c27ed566085e5c0707f623d4b08.nq.gz
│   ├── 25f09fc69d09c9e95c2c9220754b26b7b6d4028d.nq.gz
│   ├── 2730010908e3a9d38a11a80264fb1a56dd8b1e09.nq.gz
│   ├── 28625c8ab00fec7498feef4415145c031dfc9af9.nq.gz
│   ├── 2a1ff9a92ec04aa23a0a10b189428a615d6b4c9d.nq.gz
│   ├── 2c142691c34574750a1d750bb4074ba458fa2702.nq.gz
│   ├── 2eb1394d6cdd1cb4c63d739a2f03650b085c7817.nq.gz
│   ├── 338e91d82e37fc4c9ad67476f231c707dfe33d67.nq.gz
│   ├── 3542e1cbaac1a61dae58a42493ec6afc6ff4b325.nq.gz
│   ├── 3549f87ea0734d6c60bf7f8249974b9ee8480135.nq.gz
│   ├── 35a6cf6658085dcdf0217015f7b4e7352adc8a7f.nq.gz
│   ├── 362a0657859aa1eb094a32a51fb00111b0b490e5.nq.gz
│   ├── 367c7476a79c50830671e857373d21b18b698459.nq.gz
│   ├── 39778690b829f37d5814c0f685b70681a73088bf.nq.gz
│   ├── 3aa97224a641a414bcadcf0c197ba73d2448eef3.nq.gz
│   ├── 3b124cb44bb55ac6c3c83b63e42bb797a1353640.nq.gz
│   ├── 3b7ed4716b9fea23f7564ab382dac67369074681.nq.gz
│   ├── 3d2aead1220df7c90d6d637061fb8d4f587d0930.nq.gz
│   ├── 3e4fb43574719010c882777ef04b7591919fcbf0.nq.gz
│   ├── 3e55400c9aaeb219f9c1977a96e7be0aa0764fa8.nq.gz
│   ├── 403dcfc4da38b2cf0c3e9550a122716ad4ee473f.nq.gz
│   ├── 45d1b3cfe21d9741ad19a073d0127883b6c7118d.nq.gz
│   ├── 46d5063911f5178ca7b4d3c522ddd278e491466d.nq.gz
│   ├── 4a02df08e38cc84902de6d8f11520589ddc6e647.nq.gz
│   ├── 4bb663ce351ef69aa962f909756f470f857abd84.nq.gz
│   ├── 503218bcdb7b35cac43dbca856f17c3a77518ac4.nq.gz
│   ├── 511fe3f4d94ebe7e97f6698220c6faa50f0f0614.nq.gz
│   ├── 5222563f3e416352a1f0a12e124cff4e8a573cd6.nq.gz
│   ├── 54c5f3eccbc85dff94d5e6b84989c8c7a761a28b.nq.gz
│   ├── 55ccc0bf5b70bb7572bc2cb01b88ff5c2537867f.nq.gz
│   ├── 56afb1b7d90016e93d6091702bd18543ab81ddf8.nq.gz
│   ├── 574c2e0cdc9efb5d7fce3ce496d2e71e4a4321e4.nq.gz
│   ├── 57fb9639e9a26d611e749b4501e2124edc1f2184.nq.gz
│   ├── 5898b9450da1c07af1f882fabd05e1bf292911c7.nq.gz
│   ├── 5b2f50f4e0a77a9c2ea20fe701ed7102319a3b0e.nq.gz
│   ├── 5c121dd273314f859d079b135ca5e5a119108b56.nq.gz
│   ├── 5e1311a4606e10437d1572cada1003e23ab8b848.nq.gz
│   ├── 5fdab42fc90583962fbf578971e1bd8594463306.nq.gz
│   ├── 600dff94fc6d97150a8188b5d7fc55760dae302f.nq.gz
│   ├── 62621ffb0d289f0cc9fda9993d5238149bfbe551.nq.gz
│   ├── 65fe15cf70db0436d9153490bc2664e97d70cb17.nq.gz
│   ├── 66bcff73de5d0754ef1856292f1ef8df7d3c2f18.nq.gz
│   ├── 66d02ded8bce663904d78b83b38e0efd2fa35bea.nq.gz
│   ├── 67ace7e20fb8b7b99accc2502316acda0af1f22d.nq.gz
│   ├── 67d7017c81a5b39d0a11486cdd1fa218d45043b8.nq.gz
│   ├── 6ad9f397b98047faa30530c8b7f413b9694deded.nq.gz
│   ├── 6bd704f39d8eddcd7e5244b3280a0e7d2ca133ec.nq.gz
│   ├── 6d87b871e2c2de7d61005a2432b739d8874b03bd.nq.gz
│   ├── 6e839a7716a9c8f4820094706dda90da1ea78ac4.nq.gz
│   ├── 6ef55528ab16a08631d4ac1b36fca43dc6cef9b9.nq.gz
│   ├── 6f4e518b4a9f11c6f9878d2156ca97b1a38a39d1.nq.gz
│   ├── 7050a53e2a66516abdfe215775e91ba1295b49da.nq.gz
│   ├── 70796a9ec870612f5c495463ad93a2db3a70811a.nq.gz
│   ├── 739b870b86c4ea6aa3674fdf4b663048ec983934.nq.gz
│   ├── 75876aec5e214d9be5aeebf142293eb1f642c7ca.nq.gz
│   ├── 77952fea454a60697f45abdd9d977d9a55b53234.nq.gz
│   ├── 7a9583a9d3361329a1da9a716c402f5e6e20a901.nq.gz
│   ├── 7aa976ab999652a2bede00328315fc92e1693994.nq.gz
│   ├── 7deff814e26aee6fbfdef9f1e793f33ee4a1a4b2.nq.gz
│   ├── 842a71601d4a736b4928b1ba21445f6ea24f011a.nq.gz
│   ├── 87e34d18f75685bbc9dd6b040aeb4f403a49094c.nq.gz
│   ├── 88a23c9345882383368289793cfac8e8730f5a28.nq.gz
│   ├── 8906b3b17b56a726bc4b395851daa1e0ec9e9184.nq.gz
│   ├── 89f42758beb331dd41199d17cfb69230c93e64af.nq.gz
│   ├── 8aaf6e89b8b4d3032249c1dfde942020611becb5.nq.gz
│   ├── 8c33fabb1b58cf5d3c4a0e3cec02ca024076bffe.nq.gz
│   ├── 8c99e460c4b9e394075759ac16435f8508da9494.nq.gz
│   ├── 8ccb82e651030438bb560f246df1cf87b33ad9e7.nq.gz
│   ├── 90019dd927f965a9b3cdd768eeb434117040542c.nq.gz
│   ├── 906f5174b36b80c269de97abff4565aca04be541.nq.gz
│   ├── 918b40284d5258d5eff910a5d83ed08df0b6214e.nq.gz
│   ├── 9203ae17194919ea21c7b610b49b49ef20298599.nq.gz
│   ├── 924b7e6cc3659f3accff07397f9240d4d61be3c9.nq.gz
│   ├── 925c197b0909bac579a4a2932e5b365802979e01.nq.gz
│   ├── 92d19fc6b19e188944cbd5c7addd7e92c44eb564.nq.gz
│   ├── 939fd8aca4bf10e7940ea4f5849367882a482324.nq.gz
│   ├── 94f1119ef02ddeba33ea65ce3dafcfa8475d9192.nq.gz
│   ├── 9707678ed01e36bd7ee791274ff58ee1f5386046.nq.gz
│   ├── 97f286970e4c482ff6bc21360c8364cc3fcd6cc6.nq.gz
│   ├── 999e38f1f35edce0e76e82dbdd3dca619ffd5dc9.nq.gz
│   ├── 99f71827d3181cf20f80fd8ded1e201abf64ec5b.nq.gz
│   ├── 9b45b52715b177e4f7b2f2258326e516bb5a6402.nq.gz
│   ├── 9e087c340302bb4593b4d855a763c9a36aa3f49b.nq.gz
│   ├── 9f5ca1274541098cb813f1174fa0d5bb9b33a43d.nq.gz
│   ├── 9fbaad115ff0e0147add506221a0134ffa4af6e1.nq.gz
│   ├── a11d43cebd19d42e2a3f757f43e2fe5510fd6551.nq.gz
│   ├── a2cdacb6c8f35f7d8ac3795aa3f5959edf0a45f4.nq.gz
│   ├── a32a15422b6374201384699d53775368c0e1b883.nq.gz
│   ├── a3336ff14c3049b000311add70e37ed9c84e25d1.nq.gz
│   ├── a3e7a19cdfe2846238683772e64dfda316c3b8df.nq.gz
│   ├── a93efc919ac797d2645b6796afd8cdbceecc041e.nq.gz
│   ├── a9d7311c960a7a20e05780491b2c94c9c592cfa7.nq.gz
│   ├── aa85d5aaf5af92ed46b716193f0b032e37c5ea94.nq.gz
│   ├── abe73692b53cb4e5198ba801b656b9a69c54bbe5.nq.gz
│   ├── ad82a1a5b05565f057d9b863baa9a272471bc24f.nq.gz
│   ├── afef978372bd0d19da2c67aa4cd70aa3f21b5763.nq.gz
│   ├── aff610fdd0b8e4220460c7f67ad27a109a9bca0c.nq.gz
│   ├── b04c395125bbe8f30d4764dae768382fb3eaa748.nq.gz
│   ├── b1cb4690176794a2023dd027402770c69eaa7d12.nq.gz
│   ├── b23dee378521a42e1dcc5ec104280241d9d0af06.nq.gz
│   ├── b3a3f5f6a1bbc174c35f85ccfa85afede8fc94bc.nq.gz
│   ├── b4fcd1ab27721c7a8c9167324a92c2eb49837f09.nq.gz
│   ├── b60cadd1c950bd59d32d3945b385a478bae67b4e.nq.gz
│   ├── b7670a7246b72893b2b7cfe8e3c65c819d180e28.nq.gz
│   ├── b848e66dfb991a290f387d58be11f3c10a912fe3.nq.gz
│   ├── b9ad5024dbb3ff436734d187afffbc6fc66aeae1.nq.gz
│   ├── ba409b9da333effa76b074d288744768de57fc1f.nq.gz
│   ├── bed60a4911d6649e87ebb9482b84e4fc96ccd880.nq.gz
│   ├── bf81d72e6f10ced3b68e335a62eca58beb7908d9.nq.gz
│   ├── c08232d28e2545dc4920d63050e54f08ac337a11.nq.gz
│   ├── c23f508b5ed6abe3067bd561429265186aaa2f72.nq.gz
│   ├── c4d463ec0c4235815b87887e1be6ee13e9c0c8df.nq.gz
│   ├── c5da3c84ea0b6a6696bf07536ca6f0bcbe48353c.nq.gz
│   ├── c7c7cfa23de4b73c7bff3c3decbb78835b3bdbba.nq.gz
│   ├── c8499a417255284475ccff2e4db1303ae20ca627.nq.gz
│   ├── c9a3c49973a258997707c604462a509adf498ada.nq.gz
│   ├── ca1e9bb545ca3f2ca908cbb835724a489068b701.nq.gz
│   ├── cc539516d0c7a96a4a0102d74b9ce83e0457f0ec.nq.gz
│   ├── cc90f2fea6f89d106e141f675b3e22b2c360f2c2.nq.gz
│   ├── cc94be1d9f3bc6f2e7a683fb5a590dbc952d0154.nq.gz
│   ├── cfbc3a2ae28d16c9287e38e5d4aeb25863e4671b.nq.gz
│   ├── d02a3b926a779e7cae7ec97413eca4baa3e0173b.nq.gz
│   ├── d0ac2170575806617ec154cccfeb3e616a624677.nq.gz
│   ├── d0c6787d3b1c88fc513cb048a7e27cd9c1f7dcf2.nq.gz
│   ├── d1de0871b77b5a903b9da7bdd8b1cbe4c6f5fcbd.nq.gz
│   ├── d1eb819e8e951202ce991e05a9ffde7775c205fa.nq.gz
│   ├── d364d260f0e3d915da54d2a6f047834632f33d81.nq.gz
│   ├── d45cead5f1e32a48c9912c471829fb9c3505aa87.nq.gz
│   ├── d625f674034afc425f88fe0593d8de17c7a938bd.nq.gz
│   ├── d833265a26bca26b80daf6559a77e0053f771063.nq.gz
│   ├── dca5d1f5f4354a2a84b47bd70946f83a505401c4.nq.gz
│   ├── e1656a28e220fd28477d528ad4453d0733070ae2.nq.gz
│   ├── e204c431b256616254a242bb7206e121b98060a2.nq.gz
│   ├── e46d4661cf139b847f94f386195d70debd25574d.nq.gz
│   ├── e73ad184e8c9f3da326504728562ffdb5e8d75f5.nq.gz
│   ├── e75f1f776c2ac8ff2053711d117ea99b0fed8eb3.nq.gz
│   ├── e83a4958c7232e77980ca45dd919d4c2898751d0.nq.gz
│   ├── edab7b38dffecb780183d89202b3def3a4ba4fc7.nq.gz
│   ├── ee3d5157cb9f813f004ef9c9d61d615b30f10967.nq.gz
│   ├── ee59bd7756b7e707da7209038ca3dad7f2f4d4f5.nq.gz
│   ├── ef226824cb2621586f6dac3834b8f2b25933a32e.nq.gz
│   ├── f054405dc97d9c99bd0793165dec8ad9ccaa0208.nq.gz
│   ├── f07ce54a902a4c45149e0b43e945ffef9acf8c3f.nq.gz
│   ├── f0876c14736529cb2f9cea2975b12aa948bacbce.nq.gz
│   ├── f0db2f9b8f22ce9f45475d66c15e95597bfd736d.nq.gz
│   ├── f13f47cdf47799ca7f2ba75c94d4e32befff6e47.nq.gz
│   ├── f22ca365cb2ef5fd55cbf097aec4a57363b62a95.nq.gz
│   ├── f2d8073d32592b77bfffab2255fec501b735e6d5.nq.gz
│   ├── f486b8f914872a80fc32f4debc293eba06194f9a.nq.gz
│   ├── f7a3dbbc73305b5b4cfc77d41253acddb58121af.nq.gz
│   ├── f7a4db89594c5a1782ff8c213f9911bdc44e5a60.nq.gz
│   ├── f97d54a2cea3144e2be8318a648bc005a5835bd6.nq.gz
│   ├── faa7538990293491f59bca81c3faea3bba8010b5.nq.gz
│   ├── fbf082367d148b34f404a0178895c41bbb6e213a.nq.gz
│   ├── fc53f8ca344c685b396a72b0587dfc897e5b86ce.nq.gz
│   └── feaebac7dc1554caf49a861ed9a5df8627445272.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f698c7817c8bf40904fa009be1ca362a0d937ed4.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 182 files
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

[oven-sh/homebrew-bun](https://github.com/oven-sh/homebrew-bun)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
