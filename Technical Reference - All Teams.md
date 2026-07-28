# Technical Reference — UNDP SDG Blockchain Accelerator
## Cohort 1 Teams (M4 Submission) + Cohort 2 Teams (M5 Submission)

**Sources:** Debugging & Testing Reports, PoC Submissions, Technical Architecture Documents  
**Extraction date:** 2026-07-28  

---

## COHORT 1 — Milestone 4 (M4) Submission

---

### 1. AFRIKABAL

| Field | Value |
|---|---|
| **Network** | Cardano **Preview Testnet** |
| **Wallet Address** | `addr_test1vrlazhaxp3tqmddw6wg0rn593zgl5z6vfda7982evs2qwdg6mvhm2` |
| **TX Hash 1** | `20b44b056f1537bfad20b4857a5f9ce05c679a3eed54c82d0ca6459de6cc17ba` |
| **TX Hash 2** | `32dd4dfcf4e3c44417d212e73b135f23b2265e38fd38600eae41229f9ad733ab` |
| **TX Hash 3** | `c8038ef332543dd72c5309cbe444ef288a6edb3d8bdc778a8137c9c6871c7178` |
| **TX Hash 4** | `feed2ef46e9dc926d7556d81ef981eb454ed2b1fb1dabea2e67ccc95686215a1` |
| **Blockfrost Endpoint** | `https://cardano-preview.blockfrost.io/api/v0` |
| **Tooling** | cardano-cli, cardano-node, Lucid (TypeScript), Blockfrost |

---

### 2. ATLAS LEDGER

| Field | Value |
|---|---|
| **Network** | Cardano **Preprod Testnet** |
| **Contract Address 1 (HEX)** | `106c8c2497ab7173c16a389f9948aa798a22d2d476e1785b0706dfa7af534b62ad660488` |
| **Contract Address 2 (HEX)** | `108c22570eeb82089ada1539e4709841e3d3b740fde3577ad700080e90b19bd26b60b05` |
| **Notes** | Addresses derived dynamically via `validator_hash`. V6 milestone-based smart contracts. 16 test cases all passing. NestJS backend. |
| **Tooling** | Lucid, cardano-cli, NestJS |

---

### 3. CLADFY

| Field | Value |
|---|---|
| **Network** | Cardano **Preprod Testnet** |
| **Wallet Address** | `addr_test1vrs7yfg6slh9dct4q3595a9u3l3ldda7hhg9a3wg9pd2sqcsufnxc` |
| **TX Hash** | `42099f8e21e0b4c6b4777fa590bafee0c77444b6ae57a0bc13ed980a6d9fb849` |
| **Tooling** | cardano-cli, cardano-node, Blockfrost, Plutus |

---

### 4. CREATIVE OPERATIONS

| Field | Value |
|---|---|
| **Network** | Cardano **Preview Testnet** (→ Mainnet planned) |
| **Live App** | https://reloop-eco-drop.vercel.app |
| **GitHub** | https://github.com/kootie/reloop-eco-drop.git |
| **Tooling** | Cardano JS SDK, cardano-cli |

---

### 5. GENIUS TAGS

| Field | Value |
|---|---|
| **Network** | Cardano **Preview Testnet** |
| **Wallet Address** | `addr_test1wztsa3xlr60hhv35d5ek2afq3kml7h9ku0j9pkzuswrfcfce9ln58` |
| **TX Hash** | `e51fab47be03f4b4c081d8891e19afbb2b49b7bc7e6b7c2d4f88ff339e1a9576` |
| **Script Hash** | `970ec4df1e9f7bb2346d336575208db7ff5cb6e3e450d85c83869c27` |
| **Explorer (TX)** | https://preview.cardanoscan.io/transaction/961a3f7fff6090284af9f91ce7937fa8fcf48fe9dc5e9 |
| **Tooling** | Aiken smart contracts, MeshSDK v1.5.11+, Blockfrost |

---

### 6. GRINPLUS

| Field | Value |
|---|---|
| **Network** | Cardano **Preview Testnet** |
| **Wallet Address** | `addr_test1vz3dfpcaxs384dtgvm6r7rgww3ypq9mu6sat363mhuha4qgugf5vu` |
| **Demo Video** | https://www.youtube.com/watch?v=SjiWvvYmXAs |
| **Tooling** | cardano-node (Preview Testnet) |
| **Notes** | Batch minting/tokenization. No TX hashes or policy IDs published. |

