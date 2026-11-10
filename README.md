# Repolex Knowledge Graph of timocov/dts-bundle-generator

RDF knowledge graph data for [timocov/dts-bundle-generator](https://github.com/timocov/dts-bundle-generator), parsed by [repolex](https://repolex.ai).

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
rlex download timocov/dts-bundle-generator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1dfdcf8993e37d7dfc757a8b6ef38f24998b5c9f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1dfdcf8993e37d7dfc757a8b6ef38f24998b5c9f
│           └── chunk-001.nq.gz
└── blob
    ├── 0001feccf853b274beebed980ce6491c193da7bd.nq.gz
    ├── 00f5e0aa03c006bdf17c06b681da8ecc1e5e84aa.nq.gz
    ├── 01912edf269024047f0188986eee8b7788659060.nq.gz
    ├── 01bce94bc7e1d1c0da1db0b8b4776dd336f0aeca.nq.gz
    ├── 025482b1bb880b827b261c72d9d49f5d06a50cfc.nq.gz
    ├── 02dc1277ab18131628bea99de589c296f81360d3.nq.gz
    ├── 03ddd6804dd3a6e3f4eb4a17717ff283abcb1bbe.nq.gz
    ├── 03f323b26eb9c12d98e593dcf5ae0c5f2d16ec00.nq.gz
    ├── 043ad2a904905ca8d81008e6fd938fe48eccb8b0.nq.gz
    ├── 04967c1d04b5640f4b96392fbe2962bec64624e3.nq.gz
    ├── 057b32aea7c825f668f1dde6e01ab55b16499380.nq.gz
    ├── 065f1f72d584e38265a4c75e6f347e088a775c5a.nq.gz
    ├── 07ab534f98b252451790f5d81112cf62a96b6719.nq.gz
    ├── 0801d5208580909b4834e5cc3602123b64ccffc2.nq.gz
    ├── 08d725cd4e46f2d8e1157ee7a75d7cb19c08e295.nq.gz
    ├── 09708d8da23888c46b72e5200300568a6785561f.nq.gz
    ├── 09a07dfe147852dda92d52917967f16404fd1029.nq.gz
    ├── 0a5754077a5e15b425428e1d69dd275e46a60ba0.nq.gz
    ├── 0b9c49e06a95dffd252287cb2ba415b4ed0eb0b8.nq.gz
    ├── 0bf31067710e712cf28cbf2ae1469901118745de.nq.gz
    ├── 0cde14b9d7d262390495f64f027f41c0e28509e6.nq.gz
    ├── 0d6a08b9db5756eb5c1912294bbdf256af80f3a1.nq.gz
    ├── 0de10d223d17af081785c496447a8efd707ef590.nq.gz
    ├── 0eb8b7eb6793517412b0606952bf1d34fbd7b107.nq.gz
    ├── 0f656cf2256acb4b672e8789fd6696233b9a08a4.nq.gz
    ├── 10ef746cae3c0a6d5b273aade3197b1e508693d3.nq.gz
    ├── 11bc642772ab2f0c7e7d352e9dc0434d868c0e57.nq.gz
    ├── 127cbb14ce80b63fc70507e93699b6e72ee9e6b2.nq.gz
    ├── 12a0d36e28aecefa4356157b75ee72de9fef2fa1.nq.gz
    ├── 12b92478b9c5360e4b1bed85d5ceb3c27aaa9b54.nq.gz
    ├── 135c8089c54dfc3ee7bf196106ae8b3e89a80a47.nq.gz
    ├── 138b741761cbe1041898bf7817e3312ef3e44c70.nq.gz
    ├── 13a052bce8b61bd3129f82d3c294e5dc0fb09a68.nq.gz
    ├── 14647141b5db06944d204e3401df716a48a7bbe9.nq.gz
    ├── 1479367ed068aeb2ecdfdca9ab94bace0c365900.nq.gz
    ├── 14c6b9a0d5b1c2a555d59429c89672767954933f.nq.gz
    ├── 1575e2b70960ffd4ecdbece797f2b1893f533dee.nq.gz
    ├── 15be0647f31d6012387e3d6a0a5e24fb7b5cf130.nq.gz
    ├── 15df8143cc862162ddfc0050bffa2f01267106de.nq.gz
    ├── 1665d59f040b50d552ba4b3c74b87031ebad7e20.nq.gz
    ├── 1677fb124d3c7c9e54daf2e0ef9138964d757972.nq.gz
    ├── 169ad6eb6bef8c073fd8c7ac7254641c71b84c0f.nq.gz
    ├── 16eb0a6fc9ab6b7edff09faa6bed2fb2f2c23c76.nq.gz
    ├── 1708c0cbd1746ddc4711c0a4926e032490bd82ec.nq.gz
    ├── 17a50ecb6913a903e54554ec47ef529e301e935f.nq.gz
    ├── 17e05150a3d081f04fd4a7f56d9711e90c1b090c.nq.gz
    ├── 18c230e493cbe5a46df91f0ec4029223f131b73b.nq.gz
    ├── 1a0671234a6a8cad30b1cb717a8b903cfa9cab5a.nq.gz
    ├── 1ac30fd8569a80f39e61e771d9e5201b07ffb265.nq.gz
    ├── 1b9e1c1ba9c741664161c929eb9ba71c024aa47b.nq.gz
    ├── 1e05ed7c6a1b7c640cf25d378ec7198456c7afbf.nq.gz
    ├── 1e57801739afd02ef574620ec51ab8a4e624b383.nq.gz
    ├── 1ef2ae406ce1f3f5911276cff7a9f25cc860b5e7.nq.gz
    ├── 1f718a9ab83a44d012530cae16458049534b870a.nq.gz
    ├── 20f37a906f8d09343abc0a957b7c65e61234a915.nq.gz
    ├── 21403b208047c10612c7484abbe0dbd9f944471d.nq.gz
    ├── 218660a749fcfd080ddce4c9c2236c1f7eca011b.nq.gz
    ├── 21a1862140d371ca586a01c58157a6f9e1a30724.nq.gz
    ├── 224da9f5b07c43d8924da75c9965754b7f1d1932.nq.gz
    ├── 22ae0dfe9e62b74f8b158df00539f3e0685d6f40.nq.gz
    ├── 2322aa240db5ab18466a6033206b70fe165ba36e.nq.gz
    ├── 23a1ba936da978f89dcfd1089c47a2f59cfe4a40.nq.gz
    ├── 23eab4444c46294dcf628cc2469a1b563b44307c.nq.gz
    ├── 24eaf6ebde09062ca8f3990dd7d2d4bfdec403dc.nq.gz
    ├── 2540c88936aec59064b8a89f0dd2cc71f56ec23e.nq.gz
    ├── 25a501110c978b1adaf25fb450f11ddd562cfaca.nq.gz
    ├── 25a803d704cfcc1474a38525ee15f785d7332911.nq.gz
    ├── 25b7ddd8fc6fd4be43ec42ee38d224374f7f3f42.nq.gz
    ├── 2869c7173e2ed06d0f68d5776858a0a34351a1e3.nq.gz
    ├── 2a31433548fb9fdd337d540cc14dea0fec232061.nq.gz
    ├── 2ae3b90e36a351d29d97c571feba31d3462c46b2.nq.gz
    ├── 2b94213c4eae521dd26d371b55870bce91e7196f.nq.gz
    ├── 2ba7073b15b13544f215e9caff28c3e31540ed8b.nq.gz
    ├── 2bba64a1a116532cc1477a3a8dc01d453eb026cf.nq.gz
    ├── 2c306deceef6b0b58365246f4cb8fee6cd5d78cf.nq.gz
    ├── 2e2ea28fdba5e7f75ad24c333be5057f7504110c.nq.gz
    ├── 2f4b7771324c03ab836c5712e3b864ce290c621c.nq.gz
    ├── 3091029609ef943fec33e201a3f17f160e86999f.nq.gz
    ├── 32954d0394bc10beed8675f856be8ada70250911.nq.gz
    ├── 32c01d63ded7ad6b37dbd4cf29e724126b646e35.nq.gz
    ├── 32d1222de861ae88794a57836327d5230657c3f2.nq.gz
    ├── 346d22fa68d559abeadcd5f76ff16f7e64e01109.nq.gz
    ├── 34e4d819d5d07fd6167dd055872e3da124ad1eab.nq.gz
    ├── 35342b6f2561025fab0464e8ccc85980ab6d31ed.nq.gz
    ├── 355a4b1f34d34fe5a1beee206a8afa6d7ef66d68.nq.gz
    ├── 367c710bba62dda60f89486443926fa7bf5de7cf.nq.gz
    ├── 3701f718b53995f0b0ecd34bd2b2e8b27ee3cff8.nq.gz
    ├── 37f0353fdd44815ecd42d9c11e6d59e04e434baf.nq.gz
    ├── 38195d7d3c2ca7b3244418bba2cf453d28bfb111.nq.gz
    ├── 38cd5c2d92f7db67ee017027ffa68d8b6c5fd01d.nq.gz
    ├── 38f02ea7b853b92dc5ba067a0d9ec5f0cfce1f15.nq.gz
    ├── 393e715f4ef8705e768bfb6ff84e5702f0d980ec.nq.gz
    ├── 3940cbf728278de6a47e3081c1038b55280f717b.nq.gz
    ├── 39da7b4a79854cb9471136e78cde1f4e1de01406.nq.gz
    ├── 3a0392f240a1bef43ca0daae62ff64ae3c6bcd17.nq.gz
    ├── 3a03f90c4373cfe8bdf4a5f8e061a7820a259440.nq.gz
    ├── 3bf3ae417fa36d7cf338fcaa333748399cf77183.nq.gz
    ├── 3e0b2870097aed4064758a92dad6cafccb9ae363.nq.gz
    ├── 3e9c7fac036fe44eb9d69b1c59b429751a794b52.nq.gz
    ├── 3f060171ad1db884679ce7f45588e52a3313e630.nq.gz
    ├── 3f7eea345b49aea415d0cad0d8753cc2c57a8694.nq.gz
    ├── 3fdcbb452d56c8dccabcfa8b3ff58b8821da5535.nq.gz
    ├── 40d8849f5368187d92429dda5faf94556d704e2c.nq.gz
    ├── 420da73f8d603245f857edf157fb5012bd563f8d.nq.gz
    ├── 4236e2752caf8cb3355aee2a605b75f7c05aa317.nq.gz
    ├── 4327a476998f697c26f791e52e18ddbc7a647201.nq.gz
    ├── 437c068973b809ded5abbf92046fdbeb0d327dfc.nq.gz
    ├── 43c97e719a5a824700932f72e6e7e6748ce45d01.nq.gz
    ├── 44a4c3a4486d23c6a19732695b514d5da2c7b908.nq.gz
    ├── 450512fe44013e1e23b53972ea981b59334416bf.nq.gz
    ├── 4544e171ebef825594cfe957020efba21fa7d570.nq.gz
    ├── 462f1655ac97f36ca2b994b07cfcd4b006bf2cc6.nq.gz
    ├── 484bec7d5dad36816d1f2c08e8d46da40968d059.nq.gz
    ├── 491ac888a863de69ec426b55b725322a7c76255b.nq.gz
    ├── 49b6876294d5e211eaa9c4a670e7f90056e13313.nq.gz
    ├── 49ebee322f6dc63e57cdbbba3ed77d5c5ac00c4c.nq.gz
    ├── 4b05341bcf433c95ff9e67ebe6f07621820b5284.nq.gz
    ├── 4baea076122677343f259e28823a0f80f69f7416.nq.gz
    ├── 4bc51df9fffd03d00c1d23cfacdf019d05a16ee1.nq.gz
    ├── 4c6133a89dde493f5921496fee9452d172e80c9f.nq.gz
    ├── 4cc9316b2b32944843cc3fc1ea9a1d4d8d8926cb.nq.gz
    ├── 4d0ac35c4e34add21c5976f6b30d36a849387c39.nq.gz
    ├── 4d4a5f091d9e67fa6bf01b4bbf70b44b9013e73b.nq.gz
    ├── 4d6e051ce1e771d6c0411ca1b2c779c35d05de7c.nq.gz
    ├── 4dcbff1196e9304c0327ea41cb6fc00917c9a45d.nq.gz
    ├── 4e16911548337736419a2290d596b7a75b3b52bb.nq.gz
    ├── 4ed55835a29e446701897f6d126812d124001b5b.nq.gz
    ├── 4f09a612ce0bfb027782022b94f158d88641e86e.nq.gz
    ├── 4fb2679ed9f505c7c2dd2e33875d8647bae369ea.nq.gz
    ├── 4ffbdf779a22ff54aea87d253024d265b258bb8a.nq.gz
    ├── 51c07cd2c9c6959fe6e711605c1789ad6bf414a8.nq.gz
    ├── 521c761c883212ec63caa53425fd6f7db59c926c.nq.gz
    ├── 52250b777dd1b0d4f757b5bf13890f9768724936.nq.gz
    ├── 52d6ac91714310c715136abf090aa93572ec424f.nq.gz
    ├── 5323a119f806ea71422a17c339fce0b0a5e4e51c.nq.gz
    ├── 5380870f0f06900430e28a867f67410fb9a0f8a7.nq.gz
    ├── 538cbd6c5c0c933b115db06b36a4601f53c84e24.nq.gz
    ├── 54f331d2352d8480d3f2d88cbc2298d541a0acdb.nq.gz
    ├── 54faf006a5a8700b2e133163002b1d39412ab5f4.nq.gz
    ├── 55629c9493150f23f5c205e1d7ba8294cf4b824f.nq.gz
    ├── 55cbb7a711f9ed5b60aeccd1a818bc4c2ea79f0b.nq.gz
    ├── 571ca8a8051bb1bf5d6cc4ba78397419b6e9fe78.nq.gz
    ├── 5792d3b96df0419532f5883d635dee29aa344647.nq.gz
    ├── 57c4d378911cc224315a506140b3b11f1465cc7a.nq.gz
    ├── 57dbbf0f2cfb3dfcf08411fc0b21dd1de723b827.nq.gz
    ├── 5833fc7041573c3015881382dc42bc00e828d388.nq.gz
    ├── 583bd0dfb206f2c81a60eea4bcc3a7a1f570fca3.nq.gz
    ├── 595b13947a34a7fd3ebff51c7d91a2f4a4b79d23.nq.gz
    ├── 5a0d9923e4fff2e61f775117712e9f08860a607d.nq.gz
    ├── 5a5356c0a4050bfb8dfb3ed04c887244d46aea84.nq.gz
    ├── 5ad3726e154404c41a053f36d7a566b8c16fcb71.nq.gz
    ├── 5b1ebe24239bd1fad2fda98a06bf859c9e05b688.nq.gz
    ├── 5b867b3123a0e0f3ef1cb22175fbf7a1c239a623.nq.gz
    ├── 5bc3dc0957c0be749ed7657974ebc01b34b4a4e1.nq.gz
    ├── 5c247fce92c40571e9eb8f5b46478b41885f2955.nq.gz
    ├── 5cfb82816d5d89ff29e83a7398c51c1f43d31816.nq.gz
    ├── 5d66d988102610f5c3f4ce358a1097fbd679a359.nq.gz
    ├── 5dfbc95fdde70caba6acff7c341ec35104c58dd0.nq.gz
    ├── 5e2cfd1c461bb27f43cf32e11a8721eacb71d147.nq.gz
    ├── 5f63a97b5dde1b741a68dc6a392acf3e2d93cfb4.nq.gz
    ├── 601732aabd3c30ab4bfe7173ad1b87ecdcb6ec22.nq.gz
    ├── 60cef03603c69f61d5fad786a34caa98347a074a.nq.gz
    ├── 61aca34b368e04cea72508fd6b0f40649b786de1.nq.gz
    ├── 61db12dc04aec15cbfe9cce30e8f2045cdad4aff.nq.gz
    ├── 6214fd7a34558ddaf7bcdc8f9fe37e05d5985740.nq.gz
    ├── 6272c1757f14a4570c924a9a15df0329d60b86f5.nq.gz
    ├── 62b4fab699ba48696f064d9ccef2f26d31536218.nq.gz
    ├── 63023ed42e6cd3435b9cfbca1ea3cc6b96e0867b.nq.gz
    ├── 635b3c9fdead2ba5439eaa6784f1f93c3f215ecf.nq.gz
    ├── 648bda805ab2c6c36719b51d09eca282cc3d30ce.nq.gz
    ├── 662677f6184c1753aabf670698eb38135cafa00a.nq.gz
    ├── 66d0118bce990f21063dc22828f4daba57225201.nq.gz
    ├── 675092181745d75eeadc06dc4fd0c93bb95e2128.nq.gz
    ├── 680901be90dec0afdbc1c2b0f728bd768cfa6cbd.nq.gz
    ├── 692e56712cd48bfe5523823e04a46ae40096f360.nq.gz
    ├── 697d7dc613e10a6cdd777228e833e8303ff13151.nq.gz
    ├── 6a19bd80a46d4bfa45e93fcfb7eb5952b19b016e.nq.gz
    ├── 6a60a7a8e6fc8c0f8c9db50dea5c1945c7c644f4.nq.gz
    ├── 6a6410086bd42da4acfa4f649a39a4dc51b4eb78.nq.gz
    ├── 6ab43f13df1ae6454a6c3e789956fae56d417b94.nq.gz
    ├── 6b567ee8c24986c47f9d9f8c9d2e749f619fe3bc.nq.gz
    ├── 6b8d9eb5f4f3fcbbcdc27c279483103b038c4d25.nq.gz
    ├── 6bb6305288411b8fb9b1a73e5800c47bd9d56f22.nq.gz
    ├── 6ceba66c54f318d5e14001667cb37b3c369960db.nq.gz
    ├── 6d40e83501c59c69f96c1e78832c026085cec43d.nq.gz
    ├── 6d730002f3bc7620c73fdb95d24da30913a5c72a.nq.gz
    ├── 6db50acfbe8426135194cb162d469711bccd5c31.nq.gz
    ├── 6e3362fa6cc7f9ccc4a6e7212cc516a2c8c18862.nq.gz
    ├── 6e51dc5464021042d4c6632005cb056b90f083c7.nq.gz
    ├── 6f754061466299434aa55f4eb15b43ed6d18f535.nq.gz
    ├── 706b90a03abf8f04a4c64d5960f6a90c89ab776a.nq.gz
    ├── 70c62f3bb800bb6f196dfcbb79e4c259829853d6.nq.gz
    ├── 70e55e30b7e9080f3e6dce86e94f58f26cf19318.nq.gz
    ├── 7123372f16d3624205c10e30420937f8713ce713.nq.gz
    ├── 714fd7805fdb7b6346720ae6a45f2ef047ab54ad.nq.gz
    ├── 71ed6e3765be7c9c8d6f41ecd135d912a6bcbe5c.nq.gz
    ├── 71eff75dc10f2f20195e8a8ed0685c63627a494e.nq.gz
    └── 73f40c623527d7128dc520acc1406d544b5f0e2e.nq.gz

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

[timocov/dts-bundle-generator](https://github.com/timocov/dts-bundle-generator)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
