# Repolex Knowledge Graph of indygreg/python-zstandard

RDF knowledge graph data for [indygreg/python-zstandard](https://github.com/indygreg/python-zstandard), parsed by [repolex](https://repolex.ai).

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
rlex download indygreg/python-zstandard
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a2bb3c0bb3657007b79617dcd63ff3c6e2acedd2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a2bb3c0bb3657007b79617dcd63ff3c6e2acedd2
│           └── chunk-001.nq.gz
├── blob
│   ├── 00384cbca3fffb4afb8476953cfbdc6c7be5247b.nq.gz
│   ├── 00a1acfd3523e2c496bc54688b64067876929209.nq.gz
│   ├── 02499c73439429ca8a29e967c692577ef25cf254.nq.gz
│   ├── 02c3861b6633e8bb2c4faa49ec198c3f3c0fdb34.nq.gz
│   ├── 05679d19b6f00d941818eff496b783cc896e9c4c.nq.gz
│   ├── 056d3d50199fb7be652015d2cb2630b6b815a2a7.nq.gz
│   ├── 067e6810e4af9183bf6d4260aaf4eab842198a5d.nq.gz
│   ├── 06fe57be0913de1c123b6503f02e7577b32f1f31.nq.gz
│   ├── 0bdb1915c8bfe84e436ca7dc37b60c823c249a2d.nq.gz
│   ├── 12ccd820666b119aba5f9f262f9f1fa17db5d29f.nq.gz
│   ├── 157822f0152e1fb21191627136d63e3703e37c34.nq.gz
│   ├── 15be5e9f8661d21ba043db6ad7deb51e570e2dcf.nq.gz
│   ├── 163aaf8d82b6c54f23c45f32895dbdfdcc27b047.nq.gz
│   ├── 198fd94828174ba662e495d895b747862ca7a93a.nq.gz
│   ├── 1b02d081ae8266d17c170fd5b3c038a8ce4da534.nq.gz
│   ├── 1f1855fc5c1973cce183f764d26975f31eeec028.nq.gz
│   ├── 1f226955e39c2210b5f0860a854bb2c4fb7f83a6.nq.gz
│   ├── 2129484cf24a311bb3ce38d77bde539402c3e052.nq.gz
│   ├── 24188ba5b9532a382e13c09160904f325e5d7907.nq.gz
│   ├── 25a918bf66fb275a8e4a55c9a150121464360ed3.nq.gz
│   ├── 287d662ca6bf267aac5fbd8a3b20220b8130df48.nq.gz
│   ├── 293baddb0301902abe810455e8718ec0fd6b1048.nq.gz
│   ├── 2d901a55ab696df3c47c32e1ff0cff67b7b4094f.nq.gz
│   ├── 2e0f3b693c3928585a3271c4641306e5aefa16d7.nq.gz
│   ├── 2ec8b0bf437fc470dc7498d1fae1db16c76bd27c.nq.gz
│   ├── 2fcaf02e0da952c6e4a13beb7d2e84459e21b485.nq.gz
│   ├── 33ac0ce01800ae0ae66698cdfe9a57ed6296fd5f.nq.gz
│   ├── 33c1231072fb1b82915eaf3dc73d06370ca80d9c.nq.gz
│   ├── 34fbd47efee1f9e55cf017d5776590c88f0c25ad.nq.gz
│   ├── 3578620154b7209bf30796145c042ea5f607d8b8.nq.gz
│   ├── 37a29cfef056352480b622b90f45946401d88de4.nq.gz
│   ├── 38a04bf3f5ea5fe957b47e1437486f9dd0fc1362.nq.gz
│   ├── 39765cba18bd784b759e6d7a20a65e4b7fb36e26.nq.gz
│   ├── 3a2c1b59550a253a149189e1221589470ba59a4d.nq.gz
│   ├── 4063ed27c965cd175fa5768a60e7fa18ae5d955f.nq.gz
│   ├── 4222e2bf5dcb2fbbac93928b847374e6ed72b8e5.nq.gz
│   ├── 44d74ff5e2d6be7860e30a1c51c77628e0e56d48.nq.gz
│   ├── 44e14ab64f7c8abb2a85241b0cb7d9e4d67c00a9.nq.gz
│   ├── 47626e34098cf9b216eaf8f5cb3e23877ae9c68f.nq.gz
│   ├── 4df172e667b46ce6967998b404e6c282bd7a5162.nq.gz
│   ├── 4e09399bc018724098c3cefdffebccc510edbcbe.nq.gz
│   ├── 51628504370e22e89fd9c04a1ec387699d881238.nq.gz
│   ├── 52174dc318e3bb2743357ef4d26fe716486fc6e8.nq.gz
│   ├── 53ecf0cc9606a16cecbee91dbec1aaba5ca5c5a6.nq.gz
│   ├── 5657a8583e015ec25e53ef00cc7cb98e3686e22d.nq.gz
│   ├── 599b793013ba97745d61dfb62a710da16ae7c86c.nq.gz
│   ├── 5c6ef1724f34b43e7860167c62b79971d6663893.nq.gz
│   ├── 5c715ea0740403bfd65f6c2d6d6bfdeae890104d.nq.gz
│   ├── 5ce66fd2bff79fd8e7f2f8c81ed16148991a982e.nq.gz
│   ├── 5d27e6c98d84d3eab90441c5cc16b5177be1a485.nq.gz
│   ├── 5ebb9e12c13e683fdb24a5e9f0626cf3bfc15606.nq.gz
│   ├── 602df6fe90a6e97fe37ee105e916022b250a0184.nq.gz
│   ├── 63f98ca837fdfedf22c2e0f62407709dd74fbc35.nq.gz
│   ├── 685660f2f48788fb2b75f5a77112c3f04b80c7fe.nq.gz
│   ├── 6b067bf31bde8605587f066b8acf40acc4f3a855.nq.gz
│   ├── 6c1fca21e05fb4af89adbbc4c30a06a03cefa1bc.nq.gz
│   ├── 6e059fd3d54401321ce8cb5f6da0f03e9844aed9.nq.gz
│   ├── 6ec8eb2b420f86681a042db1c2f6a6253cbca0bb.nq.gz
│   ├── 702ebcbda22271d9299f1970a49d788eba1920e2.nq.gz
│   ├── 71a148be4fd50e067eacdd29c7f7c0a95e895105.nq.gz
│   ├── 7277463de481b68ef8bdb1eb741533430a3f690f.nq.gz
│   ├── 72dbbe4ee367afaaf0ee87af5e74280d1a37abd9.nq.gz
│   ├── 72f3b713a8cc506da1da76fcea6fdb4c86ddc87e.nq.gz
│   ├── 75800288cc243f164b9d130f125e2ffae28f8e39.nq.gz
│   ├── 76578db61235a716933fab64727ebb39b6716ec6.nq.gz
│   ├── 779165b208566ad0ef9f9542c9d53cde05c4454d.nq.gz
│   ├── 787a63ac867c80881f6c5631312f590f82beb2fa.nq.gz
│   ├── 7f8f011eb73d6043d2e6db9d2c101195ae2801f2.nq.gz
│   ├── 83641a758014a4ea77b233224488314df548a0be.nq.gz
│   ├── 83ddea047e298b78c90d751ef5bc6cd3ef83faba.nq.gz
│   ├── 84e712155a4dd8edfcc83ad75ad221b3028b6d73.nq.gz
│   ├── 86bf25d26c01f22b4c28a4a77f78905641f7b424.nq.gz
│   ├── 87c3b902b3c08c24d1bba058f5f84e7a59b1d454.nq.gz
│   ├── 88a40fe5269aa88ef7a005eee17314f963e9dc64.nq.gz
│   ├── 89b3d743b6e32962324a5275bcd85f5ff1f17ded.nq.gz
│   ├── 89fdd4508024f272f7f89092d457b42adbda2e67.nq.gz
│   ├── 8a0876e559f634eabc5e94f3dd3325fda0e61cce.nq.gz
│   ├── 8c3b5bd17f498785ac3518e602066d3b52d72a10.nq.gz
│   ├── 8ebc95cbb2ab882027a3e6cc92cdd5abc1a0dee4.nq.gz
│   ├── 9502c29d857e17c29423d1fe80676660d4d8d271.nq.gz
│   ├── 9606eb5da4bca5a7c6236e8513ede60c7f46f9dd.nq.gz
│   ├── 97e63742b4eadd260adb62fd0a23f3d29f389f7e.nq.gz
│   ├── 98994b82a2eba519a2e36a9dfd6f653d4b5b1721.nq.gz
│   ├── 99ba80bc1441ee44af638632ffbcebb10324ac9b.nq.gz
│   ├── 9a86c14262c6114dbe20a2506ed556d377ec06d2.nq.gz
│   ├── 9ad609b1d3de19fb416b5c346e34fd86457c4859.nq.gz
│   ├── 9b00d24fdb62dbf819b94015bc28a06082a55da5.nq.gz
│   ├── 9b5fc0f5c6721cd40e16da2edd7fe796e1acf84e.nq.gz
│   ├── 9d830cf17e480954a5667f706470b31439fa3508.nq.gz
│   ├── 9eaa349ed8eca97854de7b35bb6e4ab7c19f13b7.nq.gz
│   ├── a390e1fb6f62f760e7f64d22905994b3e6ea705b.nq.gz
│   ├── a5f53c29ce6ab9a141c5af8552373c2698beb8dd.nq.gz
│   ├── ac6f255c2de6da3232586a2ae554b35a8eb2c275.nq.gz
│   ├── ae477e2dac2ea0236716c54512291f12c6cadc46.nq.gz
│   ├── affcbdf4a8b0ebbdbdee06b23961473cc53fd512.nq.gz
│   ├── b08c63a73f9fc54f062be3795c9ca642f0ddc884.nq.gz
│   ├── b14a63b1eb655390d94bc4d5a984efb1df597d9c.nq.gz
│   ├── b22256f670fc59b2fd80e42da8445f8ddad75e06.nq.gz
│   ├── b358a7f5467c5615e11f9c9382329052e4ae6ed1.nq.gz
│   ├── b3f7f2969c1a6b7f9f10b5e078de79fbf167bf48.nq.gz
│   ├── b40197573a92255608e3eeb459aba812acd02a0f.nq.gz
│   ├── b89ae20122169a16cc6f905f7626834a1e5f8fe8.nq.gz
│   ├── b8c0644a7ec6533916e06aa8392a2727cbe55573.nq.gz
│   ├── bec82d2c3eb2aa91ef923dafdd6e6f1739d3bc34.nq.gz
│   ├── bef969d2d29bd85b771e3bf85e8279a071a0d955.nq.gz
│   ├── c2f0e72b33edf7f7a3b52af4e7f83764b71e44cc.nq.gz
│   ├── c40a9bbeff7d6fc482af4fd1713e46c16aa9f345.nq.gz
│   ├── c7490713cbf749091b3626c45d4ea9c6c308e51f.nq.gz
│   ├── c78c052c9d988062f3e7b59ca401c29ff3205cf0.nq.gz
│   ├── c803c70a1a384aaef66a8e02cd8a86903fa6c678.nq.gz
│   ├── c879b941870b8c6b49dba26c7530b890224b90b3.nq.gz
│   ├── c896aa680a3c55658b3e8806d75ed10ee6439bae.nq.gz
│   ├── c8a365678ebebcab85ea7924fe88d75e908383f4.nq.gz
│   ├── ca53b454620b2c1518c5dfd283a1ee1ca92c4486.nq.gz
│   ├── cb8c02ddc4cadf307f44bc242cbd98d0c3d3daae.nq.gz
│   ├── cbea594a9883306488746ce76e700ec577471909.nq.gz
│   ├── cc53d2fac2c565f19d9cd50ff2acf29d70218ad5.nq.gz
│   ├── cdc5194ecc2bd64d9b823aaf5f26b4deb19e1ad5.nq.gz
│   ├── ce32e82eff969e387db54f0ae533a8aae2fe6589.nq.gz
│   ├── ced06669725f9f7199a8c3020e3873be18978e9c.nq.gz
│   ├── d14e90f63747aa9c46a0502399b50c4a1183ec25.nq.gz
│   ├── d5e988369455b9f83027407d7eaa472343d55aae.nq.gz
│   ├── d7d1b37389fc61f8ec577b348bad0dae7938e1d8.nq.gz
│   ├── dae8dcacad3b5adfbefd9871d3d8772aa5872fe9.nq.gz
│   ├── dcec4760996be2143d28a12718adc8f9e050bf29.nq.gz
│   ├── dd8a48f41f758a09bcd2b4f2b046ba7ef2f777fc.nq.gz
│   ├── de01047de9d18deed2a07c05a83ccd56accbd687.nq.gz
│   ├── dfd8fe092bba2e92ebce4417d39f0d5002cba628.nq.gz
│   ├── e58ed02fa8c9150f459e1f8444d1d735e80c9276.nq.gz
│   ├── e624a16e44c49779ca1f33baf8d45154031e6cd9.nq.gz
│   ├── e636b3872f03cf4f82654b916248dac733ff9921.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7920e8cf1790590c410ec59e774d8b993fb3fa0.nq.gz
│   ├── e827e74d7908722070c27f4efe8653663276600d.nq.gz
│   ├── eac71b498002a28ed61aa1c48c6f210e3753ce7f.nq.gz
│   ├── ecbc0593737be657aef92e3adcf3bcbd6fdb812e.nq.gz
│   ├── ed6ee1d6283b116171ca7d8aff3a876598c8580c.nq.gz
│   ├── eed85fe225a29d0b3ffe60b86c0c543a8d4c1388.nq.gz
│   ├── f341405faebf70114d2deaf4a7b3042c266a0ce8.nq.gz
│   ├── f5d654459e1cdb75e0cb55c1fb8e1d88c1c201f8.nq.gz
│   ├── f68bfaebcbe508327137b78dffbce6a5e68b3db9.nq.gz
│   ├── f854ebad8376b6b82280156004d246910c191d97.nq.gz
│   ├── f9e8f2e5ebc73826bb7f07bf4bcc737c35c20446.nq.gz
│   ├── fac6d259572c0e3e194218746e4782fe3244ca7d.nq.gz
│   ├── fb62c47b4b4d1cc39811cf5a9b7eb85b38153e6f.nq.gz
│   └── fd0318d948a458175a386766f22ebba8373d9d05.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a2bb3c0bb3657007b79617dcd63ff3c6e2acedd2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 154 files
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

[indygreg/python-zstandard](https://github.com/indygreg/python-zstandard)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
