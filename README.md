# Repolex Knowledge Graph of UKPLab/FEGA

RDF knowledge graph data for [UKPLab/FEGA](https://github.com/UKPLab/FEGA), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/FEGA
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c4938c332851e7d10258d5f49899e12fdbc5e517
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c4938c332851e7d10258d5f49899e12fdbc5e517
│           └── chunk-001.nq.gz
└── blob
    ├── 004baf280300d75cf7128301cf6e9453476a0f08.nq.gz
    ├── 00b45a522aa41db7500391e02920940a6c4d871f.nq.gz
    ├── 014a67383bfa9c1571cbdc52af367459c73298c6.nq.gz
    ├── 04a4a5a3594d3e8b6c4b102522bf4ddaabd1108f.nq.gz
    ├── 04c503f60d10e17d4614fce70bd687c6e5b8da9e.nq.gz
    ├── 04cbfb5404ffc5c0447a4e08e04f2ab296aeb32a.nq.gz
    ├── 0563281c8ee20d00f6016e4b395ec473108aa189.nq.gz
    ├── 05715c6785c924b14670f8fe5fcec6acbdfb6219.nq.gz
    ├── 0668b15ef2fdd71d8f01970ec047fd9bccb9238f.nq.gz
    ├── 06a6d2a06efaaa07a866cfd55ea26ec9b6a0562e.nq.gz
    ├── 076c7bf6400c6b4735e6f39424ec7cc1724320da.nq.gz
    ├── 098a991dfa505c969428018699d11775d034464d.nq.gz
    ├── 09a02b6ede1342d3579247cfbf55d506250683d2.nq.gz
    ├── 09a5b3d31217981b692cf5a1e68db4e719b8e0a3.nq.gz
    ├── 0aed5e888badf5b4ab01bd145d464e78426d0789.nq.gz
    ├── 0cafb85ace9f12d566cbde06eeb61152d3fbd7f7.nq.gz
    ├── 0cfed59d0c3b40699e939c3ca48bd1e2399d1d51.nq.gz
    ├── 0efea6f7b602e3b0e9cd530840f05a065de13ac1.nq.gz
    ├── 10450890bf6dc83712ddc5efb9da9bf8c16add0b.nq.gz
    ├── 10504c31d60d2c7562f9442833e79a5fa5234df6.nq.gz
    ├── 105b716a9922116eb3a3864fd6716c50ec55ac48.nq.gz
    ├── 11997668777287ee41e2854d6057d5d20de29e53.nq.gz
    ├── 11c8455c1d62f8717148c45d02978d32edce994a.nq.gz
    ├── 154c5b03e07b46c3f8f352d0692798ecac0acd3a.nq.gz
    ├── 161d33005178a83dd28f46dd33371b291ab9c0d7.nq.gz
    ├── 161e2460f8cac1eb1eb71ba673ca449e5b63ce2d.nq.gz
    ├── 167fa176badc7040901ae12d8c0851239ead4e3b.nq.gz
    ├── 17fca138a9426979d63f10e1d0ddf53ca780f4d1.nq.gz
    ├── 182a2c874345da09eb1510f31dd7acb7ae360e03.nq.gz
    ├── 183c60fb2712669278b53bb0b3e7b2373fb03992.nq.gz
    ├── 18989314d099f1a6e99b2887939b0cf470a1e75a.nq.gz
    ├── 19083717eed2fcaa0d6d61446e8218249f73ee06.nq.gz
    ├── 19487bc7bcf8c25373beda129e3fe958158af5c5.nq.gz
    ├── 19ad9296ae2b09947abf99e3326eb5d8e1562ae8.nq.gz
    ├── 19c4133e1845435ae0c5332145b84120696c99da.nq.gz
    ├── 1abbc0850d591ea9ad77679240b58ec9b28b6fcd.nq.gz
    ├── 1acdbe77e61aace9fc2cb948ed09fcd8315794ef.nq.gz
    ├── 1c79c7fa51a0a964fdf4da43325c797906e91e17.nq.gz
    ├── 1cea048797feb789e94fb359f085fd7385123ecc.nq.gz
    ├── 1ddd09c2ee27c2df785f8799d1aeb9b2ebaa20b8.nq.gz
    ├── 1e9575502df54ea746646970b2b1553a075d99c5.nq.gz
    ├── 1e99fdd925d1540dfea67f5722684a42c4fca0c8.nq.gz
    ├── 1ead89515a2303497825aa5556183fd664fc3d66.nq.gz
    ├── 1f255eb1cfae94d2929346a79eed80edd5f73c93.nq.gz
    ├── 2071f9187aae66628dfa7334c384fb3026f315e0.nq.gz
    ├── 21ba26c5738c2f712d717bb9cab9ebdff9e9bafc.nq.gz
    ├── 230dfd870216346221fcf77e81e65c77896fc1e7.nq.gz
    ├── 23d17e83762369ffa069bfb2ec56ff1db9d8dcf9.nq.gz
    ├── 24eef67cfae524a4785cf3f86743e16699fc56ac.nq.gz
    ├── 25086884154771cb2ca9a41833cc4f0897bf3da8.nq.gz
    ├── 2563a7a665ea22e3fbae1a7d369673386d218743.nq.gz
    ├── 262889671a37abcf54209f79bc1bbfda73b16eb6.nq.gz
    ├── 27565e2c0897ec94476ef224e23a719456b9f709.nq.gz
    ├── 27ece499849c3a97ce16725fbe184f5139d30f8e.nq.gz
    ├── 2968e275bc7af8945698ace5429b89c03a141b7c.nq.gz
    ├── 2aa386247ce6a267e425a4a6d962c072c4abd88b.nq.gz
    ├── 2aba25b2d5d0343d9d460e9d4709263957d84d38.nq.gz
    ├── 2b8010381c8a7ce694135256c4eba6e5cf5f40d1.nq.gz
    ├── 2bac617ea7b6f2cd495ba3029a87efa5f8526d92.nq.gz
    ├── 2c6c2e9b08388144bd10005f3e08a5afb87aa776.nq.gz
    ├── 2c99ec3d14cf88d896b4df919a50f49b470733c3.nq.gz
    ├── 2e8381f953604a3dd5824958fdbe88423a4ed843.nq.gz
    ├── 2eb30dd50ec6387a4352598f1f3fd108ac437837.nq.gz
    ├── 2f4826741a84b8f1091081c6481e5e5b449d742b.nq.gz
    ├── 30a6630cf66b6abc52da9e3e0a61df94532a0442.nq.gz
    ├── 30dc8cf62a54891279fc39b759e689e0e38fd5b0.nq.gz
    ├── 3126760ecf46b2bec5a4aceea8faaba2fd6b6734.nq.gz
    ├── 312be83b39ae1dd9ab568a5596a24eb3aa8d3f6a.nq.gz
    ├── 3135eafa0fa4aca6ff079627a07b1fde59f69574.nq.gz
    ├── 31a07fc6d1a89168f795581a61cae03e36ab2fc3.nq.gz
    ├── 31c613b134cded6cc476b02306db7793006dbe6f.nq.gz
    ├── 329a078e67ce5a2822e209a5d00e1381da7094cd.nq.gz
    ├── 32e6d7b2f718173266f6ef7e63053b455fd4a9d9.nq.gz
    ├── 330d3e5b3c4ac73d4d273158409c4202d80577c9.nq.gz
    ├── 343ca96098a761c3fdb0f6779b8fa28937acc7b9.nq.gz
    ├── 34f995f967569f123b6a2eff1de646a85f8c3486.nq.gz
    ├── 3516c15d06aaa08f382d2639a76248bc508ddc03.nq.gz
    ├── 35ff17dae57916f83acd48301a56eafd62aaa7eb.nq.gz
    ├── 364736e0209877f90db3707546a989906d55d601.nq.gz
    ├── 377010a0c39830a9edc2402e630b84c7f63e0b43.nq.gz
    ├── 378cd9d2319b3594bcd92a62451c1ceac75c9251.nq.gz
    ├── 382ea4b2a5e6aa7dcc641f497f9b8b5a44369f87.nq.gz
    ├── 386318c1bbbe5e2046eb05bd1beceaad5ed29a2f.nq.gz
    ├── 39274bf87b27d409d543907bdd3e1ee75724e7f6.nq.gz
    ├── 39f5bb2a56d4001d7e8aa99e8af940f31eac7eb9.nq.gz
    ├── 39f9ee3ae166da7560a6aca9a6c5829733dd487f.nq.gz
    ├── 3aa1787b8527986146eb5c9577fabdbc9c81bc93.nq.gz
    ├── 3b0305f45e242025a618c027620ebd5aee40ee1c.nq.gz
    ├── 3b158958de3843f464bcb8f064b7e60b54ebf456.nq.gz
    ├── 3c611ab2b742fb12d74ea74c8f3362df05becf39.nq.gz
    ├── 3c798e0eb8e19404d40cb5c1ffab1ce309bbeb18.nq.gz
    ├── 3ce55a69ae6367ee3ac93a98ce7455e9f01d9ed2.nq.gz
    ├── 3daaa78608f8f47eb07a86663815db1764455639.nq.gz
    ├── 3dc524020e430d80e456c4eeac8209756fe73f93.nq.gz
    ├── 3f8ca7960139916a6357a2e77004dd898329c884.nq.gz
    ├── 408836b2ad352f4b29129e65f034b906979f7571.nq.gz
    ├── 40a66d647f6e51d32f4c98fca7878bf9d83b3ba3.nq.gz
    ├── 41b3f34e585429c4231c9250159c5a6f3a89148d.nq.gz
    ├── 429e0581a7211f81f5c1d5aea0fbd12dbe661924.nq.gz
    ├── 43cbe640c2ec161cad11d9815bb1d7d2bdedc345.nq.gz
    ├── 44032a0273634b70af4992da55a03ea712e891d8.nq.gz
    ├── 442ea4bbdf96f57965a64ce37f7a4b3963687625.nq.gz
    ├── 45afad020859ca5b794652e804e0aa7e4f94e998.nq.gz
    ├── 45d116c55f7a1849efdf687b9590922798ee4803.nq.gz
    ├── 4990cfa9c5216043c3f7660a01d644d9461e3529.nq.gz
    ├── 49981bf50b27174abf77b7e61ce83971980f811f.nq.gz
    ├── 4b9173dd97031a0d32b939b90220a29a2f16b730.nq.gz
    ├── 4cf2f521117120d625f8bd8d00c8237b83f01024.nq.gz
    ├── 4d59da71d99cf9c082d672259bafce1b2dc210f9.nq.gz
    ├── 4d7c01ddc4fdc6c735353e26367d87e28f142873.nq.gz
    ├── 4eec49ab0cc74b77fc410d086c3c44b950f5eac3.nq.gz
    ├── 50243533f4543974c6a3c297292922eaa295175f.nq.gz
    ├── 50ff3a622bc6e4471deea9a476e5f972c8f93d78.nq.gz
    ├── 5107a8a6a08018f405592d63b40c141c931cca9a.nq.gz
    ├── 5174517498fd66e4981a293bf970970b09972d51.nq.gz
    ├── 51c53e6a1a8b31084cedb8479def65efe4ef4819.nq.gz
    ├── 5201fb883bbf3d8f89076fca4abcc63aff4e14e0.nq.gz
    ├── 53ef86ae217814167ffe4a58127f9191b1fe287e.nq.gz
    ├── 543fbab466b6c22395c302d21eadb5701a0b43f5.nq.gz
    ├── 546897b3f03764d679c8fd7c7f19c8c378087239.nq.gz
    ├── 54864f2a16102f5c2366dc46fd573e0c64e07f58.nq.gz
    ├── 56a7c03af0c9dbfcf18f2f36b3c35a1c79812aed.nq.gz
    ├── 57439dcab4eea7800366e01539dee2e97a23885f.nq.gz
    ├── 588ba921b22b651351ed884e3a1e36e52d0a00e3.nq.gz
    ├── 59899c392407b8c6ffad773bcacc2a1b5f91d32b.nq.gz
    ├── 598a5f9182c3719bcabf361d44352108c68b21e8.nq.gz
    ├── 5ab24d0d19547f955aee8737bdc0f2b14685228b.nq.gz
    ├── 5c3a2cd62f9ec2e6039e3e66d8c726f8493efb04.nq.gz
    ├── 5c77cef2d5ae417a7356a35acace59c0a48294aa.nq.gz
    ├── 5c7f2def9e3cd25fee4006d4f6a8bc6462402892.nq.gz
    ├── 5d057f9a22b93ab036a310254c1b90358fe7ab4e.nq.gz
    ├── 5d357214341a428a7aded538a974d15f136d20a4.nq.gz
    ├── 5dcef726f671e400c7a0873dc8e9d9f061889630.nq.gz
    ├── 5eb834da2977b4b01deec36e4fc62fa84dd99fa6.nq.gz
    ├── 5edf8c9b2e635f6f6baf20775921137b94efabb7.nq.gz
    ├── 5f062fa01fa296555c48262febc40dfd8b2c18d6.nq.gz
    ├── 60ab8ca814edeff8de55cc8d1749a8d82fd0f99e.nq.gz
    ├── 62b38247396f82e9c7d073b17c29cf505e768e0c.nq.gz
    ├── 6367a348ff9707b5d3c346a9870309508f6557ff.nq.gz
    ├── 643856288ce6b3e457f997b9cefe22010c5dc298.nq.gz
    ├── 6571c0d685666ff95150714187856b95df7898b3.nq.gz
    ├── 69f71a257e96e85536fa82b453eb2f9780750f9a.nq.gz
    ├── 6b15fd0e16de60c9c2e6f90f6a41aca5c7abbc8f.nq.gz
    ├── 6b2807573fbee3fc3d61afaeac331e18e26e76b6.nq.gz
    ├── 6c7d7e7d39484f342ced0d6db82d812256f23838.nq.gz
    ├── 6c9016b6065202ad5036b6b45faa50bf15a1740f.nq.gz
    ├── 6cfd374fa820c1837edab07a57cdf443b626e6c0.nq.gz
    ├── 6e1deebbec8a4e9fc5373c79ed504c4e5f7a7ac3.nq.gz
    ├── 6f5a9ad2382b7a07cc5aebbe2f179aa8df8e8372.nq.gz
    ├── 6f7ce04e264cdb4e3a659a26d239f73131258961.nq.gz
    ├── 6fb5e88c9cb70c80eae0cf56e57b2a8f39607ed8.nq.gz
    ├── 7032d90f09304d5a51da9bd34f5494d8fe777c0f.nq.gz
    ├── 70e6958602f23efbf2f5e728d3d457d2dee54a26.nq.gz
    ├── 72081b801d4aff81a10641c086ff054a8eb35e18.nq.gz
    ├── 7340be2f38277c104b76a15436c5697611da4613.nq.gz
    ├── 7380c4c86c4864533613c6f3172952d4f4a6ff88.nq.gz
    ├── 73dc444b92b195ce380faa2c0ff215e6d8b352b3.nq.gz
    ├── 74ad9428100d33037096145e824a2c83cf5bdbc9.nq.gz
    ├── 7615f1a987ace609c3264aa66a49f3c018413a69.nq.gz
    ├── 77517f21786e5d648f72d001d394a8c7555cbdc9.nq.gz
    ├── 7a7671d848998cab19e2592d606e3cb71ac1252d.nq.gz
    ├── 7ad99ce48094f537dca6bbd76b289ced63ad63e4.nq.gz
    ├── 7b01728537a730b626f74dfc2ee6bd4f43fa0a2f.nq.gz
    ├── 7b6d1bafa799e3d84d727a20778138b95826e770.nq.gz
    ├── 7cbd981d62423a72541dd747cf7d54ad2fffbe8e.nq.gz
    ├── 7cefaebe748afa572bafd7ed98b1b353d6bd7dc1.nq.gz
    ├── 7cf2cccf60570df48abf90e17cb47f0c9a754474.nq.gz
    ├── 7d44712a3891c9a759b0d5acbcd712b3aa4c8f0b.nq.gz
    ├── 7e48c989a2dda8dc1cf96660475a279eaa1c5ef1.nq.gz
    ├── 7e8c1fcf656427eca840feea4c13fb24afeb012b.nq.gz
    ├── 7f29a435d325d3f79a0371e70ff940139bb146e3.nq.gz
    ├── 7f531bd4d2cc07ddd5ae29b503cd60dd79fffcf7.nq.gz
    ├── 7fcfd0611c59487dcdfc623427d846ccd8d9bd34.nq.gz
    ├── 806f1a4cb2942884676d87cde73e26f58080d76a.nq.gz
    ├── 8143b55961f017ff36e34a2abd22aae5693d2381.nq.gz
    ├── 814b3983d34edbb75d13508c56df87148b18d09a.nq.gz
    ├── 815b045dca06f843f170f6ecc6dcc27384dd0c08.nq.gz
    ├── 822ddd869e6200ccd48a094b64daf9e1e74e5313.nq.gz
    ├── 83d8b9da64c3450259818359a88d082726629cf3.nq.gz
    ├── 846884ec530a01a004fa7d501a2b5a88a2c3bae3.nq.gz
    ├── 84c7c3e95864a1b9ff82671db226129952a95b01.nq.gz
    ├── 84c8cbd49c20dfc3397c0a512f1fa63ee52474c0.nq.gz
    ├── 84e5abc734c1e1799d2b0eedd552d54d7236b32e.nq.gz
    ├── 851f40bdd9f6f99df7b3acd3be4bd07267bfe3b6.nq.gz
    ├── 860aa1a3341294bf263babdb17bcc07aea035834.nq.gz
    ├── 861c8e097cd9c88f173a9b22107b9f702eadf55d.nq.gz
    ├── 87731361483b7bce080fdc3c9669d11aa6897823.nq.gz
    ├── 877e5c719da0eaa93644b8aa213e845e3caf634e.nq.gz
    ├── 89f31096a066fcaf064ffc7e8f433858bb60a82d.nq.gz
    ├── 8ac6cd109f72062db885b7aba3916dab6b0cad12.nq.gz
    ├── 8b4ea562abfc33f31f9515e9d7d88890cf25e80e.nq.gz
    ├── 8b8b5609520f0efeb8e61bc379ea0a499cd226d7.nq.gz
    ├── 8c32a8106ee00dd30259df32ae140dbfd33f411e.nq.gz
    ├── 8c3738e14cb35237c99bd3f524bb253634c93de4.nq.gz
    ├── 8ce59a3060c314eeba7099a811fd023f5b3027f7.nq.gz
    ├── 8e116c0f468d03f82e33d570bd52f511cdc62161.nq.gz
    ├── 8fa5ea0316379432d26315c459c7513413d7b1e8.nq.gz
    └── 900fa35fd8c1208c4dff7f7e09480bdb737c3a5f.nq.gz

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

[UKPLab/FEGA](https://github.com/UKPLab/FEGA)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
