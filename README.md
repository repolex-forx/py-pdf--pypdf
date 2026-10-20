# Repolex Knowledge Graph of py-pdf/pypdf

RDF knowledge graph data for [py-pdf/pypdf](https://github.com/py-pdf/pypdf), parsed by [repolex](https://repolex.ai).

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
rlex download py-pdf/pypdf
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 885e7430cdf96b55b4ebaf2515e6efe46c396834
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 885e7430cdf96b55b4ebaf2515e6efe46c396834
│           └── chunk-001.nq.gz
└── blob
    ├── 01aa54ff9b254a2e9438662e9101bdd303ce16a4.nq.gz
    ├── 0516d6f33212d829b53316c52078942099613539.nq.gz
    ├── 05284f39bea445820e1c4ac4502e99ee1a8742d9.nq.gz
    ├── 054c32ac38f80359b1e2fddc41296f2540e1786b.nq.gz
    ├── 0599e34e561332af122f502e686313d51d2543db.nq.gz
    ├── 064dd7969bcea476627bb3e1c1806237bf7d0c03.nq.gz
    ├── 07a7fbbcb0acdf9e860d0c2e99aa7de16beef809.nq.gz
    ├── 07a973997233a2d75fcbf38b1d6230df081ce9d2.nq.gz
    ├── 09f9aa3bb8d0f4efe251cf3c80426c4118a42eca.nq.gz
    ├── 0bef0b80ee582cfeb0fa63d5271ca4c28a60df9c.nq.gz
    ├── 0c67763463aa3f9a56ae3d324e873abf0fb0859d.nq.gz
    ├── 0cef4743a7cfed59d24e635a0f792d1de26d2c75.nq.gz
    ├── 0d218c890e76af93a705995b8afad9cb05c5b327.nq.gz
    ├── 1089a70ebd9c377a954401be53986f16d425d8b6.nq.gz
    ├── 10cd5293ecb9f5712be523c026c4487911e79517.nq.gz
    ├── 116be729106e956d33d59891e0a1cc48babb7f4a.nq.gz
    ├── 121c61ed7a5c2922738afa8101e832e47f72f642.nq.gz
    ├── 12730fc2aa055ba008d38bb41863760a97c0b09e.nq.gz
    ├── 13594b795a62ebdf358c622389bdb98ab3148da7.nq.gz
    ├── 1631724355fe2a20f67af95ecf93d00d16bc1e75.nq.gz
    ├── 18a51edbfca98b55f1a2c48a64adcaf2fd4e37d8.nq.gz
    ├── 19a878b82969cf9859c628c7013f445067344840.nq.gz
    ├── 19c1140115fd109506e350bbf8213fb0e6db4dfc.nq.gz
    ├── 1a1d56904d3ae48bf3cb7b49968b9d72ee86abf1.nq.gz
    ├── 1a8f5684305c7e850c0e84bba9adb1180eff7e7f.nq.gz
    ├── 1b5a4409b9f027752abef10f4cd520eeed7c344a.nq.gz
    ├── 1c2f69ed3a6a83970cfb98be9e9984eddf17ec76.nq.gz
    ├── 1cf7d6d6d11dea1b18aa4541db029323b3e66dc0.nq.gz
    ├── 1d70b42d4a368cbfaffceda2803e8fa1ad078df1.nq.gz
    ├── 1f0dc7ff13bbb147d526f9fdec469c3705584912.nq.gz
    ├── 1f60aabac45e7b47c3c1f78487a8b98aa5b25b74.nq.gz
    ├── 1fb4924c227eee4cbdab324408c8a654dcb9375a.nq.gz
    ├── 206a43bf7536f79bca3638520be1fd09c5c0fd3a.nq.gz
    ├── 21236411754e54f2e0843a252458019d9df6a800.nq.gz
    ├── 21d299b81ec457885fcf5b820ef9beb1c45cfcb0.nq.gz
    ├── 22917d5099bbcf391fc18918553c502f72657913.nq.gz
    ├── 22c51e57a128157bc2aa15d4a9b8d62382b5d70a.nq.gz
    ├── 234f39b75b8a2dc7f5ad91a8c4a9f758f777e9ae.nq.gz
    ├── 245137eedee699a05928170e99401a8d4668850e.nq.gz
    ├── 2734f5f820e7cdb240800386d7bda2ac7996d4da.nq.gz
    ├── 27467115390db32139fb7f792a2b274a11a66674.nq.gz
    ├── 2808e8a6c4dbcb4bc58b43b04d27dfa5b6d4a509.nq.gz
    ├── 28777cef3cc4cf9008c3f15184e8714d6675a4c0.nq.gz
    ├── 2a0616ea04e73aa5377d4e179b741bbab9009795.nq.gz
    ├── 2a188c0ef2cb2e36970574f15f03116a19e1bd60.nq.gz
    ├── 2a6460b3a32bba669c7db267e369152dcd3178df.nq.gz
    ├── 2b0b250e30db71568661daa762135f6df22283df.nq.gz
    ├── 2b7d3275fd6c0fce04de8df7a316087350a02373.nq.gz
    ├── 2d1133ace33c988a47ac24ec926ccaad4ea6221a.nq.gz
    ├── 2dcc0958976595944f37151234f81b4883e4df8f.nq.gz
    ├── 2ed8bfab491e7a05e870f78c7bbeaf8a6a607586.nq.gz
    ├── 2ef0873c8878c41ac4be8bb50344c63cd266279c.nq.gz
    ├── 2fe8710121143899fabbc953071ed33b2d979754.nq.gz
    ├── 3026e7acfa36b8c7b390843a56f5be75e38b496c.nq.gz
    ├── 304546c86e338ba8714b93139081f3f9dbc76377.nq.gz
    ├── 306357a59c4d9a0fd846bb52e5b6774d82c6ae51.nq.gz
    ├── 30d6046c6bc5a551e8be9fedb56413f21ab9108f.nq.gz
    ├── 30d81bb1873b4c5d48ea736b05bd3a0481bde1ff.nq.gz
    ├── 325c41b8f4678d2badd8e43e93245cfb684e65ba.nq.gz
    ├── 32bb24529f92346af26219baed295b7488b77534.nq.gz
    ├── 332e23a0adc03ba2d87183491a9746e729b14749.nq.gz
    ├── 34b4802efa3363a676ad2f43e6b52ad37243317c.nq.gz
    ├── 365981ffba447f741d2856b6088c2bc8ffd7b469.nq.gz
    ├── 37a538c178a311a0ecb9a305be7cba3545c4bca3.nq.gz
    ├── 382c266b75d12017679b74253dc20a8c10763973.nq.gz
    ├── 39edbf5a4376a9ad5269dcfad67958500e713aa4.nq.gz
    ├── 3a67b4aa95a07483d6567e80cb6eadc5ed55f132.nq.gz
    ├── 3ab490ca7c57b9c3f95dfd1ac206d3ae41c28e0e.nq.gz
    ├── 3ac82460f74f2bd134be8de3319ddf6aa8f3cbdb.nq.gz
    ├── 3b36c563a81464e0e96965f1a160313e2fe717cf.nq.gz
    ├── 3bfd3e56b27ef43e0a8c1883b1220965a2f9d04a.nq.gz
    ├── 3dd64d0cfde30539499f224ddd68f7cb5c206d7b.nq.gz
    ├── 3e34c6eedfe3398050a67932977a99c566b716dc.nq.gz
    ├── 3e6e4fc4d2a800fe8aa210cdfccb16328d05cc05.nq.gz
    ├── 3f7066dd8334800d251ecf985677e7637cd44306.nq.gz
    ├── 40315a9aa07baf38980c40e6204328eb28729f72.nq.gz
    ├── 40f8e5a4f86e2dd8f0359c873d1a722ae66b1bfd.nq.gz
    ├── 414f04895b8f48a0b12041b45b4edfcc1cdbaf65.nq.gz
    ├── 427ea46f5c26d29df7f6e8cec7af608e9a47d2f4.nq.gz
    ├── 432a5038799c87450818b1e3099d9aadba5ce546.nq.gz
    ├── 44397bf9b3e222084c61296ede4f9aecb6202e84.nq.gz
    ├── 449818daa717c70075024079a0ed265ac91b2898.nq.gz
    ├── 44ed1dab5cacdfc7dbc9c07605e164e757a927b5.nq.gz
    ├── 45c0604e94e1b1478512f43517c70e0565fab332.nq.gz
    ├── 45cdc3747cd4a9a6efe7bf2f3e93d4d6b3c7d93f.nq.gz
    ├── 46aabc0fc4aa9125f7bea9a67d748712d4663ba1.nq.gz
    ├── 472ac2036a6e2e2ff6394290e6684436b89550e4.nq.gz
    ├── 4890882cf2c5e95e6ccc3ce900fba85c22f0a1b4.nq.gz
    ├── 49b7f2d9e0efc3b57ff21e8b5c3271e68b34b1aa.nq.gz
    ├── 4be4b2f336662b500fa417b2688c584ebf1f95b0.nq.gz
    ├── 4bef01421086072be94b724d06455754235a8ef6.nq.gz
    ├── 4d6f04c50aaf2d4fc50fc90f9df482900bc98d0c.nq.gz
    ├── 4d901e1f80a778353ea6f703e1cecc86d2720951.nq.gz
    ├── 4d9fcdd4a8beeb700d1c543fbf20a676e39ad2b6.nq.gz
    ├── 4dbe682330a137dc41e89daa7498245918c745b5.nq.gz
    ├── 4ee981d2c796f4f18d9a89f082c1554794f8630e.nq.gz
    ├── 51997a11526ecae75a30b0e138b4386bf023e601.nq.gz
    ├── 5295d2a86bdb3b67c430bcc5760fc828216f89f8.nq.gz
    ├── 5303731021f7a7834ad5419745814e26a5f85da1.nq.gz
    ├── 543ddeb43435a9ed774c8a92eb181a88870bf3ab.nq.gz
    ├── 552b3abf6543ca4a2848b54736b20813e5dc62cc.nq.gz
    ├── 56ba399e494dae3cce7c7a29ebe88f8eed8b4521.nq.gz
    ├── 573701897d52b00d25c1f2c097828a0d47b6fa45.nq.gz
    ├── 57f199aebb10ace6182d56560bcf09c4b84bf4c2.nq.gz
    ├── 58e9be4a044faded788c333d44adbef4db5a8121.nq.gz
    ├── 596ff270ce6b2d06d8e934069b9cf3da5e81e1a0.nq.gz
    ├── 5b11c69e3f966dc8cc4c290219cec4f98e61132e.nq.gz
    ├── 5b7c362e56de1c153f9ae441b1d4dc3c0e4d8e76.nq.gz
    ├── 5b8e74f744e7b9b77371c18e3d46b0a458be7dc2.nq.gz
    ├── 5b901bbbc863742610a6fbe54ea80210fb2d1e81.nq.gz
    ├── 5bce717c20e677d354ccf18f037bd0043f0b43db.nq.gz
    ├── 5bd26bd603f7f28853338cadd99b4fca9e307b10.nq.gz
    ├── 5ca78bddd50468ec5666fe64c457baaee9fbdc99.nq.gz
    ├── 5cb5ce556c204947c4f42fdc90ee367324f3f241.nq.gz
    ├── 5d06d9191e5f8fb14e02f04c3ac7b4f1e527ccc8.nq.gz
    ├── 5f48c0651ad0e3154b7b5d1e2e0b6317933e6163.nq.gz
    ├── 5fa12c1ffee915a10478c04384628ed15913e3cd.nq.gz
    ├── 5fb3530d04376f662e83fd64b00b7e7c6b2ad94a.nq.gz
    ├── 5fdc2c6e1f2df8750e5abff04705c12c5540e893.nq.gz
    ├── 608056d8f23060abfbb56e50367443049dd318db.nq.gz
    ├── 608ce2b6b646b5226c49c96bcb90f6df1f6474c6.nq.gz
    ├── 60f74763b053b7f842e1c7a9e4314fca15ada12c.nq.gz
    ├── 61262f7d4b8b69dca444c010f4735f6260f8b66d.nq.gz
    ├── 614606a9425441bac403123e3a96435786f23561.nq.gz
    ├── 62045a5205d1056fcb8d0129f0461a9f7e22dbbb.nq.gz
    ├── 630c569f805d1459753b15f07f0ae067a8654358.nq.gz
    ├── 632fe14417236574d8a0d998ef612b31de9cc2f0.nq.gz
    ├── 63b9423245a9a56872c6bf3c0c156123bcee080e.nq.gz
    ├── 6441a1c884d204c7b9c3ce294ee3810da7833e88.nq.gz
    ├── 6505b2984fd92abf3e2599865320c42b9b98a457.nq.gz
    ├── 654c654df20197e819b0c9bd10e0969ffedb4fb2.nq.gz
    ├── 6717e1147d29dd4cacbf47285eaa9f583e389454.nq.gz
    ├── 69aea5ec025d3ee9d213bad7ad961fcfb8fbfd6f.nq.gz
    ├── 6a2de1ff749509cbc3361a946440d6c8e237f0bd.nq.gz
    ├── 6ad3383ec13f5aabcb51ca3df9a48fef4264f45c.nq.gz
    ├── 6b548030524afad83a6f50c8524b1114776b09f1.nq.gz
    ├── 6d000ffe33f78889adc9b9f60191863360e6a810.nq.gz
    ├── 6d95b07114ad1eae41b8351ea687cc2d410caf33.nq.gz
    ├── 6ecf159adfcf5072673c500429cbdb5529969516.nq.gz
    ├── 6f4895f9cfdd56887654b4b468c01f19fadad318.nq.gz
    ├── 6f4d7c6fc4f1619632d6d9cfa5c5a53d876b2b14.nq.gz
    ├── 6fc353a969744ffe221da12f62c8bd3429bf698a.nq.gz
    ├── 709547468ebef27478491a3f1a22741ce2dcb548.nq.gz
    ├── 70b18eb6c876d118177ea876a79c770a6f229b81.nq.gz
    ├── 73844689914f071fef1d80728d5b2007ed2cc035.nq.gz
    ├── 73f9ebf7601798b54f0d35dfc82305c57e8f44b4.nq.gz
    ├── 7443c2fa80b142b60b0ceea4ec2e6ba24f9b3f97.nq.gz
    ├── 74b16353d768a49fdc6904ab2736ed2b01c88dad.nq.gz
    ├── 7513c9e69355b5f4d982a8b2d4541fa59d69a7ae.nq.gz
    ├── 75c2c62380c08f8b1cf92ccbaa907efe6912642e.nq.gz
    ├── 7641b4d54a5cbb58de44b9b0f9f669ccddb4f868.nq.gz
    ├── 76cc762d033d0cbf193f4b9eca8715b87e7b8619.nq.gz
    ├── 7731b18682b898a4f5b312d69e07df7df3494100.nq.gz
    ├── 774882c779cd94d1169317ce2f2a99cc1a031d04.nq.gz
    ├── 77706ae77dc43dbd51499be50ab9ec54c5055efa.nq.gz
    ├── 780e81841f1617246461fe16a7e4a87d42cf1a37.nq.gz
    ├── 78445ff7c8cd4a31036fcc6880c1f2392cceccd1.nq.gz
    ├── 786763fc58e2437d4480b7d076e4b97e6b32f2c5.nq.gz
    ├── 787afcfbaa55ec043169cc81cfddc36ba46e503c.nq.gz
    ├── 78aed06eb3f5ecba182bc216091a6662c1266e95.nq.gz
    ├── 78c579e56a0f69754a7a482b9d7bd4248d55a1cf.nq.gz
    ├── 7a5ce098382f365cfecf252ea41b5c0ab68d2586.nq.gz
    ├── 7af475679bbe993d4011fe599c223928d30a2a1d.nq.gz
    ├── 7b00455df16bcbe7a97ace9a05c0ce4c0a015402.nq.gz
    ├── 7b22a0c26fd8ed0898a2554e94f9121a317e9ee8.nq.gz
    ├── 7e2dfaada61ba17a432f14d9f5d52c621e88718f.nq.gz
    ├── 7e33bce26a533574050b42ab5899cbf70170ea76.nq.gz
    ├── 7ef1cf05905d98092c5b26e137a71fe2ff8a2894.nq.gz
    ├── 7ef4b5ab01903e6d3355686f5f3173caa14b5137.nq.gz
    ├── 7f0bd5cba61dc53c30b03853ce42e5ada61b0104.nq.gz
    ├── 7f7d8dd4e53f9172ac9c467a3ec866a6625ebaa4.nq.gz
    ├── 8071613a04ca1a60b18bce0923288c299fa528d3.nq.gz
    ├── 80f4a61d67ccabd6e0d02c02159e161f9d9ec922.nq.gz
    ├── 81841c4d6da4beaffc89b90d1b23a032c58dea27.nq.gz
    ├── 82609bb5613d281a39b4ffdc4dfd191bef825f11.nq.gz
    ├── 8270c1e448966fc81c6b5116baabe1fb57f786b7.nq.gz
    ├── 82d2ad28c0f6f3241e864add9e1a9bdad4179402.nq.gz
    ├── 837c97832fb845a82c47c68aff015725d3b69d12.nq.gz
    ├── 849538999085a292bb02ee40266e2a243fa59232.nq.gz
    ├── 84b90f799b1b20c75afbb4707de158d509145a27.nq.gz
    ├── 85d2371ef3bc3c08a5fdd8fefd3e782a8b8f971b.nq.gz
    ├── 87893f077acf26a7764fe83f06fbfe40dd4cf909.nq.gz
    ├── 87abef11ab20e9059e0d16316432cd45e007532f.nq.gz
    ├── 87c3410a695ba97a8455f0a103520bca049bd8ac.nq.gz
    ├── 888ff7fe19b464454a15155edbae0fec833ae57b.nq.gz
    ├── 8a470b00af20f6f5b299a80eceb09bd0dd776987.nq.gz
    ├── 8bd720622922ea62941c34f4cfae03547e803358.nq.gz
    ├── 8bf8bdf9dd00fac5dcf7626c13dc9fc1e3c4a5df.nq.gz
    ├── 8c48601d0fe1c335035fd7861b9348108264dfd7.nq.gz
    ├── 8c68c358b082d728e25a305c8ca44f611722bba6.nq.gz
    ├── 8cd3daee0dfa186daa32f8fa16515f4cc50e04f3.nq.gz
    ├── 8d84d4eaefbf2930f7a55f0588045a71ce03ae75.nq.gz
    ├── 8d86451cf3fc0f3e47792187db3a0ca2883cddb2.nq.gz
    ├── 8f9afff9e0329f2e5e609e7840bc9def9d52f564.nq.gz
    ├── 8fec6e13a279b9de013e41c91890d91873fbf1da.nq.gz
    ├── 910a2682e2f08ff84803902811389f063625771a.nq.gz
    ├── 949798aeb4fe409b945f63493b90d056fab444da.nq.gz
    └── 95e0c1695bedb11b91c6d579e28b2d95b9a91447.nq.gz

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

[py-pdf/pypdf](https://github.com/py-pdf/pypdf)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
