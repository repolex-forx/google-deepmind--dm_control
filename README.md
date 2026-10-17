# Repolex Knowledge Graph of google-deepmind/dm_control

RDF knowledge graph data for [google-deepmind/dm_control](https://github.com/google-deepmind/dm_control), parsed by [repolex](https://repolex.ai).

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
rlex download google-deepmind/dm_control
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 773d5b5d94d8f58943cf56a66b9b9755818fe5b4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 773d5b5d94d8f58943cf56a66b9b9755818fe5b4
│           └── chunk-001.nq.gz
└── blob
    ├── 00f5ada0d9ae359abf18a7f6209e39aff4cebd6d.nq.gz
    ├── 01bf7afb1fb27fd6bc063de55754c6ae39d7694b.nq.gz
    ├── 01c667c9da50c6138e521af9b82a8d49b1f69a02.nq.gz
    ├── 01d3c8a50d004a158fba20b8e7a4bee7c2beb401.nq.gz
    ├── 02d449d785bda3e159d88672b822791fb422d5ff.nq.gz
    ├── 02fdc69f72eee92ceb22dec95b1926706f69d167.nq.gz
    ├── 04193e1b68b1a92d4df77483533e14d9caf2359c.nq.gz
    ├── 0488a52b07880f5161a3e9e3337518c9997c78ae.nq.gz
    ├── 0523153be2970c498f9cd7fb436a28deef3aa63a.nq.gz
    ├── 062513e31dc800c1d450fd55f400913fc1fb53e7.nq.gz
    ├── 06f49a6233947919186903c4040770ab67477b89.nq.gz
    ├── 075c526289c5959c775b626f70a4e3f39195ce45.nq.gz
    ├── 07dc68ec59a1d1395f63864f4db3ad09aa3aa51e.nq.gz
    ├── 07dfa5beace04596efd0a7762239ae7ee0c94c50.nq.gz
    ├── 0846d314b04b3b04a6db4dc6b55184f465725471.nq.gz
    ├── 085516a68c5f433f0ebfa8208c49b5d25d8a5d55.nq.gz
    ├── 08a397253a8ffa5c41715724d71aa1dcd19a22e2.nq.gz
    ├── 08d9102a86a0db31976ac9f6881405208ffbee73.nq.gz
    ├── 09e452404101a5fa886a17c772f65c34f79f9c1a.nq.gz
    ├── 0b1495cae266c07bc0f1aa061c2e77475ab4b0fc.nq.gz
    ├── 0b8e578733d50201cea311cbd0a054f3bb251d6d.nq.gz
    ├── 0bcc89810868cdfaa0b8e0f7ad089a82afc057e1.nq.gz
    ├── 0c66508656476b34807817cf9a59b344cbdfc4be.nq.gz
    ├── 0d08068e54d04e0d246bd8e3cdf44beae49f6d09.nq.gz
    ├── 0d2926cc5a378c3b61e4870b10eb10c8c4555e25.nq.gz
    ├── 0da626849cdf2731a42f83364bfb6edc0887df34.nq.gz
    ├── 0dc9dd56a84028d3a696b4e83160c379f87a0ee2.nq.gz
    ├── 0e04d93cf8919d38ef363561da5945a32fb40671.nq.gz
    ├── 0e6d3f6d3475d979ae4af4600fabc4d9a2a1cc20.nq.gz
    ├── 0f69eb68846fbba5e209fd9f95f619d37691cd37.nq.gz
    ├── 0ffbd8ae0af2ba8ffd7d4ac7de923b099615b57c.nq.gz
    ├── 100df7abcd6a7b8d06ea63bbcfcc735bee211f3c.nq.gz
    ├── 104c24cc3a8d126a36417e2754523bebd6f3ac26.nq.gz
    ├── 108ad9533746b441a51457316e09ce27211b344d.nq.gz
    ├── 10c22fae7828d5a556fefcb1529868942cf844c9.nq.gz
    ├── 10f06afe4cafd972be1787c3eb19d8d4a554b85d.nq.gz
    ├── 1112a79870341b7ca45f3f7403830121a1a131d4.nq.gz
    ├── 11545d5afb2bfd325ae1ac08813d00ea0cd5eb1d.nq.gz
    ├── 11e5f0c5798afa9b61adc637bd2871e867308973.nq.gz
    ├── 12a9c48ffa97bcd1c9a74afb8fe6071bae8fd7cd.nq.gz
    ├── 13ddba07f2142847391c40e9662d303b9a7c470e.nq.gz
    ├── 14ffddc0fa4eed338d33882d011f0d7f5428f637.nq.gz
    ├── 1682838f510cc1014a38661adf02903aa8b1131b.nq.gz
    ├── 169c44fb99d859ca9e58c9df701606ccc16f4db5.nq.gz
    ├── 17281a6859122710cefb912fbddfade2e43d835a.nq.gz
    ├── 1886517e5e14826cb579e844fbff750c7c4959f6.nq.gz
    ├── 18de4f0fa0a7eb1c715b48cd042a1254d14e140a.nq.gz
    ├── 18f5df14066baf9fd0ce9989f170ddb953839764.nq.gz
    ├── 1903f45118cdcc77f76a03e50763a0e8f270b5f2.nq.gz
    ├── 19b5ae87295acc1de6d5f30bef7181a25db92960.nq.gz
    ├── 19fe8033014fcf8f39cbeae75fc4333c99fb1516.nq.gz
    ├── 1a57f115b1fe1d2811364f6686dfc1cf38a5646a.nq.gz
    ├── 1a8cb21b5f96f6cb4ca953e2047154da64184213.nq.gz
    ├── 1b8facece95e28ca9ff7435c4dcb919479d528e6.nq.gz
    ├── 1c2cb58ce8b9db40a29b123002b3a2b59075942c.nq.gz
    ├── 1c611a9f391485966679eb9d8407998931387ca3.nq.gz
    ├── 1d0da5bba8ba3543cb2f1509cacc29b42144ec17.nq.gz
    ├── 1d0fba22e5ccc6441030dfe8db04b2f4d048b044.nq.gz
    ├── 1d4e5da4e5641e9eb589124206dad146325d6926.nq.gz
    ├── 1d95f84c5ba712c732c0c3b102fe4fa546540df6.nq.gz
    ├── 1d9e39f09ebf4f68b77dce9d1193a3a62a58de6d.nq.gz
    ├── 1db02ccd9052996992742605c3b800091d8ee3a5.nq.gz
    ├── 1db8820bbd0cdec2695fc19e1a1dd2e30c88baca.nq.gz
    ├── 1dd86b3d76a7a6498dcaf905a8ebe65327fbb122.nq.gz
    ├── 1e6bedc2142bf7df95b46cd9fb10b898301eb090.nq.gz
    ├── 1eb187296d59f7721a61100d92f6b6f04562da62.nq.gz
    ├── 1ebb270f6bc91d1ae2956e49c7084ef33c333bbe.nq.gz
    ├── 1eda0e8c64f286a7bd23b6e5e92a8930d67d9706.nq.gz
    ├── 1fa0879197b8ba7fbd35b979304b2a4a6b41af63.nq.gz
    ├── 205df18bf0b7170a7661ba16c6f47641ee237ab4.nq.gz
    ├── 20ef2c818877ff96178cf5f328704c02db36ddcd.nq.gz
    ├── 2200b5913e89f642e45caa8a2889a9c9a1615455.nq.gz
    ├── 2213a1a50436be18ba286f3e04489e2747e2f91b.nq.gz
    ├── 2216ffdd3a5b055754c45da1cba8322672b0ddb5.nq.gz
    ├── 22823c75332f1c4b715ba0e786d4d88dcc5c75e8.nq.gz
    ├── 22ddb408d5eb76a56600ca644b8341658eac9875.nq.gz
    ├── 233182f053c1858fff6833c131e836ccdba89319.nq.gz
    ├── 23a005304a54d16acfa311bdeff4566a360e058b.nq.gz
    ├── 23d321dd6821f5e37858aba2ec850f53aa9de4e4.nq.gz
    ├── 2443ced3300f1553a657199aa357a6f9f961a56b.nq.gz
    ├── 24a6debdfa92064430bf91cd326323339d790869.nq.gz
    ├── 24edea253adc6212a8f6b50ffa78280e80c5c005.nq.gz
    ├── 25354c837e35ea3ac500cec226659c68d056eacc.nq.gz
    ├── 25574f6302121340d3d75274fd07f84a364b1fb0.nq.gz
    ├── 256dc0cc5881c3b909ea8b8ae5ff6be547c2a9fb.nq.gz
    ├── 25b3e57bf5c109d2201c62690b27651f84d51820.nq.gz
    ├── 260f2972701b92616b49fe92b48e31427bb8c5f9.nq.gz
    ├── 28c3c8294801ec79dfb7b296462af1f3d100b5ea.nq.gz
    ├── 29188e5f7addba83e4d677074661f05102536d84.nq.gz
    ├── 29f5a7c7ea14a10cc52f04358408b9aeb1fb92d6.nq.gz
    ├── 2b511182b5a2646d693415133d42a03f1f7a6079.nq.gz
    ├── 2be3bcf0c5a77870bd64ef7ddabb5167e4d74a80.nq.gz
    ├── 2be7b894c7fce2db08bd5503b711c137e1f0b311.nq.gz
    ├── 2bf8edddd93404df845148ce6a053d1727970eb7.nq.gz
    ├── 2c3160c29647cdba35b9a967e74216c6afcf481e.nq.gz
    ├── 2dbbb9cfce254a006dc6554e9195dd9289ba51b9.nq.gz
    ├── 2e05586571ea300e50b563c0a367884716870401.nq.gz
    ├── 2e0acbbb06b4dd852fa246bcbb43b9995abef884.nq.gz
    ├── 2ea19cfadfcc6ab5b7cefb0cacfa54a9ad37662a.nq.gz
    ├── 2fae21a8acd2f6dfcb6e722d3201170f777c5011.nq.gz
    ├── 2fd6eb5b80750feadfa8cc587d2fa2dec8c3f029.nq.gz
    ├── 30bffa796d973803938e8f5d42c7a6d35ec939b4.nq.gz
    ├── 3309284bf29c87bc48776b814bbbaa165233854e.nq.gz
    ├── 33138d8849eab20b881da80d53aace0b6f9f3d45.nq.gz
    ├── 3344dcc8a4b535f66ccc80eab1e07d3724c6b05f.nq.gz
    ├── 338e80eb47a7d332f0e60e3b045e497f3f3737ee.nq.gz
    ├── 343f799c01ec76abd396e74bcb011b7088f02273.nq.gz
    ├── 3550adf8f7b11dc8907d82e2e4c8234042ab02d6.nq.gz
    ├── 36cbec33e27bd558d3d2d8177dbff5c36322232a.nq.gz
    ├── 391703b8d05140a54e31f823bbfb18a59364cce0.nq.gz
    ├── 3968f67e19de4fd1bc40724aad53bea8da04636d.nq.gz
    ├── 39f89db0da2d1bdc00a1a56454b85a6458212f56.nq.gz
    ├── 3a737c4950fd04f7811fe727cbcbb645625ef0cd.nq.gz
    ├── 3aed61bcd6072b520a1fa5be4ce2963372c1f47e.nq.gz
    ├── 3b92482b7d6c86dfef389747348c7a3e8d74bcd7.nq.gz
    ├── 3c4e14be47ef4d861143179b1dc6bca6a0f54853.nq.gz
    ├── 3cb4fcf2b6ff97cfa65c146dfcaebda2b0da9031.nq.gz
    ├── 3cf0b6914ca8bc2e553f8213fe1fffad114eef24.nq.gz
    ├── 3cfa95755a8a8ec4bf398a240406e8836a5736ee.nq.gz
    ├── 3d160a2a3b8de09b623577324d3d005f54167998.nq.gz
    ├── 3d43cb10cd812371c81f981a5a7acbda6289c2e0.nq.gz
    ├── 3e4aa539610a54267420261fb2a37319f8aaba81.nq.gz
    ├── 3e936e618aec8b893222ce8a1c8e80d10b8508a3.nq.gz
    ├── 3ed2fe27377106369f9e4163ed005de843ca6e22.nq.gz
    ├── 3ffee81f590ae73ea052cc886c53c82ed827a667.nq.gz
    ├── 401e807c73bbe4cc2832dc23d2c277d5b30ded3d.nq.gz
    ├── 407132a48e13a9d163606d7bbca8719be7b6e2ab.nq.gz
    ├── 40d0ca87e9f5d28aa129097c7cf61e9fc40a6ae0.nq.gz
    ├── 41518d3ce39e9cc56be896e5a630480a4a270556.nq.gz
    ├── 41d09b9b44101de0eada2ba9547f9e5c3b9bec0a.nq.gz
    ├── 41ed618f8d9aa9eed68c40f8e988ae17ce429643.nq.gz
    ├── 420d73c0a7074c762ee61becf799d9a86d7ba55e.nq.gz
    ├── 421f58bca2564e03f155b3817d41a8e515550f3e.nq.gz
    ├── 42f9d29da9cbe9f0561d5587cfd6f949ec248d15.nq.gz
    ├── 4318673159a60144a83d36c72ca7b17b3b453bd7.nq.gz
    ├── 432ba6ad2a0eb1d5ee131bee538af34a74e50b49.nq.gz
    ├── 439a67881c22c94521faa832d06ea4454998adec.nq.gz
    ├── 43b2115248fda8eac217c1cae7fc496c20aa5ed7.nq.gz
    ├── 4474b1089de207365b8ea2b9ab58fffe2250bda0.nq.gz
    ├── 44eced51043f8874c95400491be2d6c74acfb9bf.nq.gz
    ├── 4518ceb2db60bd70000ea8c84c0cf70b1393d762.nq.gz
    ├── 4592e19a4fa86bac67165d06fbfdd058268bb138.nq.gz
    ├── 4658f004e888bab95d8d15453654f5b1bcb9b267.nq.gz
    ├── 46ab4494b64a18d6d9bf38f3b62994d557511661.nq.gz
    ├── 46ccf2cd4ae75612aad2dfb4072b3191f29982b4.nq.gz
    ├── 46d43b0b92cd18becdda77f895556b7ab9031ee0.nq.gz
    ├── 46ed4fb43eebbee296642d0c119a0a241418eb96.nq.gz
    ├── 46feef3b42b53abb2893841040ab97dc0f1e1f6c.nq.gz
    ├── 47858d53a1f20ff54038791fa845a709c1e33dba.nq.gz
    ├── 480691c7a4e669f7b690f4b4880dcfa2f4d9c71a.nq.gz
    ├── 4937614fdf685afbe5f3553831771e0d4fb92e39.nq.gz
    ├── 493a1dbe4103cd96ba840c063f605b4a140c329d.nq.gz
    ├── 49de0c2518157b61c13e1500c153a557c71806f2.nq.gz
    ├── 49ef02722d4c56b68bda0ed64db8c6281b51add7.nq.gz
    ├── 4a79c5d49d3b30a6b141cf984d8ecc605ee3dce5.nq.gz
    ├── 4ae5dd909e6913e8c9c772296bc16c6394a8fbf7.nq.gz
    ├── 4b6a026e4914ea040ca4cd24f32ac48d38ea808b.nq.gz
    ├── 4b72db03fbf23a597b46c1cd59c78fc8cb04d957.nq.gz
    ├── 4b75626b96faf030f1dac1c6b7b4b4b3aa9dc9db.nq.gz
    ├── 4bce42b277fb1ec0f3b3ee1443e05252d8b542c7.nq.gz
    ├── 4c224a0da45cf6466609147f74aa9cd08fdd656c.nq.gz
    ├── 4c7d13135d40fece53e64d9a7a37bd09b7a0b6d6.nq.gz
    ├── 4cd886b5473c1c44fe9ac9592b2df1ca77827c43.nq.gz
    ├── 4cf6005d8d155c09cc9cc151131fb17d4980d630.nq.gz
    ├── 4d6afe4331155ba52c88f74ff4bf19765d551c27.nq.gz
    ├── 4d92e64a5a9dc4683f18c971461c2a20f44cb0b6.nq.gz
    ├── 4db770a7a8341a7165a90038bbb157247cd1c994.nq.gz
    ├── 4de5080cf110a0d809c45162e182133f3617ad41.nq.gz
    ├── 4e023fa819e4dc69f674ae0efc265f923756177d.nq.gz
    ├── 4ed80767d54ba4ed1b1790d4a0a30da34029991e.nq.gz
    ├── 4eff59b91f88f814530781dd8e5623ee43a25722.nq.gz
    ├── 4f42aba4ae7e43d3d1115f7b2ffa84b9d5fd596d.nq.gz
    ├── 500ae4c19710d43e682ea32b2be1fe39ad79c4ca.nq.gz
    ├── 517841a5d5b004c75c4b4638fcc83a7a2ad47376.nq.gz
    ├── 520f668cc9d03ff3da8cb64fbcd6322637388a99.nq.gz
    ├── 5266fc5833184e3486844418a5d9827f61a92b8e.nq.gz
    ├── 53585ca5146429018bd7700ac2a6cde578f30f2d.nq.gz
    ├── 53c06e7cc2fc7644f448f1e14f1ee922cef4ff95.nq.gz
    ├── 542933a9f6c227dd4e2f287f4a655a896ccdefbf.nq.gz
    ├── 547fa7679a92cc5a3257d9f12c3a9e733469e307.nq.gz
    ├── 54d218edbc91952df07f8cab56089df16b557a22.nq.gz
    ├── 55833174a658faba2ab9ed85e4b617759def3038.nq.gz
    ├── 563fb5e0b5cf61ee05764b3f34fef0c4edfe5ed1.nq.gz
    ├── 57d1dcb7837867387ed014907376a835fb9e59d5.nq.gz
    ├── 58989bcb4192ffc38ab9bddcf1d190c63692918c.nq.gz
    ├── 58e2a092f6d0162b3b74ba34f94ce243dd4ba04b.nq.gz
    ├── 59d3fc7bed926daa7d0a5452c35ea4998f66f509.nq.gz
    ├── 5a0aad76b061cfa9af5b7fc28bc925df9235e135.nq.gz
    ├── 5a7718fa79d033f5a83cf237c61b894a275e93c6.nq.gz
    ├── 5ade6aa20f73604e3cd47ea5702b0d52c1a216f4.nq.gz
    ├── 5b19629ddcf74849f4efe541c7c17d3227a1b0b4.nq.gz
    ├── 5b206d5b1575e6b7cb064dc62b199c063b1d8211.nq.gz
    ├── 5ca584b399e3f4a9211a942ef18e76708225e740.nq.gz
    ├── 5cfc615cc0afdf8db5f21fcdcff64065b7e49b41.nq.gz
    ├── 5d6736bd7c5c9d6afdb1da9e58818ec9e15ff1ab.nq.gz
    ├── 5fa0b6674b966c90e1e926a7cbb931421a3201d1.nq.gz
    ├── 5fdcb7351669a7236ca7fd7f8087e0ceb32ceccb.nq.gz
    └── 60e0ede2477a1d3975169f47d51b1c5b661b81c2.nq.gz

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

[google-deepmind/dm_control](https://github.com/google-deepmind/dm_control)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
