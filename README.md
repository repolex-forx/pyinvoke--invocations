# Repolex Knowledge Graph of pyinvoke/invocations

RDF knowledge graph data for [pyinvoke/invocations](https://github.com/pyinvoke/invocations), parsed by [repolex](https://repolex.ai).

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
rlex download pyinvoke/invocations
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── da97d736f919390a9e53206a217f5119422b7946
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── da97d736f919390a9e53206a217f5119422b7946
│           └── chunk-001.nq.gz
├── blob
│   ├── 0713c9981ef24a83140f9295379c7e1955c1709f.nq.gz
│   ├── 0d165752ce3be0783067a8cc862abf2e2e9e0405.nq.gz
│   ├── 0f45d06d38035d9521eb580c2f393056d7a6d6ff.nq.gz
│   ├── 10e0dcedd556981a2ea6c21acbf7763731992e07.nq.gz
│   ├── 18d210570dfa4b1e0333b443eeda37b296491c30.nq.gz
│   ├── 1fea14869b02204f04da1580000fe086a250018c.nq.gz
│   ├── 276ad5cf2f1f4608ccd243bfd9559740d76cdd3b.nq.gz
│   ├── 2c7392cd6a9ba5be826ce4e857458f165198f8dc.nq.gz
│   ├── 31f1b176ae15c699df0c38e1aad350fc736a0dfb.nq.gz
│   ├── 41ab9cc4aa97c2e45cc2230edc2b8cf1d5d0bf3e.nq.gz
│   ├── 42c7db4408458945b8ca0911b9feec120b434948.nq.gz
│   ├── 48f0360fbf2cfb2f9dc21429cd5eb9454a773311.nq.gz
│   ├── 4e9edab4dc2665f3b9adef9ddffd4fe543abdd6f.nq.gz
│   ├── 53d45fc50a59e18d03bbc14e8f33c454f4470c54.nq.gz
│   ├── 56234a5630ccedcb8b8dbb7a0ace95f3bc790a5e.nq.gz
│   ├── 5e2c75bda0cdfb1ecba6e074e5d223ef172c1e05.nq.gz
│   ├── 6153ec32ebd96c2d689876badd6d060c9d8a52ad.nq.gz
│   ├── 64ae6a5c0f408df50a0860b0bea6e3c6c4399282.nq.gz
│   ├── 663d938748442188007743b240637b8d58a4de25.nq.gz
│   ├── 679dfafeedff58ef00c177bd257829d369031663.nq.gz
│   ├── 6bcfec22b97aa78f0e3cc28847f32aad8d430d47.nq.gz
│   ├── 766f72ee6e773acc8f137b5961b59923adc95bea.nq.gz
│   ├── 793f5241f696b7dda6a29d6341e7eb649b54afc4.nq.gz
│   ├── 7f3f9b7a9293910140dc98b6b60dff758af11665.nq.gz
│   ├── 96e9b9cef641814e4e19ee40bd76168f91cfd64f.nq.gz
│   ├── 9bf7f5892b11917597363309a16dc5d23436bbd7.nq.gz
│   ├── 9df4d6b1b29a4cbf1287fd44db657cf9705e001b.nq.gz
│   ├── 9e528d2f5ef3c29ce63bdaf410ee82b953979cd8.nq.gz
│   ├── a1b474543a00c68e8d7b89bc6b298eeb2f5cc0c3.nq.gz
│   ├── a33252e97164d4b6d3776e64450b153f398b4609.nq.gz
│   ├── b0199d99511215ee51b35075a07bfc955de379f5.nq.gz
│   ├── b3468c47a754de1a47057d137d07c5241355802d.nq.gz
│   ├── b35b13256d26d1352e47693f1adf965c7686cf42.nq.gz
│   ├── b3bb1d351211170463b6b6cbc1a527cd04f6f3c1.nq.gz
│   ├── b59c7e6461583a9f7732796afa03274adcf3e811.nq.gz
│   ├── b67ee3d73d3bdd58d33a48484bc488fee0b7ffdf.nq.gz
│   ├── b6a507089ae9f9f6c4e79222d5bec32fa1a1f266.nq.gz
│   ├── bb47c45520beb002e65fd9d6fa059ab2167423ab.nq.gz
│   ├── bbe1b2df3025c8d071015c17ab7216826053c1ed.nq.gz
│   ├── bbeb6e3179b7013f912bf6a52df5b7d977bf028d.nq.gz
│   ├── c49f776447a3a40742701240ca44d3ee7ead6700.nq.gz
│   ├── d48ad9b7bc97badb22b5c9e5eb3bc3d7e5af8b43.nq.gz
│   ├── da9c516dd744b6c88dd8c91f58f7bcf8f7e8341b.nq.gz
│   ├── dc30f3a51dbf5d9d43e716f1dd743cb5b5f75dd1.nq.gz
│   ├── e0b2dd0987fdfa306f598fea9dcedf4eea19b59a.nq.gz
│   ├── e54dd2159d45b175f356816065c662f5241cf12f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7438deb9a23f974a64dbb5871a718db727ca525.nq.gz
│   ├── efe340c828934187c949f99b1d59c31e708696f8.nq.gz
│   ├── f15507981f6ff58ec200bcc12785b081f5722172.nq.gz
│   ├── f51e190a1f80179a16cf70af1071077cc4806b97.nq.gz
│   ├── faddf81d77508ff0e04c5dc55aa876d1ae2d76cd.nq.gz
│   ├── fbff26798ed6f3733cab226781b2ac8a2c978e2a.nq.gz
│   ├── ff034599b4f1e4ced053bd2ba158778f645176e8.nq.gz
│   └── ff5354b95f2744c5a16f7e9e921105707cbbba66.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── da97d736f919390a9e53206a217f5119422b7946.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 63 files
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

[pyinvoke/invocations](https://github.com/pyinvoke/invocations)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
