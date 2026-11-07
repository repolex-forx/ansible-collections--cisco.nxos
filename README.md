# Repolex Knowledge Graph of ansible-collections/cisco.nxos

RDF knowledge graph data for [ansible-collections/cisco.nxos](https://github.com/ansible-collections/cisco.nxos), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/cisco.nxos
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6395a319705fa1ef40da2239f9cab050efb6734d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6395a319705fa1ef40da2239f9cab050efb6734d
│           └── chunk-001.nq.gz
└── blob
    ├── 00f9370e3374650a1bd2a86ab7ea82b2cf4b8e0d.nq.gz
    ├── 0258db28be0c023c63290e61e5f484e893f57ef8.nq.gz
    ├── 03049905289307968892eecbcb98725169914aed.nq.gz
    ├── 031feb056932653a207b0c1153a16f39226fa872.nq.gz
    ├── 044ba3969d378bf1a0223f74d15393abef2fadf0.nq.gz
    ├── 05cd385f0876080b25a69611251049cafafb688a.nq.gz
    ├── 0618e25803e3a6257fb817c0b911c1822e9b8a35.nq.gz
    ├── 06bd437e89eb806df13bacbd40afdea2e3005eb3.nq.gz
    ├── 0816b2b13f9895e1334593e750ff549b38f2cef5.nq.gz
    ├── 081e71cf0644a4fdcc1a631d6538e2d72a446803.nq.gz
    ├── 0859bd78b13c208961b6d077ac4eb908eca515e8.nq.gz
    ├── 0863ffcef3b917cae8e0fba3aad1f26d8fa6a032.nq.gz
    ├── 08ba1ad3a7a3410ad5cd3f60a580628dc702bda8.nq.gz
    ├── 096615b11694baf5b8dcf22cef65e2077a3e0e2a.nq.gz
    ├── 0967ef424bce6791893e9a57bb952f80fd536e93.nq.gz
    ├── 098c2a4718f670c629a29365ff97abf9a3717e2a.nq.gz
    ├── 09a406e3a9bfb5f27b27fab5251745967214bed8.nq.gz
    ├── 0b48c6d8c07c2d6e9306891f2126d7ac2819f447.nq.gz
    ├── 0c3f102ff55cbc654cd6f6e39fdfee9f0bd2832f.nq.gz
    ├── 0c5102d5435ab114df35889c7381101a314de59d.nq.gz
    ├── 0ced59fd8d578f7d90c3ef6e0ea1bbe690025a06.nq.gz
    ├── 0def97b81071e00819a4da6a59c6e53391fb989f.nq.gz
    ├── 0e26ff50f42a98b3ade062934340b584aa317d6c.nq.gz
    ├── 0ec25f7505c14bad77f34453b2730417ab431293.nq.gz
    ├── 0fad903031d070cc0b6a928b07582930fd646160.nq.gz
    ├── 0fc5ff730e8ea85c56e2fab4eea6024d089321bb.nq.gz
    ├── 0fe23c56a98c8f0780bee528ded9ed63745217d9.nq.gz
    ├── 1049b9bd1a6494a75a99bb01b09eac31e028bece.nq.gz
    ├── 10be7ff1929e5926d42ebc439d0cd396ec83aade.nq.gz
    ├── 114792d0a0b1e50a73ef0e33855dabbf86dc2c7e.nq.gz
    ├── 1169667d21418b83d8313362b453e0d7d133e83e.nq.gz
    ├── 1356a83c18ab91fd3547f2cc6cd4bfd15b5616d8.nq.gz
    ├── 1368ab240b6527adabbf4cebc657406274194e4a.nq.gz
    ├── 13df8d1e28139bf027089970d626641a45f7857d.nq.gz
    ├── 13eaed64cfda8199a0bc9524e111bf39d5558062.nq.gz
    ├── 144efbb59b3a1d8d0aacef411b96b91a1e6df83a.nq.gz
    ├── 14fdcf0d53229f78e3cfa4ad5aef3e5acb8b3246.nq.gz
    ├── 152b2501f0b6d62cdfabd0baf4925212e8bd181b.nq.gz
    ├── 1590860040ef7829fe9f08f99aa96912f033d41c.nq.gz
    ├── 15c6748b59c97fe8a5b6c549122586fc7cfeeb81.nq.gz
    ├── 1744c224c0754750e438909b2b4cdd7e0bcbc03c.nq.gz
    ├── 17c6b5bc4739ef52ff92b3fb538c85b8758ae893.nq.gz
    ├── 17e3845ef98b551e9989392624c2212bd52a5c10.nq.gz
    ├── 1982b15ffa79482faf79eb309976015db70edc8a.nq.gz
    ├── 1a39547de9488c52866511fb29a8b274e2e73201.nq.gz
    ├── 1cdf9a2f2109f2f533d6b99e08f195da491cd1ed.nq.gz
    ├── 1d127b707f0a04f1ac344a666642ff6b7ad63e16.nq.gz
    ├── 1ea69367cd566dc7beee5ec60d1cf989224a5e4d.nq.gz
    ├── 1f8b1042043dcc7cbe295c282ef20e385267d090.nq.gz
    ├── 1fb80497febac885d9f25f17255971d9078ba243.nq.gz
    ├── 210bd45db8fc48fada02a2dd9a32a652c077f20b.nq.gz
    ├── 2206eca096d568abda8878546575f3263c493b5c.nq.gz
    ├── 22a4fc9f498884634833215c3d6e786afa2890d9.nq.gz
    ├── 22a6666e5864e7d5a122e3ab6792f658b6fdd5fb.nq.gz
    ├── 22a95f77e0df7f73fbe9bf7bc07c1ce779e69f7c.nq.gz
    ├── 2321fcaf1a23f8162c224868b2ddeeec326d9d0e.nq.gz
    ├── 2359bd0debe7fb37bdd5699cc9e4dc25e4740cff.nq.gz
    ├── 23d65c7ef4514be9029e7c1d73b885867d81c383.nq.gz
    ├── 23fab8f352f73cacd79933290cadb16c00feb5e9.nq.gz
    ├── 2409dd90c2c205ffecb866ffd436c32257534c03.nq.gz
    ├── 24e62ff5188c893758b914dd96cecdb1a426e6f8.nq.gz
    ├── 2532ecf999adeee2b698d6c7a92f04b80464d4fe.nq.gz
    ├── 258357ff7add5cb741f98d41278c264c6adb156f.nq.gz
    ├── 258b68aafde0584e42b5ff65f07b9850c7194635.nq.gz
    ├── 269ed1ccf3c7396e7a86f635eca7efd0aae31b2f.nq.gz
    ├── 27209249d50c6e4470139a77b04c35b1e46e0de6.nq.gz
    ├── 27d9e959914a30873af3010622792c6b8968101d.nq.gz
    ├── 28a8751bb8adf2447bf8481d8b1d721fdc8fec6c.nq.gz
    ├── 2946231db28dbd8f7c8729ce4287f7b80e7f2ce9.nq.gz
    ├── 29b42cdad4ffbb3c846a4cd89d7993795c4d3d4a.nq.gz
    ├── 29df4d48ff95198c9aa35f45207a0e3aeb4ceaf8.nq.gz
    ├── 2a5ffad54176b73617d30d0f77b052e60d327319.nq.gz
    ├── 2ae8f41b1b09662c4990e51fb8437120919e2982.nq.gz
    ├── 2b86b35471513bfbca5b32407a3a566d4cd39ef5.nq.gz
    ├── 2baf6bfdd4e4af3c5b114ed8e102cfd85b69183f.nq.gz
    ├── 2bbd1eb5d7267ce9027e3b772a56548d84729a28.nq.gz
    ├── 2c237d360ca30f3685e5afb846b761b7c5721e47.nq.gz
    ├── 2c2e860cb901a372c337e1aee7a4300dfdf66609.nq.gz
    ├── 2c72aef4ce80f9e5f61d14df1960e259cf31799f.nq.gz
    ├── 2cbd866fcc0171cc9a8da7949af19f5b29fee78f.nq.gz
    ├── 2d416b39588e0e73241af4a1e06b385d0e65001a.nq.gz
    ├── 2ddce69affacac453aa55917ed4c90c2c98953c3.nq.gz
    ├── 2fb981c2dc5fe4b5325c280b747454609afc5caa.nq.gz
    ├── 304e266911869d8a3421b4310a21756b1023b897.nq.gz
    ├── 30da2d2bf0b946244848fa52eabf8f094ddefb66.nq.gz
    ├── 315eeed0fd1c0ecc7c8e3e49ed1a5095676cc5e5.nq.gz
    ├── 3166ba6d453824a72132874337438d5134fb3747.nq.gz
    ├── 319398d5fec96c894cf36bd97a3979c8b7ddc61b.nq.gz
    ├── 321c2a9fbb100783afd2e531668d4d52fe7d31d1.nq.gz
    ├── 32ae5fc4c9574d50dd2440b4ac705e658cf294c6.nq.gz
    ├── 32be1adedacaf27850b32eb8b4c9c8245397a837.nq.gz
    ├── 32f2e040fcb906436d354ef88d910b7e9fae2e85.nq.gz
    ├── 32f80636f23f820b5329c0c102919843e5a8da66.nq.gz
    ├── 3421318474c111d9250ef65708496a0517285136.nq.gz
    ├── 34996cf3f53c5275468381d2f8887e436d68dab0.nq.gz
    ├── 34efcfc8ba1b12a8b51effbc9df9923253a191dc.nq.gz
    ├── 35078a7f950a96a03a714eb146738923206e9c20.nq.gz
    ├── 35d525e279974a969d02f089a095b954c61d2c46.nq.gz
    ├── 36db4cbbaf8e388c62fffc66ff178fbc8068df59.nq.gz
    ├── 3768a1cd897956005765cba7d9e260f1ad1b362a.nq.gz
    ├── 37e2c6adb934f7a45b2d4f5c7369fb704e302e31.nq.gz
    ├── 37f24b208731578cdb98859756e6e8910e72dcc0.nq.gz
    ├── 381eef8a61203cf3b26d97b7534250827e616814.nq.gz
    ├── 397acb1f47c329e823a97ec7eeea67b6833c2db4.nq.gz
    ├── 39cca32a40078580c843fd2aae99202c864b3452.nq.gz
    ├── 3a5af124094e46534af8d92c1163a92fce830a7a.nq.gz
    ├── 3ad2f4692001b9c0d75490bd55808e1a7aae0acb.nq.gz
    ├── 3ba28ea14373f1668ee784e134ded3eaf58239cc.nq.gz
    ├── 3c314022a4b590cbb9d5e4ae4b06ba8917b885e3.nq.gz
    ├── 3d8f7e6d15a95b80c366063b5f0bfe89bc36820f.nq.gz
    ├── 3db199ae4c4007f4802a259e52a7e0b0be7b9a62.nq.gz
    ├── 3e4f197876fd0f1c22f4d3dd4ff487076ee4097d.nq.gz
    ├── 3f56f8adbbc1cbe2a7f8d8fad5467eb7b7327c66.nq.gz
    ├── 3f6eb5b49f610877aad334accf88b5368191b90a.nq.gz
    ├── 4031d47a08c9b21b12968ca95748ff0e34dee141.nq.gz
    ├── 41002d699c9ed4d7ca05f43aa05510acb42ec02c.nq.gz
    ├── 419d2a85518d8b160cecb53eb2cddc10c31ac634.nq.gz
    ├── 42a64ce430f7b3a183caab6f399dfa9cb2935893.nq.gz
    ├── 4308a6582b031e4b059baf093a310a34605277f1.nq.gz
    ├── 439828e430d34db8336440820050946639f07cd8.nq.gz
    ├── 440638a8133afcbbfcbe4e281e48d2f0943c3f06.nq.gz
    ├── 440c400eb2d977f683a977a321e46a0502b70e72.nq.gz
    ├── 4423df580922e8289107b9299a439b4a9b81baae.nq.gz
    ├── 44f4fae7f15e7478654760440a35231c515b7eb1.nq.gz
    ├── 4655bcffdfede5fd9e9db59cec3f347f080a7e04.nq.gz
    ├── 477c761ab6e134c8085fa21a0c9d3e12fa06f7d5.nq.gz
    ├── 48322a822c64b43b96e45cfe5b374f7514e8ddaf.nq.gz
    ├── 485e94cbb08f0c3f9b03960f173664e6ad4de6d4.nq.gz
    ├── 489b6fa30b132137ca10830e947ff6168f05ff52.nq.gz
    ├── 491b3857e2e5ed0d4a85e8790bd299a47199e834.nq.gz
    ├── 4b8567a44fc38b388c56b33cd357ae7d06707450.nq.gz
    ├── 4b997c8be6bac1026d5d82abab10cd2e6a2ca348.nq.gz
    ├── 4ba12553edb5c45d9897e4614154fa1617769cef.nq.gz
    ├── 4bd4af4fc73a26ba41ebe2022e7a7cd3b4e1b7cf.nq.gz
    ├── 4cea7973502223c5eb24b2083aab3774a997914c.nq.gz
    ├── 4d2e8b5b4a593379bfbd701d464d2b06e9114bd4.nq.gz
    ├── 4deb6c33fc5bf41e7c0f12c97eddce31bcdd96d8.nq.gz
    ├── 4e0d62acbaf83f2c0963bccdb28e41f01f1a0a25.nq.gz
    ├── 4e714754100ff02a174deb697f420f5edda4ce10.nq.gz
    ├── 4e8c5fbcdb92c5a13be857b48ac7a1e88efb8ade.nq.gz
    ├── 4ef02263bf7a25c3950f019292492725e91e1343.nq.gz
    ├── 4f2cc676794d8bb2920d1eaec0f64a4503651f1b.nq.gz
    ├── 4f34570f9847acf836a58d0846056cc0a5b5329b.nq.gz
    ├── 4f65ee5f2fb21fbc231f21206e73e2da64f9172a.nq.gz
    ├── 4fab694c8a1b915be6fc75fc2a297500a95cfede.nq.gz
    ├── 50f6b5a74b00801a27bb98b1f991afa6102c20e4.nq.gz
    ├── 51b1413da64e30de6b61dbc2e4538bca523cadc2.nq.gz
    ├── 51b255f9d8cd931de7068cd394bdfd68cb828c53.nq.gz
    ├── 52a8aad854cf6434060617836bb5c64f939cb6c0.nq.gz
    ├── 52d385973eb3d8ce026cee17484f7c060ac630ca.nq.gz
    ├── 530266d4cadb073aa571fb86a35a035988ed8cdd.nq.gz
    ├── 532e4e058a8196ac7bbc9aa56f893a2baeb993fc.nq.gz
    ├── 53e949b821528ad61229107380b69307d5f11177.nq.gz
    ├── 54eea69abb94842c749219b00b9341d98d78510b.nq.gz
    ├── 55805194eda7254659cf36e0730b648785f4d31a.nq.gz
    ├── 56b658afc0e6a6ddbf85cbca9d0d6dd8c8b1b904.nq.gz
    ├── 56b7a04eb5a1986c8b67a2037b30b4bece85d509.nq.gz
    ├── 581197d7f1030c543aede81ed26eb391f80dc639.nq.gz
    ├── 5812ce24ca4c220b263d4d94490ce409f7a80192.nq.gz
    ├── 589aa81609048aefe1859a1aae1f472a99e17292.nq.gz
    ├── 59450bd4d81473c8f126ff885f49f911632666a4.nq.gz
    ├── 5a8394d51097638652ef77b01f7dec5af617fe8f.nq.gz
    ├── 5b062d952df6a8ea45e8e5d7a2e44dc2ba4a254d.nq.gz
    ├── 5b9ff2f70a8129a001e5d770b200643c9469c271.nq.gz
    ├── 5d43583cb454b384e85a4131b3928e7764acfe34.nq.gz
    ├── 5d9d82223f00f7175b38b04042ae8bbf1cde3948.nq.gz
    ├── 5f13e370bc43d4baa6ecda05f1037ce7fcac601b.nq.gz
    ├── 5f709c5aac15f11a4cb08bbb627883011ff762b7.nq.gz
    ├── 60977a688b037728116024e0bd491dce2c8068be.nq.gz
    ├── 60c284d78fd80a6e1766814ad6de8c77e90f1e80.nq.gz
    ├── 60fd511d4364467d16f0bc12380afb3cec253b27.nq.gz
    ├── 6138b8c72d64356e8e08580ee81d10f7393dfa95.nq.gz
    ├── 618f8a379d432ac8bbe2b45014f2e3468f52c0de.nq.gz
    ├── 61d8a02dfc40ab3249d97df2f1b815a84cf776d8.nq.gz
    ├── 62298058d1f28a1f35e9378e4544fc770b984703.nq.gz
    ├── 62507228b4ea855ff61a1791cca755db20e25315.nq.gz
    ├── 625ed5082dd509e0ed5f2162cd2824fd021c908c.nq.gz
    ├── 628bf5cdf22070c0b4f2692cee269ba52c34355f.nq.gz
    ├── 62db246838934a47299e3444c10100ac5189fc05.nq.gz
    ├── 633e5a08c4705dd3631054a5a82fa99aa3437467.nq.gz
    ├── 637a0bce955105dc411903abe9fd1367b0e1d21c.nq.gz
    ├── 654fc71e691391c0793f39fca1b4cb22b257631c.nq.gz
    ├── 66aa89b87a08f6acb4a14582b2a2cb626fb6134b.nq.gz
    ├── 6758c8296997bc018cb30a32b7ea90a96692f535.nq.gz
    ├── 68ba10376c0371e60dde9e71be2ee12ee10a71e3.nq.gz
    ├── 697c2c18bfe4a496a0db3a5aafc2520b9fb2ea1f.nq.gz
    ├── 6a2ba9d7a2ea84e8ee592d39cc03614ce7d3aeb6.nq.gz
    ├── 6bd9fbe309a03ac1ea93b74ae77ec5b1bfdf12ee.nq.gz
    ├── 6c055dd5589263c52ae613830bc5219d4deb6a69.nq.gz
    ├── 6c47d2e573ade4475a3426ffafd2f656ea1db8e2.nq.gz
    ├── 6d316040db0eae5e9681bc2a6876b5657c4f8a60.nq.gz
    ├── 6d476da77e0ee1ca4385928b508f782cd84d9035.nq.gz
    ├── 6db72f951072bc13af321028198b94bdbf90f6e7.nq.gz
    ├── 6e4a8c21ca8ec2fb2ab04030ed553be585ca97a7.nq.gz
    ├── 6e84ddf169c7e73f0e13beea842c2628de1ca7d0.nq.gz
    ├── 6ea35db3dc664497e5165f8d897b9b0621f3faf9.nq.gz
    ├── 6eddf5893ecb039420c7c2559f046b89067682ab.nq.gz
    └── 6f4560e58ccf72f7ef9e5ed421d299e497bfeb2a.nq.gz

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

[ansible-collections/cisco.nxos](https://github.com/ansible-collections/cisco.nxos)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
