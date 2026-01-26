# Hi, I'm Rim Dinov 👋
**Blockchain Engineer | L2 Core Contributor**

Expert in blockchain infrastructure, node stability, and high-performance Go development. Focused on enhancing Layer 2 protocols and ensuring data integrity.

Blockchain & Web3 Security Research

In this repository I collect my findings as part of the Bug Bounty programs.

Vulnerabilities found:

CSWSH (Cross-Site WebSocket Hijacking) — Backpack Exchange.

IDOR / Data Injection — Analytics endpoints (Amplitude).

Tools: Python, Requests, Burp Suite.
https://hackenproof.com/hackers/rdin777


### 🚀 Recent Open Source Work
* **[go-ethereum](https://github.com/ethereum/go-ethereum/pull/33498):** Refactored core codebase by removing deprecated vulnerability logic (-815 lines).
* **[Tezsign Security](https://gist.github.com/rdin777/...):** Engineered a hardened 24MB minimal Linux kernel for RK3566-based hardware signing devices.
* **[Arbitrum Nitro](https://github.com/OffchainLabs/nitro/pull/4163):** Improved state validation logic to prevent database corruption.

### 🏛 Core Contributions
- **[Offchain Labs / Nitro](https://github.com/OffchainLabs/nitro)**
  - **[PR #4163](https://github.com/OffchainLabs/nitro/pull/4163)**: Fixed a critical database corruption vulnerability during node reorgs.
  - Performance benchmarking and verification of the Nitro stack on the **Go 1.25** toolchain.
- **[Layr-Labs / EigenDA](https://github.com/Layr-Labs/eigenda)**
  - **[PR #2431](https://github.com/Layr-Labs/eigenda/pull/2431)**: Improved client resilience and connectivity logic.

### 🛠 Tech Stack
- **Languages:** Go (Expert), SQL, Shell
- **L2/L1 Tech:** Arbitrum Nitro, ZKsync, Linea, EigenDA, Cosmos SDK
- **Specialization:** Node Infrastructure, DB Integrity, RPC Optimization

### 📬 Contact Me
- **Telegram:** @[ТВОЙ_НИК]
- **Email:** rdin35051@gmail.com
**L2 Core Contributor | Blockchain Security & Architecture**

I focus on the architectural integrity, prover stability, and security of Ethereum Layer 2 ecosystems. I recently completed a "contribution marathon" across **Arbitrum**, **Linea**, and **ZKsync**, solving critical bottlenecks in node logic and proof generation.

For the bounty payout, I prefer using my MetaMask (EVM compatible) address: 0xBDDD7973D0DE27B715A4A5cbdb87d0DF78757b3A 
You can send the funds in USDT/USDC/ETH or any other token on Ethereum, BSC, Arbitrum, Base networks. Thank you!


### 💰 Bounty & Donations
**MetaMask (EVM):** 0xBDDD7973D0DE27B715A4A5cbdb87d0DF78757b3A 
Accepting: USDT / USDC / ETH / MATIC



---

### 🚀 Recent Contributions (L2 Marathon)

#### 1. Arbitrum (Offchain Labs) — Node Integrity
* **Issue:** Prevented database corruption during node reorgs ([#4098](https://github.com/OffchainLabs/nitro/issues/4098)).
* **Solution:** Implemented pre-initialization state validation in `cmd/nitro/init.go` (PR [#4163](https://github.com/OffchainLabs/nitro/pull/4163)).
* **Impact:** Eliminated risks of "bricking" nodes during rollbacks, protecting operator databases from inconsistency.


#### 2. Linea (Consensys) — ZkTracer Architecture
* **Issue:** Fixed decoupling of line counts from trace height in arithmetic modules (Issue #1955).
* **Solution:** Refactored `computeLineCount()` logic in Java-based tracers to support dynamic complexity.
* **Impact:** Ensured stable proof generation and eliminated "silent errors" in trace files.


#### 3. ZKsync Era — Prover & CI Optimization
* **Contribution:** Refactored magic constants into named parameters to improve system auditability (PR #1230).
* **Action:** Optimized GitHub Actions for the core proof generation pipeline to speed up CI/CD cycles.
* **Result:** Enhanced code maintainability and transparency for the prover infrastructure.


---

### 🛠 Tech Stack
* **Languages:** Go (Nitro/Geth Core), Java (ZkTracer), Rust (Provers).
* **Tools:** Ethereum rawdb, Pebble DB, ZK-proof systems, GitHub Actions.

---

### 📫 Connect with me
* **GitHub:** [rdin777](https://github.com/rdin777)
* **Email:** rdin35051@gmail.com
