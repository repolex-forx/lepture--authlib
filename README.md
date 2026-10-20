# Repolex Knowledge Graph of lepture/authlib

RDF knowledge graph data for [lepture/authlib](https://github.com/lepture/authlib), parsed by [repolex](https://repolex.ai).

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
rlex download lepture/authlib
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dbf2f5c4fcb491527b7f74791caff9451c51b58c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── dbf2f5c4fcb491527b7f74791caff9451c51b58c
│           └── chunk-001.nq.gz
└── blob
    ├── 00053d80f1dbe0ee1a68cd3ea7ece5ae877f0f5d.nq.gz
    ├── 00649412155fe6534357621ae9eb83223b1b3ff7.nq.gz
    ├── 0071f95c0f0315190e1c07b81d3e19e92b4bd03e.nq.gz
    ├── 018c9f951e854a91b1b2a2175e1b202da8b6fc2d.nq.gz
    ├── 02194770d3b8ed260dec8229d7646d4badb4b101.nq.gz
    ├── 0222962d039e2119fbc91f47a1c40eafcbf6cce4.nq.gz
    ├── 02597fcdefe9ef2bf628e82af015d4043cb777c9.nq.gz
    ├── 0317657da4520f67909d5103907e5030abb01a7e.nq.gz
    ├── 034691d2a5d8a0163fae5d46fe69cfe32241e765.nq.gz
    ├── 034b40d148554fef32b81c28bded92b8ec9170a2.nq.gz
    ├── 034ce309b44203d1165ca065ab1bde2b5269c8db.nq.gz
    ├── 04120af5a25dab8363335dd186c9ae2b48c15981.nq.gz
    ├── 0432a0f62653b12514f9656a7a4a8f25af9ec46e.nq.gz
    ├── 04ceed2a0d4d58806ce6d9924e6a3616b7601ff9.nq.gz
    ├── 05e5c58b19f28fe965475bc2824cf59b09c66092.nq.gz
    ├── 0615e1db0f15d1a5695c7e8d1be0d6ee3273fdbf.nq.gz
    ├── 061a715e619c85acd36c7feb876c05b0ebbebe3e.nq.gz
    ├── 06f19c3753094c5a06c70e2704cd8797170ddb0a.nq.gz
    ├── 06f7b33a999ba84b02cb162ec33d010565333ad9.nq.gz
    ├── 08a9d4f674a80d6300c15f07f33efa6386c277f6.nq.gz
    ├── 08cbf656c81a67b436f71ed893a1604ed3e79293.nq.gz
    ├── 0940a2836df04c4105e3626f3bb564fc69abc2c8.nq.gz
    ├── 09e616a4e24db4b250cecffeccbff53387f29184.nq.gz
    ├── 0ae826570c435c3d9e5a10dbf81546142038fb8e.nq.gz
    ├── 0b83b859c139a4b661572fc72d382e5672d05f13.nq.gz
    ├── 0baa62c60a1cd234880da37bbc437dd48757838e.nq.gz
    ├── 0cef60d614781bfaf5f85d9fabe87265d8e0fc65.nq.gz
    ├── 0f37c221dcf121f524a9209a56cf0bbe7554da20.nq.gz
    ├── 10bd56c5e5aa420c7acdeba16f1f0cdb8943dc2e.nq.gz
    ├── 1127ad4a3090085db98ff5741ce1a0d721ae1d36.nq.gz
    ├── 12efda483e8f24778a62b6529f65207934671a05.nq.gz
    ├── 1332002b1082dc741d66b045726c5b464da311db.nq.gz
    ├── 13b58878640e3652e6d456afd442c549d7571b45.nq.gz
    ├── 15655ba1a8d44f356981686685063cd1a2d6575e.nq.gz
    ├── 16328a203254f4ea43712be16dc8b2779c4be105.nq.gz
    ├── 169ef0046a3d0f5824b061620496ee319f00d7af.nq.gz
    ├── 16a9cb0ac22ecb27cf9f0094315d90b6ef86b310.nq.gz
    ├── 16c709067e6eeb3d385e2e7d34ed506cb5bdfaef.nq.gz
    ├── 173d08c584e7215e66ee834c2624d2c217330d05.nq.gz
    ├── 175feaba07586f446716328eab90b9c7106e03a4.nq.gz
    ├── 1774248b579062f410e6d31ab55692113aebef66.nq.gz
    ├── 17994c5005a2c46f6924aafdd2e5e421633d3f57.nq.gz
    ├── 17de50178550a6403673f22bc44128b37bf6da01.nq.gz
    ├── 1807584b77159cbd1c14103bb053858a31baf186.nq.gz
    ├── 196eefe5f91fa71c4e0c8824a43addc4548fa04d.nq.gz
    ├── 19a14597f53e6def936ed0b7a6afc5dc446d11c5.nq.gz
    ├── 1a0a01f3f819e850fa322db04adb76d8a8d1fe59.nq.gz
    ├── 1a37c8aad86c4ace64f4815cd17d28fcfd5284e7.nq.gz
    ├── 1b4fee33dc3e87bef918698a937383813bf33f12.nq.gz
    ├── 1b6269f5ce714d0fe69fa027779faa89a1a98bb8.nq.gz
    ├── 1e3d4f0ac4ede6e1da33d11c77f8f0fbdc25e656.nq.gz
    ├── 1ef0d2dab9bab46a0cab524a7044856fbc19dd82.nq.gz
    ├── 203b73e4adf0d98cda9e574f8066ff378b685075.nq.gz
    ├── 2084178eb1a7290bb51096e405fea18848f168fc.nq.gz
    ├── 213be56411415864903632b5142f2d14b71cca96.nq.gz
    ├── 224c39aaf69d844c85c4b3437b8c799c9ef87f8a.nq.gz
    ├── 2393ed8835f3e9b8c9a467d1ead65f7c20e568f2.nq.gz
    ├── 23de32e7dfdb554d646370d7387e1040cb79576b.nq.gz
    ├── 24240c3dd79d8283d56cbd7d1b0e7e455895e292.nq.gz
    ├── 24a1e73165dd8005c4cca60c4e13924627e0c5ae.nq.gz
    ├── 25063dc25df941cc7716f5bada8760b3dcdb0d06.nq.gz
    ├── 26452eca24c96ac9c5bf69e38514a3c4f0b7a872.nq.gz
    ├── 265e439569d00c6ace5bea5869cba028bef4f99d.nq.gz
    ├── 2807b0ede15ca5f688c335be866ee9d415da4fe3.nq.gz
    ├── 282e5bc7754ffe0bed302444d80427e7c659965d.nq.gz
    ├── 28b5ff0718783b0bd13bd946e6f1de403e8c70b3.nq.gz
    ├── 29782f324208caa7a46466610c87812c57a3b8ab.nq.gz
    ├── 2a2292b129f6f4079ec6bbf45d27444451ff0e28.nq.gz
    ├── 2a50b974b1e0abcf130ca4e2d9e073df8ff24c8e.nq.gz
    ├── 2b2149f8048da1c7a410e4cb5aad480f4369389b.nq.gz
    ├── 2b381d57146958d9e4637622c8bb9bfe360e7702.nq.gz
    ├── 2b9cddea9a32dec6d061d4cb496acc12807e13a7.nq.gz
    ├── 2c13c3741bc8946ba6edc0f9745b656c3cf642b3.nq.gz
    ├── 2c99d5e1f085a949f13eb5f0ff14f157a9a69793.nq.gz
    ├── 2d1d87d861b4997e43d224eadff44afc8b57bff0.nq.gz
    ├── 2d3f5b19bdc5466e3cb250ee9dfc897216c0deab.nq.gz
    ├── 2d86ecc118a41f12bab4d26b8ee9407deba34a47.nq.gz
    ├── 2e76711b39baeb9ac7a58ed1ef5635445836dab2.nq.gz
    ├── 2fbab877465e82841dc8a8dc55fb564261c6927b.nq.gz
    ├── 304064fbef445941d289a08c27c3f0aefdd12e5d.nq.gz
    ├── 30776c34c197c9adda058fe3d7ed8b6f965b4a53.nq.gz
    ├── 30a3bf83c6149712cbf94407e57976142d529ef8.nq.gz
    ├── 312c321ec8b05b8fbdfc9d524e6985df596d8fe9.nq.gz
    ├── 32b572d343ce1f5fe8228e2d406820acd7d37c42.nq.gz
    ├── 32e23e6b8d7251094f949ca6c903181c58af72b5.nq.gz
    ├── 331c3b53a51a19a81086a33acdf7bbee0e04215f.nq.gz
    ├── 3440f2a9ad5654fc8c71caf6c1f789ea17ddb1f0.nq.gz
    ├── 346c14ab212f650f08e40f7245806b41de899a0b.nq.gz
    ├── 3496da3cf4d2dd197ae63e6a500b89e7f1e4e1c5.nq.gz
    ├── 3537c8a320ec33ee7101452f5c442fc494ed4c9e.nq.gz
    ├── 354306dc62c6c7c258ef95638bb6a78fb1cc935a.nq.gz
    ├── 35989c2073ab9a59148bd2ba9b8187f965622dba.nq.gz
    ├── 359fa89f95cb8144073f84f62b3cfac6ee34898d.nq.gz
    ├── 364b6b5a60e6214daa86022bf909b7a288b881d0.nq.gz
    ├── 377b9e32d03531cebb736aae99dcc24aa8e22222.nq.gz
    ├── 381c5b09dcf322de24097cbfe6d92b44fa7e975a.nq.gz
    ├── 385a866eff6d01e3ef6db4d957e9fc31a3f92646.nq.gz
    ├── 387bc59032dc2a16145697bd5be111ebc46f27d2.nq.gz
    ├── 38fd2c479004e5398f3adffe02c58c2b6fb4908a.nq.gz
    ├── 398ff9c49d96610b09f7772a9f4ae6ceae99e8ee.nq.gz
    ├── 3b528b80e6d961029a1d7d52f81e62ba89f129ed.nq.gz
    ├── 3b6846d268712fa1dba76174a7a1e96c57d398cc.nq.gz
    ├── 3b9ff5f502e87a6d5076b7c5589c9fd2c4ca358c.nq.gz
    ├── 3bf4a9050345bcf45b74629d37e8d57d1cb89925.nq.gz
    ├── 3c3b5c03aefe653f721fb94f955cdd1d9ea42d7a.nq.gz
    ├── 3c8f32494f7ab337e391ce5099efb4a0536f7784.nq.gz
    ├── 3ca43c02e1231f453654d76334b02bfdbba17d1c.nq.gz
    ├── 3cfc93729e5abb92b9d41499e2e404a1bf9496ba.nq.gz
    ├── 3d79b82dc64a591df8c13b8618b1e7c552e07289.nq.gz
    ├── 3e91466219cab19b1793f55d6645716c2a10b8c0.nq.gz
    ├── 3f82c2b1da8997efb9115637eb3f3e1487ebef60.nq.gz
    ├── 3feeeaabf913c9c612512d01d447b3a124d1bdb6.nq.gz
    ├── 405870047e79c21c0f4ab0b2ec77cf7e9f500910.nq.gz
    ├── 40744828931e555e00b620dff87e4c805382902a.nq.gz
    ├── 40d850a72042625ad8c38ec1eecdeb165e7093f2.nq.gz
    ├── 41dffceda222322899ddbc66db68dbe9c49b4b2c.nq.gz
    ├── 424419946c1b68036cfe419e339efa9bb6b9cbbb.nq.gz
    ├── 4270dc76ef67d9b805c711c1b10220c82dce2f94.nq.gz
    ├── 427667b642789d68b18dfa85b6fc93f2956c0bb6.nq.gz
    ├── 42df2f835df439a148d9a0b2e06716edc23486aa.nq.gz
    ├── 4339b013f61577bc3a20892c1b84a9365867ea5b.nq.gz
    ├── 4377020a9d081a502d46fdb9386241b8972b3b4e.nq.gz
    ├── 43c94d0b6a67e092ef58f9cfefce7517b05e5cf3.nq.gz
    ├── 4436296820be5e342c1b386c60c0463f270d68fd.nq.gz
    ├── 44514a11ea65de8ddb68bc58fd85ed7ec8ec739a.nq.gz
    ├── 44e0ec32fc36d7f85125eab4e48cc54aa8a62d95.nq.gz
    ├── 45166c0ab301af1c7d52316250452539cab8c120.nq.gz
    ├── 46faabccd613caebe2bbd0b992f34b80d9379df3.nq.gz
    ├── 471dd07da43276d19bebc2c3c9b8fe3848a8f63a.nq.gz
    ├── 479420380f2382923828e8d4ee7039810203d3cc.nq.gz
    ├── 47ac10f6f7ef919e0c1122ea1442c15de2a599b3.nq.gz
    ├── 47d69926eddc0a53ab028c8f04ac5973d6913c8f.nq.gz
    ├── 48227aefa875f2f5b93bbef8b8530d167b630947.nq.gz
    ├── 4931a18eb7205dff62a0908b4887d4eeac89170d.nq.gz
    ├── 499f704b3eefc060de30c02bd80bb31f1058b793.nq.gz
    ├── 4aa3bf831787e72cda152cb27fde3798a303ec13.nq.gz
    ├── 4c1533b0bfe57fa2ba56044b10e7471a6de5e540.nq.gz
    ├── 4d5078c28ebf7ddc77e90a49c1bfd559a77c883b.nq.gz
    ├── 4df1435d1fbdcd6c7047b81f3cb075507fced21e.nq.gz
    ├── 4e400f553de37a969258aae8098faef2d8c5ff20.nq.gz
    ├── 4e4e8bc0176477bba00c03f393235e7c64765426.nq.gz
    ├── 4ead0e1daf29aa74e50d6dfcdd259b0bbd43f84f.nq.gz
    ├── 539c57347cc9752dfdd4c8dcbe6c1fd785b8260b.nq.gz
    ├── 53de55aa571e2ac310a6f630e456d21b2f5392a6.nq.gz
    ├── 5403bab6e3b6d54c5a3e12453785ed97cf30df3f.nq.gz
    ├── 542331e00671e860960a6fb45a5cb33629c83aea.nq.gz
    ├── 554ec0565f04d76116fb7a92472d8cf9e6e2688f.nq.gz
    ├── 56d615d858f9749f281754fb751fb96994db464c.nq.gz
    ├── 570c586d937ea8ca699af12bbf97d1f9698cb7bf.nq.gz
    ├── 571c851ebdb20f5de8a32b9a25fda7acfd31fc24.nq.gz
    ├── 57a437b33765af1d943ba21f72f647fd961658db.nq.gz
    ├── 57cce2536abcadb0b4b41e05a7be732b106b02b0.nq.gz
    ├── 58076f258933a3a693ac051f61c4595a94d6a921.nq.gz
    ├── 5837788c97e6be8e65253f93b2fafb60018850e8.nq.gz
    ├── 58ca4f72a23a42e25ca0b9ae5dfd2ee0cff0e410.nq.gz
    ├── 5a2361385fca6673d0e81f951f052c0a1dd489d7.nq.gz
    ├── 5b1adfa827dc5048fb016991e4156773e3bfc744.nq.gz
    ├── 5b6f3c4070000ec6c6ae28b93ca719432647200a.nq.gz
    ├── 5bba746567ae1562a3af46197d9e085741c56ed4.nq.gz
    ├── 5d22216fed85665b87ef75f40ae0975d8ae23e60.nq.gz
    ├── 5d30cae977771a3ee4318bfe6ab75ebcebd6987a.nq.gz
    ├── 5d9e2011be6c3a184da88ed35e186a28fd1050fd.nq.gz
    ├── 5da940bf2c8d45a926fb74afffb0b996dfd81161.nq.gz
    ├── 5e1827b3e8a0681685ae2cf7d2c4cf7b053b401f.nq.gz
    ├── 5e70005c3ced391929dac8f46073a01086ffc8e2.nq.gz
    ├── 5f499d119ebea0bbb98fc7923e39feae5c2a7684.nq.gz
    ├── 5f6c5e591b383c76c5067adbb433a9cf74d502b2.nq.gz
    ├── 5f7f11dac6bc5406bf0f81d9c323e53b6a9724f8.nq.gz
    ├── 5fa65b228e7119946e283cff73e402a9cd3e6c94.nq.gz
    ├── 60535a0cfab2891be08ce98920f083e4c119471b.nq.gz
    ├── 62be658be3f5224e5cda34483270e7880dece9b5.nq.gz
    ├── 62cff3a7fda91a2c36e2e1f0d7d4773ad367f07e.nq.gz
    ├── 632cd8775cda55e9464a5b0bc7f457e529c91578.nq.gz
    ├── 6364481e711ab8ea557c340332b484059d1e92e2.nq.gz
    ├── 637e003ff3f061e4ddc50f516545d054202792f0.nq.gz
    ├── 638a0c0dbbb6a76461e3ef6e9ae4bc078d821574.nq.gz
    ├── 63f2951f38324b90f67485732c598957ab36f72f.nq.gz
    ├── 641a63940b322d9eb3e18dee22411e9582fbafaf.nq.gz
    ├── 646863464616a1a85ebfa64e97110c0abca2a3fa.nq.gz
    ├── 646c6969b32c0ae7be4b403eed6c42f8cb45c8f3.nq.gz
    ├── 6574e4de947ffbc58194759e30ede91d74542da5.nq.gz
    ├── 659a5ad78743c5042210ec981b498a625ac1102c.nq.gz
    ├── 662f2b165e18dbffcbff8d6ef8c017fe4db077f8.nq.gz
    ├── 6793776afad029b1dd21672ab9ca965f9a26a1d9.nq.gz
    ├── 68bb426be9e03471c91ed774be3f9e62a3a597f1.nq.gz
    ├── 697e9b972fb7d7db06ede79de115eeacad2070bb.nq.gz
    ├── 6bb94f92a963f62de28d2c5a227c0a66d0c2c77b.nq.gz
    ├── 6c32a01f23f850ffd871743d1206b2030cf66db0.nq.gz
    ├── 6d4fb1b3015408d65d4d5723987d8d1481c289b2.nq.gz
    ├── 6da636f448e954fce21ad33ef2213f2e86fc220e.nq.gz
    ├── 6e0be71df285c2bdd3e20617a12e223b9199e89b.nq.gz
    ├── 6e6e7af5263f5d8d2164923a79903b02d0bcc1b3.nq.gz
    ├── 6ed1b9a7c00b4113300d148e78595c6b82b03ba9.nq.gz
    ├── 6f6db48c7a5090a8d30731e787c6e631e3e10b7d.nq.gz
    ├── 70b1c5cf40bc74f86b6ecb69d708a65e19e48beb.nq.gz
    ├── 7191fb38bb87079ee836fbc5ba05324afa11b876.nq.gz
    ├── 71d8c24398877dab041a763a84ed6338f921db3d.nq.gz
    └── 7200552ae49e445c5f482b47cba733d9e174afe0.nq.gz

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

[lepture/authlib](https://github.com/lepture/authlib)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
