# Repolex Knowledge Graph of BurntSushi/fst

RDF knowledge graph data for [BurntSushi/fst](https://github.com/BurntSushi/fst), parsed by [repolex](https://repolex.ai).

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
rlex download BurntSushi/fst
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ac9ad1c39976e0e6c06f0bbe8522ed6eb8d97620
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── ac9ad1c39976e0e6c06f0bbe8522ed6eb8d97620.nq.gz
│   └── repolex
│       └── ac9ad1c39976e0e6c06f0bbe8522ed6eb8d97620
│           └── chunk-001.nq.gz
├── blob
│   ├── 04c33645ffc2ee46af9db3b27e55a9cb59ec9b49.nq.gz
│   ├── 054761d68bd85665a21472a962380363fd85a150.nq.gz
│   ├── 06b4442051bb5b056ac8027fcc2d0864a4bf6394.nq.gz
│   ├── 13d353bffe8b90f717fb8a63bd77015d5b97c730.nq.gz
│   ├── 1e35ec180d955164b2459a028a72bdd54fd7d53d.nq.gz
│   ├── 1f506ed5b04bdb6ed381fe05ba65c863873b175f.nq.gz
│   ├── 24322bd331618029363635bef23b3e05ff64f76a.nq.gz
│   ├── 283164f2e2fa7b207c54e46c0ace6fdaf5169411.nq.gz
│   ├── 3556b3d2a8c66d51a34b68ff65fcb63fc384e108.nq.gz
│   ├── 35da4112226957b936d2e64b74549286da4375bd.nq.gz
│   ├── 3b00a5b0c2e4aba674b35b203a3449563c0c6c62.nq.gz
│   ├── 3b0a5dc09c1e16357459ddc9182a50f360f3cdba.nq.gz
│   ├── 3b67349712f6501811d00b3c3d3ad650e22f9cce.nq.gz
│   ├── 3d231951f0423cc4ff68bcebc9b1551a95b401bc.nq.gz
│   ├── 3d266d5d38e283c346d50205a552c3a5a4cea686.nq.gz
│   ├── 4144681484e155829b6e5a9b54c543b6da80bf10.nq.gz
│   ├── 45cbb5f0295bce78a6376f611463edea82a6ca47.nq.gz
│   ├── 49d5ce510be2ef51f2196acff5170e88792617d8.nq.gz
│   ├── 5085baa7d742e1dde1c74e0999252e964e216e78.nq.gz
│   ├── 530f65939cb0bfaa376b1468fe014f9e4295da70.nq.gz
│   ├── 56b40b18948ce9af548e7c729998251958bd7f0b.nq.gz
│   ├── 579d99f23402e1a867f22ac726972ad4e54800d8.nq.gz
│   ├── 60520825f3b5163bc8f308629a9875e2652e85e8.nq.gz
│   ├── 642fab4386b9534a18bc63723cff94360a2526fb.nq.gz
│   ├── 663b0123a1c8c1a9911717733f09cdcf7a6cc622.nq.gz
│   ├── 686ec972110b0e120ba980ef7b865f0f1a65ac23.nq.gz
│   ├── 68a49daad8ff7e35068f2b7a97d643aab440eaec.nq.gz
│   ├── 68bf8e4cfaaff710e1ed776b29c36ab4390a967b.nq.gz
│   ├── 6c1fffd843483016bb6878e128870c9e9b33d2fe.nq.gz
│   ├── 70340bd1ebfd705c0d8ba9ecf34da5b84562e636.nq.gz
│   ├── 70d9315fff6f67aee45800db76424913bc78b053.nq.gz
│   ├── 722f2912a6a11a0b61801922a7d8fbddb537565a.nq.gz
│   ├── 7821b5d86e8f42aa14e9d57ab156af16d986b1d9.nq.gz
│   ├── 7df3ac6e1cb6476caf89fe44c6e5009951ff369d.nq.gz
│   ├── 7f2bd347ff501295718c2c092ba6b4b29e2a1ff2.nq.gz
│   ├── 84a320ba7fcb7a0d3772197df59d9fc01d197d00.nq.gz
│   ├── 868e0dec774a7761b7ff9cb99ac7d4c3a3a2c8b3.nq.gz
│   ├── 8a9b95b53adb3dba44231f1fc60f49ce7a528b16.nq.gz
│   ├── 8d91cb4bc7f264dfc0da95f9ce7b2fd7aec1465e.nq.gz
│   ├── 92136684f0a9b82374404cd8a15c23610ecf5831.nq.gz
│   ├── 980c3eb841837eefb1ab02a1acc14c197efd0725.nq.gz
│   ├── 9baf8554081eaa769f569b55ab8ebacf1e637e91.nq.gz
│   ├── 9db9748b2a634d58a436d92e71d2ea5856f3fefd.nq.gz
│   ├── a3419c68f01c4458a36d872309a83b44cac543c1.nq.gz
│   ├── a36392ab89d200768c07da7c8b013a3341050863.nq.gz
│   ├── aa37a218b97e5f6ad37a74a62b50727279a5e460.nq.gz
│   ├── abfe94b8a015390a4c8051dc7d98b08063692468.nq.gz
│   ├── b058599c53a71d6eb4b640850fbd7cd57565c01e.nq.gz
│   ├── b08b133a846cdd4771d8aa8ded0467dec82217ef.nq.gz
│   ├── b283771798f98ed0f40f4d92ae5a32a917a146db.nq.gz
│   ├── b9755ef8e0a9dca4511cc62285f8351fbf76f839.nq.gz
│   ├── bb9c20a094e41b7632d63bcff20c0b4b95e80777.nq.gz
│   ├── c757be84e575df9d549d2c4010c1d942ade9ad14.nq.gz
│   ├── c7d733c781435136d087c43ce555d2cfd3e23930.nq.gz
│   ├── c9e77a5f78d3caa582de78d037e3343dc208e0d1.nq.gz
│   ├── d104ab2e588fc068471cbd539ba0df565ba81884.nq.gz
│   ├── d131bb45f128b613806c503539d26645f4fbabbc.nq.gz
│   ├── d6e356e2e1ed7512ed439f6693cdba5de1504a47.nq.gz
│   ├── dfe4970ca344d885d295ad5bc3c14f946794bb87.nq.gz
│   ├── e5c65f97f1ba48ed3b19c669bc5f1774d9bd5f47.nq.gz
│   ├── e78a59657e56380c96b654ec7337b5f0f78b0a0f.nq.gz
│   ├── e8bb7f52b18706d1e4b0323b7ba9a1c8a72e0d9f.nq.gz
│   ├── f6642d94c891021ab99b480d696952f3453dd34e.nq.gz
│   ├── f7d7d23b1a75c5f97e87ec5a220323a126fcfb2f.nq.gz
│   └── fe880ffca687b96199e697e4f5f3ba1d75003dd5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── ac9ad1c39976e0e6c06f0bbe8522ed6eb8d97620.nq.gz
├── filetree
│   └── ac9ad1c39976e0e6c06f0bbe8522ed6eb8d97620.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 75 files
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

[BurntSushi/fst](https://github.com/BurntSushi/fst)

---
*Parsed on 2026-11-23 by [repolex](https://repolex.ai)*
