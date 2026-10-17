# Repolex Knowledge Graph of joaomdmoura/crewAI-tools

RDF knowledge graph data for [joaomdmoura/crewAI-tools](https://github.com/joaomdmoura/crewAI-tools), parsed by [repolex](https://repolex.ai).

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
rlex download joaomdmoura/crewAI-tools
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 62f4d7efd1ea61ec11e5c0922eee01b444b6c6d2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 62f4d7efd1ea61ec11e5c0922eee01b444b6c6d2
│           └── chunk-001.nq.gz
└── blob
    ├── 000c81cec620719bc3a91a9c8da2441d0d3cefcd.nq.gz
    ├── 013d94cf39923df7b165c6325800c75738897099.nq.gz
    ├── 019b7895c1f90ed9c60bad015a7221c846868946.nq.gz
    ├── 01fdeee7d963a6520e34e0aa58cacf6f2209f313.nq.gz
    ├── 0278e5aa0aea5ab57b6966574a842c6bfac79326.nq.gz
    ├── 02e9b4cc2b04220de578fa2307527cc63ae28867.nq.gz
    ├── 05b174500646c34ebcac98ab5c591b26371d133e.nq.gz
    ├── 06f1abd56eea1e20ba381339ed9c146cdf2a48b5.nq.gz
    ├── 06fd3ce38d93ed896a0a5ed61dde8dd3aa391871.nq.gz
    ├── 0839719d70d4679d79d5d4007420b342196dfc4b.nq.gz
    ├── 0842e97eab22ee5a6bdef258897cc0bcc2b99a8d.nq.gz
    ├── 090684f48f016f1e056794aa26ae942c80def966.nq.gz
    ├── 09b076cc10a59d29479eacd1560cc73bbe45d76b.nq.gz
    ├── 0aa4b666c8df1ffe947583cb710fe271da2c224a.nq.gz
    ├── 0d0ec6935b79f293802946b9f2aabdb2742f8f3a.nq.gz
    ├── 0d4df60a73e3c2ce1bbcf40437fe824cfe642a78.nq.gz
    ├── 0d9735cad9beb1a0584a21103f6602dcb8834a6d.nq.gz
    ├── 0e285d136f94dbdba21df3f90523b38780549c48.nq.gz
    ├── 1015e408def0fe76707d77f8485d9120ae2239d0.nq.gz
    ├── 1096df0982fe0cfc89f36b9e3cb50c795e8a5a75.nq.gz
    ├── 11ca018e8d0d7244949cb4b26048f3d6004b2f47.nq.gz
    ├── 127169676b879741baf5fb40d270665b3d740d84.nq.gz
    ├── 131dbdc3f6b305d5ae6cc295dd0f6b0403b404c0.nq.gz
    ├── 141518f3bb786c6b66049be583292eae55853889.nq.gz
    ├── 174b322290ba62265685b2abf896709af108e85f.nq.gz
    ├── 18045e7f19a12093454629f2d8144c49894b71ae.nq.gz
    ├── 185b1988794ccdd61851a3036c9da362b24c5e10.nq.gz
    ├── 185e9f485a19838022f775140167d4da0006729c.nq.gz
    ├── 18d07c0b3d23be91259f181b9a1f4ed1c921c1b8.nq.gz
    ├── 190ef3fc35461c9f00544a917c8c835d6e04cee0.nq.gz
    ├── 1d1d2015041b3b4cfdb1f6ea5336fddf06839d4d.nq.gz
    ├── 1d4146fcb7c26a28ff72fa044e8f18df8b515b29.nq.gz
    ├── 1d8f3ffd8892e9f773876b96e7a15aec84b17442.nq.gz
    ├── 1e5e8069c436e2519aa80a875d4773f4c5fa96b9.nq.gz
    ├── 1e6f0d8c666ca25f3632da3ba71d601ff3ab7911.nq.gz
    ├── 1f96d452a104f3ea7ca91f83bfff5f617dc08afa.nq.gz
    ├── 23f15dd926fa7789e115fd9ab0736388938e9337.nq.gz
    ├── 25c71c934d9b2437b6024547683e7bf629a1a8c7.nq.gz
    ├── 262e79a69b722dfa00cb445a1d039feff7bfe803.nq.gz
    ├── 26ad9a15f13334a31c4acd13af8740b48de22bd4.nq.gz
    ├── 2712a6c69239ae8f33b127c5e7daa7c7a752c98f.nq.gz
    ├── 291fa8f82879b8cfed7801790bcc841de2604c39.nq.gz
    ├── 2939bbb00fe81ca185692a2a243211dcaceb769e.nq.gz
    ├── 295c687457ee6fc7fb04c427c751c9843b6715c1.nq.gz
    ├── 2994b918e489e81531ed6f2c221135362fe84d7c.nq.gz
    ├── 2b0bb968a70f7f1068321ae9660646429d0efb4f.nq.gz
    ├── 2b3e248566b84619aae7d424e3bcacd7c7d1d089.nq.gz
    ├── 2ccfa4eb2157904d374af57be11a5018f88e57e8.nq.gz
    ├── 2d54eb9702aefd8279377b4870e5e455cc8cefc6.nq.gz
    ├── 2e1528d139bf21fcc71065c5db0a3edcfe03ed8d.nq.gz
    ├── 2e4f51ca9c0282ced42c9cf36ce878c25a5a705a.nq.gz
    ├── 2e509ef4a12fba1021d2ca0f1d67723e9b781ba7.nq.gz
    ├── 2e76df8abe3b18241afd2c49e6059ea0947889ef.nq.gz
    ├── 2f5df23af674227086cb9ba66f336637c1242768.nq.gz
    ├── 2f9d6dcca4cf0693cf5ac1bcf71081814d9ce201.nq.gz
    ├── 3017f694fa6f74ec50837193ea8a47c76b8fd2d3.nq.gz
    ├── 30b78a3c4d9b7e953172b1d6716a71ec46a98544.nq.gz
    ├── 30c949932469be698a7cec9782bb75148eb0bcba.nq.gz
    ├── 31f2e697cdd0a3b6ac1356733a32767c3f3b0460.nq.gz
    ├── 3390b8dba7593d0723bc89381e9dfaf860744b62.nq.gz
    ├── 34f42e52e83565cc6cdbc2fa7dd3a7d7ce4b5686.nq.gz
    ├── 351cced922f5e77d4747de6fcdef22b295fb4588.nq.gz
    ├── 36300f7235071c0d2f0158a3f5b196138bd3c038.nq.gz
    ├── 37f4135612e59b679572311be0db21133fb99b8e.nq.gz
    ├── 382f6eae0136363bb6ae6875a86e4439eee23a91.nq.gz
    ├── 38bdab2a014884d215dd61ab5fe5db56bd08efd9.nq.gz
    ├── 39bcb62790460d6ff59ebeb8334981eaa0aade00.nq.gz
    ├── 3a0fe42b60e92c404ff1e2992f899ffee03608c3.nq.gz
    ├── 3a62c514637f37f3a5f5bb4a3da228f3b1698d34.nq.gz
    ├── 3aee6ef8897927336eddf06b2f9ff79b43a81ad5.nq.gz
    ├── 3d52ae3faf8b5234ca8f3898362de819aac24a2b.nq.gz
    ├── 3edb73f026c7c8b7b35280f1b7eccceca07f3ca4.nq.gz
    ├── 3fd3feca3948e576985970da0cbc4f936113f401.nq.gz
    ├── 4112aa500fe3ae24b0fef097060bb1b50af85d33.nq.gz
    ├── 4247ba7bb6587518576d94639e9f08be340e73cb.nq.gz
    ├── 424a19025879646730b1eda7d5b08fe9161e0eb3.nq.gz
    ├── 428bb6b52baa422be4b594598dded46be673d2bb.nq.gz
    ├── 48255e7b4b77067ec4dbae5e463d90b9f63d962d.nq.gz
    ├── 482c7c8307500ac62703b52e03e5eddc467a0614.nq.gz
    ├── 483f92588e94b0e25a1191f195541b4e041d2902.nq.gz
    ├── 4848d4c6b19b1da998326dbd6a3efdf3671a48a3.nq.gz
    ├── 49dad0ac7052c311f24afe8bcc4e007017863636.nq.gz
    ├── 4c858837c31f44189ac09cc091fe719a3d1898e7.nq.gz
    ├── 4c8d768a337e41f38c22b8698a6a2ba1eae57a16.nq.gz
    ├── 4df22ca5885a748adc5cf9bde7ebe8cf11c9ad18.nq.gz
    ├── 4e04e3a7d1d907c9d7c75be1e9acfa65eeb51884.nq.gz
    ├── 4e697cafebbd39fae2aec0adbdc5cb2f54a7a75d.nq.gz
    ├── 4eae2b11a4d0c702042b0adc0f5be968ea47fc7d.nq.gz
    ├── 4ec997152f2a98f38ac95aa611961b44945c0c53.nq.gz
    ├── 4f8747d2fe8620db8502129531f78768f6bc88bc.nq.gz
    ├── 4fcb1e0c4f2b0654d2b9f5b29d007fd9f3c8d06a.nq.gz
    ├── 51510932e92917a9ae051e9d975f90a1113c297a.nq.gz
    ├── 55db598c500864e95dd9b4d07953d42d3d64c4d4.nq.gz
    ├── 5635832ed2d7c4d3eaf468e6909e4240e0ec674e.nq.gz
    ├── 579dc8941b650915fe22455367eabab06eef99ab.nq.gz
    ├── 58ab4bbcc9313e4824fec792c8cb4d845d013eaa.nq.gz
    ├── 58fc5bca9022cb775f05d3d91060ded32d730844.nq.gz
    ├── 59530c8d8c7c562a655cb08a1e00ee5587b4832c.nq.gz
    ├── 596cb4d580c66ec1fbc714ab2001845871c45605.nq.gz
    ├── 5985b60f190f9ed2256662f335e980d7aaba754c.nq.gz
    ├── 5a2b27798f22f5fe7bc00bc962b0472f09109697.nq.gz
    ├── 5a6dad43b833d3a70cb0bf4af586fd2e3c476b77.nq.gz
    ├── 5c6b9395ec361332c9b8a35fbbbb02dde00a2422.nq.gz
    ├── 5dbd1df0b940f8d8e9d77ce5953ac01b07e4af11.nq.gz
    ├── 5e8a760ee09582ee56cf534f31fce39b07daa0f7.nq.gz
    ├── 5f7365c8aa706f891e0f005f1c67a701d12002cb.nq.gz
    ├── 615dc0849b8999d4a45bf5e342902f85e31b3a4f.nq.gz
    ├── 61f5d9c8c348cceabfadc9dd6299c09e6f84228c.nq.gz
    ├── 61fd63c8cd89fbc245338cd529bc609ff76d7799.nq.gz
    ├── 629cb2e877c092c88d518a035b6d3497a999b1ec.nq.gz
    ├── 634ba2863a5bf90f0192cf41138a1820a5e53f2e.nq.gz
    ├── 65280fe7b015c0c7f58be0554f7ec3542da891c0.nq.gz
    ├── 676fa4106dc5199347014f57e8ef49c21e465fe9.nq.gz
    ├── 6801f40656e5a75e83a01788e13944ae424caa26.nq.gz
    ├── 6a4a9e84f41f9126fc02ddf222933a26a6604370.nq.gz
    ├── 6a933c355a1bbfa917cdd76f376fc86d44f1dd32.nq.gz
    ├── 6ab9c9d527a8c6b3dfc8b80a3c2a5697c54d748b.nq.gz
    ├── 6c928ef3fd283a56d9d173e3be02667723bb3a54.nq.gz
    ├── 6da54f848fa330ecad2f8cabc276bc52f65988a5.nq.gz
    ├── 6da9dc8963b8211e91120608fe08492ebe4e2ea5.nq.gz
    ├── 6df658898dc89aa75ed2653979765713c63f2667.nq.gz
    ├── 6e0fd39e8c0292afa84e588fe0c01435989e4596.nq.gz
    ├── 6e8b48e3a9be5e6ac3e23468f0177f7b8584b664.nq.gz
    ├── 6efab393abc5e1e1b07605dfab78ee8b09f7a138.nq.gz
    ├── 6f3fd2d58bdbd8e39636ea097e18b688cab2022c.nq.gz
    ├── 707b99343a2cba1e8507612d24018b25f18f7875.nq.gz
    ├── 715e00804e677951c1afde7615f590965f63c919.nq.gz
    ├── 71b58131a02398ae2d7484891a3b19d3b46b1e75.nq.gz
    ├── 78011328c0f57f58f326fb039b8cc2e5b6d10108.nq.gz
    ├── 78c996964d6e2158f86dcc9198922296c78b6aee.nq.gz
    ├── 79a95e67809f44c63cf3321f290035a9deecb448.nq.gz
    ├── 7a4d2890a8a9188ede6794c185160e67d20de640.nq.gz
    ├── 7aa43b65d93437324b185b921288d3b01b8059bf.nq.gz
    ├── 7b8a154885baa679b0770c959e130ad84dee106f.nq.gz
    ├── 7bc5f298b44e03445a92399cc1274209fd83a6b5.nq.gz
    ├── 7c531273e9446005b71d91fd8525eaedda6921db.nq.gz
    ├── 7ddb38341a93e274233b60d7ae8a993504b8ed61.nq.gz
    ├── 7f0188bbb97e2db7d8a092dd531e830afbf2ed52.nq.gz
    ├── 80f597665ba1bc2e743e38c432da68f23e49d85d.nq.gz
    ├── 816e4015900a1ffcefbf41981b51062bc9ea3fc6.nq.gz
    ├── 81c3c529b2b87730c0e5980d42e19a81ab0e4638.nq.gz
    ├── 82f345a657b3d876f47a5669dc5d589129cea4cc.nq.gz
    ├── 8488f391ed62f85f3a536a13de03247cbba735c0.nq.gz
    ├── 8509c2d4283215a5249ce04c371874875810d383.nq.gz
    ├── 85be978946eb400257a4d0b03805672a42e46644.nq.gz
    ├── 85fe5ed6e485b7014f25f198124d0f83888c471f.nq.gz
    ├── 86bb42573b337f0be65c64ee51cc80a4f1b2c6ba.nq.gz
    ├── 86f771cd080ce0cf5e15df0e836dc0f1abd520eb.nq.gz
    ├── 87f3824342c3aa28496ac5a44f06fad67f0d36fb.nq.gz
    ├── 8b84613b45e3449b23d12f8ddf6204ad75f9799c.nq.gz
    ├── 8b9ca5225654c679ce61478fad03a35caf86b7de.nq.gz
    ├── 8bfa1073a8e9420f7d877b475d841c5b257c5a32.nq.gz
    ├── 8d08b2907e590b47f40a85aabc17c6d1911e2fba.nq.gz
    ├── 8e2794dd12f9a6a4ca24b2edffb19793034faae3.nq.gz
    ├── 8e602f3769e746115e082fcaac13acb5ac582cb7.nq.gz
    ├── 8f65e78e59dc73dcd0638420b1e24f99f14ffa63.nq.gz
    ├── 903c84e247eb03c2c04908d2e402547778391316.nq.gz
    ├── 914ee947fd07f96e612e9deacf144f48d422ba89.nq.gz
    ├── 92e8ec5b2b615aeb2b8d20013fcba487dab5ffec.nq.gz
    ├── 9305fd1a33116ed27646476dce4ddbfc20bfea77.nq.gz
    ├── 932867c9085244e65f127252c4c0f218405b3f83.nq.gz
    ├── 95426468305d8ddbc0b45a6c1d38c731d86c93d3.nq.gz
    ├── 95559f2a714d5d77259a16c92f75578d98de7d7d.nq.gz
    ├── 955ba6a39a801bf9f6a70d7c0894e4f0889f6e7b.nq.gz
    ├── 95d2deb424832fb06535d3136a27272f50e5c816.nq.gz
    ├── 9a33bade942261f8747591a24aa4fe9bb5b83cca.nq.gz
    ├── 9a8feb94c74be47619fbd5ade9bfc97216a71f72.nq.gz
    ├── 9ab1f29ea182e9d055016ce01b618455f6323d17.nq.gz
    ├── 9c99fe8d416e13c3e135fd6c7c5ec3bce802fb07.nq.gz
    ├── 9d99fa01b2beb261cb581e2455f2f6debdcf9063.nq.gz
    ├── 9e02f410b3698978787cad4fc6c20a9d86ab42d0.nq.gz
    ├── 9f0765f2d8460fc59c542e431f289259da3f207e.nq.gz
    ├── 9f11611ab8fb0a9c4188251e47647c41794f8310.nq.gz
    ├── a019d9e151a49d10eaa862430a72afe2119a5f2b.nq.gz
    ├── a2037e95157a47f0515d53f321dbe53981c477ec.nq.gz
    ├── a2571b94b61a53dd61077791e775f777b50d4cf2.nq.gz
    ├── a4bf5d8eda1a38ee1022e83b6b5b57058d2bb523.nq.gz
    ├── a4cd21044032a162e2e3d109bc8a67cc2138f41e.nq.gz
    ├── a4e2a259e65a365362b246340ba035aee55398d6.nq.gz
    ├── a633c22c7130cb93a4ee4bae4e9f5abc961880e5.nq.gz
    ├── a662104915bd67e8a0b54a91547d4a99ec861af1.nq.gz
    ├── a66586f6f7a2174ebc2ce5a83fd5ea4d2f9f38f4.nq.gz
    ├── a86c75b450612c97142e1894f54b15381cbc0fe3.nq.gz
    ├── a97cf29f484ce812c9eae21ca4d2fad7a4d90cb0.nq.gz
    ├── aa73d63d5d8003372c3662d270f38c10fd4cc826.nq.gz
    ├── aa88dad50cec0bfb36657ce58df12f577f88d990.nq.gz
    ├── aabe0ffbdf5f153c6485fb4ffd02f4bacc82a7d2.nq.gz
    ├── aaf68c291fc7a26b32c8076f45294830cc638ea0.nq.gz
    ├── ab0cbf44b2533b73a54ae3adabfbc04e865fb1e8.nq.gz
    ├── abc1a45f5b18942c98def11de861c6b521cb4810.nq.gz
    ├── ac8084d3f7503ee9531ac77365163544a7897f3d.nq.gz
    ├── ac95b1df50dbaf273ebbb7105531a1bd148a2f80.nq.gz
    ├── acd6bbe77c62fbf45e9ddcb65d6c05f9445c7141.nq.gz
    ├── b033c2071c9f7e6123c3baf523642461d57ae61e.nq.gz
    ├── b0e2ef7b0e58d73c87db83a61fd1f414d083e7a4.nq.gz
    ├── b1f799872c264b3d5048af8a1f7930b2a9ce2038.nq.gz
    ├── b2d27907892503c267703ecadaf810b339a72bbc.nq.gz
    └── b2d691a619a4be4702c6a100fdc667ed35c79ee9.nq.gz

7 directories, 200 files
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

[joaomdmoura/crewAI-tools](https://github.com/joaomdmoura/crewAI-tools)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
