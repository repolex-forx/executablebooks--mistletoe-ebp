# Repolex Knowledge Graph of executablebooks/mistletoe-ebp

RDF knowledge graph data for [executablebooks/mistletoe-ebp](https://github.com/executablebooks/mistletoe-ebp), parsed by [repolex](https://repolex.ai).

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
rlex download executablebooks/mistletoe-ebp
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 229812436726fd9b1af85c6e66ff8c81b415758d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 229812436726fd9b1af85c6e66ff8c81b415758d
│           └── chunk-001.nq.gz
├── blob
│   ├── 006368b6a19be635406751124adb6dda8ebe4e99.nq.gz
│   ├── 0421bc9a3327a64600dce0b24a53e84f182ae0af.nq.gz
│   ├── 077e69906556dc4337c78b4e3f2bfbcf5f96f8c6.nq.gz
│   ├── 086ec535a45b70b224f5566437c6873e1737fcd4.nq.gz
│   ├── 08de63d632b1def200a89cc5f8160b5f10583b50.nq.gz
│   ├── 090d74942a13ca6b418bcc0078d8bdb81aa564d1.nq.gz
│   ├── 0944a721b777db5fa9a025fdfb6666454a90b745.nq.gz
│   ├── 0a82da59a7c01324ca2741c904cbfb478cb99174.nq.gz
│   ├── 0aff89b615cee0beaff53791705ce8ab6c83ee3b.nq.gz
│   ├── 0e706bb598c5b81d3ec4b5de3ef668340a4c6524.nq.gz
│   ├── 11fc491ef1dae316f2b06bbb40eaba9c757fdfd1.nq.gz
│   ├── 1261dd60577896db85eb448c425457cf5ab34d3d.nq.gz
│   ├── 12748a40bd039458c881ed6fe009163ffd5eb04c.nq.gz
│   ├── 132291a4f2066a3dd5c1bb79f68228f989f8c630.nq.gz
│   ├── 14859238e7a329beb30501f3dbf68b7cd806f838.nq.gz
│   ├── 160d30b1a79eaeddeef2083ad51d9189c2c906ef.nq.gz
│   ├── 17096cfbb3dbbd61e5cbd3205f54ba474da3546e.nq.gz
│   ├── 1825205835c72c56b1d6edce587941d6306f235d.nq.gz
│   ├── 18e7983c229f5ad63d376964b3c032aed88bf375.nq.gz
│   ├── 1a87817628128a8a0907ce58b2a76b845e9fe2cc.nq.gz
│   ├── 1aba38f67a2211cf5b09466d7b411206cb7223bf.nq.gz
│   ├── 1bc400e5171694cf857164d64435e215dbb29377.nq.gz
│   ├── 1c10c319762668d611e6ca6e8533d7d205165387.nq.gz
│   ├── 1c34bad51a43d4f192b695f53ace1af46a30e281.nq.gz
│   ├── 1ff9cf556c3a0b52e70eeef6c69650663f4411eb.nq.gz
│   ├── 21024a66ca4d8a2d1ce8e6d0b5076f275055af2d.nq.gz
│   ├── 2750ef005e7d3203c08708abf4c00f68c601e386.nq.gz
│   ├── 2902c638d1c3ba0e11888a96fb1b44057a2a5313.nq.gz
│   ├── 2b27ac72ad98f9636ac3e0cba6f3e413dc4abccb.nq.gz
│   ├── 2edc31e4520a01bcdd1e563b9cccb35af074d77a.nq.gz
│   ├── 312a7c8549fe415a3035e1a6c2d04080ae120a61.nq.gz
│   ├── 3206f1028b5c39b1e207d93c965e32609bb9fef0.nq.gz
│   ├── 3890336dd0d8298117064d285894216d97b26c2b.nq.gz
│   ├── 3aef09db421a3d592e6c005a1e5113fbcb500a73.nq.gz
│   ├── 3b7103162e90e8378bcb8506bdf55d32f5b80786.nq.gz
│   ├── 3ba58cf45399d5cc74c21f0cf3c4b9539a41756e.nq.gz
│   ├── 3ffdf89dde02d38c81e25101d75566539a2f2a57.nq.gz
│   ├── 40c71285f4c48c480555a8cb6aa7b62ba9fc3d30.nq.gz
│   ├── 4a03389e7d6ee5ae83fab90ea32632228a50dd91.nq.gz
│   ├── 4c8b474c54f404da4a9c74a69c25a18c0cdf12ae.nq.gz
│   ├── 50a376d706de7a932fa8f243ee6d88fa9edef7c0.nq.gz
│   ├── 5126f59b3aedad53ef0b132a7ce37d3ce57a5669.nq.gz
│   ├── 5313c3ae0ffa321b41b1ae9a8f6fe01c7d2c5ee8.nq.gz
│   ├── 53bd018ea62618e1a3d0d9d550cbfcee03a4415e.nq.gz
│   ├── 54ff01b11bdf1253c80bd6f4b1396ef5346b5074.nq.gz
│   ├── 56d2eb44e18101766c444895bb441ba22c1bb04d.nq.gz
│   ├── 582ddf59e08277fe6e78cee924d2c84805fe36fe.nq.gz
│   ├── 5a97ae816acf834bd5e35617c9af6502862fa381.nq.gz
│   ├── 5c7865b2a2dfd819ee9b2c0c58f72e36c07b18b8.nq.gz
│   ├── 5d7dac47802f247a4497415d5e863d346ab335fd.nq.gz
│   ├── 5ea1f7af804def3075e475abe05f9c4a28301456.nq.gz
│   ├── 5ea5dcd686a81590b51ca2213ca011955c490ea5.nq.gz
│   ├── 5eb45ea6593fc3456d772836ed4cecd6dd11690c.nq.gz
│   ├── 5fd6f66781d3fdcb74489f66aea7ac39b1209fdb.nq.gz
│   ├── 6204ef53beaf56d443c79379f3229bac2bd89c2e.nq.gz
│   ├── 635254e5932e341694d7347a36ab2e93a4c4bb43.nq.gz
│   ├── 66dc5e3a78cb97c1cd3e9491188e5f0e68dc4422.nq.gz
│   ├── 66fa4e29025884b35a5f44217766a71388c83315.nq.gz
│   ├── 69413c7987a2d7fb186c60d27482b500e56e2dea.nq.gz
│   ├── 69626048fa8b3ed311cbed0e368e8b2dd0ef33ad.nq.gz
│   ├── 69ae38bcc3e1c3a96f029ef4bf3be39e434ef046.nq.gz
│   ├── 69fa449dd96e2405945b2e4cff2fd0ab8b102097.nq.gz
│   ├── 6af503acc80a56f8d310b0c2b5905d3dc6b69f94.nq.gz
│   ├── 6c94179e90d29498468bb284b0b683bf90677555.nq.gz
│   ├── 6db47dbcab9eefc95a89938186924ef216471079.nq.gz
│   ├── 6e0b4b86a52c7248e19304fb5087b3db9eb9b52b.nq.gz
│   ├── 6ea4f51989be4a2cf4216ed2aec38eabf4fb3dbe.nq.gz
│   ├── 6f8a9ca81a1a43142946cae1a2449a93ae872544.nq.gz
│   ├── 7071f9cc66dcc14696f3074313b617489cf90ba0.nq.gz
│   ├── 7123108fe47e8c16e38b91a3d4f2e841fc1f47e5.nq.gz
│   ├── 717a45728e08b8ff5ec891ec68e8bb21a3d11daf.nq.gz
│   ├── 7368007eda947aa7a6431a0a350efb540b150176.nq.gz
│   ├── 75f8508c8bbce68181a1d36ee1e37f528d714179.nq.gz
│   ├── 76399495a984162949c792d4a94ccd586b8d1309.nq.gz
│   ├── 763ef01ba73fea2f0a36837cf396a146e39a2b66.nq.gz
│   ├── 76b24852e55667589e9983d1ed732b2614be074f.nq.gz
│   ├── 78981ec72cbebea4f6e1e309be2dc2e582464e46.nq.gz
│   ├── 795976d614fbddc7c9a050d27161d720510be889.nq.gz
│   ├── 79f4f2597b182dd764c7911465862fa90d490b88.nq.gz
│   ├── 7a5d09cedaa755f583575fac7a1f56623c686407.nq.gz
│   ├── 7a955c9221669700d6168fb3301c04bc68273834.nq.gz
│   ├── 7b19785a346d2715a7b0d154a3506eab57c7902d.nq.gz
│   ├── 7b74840147ed203ff25037d2ab3aa0dc0f8d7546.nq.gz
│   ├── 7d7ab703ff0c168d7ef7063643483fbe1e50b9bc.nq.gz
│   ├── 7d9456d99d2300be438db9c591c877922b37c9a6.nq.gz
│   ├── 7ded11928fef3885547e5f84c8e6ba4ab2080ea6.nq.gz
│   ├── 7e375128d7d10b826361cffe9f21a27eb5bc2913.nq.gz
│   ├── 7f2eac54b62aa42a627f52bdf8ea350e9b8f0527.nq.gz
│   ├── 8009d5ca184f65fa44fee9c7b51ddd8c7e9a59ad.nq.gz
│   ├── 80d4c561ce7a0d51541549166a0affbc094a0e76.nq.gz
│   ├── 812661e03cbd055e80ce754a2767d45322440f01.nq.gz
│   ├── 812662040c8efdda161294ec7230d3b20b71b413.nq.gz
│   ├── 81f502f4cdcdf798c1e08a839c072b78e4312171.nq.gz
│   ├── 8237dec5a2eb0beae62835cd2bba1fbf35a86109.nq.gz
│   ├── 8317c3bae9bee9b745fef4d0fb3f2d52428d3e97.nq.gz
│   ├── 8342109af8e3b3a4b7f90ee729702ae909aedfe1.nq.gz
│   ├── 835d78b37dc6aee304aa3cd95c7c744b6eb7f631.nq.gz
│   ├── 83fbefcc33906798a7c4dae1d8c546bf836610b4.nq.gz
│   ├── 8484ee50e93c6e8cbea839baec5dbf4a92b19fd3.nq.gz
│   ├── 85ff76b7f34f9abc8f910e03a1576bfe726a0de5.nq.gz
│   ├── 8602cfb5ca9df37fd026dfb0e01f9d2939b89b73.nq.gz
│   ├── 86d17b2300b94f58693b8f099c0184598e60213c.nq.gz
│   ├── 8b7529a51dd651948e8403a8b82daf96be085161.nq.gz
│   ├── 8c27ebf8b759000eb9d21dc10c6a1faed3b9dca4.nq.gz
│   ├── 8ddfa76c172060a80825cfec446e8675460aa67c.nq.gz
│   ├── 90c144d43d552bab94ba717939f21ebd192ad57d.nq.gz
│   ├── 914a4f5a233dede578264860912339428c96a3e1.nq.gz
│   ├── 96b164bd5225c16b8e6ef0566491c78e3338978c.nq.gz
│   ├── 97ec1da2e5f0e647a9a9f8891f579e1436a025b1.nq.gz
│   ├── 981b8097d2190c7a7c73b4a3757f063261260be9.nq.gz
│   ├── 98272d87a69a92aa3a0564bb526515cd9f278459.nq.gz
│   ├── 987c11614d8be6370dc7b7a5ac758790714523b7.nq.gz
│   ├── 995aced79014b06bc133a895dbf61d15afb0c572.nq.gz
│   ├── 9a6ed554eebffb5c8831bbaf78b39e5b7a249c5f.nq.gz
│   ├── 9b6db7cd4da8a6ce96c0d82200f4536b72dacb64.nq.gz
│   ├── 9ba5e5ce115447e0cc1bd219d83c1d283ed29ed6.nq.gz
│   ├── 9e14a47c7ea76e2f93dcd419e54a019287d06950.nq.gz
│   ├── 9e3c8f24d32022410c65cf21a5a032025f2814d4.nq.gz
│   ├── 9e5b130c4322a0042b26957c5e25a367f33f6c64.nq.gz
│   ├── 9ed9ec5be9ab57abcf7944dd3fd489d613386b1d.nq.gz
│   ├── a0969a9013fcd5afcb912d89b95bc3cb12dd4cdb.nq.gz
│   ├── a09fe0b6017ce2719a7ac9502e396da273a878bf.nq.gz
│   ├── a40d0767e10df69b388d9853d04d8dc6e3ca9cea.nq.gz
│   ├── a413f070ad39cd2e0976a92eaeeb9900be405079.nq.gz
│   ├── a7cfa7bcbfc57f3f5eef6edd017739a1bf634f0e.nq.gz
│   ├── a7fee83aeec02765916f42fcac4924852a664d80.nq.gz
│   ├── acbe7bef61696b4ddbece30680fcb6d9c08609c5.nq.gz
│   ├── adb23c5d4dfe823cf8b08fd5c3b134136325ec2d.nq.gz
│   ├── add4370a7d11d0052c2387421fb74f7edf2f33bd.nq.gz
│   ├── adfddd573e30607f803893d34524de4cdd56aece.nq.gz
│   ├── af5f6c8a2a2ffbc954344133e7efb4851ff5310d.nq.gz
│   ├── afc4eea8a0fc7229d3076218e59d4ffa72c050f6.nq.gz
│   ├── b15f4fb3dca9913bc5c6acae50fc5c25eec7928e.nq.gz
│   ├── b32a48046694ae1dbb999f26c4676b7e2b447a72.nq.gz
│   ├── b3e59010d4135236a3c62ba980c686b4ce36c5e0.nq.gz
│   ├── b443f27f9d8fc2630fbc2536bb2c8ebff2df5dad.nq.gz
│   ├── b5476ea3b8715e2896efb50d2c8f54c6d6860bf5.nq.gz
│   ├── b61cd5171f3e3cfc7d9ab9c8413dd74f114b36e2.nq.gz
│   ├── b67443ae65467f5c292fbe2371c764eb60003c45.nq.gz
│   ├── b6e47617de110dea7ca47e087ff1347cc2646eda.nq.gz
│   ├── b90abe4ff383915eac6f6da874e1dd0608dfc5b9.nq.gz
│   ├── b9b09f0c9f1bac35355f7e36d2594eb36b87e839.nq.gz
│   ├── bacffd4828f0f793b6e66ac6d77fdab1393b4363.nq.gz
│   ├── bd8ce07d1e5729b753c283595840c2e8dcb5dc1a.nq.gz
│   ├── bf09a89a7b22ab168546cdcd2be339c70dc17438.nq.gz
│   ├── c012ed716ee3abc63554a61e19235d7bfc9dc109.nq.gz
│   ├── c5af1577234a1c1c041c3f48dc3db09ea22cdb7b.nq.gz
│   ├── c8015cb6d081a6b61475b36b22a5d15d3bfdadf4.nq.gz
│   ├── c8352620b5efd974bb9352177ceca211a32ec40f.nq.gz
│   ├── cad068520f2771c8ecb24daed4ef12900f9e6a01.nq.gz
│   ├── cbefd9860a7c13c8a82f11dd1eea4b5b7e19f86e.nq.gz
│   ├── cbf0655d6084177392927742d5a1dc24de062db8.nq.gz
│   ├── cc8db4e8ad089a99794377c72340dcba877ccbfb.nq.gz
│   ├── ccf5c8071f1c6fcecf4950454bfb141c2c1c3594.nq.gz
│   ├── ce26e60a55ec23cf2832d0191d594ad327062219.nq.gz
│   ├── cece8d7ec99baad5d6717df5954d05ccf3430ada.nq.gz
│   ├── cf7bb154d2e977190acaa8fcbd60686d144208b7.nq.gz
│   ├── d0b1794a081a394c1583905d8a1401c435fe0670.nq.gz
│   ├── d1050fb69e5504074591f6a38d7b0f277a8c5c32.nq.gz
│   ├── d14780e731eb0d013924a8e7dd8ecf5025fad484.nq.gz
│   ├── d24a7ce00ee416e426d7a5c3d9bd8b737af39b70.nq.gz
│   ├── d29c9d3f027d1792d49144d510ab8d0c4e6ada2a.nq.gz
│   ├── d32626af276310f8cc4f2c288c495b0566ce3972.nq.gz
│   ├── d861e04fc880076408acfba79d3262de092c05d4.nq.gz
│   ├── d8d4c4f8c9dbb5f01f750cfa7bf4a02014d748e5.nq.gz
│   ├── dda9865ad01e8f6ecebfc69f0889c81050a594f0.nq.gz
│   ├── de135ddf3a0be472f7466637af9a57e7a7631adf.nq.gz
│   ├── e303c9e2bd48b1bed7013725028964f20bd2627c.nq.gz
│   ├── e525814cef2cbb15d1962098f9236a84b4a73fd4.nq.gz
│   ├── e5c1c1aa957abdf6f8b04623c91062c8c9b0d5ce.nq.gz
│   ├── e5f4e8f65576ff57f3c5ed043950b9c1b74d99b1.nq.gz
│   ├── e63cac8fbd6fdc59660806191be28e7b9bd7e32c.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e80b36308d1f36534fb0b8c093e257737d523692.nq.gz
│   ├── e8678444df61d7bafa5c4db466f60a7ac580c80c.nq.gz
│   ├── ebc85a3b26ffe8872b0590320790df20fac7989c.nq.gz
│   ├── ec9949149dd24b52895ed7aba19284cdb19ef429.nq.gz
│   ├── ecaa75d25736b812f8fa95ccc05195ec3cac20fd.nq.gz
│   ├── eda4cf21628cf30e392b67a56acbc73b52b6ff66.nq.gz
│   ├── eedf163db50a18c6838899d0976fccb2fc39f7b7.nq.gz
│   ├── f079d6aa40dbaa64f3cb9e133fff59118dce5ade.nq.gz
│   ├── f0f3b0d6f0dc1c32659d336f3bd357963ef50bc6.nq.gz
│   ├── f102baabcc1415999b215df6e19147bad596067b.nq.gz
│   ├── f331d1a14d31ffeb0e29e3e1298b1af82545cfbd.nq.gz
│   ├── f338753a8d54fd5cce738cff9792ca9d959e3aeb.nq.gz
│   ├── f4f854949c55b880bb6de8b825cf15ae98ad6ded.nq.gz
│   ├── f70b39a7b079818b75b2987debe5c453c1a7d742.nq.gz
│   ├── f9a3d6cbc29c867db5c3bd4ca61babc197d6764d.nq.gz
│   ├── f9c18dc5d6fb84e59f73f4d2b1d23e3d99c721e8.nq.gz
│   └── fc7dc9389298ae411791065678e62f9377afbc84.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 229812436726fd9b1af85c6e66ff8c81b415758d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 198 files
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

[executablebooks/mistletoe-ebp](https://github.com/executablebooks/mistletoe-ebp)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
