# Repolex Knowledge Graph of gyscos/zstd-rs

RDF knowledge graph data for [gyscos/zstd-rs](https://github.com/gyscos/zstd-rs), parsed by [repolex](https://repolex.ai).

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
rlex download gyscos/zstd-rs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 229054099aa73f7e861762f687d7e07cac1d9b3b
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 229054099aa73f7e861762f687d7e07cac1d9b3b.nq.gz
│   └── repolex
│       └── 229054099aa73f7e861762f687d7e07cac1d9b3b
│           └── chunk-001.nq.gz
├── blob
│   ├── 0651fc17b89fb7d70ba1c9804b9b11bd99f47017.nq.gz
│   ├── 1190b3c62159e85f739d7cdd1e53f21c318f48f2.nq.gz
│   ├── 128e0754cb62fb7badb9141c80fe8ba8b6064d5e.nq.gz
│   ├── 16f6316e3a563fe36e4ca07875a537cb3598955e.nq.gz
│   ├── 1843dc1063ac8e310fdb7419fb3921fc68425734.nq.gz
│   ├── 1a45eee7760d240bfa8ac1989088e0349169f264.nq.gz
│   ├── 202c68cfd490f2bd0f44855523a1c9d696e8f014.nq.gz
│   ├── 20f286d671252fd3e6bc4a10ed3781b56b948b95.nq.gz
│   ├── 276b59bca971a862c8742124702fb16b5c763d2a.nq.gz
│   ├── 2ceef823174c19032936acf90681cba9dc62d0ad.nq.gz
│   ├── 2d3bc3eadf21d4fffef372665862c382aa2eed81.nq.gz
│   ├── 320889fbf22438c8619c28e7657e45825ffaee2b.nq.gz
│   ├── 32473ee6c7aaa711cdcaf517c0caaff44f354331.nq.gz
│   ├── 34d55153cd6cbb9ad8b375de4774dbae84d775f2.nq.gz
│   ├── 3d485f862916c31ea5cbe66f58c8b058e8e47aa5.nq.gz
│   ├── 408e1633b8e4a352236f8438e6681e2f90df0afa.nq.gz
│   ├── 4214bbd535448cf902ef543ad3c54459768f6ece.nq.gz
│   ├── 444a52de04ec63a4d1de751986f1a95294d3e8f5.nq.gz
│   ├── 45381ef0d1c257c04fb461d578eb6265b0f51846.nq.gz
│   ├── 46e078649579292d1e817406c5321e66c5bfde7d.nq.gz
│   ├── 49190f7361f0c347604d90c7ee76e209f4f54348.nq.gz
│   ├── 49942efbd284ac5f8b1941baa3b887287efab569.nq.gz
│   ├── 4c2d168ffa7010f92787aefe5d6368ef21c3640e.nq.gz
│   ├── 506b8199c30fa506b6bbf9c4cd06e2f5f1a1cf0c.nq.gz
│   ├── 51942d1e6b87db42ef13f28c06c8d9b4b8040aa6.nq.gz
│   ├── 570c09ea109838a311abafe659e506f5e7e35548.nq.gz
│   ├── 58086ec8b9ff7344c9bf3aa80cb50dad66b8d83a.nq.gz
│   ├── 601d8d617156c5dda472b78799ffe7d2e8cf5155.nq.gz
│   ├── 61e20da9fa16196f2f81e935acc95b52db8e49c6.nq.gz
│   ├── 6205f2b300dd563536e135868e1d07342834fbde.nq.gz
│   ├── 64ab478168c497342695e19c472b4ec4c6ee228b.nq.gz
│   ├── 682b8e0bc857c8a7e0a9b79465c9472e2663d4a5.nq.gz
│   ├── 6c798c21495fde9a754fec8dd08fcd05738578c6.nq.gz
│   ├── 6d6f86a78f4eceb2f414b802fa65d0900bb91564.nq.gz
│   ├── 6dfea3aa03006ccf6fc5818ec05e93ff49111ceb.nq.gz
│   ├── 74bd761ea062ee879da3ff84ed1d13c9216e6fc3.nq.gz
│   ├── 75ab6c15e96814584fb3f2551b8564a390115970.nq.gz
│   ├── 7753401d6281d7e33291aab983b670b62bf54d06.nq.gz
│   ├── 7eb782c508848c4e2b95b1aa63185095b0bcb7d9.nq.gz
│   ├── 8097712dc03508e59fc1184cba087a8b5d55103c.nq.gz
│   ├── 80c6b9c9d7c5091f6bc1d9753976bbd3460f30bf.nq.gz
│   ├── 80ee6af0da5e1aa2d37eeb3ae8c05c558a4ac320.nq.gz
│   ├── 8469e5a7a233e5faa8acb94aca280de10683af26.nq.gz
│   ├── 8c443f936adaef6985da32d01343a4c087e90902.nq.gz
│   ├── 8e893559235efa152128f9db280b44f7020634dd.nq.gz
│   ├── 94612a1b32abb22616fc3b276a2f5f2952fa3e20.nq.gz
│   ├── 986da3f01805f285dcc3961844437e1e1427f257.nq.gz
│   ├── 9af43c11d9f68e7312d03138e7eaf5bb2326d0f4.nq.gz
│   ├── a067bf04f1583482af5fb5cb8236fa290ce30155.nq.gz
│   ├── a0ae70e93e438ee7af9dfe12488106e45aefe952.nq.gz
│   ├── a146701434f7086df76ca8d15de8d386697226b5.nq.gz
│   ├── a2b7c66b5034cb07e5e585f17e12fad2a449179d.nq.gz
│   ├── a7a10aaf5f79996a25b22ce4cddbb3d2ab469bbe.nq.gz
│   ├── ab3130fd7aeecd4a5f6a3755bc86f15cef474770.nq.gz
│   ├── ad896d9aee3fe2fbf2ce2b69616c8498536586ef.nq.gz
│   ├── ae48626050a421e23892b115274ea064355896cc.nq.gz
│   ├── b125bf80795ed373d148f6993853e65d7a1a28b2.nq.gz
│   ├── b27fc3b98400e249acee078e02aa8afabd0ced8f.nq.gz
│   ├── b5a1fd1b14bc161fe87446aab734f72d9728bd4b.nq.gz
│   ├── b72ce5637f83ea2595926d06fedcddafcbee2680.nq.gz
│   ├── b750262eeffc8e9db731c29eb1ef96a584e7671a.nq.gz
│   ├── bd16ee95641310e2696531c2315b7cbad961eb8a.nq.gz
│   ├── c783bb9e8ce9e6399ba9fa674cf4036d719c79b3.nq.gz
│   ├── cba3e8f12905171c7804ced5516cba3e886836d9.nq.gz
│   ├── cc186c0744eafef58d2de0d7fa33948dede0bb1c.nq.gz
│   ├── cc2b660778b1b0704c7089994883a511a9aac908.nq.gz
│   ├── cf6530d5a5428fabee567f72aff1a9c4603255f4.nq.gz
│   ├── d3c16a3effb2d64c27fc018a203a88b9c6d8413d.nq.gz
│   ├── d9416b2a6e57d683656b3af8ddf4dd7814136685.nq.gz
│   ├── d9edf373231592a10cfea8d487b90e6b07c0222c.nq.gz
│   ├── dee13500878028e207bc1438789931532e9ab675.nq.gz
│   ├── e107bd823a0d73e069ea7a042d8fe813de2c073e.nq.gz
│   ├── e7d81c9fdd0711277aee8eb92344a9558ad65b1a.nq.gz
│   ├── e8067083f6aa6619d48ad66be9e610c7d9b761a3.nq.gz
│   ├── e858ec9459c7793fa8e818f4d7176ac5daa22cd4.nq.gz
│   ├── ef1a78108eb0a55525ee45f0758766a2adc934a9.nq.gz
│   ├── f22ef7b2f205632db10d3b22e09f502fa0dd0d49.nq.gz
│   ├── f433b1a53f5b830a205fd2df78e2b34974656c7b.nq.gz
│   ├── f6b69cd069ca2c831a67bce306ae8830c214f1ba.nq.gz
│   ├── fa10a192c6b72636463263e416062ef2d7b42b82.nq.gz
│   ├── facdb65b4c8b561478aab49451d7134c2cce4629.nq.gz
│   └── fc26e347bd6661706d8ecac690fa65d7f3cfb123.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 229054099aa73f7e861762f687d7e07cac1d9b3b.nq.gz
├── filetree
│   └── 229054099aa73f7e861762f687d7e07cac1d9b3b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 92 files
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

[gyscos/zstd-rs](https://github.com/gyscos/zstd-rs)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