---

### 7. IOTA ORIGIN

| Field | Value |
|---|---|
| **Network** | Cardano **Preprod Testnet** (→ Mainnet planned) |
| **Wallet Address** | `addr_test1wrdzsldt65nfpsy3e7gzfmfhstuwm3wjz5qxyt8e5jn0jegzlz7z2` |
| **TX Hash** | `306f36a5332040da394a1652ef792b9214f92b60fc46e201a9f33d176a0d1245` |
| **Blockfrost Endpoint** | `https://cardano-preprod.blockfrost.io/api/v0` |
| **GitHub** | https://github.com/Elizaproai/rwa-cardano-launchpad |
| **Tooling** | Aiken v1.1.17+c3a7fba, Blockfrost |

---

### 8. KARBON LEDGER

| Field | Value |
|---|---|
| **Network** | Cardano **Preview Testnet** (network_id 41) |
| **TX Hash** | `ba00af4ba57d0cddcac13386494edaff23d44f4f549195975ad7a066b9e735d4` |
| **Policy ID** | `68d6e7d81446bb1b72ef42759185bba6e686fc3111eeb9e9af6bafbe` |
| **Explorer (Policy — mint)** | https://preview.cexplorer.io/policy/68d6e7d81446bb1b72ef42759185bba6e686fc3111eeb9e9af6bafbe?tab=mint |
| **Explorer (Policy — owners)** | https://preview.cexplorer.io/policy/68d6e7d81446bb1b72ef42759185bba6e686fc3111eeb9e9af6bafbe?tab=owner |
| **Explorer (TX)** | https://preview.cexplorer.io/tx/ba00af4ba57d0cddcac13386494edaff23d44f4f549195975ad7a066b9e735d4?tab=meta |
| **GitHub (contracts)** | https://github.com/KonmaORG/carbonica-ledger |
| **GitHub (umbrella)** | https://github.com/KonmaORG/karbonUmbrella |
| **Tooling** | Aiken v1.1.17, Plutus v3, cardano-node v8.9.0, Blockfrost |

---

### 9. PLASTIKS (M4)

| Field | Value |
|---|---|
| **Network** | Cardano **Mainnet** (Conway Era) |
| **Contract Language** | Plutus V2 |
| **Node Version** | cardano-node 10.4.1 |
| **Notes** | Smart contract ecosystem on Cardano Mainnet. Deployment scripts generate script addresses and policy IDs at deploy time — specific values not published in documents. `sdNftPolicy` and parameterized `policyId` used per validator. Preprod → Mainnet rollout pipeline in place. |

---

### 10. SOCIOUS FUND

| Field | Value |
|---|---|
| **Network** | Cardano **Preprod Testnet** |
| **GitHub (GoPay lib)** | `github.com/socious-io/gopay` |
| **Notes** | Cardano integration configured but still in early testing. Automated payment smart contracts. No TX hashes or contract addresses published. |

---

### 11. THALLO

| Field | Value |
|---|---|
| **Network** | Cardano **Preprod Testnet** |
| **Contract Address** | `addr_test1vpcpquku64qz3ltmhjfn8ya3p2pykfp0cnk95vfh85aet4qe9drpy` |
| **TX Hash 1** | `1d383c67574f42ba15d59ad16c2fe3df928061ef6dcb` |
| **TX Hash 2** | `b590b5f6a899ddd497b28ce93cf40fc191af0fbb36d0c` |
| **TX Hash 3** | `f0e66024dbb5c5987b6deb6233c7c05a8ef5c5cfa614` |
| **Explorer (address)** | https://preprod.cardanoscan.io/address/addr_test1vpcpquku64qz3ltmhjfn8ya3p2pykfp0cnk95vfh |
| **Explorer (TX 1)** | https://preprod.cardanoscan.io/transaction/1d383c67574f42ba15d59ad16c2fe3df928061ef6dcb |
| **Explorer (TX 2)** | https://preprod.cardanoscan.io/transaction/b590b5f6a899ddd497b28ce93cf40fc191af0fbb36d0c |
| **Explorer (TX 3)** | https://preprod.cardanoscan.io/transaction/f0e66024dbb5c5987b6deb6233c7c05a8ef5c5cfa614 |

---

### 12. UNICORN.ETH

