# Repolex Knowledge Graph of plotly/dash-recipes

RDF knowledge graph data for [plotly/dash-recipes](https://github.com/plotly/dash-recipes), parsed by [repolex](https://repolex.ai).

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
rlex download plotly/dash-recipes
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 707c225a15f6903bb0079b986e3df0516504d38e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 707c225a15f6903bb0079b986e3df0516504d38e
│           └── chunk-001.nq.gz
└── blob
    ├── 005cae7f45e6d3d2228c48521249eb3c9b4baeec.nq.gz
    ├── 0073146000b0815992909c6926241d4f599b2721.nq.gz
    ├── 00804503ddd8deab579890deddb601e042cadf4e.nq.gz
    ├── 02b2210ffc65a64bb7614017e204cfe314de4197.nq.gz
    ├── 02d2f6c0c63254e5e1b1db7b7b36838910737a9d.nq.gz
    ├── 04364a6dcccacd4265cd27724c68174fa1e8e937.nq.gz
    ├── 0438c953e670572bbd99c475abab8162c9217d0e.nq.gz
    ├── 059ed5850b09058b2e1d821737ace2a599966d0e.nq.gz
    ├── 05c2a1b3abdd8ecacc1c6b64e9afe3fdbc0973a4.nq.gz
    ├── 06216836c53818fc900162714c848e50e806abae.nq.gz
    ├── 0678fa76e467942a297cb6f1ce57e14bfd207d70.nq.gz
    ├── 06eafffd869fbe5d0794f282785716aa704f439e.nq.gz
    ├── 08d9ebb448c6ff97a726b2b68fa4bfb79d39a2d6.nq.gz
    ├── 0a01b997f9434dff056c5c882506909633ea9f20.nq.gz
    ├── 0a1b7f277aa4e44746bd768199ea072f16ed6cbc.nq.gz
    ├── 0a42551be6573bb8d8ab7fa262f3b2245c8489d4.nq.gz
    ├── 0ac2d84e904db7dd954f72721a7c3f05a5c50ebf.nq.gz
    ├── 0b1d8efc586891464ecd5294625ffd04e5ff126e.nq.gz
    ├── 0b8c2d845e73319b6174359915b7251a5ee25af6.nq.gz
    ├── 0c6519fa36df20642fb6a925886a6d7592e15c89.nq.gz
    ├── 0ca4aa3ab45a19f4048a945efb6b6f8116a241e2.nq.gz
    ├── 0caec2d77de97c659e38fe8f1b065a797da149ba.nq.gz
    ├── 0dcd4ebc5adf790e77d6fa8193bf6fc7a03d7706.nq.gz
    ├── 0e233e1dfedbc5c932112d3fcbe897c970b1e85f.nq.gz
    ├── 0ebdff127cf2527cf56a24dda5385163c4d55525.nq.gz
    ├── 0f39f161f8aded72029aed5955afd1e0903de1dc.nq.gz
    ├── 0f95ca9e69003096cb0d0a04b86015153ae1d0d3.nq.gz
    ├── 0fd68ee41c6bd9b5bf5a6b34975a82b938c2911d.nq.gz
    ├── 1006b48b5dec669527663ea953ecf421ebb9418d.nq.gz
    ├── 101b3b1a42a4e9413a3969bdc8128b4a9b857f35.nq.gz
    ├── 1174160d3219d904e338b7d6fd14beaf6bc5f477.nq.gz
    ├── 119cdb7a87fd9b8dce4c141f156e59a0dcd8eb19.nq.gz
    ├── 11aa905f3b39b9a2cade24c74b6c2f3d2571187a.nq.gz
    ├── 11dae5264185a4d97a72de1481b4154f7cdded90.nq.gz
    ├── 123ec78a3257634bdb9f308759f33d1209e42ae0.nq.gz
    ├── 157eb76862ba54e5d83ca67e72773204a23c6326.nq.gz
    ├── 15e18f94535255571c4e7f664c0bfbacd0f25213.nq.gz
    ├── 16dc497da7f6f7b860af8923078b35637eced8dc.nq.gz
    ├── 1847d739be1bff4fe949df4a239912996fe6747b.nq.gz
    ├── 186bc6c7db4672e59a9cef0042a3373fa8406026.nq.gz
    ├── 18726a9d6281caa297e48c850e76ce4a07d44290.nq.gz
    ├── 18900362e3d7852d93bf24368814699dd039232a.nq.gz
    ├── 1a7c83ddcbc16c0f339de5b992366db5b5d6b827.nq.gz
    ├── 1e53f10d4e0f0cfd4ddbfb046269248e535b0e72.nq.gz
    ├── 1fbc8cd146c82b07a2a6828a9698c2779bfbb67b.nq.gz
    ├── 1fdafc98e627bebc25f3354fd36b4f009497f4dd.nq.gz
    ├── 21cb6061d39820d328fd24644a0d130c2b3c0751.nq.gz
    ├── 21fa75041f6e80d1e0361d6c40de51ac1d074e85.nq.gz
    ├── 25f360a371b8d3cd9fa4876bdaf0c4bee839ca8c.nq.gz
    ├── 268286b63731e12af29422af5fef20a9ecbc64eb.nq.gz
    ├── 27b64c867f0bad0b0a99bc66c2502b5986602f22.nq.gz
    ├── 29ac171d768ea985c0a27293062eb6f47f457ba5.nq.gz
    ├── 2afecd86f32a4b1333f02f27fc8f334f3e06b45f.nq.gz
    ├── 2e029f3ef9188c11ca35f3d13c7dfc58a4c439e1.nq.gz
    ├── 2f51db7abadacbf20379e1ec347793b794939562.nq.gz
    ├── 30e192e49f04f12d6924bd823699d3cca7790934.nq.gz
    ├── 317d64d56fe089103a6892a5a473c5adf5323a59.nq.gz
    ├── 31c33083a413405f530bb30a6168f5c4bc18608f.nq.gz
    ├── 32207c2b5747971fa4388f857b99f9a3d5da55ab.nq.gz
    ├── 33dc840915a35484a4e85619bd4b9b9f1c288f72.nq.gz
    ├── 343492cdc56c511a9354df3b0953e8afcbd84187.nq.gz
    ├── 348ebd9491ed019f54af8f313ce8a4d782e0e609.nq.gz
    ├── 360448441dc25c6e1026c9b4dd81a157c0c47bc9.nq.gz
    ├── 36464d384187978697c8fc50852b313189630235.nq.gz
    ├── 377ffe9225322dec9839fbeb3536f71e7d162ab0.nq.gz
    ├── 38173a2c48d9a96f1495cc60185432c251d507d2.nq.gz
    ├── 3bbfdb9ff55ddadb20413cbac16b87b4e2df19f9.nq.gz
    ├── 3c2922cc219e0323043335f9612dc85624929add.nq.gz
    ├── 3dcf20dbf9a52cde60296e272c577b5e7e59ca15.nq.gz
    ├── 3dfc37dd9a0034b57bac3bd0370f510f36bff465.nq.gz
    ├── 3e38657fa9bd3cba04f2d8c52b7dc2f5a1fedbfb.nq.gz
    ├── 400c16008ca43144510cf3f5d8b561b0672c8458.nq.gz
    ├── 401a161a5b67d6209ce2b29a333b5921a2114ed9.nq.gz
    ├── 40340331aa8bc7fae78638adfc5b9ce397b1ebe4.nq.gz
    ├── 4063a7ea47821e690416dfe9a0eaaf13504d2cf0.nq.gz
    ├── 420cd7105b0560c407e65ac6240caca9fe354912.nq.gz
    ├── 4287560c8397fef477a5ca1b36ddf62fa04e7fb5.nq.gz
    ├── 452f91a8e16fcbcb7883080049422c40384da41a.nq.gz
    ├── 457f3766fe4be308ef9eb4e411c857c12dd8a5ed.nq.gz
    ├── 46d63c39dc5b605206fa1c942be1668ad0a57d9b.nq.gz
    ├── 4773b9bfa76ea0c0d309f44b42ebdac814e05e5f.nq.gz
    ├── 4853edfa7ef756a2f616152593e2e39ec7388d9c.nq.gz
    ├── 488b8dd399d0acb898738b4f9d690002d9e58b5d.nq.gz
    ├── 489e27eec95611b667dff50b9074e01d010b8ae8.nq.gz
    ├── 48aca710efb55e68c5bcaa214040a7b0c70a978d.nq.gz
    ├── 4a46e6fcfaaf0a48a680824ee9151fcec43e2594.nq.gz
    ├── 4aca76a7cf6f169a0807309e6e07bd2adc38883a.nq.gz
    ├── 4bbc8609283eb156db795edc3857715f0caa539b.nq.gz
    ├── 4bf0408f0ccafef07ba4639dc4d21692843bd974.nq.gz
    ├── 4c260fe60ab5d9370cc0a6de9942fe5b8d406648.nq.gz
    ├── 4c7f0d4100cfec06af7aa508c73b0d3dbac6d106.nq.gz
    ├── 4d886801e72a1d98b192c3f8ebd89cf79a9a16ad.nq.gz
    ├── 4dadc94f0dba118d86383292f23c67e22be95e8b.nq.gz
    ├── 4e2819972164d1505e2ace3109fedc741eaa06c5.nq.gz
    ├── 4e41f4fbe446e294b4a42e751ac768e32905f6d9.nq.gz
    ├── 4e545e662122ce58f8db3adb4b3f919446637a1a.nq.gz
    ├── 4fe368712435f8dd73b38eec06f596c090ff2471.nq.gz
    ├── 504255bc4ec62ef7af9af55230a02b7c8243214d.nq.gz
    ├── 50438ef0bd03ff33572bfff7f75c559d1361bb1f.nq.gz
    ├── 508695930c2b8b7af924be4865f436e405cac837.nq.gz
    ├── 50c3ba2b4b2e8e94359091cc1de3aea277a5f361.nq.gz
    ├── 512c5bf92e20021de42fa1aa791d6d62eb8fe20e.nq.gz
    ├── 515be4b13116199bb53a7b5a68bd2105271cb48c.nq.gz
    ├── 51dd3b9a8c669e945c232908f441adde9cceb431.nq.gz
    ├── 526d05fb31194198cea67ae5914cc4d6f69ce554.nq.gz
    ├── 52cfc349325aa478ea7076e3cc7e1bafc396e536.nq.gz
    ├── 5383cf1c7b932867516dabf5ca2fef30b212b7bf.nq.gz
    ├── 54ddae3430a7872a3213c0bb163f11274c1901bc.nq.gz
    ├── 552658d92930bd5d6acc32c5235b81a3c22da27f.nq.gz
    ├── 56b7ad230e4dccfe42838593799b9ae85587ce94.nq.gz
    ├── 57280031f1e9082f1ba2890a33bab974c3ee6d00.nq.gz
    ├── 57512c03b3d4adadaf7618e5315822769f892559.nq.gz
    ├── 57ca66428e4a60a40dba0d12f5f6b989c7ebf9fc.nq.gz
    ├── 57ee6a8891ba7b3c45711db4568479be5705ee3c.nq.gz
    ├── 589fc7a830dfe29f7c6fec183b39169e4dafa0fc.nq.gz
    ├── 5924b163f3732ec660da0a5379e6c6bb642d35fb.nq.gz
    ├── 5967addbf881dfee83132ca1a4010c2734c702c4.nq.gz
    ├── 5a534ded5ba32259f38599bdd230221f9b797cd2.nq.gz
    ├── 5a88047cda01377394f7bc24822d43f031747028.nq.gz
    ├── 5b12ada55934a17b71169bf3ec59f8415aeb38e9.nq.gz
    ├── 5c683fa748f1350d4b9fe8b639d2050283366061.nq.gz
    ├── 5c82f193b9d1bc5e7139066ba4ded1fcb554e33d.nq.gz
    ├── 5ccbd257a94dc9e21d1c5a499d0eb7cb709bc689.nq.gz
    ├── 5e12c737eb863c81017e420d3d83780705bf6cc2.nq.gz
    ├── 5ea52dfb5ba27b2921af87fba410076d6690adb6.nq.gz
    ├── 5ef01cae1f1392bf7ae6975ff854c42655b43988.nq.gz
    ├── 5efdb920d8c4875bdd85ab8a253e78c9690cbc42.nq.gz
    ├── 5f3d4cc67d3f4a13d8fe3c763d650f075c8bfb56.nq.gz
    ├── 5fb563e9bb9a61de28a6beec5cb76ddc799d5744.nq.gz
    ├── 60ee18832954b67d7c0d5b222ccfbf59120018bb.nq.gz
    ├── 61011e19886c44b41d02433f13d46ae85a1f7ca5.nq.gz
    ├── 61ffafc89f0ba0cf699d374e1c4ddfc4b4331955.nq.gz
    ├── 6282810a62a15249c56909102407fc4be5ee83bf.nq.gz
    ├── 6308eaf1330df37b7c779a5ff83a9703358335a8.nq.gz
    ├── 636a7e34e426546a3ab960ee239a213df051f7d6.nq.gz
    ├── 63a62b2cdcd66bf5bccf1a849a132062192e5dc7.nq.gz
    ├── 63a72206cc85e326ffaee8851cd1416f270c0bd7.nq.gz
    ├── 63cbccb5af38c38b52cb456b732d602b4aaed462.nq.gz
    ├── 64781a7ee25e265c833ac1b3876e0d15211938d4.nq.gz
    ├── 64c73beaf6aba31d10e2f3851edbbafd7f6c8330.nq.gz
    ├── 66274a3cb55f161b4e59076341b5a499aa893ace.nq.gz
    ├── 696a6a7095a4568c3569152df62b19046bb82c91.nq.gz
    ├── 69ffbb77b92e3d53dc1c676fcb26398445f73ed1.nq.gz
    ├── 6a268db28eadc77bf58962dd2a61e520590263f6.nq.gz
    ├── 6a422e6aaebe0141d96436d212b7c65b2d8f7432.nq.gz
    ├── 6a97d9e63dfe9c72d160a22f4e491a202cfe04e6.nq.gz
    ├── 6c9ded1f2c277b427d1bc1604c75b62494d98e59.nq.gz
    ├── 6cfc5252971a514178e062d7d1e88d61c3ff5e01.nq.gz
    ├── 6d30c77bdbadf30d7482a0156f981b16b4c7aa49.nq.gz
    ├── 6db6eb7236d3d5a49384d6970dafde478781b096.nq.gz
    ├── 6dc98d3aa4c0dde6979192540b7c4842fa19771c.nq.gz
    ├── 7210ef8881d01f580d5fba16710b32e1215d4643.nq.gz
    ├── 75518e5c5f87d91e0258873d12400056a1189975.nq.gz
    ├── 7825b3a17745c2a044417570f2257dc2abc15546.nq.gz
    ├── 78bad3630f37e01c0791258cc287bf17409e9197.nq.gz
    ├── 78e03b21ab48d478a1c4facfe8625dd88ad16809.nq.gz
    ├── 793e6a77221979ec05f58041ed4cfa670f5ccc85.nq.gz
    ├── 795a1f9d618fc24cd3f548d48dff87818d239ee9.nq.gz
    ├── 796bfdf96806e495fb51fa2380b17d8a808fbee7.nq.gz
    ├── 79e82a6b0385aef0e608e39c30ded648430f486b.nq.gz
    ├── 7bbf3475a4efb11eaf455f52af6cc81d76259e6c.nq.gz
    ├── 7cbcf7b69ef8f881c539904ddf7616ca3dab3034.nq.gz
    ├── 7d1181218229ef907206e3ce1266c6c02ec22dea.nq.gz
    ├── 7d393947dc84edbaa84b2fc001dac600c7aafc2a.nq.gz
    ├── 7fd63c074956211638541a97944ad367dee8c1bc.nq.gz
    ├── 817b0754097c13410025616bccfbe801c8931564.nq.gz
    ├── 82792f19b3dcaa1bd5c2b3ef2a065b9ac0dbb3b5.nq.gz
    ├── 83002ab4e88520712c518c3046d44201d1195212.nq.gz
    ├── 850adfa732017f0a220f2f4b0041b4253b65d025.nq.gz
    ├── 85843f83afc8d53e528e5b0612f6af087cd8d038.nq.gz
    ├── 86b695e6b6bcb642e33cbb88b4a83ab60c5d198f.nq.gz
    ├── 872920566ad9c7b57356056c188e13b3836e30f1.nq.gz
    ├── 893ed2655c138655a9cedda07de0d8434e6e753b.nq.gz
    ├── 8a065cb4ec3351a9c9fcf9788f9bd8913b37964f.nq.gz
    ├── 8a4476ba72ef13c63d1541d169a7daee30ba0754.nq.gz
    ├── 8aa6a4f06a111a5f55dded44b9fd3a5d7e8313ec.nq.gz
    ├── 8c611b249cebbfad0fa64441a96af8e1b2534ad4.nq.gz
    ├── 8cf4da0b518c1cc12a4fdc18809b9420310b67e3.nq.gz
    ├── 8e914b19ef0f8eb02d835da5212d789aa558ae6f.nq.gz
    ├── 9044c7d8c35a05c0944957f173299094869f01b2.nq.gz
    ├── 92780d9bbf47ff36f789809406b4d90c652a491a.nq.gz
    ├── 92d316560c8a618955eb09f8161ebd90599e37d5.nq.gz
    ├── 9343e4fe0ea52d1554f3e27f73997db90872250c.nq.gz
    ├── 94ff31ba6450c054e5492470af2d1b4ea671a919.nq.gz
    ├── 962db60ba7a62d15567b4da029147c6b472e2463.nq.gz
    ├── 9707aa2bff343c4ca405109733a9b68a8da282cd.nq.gz
    ├── 975e0b5dec68b5937d3c862f9f6051f07854c28a.nq.gz
    ├── 995a035862410e9c10e03129dae7e8a86d808c2b.nq.gz
    ├── 9c53358d50d98695ee888c2e64c8a4d44bdca67d.nq.gz
    ├── 9cd18097e36096f584a452dcfced73dc4810b399.nq.gz
    ├── a0739d4617782243009a47232d01d22f5df70857.nq.gz
    ├── a07df29640be5275da7bd5663276ed126d34fc89.nq.gz
    ├── a22e4ba179232a3d94ee828435ae1d6b1b88d5bb.nq.gz
    ├── a27129b438dd2c603926786e9e40eba337504a47.nq.gz
    ├── a4edc9035a0323bf57b812507f219e45279d42f1.nq.gz
    ├── a6644789ebc3863e9dc647f9264a1a028e158763.nq.gz
    ├── a687ac358d7b24100c3b8a025f499d150f11fe60.nq.gz
    └── a797622354772308610b7254779432639c3bf60f.nq.gz

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

[plotly/dash-recipes](https://github.com/plotly/dash-recipes)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
