# Repolex Knowledge Graph of zenml-io/deep-research

RDF knowledge graph data for [zenml-io/deep-research](https://github.com/zenml-io/deep-research), parsed by [repolex](https://repolex.ai).

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
rlex download zenml-io/deep-research
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b98b6c0a0a4c855219e69b8b833ea1ed84710046
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b98b6c0a0a4c855219e69b8b833ea1ed84710046
│           └── chunk-001.nq.gz
├── blob
│   ├── 04f0115dadc9c1ef1807bfc61a7de20c1fe04902.nq.gz
│   ├── 07aa1bc05f03eab65cb10de362dda7008e2d04ea.nq.gz
│   ├── 0dab88183a26decbd0de5d1fc1fd0cbf00f14a42.nq.gz
│   ├── 0dcde6fd950192c3e53e46a47191b4bea95797c8.nq.gz
│   ├── 0f172dec01ecaa9003e38b10270a8e2fad74cc7d.nq.gz
│   ├── 0f6f63b86a256f119e01c59d66c2f0b5d388ff70.nq.gz
│   ├── 10f81e0509a2212eadf8882052e86d3f4f9b8ff3.nq.gz
│   ├── 114166d3f4dcbf0f5b42b2dbf5dc1cd82d37df16.nq.gz
│   ├── 1183f71110c7e549084f75a56927805666029692.nq.gz
│   ├── 142c5c4dff16c018914c650be45fb3a1d9e9b0c9.nq.gz
│   ├── 14a89a3fadb3bffa4ffd6f4386f2bb6fe8a28384.nq.gz
│   ├── 190625ef5c0d1c2c036a918b72826c0a73be4395.nq.gz
│   ├── 19533c6d9c8dac618b29772bfc4b623183efc92d.nq.gz
│   ├── 1d9c286999ba9592e79a51b4293c171e6586c0d7.nq.gz
│   ├── 1efc1eb1beeb172690e5c0b591d83a74309b0ec4.nq.gz
│   ├── 21571c18fa43b83a0dde81b1fdd6dc3e57dac9dc.nq.gz
│   ├── 2222c0c69234ab6f00450e56bfd42cb221aa4a15.nq.gz
│   ├── 24ee5b1be9961e38a503c8e764b7385dbb6ba124.nq.gz
│   ├── 26abe2993898286fca9b527b2fada5a6f3aa7d40.nq.gz
│   ├── 280654dfb7af71ccec9973deeb0d6582ffb65998.nq.gz
│   ├── 3736f12db26df2d54561a71f268e829f4fd81d66.nq.gz
│   ├── 377b122211d342be292cef9c878822577b05932a.nq.gz
│   ├── 3afb075a2cb5e76165b62f845eeeea1180831c4e.nq.gz
│   ├── 3da5cd18bf5998def291d5a9e0c82cae7f632c54.nq.gz
│   ├── 40d298779b00fbaf57be2d826bfb7212810b60f5.nq.gz
│   ├── 40ddc9a6bdae68ad0976b8265eb314aff4b20983.nq.gz
│   ├── 4430c532845a3723da62bcca5853daaf1d0e40a0.nq.gz
│   ├── 463761026945fa1432b1ba78a3e5f67b2718176b.nq.gz
│   ├── 4a8e9269b8be0f5004022a692e7b2d62ee5fd51f.nq.gz
│   ├── 4b0d3268f3cf88dde292300ae9921755b5944318.nq.gz
│   ├── 4cdfbcc383c69884881d8cdb8eae0616403c374a.nq.gz
│   ├── 54d96af22c28cf41c41913fb90e2af501a379f23.nq.gz
│   ├── 54dfe3d82b30158a1e426a8fc26622cdfd1d8a71.nq.gz
│   ├── 559bf637af5d6a9cb5251574d9b53e1a4934fee8.nq.gz
│   ├── 5616ad3473c11ee5b2e98fde698a18185a74c4c5.nq.gz
│   ├── 589e69cf9c1e866cbba9929808e40b9dcea33f38.nq.gz
│   ├── 58b111b854be308f230fef688472ef6007c15f6f.nq.gz
│   ├── 5cee4054b80c4ab3456945ab8bf407182012fdcd.nq.gz
│   ├── 5ef2eedd6397e01cd1412ab1df1e9fc13a12a70e.nq.gz
│   ├── 5f1f187745cbf0d1526268b7f63de4e030c6675d.nq.gz
│   ├── 5f6d1a9e1a115bb222575f00ecd4f550b05daf44.nq.gz
│   ├── 6065d1e2fa8cceb36da969ffb0fe50431e9dcfa9.nq.gz
│   ├── 61e7616e85c6d04dd41c4656d759b8a8de3865f5.nq.gz
│   ├── 6330c120e4ea0c078e5aade9617829524fd41950.nq.gz
│   ├── 63aefd5ffcee158a467d6ee85e2a335c2636e05a.nq.gz
│   ├── 63bcb439859d9b8db83a239b455cf2fe15082039.nq.gz
│   ├── 64b12388d9ce41d0280d437999c7fe0b0c63a6f6.nq.gz
│   ├── 6555b6359e2f3d6fb306e1f3c8a0ce068d7ffaff.nq.gz
│   ├── 655a7fd323bbe97248c08513abfc9b40213b6563.nq.gz
│   ├── 6929a69857eafc4033fdf5ecc6e011b204428837.nq.gz
│   ├── 6c1004c30464e758cfe3db6ab7c10b64303a45df.nq.gz
│   ├── 6c1925f06e8d14bc9cc6cd88e65878c4b037f2d8.nq.gz
│   ├── 6d6766efe51d55291e8e38f9e49349d34f045c8c.nq.gz
│   ├── 6db5994d28e87903bb02f9b14a5cbefe1f4dbc0b.nq.gz
│   ├── 6e13d3976e5486047dd8ae43839b9584b9e894d9.nq.gz
│   ├── 6e731946e8aae8d32923910a2dd515e261b7bf9e.nq.gz
│   ├── 741206156070b075d649b54e93ead66f336b341c.nq.gz
│   ├── 74dcaa03f70d95b2773d5daea42396533995e8a0.nq.gz
│   ├── 7614861d51ee6a99f379ebcf2ff68979113f03d5.nq.gz
│   ├── 77cd77a64f5cfa6f8b428d41aaa98b5e5e2264cc.nq.gz
│   ├── 7a306b1c84da02a8b15f1199cf75b3aadce0eecf.nq.gz
│   ├── 7cdb0fe3f5626c919c9fe3f2186a15cea6c81d8a.nq.gz
│   ├── 7deaeea39229995f1c7500c5588773529192dd04.nq.gz
│   ├── 803a4bf363d36f9b0a3867d44cf70634e3ab0028.nq.gz
│   ├── 8068dd7f6e1d6b0d536a5b4f1f275900c3e430f7.nq.gz
│   ├── 80bb8ebb9bc352fcb6525a6a6a184ea7c82c9f7a.nq.gz
│   ├── 818727ebd649a2da7ef60381deb7a52ce9a0b783.nq.gz
│   ├── 8c0edeb3f9d8cfce12ed61895c21400c49586d88.nq.gz
│   ├── 8c2b68ebf7f484e301efb2198aff336febaafef5.nq.gz
│   ├── 8e84797e5fcd40bd5e4f7a928ccf057076d5c83a.nq.gz
│   ├── 8f185db4a4f0505b1ec3213aacb94398018307ec.nq.gz
│   ├── 91829251ed7a7947a87368129664527cb236c4f8.nq.gz
│   ├── 92907f00c157a782b213836a13b58b78a0ac1678.nq.gz
│   ├── 93c078a6bc7051bffb68184fff5bda62d20a7308.nq.gz
│   ├── 95e897733f42ce6fdb6996bf1b9bb861b9a30dd9.nq.gz
│   ├── 9674b4bf8cec677b9b0f42e6f2fbd06ef4684d18.nq.gz
│   ├── 990df8f723f3a8e72d983dc07816c17b32a1282e.nq.gz
│   ├── 996374c31a1038b86d5bf6f749e1478676273197.nq.gz
│   ├── 9b9e6fc2e47b31120700d1ddfbbffadcec9dd0d2.nq.gz
│   ├── 9c2e7a0497854d780a90305d60c68fa33f126155.nq.gz
│   ├── 9d7fd5da93da179e9bf62293149ae58ff2f3c56e.nq.gz
│   ├── 9f41b7c46eee84c7019284114f6ba2be85d2aad6.nq.gz
│   ├── 9f6111530400804cc4e8911c5a866805defce6f1.nq.gz
│   ├── a2c6f7dbce313f686935538e3a23331cad2df2ac.nq.gz
│   ├── a4eeecf2ce8301df1087e4ab7ea38447db5369f0.nq.gz
│   ├── a4ff141b8092e846719c45d4ea5914030acc088a.nq.gz
│   ├── aacc4b6a8e31ae2370469f9dced104bbfbbb934a.nq.gz
│   ├── ad7fb4a32bc702dbe9b718972794de1e31234600.nq.gz
│   ├── af142fe0f8b8769230a03d357635162c824010af.nq.gz
│   ├── af3ece273f8b92dae1afb840637434be762d45ca.nq.gz
│   ├── b098410cbf436fcc727e8054bb796a5243cdfd4f.nq.gz
│   ├── b1d21ad729b585093c0bd3988d6c47ef619fb15e.nq.gz
│   ├── b95ae5bbd922ecc94546120fe5e6d417339216bd.nq.gz
│   ├── ba205e4172c3686dd71516f45564dd3b9942b7f5.nq.gz
│   ├── be39dd6cd44fedc0c76d3f6147f40e2362ff602b.nq.gz
│   ├── be3dfbed40a254ceb641451519c895d5e3e3a34b.nq.gz
│   ├── bec903b4403b57b042935f62f3dd7bbc5cfafa44.nq.gz
│   ├── bff845162894d9679ae8b78d016b255ac33e83e4.nq.gz
│   ├── c276657efedc43251103ef01c28fe7004a396254.nq.gz
│   ├── c2dcf380dde199d89633136e25bba1f6518f8fb5.nq.gz
│   ├── c6b094b8751e1c5b544891a2bda1f39b13a09efc.nq.gz
│   ├── c959c91150ccbdb7dd22893683bb421a03f1536b.nq.gz
│   ├── ca4b3c8891943058bb17d59d24da49957c69c02d.nq.gz
│   ├── ce2560f9844d3137c241b84c5be8e49c1926230b.nq.gz
│   ├── ce88645db8e3572b1c0c3959f58a53bbe47d2509.nq.gz
│   ├── cea6729214fb744ab7670d6b9491b7d3663e0238.nq.gz
│   ├── cffa55ffe6a47af61ead8f0c7ddf4b612d2c4684.nq.gz
│   ├── d108628d2559459f2da1f47bbedb0ed544629326.nq.gz
│   ├── d31dec36b6cb1965621fb564bc60b49f99e3505f.nq.gz
│   ├── d4e93012ac50b41eebb0497499ba307d53fd547c.nq.gz
│   ├── d5db593a6b347714b7209787519b8f525b1d6328.nq.gz
│   ├── da10824c0ed097b76086e32e95a05d68ce1a8b92.nq.gz
│   ├── dc11ce22a92e91815cbcfee99b01ca6da2a5a8c3.nq.gz
│   ├── dda88c1a8da72c03c9e73569b75009fde8a91867.nq.gz
│   ├── de451cd87642252c9295246f8fceea5ab92a5c1e.nq.gz
│   ├── df64e54b2052dedae53a472e1434268e8c8dc721.nq.gz
│   ├── e00b6c894311336c8fe855498bf40274e8f3908c.nq.gz
│   ├── e3ff95c54cdc4c4c1b0fb8798ac8f37916b231e3.nq.gz
│   ├── e435e5ea180c55100237442b46ed8d00c20af09d.nq.gz
│   ├── e4eec5142deaaf742bb22a307d7570ab158eb78d.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e81e4e5dd18d2825bd1fb0c399882d4411d3d9cf.nq.gz
│   ├── ecf38349ed6c95e4502e79570a553c64025bd038.nq.gz
│   ├── ef8a7af0118ef73f137f9656a99c199e09462742.nq.gz
│   ├── f040e2170e9ae2e74b0c4b80511fcbde6752a279.nq.gz
│   ├── f23b459d68873e9e4008fe0be6a983b2996c91ae.nq.gz
│   ├── f4a99495dca6355141cf84a695287e016a26ee3b.nq.gz
│   ├── f4b12886c1611c7902e5874f8cbd167265a8ffb2.nq.gz
│   ├── f743e9a404aba2457a0d445d754dfda5dfaae62b.nq.gz
│   ├── f86d9ce405daa50cb350a8a906e0e8ada0793769.nq.gz
│   ├── fde336e670cc3c88a6429c97811e4d4efdcf1361.nq.gz
│   ├── fe5e7f2ac1d51c0deb8b2affe7298eb1a2d878f0.nq.gz
│   └── ff8de627d332853cad36d965c83fc6595c6452da.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b98b6c0a0a4c855219e69b8b833ea1ed84710046.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 140 files
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

[zenml-io/deep-research](https://github.com/zenml-io/deep-research)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