| Field | Value |
|---|---|
| **Network** | Cardano **Preprod Testnet** (testing) + **Mainnet** (read-only / production) |
| **Supported Wallets** | Yoroi, Nami, Eternl, Flint |
| **Staging App (Vercel)** | https://giveth-dapps-v2-git-testcardano-general-magic.vercel.app/cardano/giveth/donate |
| **Production App** | https://cardano-general-magic.vercel.app/cardano/giveth/donate |
| **GraphQL API** | https://impact-graph.serve.giveth.io/graphql |
| **Notes** | SHEN token tested (policyId truncated in docs). Uses native ADA/token transfers — no custom Plutus script. Transactions confirmed on Preprod Cardanoscan. Also integrates EVM/Solana side. |
| **Tooling** | MeshSDK, Blockfrost (Preprod + Mainnet) |

---

### 13. ZENGATE

| Field | Value |
|---|---|
| **Network** | Cardano **Preview Testnet** |
| **GitHub (backend)** | https://github.com/zenGate-Global/winter-backend-cardano |
| **GitHub (contracts)** | https://github.com/zenGate-Global/winter-cardano-contracts |
| **GitHub (library)** | https://github.com/zenGate-Global/winter-cardano/tree/main |
| **Tooling** | cardano-node 8.9.0, Lucid (TypeScript) |

---

---

## COHORT 2 — Milestone 5 (M5) Submission

---

### 14. ClimaFi × BTCA (Better Than Cash Alliance)

| Field | Value |
|---|---|
| **Network** | Cardano **Preview Testnet** |
| **Website** | https://vakaconsulting.io |
| **Policy ID** | Derived from hash of combined script (specific value not published) |
| **Tooling** | Blockfrost API, custodial wallets, MXN token |
| **Status** | Deployed to Preview Testnet; mainnet migration pending security audit (85%+ coverage target) |

---

### 15. ClimaFi × Office of Procurement (UNSOFF)

| Field | Value |
|---|---|
| **Network** | Cardano **Preview Testnet** |
| **Website** | https://un-soff.org |
| **Policy ID** | `066cf48ed27898c8755818b0d2c352adf77cb9655190abd524a62858` |
| **Token** | UNSOFF token |
| **Notes** | Policy ID derived from hash of `ScriptAll` script. Deployed to Preview Testnet. Blockfrost auth mismatch between mainnet and preview was a noted bug (now fixed). |
| **Tooling** | Blockfrost API, custodial HD wallets |

---

### 16. Fuel Switch

| Field | Value |
|---|---|
| **Network** | Cardano **Preprod Testnet** |
| **Contract Language** | Aiken v1.1.19 |
| **Policy ID** | Derived via `aiken blueprint policy` from compiled Aiken blueprint (set via `POLICY_ID` env var) |
| **Blockfrost Key** | `BLOCKFROST_PROJECT_ID=preprod...` (preprod key) |
| **Notes** | Node.js backend server; UAT on Preprod; env variable switch to Mainnet planned. |
| **Tooling** | Aiken v1.1.19, Node.js, Blockfrost (Preprod) |

---

### 17. Green Giraffe

| Field | Value |
|---|---|
| **Network** | Cardano **Preprod Testnet** |
| **Website** | https://greengiraffetechnologies.com |
| **Demo Video** | https://www.youtube.com/watch?v=JOa8aQzBHsM&t=23s |
| **Wallet Address 1** | `addr_test1qq96vaw3q9xgcaz7dmkyuphcghx2sva9jn70nrnln63gpv9uem` |
| **Wallet Address 2** | `addr_test1qq9paspj9wr5xz6ru7z505tj8l7zl8x0uw852s58cvclvtew77` |
| **Explorer** | https://preprod.cardanoscan.io |
| **Notes** | Minting policy + spending validators deployed sequentially. 55% complete — ready for testnet validation. |
| **Tooling** | cardano-node (Preprod), Blockfrost, cardano-cli |

---

### 18. Plastiks (M5 — El Salvador & India)

| Field | Value |
|---|---|
| **Network** | Cardano **Mainnet** (Conway Era) |
| **Contract Language** | Plutus V2 |
| **Notes** | Same Smart Contract Ecosystem as M4; extended to El Salvador and India UNDP contexts. `sdNftPolicy` policyId parameterized per validator. Preprod → Mainnet rollout pipeline. Specific deployed policy IDs not published in documents. |

---

### 19. SALA

