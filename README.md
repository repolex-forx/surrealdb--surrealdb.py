# Repolex Knowledge Graph of surrealdb/surrealdb.py

RDF knowledge graph data for [surrealdb/surrealdb.py](https://github.com/surrealdb/surrealdb.py), parsed by [repolex](https://repolex.ai).

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
rlex download surrealdb/surrealdb.py
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4f2b9d784cbc7d5865c4c7aca48fcda4354a2ff1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4f2b9d784cbc7d5865c4c7aca48fcda4354a2ff1
│           └── chunk-001.nq.gz
└── blob
    ├── 002a659edabf2eaf44d089d89632f43f291160cf.nq.gz
    ├── 012e435e4f7c51d511dee206e6c96b29041a1608.nq.gz
    ├── 01a7b61702a70df1f4509b1c3e3093b3bd01a450.nq.gz
    ├── 01d9b76bef459108fe7689668ebac36262dbd18d.nq.gz
    ├── 01e81856e2253b81237fc521d314cfa13a43c166.nq.gz
    ├── 021164c2d2b2dfdc25848b7f9b60a85bd41789e3.nq.gz
    ├── 02bac21720879404455daaeaf90810cc0da517aa.nq.gz
    ├── 035fb0079771c40e0123a14a6d494e770c060b67.nq.gz
    ├── 05c01fa8bd5f3df4eeafea1fda470fc6b9b96046.nq.gz
    ├── 05fd64c0540929a8513c6e2a2cb91bd87bd20f42.nq.gz
    ├── 06f7cc2e81dfb2f7ad4d40374e0d155a8cf4e98b.nq.gz
    ├── 07f10a987793b4ba1ef04cf8a7dbfbd5fa18c87e.nq.gz
    ├── 08e720b1520af5491b3a5bc8b1398feaf4a0218d.nq.gz
    ├── 08f3cec47116e160f5849881a259723bdb6bb9e6.nq.gz
    ├── 096eb3717d1d5cbafbae421006d03d87a756a538.nq.gz
    ├── 09e31619bc36071061e049533c21e66dfa5f99e6.nq.gz
    ├── 0aecaf69fc515e9b514bd9d686bb9ba39796f2ce.nq.gz
    ├── 0b581b1fc29a4653119d4fd153f356407c4ad293.nq.gz
    ├── 0bfaf9a77d7548ae517e52b944f29553aebdf2d8.nq.gz
    ├── 0d16310d3fc3ab29bc8e6fbf12471c205444bfe8.nq.gz
    ├── 0d7d0f08d7b5cf98f44ed4a11609e7015791caca.nq.gz
    ├── 0db01e9df64d346056b7ed13a5d19dcda91e5cbd.nq.gz
    ├── 0e78182a83cc79af609dea59d79c4afac297d872.nq.gz
    ├── 0e9ab17ee462d891cc8e1982b501e7cb2d3da2bc.nq.gz
    ├── 0ea1a71e9d2d2bc4b06632313d86d03ecad133f4.nq.gz
    ├── 0fb1129b5b24e0b1b3ffa8256c6f019e693d43cf.nq.gz
    ├── 0fb6a7c610706aead557839b1e3439148b0bb66b.nq.gz
    ├── 101ede5466518de89b6f11407191a72850d47c7a.nq.gz
    ├── 1065cc6fe9d99a5712d082c0f780f1fa7918ef46.nq.gz
    ├── 12051b293ddf587427ad7d5698fe2de1b2768ddb.nq.gz
    ├── 130d2ec1b1adf8ea03eac96969ccb0c2d9173583.nq.gz
    ├── 13be92acd42e0ea18c7f768ff63ba6805af08ef5.nq.gz
    ├── 13c08cbb29aaa898db824b5dd33ac847abde55bc.nq.gz
    ├── 140943af96b240d9090c36c744965727898e1cb6.nq.gz
    ├── 159b70d189520324e625b3e7384c30c29f674b85.nq.gz
    ├── 159eb4446a017d97b5897dc319f76fa0603341e6.nq.gz
    ├── 1661f0c4225162b8f72bbde04ef68de87bc3f2d0.nq.gz
    ├── 16ae4bba87e181bfaa085cc1706a56fd7b89eac7.nq.gz
    ├── 16e23fbd01ec6739c090c05ef2da65734639e9c6.nq.gz
    ├── 19258c8692307dd803a12a1d83e327e8115c2df9.nq.gz
    ├── 1947cda51290b22b071c0697dda240bdc139164b.nq.gz
    ├── 195fa988fe55e2664346833f46a27cc88d0ea4f8.nq.gz
    ├── 19a9c6039f9a590d694f03b4c928080cb530f95e.nq.gz
    ├── 1a4622de5e984a86ecdf86923858be30e424f46a.nq.gz
    ├── 1a705455dc269bf512b0ffd0568838dc3e1149e3.nq.gz
    ├── 1c0299a602914c734751d8f6c8c3342a9833261e.nq.gz
    ├── 1c9f3cdc1fe62c5de9965fa153535c4f51a68f92.nq.gz
    ├── 1d8a5f21018f488389898c3cda45b1c80de4552a.nq.gz
    ├── 1e8b362f50b6574711006f449ae7fecb12f0f894.nq.gz
    ├── 1fb18fb3e34c97311fbca0ca4b135daad4076236.nq.gz
    ├── 200443ec81a09db42cea6e0a9266baedf8363d2f.nq.gz
    ├── 205394f96568e87b89aa60ecec1a40711ec3c93f.nq.gz
    ├── 20ca29448792f08b444c887727a389436233c244.nq.gz
    ├── 21a3dd52fb731cc819703c523a9e0c3d97d189fa.nq.gz
    ├── 21e66d883407bb1471f8f83c156d17269a9f192a.nq.gz
    ├── 221828af96482ba1e66d7c91612d69ddb5532875.nq.gz
    ├── 23f90b684251967072ac233da98cb84576871a4b.nq.gz
    ├── 23f91461e95f29259d570983d6fea25a4246268f.nq.gz
    ├── 24c73ed5974c700fc23be20e35fcee02a2c28d9d.nq.gz
    ├── 259e2c56d4e957777b2b4a139398273956a6b2d6.nq.gz
    ├── 25d468a903bb6fee756a5c5ac6d183ad85419df6.nq.gz
    ├── 265fd357ace5f369958a4e055bd31bfbf96f6112.nq.gz
    ├── 2765d3405a66f3b8bce7166d7676cdc90d44ce01.nq.gz
    ├── 27c65de3feea87584eaba18d5ee6ceeb4e7781c8.nq.gz
    ├── 281ed7051dfe3f226f8015c84fb6aa7b83b62f42.nq.gz
    ├── 28973b3bc92853ea327bcd8731c71bdd8da25c75.nq.gz
    ├── 297f4a59d921cb439567464d8fc44b08442e74be.nq.gz
    ├── 2a37ae59bf7765dca40cd424bc0aea206aa185e2.nq.gz
    ├── 2a4dddcd513ae4dde1e8f9015b013de83abf50ea.nq.gz
    ├── 2af1beb4ea209749ec51c4c0d4b0a87b74fe9fbb.nq.gz
    ├── 2c0bcbf3a3fc4d7ffa6a4eebdd4f15749a70d118.nq.gz
    ├── 2c131657341de737d5facc6e19220eeeeb5efcd9.nq.gz
    ├── 2c378770672f48e4f8778ced7b2b81f26d5856af.nq.gz
    ├── 2ca7634bdcd560dd1a683a6e0a353c1b18402e24.nq.gz
    ├── 2d540054808743310dea329cd3aa4d650c0e225d.nq.gz
    ├── 2dbedd6211274f98cd106e26cef6ffc7d0fc9d9c.nq.gz
    ├── 2dce621d28d162c66c4b6caa78a3e25f2e2f52e5.nq.gz
    ├── 2ec33cf7c717b4a3e5948194160cc826226036eb.nq.gz
    ├── 2ef92be45fde3324b5cb0a313a51f4cb47d0b544.nq.gz
    ├── 2fc0348a455fb3593a7c19159ed6f24445309e94.nq.gz
    ├── 30397ca78405535ed287fe3091968c275627a31b.nq.gz
    ├── 306012842e3b042c8273a0872d86ba17484effcd.nq.gz
    ├── 30b058d1fe7a66e645af82183205edccea0fef6a.nq.gz
    ├── 30e41845a149193b7bbfdc92699db9ddecf1a167.nq.gz
    ├── 3241c898977777ece25f524d251a9d17cd052d1e.nq.gz
    ├── 32611ac794e6c02095e6d925773592a40c855a95.nq.gz
    ├── 32fdc9b7fd63c03de0430d9d48d4e51eb24ce803.nq.gz
    ├── 3313b773aa14ab0d9ee6f2a008b9f6e077b38d75.nq.gz
    ├── 339cc5c2f6bdb1f74b5e26701173fa256660addf.nq.gz
    ├── 360df4927e224f73d1748ede35bd504cb19a9923.nq.gz
    ├── 363935d467c9128aea587e81b4ace68af09895c3.nq.gz
    ├── 368da6e780449021d8a9fff40b91262fdfa90f13.nq.gz
    ├── 370714170b343fd50587e4001d2ff90bb6308356.nq.gz
    ├── 37537f8b04741d80da8ff2b301b8d4e2ef38da55.nq.gz
    ├── 3821502e536ea2486bd31fde612963c88ef87a8f.nq.gz
    ├── 388345b56781963e5cafd9da41636ebc30fa3976.nq.gz
    ├── 38e2069f0c9943540b527757afe311fe5a3ec957.nq.gz
    ├── 38f63c1a1d5cb6f0ba313e61e8b2e2b360b116cb.nq.gz
    ├── 39153461acd82c79efec9619ee90dc13e974cde2.nq.gz
    ├── 392c5693f139bc4be923049fff3f0624c8b33900.nq.gz
    ├── 3a9b114837bf6dba2a5b3a94ebf81b64957a24e8.nq.gz
    ├── 3ac60a5280077040756d84ea7c14dd2741d8458e.nq.gz
    ├── 3b937ea0d9b8a52ca87963adbd54c94b85a103eb.nq.gz
    ├── 3b996f59f492373e13e2f0f3e84178c54d1db2fe.nq.gz
    ├── 3bcb0221decdface23534595ccdced95fd50d6e6.nq.gz
    ├── 3c777248f24eb28d3387c428789d2e13b9728873.nq.gz
    ├── 3cf26c937e56b8ab8b4c0bff9ab52f957ee16abc.nq.gz
    ├── 3d5da11755a23c4b9ae8cf70123e2ecf9dabdece.nq.gz
    ├── 3e208ca6d63c5d3f0769d70b246d9d5a7f4f5c03.nq.gz
    ├── 3e24176cab4ad80e79f3ddfb86773e09192e0a5f.nq.gz
    ├── 3e246f5b47f8118ab01a201b2d2969b61a5516d6.nq.gz
    ├── 3e61d3589fbc1961539ae43151a2238eb43f4b4b.nq.gz
    ├── 3e7bdf71513ab71722d9fabb806b5f8e53d97538.nq.gz
    ├── 4002a10af2face083b35845d044e38d0adf85578.nq.gz
    ├── 4371bae895d31a84e8abf07378a3d0e82e7ca32b.nq.gz
    ├── 43bdb7a2d04029744a87f72f3e6e72705fa42935.nq.gz
    ├── 43fd69e9813c038a8f4887793a6f2b542d8223bf.nq.gz
    ├── 445ab47ec0bebd2e0f2b7e77645091c175db09f4.nq.gz
    ├── 455f01fc94e379a9158885d80edaaa93185423c7.nq.gz
    ├── 4566dd593baac24bb43d859dd965dec53cba7564.nq.gz
    ├── 45a172c3b09ca7742a952b277b6c0ea5d2f7b778.nq.gz
    ├── 46a52c0e066913d13928e90da0cde09a1b2dc5d0.nq.gz
    ├── 46ad02e75f94265cef474906dd61ed12b4eaf2d0.nq.gz
    ├── 46e4d491550ad4152282505711e95fa434fa01e3.nq.gz
    ├── 476c2cc66895948aad4308422941407b2e129b65.nq.gz
    ├── 478b988e67df6f798bb7f1926f952f2d5872868c.nq.gz
    ├── 4800fb2254c628a0a306a59a367299658937dc90.nq.gz
    ├── 48d14e805304e13a4544b87ddc4bf339884457a7.nq.gz
    ├── 48efbb2e4dcbf42ec3aedbcf690faa5c0322a9b6.nq.gz
    ├── 493968668213ea92886218f593fbcc7bbeb42805.nq.gz
    ├── 49e4d81c144be6b565798879b28dc3e2267ad965.nq.gz
    ├── 4a026893278663c9b80786e593cf417aa534f9bb.nq.gz
    ├── 4b12e4a1a1fbb86b40641313b30fe63b97ce1f24.nq.gz
    ├── 4b4da8cd58239b246228675f0c90a7209d2c8b51.nq.gz
    ├── 4bb1d777d3ab9da4b6d4e6a05097970caa449119.nq.gz
    ├── 4bfd29b3edcff8076db968bfb90e62974f485868.nq.gz
    ├── 4c6c97d59b9290d115e88f0b6ab4db828b36c9c7.nq.gz
    ├── 4cd9356581f420ce37c9e353babfbcf590486531.nq.gz
    ├── 4d33d55e516ea6b8da656572fe2d3cd8f2f6d8ca.nq.gz
    ├── 4d580374f89b4901a8fd3804d530d4a32d2daff6.nq.gz
    ├── 4e54eb44fa79dd43a260741160f89644e4152d6f.nq.gz
    ├── 4e64bca540d9d63c65581d8f5387d62b3c1580fd.nq.gz
    ├── 4f131f6f28e77e8e91e9aee7a0b63f6645cee5f7.nq.gz
    ├── 4f588346850dc525e1fbd5c244bfe6af9710cc74.nq.gz
    ├── 50e9293aa5ef6eeef007eceeeb7a0e1dc6cc5a6a.nq.gz
    ├── 518c67c60e080d247abb6b06ac31748a72e056b9.nq.gz
    ├── 51aa5927e96b793a1f58073ccb87075434ac04fc.nq.gz
    ├── 522b911ea57b910923e27ff3b28ea929381b46c9.nq.gz
    ├── 529d56d78ceedc0a5908e3b4b86366e6db2065ad.nq.gz
    ├── 52a305dec43d4e965d2caa2a9fca256fa0f174fa.nq.gz
    ├── 534e9259b275577f7efa1c5d2b2c150182a96333.nq.gz
    ├── 53bc60a1ef9860f140ab2eec2f15d18499118fee.nq.gz
    ├── 53ddb081f222d37441b4238f20b49389d98b84ca.nq.gz
    ├── 54e5710d16c721c7b2e3a28ddda9e1d213579066.nq.gz
    ├── 56471455bd36517bd6c00edb24ead39406d9912c.nq.gz
    ├── 570c7b033ac91b7eadabb8e71afdaa057a9af378.nq.gz
    ├── 57d83db1988d846dc36d6ca1fee4743a95e1d326.nq.gz
    ├── 5880b073bcd38399624bde7b5496953278c5d901.nq.gz
    ├── 59ba5d68024fd5add5dedeb253bc3257700df971.nq.gz
    ├── 5a377b816175117223fb7de63c6e164edc7a603b.nq.gz
    ├── 5a79effff34b99be40523b4052a9c00615d82f34.nq.gz
    ├── 5b43b71a511895827e86118b8c3fd94e9d24215f.nq.gz
    ├── 5b4a34fc6c63e2f31b1d8e5e1ba32d08c8bbfb87.nq.gz
    ├── 5ba3b4441b1d8896d37e70725ad49e1992af9209.nq.gz
    ├── 5bba63cea6e9582d25601029f5dcffe8964cef14.nq.gz
    ├── 5bfd3dee1c1ab583cae5a7b6b25e8444178ce5be.nq.gz
    ├── 5cad36cdf38550975e45cea482e5d559ce79c11d.nq.gz
    ├── 5cf316ec68c42ef300d9db1af08bcd87a191eb54.nq.gz
    ├── 5d67dce8346491ace846c99b025e349fe813ef3c.nq.gz
    ├── 5e158ad83ab5713cdd80e1a75b01412ac8f021a9.nq.gz
    ├── 5f2482de48f5e9e3c75431423f540aeca49ca37f.nq.gz
    ├── 5f41c286389cd96fa63e9311e4c3443054ee6cad.nq.gz
    ├── 5f63ce3d496b5d01b3ba4cd0fd8750d836ba19a9.nq.gz
    ├── 5f8746bc8248fd3fed232fa175af515d3773fc88.nq.gz
    ├── 5fa398b51499e1b8142cffe10bfbebe3b78fa4ef.nq.gz
    ├── 5fdd88a932473af6e8d166769739c5316748e3d9.nq.gz
    ├── 60879e293cbb673887b87dd80b5863c252624d2c.nq.gz
    ├── 60adc0d2f3c4ffbe36d32f6e60d75a32e357a6ad.nq.gz
    ├── 61870e24a991a3d7b8e0818f476997e18d7dd77a.nq.gz
    ├── 61d913bc909c07c33af11984bcd5cfb76cbb972d.nq.gz
    ├── 61ee8b18013d723dcceeb4548a794575647450ee.nq.gz
    ├── 6203ee940f2c9daabd94eef97adc04d9ed9bb408.nq.gz
    ├── 639fb8cc98218a8a14fa17f323d929ab6c9255aa.nq.gz
    ├── 642880e8b42f44c92a2f0f3c329b85b9420cc732.nq.gz
    ├── 65d739a118b7131c8610d19276c7497f9fccc742.nq.gz
    ├── 65f46f594b0c50d6181c7e3a997aef1bdd6452b9.nq.gz
    ├── 666579e071c0d48b323dc396d4de89a0530f4592.nq.gz
    ├── 66b88abffb5063741a08923aae8ba9d771585c5e.nq.gz
    ├── 66e88ca0864aae3c4bdfc6800294f61cd8b8b469.nq.gz
    ├── 67e433aa802342e1bc270c297290d2d27cd9ec5f.nq.gz
    ├── 67e6638bd100cfdc4021da43ce8b9c1a46667ca3.nq.gz
    ├── 68ab7d78fc0ecf59958e17b01f6a85a268528717.nq.gz
    ├── 69bf840f2d201c378d12b5da9a719c3464df1f2e.nq.gz
    ├── 69e32680c1196504d20f8c1e182b919f67093085.nq.gz
    ├── 6b29b16f6c99824b0634a5aa5aada3ed0993501a.nq.gz
    ├── 6b8982cc51259a33b01218ee5c34c42a47b3ee1e.nq.gz
    ├── 6c4a6f2c239a3c4622848235f7ee465d56903573.nq.gz
    └── 6d676df954086e38a1066ad25465e8e74ab5b321.nq.gz

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

[surrealdb/surrealdb.py](https://github.com/surrealdb/surrealdb.py)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
