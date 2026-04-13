# Repolex Knowledge Graph of chriseppstein/compass

RDF knowledge graph data for [chriseppstein/compass](https://github.com/chriseppstein/compass), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download chriseppstein/compass
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 76251a8d38902a46a5213ec6343f776ee7f8be2a
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 76251a8d38902a46a5213ec6343f776ee7f8be2a.nq.gz
│   └── repolex
│       └── 76251a8d38902a46a5213ec6343f776ee7f8be2a
│           └── chunk-001.nq.gz
└── blob
    ├── 001ccfa25aeb34f1cbf99566cb031d9d95472257.nq.gz
    ├── 004dbc09c8b42f069c13d663fa17fba30c511c16.nq.gz
    ├── 006680487e2dba572b80cfd59b5599690aed53c3.nq.gz
    ├── 00a931faa035b73b657e08f020751406774e563c.nq.gz
    ├── 00ab34e53c933d098e07e806aa00742e0c02a050.nq.gz
    ├── 00d8a20b0c32d97fc97f9b4e40ba6f7b0d45024c.nq.gz
    ├── 0107be27349330250c3c28f52ef5dd58a25690ce.nq.gz
    ├── 013653b1dd6231311e969d6844f4a6e3a222d8b7.nq.gz
    ├── 016aba9059c7c93093fdda0065e6488d601288ca.nq.gz
    ├── 019bb56866adf55f10a2483ec39162efe17c2223.nq.gz
    ├── 01a595fa3f434335d3bb621908dc0d1bb70b92ac.nq.gz
    ├── 01a703afc3d7fd223d821f4f23367ad2fe74ab07.nq.gz
    ├── 01c747d25f4bf25582872bda6ae0ffa84e0cc50d.nq.gz
    ├── 020b4566bbb1a793628933fdb46c1d49e6659c69.nq.gz
    ├── 02b5234533f563425bb180b685d49c75d9299bf2.nq.gz
    ├── 02db69fce20c5f71bb2dd4f925b5533ba8f6b9f7.nq.gz
    ├── 02dfb0036aaaef70d3e7960071da5903ded3c2c1.nq.gz
    ├── 03103651366267ee62c793a93613126f8f5c96ee.nq.gz
    ├── 03b2845008d00329da1130391d20692966cdb645.nq.gz
    ├── 042916092577690677ae32340167cb614e8a2085.nq.gz
    ├── 045a76f97deb78ab6c4a9ba9487885f81d18e3e5.nq.gz
    ├── 0475a8a562fd8158b1dad71b4f87817fd491ce40.nq.gz
    ├── 047e6368dca78a66106cbac36afbcb7010d7d9a5.nq.gz
    ├── 047f8f520d8e2a9b1c1e8639f7a115e76a027861.nq.gz
    ├── 05170cf4d35cd2c240021fb119e2a80bf89c5c33.nq.gz
    ├── 05485bce1429e6c2f754899c5ce3ad66f6403bd4.nq.gz
    ├── 055f641635633ac12916d5d9ac7c9edf76a5044c.nq.gz
    ├── 057568e4d18d2e484e8a80bf77845cc357621318.nq.gz
    ├── 05838f9f9b2bbd097bce92a50cf04a9670844b74.nq.gz
    ├── 0668be8d50b0b71696f40898444e762e609e0dc3.nq.gz
    ├── 070ab3fb3caefb3c3b02ed017b86d0a92805b58c.nq.gz
    ├── 0713f986c0876e6898226e65c4ecc70fdc28e8a5.nq.gz
    ├── 073874c9d64f78337c9baf97fd53c450e43f0149.nq.gz
    ├── 0761261ffbd00694300bf2e34749442e3ab13206.nq.gz
    ├── 07757c5daca26d1fb1711c2bf75d2a69db54445c.nq.gz
    ├── 07874576d7c65f1bfd208d56841def5a294550e8.nq.gz
    ├── 079a84e6d2f5f04d878c67a7e5f1b56394e9095d.nq.gz
    ├── 07b2024c361bb90c072a24f1f4d653b04afb80a2.nq.gz
    ├── 07e5b5c6d800efcb74cc1b8dfbfae04095f46216.nq.gz
    ├── 0843c512bfab1bf8729eaf9dfd50521ffcc0354e.nq.gz
    ├── 08b4afda548929547f283ff00d95394aa9985f56.nq.gz
    ├── 08eb086fd22d94d4ed70284127605818efeca830.nq.gz
    ├── 08f927955373c40288dbd84e1cadc100d94a94b4.nq.gz
    ├── 0968f6da905af3b9c0bdfe4c9a838593ea469da9.nq.gz
    ├── 0978b0d1cfcf091b0f4f8f541b323b48c746a83f.nq.gz
    ├── 09980732409247dcd1eceaaea5de8a53e531ecb4.nq.gz
    ├── 0a267049fb9a8dfa0d9f16a770fa092db94fc92c.nq.gz
    ├── 0a5546a5d20f9bc7746248175a51b1737060f263.nq.gz
    ├── 0a593f13b1577c7b6d30fd4cbfeb8b69df074436.nq.gz
    ├── 0a6606ce54b6709212506a9abac396772791a24f.nq.gz
    ├── 0a89862258df5e5cb8fa60e37348de58a0875009.nq.gz
    ├── 0a976dfed9905458bf0e6f8545ad4e541efe8d5b.nq.gz
    ├── 0a9851850b39d5c1527bd9152041f2995b1a8dee.nq.gz
    ├── 0ab5d2768d8a9f5ab012e3656d1c5e0e4fca8628.nq.gz
    ├── 0b920b39bbd2e71bfff81252eda33f54aa2f5322.nq.gz
    ├── 0bc97ca035313ff5ab7ef818347ae0c75dfec01a.nq.gz
    ├── 0bf4eb09287c63a972efd7eb091b6ade4e5ae87f.nq.gz
    ├── 0c01a39183cb00c3bc05ed4f0144b3401370f039.nq.gz
    ├── 0c2ab885b363acd8a7599dad4b43fe2f4303968f.nq.gz
    ├── 0c6363c1e1c7be80ca9449747cb6fdd1d66e271d.nq.gz
    ├── 0c64457a3aa9f8dc03a9907acbb906ad1229fc09.nq.gz
    ├── 0c82f64ce71dd662268f072d41565c7b36aa3365.nq.gz
    ├── 0ca550e016e2c245c0f789869702c4a9bb8c768f.nq.gz
    ├── 0ca9f671023fe8931656c885dd83dd0ef47e52dc.nq.gz
    ├── 0cbf627b2848e3b7e2d355b51cff0581a7ef26dd.nq.gz
    ├── 0cc7fd1638c8da90db7bb7bea719fa51fd770958.nq.gz
    ├── 0cd4e205841d82b8f199df16d5e3d281ba115498.nq.gz
    ├── 0d48b807076df888c94fcf790846c8aa9e740eda.nq.gz
    ├── 0db0204149e1886425fed6a8600b9c14aa3dc23c.nq.gz
    ├── 0e649bd4eab239d1b05f1bf4bad9f5f6a1a47e65.nq.gz
    ├── 0e8736f8c181d53b8ae69fa1017706acbc67ad63.nq.gz
    ├── 0ee0167cfb8b68f4c629c17fc8c9542419a0af52.nq.gz
    ├── 0f4f8e645523193c0641414a694cd3dcd0dec9d3.nq.gz
    ├── 0f820a9c5a8d5d53b3981b783027d93710a1c506.nq.gz
    ├── 0f8775a4f4ad72d68e86dc9ea30aaa35524b0793.nq.gz
    ├── 100b647996c40cb8bd45d01bd07fbcaf2d7ffd31.nq.gz
    ├── 10ac07c2aec30a2f91811ae13559f17c2c6e6c25.nq.gz
    ├── 10be5baf51b9acf2541fd3fd123c3cbef6edaa48.nq.gz
    ├── 1121c1268e7f9009ab5876fbecffd745b1a7e44c.nq.gz
    ├── 11492be71d8426eb074cf61157165dec4a933bf1.nq.gz
    ├── 11570d8ad30a59ae03388f588e23c4cc9140cd8a.nq.gz
    ├── 118c5c7dca4d6c1bd184cbced44e3d98b26265d9.nq.gz
    ├── 11d24a66f8fe46d71184d2b6d1b6afc5ba6fec46.nq.gz
    ├── 12616153338778c9203dd8667ba8c94c4936291d.nq.gz
    ├── 127f0f24298b2aa88b27bb2142e77d3df6e638bb.nq.gz
    ├── 129d4a29fbe92688aabed5638e0c4f73a7bca818.nq.gz
    ├── 12a9c3e4f780ca89161ba65d75783981dd62a812.nq.gz
    ├── 12f8f7cf2f39839020fdb743b1c3970ff6c48539.nq.gz
    ├── 131e54d8c0a3606c9de390983f1dd9ea08f1391a.nq.gz
    ├── 1324baad2e9d7299d2d795df08ab05acd0c60f30.nq.gz
    ├── 13400385154d6c70059ac8647375fad5f369fe02.nq.gz
    ├── 13821b8eae0f2d6d023d390da25206cca63f0b13.nq.gz
    ├── 13e11013ed8134925d48b4f30aec68fc56793f92.nq.gz
    ├── 13e93f2f0f361e797c401c691ce62f8c054aef19.nq.gz
    ├── 14ae800f93cc9d00bad084e0abb50bc3414c2751.nq.gz
    ├── 14bfb29b0011f2d28d2f0b0ee8387ecebe58302d.nq.gz
    ├── 15130687e154b3c668a760452a01255ae8781037.nq.gz
    ├── 1514d51a3cf1b67e1c5b9ada36f1fd474e2d214a.nq.gz
    ├── 156c89321c36a929d7e416cc91093e02c51259ee.nq.gz
    ├── 15dd2cf32abac8eec2ce6a39fd4e8cfac07da5a2.nq.gz
    ├── 1613dd67156aa12897edc023018d2c3c2d8633cf.nq.gz
    ├── 16981e5ab0c8017d03eb90855f2eab13eb953885.nq.gz
    ├── 16f4235dd1c9e6e954cc3c926e9baa4330458faa.nq.gz
    ├── 172a815f7b359017f2b3f915e05d4647d48eea40.nq.gz
    ├── 17398e417df9a9591a430fe9e483b0c74e109798.nq.gz
    ├── 1743fe8f8de4a39a6568093883a8a60c188b4705.nq.gz
    ├── 177c6604df9d8d2cf90ce1a2c4ed4c8e0166d599.nq.gz
    ├── 182e7f285e5e4f08ed3d9865af4720e9ce052d77.nq.gz
    ├── 18353b275835850e4d38978644fbd02cc3196e36.nq.gz
    ├── 183626b77e6eaf3267367b0af9a966ee76c991ed.nq.gz
    ├── 18c05a8db97491b7937c120ce769643d938f5323.nq.gz
    ├── 18e9b14383148c59709a3491b3d1f6892e06044e.nq.gz
    ├── 1904b78f5a85f0b4b8609fc3b672e92cdb944c79.nq.gz
    ├── 191b74fb69c3287c89437f041d00dbaf0efe39c8.nq.gz
    ├── 1958bde60405334d3968907179f392d4ee0852a7.nq.gz
    ├── 1963e9dedcea70e5de0b01355052f817bf8a80e9.nq.gz
    ├── 199b5df54c2ab593a4a926b4d41a7df525f1e292.nq.gz
    ├── 19cc57c9d7d7e696bff7fee3df606b9aa5d2012d.nq.gz
    ├── 19d06f17f0913f0dfb1bb8cce8d69477f56520a1.nq.gz
    ├── 19dd7b46e8843183938acfe13c7d06163ab5f0cb.nq.gz
    ├── 1a065e503260a3655f2c31abf9dbef437ab66669.nq.gz
    ├── 1a3900f3173f36adab519d452b332caf2daa4c67.nq.gz
    ├── 1b86ef56819e614873873dbaa33f66036f5f9b53.nq.gz
    ├── 1bd4bac44affc956aad4edb8057ee1cb237e35b9.nq.gz
    ├── 1c1d071d9319db880183ee61c71eb45b1e6c4047.nq.gz
    ├── 1c48f468459ddba7ecbde80585802752f5ef6db0.nq.gz
    ├── 1c57ddfe7950f577c6178ddd07949fd155ef8107.nq.gz
    ├── 1c761f0227f825848c76a3f7a757e89fda14d670.nq.gz
    ├── 1c7c689e65da935e115b72e3995fbc1b3434f4a5.nq.gz
    ├── 1d6a91b1d0c856d02f1e35cc1cfcc2b0127eb0ec.nq.gz
    ├── 1dc9f0b471a6f98a8abbe39e17f6a4fb37a9c37b.nq.gz
    ├── 1e02644183b2ffa952e830dac26a17a30bd3ee41.nq.gz
    ├── 1e2f5f139f60d1c17b1a5649e0f5122e4c00eb62.nq.gz
    ├── 1e6e08fb6dc3c2f46c6b43e4178c1feab9ee6680.nq.gz
    ├── 1e7dcd500cd074d079fe3cb38ab2575a7e5c0d2c.nq.gz
    ├── 1ed4b91582b9bbf1ec37ef24cb0490480754f5ec.nq.gz
    ├── 1ef34a8596ade105d0449745fb0cb8b5c3135cec.nq.gz
    ├── 1f4230633ae629eb88daa1fbbcb045975c4bfed0.nq.gz
    ├── 1f93409e8524cb9b690f444a6d1a736fa5cf0e49.nq.gz
    ├── 1fbf4ef9cc85789fa141a469b2a07adde553b6c9.nq.gz
    ├── 201edfc565dd6a23e89e348e5032eab758be47fb.nq.gz
    ├── 205d8d6be7292db7ced417a097f9b7eaaca172e0.nq.gz
    ├── 2089c091b40a55fbddfd26775b4b2b10ce448d0e.nq.gz
    ├── 209112fd32b6e2c65ed413afc7ed012870f160d7.nq.gz
    ├── 20c379863f92a3321f03fcfc1a92750735adf70d.nq.gz
    ├── 212e211de9e131808cba9a5ad7e3e20ed149daa7.nq.gz
    ├── 214776ef89db028d8ae01e57ff13e210f6148738.nq.gz
    ├── 21728f74d74f4e5a29914df45ac7f8131b8ff44f.nq.gz
    ├── 21b5fb610412faa7c3a08ec9a3b76cccc256611f.nq.gz
    ├── 21f67fc51f266a8e51d8e054863d1c1368c36fb4.nq.gz
    ├── 22382d2520dc76b80e9b2d67d239e61c283957a6.nq.gz
    ├── 226d9264fa973d35ff7f3efadab08111f011f596.nq.gz
    ├── 22e70a52a4cba6d691b08e2add7e985a8bab4a2c.nq.gz
    ├── 231994c2d310b61b75de1c2fd60742ed24bca631.nq.gz
    ├── 2379dc30a828d81591ab9959791950d7996db783.nq.gz
    ├── 241163e932a5815ef1ec5d0b4f13059c49987228.nq.gz
    ├── 2415a554b234c8493c5d816915a46b12d25174f4.nq.gz
    ├── 2439984d904887f02d5dbcd87c0d36501372718a.nq.gz
    ├── 247acd2c8e560a31c743a929b3561755a01732b4.nq.gz
    ├── 24a2f31e64413880456a04cd3df7f8a52c1ce3ad.nq.gz
    ├── 2505a996f28f16335ddcd3f79f3e525617d7dda6.nq.gz
    ├── 25202a24b3a8191365b070045cffea8b69b45f7f.nq.gz
    ├── 2566776e3b3d59dbe7e427183a5d495401846e73.nq.gz
    ├── 2592de09bc94f79682d4162e0df38b14764b6e21.nq.gz
    ├── 25a4b64a5b7b7ffd6ee19ecc1e2295b797c365fa.nq.gz
    ├── 25aa1a2764ead53fcac95bf78c8cd4d612316533.nq.gz
    ├── 25af545b3843446bfd7fd4a8d5a6fe817893ce15.nq.gz
    ├── 260bd900dc07dd1d7a46b38923ea9e86c76d37d7.nq.gz
    ├── 26670864d9243a6c3949abb295b13a798bbd213a.nq.gz
    ├── 267f98f45f1648c796e2ea864f159f25aba02eff.nq.gz
    ├── 27161f17783d0ef2176687867459503050b87ac3.nq.gz
    ├── 27434f29efa5a0712f277d87bacd463e17e754ff.nq.gz
    ├── 275c09e9acd9f2ddbbaceb8d788fa0934a60dc8f.nq.gz
    ├── 277ae9127a053482f1047f9c7e8599f7f5c86c3f.nq.gz
    ├── 27e6647091dd2f636c22eaced877bf013d4d2319.nq.gz
    ├── 28d8ba89a8d18509b80b3100cc5d0c6287a8cb46.nq.gz
    ├── 28de86e4716d5ce34c5f34de45f403828a165162.nq.gz
    ├── 28ec49bb4611f6499c3fc8cf930d16aba05f8856.nq.gz
    ├── 296539f4244a035d001d023cc5f941dcc3ce4a5b.nq.gz
    ├── 29aaa169175a0e86f0826c900e945578435102b1.nq.gz
    ├── 29c8cd119f797589efcacefe4f319d55c0d57ae2.nq.gz
    ├── 29d0e184099b68d4e9532800201ffbe86e0457c3.nq.gz
    ├── 29d448a0b6f56c0a4224c7ed18f3a9ce9fe6f3e4.nq.gz
    ├── 29e331877ffd8a0c1eea2474ccf0a3dbaded26cf.nq.gz
    ├── 2a00d195d1a4840a854c79e33f79631787a72163.nq.gz
    ├── 2a6165c4a7c4a8febf8e5b1c8e04b5a5651d8072.nq.gz
    ├── 2aaecf9c21013610931cb21cd72fdbc2d57338a1.nq.gz
    ├── 2aece0af4708b008ae3bfacdf29c0eda9fac9bfd.nq.gz
    ├── 2b0933a7394d24ef1dd0d71930ee8dd7a225dcbc.nq.gz
    ├── 2b4a36e4047eb4a0a83df87d37b258c2d5215454.nq.gz
    ├── 2ba10d5178f19bef7bf4b20eafe436961d060be4.nq.gz
    ├── 2bb89b98d16028707731af66ffb7af917781c60b.nq.gz
    ├── 2bcd04a82524cf2484b486ed24047e6abf9863a8.nq.gz
    ├── 2c11f0bd49376116e0c72b6d38d1ed089e4cac43.nq.gz
    ├── 2c16c9c5e77c76f85659e904190abee8cab6af1a.nq.gz
    ├── 2c30c1681cb238a87d7edb3e691add6fdc005483.nq.gz
    └── 2c60244e1d8c0d93924bf523867b7761e938e3c3.nq.gz

8 directories, 200 files
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

## Source repository

[chriseppstein/compass](https://github.com/chriseppstein/compass)

---
*Parsed on 2026-04-13 by [repolex](https://repolex.ai)*
