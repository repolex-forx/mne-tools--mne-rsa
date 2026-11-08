# Repolex Knowledge Graph of mne-tools/mne-rsa

RDF knowledge graph data for [mne-tools/mne-rsa](https://github.com/mne-tools/mne-rsa), parsed by [repolex](https://repolex.ai).

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
rlex download mne-tools/mne-rsa
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 808ff4bbd998895270ae75789008963038cc0267
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 808ff4bbd998895270ae75789008963038cc0267
│           └── chunk-001.nq.gz
├── blob
│   ├── 00a71bd4e13ec19773243bfc8be6e6ff8b451e8d.nq.gz
│   ├── 00c6c977b9640c8fa7899957ee54c6dd35583e14.nq.gz
│   ├── 04668aaf2a673cde8cf5dff4deed503e5096535c.nq.gz
│   ├── 0490c1235564c376361d3547322faeeb6718954b.nq.gz
│   ├── 069464821dbbb3a7fdea4463e4ef3fa09c4a81f6.nq.gz
│   ├── 08305113369201fc09c38c8765f6f19b920b20d7.nq.gz
│   ├── 0c3a30eabf42bb6d1ff22bfce592e381b8939425.nq.gz
│   ├── 100c22837a7c2ed37bef6efeff9612df8532e744.nq.gz
│   ├── 10fde3645990777df2acd1b3a75a8fbc97db7b7e.nq.gz
│   ├── 11b72d544ce484f8f101a6cdf1bde2657154a799.nq.gz
│   ├── 14e529029f56de2dba66be0d94b0b63d5906a2a9.nq.gz
│   ├── 19aee97ba9b7502d43f3c40837d2f98d2249c2a4.nq.gz
│   ├── 1dd444eed731c15eeb1cac9a8c96d409090cd63d.nq.gz
│   ├── 1e44439e38b1c40c416032a3853e6367c85bbf5d.nq.gz
│   ├── 1edc0acc441f21f8ac2c404e4fa5265ad460355e.nq.gz
│   ├── 29ea79bb7bfc5d7a21661fb9ed530fe5fa416d56.nq.gz
│   ├── 3328ed9979dded278a809b16a2f462d4de2c0fa5.nq.gz
│   ├── 37ecae37cee8c1617c2b47baf9aafdb3524c498f.nq.gz
│   ├── 38b2c653ece7679c7d975d959e091c651bf35b40.nq.gz
│   ├── 399257a7ec7c91f9df945fe98c5d610ff5a1f6b2.nq.gz
│   ├── 3c5261eca6cef9d8e452223b504fefeb512ccaef.nq.gz
│   ├── 3c86154911c16a9944c53aeb23983dec621e97cd.nq.gz
│   ├── 46a9b3dc0e2dfdf157cbad85463d63eb5b0cf669.nq.gz
│   ├── 47d3e27c667c738a558f8f5a92780b8dcff50a16.nq.gz
│   ├── 4d6887303f84f9a36beb577390a34df48165e8ff.nq.gz
│   ├── 4fecc72de0980d4865df5ef24be17a3cbec6505d.nq.gz
│   ├── 504bd7f40e296d5b0831c33db0b9b9621408605b.nq.gz
│   ├── 51519e55ad1899148ae41c659dc17c86ca9daafa.nq.gz
│   ├── 52e9863e6cef3e1bcf6272fa06d522ea2668cac1.nq.gz
│   ├── 549f377a2a270e28acd4447ef3450a4912317b29.nq.gz
│   ├── 55edbcbfb56c8055b062712a9dd1084ea7e29f14.nq.gz
│   ├── 5670e8346ed51fb056c7db72a2f84509adafb7b3.nq.gz
│   ├── 59a48064d68cf6d81fdb1ba894827c847456f9c8.nq.gz
│   ├── 5e75b12cc913bcd70349b9935789e0002ff8c7c7.nq.gz
│   ├── 6119ee7b662dd69e37de7bbff1d708929736d5e7.nq.gz
│   ├── 688fb0a6610ba535705293cc2d1d1ac66419e26b.nq.gz
│   ├── 68b28fa1e32b930db07c9d3e346fe0bdaf2057b2.nq.gz
│   ├── 6f9a281fe7b3825ac27baa662f6588d31b911a0f.nq.gz
│   ├── 77586a11340775f3f84ee415e3da8cb0f1fcab8b.nq.gz
│   ├── 7af9de8755f499e243869cba85eb3fdfbfeb6ee5.nq.gz
│   ├── 8ab04d7c3926d97050dd9119cbdb91ab6ddd3e45.nq.gz
│   ├── 903b5f67d09215e25f42fc7ebe279e05731dbf3c.nq.gz
│   ├── 94a8147a545492c2cfbd8fcb864536db48f60ea3.nq.gz
│   ├── 94c3aa0e7ad31d559faecb45115f3f813924ef5e.nq.gz
│   ├── 96ff41ead849b1f9efa5f7fcdf21e6f4083014ab.nq.gz
│   ├── 9b07604749c1457c0cc45d376626f9f9bfb4b4ee.nq.gz
│   ├── 9f8309ebb4c26208cf5eecfea8b0364a90a7f3bf.nq.gz
│   ├── a7e141d205e374e6d5ed22e70d0b28477ea5bff2.nq.gz
│   ├── aa65b0cb7ce644538ab1c17c1f02ec310e8dfe70.nq.gz
│   ├── ad1f6b9b78693fe080364bc337814798cb5aec90.nq.gz
│   ├── adbd275ccc17623fa7dc2efc4fc757f1b2e13cbf.nq.gz
│   ├── bdde24208c99afc71bde6f58ea4fc80212db7971.nq.gz
│   ├── c0a4b670d624924b802128b5c16837257be9ae15.nq.gz
│   ├── c1aee2bc68d637be0220d46e650e0158ec90e2a4.nq.gz
│   ├── c6fa37835c6793ae8869f8c8bfd04cc64cb565f1.nq.gz
│   ├── d1b2b5e46661dfebcee8d41d17c3b1249821df7e.nq.gz
│   ├── d68ffbcdcc4bf33385a12b73482d41326da4e81c.nq.gz
│   ├── d739b5602f5a3167719f0ed30071bdb1e0ec8276.nq.gz
│   ├── d9e6ba884a7faef1e158589cad2f0b28c571609d.nq.gz
│   ├── dc5b169b6b5d735773b42a64ea9fd8bb73f8d403.nq.gz
│   ├── ea4fecbfc6c86fbc0e0701906d0e6450a2cbaf70.nq.gz
│   ├── f58f84676ab3c33d5e7b58901fb806d282ab19b8.nq.gz
│   ├── f8e9ed64dca1b5f985d8197ac558b0acde3c39c6.nq.gz
│   ├── fa7e5272960494d8fc4b4ae2cee48ea747d1db5b.nq.gz
│   ├── fcb7e512812626390dde23bf9e99a8675035b7c9.nq.gz
│   └── fe197da955b8c25efbe2c53224852d116505a320.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 808ff4bbd998895270ae75789008963038cc0267.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 74 files
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

[mne-tools/mne-rsa](https://github.com/mne-tools/mne-rsa)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
