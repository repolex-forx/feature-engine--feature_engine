# Repolex Knowledge Graph of feature-engine/feature_engine

RDF knowledge graph data for [feature-engine/feature_engine](https://github.com/feature-engine/feature_engine), parsed by [repolex](https://repolex.ai).

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
rlex download feature-engine/feature_engine
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d866312874a66364c6dee3c247e69476b478395c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d866312874a66364c6dee3c247e69476b478395c
│           └── chunk-001.nq.gz
└── blob
    ├── 012cf7b233cc78fe4b8732a2f0039e735086259e.nq.gz
    ├── 01aeb2bb85c1757e9d5b921ee55c8ccbebb505d3.nq.gz
    ├── 01e7edc1d5aa8f6280a2292d61ba58514816c95c.nq.gz
    ├── 022c051c3c62df9a7947fefcee808e733fcfe821.nq.gz
    ├── 028527e0b63b286b9586425dc572356b456aac7b.nq.gz
    ├── 02901671e45586dcd93a35d78da6206d1712efb3.nq.gz
    ├── 02d353676c1bb89476935f0a0b79b2905c2dcf3a.nq.gz
    ├── 03a34f3d5d90cd312e0b5471ec085c84b1de428b.nq.gz
    ├── 049b768e3911b437adffed9ef81ff55588cdbb99.nq.gz
    ├── 055fac7884f8d35ba596647661c2071de171013c.nq.gz
    ├── 05d5807cc35c54951440366f6f5eb3f5490ca6d0.nq.gz
    ├── 063339971aaf4b14bde19e622a33cbff726a5e6f.nq.gz
    ├── 06f02cfe62d58026592b4ea953173fd0ead9716d.nq.gz
    ├── 077a5204921630c41190de1d2650508bd89fe68d.nq.gz
    ├── 07a52dcfc01fde81d6e01ded748fc468ed30398e.nq.gz
    ├── 0828e2d5775f58b28dded6144a9bae6515cad360.nq.gz
    ├── 086eef00f1144c1060d7ee895756a30b9e092f0b.nq.gz
    ├── 0acd558c168119910c5961258d92c1097f0ec995.nq.gz
    ├── 0cfa42e3ef7f646a8ff14c04c0b9e58ce880a87f.nq.gz
    ├── 0d24276774dac0a17bad5c53d2b1f35a1f03c083.nq.gz
    ├── 0d275cdbae09af1defa6c249b811f9f99f345ad3.nq.gz
    ├── 0db1bc2a3e46102a1374871bac25690fe0a94b0d.nq.gz
    ├── 0de8fa439d5ec3690213f2f5d6e1285b414a7165.nq.gz
    ├── 0e1689afc5ace04e959c784d2e2b955e6f9cc64d.nq.gz
    ├── 0f383c8ecbbdf0945fa4dd17a2d47185ac9e9dc9.nq.gz
    ├── 0f90f85afa233d44e196587f83ccac6c79d8d36b.nq.gz
    ├── 0f9a33d14f871349e3bec8c651f0d1a38f0baa99.nq.gz
    ├── 10417f1d0a8071287ebe76b78947454613f8077b.nq.gz
    ├── 106d50277a1f563756a9ba7a6459970ea4cc58ee.nq.gz
    ├── 112262dd1d3e03acb1900bf5b29949e32921d091.nq.gz
    ├── 1125e3a0826a1beff0766824bc7b1d2244100371.nq.gz
    ├── 124bc96b69c5d897948fc0c9674afe7427437fab.nq.gz
    ├── 124efff479fe87bdc8db2091eaf6e442f8dccd62.nq.gz
    ├── 1264bece3e86c460e719857e9a71ed018678d949.nq.gz
    ├── 127b33befb12fc541335f073da63f6d7f55cd819.nq.gz
    ├── 1370300b94ab51823084b94beeccd94e02d40b06.nq.gz
    ├── 1409ece17438356c06311f5a4564c9db1d892033.nq.gz
    ├── 145aa6394cbf905fcbd828694f2fdc2d56a2fcd2.nq.gz
    ├── 14626b79cd1ec3ed3f943410f054128967fe3a65.nq.gz
    ├── 160e6f79583176fa65766a6228b035f3af3759f9.nq.gz
    ├── 17eb4e41d1937d4a74ee61cf57f711b685f05136.nq.gz
    ├── 1813d98d55dc64804c1ab438eed00f36a8b9cbc8.nq.gz
    ├── 182e8826b24911ee7729580f8e507b91a3056ab8.nq.gz
    ├── 198b6d5a5a7b122d8a66728e732a74b208d8396a.nq.gz
    ├── 199bb1d407909d159292ac6d753e0377e4f8c290.nq.gz
    ├── 19a10f9f1c918acd6e3adcdf5985b14a988895c1.nq.gz
    ├── 1a0420797d288dc36ccf8804695310078574566c.nq.gz
    ├── 1a2535c660d9795e03d284d8601f4af6ab98dfdc.nq.gz
    ├── 1bdc8a066146aa7fbd5365c17b6234a337b48ab0.nq.gz
    ├── 1c39a09c9f32d8aa431aa00d8979cfe93155b7a2.nq.gz
    ├── 1e4b71ccd82c745e1cfa00f857683220f898f9cb.nq.gz
    ├── 1e6e91628f469f0a0008aa6ec39f7a76708e1bb8.nq.gz
    ├── 1e89058da34cb04e8767b6153cb80d1f7c4af74a.nq.gz
    ├── 1eb667c4cf48ef7eb20375fd1eafc790ba8b5432.nq.gz
    ├── 2048b1dbb872a78e19746a025ae531c314ef0fcc.nq.gz
    ├── 204aabbe7067c41050e20247f6d61d48046679b5.nq.gz
    ├── 211c00fa0f3cf3804fbf6b8f66acc2295e9c2840.nq.gz
    ├── 22678544ceb9fa75f970c3e294d6bd95975f3988.nq.gz
    ├── 22fada8a888d5e996fedbc6fff88459ba064fadb.nq.gz
    ├── 2304ff1ba52190265dc8072148d708efcdca4125.nq.gz
    ├── 2382d47adb01518c5120c2bb125b0eb416d705f3.nq.gz
    ├── 24018b0cda357e686bb9ab3c62c26e997cb48ad5.nq.gz
    ├── 25ba6002c7262db4395321a93d75e41b62910fd8.nq.gz
    ├── 25fd20c40fd7d045850887e254df42db91b75f6e.nq.gz
    ├── 262bc5435e001bce03f9685f46389beffad78306.nq.gz
    ├── 26382b4eb73f96fac9a044768eb73d6eaf04b9a2.nq.gz
    ├── 26fa278757b41e237e78bcda84ebcfea8c73321e.nq.gz
    ├── 274232c959488093630d75d7cca968953d0f7ff4.nq.gz
    ├── 2893c9445ca7910a3703fbb7bdcc30a8202e6e1e.nq.gz
    ├── 294de9d9fe8e6f3c7a5a5ca306bf8314afa85295.nq.gz
    ├── 29e6ba8d7db1ac5bcd8bfbadfbfc1e82b27b9180.nq.gz
    ├── 2a11e0d3e62d89d5a30a62ea2fd87d6ce2a0fb9b.nq.gz
    ├── 2a27499b185cf6801ded6bc8034d3d75296847ac.nq.gz
    ├── 2a33c84e967714806b0387a4600e534a8267b04d.nq.gz
    ├── 2af8b679ed8b0e82a3baa9cbedb3aa45b7c352bc.nq.gz
    ├── 2be904612340a17e52205e69c89023501c90aab3.nq.gz
    ├── 2c2e935ca1b50ba0899cd972a9dcf86ba6bbf51b.nq.gz
    ├── 2c3cd08f83af6c72a58ebb859347a1d2e1791a0b.nq.gz
    ├── 2c6e65fb49fc39b1b1db7337dcb1c84491f5ce29.nq.gz
    ├── 2cc9634703fe59a58968287bebfb68748025a6eb.nq.gz
    ├── 2cd4a00a3c35550479f8b329aa8a9b3a3be780c1.nq.gz
    ├── 2da91ba526bce81b0b167864101a86854feac087.nq.gz
    ├── 2e9941b0caef0e9647f30731c7c120a468661aec.nq.gz
    ├── 2f7a5471cf174298e1e60816a759e59c64a94dfb.nq.gz
    ├── 2f914df86110628f903289d12e6655950088b658.nq.gz
    ├── 2fcf1c6d005f3836a3ac8223741894a34180e3ab.nq.gz
    ├── 308f0442f39123e348b3c311d3228b47c99463fa.nq.gz
    ├── 30952f06c4f4a35a4028443947f848ca04947575.nq.gz
    ├── 314684a444023f2d6e90ad654bde0ff521f2344a.nq.gz
    ├── 31babf23392273170dfb3f6145c1112d401b4737.nq.gz
    ├── 31ed76c8e142eb948fa5deb48369a700b9d8d62a.nq.gz
    ├── 325367769a7f99b562ab53b4dd254c31804f2695.nq.gz
    ├── 32c5f0c5874f1b344bd170f6dbf5a508bd7545a3.nq.gz
    ├── 33209e0b9937d443a3f1c651899af836419e9b89.nq.gz
    ├── 333a8191811aba600222ec04eabb77156e084200.nq.gz
    ├── 337f9840abbdd4e34643665de0c399149e8c3ede.nq.gz
    ├── 351d4f0f1072b18ef79c3a23a2f6aee8ffaf3ffe.nq.gz
    ├── 353c315a053a8e0cf951a1b312dab244be042b67.nq.gz
    ├── 35427f2605c970874195f98f226ac0f52e21a36a.nq.gz
    ├── 35f7416e2e7c1f59a549f38650ee7cbbb6ff35cc.nq.gz
    ├── 3618933b3258ef1a9a5045c70fde7eaf04503268.nq.gz
    ├── 36bb9627dcbbb1f914af24f1750e72e7fa66e1a2.nq.gz
    ├── 36dd4486207cb55710cf845dd2281af6c91ff170.nq.gz
    ├── 386d3b61efb94d021a0c21722dd23c5ba2cee613.nq.gz
    ├── 38d04868704561c6053ebd67dbfd1a1018fe9953.nq.gz
    ├── 3984d2c456b67231acdce2aba0f80a1875e2f0ec.nq.gz
    ├── 3a7b5cd5d1e7cdc057d6c1bfe383c0479d9bd3b6.nq.gz
    ├── 3a91a61bd5abcd1ed87a63892a87d5515c5c54b1.nq.gz
    ├── 3ba72acd90c6663484988d8d0f46a97bfb9a4b8d.nq.gz
    ├── 3d306033b081fc85465829424cb7318a7faf06f5.nq.gz
    ├── 3d4766fe985519e450c305ebac676d025fa43608.nq.gz
    ├── 3d66fadc0a4e1d6855800ec72ad54c3c31886b0f.nq.gz
    ├── 3d75543ff5021cb725aebd7037412df15a8bb03f.nq.gz
    ├── 3d8714a673720b9d8382f923d2d2003878ae5fa3.nq.gz
    ├── 3ee3222fb17135293cbf325d4079c41cba26f0dc.nq.gz
    ├── 3f0882676255b9823f330d44e534c55e979dee1f.nq.gz
    ├── 3f790da78593d1c81640b23d877559348846fb4d.nq.gz
    ├── 3fbfaec27a0fa287bbe7994fe7aa8650de5cf017.nq.gz
    ├── 40b9b7f3b16b6e58f8dc07bdd6857359a5d370ec.nq.gz
    ├── 41cb4814552260c92e02fa8bddf86119d0759208.nq.gz
    ├── 42b773627d61ce5a0fd7ef4256e119c1dcee032f.nq.gz
    ├── 4332b3de7cc4847334d2372cf7be6d97ade2f3ad.nq.gz
    ├── 435b18e3508a821873195d9d9bef250bb25b9cb4.nq.gz
    ├── 44a84bb0a037aaecb6b1c419f49c9312bb478bb8.nq.gz
    ├── 455a709fbb79d266ea4ff85050e948137c1f1b86.nq.gz
    ├── 462026df390971cdf542a5084b2387ee3c3c1295.nq.gz
    ├── 465e008fc215d46896909ea28bb484099026a67c.nq.gz
    ├── 46d27c24e123700f680b0a3487e9b85dacafef39.nq.gz
    ├── 4934e4b57bd2ba980e3dfb38eecce9a3105aecab.nq.gz
    ├── 49e99069eb4754b52ef96274c659332c6a3b3dea.nq.gz
    ├── 4a1598d4938a644d9929ea0db0a334257e35d01e.nq.gz
    ├── 4a3ef6a2fa32704202f68884e4246540f84c848a.nq.gz
    ├── 4a7f0f8d7c788caace7e1e689c5b7e5345898cf7.nq.gz
    ├── 4e262ecef1496954dec38905cea9f28cd06f2e50.nq.gz
    ├── 4e854d04e4feb3aec04be7b76e613b215d868632.nq.gz
    ├── 4e85515ec0a4bfad82de33c15ecb1bc283fc111f.nq.gz
    ├── 4e8a93e8c6ebc5cf6789d92234dbaffedb68c504.nq.gz
    ├── 4eb2530b713e811e0b8abdee474c54025859f884.nq.gz
    ├── 4f4ab71cd84c85aacbdcd86a522f68805220c421.nq.gz
    ├── 4f4b7f631aba2f2eeede2d030ab99cda685ecc9b.nq.gz
    ├── 4f640c73f44cb7d74e34e7a3d92919784e1b91e9.nq.gz
    ├── 4f7f48395e2c9acf2ccf98e8b2add5298f2f4609.nq.gz
    ├── 5016d1aa98a2cbccac56c7bfa0bb536883c064d3.nq.gz
    ├── 521f6e31eb055a84b6145c316f00943b2ecc578d.nq.gz
    ├── 52d5feffb66217e462cd34fb652d363c72b4f58d.nq.gz
    ├── 5339fbe058ebbe9432b2732d35cbe6c379818e96.nq.gz
    ├── 5340d88b19a4cf6c241f66cefb95267f0047e02b.nq.gz
    ├── 54257ade7aeb60405c062ce966e9695bc5894680.nq.gz
    ├── 54667f8d34711aebd48135eac7bde5233d3f18cd.nq.gz
    ├── 54cc5bfc0b973dbbf822939205a5317e7d0f62cc.nq.gz
    ├── 557a462ba73d0bd8b60154a02498f32e04e5242c.nq.gz
    ├── 558b3baa4873f9b124ac369b29f96dbfa033e0c6.nq.gz
    ├── 5611aa204b520d9521fd494311dac33437005033.nq.gz
    ├── 56290328b9666bc37f9b8bffc27ece434c674bf0.nq.gz
    ├── 568059e978ee29cda41aba19626fa317fd3021b9.nq.gz
    ├── 56f5a04367eee0aa42c9afa0fddcb555b35c659a.nq.gz
    ├── 570ca242f3c0adcba1bad46b011cb7a51401710b.nq.gz
    ├── 58d489122724edb2e2bb1bf5f5fa3d1c769ba966.nq.gz
    ├── 591f1d3e21fb2ec297f6de4a2a90436b8ddfad6b.nq.gz
    ├── 59b26567a9e44d55bf0b24bedbc8569d071ed330.nq.gz
    ├── 5a1d8be4743b3fab4de291671b9da6e8fdc2a5c5.nq.gz
    ├── 5aaa18c2648ebea3dfeb81f04e3530f8b5e2322a.nq.gz
    ├── 5b1971c1c30cec23bcf5319fcad22088ef4d940d.nq.gz
    ├── 5b2957bff356476c3fe812e1db5e42edae3e1a18.nq.gz
    ├── 5bc1df88fe226c54f4d71e46e4ce834b631a1885.nq.gz
    ├── 5be7a19cbcb3cca61e6b0194ca4d0b97b33a1a11.nq.gz
    ├── 5cba357b8ac2e499645bc040a62fceb3d45fa99a.nq.gz
    ├── 5d072eb566deaa41c91e02f4b01fcf1c6e8675e9.nq.gz
    ├── 5e5deb45944d87c0fe50685e485e1bac15d66857.nq.gz
    ├── 5e98b6dbd0b4f6d794c6fcc83d16abee43f9aa20.nq.gz
    ├── 5eca8b60d8e19d56f98ae93026b640d7735857ff.nq.gz
    ├── 5f1e65dbb2f46bde0a745ec24863a39fc01ba3db.nq.gz
    ├── 6088520da6c4ad6a429e50ea44304471b978cae5.nq.gz
    ├── 61043945dc1429fab21020788bce84ba7ad95eb5.nq.gz
    ├── 6208657350b521134674cab68c71a164e8bb6fee.nq.gz
    ├── 6237d6a645f72f4d523054f4c7a5440e344985a0.nq.gz
    ├── 6264fcdb4c8b6560fe53232435af839909b638fd.nq.gz
    ├── 62b2da7d2a9bad4b28ce3dfa330c9ec9115fe25d.nq.gz
    ├── 66097f7171f8ed6deb37b65e281471c0f6ac7d61.nq.gz
    ├── 661c0c096735f7e5c2d82e7878a3bb28b7dac924.nq.gz
    ├── 662657692659965cb09e2cb45a4175cc6c273db0.nq.gz
    ├── 665c7d348300accf24bf39bba9589c6248264c86.nq.gz
    ├── 6694fcb6987e01a81690fd35ccf15b63489de2b6.nq.gz
    ├── 6726b33f99ab09caeedd0fdb948217876ac557a1.nq.gz
    ├── 6729b25139c3b121131a19eaac2baa8a82f862d2.nq.gz
    ├── 67c7c9caaec0b0667bf28fe40e6139f5640153d6.nq.gz
    ├── 68ecad828977cd226280c4f393bb9d5f4bcd4e20.nq.gz
    ├── 698d4e8351bf74a47d7670072eb4f6cc7bdc80fe.nq.gz
    ├── 69d93febb5278691bafae528b204ccb20a81a5c5.nq.gz
    ├── 6a3da451fe40b3b1220e429bee67d33e0d3ea56b.nq.gz
    ├── 6a4b56c2d97fa8d601c527dcab268d5e1137bc06.nq.gz
    ├── 6ae29384d10bd79c0aafb560a3012e59cccb2b8f.nq.gz
    ├── 6b79af5251aa22415a1834f1618e68e1edf6a614.nq.gz
    ├── 6bfcd24b1dc0965b4afc54dc1f298df86a8b4795.nq.gz
    ├── 6c61d05d37f1e5fe4c1fd7214a7ae1b752ffe8e7.nq.gz
    ├── 6db782ef3ec7f6bfd45a3a16487a277e20c3f1a5.nq.gz
    ├── 6e64e3533266462d8ebba68afc4c76f00a442b8f.nq.gz
    └── 6e9826428f9dc1725257bcd5c0fda4ba1dfe4148.nq.gz

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

[feature-engine/feature_engine](https://github.com/feature-engine/feature_engine)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
