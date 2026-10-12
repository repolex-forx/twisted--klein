# Repolex Knowledge Graph of twisted/klein

RDF knowledge graph data for [twisted/klein](https://github.com/twisted/klein), parsed by [repolex](https://repolex.ai).

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
rlex download twisted/klein
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 722840bf1b9d7a725c5b4710b8b4255ebe87562f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 722840bf1b9d7a725c5b4710b8b4255ebe87562f
│           └── chunk-001.nq.gz
├── blob
│   ├── 00c6b4dae9b409ddf28308a2ea07aff4ac704314.nq.gz
│   ├── 01ea715461d65e83b8c4cd09d1f1b49ec9711a29.nq.gz
│   ├── 03037a08c808d1805e07170df48129a45a2e7e71.nq.gz
│   ├── 03a66077a0f085b9e93d0eaccb047a47c6dd6ce6.nq.gz
│   ├── 04070878bf8c775a68803d1166aac5c7d96b0378.nq.gz
│   ├── 044da849a2b76fa1121f4d771b5cf4b34ec904e4.nq.gz
│   ├── 05679d5e90f4a11e1cb4118b91878a29d8e59f8e.nq.gz
│   ├── 07ae6ec55f9087f7c71e0d1cf01f3d274614efcb.nq.gz
│   ├── 07ec7d9602b0ec77797abf813169be26f8facaa3.nq.gz
│   ├── 0dc84ab60e9e3139cea121c15232a20fe7c67082.nq.gz
│   ├── 1269169d7d756a17a38aabb03241b72806da3548.nq.gz
│   ├── 1602e08f68b66f831b9051885c939d5a2f9643ef.nq.gz
│   ├── 1607d660bb25b5efbe33a1868e5e523f29b25042.nq.gz
│   ├── 1bcf01fd682e7ed31f29fc2364b442cf3a75b05d.nq.gz
│   ├── 1dcf4dd97bf54cbabc863df1c3af96d63c6e9744.nq.gz
│   ├── 1e8022eacdbc2b2a1effbf2f346ab3de31dbe1e7.nq.gz
│   ├── 1eed5c1ad54723fb92f7bafee6389bb459b52d88.nq.gz
│   ├── 1fe5165f00a8d63ee7cbf6ad76c1bbd6302dc006.nq.gz
│   ├── 23705400953a7a671c2c42dd1439aee2f62c689d.nq.gz
│   ├── 24a839d0a8ef146ca77fa826b8181364e5024f32.nq.gz
│   ├── 2d21da3d7ea73db14f2dba80d1b85eb3961e5e06.nq.gz
│   ├── 2ea2fae95457322a7e58c8f7cab1c239fdc4bf46.nq.gz
│   ├── 31a02ac2fe54f0b10eb1882acb92dab872b61aa4.nq.gz
│   ├── 32412cc6de9e803b1696acb656a381c4a206ae90.nq.gz
│   ├── 351b3f895bd3c8f1c2253803769a7ee3c59981d8.nq.gz
│   ├── 3549b0cd166a9acf37582f50cb0196e05a399838.nq.gz
│   ├── 399db7a719f49b7c28f967ce5e0f9c06dddd27eb.nq.gz
│   ├── 3e24e262ce6dacdecf4027e1e83dec104dd807fd.nq.gz
│   ├── 3e8b0fda36bedd0ad856ef6155eab030b2ccaf5c.nq.gz
│   ├── 3f6a409f392132769378c071e587b0e9c04f5c15.nq.gz
│   ├── 402a0e9c2f5f4cccf95da1806ef0ecdfe1515423.nq.gz
│   ├── 433665fa40f4200212bfe8bf6db51ab4583f5d2b.nq.gz
│   ├── 452a216def4dcd7ad248589fad15d01320c147d0.nq.gz
│   ├── 462818222b531ec0c2569ba4cac22bef11bacc88.nq.gz
│   ├── 467da2b51b5cc86628d163ade4c59b7f00a9bc19.nq.gz
│   ├── 48ad4b97d97c2051f1bac43e7633bbf611ea24c6.nq.gz
│   ├── 4ae245ab157447f3e31c3d28a2d8769b96022874.nq.gz
│   ├── 4c1cb062f94e185d7ec88720f0cdee7cf3570a9a.nq.gz
│   ├── 4eb9a0566edc59fc999f773abbab866e705a973a.nq.gz
│   ├── 509f71d3a509356f1a990c7b148800d27a388397.nq.gz
│   ├── 50db4648b70e9885f425bd3c9b82ce98d66cf1cd.nq.gz
│   ├── 515f85720202a7bcc3839db03f15df54d48930f7.nq.gz
│   ├── 5770a2a8932bacd0950f8280f953eefc754126b2.nq.gz
│   ├── 59903ef55172acca4dbfdb6fb4e606d1d375773e.nq.gz
│   ├── 5a96b728a0fda2b2f394a59e223ea2dd9aca91a8.nq.gz
│   ├── 5b2b11cb949665453ad6346db945c5e7bd42c6a6.nq.gz
│   ├── 5e0ada688eb5bf443f3707ac599e038e11eb8684.nq.gz
│   ├── 612b5c00362952765250e1e8a92c286ea16a968c.nq.gz
│   ├── 61a876a6eb48e0c4c76f4c210b73171e5f7fa135.nq.gz
│   ├── 63879e9e60794dfb23b72d2dac342ea90f8be39e.nq.gz
│   ├── 687efbe8a706880992b1e7b6ab59fb54f979fd51.nq.gz
│   ├── 6ab18fa930f8e7fb89392c36c138f25de0c7e1f6.nq.gz
│   ├── 6c2cc0948216e9938d5ec6ea3c96966443cf0952.nq.gz
│   ├── 6e7c7b65f0bffe05c3dc2bf0421113cc732d4903.nq.gz
│   ├── 7041667d1393fa46d28bac70e33b10ffc55c6bf6.nq.gz
│   ├── 71ba6680bfcd5037abdbcb172aee20b525b83ee5.nq.gz
│   ├── 71c258fa8ec3c0ccf22f34442430baee8d77fb05.nq.gz
│   ├── 749791161397c81190a0a4cc11d60a095517a6ff.nq.gz
│   ├── 751b2fc63c608d5df502a0890ca5b7c90765d207.nq.gz
│   ├── 790661d4c230f412656b57751b2df8946fa1e19c.nq.gz
│   ├── 7a45af95e9283e8e35d7484d49ea36ddf0f32c1a.nq.gz
│   ├── 7bfeea42573f6449a38b8db93218efbef8b2f5ff.nq.gz
│   ├── 7d2a43064c5df5a57409cbdaaf591fb49b89c4d9.nq.gz
│   ├── 8233b67b46d7d6e3c8aa4258c5532c3608b783ad.nq.gz
│   ├── 832d60f3c66d8e0f24a9c71363e7954b5b7ce149.nq.gz
│   ├── 87197aed744306e1edea87a71b38ffc46d0f1519.nq.gz
│   ├── 8779d37aea240ff6641b9ea111ef6ace877951ee.nq.gz
│   ├── 8c2a4416b78feaff61d7931f4d040d875b252faa.nq.gz
│   ├── 8cdb12428e0e90d674f5ba41f34552592cd837b3.nq.gz
│   ├── 911327ca626169e40e599995e1c1940b9b9814ca.nq.gz
│   ├── 91b886a6a1b5bbd41b2e424ecc40bd08b8c621ff.nq.gz
│   ├── 91f930d7e0d70b9347818e9e420961f9c5fb377c.nq.gz
│   ├── 928b32377eaca9aa4376b06cdb050ae8d3eb8cbb.nq.gz
│   ├── 9397fc49c03d7924d69b576c417ead9e96f93f01.nq.gz
│   ├── 9517894d4fe16c62c1ee918146d0f5ddb302db40.nq.gz
│   ├── 96542343d0384f5dfea36d5a86c8dedb1d913bca.nq.gz
│   ├── 990cad10066f70e30f0502a93bedbfe18a42710e.nq.gz
│   ├── 99650d1c21f38ee4b61dfda34a988430088f1656.nq.gz
│   ├── 99dfd84007aee1acb7b966b655b22e04dd4c9233.nq.gz
│   ├── 9a98a2279c0e42b4c68f8c1e1bf19d9005039baf.nq.gz
│   ├── 9c80e814381c45b3b446ed716ab15d37bc47a2ab.nq.gz
│   ├── a11e54462bfbce7cb968df582f2297b417a48e86.nq.gz
│   ├── a17d61da685d93a5434257171b337ea3c05f114c.nq.gz
│   ├── a1be4c6e0c2236cf818f64504d181f5a8765a976.nq.gz
│   ├── a7bc45f87ae38b2ff97519151758d8868a2c033a.nq.gz
│   ├── aa93fb4f414e6c5868b9db6b42dffac32e8bf297.nq.gz
│   ├── ab3c7f973ac0e9892f502b029ce9d278fdd17394.nq.gz
│   ├── b08afac7a761d75fc5879a6c29377ac11cb6d5e9.nq.gz
│   ├── b0a9683d703866d6d3dc9ac97f162841f2a2f9c4.nq.gz
│   ├── b2783e02f9c363bc2ef55a17ee9ec70e66948b76.nq.gz
│   ├── b5079e042e8be03031eff9b18f1e5592ef098713.nq.gz
│   ├── b5318f5da7cf5ca2b822a4ef656af9c980b7ae0d.nq.gz
│   ├── b79ea29228d39ec482f53f95e33cbc1aa5732dee.nq.gz
│   ├── baa945087d1b53d873a78f83cc7939a730ac398a.nq.gz
│   ├── bb241c0fe7f0349ada9ecc3bc155e2cc04160573.nq.gz
│   ├── bb2fa5b17300deb818922d08bcb79abd994d5e08.nq.gz
│   ├── bb3d441381599cc97b935d22451568c24218b4f9.nq.gz
│   ├── bc6e58a2889f42b7a02b4dc8a6e76e17ba12a936.nq.gz
│   ├── bd51427e39d983cb8538628f7f8b1453fc728e03.nq.gz
│   ├── c2200c0c4e88fabcab3349a9c7e4716a22642dc4.nq.gz
│   ├── c260a62498cb28fc9914a44918086740b5103f9c.nq.gz
│   ├── c42182d8c0749775272e4a65ee2bd6a7d6432196.nq.gz
│   ├── c4d24d40670797120b38e71726c4ebe639ee8035.nq.gz
│   ├── c4d302d471ab9bb449450cffe1fcd3a3801e0c53.nq.gz
│   ├── c505674caf35d02e953b28cdf887291a924e15af.nq.gz
│   ├── c74881b3ef74e34a1d26a05ebd3ec512e995d2dd.nq.gz
│   ├── c7b1de2430da86165cbb88fced6f34e711842e63.nq.gz
│   ├── d17b3bebfd903b56f3eca323bddfdeeb36e1e1ce.nq.gz
│   ├── d2dfd5e49152ea42b697a4647ba9c5b56a53639b.nq.gz
│   ├── d30465a3d06002c3f783d6d9bbafbdc2328e57d4.nq.gz
│   ├── d3ff7eb28ddb4a7f1d10add5383a0738347d7b63.nq.gz
│   ├── d5eb27fc04f647cd6f117d5ca377ac4dd59bad76.nq.gz
│   ├── d7e6a032cbd81ab0292f8e31ef11dd4acc516f7b.nq.gz
│   ├── d9532ab5d01530cc2ef4532a5767063b1fb6188a.nq.gz
│   ├── dac3f7c2c549ca25bb764124ea2ca6f1c9e2e864.nq.gz
│   ├── db288c818622ac5dc5b13effe0ff9c81d22142bb.nq.gz
│   ├── dc0b5c26985ebaf04e452f67642ab7eb862e9005.nq.gz
│   ├── dc5b8effc8806255dc204b5126db267f0b99c244.nq.gz
│   ├── dc853ea3ca1ed2eb891563d9a8091813883be4b3.nq.gz
│   ├── dc8d3f4a7bdd7b9984992c7756b447ac36041276.nq.gz
│   ├── dee3cd3d9d31c83b43e6f766b59b8e86214926ad.nq.gz
│   ├── e01ae3b5bc36fadbe03fcd4e9a35bcfafa886d72.nq.gz
│   ├── e075a43fcfe32f9b381df240786d9df140db2174.nq.gz
│   ├── e1787fd4d8842aaf99f0d0d2ceb1a5b81d9b4f75.nq.gz
│   ├── e220e6e676245af960812b7d212f9c1d80505991.nq.gz
│   ├── e299e6117e586dd2b73d2f67aad929e98cdf8ab4.nq.gz
│   ├── e47b0765a351a0eaaa5c03c4a792fb1ba840de95.nq.gz
│   ├── e5ec00f4c133d1e7d0117f00ce84f739a55f9c7f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6b369ffe9bf1bc5c726bae4c11faba707e39aab.nq.gz
│   ├── e769b45a76b41f9d26e48ee50e81deaf7841108f.nq.gz
│   ├── e78e349482c16bc14d8898a726da0809ef5bedab.nq.gz
│   ├── e8b3f617ff36dbe4d2f6d0e0c3dce5588341597a.nq.gz
│   ├── e8dca73e41c27ec1490d1621325f094ea55dd336.nq.gz
│   ├── e91a44a0ff828378efd8552d3dd76006b3f2dccf.nq.gz
│   ├── ee1d407d7f1bcd6d59da90e203a8be03b98a667d.nq.gz
│   ├── f087e34dea47b52ba5a3e5b644d8d985fab10b6c.nq.gz
│   ├── f21054b014ae86154998a705d15ba1eca30c8e64.nq.gz
│   ├── f8665034c8bcdc926e1fc01dda13c3b54c0dc12b.nq.gz
│   ├── f8a05dd22ae4c19e7458799151f4e20beccee72f.nq.gz
│   ├── f96b74324b977015b03b6e2e637306913b15688f.nq.gz
│   ├── fa79e1803b207958b1aab488f54119fa2bd35d8a.nq.gz
│   ├── fb959d94912939dd5f184a1a1bc4d454a85e06cd.nq.gz
│   ├── fcea8ad18d7cb6accd59d478699a4c3c8347fce5.nq.gz
│   └── feff72a94ab4c8bca3eabb3a05841315ca067097.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 722840bf1b9d7a725c5b4710b8b4255ebe87562f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 153 files
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

[twisted/klein](https://github.com/twisted/klein)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
