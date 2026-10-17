# Repolex Knowledge Graph of pyserial/pyserial

RDF knowledge graph data for [pyserial/pyserial](https://github.com/pyserial/pyserial), parsed by [repolex](https://repolex.ai).

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
rlex download pyserial/pyserial
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a5c48d445fbc1943d4fabf8d9090a50fda3172fd
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a5c48d445fbc1943d4fabf8d9090a50fda3172fd
│           └── chunk-001.nq.gz
├── blob
│   ├── 010b0ceeab1ead2321ee07166c83a597c487f404.nq.gz
│   ├── 0e8f60160525f545ff5e6540e4ed1ddcb0fd8e36.nq.gz
│   ├── 0eded9a5b64c5f73c42194caddd7f8353259bf61.nq.gz
│   ├── 14e171a416d821722d1a0f87760c83d286cb15c4.nq.gz
│   ├── 157f4702b84922555c8d9a171bab3695e07b5060.nq.gz
│   ├── 1839c834116bf142e80c21883ae306f82d420e21.nq.gz
│   ├── 1901d77a9c04d2a28dc653f0f40e8f416cab2e40.nq.gz
│   ├── 1b21598ced0b9b505a66e1680a10f450082e0818.nq.gz
│   ├── 216658bb9f446de1017a46ed251badb2bb132b90.nq.gz
│   ├── 22390cc78ebea3e9c361c39cf76516c6066f7df2.nq.gz
│   ├── 22805cc3e84215b898636f83484f4eb8bff71267.nq.gz
│   ├── 27b049e4daea8d2f8d86abb9253b229324b3cd0b.nq.gz
│   ├── 2e666ca7258faf228a4ffbcc24e9796ecf39ade7.nq.gz
│   ├── 2f43ff388db15b0b34b05b7ab2ac1a36c231b71f.nq.gz
│   ├── 339b0f275b952b6dee7e53665d655427e543b001.nq.gz
│   ├── 34fb51a6ff6d972002d7896df5325241eadb40f0.nq.gz
│   ├── 38226293d186d493c7af708fc371fab6c543981e.nq.gz
│   ├── 3c575f50f23681529b60fc8d645618671b12b7bd.nq.gz
│   ├── 42660dd3f052cd8c182c8997c174acf8b0d1ed2d.nq.gz
│   ├── 443c9377c84e99009e5ae9d48d5febbfaf502b24.nq.gz
│   ├── 4546e5f10e029d5437208ccbfb67171a1de63c8c.nq.gz
│   ├── 47ca7155394f1f163f4b617a2b88352695e3a8a3.nq.gz
│   ├── 499be92e0add1e0fc9a734111ceb2a9e056b1d7a.nq.gz
│   ├── 4bb60a199bf12e97aff66b0f2299d5e1d1ef423c.nq.gz
│   ├── 4e3647a838e796b9bf8f85b3195f346d1f45fa3c.nq.gz
│   ├── 4e50bd2fb69ed69d9bc05cdc0d11aff2d81665aa.nq.gz
│   ├── 50d4f172aa9c6c106271bbc32030b7dd7b89f858.nq.gz
│   ├── 57db144b59570d5c40b5e273c5857739e6507971.nq.gz
│   ├── 5900198a54845029a6c8dc4f3a1f1dffb7430ea7.nq.gz
│   ├── 59ca8f1724f8c13b29e14ec5b319f6ef289bb655.nq.gz
│   ├── 5bf8e606c0c036ff929233dc2b1a53142b8511d7.nq.gz
│   ├── 5cde5c49051b5ebea851ab4f5fd3bdcc12aa278a.nq.gz
│   ├── 6022eeb92cf78d762f87d70324c90104603c71c9.nq.gz
│   ├── 6606ff7bf743bfaba0d5cdd95bafd395dace8c2d.nq.gz
│   ├── 6ad8022c3a63dd05e008a6012df54c7254544a06.nq.gz
│   ├── 6e37b8de9b002a7f64e1113e2a32acd14dac4d4e.nq.gz
│   ├── 7104b190340806f8b50ae0fe245aeacc0594bf8c.nq.gz
│   ├── 71e98bf4d0facffb99affc1a5a918c000af8eff6.nq.gz
│   ├── 7db883ad4c93a10db1ed247ecb6e6e868e66a500.nq.gz
│   ├── 7dbe2a6828c0c83071fb6c598c2158cb72d716a1.nq.gz
│   ├── 7fd45f46eb11b8ec36fb51bb5643832d959a4820.nq.gz
│   ├── 81c924c02624060d933a30336dd236a331fa9012.nq.gz
│   ├── 82d0fbc70568f907857815804f5e17e458a5894d.nq.gz
│   ├── 86717f41f1c86ed03b5610c746c99c8877124fae.nq.gz
│   ├── 86a6556ee0f05f4bf7cd24d630de44753c1c1124.nq.gz
│   ├── 8790801ac72028c972bcb91dc83bb13a14f63f94.nq.gz
│   ├── 888f89f9b6c818f60f4299b5d1101000256682a5.nq.gz
│   ├── 8aab3bda1e02217796975a7690bf7bd022fc29d1.nq.gz
│   ├── 8ab65de7f17f8d601cd0391284340f019e3defce.nq.gz
│   ├── 8e63fc1716abe390344be87a5eb86c804a84b032.nq.gz
│   ├── 8f2b440d8edb433440480bed2dfc6e934fa37757.nq.gz
│   ├── 90d5ad4198966550cdc6c8bd583844ff6cd15edd.nq.gz
│   ├── 91a71fd041c9490d9f0eaf249e72515834c63698.nq.gz
│   ├── 9abd10885d56ea096333aa12e8c111dc858b9b36.nq.gz
│   ├── 9e4f7c496aaa22da236f0ec58ec2cde5939a83ae.nq.gz
│   ├── 9f0a41b9a14996161d2e1c8ffefda8f3fa3d5d60.nq.gz
│   ├── a243d428bc984b8047b64fbf9e0567ba0777a646.nq.gz
│   ├── a534f16934a214e38b81fe65441a6a46a008a368.nq.gz
│   ├── a98b2fe7173069a3fe08c4dd913bd7385aebe9dd.nq.gz
│   ├── ab0dba09df81da315fca1cce965658e5c8e99cf9.nq.gz
│   ├── b8112a529e4df71ad671ca1510e15410d269e98a.nq.gz
│   ├── bd0a2e63b3e4d29c8cdc68b9de4e112aac5a7e33.nq.gz
│   ├── bd7db77894573c10335e8c3b53870a53a780e8ad.nq.gz
│   ├── bf17fa521c28b9143a177e53157b08ff57c3a651.nq.gz
│   ├── bf339cc451bbc89549d882feab9f05ab88cf4290.nq.gz
│   ├── c55ae5db2376ea48ce9967c7b255a56b59c3ae95.nq.gz
│   ├── c62d9182705d3d4afb41b989496bcbae1b7ce942.nq.gz
│   ├── d09e4eccd1588f034b3f9c1fd1d65c5cf1b4bd47.nq.gz
│   ├── d471a8e3470e6b701c4c6a68a5de47c1946ad54a.nq.gz
│   ├── deda665796386e196f3afe0e4efbafa135a6c6a6.nq.gz
│   ├── e458339aa6baebebaf9801afc7412a68e3060df2.nq.gz
│   ├── e533e4d4d5bfce59d39fc5c996fa845cc6b1d242.nq.gz
│   ├── e63910714c420e5c772cb9046e4d87fac6f8b9e5.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e918f67d38416da8eb7607159a969d0e17761f5a.nq.gz
│   ├── e97e58bdaf1c6aa21213cf66d4efb886b34494d6.nq.gz
│   ├── ebeec3a5eee15afda83253e4c1918498adf33bbe.nq.gz
│   ├── eecc2a1133ebee24c56577e1e06011f1fe76a2cc.nq.gz
│   ├── f09fe9bb8668be13caedbd9f9668758e32899998.nq.gz
│   ├── f0b6983c6121afa108c361cbc448ade43713981e.nq.gz
│   ├── f19b9d537ce17927fe4236a0c1738b659352fd27.nq.gz
│   ├── f208a399420cc9b444bd7b99448462a549bc0e65.nq.gz
│   ├── f3ee9fc94ba16e38b87ea2d2ea02fb6bf5a9f081.nq.gz
│   ├── f66db14fc6d0ef7133acd2170bedb3b1399b3bf8.nq.gz
│   ├── f68746073f40c5b0cc0fe7ae87720a221e317236.nq.gz
│   ├── fb2f053e53ecfb381ebb68bd40005ea67ef19536.nq.gz
│   └── fb46005524cd0a7cfe0cfd77a0d0f44e507778cd.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a5c48d445fbc1943d4fabf8d9090a50fda3172fd.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 95 files
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

[pyserial/pyserial](https://github.com/pyserial/pyserial)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
