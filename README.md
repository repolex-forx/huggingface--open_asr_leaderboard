# Repolex Knowledge Graph of huggingface/open_asr_leaderboard

RDF knowledge graph data for [huggingface/open_asr_leaderboard](https://github.com/huggingface/open_asr_leaderboard), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/open_asr_leaderboard
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a768a2c7d3b911dcdddd1a0b5c39fec4ae21336a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a768a2c7d3b911dcdddd1a0b5c39fec4ae21336a
│           └── chunk-001.nq.gz
└── blob
    ├── 00ae8c498ca012f98a107062d38e5d357d0c27b6.nq.gz
    ├── 00dbdd2c1ce8d116e6265d55f18e1b8353236b9a.nq.gz
    ├── 015a787f16e4b7594b52593df46765aea8b95c51.nq.gz
    ├── 0283235803173debd6212b6d869f60c984c7ea47.nq.gz
    ├── 04a1f43b684e0d3fd67f9c6b0857fce61ba76531.nq.gz
    ├── 057461203fd85613c9a9308b99c6e856195837ff.nq.gz
    ├── 05952660cc614da21e1365b667fd91954f4e9c4a.nq.gz
    ├── 05b55bf45831016adae80d88f847ed6fbd0faeb4.nq.gz
    ├── 09ab4849937718c98735261bd80646e363df8348.nq.gz
    ├── 09ecde2bbd70da2eed093c95ff49673b4c953683.nq.gz
    ├── 0a5648deb2d2d9e90ccae2e33359c3120b879e5c.nq.gz
    ├── 0a57a97fedd1ceacff62d7601573f04a78a9eb08.nq.gz
    ├── 0bdc783773021a6c951e44b73241d103d82be964.nq.gz
    ├── 0bfde50a22a48824d27f39b5995553f40a76f7de.nq.gz
    ├── 0c83e70cdc72bfaf87a4aa3fe8cc77b7e4c78bb7.nq.gz
    ├── 0da6cc769a2df2401a6c0cb715c26823e28b3f51.nq.gz
    ├── 0dbf2e9532ec0280c663d1c30d6ed4502718a9bc.nq.gz
    ├── 0e4a5e7896f21ecd7acaa7c1a9a040358799311c.nq.gz
    ├── 0ea5b39df976d022a3211bd54c35c888826cb5de.nq.gz
    ├── 10229595d2663f8c5c7eab4b392f5d99afdbf0c1.nq.gz
    ├── 104ed042e72915c3bad54e42ed5b864977b6f0e1.nq.gz
    ├── 112764234ba0591a92fa09ed1222c8c18733add1.nq.gz
    ├── 11b4e426fa8d1d1aede533159bacdb4da6b1659b.nq.gz
    ├── 133512649ffbc4300e70479e13f2b28b974b7fc3.nq.gz
    ├── 134e3f4daa36ae5ee62d98cf2d8843bf309f1c94.nq.gz
    ├── 14200ced7b1a592c10c6d717d5b98db04339e6aa.nq.gz
    ├── 159a840e6e68a330e04fd5682aaef5e05755cb16.nq.gz
    ├── 15a6bc4daada12304449f584083bcee795982394.nq.gz
    ├── 15f4021bc907e20dc471e3577d5f28663e7a8861.nq.gz
    ├── 15f7bdd7916ac5fca2274ad5d1239bafe0f0f5a2.nq.gz
    ├── 1695db307f5cf4359154decaf6ab18b53bf06dd1.nq.gz
    ├── 182c3610aa75825b064a6de3c97d62b9eff7d23d.nq.gz
    ├── 18cc3561ba19e68342225fac2b4b63444c6b5de5.nq.gz
    ├── 1a13d2edf7e5e28f002c4670bd1cef587da3808e.nq.gz
    ├── 1da3591aa6a54496362622d4e30d1fbe9ce0042c.nq.gz
    ├── 1ef84b93a6ac943dc30d010086af4e2ccb8148da.nq.gz
    ├── 2011b4284da9d50251496d54fde36180788f0aba.nq.gz
    ├── 2198746e17bac061149ea8a5e8b7d54737a94529.nq.gz
    ├── 27d4d72db4049b6ef903556f615e93d61b859ff1.nq.gz
    ├── 28c2ea2e5342acfffede265e29691fce3b93b0b2.nq.gz
    ├── 2921f84859338e268fa71defc6604fda6866859f.nq.gz
    ├── 293d1f0dee97beeba47ad375c55f7ccd38fb5b0e.nq.gz
    ├── 296c84986fe7ea5a13955529420eceb4aa8265de.nq.gz
    ├── 2987d90ae462d3f5047fb7b1a780636995fe12d0.nq.gz
    ├── 2a3eafe6ffc9017b4be6111dfc4147feeeb2ff6b.nq.gz
    ├── 2ade3d9b80905343d0b5d7124225fab22248b2ab.nq.gz
    ├── 2afb8b9462d0a8f6568fd10bd05a64b7a7b1e2e1.nq.gz
    ├── 2b1f42dc741dbffc08980b4e0d2969fe168de5d5.nq.gz
    ├── 2ec9b5d44967d0f145c18565ad66f650b3bf9807.nq.gz
    ├── 2f1e5dcad670ccd4b430543ec215b653de84f03e.nq.gz
    ├── 2f43b9af5007e70431f59a56f3ed96e012bee402.nq.gz
    ├── 2f70c419ee1fa2e1790d8f667dd638c2af73b82c.nq.gz
    ├── 2f995cd5e7ee9bd6d33b8b33904403f663ded301.nq.gz
    ├── 32bcbebaf62050055c67dc9191a37b87416785a1.nq.gz
    ├── 3367fc866cae69ee633ccdfbe5f0e9878a47edc1.nq.gz
    ├── 3378f3b335f4b669e975166a6b8cd8a6d56e090f.nq.gz
    ├── 341175b224dee6b0451c5b8f0b0b971c07a33164.nq.gz
    ├── 3456d8178d2801a952e252418a2c79370a8f664e.nq.gz
    ├── 3457867c86c7ee177d0b936bd5a5710711000c35.nq.gz
    ├── 34efafd052f4aeec6e4f2e361f585be6f9b1da70.nq.gz
    ├── 352996de3383d819df673bdbf3aed7efe00e0466.nq.gz
    ├── 3733db8f78c82a062a2fa308fd708527b645cf59.nq.gz
    ├── 37c76007e155b83a783d107c3da700bb880f0454.nq.gz
    ├── 37c9e17be20aee87978389beb1ea02fceec49ee7.nq.gz
    ├── 38dd94dd39b4b80145a55232360c31838b0579de.nq.gz
    ├── 3bd5e99da668e49bf312d74220271df10cddaad4.nq.gz
    ├── 3cd42527e9176657cc3056025472d1e5be1217c6.nq.gz
    ├── 3d948b046e3c527caa973b0e4c465529990c5590.nq.gz
    ├── 3f99e2dbe0ab24b41ec29af341bba11d07cc0163.nq.gz
    ├── 3fd2a7b0e59e59f88b5173a50f57fa58f6cd7998.nq.gz
    ├── 4057b2f4225960beef2e39bb3d66a1a33e10a566.nq.gz
    ├── 436cf554b56d9ce57ce046a644e4cfb551b21400.nq.gz
    ├── 4446ded6fcf69eb59db06c757c8019efcc3c798f.nq.gz
    ├── 44e74e86b0a6fc958b795b8d12e9224247d476aa.nq.gz
    ├── 4559bd5de58d3aa4f9a356267528eba76611cc5b.nq.gz
    ├── 47082f73eb71b19456a4774d21bd68ae5cfbd93d.nq.gz
    ├── 47203afbd5dfd13fa2b56c7480b0e91973f7a7cc.nq.gz
    ├── 480006cd921c47aa3a60e96574517db8e7c1785b.nq.gz
    ├── 4848649f1a95a9ff055a52a698e94a3e97d5fec5.nq.gz
    ├── 48f0c5d1ed24476479b94d38a65f63802c985bd9.nq.gz
    ├── 4ce4059347d95913122d5c37398afb4eb177132d.nq.gz
    ├── 4dc4af5d02a608504b5effebec1de10582381c19.nq.gz
    ├── 4defde3ea38c8c0641a56daa12233632db9663e0.nq.gz
    ├── 4ee1c3c285bcf76519b38a6ef39fc096d6a9f541.nq.gz
    ├── 4f9b9d1f62c5864d8ef89b6f22c1ff7fa3a62335.nq.gz
    ├── 4fe34a7d7f6bef91b2cbcf0f33cbc8091759047d.nq.gz
    ├── 5120221da5b417484d97399577f2186735a4dc5d.nq.gz
    ├── 52045c63a8a0917d37956585f61543a2ea0ca3bc.nq.gz
    ├── 53b29dfa64f1865a111bffa935a3304c3fed5e3f.nq.gz
    ├── 53e091096d2b4ee18473d8671aca7b2a7388ad3e.nq.gz
    ├── 53fb5520f0b11b9b4dd6824c18eb445392ee2e80.nq.gz
    ├── 57a866a18a1ea283118c8da751abfdd3a17d9783.nq.gz
    ├── 58e660e4431b5a57e97143a4ab7346c14ea05136.nq.gz
    ├── 5afedd629951e74f371ef35d63436f922e6659e5.nq.gz
    ├── 5ba380e6a0b080bd28aa21daf3c36ef9e91923c8.nq.gz
    ├── 5c9a00dd22d24c23c5229f4a2fa2bc3132841496.nq.gz
    ├── 634d1030f83b1ad260a0576eefe690a9712f1f48.nq.gz
    ├── 63aa7e9cea71eac65faa8d7aa4e9ee4e70617599.nq.gz
    ├── 64666491e4d4490a76853a47a35c66be1dc1c752.nq.gz
    ├── 65044c884c9375fbaaf020e0c332670a240750d6.nq.gz
    ├── 6520444a0a70b5cc07c71a6bc8b32804a0a609f4.nq.gz
    ├── 65d7e1966e63324e137f2a61a23dd4bba5b300eb.nq.gz
    ├── 67529d0d04ed15eb288da0eaa7339cfd0e5651ed.nq.gz
    ├── 67e7142b570362658dee52437b02f015a7d06bf2.nq.gz
    ├── 6802d5c7e119d5a2167dba18af3db65c578ec247.nq.gz
    ├── 6a85ecb2320263a2fc0ef433fb5c829b3361ef7e.nq.gz
    ├── 6b5f4c6929fe919c54a0a370bc829e39162a6415.nq.gz
    ├── 6c14921a4de55b5366028d5aaaf38983e85bd2db.nq.gz
    ├── 6c237b588efc8060e56954bafe27a69373b0eaf7.nq.gz
    ├── 6c5d17218a1a6b904f686844d2251acc18baaa78.nq.gz
    ├── 6d40dc49b754ad3838e4e8d0d07aa3d103a4cd03.nq.gz
    ├── 6de99c054acbb606ae6d322a512f37407083ed90.nq.gz
    ├── 6f15c82bcf79e60c4b95445f84d3b4f11f79d5cd.nq.gz
    ├── 70b5544f7f7d4a625c0b93fe919eada29a8b27f3.nq.gz
    ├── 70f197fe84f4b49be71d7d1a6b4b6c14e7303b78.nq.gz
    ├── 7333f431d9d750cf27f979e0ab49d9e852523ae8.nq.gz
    ├── 73b51d40853ab331f3dae234126814b3b6a5201f.nq.gz
    ├── 74aaf0283f1bcdb35908605ac9c84b9fe5c2198f.nq.gz
    ├── 75ee8d19f5267fa203e45ed961ae5f0fdd738a12.nq.gz
    ├── 781db47ceb4dda97ac9b66887e2f3c8a7daf8f82.nq.gz
    ├── 795951c37afb35c81173973b056c3430f86e441e.nq.gz
    ├── 7b591291ae4ae0e415bd3976734cc46048745e7b.nq.gz
    ├── 7c23f39457d6bb275c12214651f42a63c1f5049a.nq.gz
    ├── 7cba34fce75bed70460535bd9def8d7a8eff99c4.nq.gz
    ├── 7d2764715b9903189dcb8edc9744d29743bce2e2.nq.gz
    ├── 7d7e72be68af935b93dd01e4bcbb13f6a0cf1796.nq.gz
    ├── 7da2bc57f49bf84f4a0d9e521afe91fd877dbd1d.nq.gz
    ├── 7e74a4def98b2593bfe04ffe9568c1f56d426985.nq.gz
    ├── 7e820b2ebfcef368c287be77675ab3447853f390.nq.gz
    ├── 7f62b7a1699de2e609eca36bf5e5ed0d8b7b161a.nq.gz
    ├── 81164dba1da0da4ee84fca5e6a169a4b9bb297d2.nq.gz
    ├── 8267e18844db9a5ae68c39fcf2dfd33ec8ad338d.nq.gz
    ├── 82fba35e46cd427700fe38dcb5a6b2794250fab1.nq.gz
    ├── 83d327249210b1624e5bccd87e66ec228f3adf94.nq.gz
    ├── 847eb4f6181088cf1fce33848c689fe9fbc3b7ba.nq.gz
    ├── 85d1e498997a73ca8656e3c81e5545f8405dbad4.nq.gz
    ├── 8740408643ea29d67e38d104ebdaf7599a120a11.nq.gz
    ├── 8a45095176cc2e55b561f3d5c629e5ed1ecc28ea.nq.gz
    ├── 8a909117cee1d7455f989c941634df0f67ea3c5c.nq.gz
    ├── 8d155fb97004240d171c1cfd095df6a0fa2910a8.nq.gz
    ├── 8decd58c4092412f9921312c4bf0db175090e513.nq.gz
    ├── 8f45d19c647d7a19227262bd7f587b92ce447092.nq.gz
    ├── 8f6f5a745fb532a7708db699f82c0aa95d96d3da.nq.gz
    ├── 903596f06a217f14ff6403256bdd11d3ac0c418c.nq.gz
    ├── 90370b70f1b928dbd9bb041ad30f5f4be0ec8b11.nq.gz
    ├── 9088136037d187f6c499f54cba3b0b6d75b2e0c5.nq.gz
    ├── 914186d1928c0e045e474d34047aea53c3616f33.nq.gz
    ├── 92c92c0cb46c2e6b8c0511c2dee80e5ad1a516c9.nq.gz
    ├── 95894c9deae1e87e9cfb12e8216253c75e33fee9.nq.gz
    ├── 96b57a0417e42f4c4f925123af9ca747572b4d7f.nq.gz
    ├── 978b2c6978b583c208904a60c3b0770018542d07.nq.gz
    ├── 979ab0cbfcaf68097500f65f092299ec76abb6ff.nq.gz
    ├── 98238640853b1b9f0b1e6a1122383900b02f681c.nq.gz
    ├── 9e414dea3161708f31567d4d23cc7c6ef6544f73.nq.gz
    ├── 9fe6175e7bbc109e35a2c0e020558d5146599ba2.nq.gz
    ├── a026dbedf3d5a3d9022917626c17c4a0ff9ccf94.nq.gz
    ├── a126f59940d2fe4b8387def90e3ac46d014c6f7d.nq.gz
    ├── a1bcdeb4064029e2d81bcfa98f98a122bfc19381.nq.gz
    ├── a35f0bcf8dfa5d5ab120f9949fa00a0674fa5450.nq.gz
    ├── a3b07843c71c2c96178d5bfbbcfb3cdf3cabb95d.nq.gz
    ├── a3d4e45db906f43e9c75b52a797efcf590f206bf.nq.gz
    ├── a5aa784d3f07809cea8365d9088d6fc0dd826301.nq.gz
    ├── ab55ed60c19c3bc8249d967dd3eae57a009768ee.nq.gz
    ├── abc9b5040eb2d68b473949c822cfb42182b820fa.nq.gz
    ├── ac1390d7a2b6c0774a554cae3d53c41dd16db4a7.nq.gz
    ├── ac3c6b7391e2eb038772c7757286eabb6ead9e3e.nq.gz
    ├── ac52aa4aaca82cd9135fc244e3273eb068e255dc.nq.gz
    ├── ac57423d5eaff28c3ebad7e4fb37d39c03edd70c.nq.gz
    ├── ac92dd40047d42cc928c161aa270a9ca6e14c0dd.nq.gz
    ├── ad020c91fdd5143b7292e4a89e04d339f34f9eeb.nq.gz
    ├── ad08311ae60dc56351173cc393abb533c1bb0918.nq.gz
    ├── ad7056ae7c9dca6becd7e9d90bd3f346e1c02156.nq.gz
    ├── ae807e2da397553d4dff37398b055813428d2a50.nq.gz
    ├── aea71456602cccbe491b658170e7196f20732baa.nq.gz
    ├── aeb6a608d09fc03986a598a5fb8bec0786e30f28.nq.gz
    ├── af81fb1d76b68f1bc77daf7d130eed2ba7858efa.nq.gz
    ├── afab9fd5e62ad120c62d05424c9eb6ab2fdde2c8.nq.gz
    ├── b02fd1f2732af5e73febff9f7d74bfc0a0eb85fd.nq.gz
    ├── b16bafc0cff93aa650806fae10ae8bd7e3bbd38d.nq.gz
    ├── b27deb0a856670dd83f6684b025d4c0d758a3c58.nq.gz
    ├── b6e466e5edc15a9affc8579831e93cfa35b96f44.nq.gz
    ├── b7883a4ec5b685faad5ed068dedc04b2f3cf07be.nq.gz
    ├── b980391a0bd943e4be275ffbea1df87b7923b754.nq.gz
    ├── b99cad0cb39efe79db0ad5437a33ecaf9b3f16a4.nq.gz
    ├── bb2f874c04fe10d412f0bf039294402cb047373f.nq.gz
    ├── bb31c326f18356c0f8e0d8c252b85e09f358f622.nq.gz
    ├── bbc271eb6cc46deb14ac1ea4ed0d253d7ed01e28.nq.gz
    ├── bd196ae99170bf2e6c4c41640f4df5d6c3a5436d.nq.gz
    ├── bd43376886e5c81a764a215cf30a4490163929d7.nq.gz
    ├── c0bbdeb29d25deffbd8973e2e11e2f49f7598f62.nq.gz
    ├── c3b11191572c8b67aa670f7ea71f59a8b47af655.nq.gz
    ├── c48aef2e845bf5af20789b6e1e7c2c1616ef341d.nq.gz
    ├── c6160507a49486ff40f7145701c4b838f8ee306b.nq.gz
    ├── c6532364414bef643310d9e146849b0654012bfb.nq.gz
    ├── ca860ce8c307fe64099acb9f4f894427301b3c46.nq.gz
    ├── cb280a485256438af1bf0114fd7674c01ccaa397.nq.gz
    ├── cdead81d67bada1a5e920e2bf1b385aab6134f62.nq.gz
    └── d026c11c6bd1167cbcb8c2be3264320a695f41e9.nq.gz

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

[huggingface/open_asr_leaderboard](https://github.com/huggingface/open_asr_leaderboard)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
