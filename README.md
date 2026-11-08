# Repolex Knowledge Graph of vllm-project/vllm-omni

RDF knowledge graph data for [vllm-project/vllm-omni](https://github.com/vllm-project/vllm-omni), parsed by [repolex](https://repolex.ai).

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
rlex download vllm-project/vllm-omni
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 62876f40ac77f14dccc4ab9d332e9d5110875ab9
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   └── repolex
│       └── 62876f40ac77f14dccc4ab9d332e9d5110875ab9
│           └── chunk-001.nq.gz
└── blob
    ├── 010f91cae5dd686576fe17d5a1116f8cb898200f.nq.gz
    ├── 028c73c86cd85ec62ca3af5d22db937fcf0158ce.nq.gz
    ├── 02908e6a2121d00acbf8a71aaef688ad60434027.nq.gz
    ├── 02937c058813ffa52f399f76d3fb4520af9bb146.nq.gz
    ├── 03f17c974f6012f99ac84d63b2a6feba0a850ece.nq.gz
    ├── 045dfd31f4a166b85a334eeb43e8845852fa3c28.nq.gz
    ├── 055a87f56780235d033e707ffbcd3389c7b2554c.nq.gz
    ├── 064d07b01aff5b2fb5e917c41edc0ee96b5cad9c.nq.gz
    ├── 0779317db2f074b49287d7c3dbe5dc058f57eeea.nq.gz
    ├── 07f1eb67e31cee0fe34c83c8cff7de77f4a533ff.nq.gz
    ├── 08b6fdf31cd3fd73f5f9a39b86f1881dca49ea76.nq.gz
    ├── 09b27ca022801906567eb1df9b86b95ab04c26ae.nq.gz
    ├── 0a7d6070b1467996bbf0867855293f4c051985dc.nq.gz
    ├── 0bacd69d200c75a19005bd5546f29faa6e159952.nq.gz
    ├── 0bf324a80ed280bc524fe5629050e5e6bb7394c1.nq.gz
    ├── 0bfe28af242fc4e88be90da09b9885474ed86297.nq.gz
    ├── 0c9771b1856de83dae498cb9018cd3f0355381ed.nq.gz
    ├── 0d560b50e36f05b850eccc1a43792a576e6bf084.nq.gz
    ├── 0d5d05976080281945ac65ad897c15fd8fcf3c2d.nq.gz
    ├── 0e15f5b6457d4c24361df7bc3aadf53e79040714.nq.gz
    ├── 0ef5dc0364f4c8b0de22e370aefd7c83307706a7.nq.gz
    ├── 0f0bf59c73e43b6df7ac5721a422ce305ae75fcf.nq.gz
    ├── 0f8cf2371b94c7e078903bd5d8a104e90ddc7de8.nq.gz
    ├── 10253b77ff92a5e39085d60d2429ccd3636eba82.nq.gz
    ├── 105251c9300f4abf4068e63a417c49f38ffe514c.nq.gz
    ├── 10db75d05673e7438a1041610d6ae04c13285499.nq.gz
    ├── 10e95d643d609afa984aa9da9059ca486e07804e.nq.gz
    ├── 116f44ef94bba9ed21b81121ab723cb5c0bbf886.nq.gz
    ├── 120acce4ce3ef6ae4ff3acf6ed12b1c793525d5a.nq.gz
    ├── 13952ddf728c465195b546759015ee08836fc0b1.nq.gz
    ├── 140234e7a524917b78658f85f679f2bdeefe1117.nq.gz
    ├── 141ccf50e881cf2e0cb02a635d9b72de91e7daf0.nq.gz
    ├── 14501ed063c0f8bc426d86c6d97c0a4042605073.nq.gz
    ├── 150fc3ebc51970a1bd04b069fcae6c426ba47f03.nq.gz
    ├── 15112d5862ae56719f3b2a56852a4c9cb9dc0160.nq.gz
    ├── 16d9f79da69851330a845ddf4e98710b559c010d.nq.gz
    ├── 175af9dc306aada1694514d3b7de4684682b2b80.nq.gz
    ├── 17b020517f7e81fc0a3367e9731c8f581bb2573b.nq.gz
    ├── 1877bd9c7c9f235d9bfc6adf1c9e8af27b5a4424.nq.gz
    ├── 18ba3dca03cd047e76ccde35b10304fcebd62913.nq.gz
    ├── 18e9a7d7a1e84c3fa42fbe31d0083f1a482dab1c.nq.gz
    ├── 1991a1c15f55a2abe22a8328d8103ac0bd2490b1.nq.gz
    ├── 19b063874007cae884f2512a57a86a91810a80cb.nq.gz
    ├── 1aa2d57d2d8875ff2da91b2c60f174a4cd417fdd.nq.gz
    ├── 1af9c0b6360d3067f5c4a98075b1ee376ee56d0e.nq.gz
    ├── 1b4e65aeae5baaa59c6e993f6a968f5120825e8c.nq.gz
    ├── 1b6e8eee3f1606737f60147bf3f4d76fb02d6c20.nq.gz
    ├── 1c30c6d7cf33fc656ff846751aa341bffd08c5f5.nq.gz
    ├── 1cd3a8b4ec45e922c11f18f20e1139ecfdac8ca8.nq.gz
    ├── 1d8c0b2f13ac6bd2b4da84140ceb464d793a7cbb.nq.gz
    ├── 1d91cabfa3fbcdc919e6c2063edd29974cbfd7a3.nq.gz
    ├── 1eefd122bf1c1e68328d7d8f8d471015a04d0503.nq.gz
    ├── 1f20a5b72aa3c5d319ff4ddaf1e0b114a6bdf9a9.nq.gz
    ├── 1f470069b2f249c90a1a40ae22662436c33e2123.nq.gz
    ├── 1fac0b9f3e668c23eca19e1bd23f01e472f2dadb.nq.gz
    ├── 208f01a7cb5ee04c88d276fec2082cd4e830884b.nq.gz
    ├── 2126e43634685b1b229380089944c4f2384e1128.nq.gz
    ├── 21c0c730087772374aa015581475bad189740bb8.nq.gz
    ├── 227822f94191e3e5babd01439aaa9a4da51ac87e.nq.gz
    ├── 227f3e97aec9a24e1635085b5e17d6e9f155d7a8.nq.gz
    ├── 229377431b0043a28e5a2dda85d4c7a6427e4984.nq.gz
    ├── 22c75cd158baf0be304d85b2da18e4028509313d.nq.gz
    ├── 2396b800b0b13fe3f79d0b18c257df0686effcd7.nq.gz
    ├── 23baa2c3e81b951daf1736f36320c0fb95b1ac69.nq.gz
    ├── 23bbb55acd88668c1da392d02108c307e118e456.nq.gz
    ├── 2495b82c88de0eac2c96d48f6fbf8b6f5a10b9eb.nq.gz
    ├── 24e1fc2e23b02dcd814ff8b7520b01060d51b161.nq.gz
    ├── 25a8b01833f1e8a93caee9e847b62a99cb555b18.nq.gz
    ├── 25c890cfb258f4328b1cdef039caac21155d0645.nq.gz
    ├── 268139fa2d1e576ff3f9d26d6d9ba7541ed07d73.nq.gz
    ├── 26af9a25973a0b82e6cf4dcb6d95295bcd2c8c26.nq.gz
    ├── 2723bd43a7c4cb02d9e9d11f72e44ad9a78920f7.nq.gz
    ├── 279feb4457863e3d8863039dac315699045899ec.nq.gz
    ├── 2821c4de04aea901ad292209bd6fb279f822e30c.nq.gz
    ├── 2852ccdab445862c98255e12bdbde3f86fe8f792.nq.gz
    ├── 28a8641cc747865732818bae427aebee8e5d5f4b.nq.gz
    ├── 29dec03d338fe1aa70cf9ebe2a92e737318c21a1.nq.gz
    ├── 2b69d9ea73096253cc3c314ab5eb9c0827012192.nq.gz
    ├── 2b9bf38d06ef4b3b7bdf6e7cf63d93bb70f2fef8.nq.gz
    ├── 2cf7ba8f4f51e3f61786f0a24b588e4823d70c3f.nq.gz
    ├── 2d46e8edb69c02bdf23159f85c4240793a761a1e.nq.gz
    ├── 2ec818aec6677800c8f914d31cf060c7ac0c37c1.nq.gz
    ├── 2f2be20915a85b61bc192a0c80fc267bb41ec7f5.nq.gz
    ├── 302f06dad0e7bc12092811847a8791fea0a93e90.nq.gz
    ├── 30c9baac19403c430adeb1f97867c0b0e32528d8.nq.gz
    ├── 30fd6d4303a9005f28bad8322f610e0781c40dff.nq.gz
    ├── 31de190529aea0b608b5389ac08e05abe2b8ca56.nq.gz
    ├── 326ea93098bd8541f028b57644378547b83c8e6e.nq.gz
    ├── 328b6d6b49703c76348a04ab73f27ed70ae4e422.nq.gz
    ├── 32de4310a9be82a96c5f6d33aa40a70cda3d23c5.nq.gz
    ├── 3303cd6ec7062648dabf248758c5a796bee2e2d1.nq.gz
    ├── 3402bd18695f1f508b845d1539c0e9c4b19324a3.nq.gz
    ├── 3412faa47249d059d8be2efcfb189c591cc43b3f.nq.gz
    ├── 349aae42925e7b0350c3be57c16458c1ff1dc1e3.nq.gz
    ├── 34ad65fbdf70992fc24e1a49ba52a82beb5eab94.nq.gz
    ├── 35ceef9f7ef3a157bae8af369cbf49aab755040c.nq.gz
    ├── 35d218903bf8d7fe86373c305bd624822a8328f5.nq.gz
    ├── 35dd2dab9173c113ea35bb70c579bc66d8dbf9f0.nq.gz
    ├── 3666d63e3c953b4885f21709a11bbadd9f1d8506.nq.gz
    ├── 368ec2d9fb01fe01a1069bc3b6455ba0653e4e29.nq.gz
    ├── 3766e9c4e457054f423212921bfc6642212c8092.nq.gz
    ├── 37b773916862ee121b29942b08f710b23a25ad47.nq.gz
    ├── 37e7434736b7be7a3b9c9a84cc20c48616f89f64.nq.gz
    ├── 39c6d05f4449766bb047066693dca898ff73ba92.nq.gz
    ├── 3b530d298c1bf920bfedbc811c5e594b45f4a92d.nq.gz
    ├── 3b7d23302cca2ae68eb543818e1d22af370fe6b5.nq.gz
    ├── 3ba00364dcd4c5685cc2f26ce6f6dc80865c5864.nq.gz
    ├── 3c20278dded7a6a0338f27903b0d4a69c164c01c.nq.gz
    ├── 3c500e393d7dd7e1423376c57f515b37e987aeaf.nq.gz
    ├── 3c8e3c021552f1ee71e4d8745e48853194ee220d.nq.gz
    ├── 3d8718e7056e3861d04099360712f3b46e312e10.nq.gz
    ├── 3dbdb1db0e9f3a1227e35e434eb95e4e7e457154.nq.gz
    ├── 3dc3c778f67397875c41aef67615a1da90237b48.nq.gz
    ├── 3dda0d44b08e544d91efa84bb1e5a9dad4d7a451.nq.gz
    ├── 3df1ebdc69779df3c0756efdb520b34d3dd50b53.nq.gz
    ├── 3f4ba216441bd5f9c70e39638ef353e43cb1846f.nq.gz
    ├── 3f7d1fb7bf5d3ee56cfb8cff1258837c2176b68c.nq.gz
    ├── 41361af6602abcbc729b842a5b065c0c815f4025.nq.gz
    ├── 41939776d471f16ef117af2e8cad0642f572e286.nq.gz
    ├── 41b399af0377014c6a9ccccc4220d0629f4288aa.nq.gz
    ├── 41ee8305d862f1d174e59ed8e4eef1074253d4d7.nq.gz
    ├── 4244ce4b4e1936202149b7825f71fc8d4fd92a9b.nq.gz
    ├── 425c147a2d9b1b679b57da5282a5f75e0057e82e.nq.gz
    ├── 42d3290cdf97b13138b4c4781c6559ffdb9d728b.nq.gz
    ├── 42f103f42211ab35f2e415fbbb115e69b1d83292.nq.gz
    ├── 443a024047e2af90b98afe6a118c4ed73c4f9d24.nq.gz
    ├── 447fcba3442ee05dc01c08bc0e9262b754930141.nq.gz
    ├── 44b5a67eb52fd48919203bf5b6d448e8b46ff36e.nq.gz
    ├── 44f7f75c77025e8bce2f05eb5141dff62efbbadf.nq.gz
    ├── 4519a72426ef410ab8888bf196ae19bfd503ce17.nq.gz
    ├── 451af0bfd17714669cf18bdcd27082efd225152c.nq.gz
    ├── 46a4f560fb37980b839cc00b1e840b146d7f36f2.nq.gz
    ├── 46d48b513557efb21d85440d812cf93e0fe039b2.nq.gz
    ├── 47af53a560e329a3d2c2275bc52a4f4a6bc2a6bd.nq.gz
    ├── 481678c8400d80a7db5571476f8d7b1bff54ffcc.nq.gz
    ├── 4832bcc9bafb14f711a329bf131fc99ecbf2a18e.nq.gz
    ├── 488ee990ef289b03869f7c17f8ec4369e8d8ceea.nq.gz
    ├── 490711d3453ccfbe94f8ac18bd6da9e165c5cb61.nq.gz
    ├── 4945242192a409e2c98b9ddc257b65a8be9a702b.nq.gz
    ├── 4a41a9d5c2ec3f7006eee6559617153f30df6de9.nq.gz
    ├── 4aca4e9ba38ca896e6a6882f45bdf7ebda1282ee.nq.gz
    ├── 4b7ead7edcc96ea8e40dd4b7b975f9dd700aef4a.nq.gz
    ├── 4c80dfded5039a40cbb2a0c1a376b2ee94820ed2.nq.gz
    ├── 4de460638e9194dcce6a43c2112a315d8e5651c1.nq.gz
    ├── 4e7b1dc958e0077c413a54ed62e7955c0b17b909.nq.gz
    ├── 4e93139c209c61a061e663dab4d5a7c0b0a18891.nq.gz
    ├── 4f05ccadfd5dd08a7cf7f0d449a4c13e6436147b.nq.gz
    ├── 4f88f973af4d457609b498be6619f4dd7f31fe4f.nq.gz
    ├── 50307f123d7d6a20ba5d9f6c44526c06733687fa.nq.gz
    ├── 5034f9642682af32614760196bb3c4fc0b1f36a3.nq.gz
    ├── 50b7fe9a0e062f0c67ebe3e2d0bca2810e195fc1.nq.gz
    ├── 50fbb2d20b89557271a6b53504e22d73b896c00d.nq.gz
    ├── 51e672a30558c84bf59bf71c3aa4ca84bf72bd93.nq.gz
    ├── 52889bfbd69851e57ca158045d147559908b9cbd.nq.gz
    ├── 53a90452e637b8958bcc48d3eb605a7422f5e80a.nq.gz
    ├── 53b4d783636a79a37ad8516b20fce66a002546b9.nq.gz
    ├── 53c15524ce6a878d9eecbcd5156dcf9bd24a13ea.nq.gz
    ├── 53c3ae8f2899215608c4df0cf6e2055bcc12379f.nq.gz
    ├── 54f78cb0588007c6757f3a0d922ff56fc7012168.nq.gz
    ├── 54fbe770d0d1fb19059b79696e4c9e8981ddb7bc.nq.gz
    ├── 56fdb328fe09b8f04d034ce199b0ebb596803936.nq.gz
    ├── 57417c8860fb19c6f1dd1155e81ae153e49ad952.nq.gz
    ├── 57b3d041a91562a20996f77c305d95cafd82081c.nq.gz
    ├── 5a1792f5139be90e6c1f73a8f357bdecd0d1c5f4.nq.gz
    ├── 5a4ce2b03a7dcefe3c3e917bd68ab865493ef966.nq.gz
    ├── 5a504adfc37d3f898a571c5df56ff846a771b2ca.nq.gz
    ├── 5aa53341bfe96f86104bf220514dd2541d3f53a6.nq.gz
    ├── 5b28001b738d8b09c83e6bed9baa1b06c6bb64f1.nq.gz
    ├── 5b5eea819a7cd28b67ff525ad42e4fce42b59d41.nq.gz
    ├── 5c681b0c92d94086e99639ccda417ea8c16b2dd0.nq.gz
    ├── 5c833320dffad6a99ad1df390a4e5f2708b0fe46.nq.gz
    ├── 5caa2c22155798165f5e7e969987461149e1aee3.nq.gz
    ├── 5dca3156c5176cae09e170434cb55f23acec89e5.nq.gz
    ├── 5dcffca1cbc7e48cdbe885f851e2cd2c6b676dc8.nq.gz
    ├── 5ddbac09c17d9644e2475e0c986c09dfd5bf01f9.nq.gz
    ├── 5e48506434218f62579ab368ff30716c608161f6.nq.gz
    ├── 5ec597fb58b559d793187c11d6adf2ebcfed2ad0.nq.gz
    ├── 5f023fe3fb6971df5199073497da4174af74462d.nq.gz
    ├── 5f0ecb452e11475481efe8c86544496b91f8f8d1.nq.gz
    ├── 5f65b450e34a1cbfcad1d5532a246608baa7e387.nq.gz
    ├── 5faa42eaf9ada19558dbd883d7407c9755ce9137.nq.gz
    ├── 6080fe7c8bf5526d0c66fd70644015fc9287ab23.nq.gz
    ├── 608ac6b01fc2a64746be51c6bb0aad54ede41c60.nq.gz
    ├── 60fc725d6e847309127660e74536439c06560ee2.nq.gz
    ├── 618bec36bf574995e7ee218843f17b49b00fb7b2.nq.gz
    ├── 621e59e430a12a06e30fa193da41545e66b06e31.nq.gz
    ├── 6262b984f01ff8938c1d8fdc5d6cf8f2117d14d9.nq.gz
    ├── 6264ca42ee7ce719908fee4315f32b4a4cd6355b.nq.gz
    ├── 645dc6a0c9ca7b6a75ec989eaca4cae1c3213f66.nq.gz
    ├── 653332355e1df535a5e56b6b158dffc14890ab99.nq.gz
    ├── 66a540065d6b9bdf973c007fd70ca42c0748b1f3.nq.gz
    ├── 672a7beda9fd2a6bf1b07f0667e3a8cb44bf0f33.nq.gz
    ├── 67610d2b2783e97c2bec6856906bdde5300583cc.nq.gz
    ├── 67898a0e83c1c0ca6458efd4ad0beeedb884576b.nq.gz
    ├── 67c61c7abf6a44aff49f2c47edc0967bb0e8503d.nq.gz
    ├── 680cc3910824d59cbe70ce98268440d12bb33cfc.nq.gz
    └── 688533113c90dd770f9b24f61c9049243a5b6544.nq.gz

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

[vllm-project/vllm-omni](https://github.com/vllm-project/vllm-omni)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
