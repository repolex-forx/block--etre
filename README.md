# Repolex Knowledge Graph of block/etre

RDF knowledge graph data for [block/etre](https://github.com/block/etre), parsed by [repolex](https://repolex.ai).

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
rlex download block/etre
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b6a89fcc477f24e5752387b22f9328fb52e1330f
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── b6a89fcc477f24e5752387b22f9328fb52e1330f.nq.gz
│   └── repolex
│       └── b6a89fcc477f24e5752387b22f9328fb52e1330f
│           └── chunk-001.nq.gz
├── blob
│   ├── 011669fe6de7c9f747aadde5ce6ecd059767e658.nq.gz
│   ├── 0138a9ea0d5fa2e85df98b5b3d290374fa291351.nq.gz
│   ├── 02dde0b909acc1da18409955b634e9607cb69983.nq.gz
│   ├── 0bb938d00cc8e447d55131dd59fa0ef8865f74dd.nq.gz
│   ├── 0cef1384eb8ace171d19e201f5e863e0f9b497b3.nq.gz
│   ├── 0de60a1666b25b57168622422ce5f3b79194495e.nq.gz
│   ├── 17374754d8184c151f2bc3c706ffa960cc1aa167.nq.gz
│   ├── 1951582d510cb769ea7e5b6942a78772f2bcac06.nq.gz
│   ├── 1994b3c510ab8bef95ac0da241558479bee9832b.nq.gz
│   ├── 1a21e90fd751fdceeb5e5219b1d52514e382ca75.nq.gz
│   ├── 1dea9c4e31978fb5f84e0ef35d817e2b13476dec.nq.gz
│   ├── 207674656af742c427525812dca5833f751bd61c.nq.gz
│   ├── 21b0f4e4e7ac90a4a9ea4c18d69a35f2d8599058.nq.gz
│   ├── 25f8409110f2b8c67a7658b2c66c6634568aef70.nq.gz
│   ├── 276fde9a042d12f0dead30827755f9e7b72200a0.nq.gz
│   ├── 2cacdf326048b3c84ba891943ff12b83dc1ad694.nq.gz
│   ├── 2e10935be101b62ab303ebb10ee487c422eb7c24.nq.gz
│   ├── 33b7ae836eaba9702faa42fd6128f4c121a85c68.nq.gz
│   ├── 36047db1aca4485c7050666387c8f67e831404bd.nq.gz
│   ├── 3979928ffe48fa39f056948d83b4858ac8ee7649.nq.gz
│   ├── 4338b2dadf092f2761636e833dcc1a6181a6dc28.nq.gz
│   ├── 43b4e844e6e437f5e673325cd41424d20b7a28e0.nq.gz
│   ├── 43fa3a1b71ebabb4098560ce7c27a67cf0cd6910.nq.gz
│   ├── 468216524f30f4aa0c0021a40008b0b2130af120.nq.gz
│   ├── 468bfdf06383904d2677ea6131a28cc6f759f615.nq.gz
│   ├── 46be4825da83ccd35e33dbc9f72cc5c7e8305fa6.nq.gz
│   ├── 488eb582cb180ac000c8af9b04af955a7510f915.nq.gz
│   ├── 490274b7653b6816d4c3d32e7332c33569f5c921.nq.gz
│   ├── 4a46f93c398cacb4697bd019a22b521b372f2fb7.nq.gz
│   ├── 4d30a59fdb7bb6b367b952b5cc8702f0b020a9a0.nq.gz
│   ├── 4fb9525133a772220bdb31b01fecdf8caa3f84d9.nq.gz
│   ├── 526a8dfd56d711d2a0b676cfc225106ad653615d.nq.gz
│   ├── 58037e19ffd988c0361fec39fc358376491de80b.nq.gz
│   ├── 59bc1df2785385cf231dc87cbc6f93bff28a6931.nq.gz
│   ├── 5bd8409ab4f203d202f1816c2cd6bb5f2788db07.nq.gz
│   ├── 5c279da79534f56fa93cb0ff1ceedb35cdaa7241.nq.gz
│   ├── 5d99ee2532e4475d17511dedc9d0fd41ac6a8e49.nq.gz
│   ├── 5e49c31c673e0ff86f72f242c83f1cae9fd162ad.nq.gz
│   ├── 6920ebb0141c2c2b028fb3c824ff7101da3a6dfe.nq.gz
│   ├── 6abba67bd578b2b797d24a4e0ff3e8fea75b3eea.nq.gz
│   ├── 6fc9db95b6e6494c26c2bb6c2e5ef393f61d8b8b.nq.gz
│   ├── 79ddbd76278cc6a915c6d4c72eebe188b7754400.nq.gz
│   ├── 7d4de02b39af16d5ae4be5b3ed90a987f33a7baa.nq.gz
│   ├── 7e452723a7240afa6918a6b83050833b46316a79.nq.gz
│   ├── 7ec888f1cddf4d995e162d5efec76f95b23296a3.nq.gz
│   ├── 8016a308b2d5cfc94324b58e5998b6fe77085a7b.nq.gz
│   ├── 817d131e5ab30df5a5f7166a0c8658c31122c72c.nq.gz
│   ├── 824372f2a9418f2a4aa6e64fa58b8665b0741265.nq.gz
│   ├── 891ae0c4ba641a6b112c4b4266b91f2086ce3a67.nq.gz
│   ├── 8a11ed973283cad135e6ed236025c74269e2596d.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 9246fa0c2f09b10923d71521ac5a1253ec9e9bad.nq.gz
│   ├── 9260e1be356995b6a51ad0e1b9a7ed6c1f3c35d1.nq.gz
│   ├── 94569f7adb84ff179a3f8b7a8db5cb1ea16f09ca.nq.gz
│   ├── 986cac746d30a5c72daa54efdba0bebe4dc6b3f5.nq.gz
│   ├── 989d878521620c9f520ed014904f15a4ce31864d.nq.gz
│   ├── 98e33a4b9a1d056c471f07be1d20627b6325fc99.nq.gz
│   ├── 9f0618fbd42109797bca7f34349407a6f86a635f.nq.gz
│   ├── a233d9ed03d2d160da3bacd93499cc81736ca1fc.nq.gz
│   ├── a423fd1b3bfee73d1b1ffdffeaec1aa16d199c54.nq.gz
│   ├── a51140f02431582e4a746a9687b00a9cbf3d38d2.nq.gz
│   ├── a7f1b0ef458d8487c073bec9adaec3125e7bd9ac.nq.gz
│   ├── a960905908abb15919a652731646797e23b6fcf1.nq.gz
│   ├── ad4d516c133b3f9aee23d7ccbf029390959ceeb7.nq.gz
│   ├── b06fb6167239da025725c2d75c7f2e472fca7e67.nq.gz
│   ├── b551efff4a3dec2a805ded6c779ac2cee789fd4e.nq.gz
│   ├── b572450cc30d3a8b4abb69185e403aac84d8e5f4.nq.gz
│   ├── b597fec7b61c5e8873c60c2cbe948be95c158c7f.nq.gz
│   ├── b8f4a4003859f89d77e829f82ae3897040f81cd3.nq.gz
│   ├── bfa253162f08edc82e157759dc284ce16d1ccd13.nq.gz
│   ├── c1dc0fb0d42f8f2ccefb4090a07c391daf28f633.nq.gz
│   ├── c2282d6264cc3c933ad1e5676ee08ba77405a3cd.nq.gz
│   ├── c6918f4ff2a6f9c3c5b5145ab607a05a1eba7d84.nq.gz
│   ├── c7de9a83ca364a06cafd90c52a724493efb26131.nq.gz
│   ├── c927d8a0c1cb9be38db8285721b420fe56735598.nq.gz
│   ├── cc251dc102903ded223df493cba5e45f38df099c.nq.gz
│   ├── d0c41aabfc0319bae25bb443ebaee04c31edcbbc.nq.gz
│   ├── d3c6afe4c1d96b00f1528a4357cc12957071857f.nq.gz
│   ├── df99500ae3eef07c371bbacf1b686be16d512e34.nq.gz
│   ├── e21d1858cbe7b5b6905371c6de680d6c1b6d4d53.nq.gz
│   ├── e328944e93ed86f82ee5e522395d143aeb4784fc.nq.gz
│   ├── e730cd5f2300107daab3d4dfe50e2b28c0b46d9e.nq.gz
│   ├── e9d73eb2be11ffacab9d59c930e050ab6d1f19d6.nq.gz
│   ├── f7794f4958f31b56ad55abe5e83344ab61d82708.nq.gz
│   ├── f78324f63b6473f83cc154c3acbebbbf4f8e66f8.nq.gz
│   ├── f822ea5b79d188ec4e3e010bbbfa471d6043d69f.nq.gz
│   └── feb960a71a891e4af932f6b75fc65579ef62dcaa.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── b6a89fcc477f24e5752387b22f9328fb52e1330f.nq.gz
├── filetree
│   └── b6a89fcc477f24e5752387b22f9328fb52e1330f.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 96 files
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

[block/etre](https://github.com/block/etre)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