| Field | Value |
|---|---|
| **Network** | Cardano **Preview Testnet** (→ Preprod → Mainnet roadmap) |
| **Certificate Verification App** | https://certificate-verification.dev.sandbox.sala.tech/ |
| **Tooling** | Aiken smart contracts, cardano-node 8.9.0 (Preview Testnet) |
| **Notes** | Stress tests on Preprod planned as next step. No TX hashes or policy IDs published yet. |

---

### 20. SolarVillage (Cubid)

| Field | Value |
|---|---|
| **Network** | Cardano **Preprod Testnet** (+ **Hydra** L2) |
| **Contract Language** | Aiken |
| **Blockfrost Endpoint** | `https://cardano-preprod.blockfrost.io/api` |
| **GitHub (main)** | https://github.com/lley154/solar-village.git |
| **GitHub (dashboard)** | https://github.com/Solar-Village/solardash-hub-fork |
| **Demo Video** | https://www.youtube.com/watch?v=f3fmP0moHTQ |
| **Hydra Head ID** | `14cab222dcef7584fba3b630a1eaef996786fa80555511f836faf4cc` |
| **Policy ID 1 (NGN)** | `487f7138717d97cd76c1f0ed50a20e5e47b491ded3ddc5afc3d2ffd5` |
| **Policy ID 2 (WH)** | `f6580a3e0847439839bc1a3e5c4f4ead39b175ec05fe4883009228ec` |
| **Policy ID 3 (SOLAR token)** | `a036d93fc2ca6a0ba60d244166e6d396aefc5841a30973d19040b832` |
| **Policy ID 4** | `6b6a4188559f744cd18c9f905ee0990b34d881d92c7169aad588259e` |
| **Wallet Address 1** | `addr_test1vphjhjr7ravlzp0d4vnfd0awy8qq937l5zrfhzndpcguv9szmjven` |
| **Wallet Address 2** | `addr_test1vq3c4vxj466jlgp2elgpzhu9gv35mck2pvxruk7utmrfa3qtkds90` |
| **Wallet Address 3** | `addr_test1vqpdlgvqygnf3mvzvp0rv3mtrukjfsy9s65qflrwgzqsqecdurccm` |
| **Wallet Address 4** | `addr_test1vq58ln4m4v02uty8z4stdjzuj25h9xdfhef2zu3du7240lgtcrlk8` |
| **Wallet Address 5** | `addr_test1vzctfpxkpajgjc56y6znkw4dhw8vjatwfau3mj9tp5a67fgzu09fq` |
| **Wallet Address 6** | `addr_test1vpt3uvh252cl0atj36mzyyww3j0lst2mznkr4e4z5gyktyqmedc0l` |
| **TX Hash 1** | `2876f57b7a29d00d8633b083984016f455d9e901f61faff8371976fe9f6011f0` |
| **TX Hash 2** | `2f9d1fab6b9fb31f8b3ef823ec72c2055e0d1f6ae82a6782b77290d8a7fbc8b9` |
| **TX Hash 3** | `83d2b6960363dba94d8f16e1c8b2f05da81174fa07689771f4a6a519db0ef58d` |
| **TX Hash 4** | `b6d0e826f3d4f02e0cb0f7fc009d7b507f41ecf1d02a68fca36e7b469f72c5aa` |
| **TX Hash 5** | `bc6c82ef126c927fc84db39b27e24df3a8b958b3df97d6a03d6c41702b68122a` |
| **TX Hash 6** | `c1f84507f2491f2b37de95a956c62db6a65da2d57dcd2ae937a9d0799e71ae3f` |
| **TX Hash 7** | `cf4754b443aff2cd70d582d33aa3f24e1243ac22f9dc2cad775269849773fde6` |
| **TX Hash 8** | `fa85e388259bbd9f88bc2c447beee3893542c006122a5e03c16b41977a78ad96` |
| **TX Hash 9** | `fca316319ac405f71d3e018562195df97252002852a978baf826ce618aed8ce0` |
| **Notes** | Aiken validators deployed inside Hydra heads (one head per microgrid). Preprod → Mainnet roadmap. |

---

### 21. Tradechainx

| Field | Value |
|---|---|
| **Network** | Cardano **Preprod Testnet** |
| **Contract Language** | Aiken + Lucid |
| **Env Var** | `CARDANO_NETWORK=preprod` |
| **Deployed Components** | Project Registry, Lifecycle Validator, Minting Policy |
| **Notes** | End-to-end flows tested using Aiken emulator and Cardano testnet. Stress tests on Preprod planned. No specific policy IDs or TX hashes published. |
| **Tooling** | Aiken, Lucid, cardano-node (Preprod) |

