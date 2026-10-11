# Repolex Knowledge Graph of aio-libs/create-aio-app

RDF knowledge graph data for [aio-libs/create-aio-app](https://github.com/aio-libs/create-aio-app), parsed by [repolex](https://repolex.ai).

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
rlex download aio-libs/create-aio-app
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ece2a2b5132787f44c04f03997976fcd120a315b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ece2a2b5132787f44c04f03997976fcd120a315b
│           └── chunk-001.nq.gz
├── blob
│   ├── 042ec21d7d816e432b5d9f4e54070663b90ff205.nq.gz
│   ├── 082d6c25633c1306214614fc9fc043a988ce5a7e.nq.gz
│   ├── 11fab0a3835de08355cc7d700ef4b9691ecdda92.nq.gz
│   ├── 22bee81fec83757d37d12957e9312fcc0f5deecb.nq.gz
│   ├── 233df64b6373150fd57d085369f6d61b59362738.nq.gz
│   ├── 29c0ce4cdd7ddc0240ece5d96df8080d95672982.nq.gz
│   ├── 2c0156303a8df3ffdc9de87765bf801bf6bea4a5.nq.gz
│   ├── 319b5c8a80b962b45e5db5b35642d82f76db85aa.nq.gz
│   ├── 32f6919001f6aafacb4c6d8d944b19fef86cdd3b.nq.gz
│   ├── 35e5423edcd42cecce5383b81b8c5c38809a8829.nq.gz
│   ├── 36d7ec6dc9d49f6675d962693808d5b9d3af42fd.nq.gz
│   ├── 3843a11fb70f52c8f5f7f494c6844c2e242d7991.nq.gz
│   ├── 3a2c830a96a9f629a69e0f584f8f0af9b0765f71.nq.gz
│   ├── 3ca034ea68c9931cb1908c9f18675d4d16557b60.nq.gz
│   ├── 40c8a20174d3339db32b73453112478ee5da6211.nq.gz
│   ├── 43dcf6c76948815e14674a552b1ed901a10c521a.nq.gz
│   ├── 465085d1fc0a71ec965ae1606db89a73cbc822e0.nq.gz
│   ├── 4d9eb83d9f9309029f4b14ff09024658bb0f5563.nq.gz
│   ├── 5383dbe995e208be50a116ba9ec2b8fafac4827f.nq.gz
│   ├── 5d2360687df75aedce3d7583ad49f73e2b52c605.nq.gz
│   ├── 666937af4283563b86c9bc288cca20b667d4cf5c.nq.gz
│   ├── 69fe55ecfa9aade66e1412aef0ee7d04a9bcde86.nq.gz
│   ├── 72a58a1d1969e27ca10bdc46aeb0260c22ce3199.nq.gz
│   ├── 75c186ab607235aff1629e7cf0ff9afc012e6a2f.nq.gz
│   ├── 75f971166aa4063943ec9c92aed81e04aac28046.nq.gz
│   ├── 7c83935e2ab54113dbe76a62ae4773bc62904b22.nq.gz
│   ├── 80479331c1fb1a4a31c3bdd1a40344df1e91d87d.nq.gz
│   ├── 807cf663baecda1f3568e2a3e5ba903273cfeaf2.nq.gz
│   ├── 8197ee1b7fa5f07b61e914a0e7687bb613dc8985.nq.gz
│   ├── 82bf71c1c5bd40572832ad8aa70262bdc8a5fcaf.nq.gz
│   ├── 894a44cc066a027465cd26d634948d56d13af9af.nq.gz
│   ├── 8abe40f9c1d3750039a5eaeee5aad4b5064094fc.nq.gz
│   ├── 8b2863bf286b2aa19e00c2f23364ddd0426e3f07.nq.gz
│   ├── 8edef98e2e845d1670dd1e54944f80b058768834.nq.gz
│   ├── 916b0373cc74c0e6d940ade65fbfc0bf185e9211.nq.gz
│   ├── 929de0eeafd0bd7acda8924c45e07690b27531c3.nq.gz
│   ├── 96a9bff9ef9b4450efd5941d4af2c12317b86bb8.nq.gz
│   ├── 96f1555dfe572f6dd2af1b7db9e100cd85bf9687.nq.gz
│   ├── 982e9d99a02a3dab73d3d0574f1a53a0ea41ee8f.nq.gz
│   ├── 9fff6eb312b2edcffa3d6f4049c53fab28a5478d.nq.gz
│   ├── a0eaa165834041a7b4bc0444f1796662d4c48fbb.nq.gz
│   ├── a1c5313772e828c165209a5f9ad3f3651ceeb218.nq.gz
│   ├── a227eeb7e2139f3a3b8b7e6d93d3469c7f2677ee.nq.gz
│   ├── a30a465c3c26156dd2b1518fbe635c10e3729d23.nq.gz
│   ├── aac3c0e3623e1302d12752c978b9df1e92b8c28a.nq.gz
│   ├── ac5c6b2c3e5e0fe86d7f17650e32c2d89073c5d8.nq.gz
│   ├── ad7c4e838dc29eadb243b29e4b9f74c1cbb8e8e6.nq.gz
│   ├── ae6a1dd838075cbd64663ba18cd16bf4bb750dc4.nq.gz
│   ├── b10129fdb3e54273b68c48e623549c81fc2a6d36.nq.gz
│   ├── b3eb6c902f76079e7a71e5439265fd8aa447f903.nq.gz
│   ├── b68422a9b326af5e0fd42a2b9d4638d2318221c6.nq.gz
│   ├── b6b12439e08eb38222b8c078d979b46a60cad74b.nq.gz
│   ├── b8471fdc873278e199097f64d7b047d682a9f86d.nq.gz
│   ├── c39bf85aa2cc83d35fcd38ae02f5d8259de2546d.nq.gz
│   ├── c39fd779cf374f89ca719a5be14b39cd497f3fd2.nq.gz
│   ├── cc10a5391607afb30bfc34516169cd096579f6c6.nq.gz
│   ├── cebc7abfe0a3d318df1e6437a804c4aed6da94d0.nq.gz
│   ├── d330e0568bcf97de66227d18ea1b4320a900e80c.nq.gz
│   ├── d3f678976a623603fe18c031a92af80d2339dff3.nq.gz
│   ├── d46728929567635872e66dc1ea987d9a23d0ec68.nq.gz
│   ├── e08e4895285bb3c5296735c103faa00ebf3a4cd9.nq.gz
│   ├── e394fa7cdb7a4683524caee7be9ae420533f440e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e94b851d3def802303c779bc2ad0522d23d746a7.nq.gz
│   ├── f102a9cadfa89ce554b3b26d2b90bfba2e05273c.nq.gz
│   ├── f13e5b4f60e3bd52fd50d48015064c2a75b15b8c.nq.gz
│   ├── f323adc9a7f2babbf6bff687d85db26b33173ddd.nq.gz
│   ├── f3c03aeb75799c6b70667b8a374f5e584cfcfb5b.nq.gz
│   ├── f4c0d6b6042c75df7454e92ade92396d731d4bd4.nq.gz
│   └── f5092d1fe8e6b1488b898f883df34adc157f0170.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ece2a2b5132787f44c04f03997976fcd120a315b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 78 files
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

[aio-libs/create-aio-app](https://github.com/aio-libs/create-aio-app)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
