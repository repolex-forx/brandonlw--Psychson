# Repolex Knowledge Graph of brandonlw/Psychson

RDF knowledge graph data for [brandonlw/Psychson](https://github.com/brandonlw/Psychson), parsed by [repolex](https://repolex.ai).

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
rlex download brandonlw/Psychson
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4522989aac27aada5f522675b33a2bde63a13b30
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4522989aac27aada5f522675b33a2bde63a13b30
│           └── chunk-001.nq.gz
├── blob
│   ├── 056838252174d4ced257a9817e2fb83799ad586c.nq.gz
│   ├── 0796caa4fd851be0dea14e4bfbe736d564bdf46d.nq.gz
│   ├── 0f80b6eaecdba5026594799e402bf7e075c24348.nq.gz
│   ├── 13695be3d47bc30495c093bc7b138e6793ed7711.nq.gz
│   ├── 310fd665901bee991e0090dd9280cf58e89f368e.nq.gz
│   ├── 34d88198f11796d394a91d0d985f5e6df0dd69bb.nq.gz
│   ├── 39036cbdee61afa9d0b415febb8de360888c6be6.nq.gz
│   ├── 395e86b0505bc85c2183b5a272f8565e5f08f001.nq.gz
│   ├── 3b40859af7972947266a0b1763f85e9f41700d10.nq.gz
│   ├── 3c83f2ec2442d62cd81b2f937263c9c7661603fd.nq.gz
│   ├── 3e1967b83d872831f260bc1f75b0f883472dc9fe.nq.gz
│   ├── 40c4c9dbd73cb4fafdd55643ed7c1e810d2dbe72.nq.gz
│   ├── 44862ff42ef9e053998e7bae69ff78a9c2171425.nq.gz
│   ├── 47ca1416d38e36fe9d9b34b3fd1c4618bcdcd900.nq.gz
│   ├── 49c8ac52598022d88291c1733bd78cebdf4dab4a.nq.gz
│   ├── 53e33d64d505c8f21328ed3da46128b204957e59.nq.gz
│   ├── 58262a1fdc6609fab0c0bf209af1e99e6c6fb831.nq.gz
│   ├── 5ae362e38b62f178551e47c1c90bfe7c7cd80406.nq.gz
│   ├── 5c45d9adb9f880f2d4207ae7d2418d107b949631.nq.gz
│   ├── 612a796f2faf403929eb595aff1b552fb6be9b7a.nq.gz
│   ├── 672238f4eae5de4b9aa115277e369d857a55a318.nq.gz
│   ├── 6bfee1ddee681c9aa046fa95a070e1e0955c0aad.nq.gz
│   ├── 755e71074bb6d4c138a2569653cf786dbebea3e0.nq.gz
│   ├── 7b718e321ac555d4624727f92075688ce1bc578b.nq.gz
│   ├── 83165a39df6d7ce090f8b33cd1639cf336ce8f94.nq.gz
│   ├── 8e15646352ec1d9a84bbc6504ef6b46e16bf7823.nq.gz
│   ├── 95c98ee71a85012fc6f58e280bb6fcdd1be953ca.nq.gz
│   ├── 96d2c259b9b62fe9c1d5c3dc8f0846508c8d0304.nq.gz
│   ├── a157f121da7f9ec2db74734da33325607071aa2e.nq.gz
│   ├── b42cc93415df616367c2f932e87676a09ec3d13c.nq.gz
│   ├── b89eb11f8676599f9e19289d2977103cde5f52bf.nq.gz
│   ├── be504e77b9088dd2d8ae14c70b1f43b53144e83a.nq.gz
│   ├── c51311bbb559625411be1742dbe10f11aeb82f46.nq.gz
│   ├── cb55d50fd37f4e3aab671d4563c3c175104a7044.nq.gz
│   ├── cfa5516516654fcf01ff43f0883d0ae06cf51996.nq.gz
│   ├── d41bf9a9cf6d9a80632fc77ea9097037340aee00.nq.gz
│   ├── d5d1c4cf5649aab8383edfdc86440f0ac84c6a11.nq.gz
│   ├── ea676f2ec5e4a7cd646ecb1ce6580d9bf5224884.nq.gz
│   ├── ea78385a79124918dbb3c8aaa9cfc28a9bf73a70.nq.gz
│   ├── ebb10c6356fca49358599d2e6f1e291f1451c54f.nq.gz
│   ├── ed6d52ab4e9c01b70788d53d7a39e776019a9130.nq.gz
│   ├── f2f12787884a2d20a1e8fcd1a37891717a6aa73e.nq.gz
│   ├── fc21a156a695ec95364185cb8421c6c74f9b9168.nq.gz
│   ├── fef047d397abf7bb1c8378482a77c283163529d5.nq.gz
│   └── ffede2079f6ea1d9d49bbddf93d0aa79f4a5e776.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4522989aac27aada5f522675b33a2bde63a13b30.nq.gz
├── issue
│   └── issue.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 52 files
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

[brandonlw/Psychson](https://github.com/brandonlw/Psychson)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