---

### 22. Xcapit (SHELTER)

| Field | Value |
|---|---|
| **Network** | Cardano **Preview Testnet** (→ Preprod stress testing planned) |
| **Policy / Script ID** | `f5cea9526cec021b74fc35fdec275ea24ddfb7221026f49c493c10d3` |
| **TX Hash 1** | `f5cea9526cec021b74f...` (truncated in docs) |
| **TX Hash 2** | `be1b89805134ad076f2...` (truncated in docs) |
| **TX Hash 3** | `051680893a2e67106a5...` (truncated in docs) |
| **Explorer (TX 1)** | https://preview.cardanoscan.io/transaction/f5cea9526cec021b74fc |
| **Explorer (TX 2)** | https://preview.cardanoscan.io/transaction/be1b89805134ad076f2 |
| **Explorer (TX 3)** | https://preview.cardanoscan.io/transaction/051680893a2e67106a5 |
| **Rahat Docs** | https://docs.rahat.io/ |
| **Tooling** | Aiken, Cardano Preview Testnet |

---

## Summary Table

| # | Team | Cohort | Network | Contract/Policy ID | TX Hash(es) | Explorer / App |
|---|---|---|---|---|---|---|
| 1 | AFRIKABAL | M4 | Cardano Preview Testnet | — | 4 TXs (see above) | Blockfrost Preview |
| 2 | ATLAS LEDGER | M4 | Cardano Preprod Testnet | 2 contract addrs (HEX) | — | — |
| 3 | CLADFY | M4 | Cardano Preprod Testnet | — | 1 TX | — |
| 4 | CREATIVE OPERATIONS | M4 | Cardano Preview Testnet | — | — | reloop-eco-drop.vercel.app |
| 5 | GENIUS TAGS | M4 | Cardano Preview Testnet | Script hash: `970ec4df...` | 1 TX | preview.cardanoscan.io |
| 6 | GRINPLUS | M4 | Cardano Preview Testnet | — | — | YouTube demo |
| 7 | IOTA ORIGIN | M4 | Cardano Preprod Testnet | — | 1 TX | Blockfrost Preprod |
| 8 | KARBON LEDGER | M4 | Cardano Preview Testnet | Policy: `68d6e7d8...` | 1 TX | preview.cexplorer.io |
| 9 | PLASTIKS | M4 | Cardano Mainnet | Plutus V2 (not published) | — | — |
| 10 | SOCIOUS FUND | M4 | Cardano Preprod Testnet | — | — | gopay lib |
| 11 | THALLO | M4 | Cardano Preprod Testnet | Contract addr: `addr_test1vpcpquku...` | 3 TXs | preprod.cardanoscan.io |
| 12 | UNICORN.ETH | M4 | Cardano Preprod + Mainnet | — (native transfers) | Confirmed on Preprod | giveth Vercel app |
| 13 | ZENGATE | M4 | Cardano Preview Testnet | — | — | GitHub repos |
| 14 | ClimaFi × BTCA | M5 | Cardano Preview Testnet | Derived from ScriptAll | — | vakaconsulting.io |
| 15 | ClimaFi × UNSOFF | M5 | Cardano Preview Testnet | `066cf48e...` (UNSOFF) | — | un-soff.org |
| 16 | Fuel Switch | M5 | Cardano Preprod Testnet | Via `aiken blueprint policy` | — | — |
| 17 | Green Giraffe | M5 | Cardano Preprod Testnet | — | — | preprod.cardanoscan.io |
| 18 | Plastiks (M5) | M5 | Cardano Mainnet | Plutus V2 (not published) | — | — |
| 19 | SALA | M5 | Cardano Preview Testnet | — | — | sala.tech sandbox |
| 20 | SolarVillage (Cubid) | M5 | Cardano Preprod + Hydra | 5 Policy IDs (see above) | 9 TXs | Blockfrost Preprod |
| 21 | Tradechainx | M5 | Cardano Preprod Testnet | — | — | — |
| 22 | Xcapit (SHELTER) | M5 | Cardano Preview Testnet | `f5cea952...` | 3 TXs (truncated) | preview.cardanoscan.io |
