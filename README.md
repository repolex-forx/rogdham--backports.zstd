# Repolex Knowledge Graph of rogdham/backports.zstd

RDF knowledge graph data for [rogdham/backports.zstd](https://github.com/rogdham/backports.zstd), parsed by [repolex](https://repolex.ai).

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
rlex download rogdham/backports.zstd
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2372ea098b7b87430293c8344888e01ad3d1d04d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2372ea098b7b87430293c8344888e01ad3d1d04d
│           └── chunk-001.nq.gz
├── blob
│   ├── 00a9eaf2f99c1aef7e008477582761d5d5dcf277.nq.gz
│   ├── 0ac7bcb4ddc41657f438e7e54df625d5d15ecc46.nq.gz
│   ├── 0f9ce5869a256e9f3ff40e9e8069698dcbcba4a2.nq.gz
│   ├── 121695295c16e89c2263c3eeeaf020420c2fd7e9.nq.gz
│   ├── 13984650e38175760c497708a3c330d3ed88430f.nq.gz
│   ├── 18794c8ded00d13be23a0083f01e7db5b54455cf.nq.gz
│   ├── 19d4fe9cbcb0a3ba97b21370c4fb55d1d07fbfb1.nq.gz
│   ├── 1a20d08b33be6cfc670f0f5bd26ebcbc03bf2a98.nq.gz
│   ├── 1a7d9aa645271a5b09e2b0a06087d39208f6483d.nq.gz
│   ├── 1afdf3b3a773d7d1e12c3671ffd3735a18b42233.nq.gz
│   ├── 1fb578ef80b8acdf713d1525b6090b652a555335.nq.gz
│   ├── 20cf39097c68baa17cc566b64e76d34ebf034044.nq.gz
│   ├── 23fd2168ae57388e73dee24451e82cad5840ec86.nq.gz
│   ├── 24745941b089239fb8584bcd729cb8fe91963b8d.nq.gz
│   ├── 254d5f692cb8cd03f91f94d0fdee1acd7e5be2a8.nq.gz
│   ├── 2d5eca2f28eb06544e828bfd5fe01e13b3838615.nq.gz
│   ├── 3054c5158197d60e751cc4560360f6012169ef2c.nq.gz
│   ├── 378eba4026d381c2cf68ccbc500abf9e75f9a47f.nq.gz
│   ├── 3ba13e0cec6cbbfd462e9ebf529dd2093148cd69.nq.gz
│   ├── 3c6d02a378bcdd61bba370958fd4568845c81e65.nq.gz
│   ├── 3e86605deefcc1d0373f63a2e1dc10532f7a885d.nq.gz
│   ├── 42274e9188f5540754458c268b61e062bdc2d8e2.nq.gz
│   ├── 46ce950433ddf64726630e2e6ef679d8eefab116.nq.gz
│   ├── 4b16ecc31156a512db4a28fe272e5339994a4538.nq.gz
│   ├── 4c7eac0b7eb674f508fe40e8ad1e0f2b184fa533.nq.gz
│   ├── 4ed74cc48d9a91689280608f954e52150f5536f5.nq.gz
│   ├── 512fa149e6cfda08642420ce6e17cabe02893c92.nq.gz
│   ├── 5482f778311cc5021db01d2305af4e3e3b3196a2.nq.gz
│   ├── 573e10359b7bd271c2da4c9674a643b8e738ae41.nq.gz
│   ├── 5f0abb2d6b22fff9aa93b68cdddcd26ea68a2b62.nq.gz
│   ├── 5f6f14afd74a6ee9e9c415a4a83b93724fd12957.nq.gz
│   ├── 64ca248fcf78014aad1dd142f7a91a1d4c6ab0e0.nq.gz
│   ├── 650a810036632f49cc708028a20fc42aa10c56a1.nq.gz
│   ├── 6c6be07a16e0826b42a18cce2fee87e1c7cbdad2.nq.gz
│   ├── 73e510fa7f5ddd8d8412464be43b305dbfcd9d91.nq.gz
│   ├── 740a879173967229f27b84977817580421effeef.nq.gz
│   ├── 7418391abadde5e7a9af8d0de59de0a70bd56249.nq.gz
│   ├── 75f2b20e06d77f7922bfe8aa1d2bc1b54facd125.nq.gz
│   ├── 796bb790fc22c57d54ce41e5d7f768a624d70104.nq.gz
│   ├── 804755914a76d9e86c7bb1826973c1c2804fee8d.nq.gz
│   ├── 80f26fe6f03439f21c39fac4f29dfc561dfd3e94.nq.gz
│   ├── 82b03cf39d919d9de05866b4f7cdf1dfe47e6eb3.nq.gz
│   ├── 83a75a182187e39742955433ea6e7e0b5d88474d.nq.gz
│   ├── 868d99efc3c4a317b869b9bfc30a0ccf857ca73e.nq.gz
│   ├── 8a94a43e8e2dbe05b3b80ae94de7231ae6d62c05.nq.gz
│   ├── 8d832f00acbd6c4e9adea1991cd9e64a04b56210.nq.gz
│   ├── 901d3744ca05fe9f9c6522d183f287a903f8d997.nq.gz
│   ├── 979126ef5e37ebd46762c76439e9b4e77431103c.nq.gz
│   ├── 9aa2a8b55e34e427eb8e32d6b9f4528e51e0686a.nq.gz
│   ├── 9cf5bcbf1f5edc979d34886e0584ecb01707f871.nq.gz
│   ├── 9f367d4e30440f75d9a32c035713b281f3fbb26a.nq.gz
│   ├── a377e0b8d5b749e14bd45c7d27d936b662644fab.nq.gz
│   ├── a50e4e9ca7167bbec4db48d2904e5bdcc219670a.nq.gz
│   ├── a8aa714d5b55103827ce2f5fcf21ce9925c3216d.nq.gz
│   ├── ac21d7a1edd2ca1177f071465ca141ab405b1927.nq.gz
│   ├── b53ab76b4e544f00a323bde27d635864a51daebe.nq.gz
│   ├── b805781837c5e9b70990238a196c601c49ed8979.nq.gz
│   ├── b8237251964983f54ed1966297e887636cd0c5f4.nq.gz
│   ├── ba2c891cc723bef94f3ad6ccb6dc278e7a1fa14a.nq.gz
│   ├── bb2aef5951b08dcb071d36a6c5ecb151b08f0b84.nq.gz
│   ├── bb9345373e9701b01f16b70844445dfe1863abc6.nq.gz
│   ├── bbc43bfce3f17b157e034b1c93c211ba54afd223.nq.gz
│   ├── befa17a03a8bf6292cfe46b2f3b40bf41cff1e72.nq.gz
│   ├── bf21765ddadfca1143ae60eb3248774c45098524.nq.gz
│   ├── c29219d0215904382ab5d6303f7382444a409cbb.nq.gz
│   ├── c39bd1cd9b244764bbdbc72652b189fe68e99835.nq.gz
│   ├── c457888f3cb2f4a99519dc59b39affd63969f45b.nq.gz
│   ├── c4bc57438cb3d93f22e8b9906c918e552f5b6098.nq.gz
│   ├── c4f5a58a946de660c57f56050d4e7f35b8d5e2fe.nq.gz
│   ├── c833cdf9f934b08fc449da077efae44aa9a06f18.nq.gz
│   ├── cbc309b9dab5b145515dded9486888764e0aa726.nq.gz
│   ├── cf87233f0e2e938a9f2e7d7906844ca009416432.nq.gz
│   ├── d66ec8a1417112b5a26b1f79193245a953dc099f.nq.gz
│   ├── d773c9ff17bbd2866bf37a91555a6b6e862ff0eb.nq.gz
│   ├── d9ad0bee43452e2c28c7981ccd5fe3018a73c519.nq.gz
│   ├── e0ae136ccc53bccb57423d6b1bbfc9195ad36433.nq.gz
│   ├── e0dc85319dfad9261ddbdfa2576a14829dbff76d.nq.gz
│   ├── e25ac946edffe425ab4990043755019afa478c55.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7e90bb353728d0807cc6b71b4f7c4ffda3c83f6.nq.gz
│   ├── eb8bf03497dcd61cbaedb2348dceae2584e9b3f7.nq.gz
│   ├── ec126c36a605fe1b6da4a1d353d1371182a7ed7d.nq.gz
│   ├── ec960932e71ac18fe6a757f79c8071e3bead1796.nq.gz
│   ├── ed2f1270e321de4d28ded9519990b86cceef388a.nq.gz
│   ├── ee354c6a2248086356f3b6a2e1621a69c3cecf1f.nq.gz
│   ├── f735dd2173300681849f25e53afd71ccb95e5f8b.nq.gz
│   ├── f7c6cf170422c48ce1337a4c05843fe66a4b0bbf.nq.gz
│   ├── fd80d0b338cb816b8e02cecdfdd37a3ec784c5d7.nq.gz
│   └── ff6a41ce1e5a0e58c07a365a3662ac698953a2ea.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2372ea098b7b87430293c8344888e01ad3d1d04d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 97 files
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

[rogdham/backports.zstd](https://github.com/rogdham/backports.zstd)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
