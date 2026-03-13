# Hi, I'm Rim Dinov 👋
![Profile Views](https://komarev.com/ghpvc/?username=rdin777&color=0055ff&style=flat-square&label=AUDIT+VISITS)

### Technical Communications & L2 Security Researcher
*Bridging the gap between deep protocol engineering and strategic technical narratives.*

---

## 👨‍💻 About Me
I am a **Security Researcher & Blockchain Engineer** specializing in infrastructure audits, L2 protocols, and internal tooling security. My approach combines deep static code analysis (SAST) with dynamic testing (strace, fuzzing) to uncover critical flaws in complex systems and translate them into actionable insights for the ecosystem.

## 🛡️ Recent Security Research
* **BSC Geth Panic Discovery:** Identified a deterministic node panic (nil-pointer dereference) in the `state` package. Developed a full PoC using Foundry to reproduce the network halt. 
    * [Read the full technical breakdown on Paragraph]https://paragraph.com/@levp254@gmail.com/bsc-halt-poc-developing-a-reproduction-environment-for-a-deterministic-node-panic-in-the-bsc-geth-client?referrer=0xBDDD7973D0DE27B715A4A5cbdb87d0DF78757b3A

* **Cronos POS & zkEVM:** Currently investigating node resilience and consensus-level vulnerabilities.
* **DeFi Auditing:** Researched rounding errors and "ghost debt" mechanics in protocols like Panoptic and Autonolas.


### 📈 Trending & High-Impact Research

### 🛡️ Active Security Audits & Vulnerability Research

L1/L2 Infrastructure Audits: Identified critical systemic vulnerabilities in EVM-Cosmos precompiled contracts, including unauthorized asset minting and cross-chain account takeover (ICA).

Interoperability Security: Researching attack vectors in IBC (Inter-Blockchain Communication) and bridge-level access control.

* **Arbitrum Nitro (L2 Execution Engine)**
  * 🔴 **Critical**: Deterministic **Sequencer Panic (SIGSEGV)** in `triedb`.
  * **Status**: ⏳ Submitted via HackerOne Disclosure Assistance (#3591692).

* **Injective Protocol (Peggy Bridge)**
  * 🟡 **Medium**: Slashed/Jailed logic vulnerability during Ethereum Key Rotation.
  * 🔴 **Critical**: Potential **Bridge Hijacking** via unvalidated Valset updates (Analysis of `attestation_handler.go`).
  * **Status**: 🛠️ Competitive Audit in progress (Code4rena).

* **Nethermind / Juno (Starknet)**
  * 🟠 **High**: Memory Aliasing in Trie Node Updates (GHSA-fh9g-4r27-crcc).
  * **Status**: 🟡 Under Triage by the Core Team.

* **Arbitrum Nitro (L2 Execution Engine)**: 
  * 🔴 **Critical**: Identified a deterministic **Sequencer Panic (SIGSEGV)** in `triedb` component.
  * **Status**: ⏳ Report submitted via HackerOne Disclosure Assistance (#3591692).
  * **Focus**: Go Runtime Safety, Wasm Activation Logic, State Database Consistency.

### 🛡️ Bug Bounty & Vulnerability Disclosure
* **Coinbase**: Discovered a **Deterministic Node Panic (DoS)** via Nil Pointer Dereference in `op-geth` core [Report #3509907].
* **Linea Mainnet**: Identified security flaws in unauthenticated JSON-RPC endpoints.
* **OAuth2 Security**: Research on PKCE Enforcement Bypass leading to account takeover risks.
* **HackerOne Profile**: [rdin777](https://hackerone.com/rdin777) — Active researcher in the Web3/Infrastructure space.

* **[Kuru Precision Loss Audit Report](https://github.com/rdin777/kuru-precision-loss-audit-report)**: 
  * 🚀 **Viral Engagement**: Over **100+ clones** by the security community within the first weeks.
  * **Focus**: Advanced mathematical edge cases in DeFi, focusing on rounding errors and dust management.
  * **Impact**: Widely used as a reference for auditing precision loss in orderbook-based DEXs.

* **[Nethermind / Juno (Starknet)](https://github.com/NethermindEth/juno)**: 
  * 🛡️ **High-Severity Discovery**: Memory Aliasing in Trie Node Updates ([GHSA-fh9g-4r27-crcc](https://github.com/NethermindEth/juno/security/advisories/GHSA-fh9g-4r27-crcc)).
  * **Status**: 🟡 Under Triage by the Core Team.

## 🛡️ Recent Impact & Security Research

### [GHSA-fh9g-4r27-crcc](https://github.com/NethermindEth/juno/security/advisories/GHSA-fh9g-4r27-crcc) | Nethermind Juno (Starknet)
* **Status**: 🟠 Triage / High Severity
* **Impact**: Identified a critical memory safety vulnerability in the Trie implementation. Discovered that pointer aliasing in `Node.Update` when combined with `sync.Pool` leads to non-deterministic state corruption.
* **Write-up**: [Deep Dive into Trie Node Corruption on HackerNoon](твоя_ссылка_на_hackernoon)

### 🐧 Systems Engineering
* **[radxa-zero3-minimal-kernel](https://github.com/rdin777/radxa-zero3-minimal-kernel)**: Developing a performance-optimized minimal kernel for Radxa Zero 3.
* **Community Traction**: Steady interest with **20+ unique clones** bi-weekly, demonstrating expertise in low-level systems and resource-constrained environments.

## 🛡️ Featured Security Research
**Blockchain & L2 (Optimism/Base)**
* **Node Panic (DoS) in op-geth** — Discovered a state management flaw leading to node instability in the Optimism/Base stack.

## 🚀 Core Contributions
* **Arbitrum Nitro:** Implemented block state validation (PR #4163) to prevent database corruption.
* **EigenDA:** Enhanced network resilience via advanced connectivity checks for high-throughput clients.
* **Ecosystems:** Active contributor to **Linea** and **ZKsync** core infrastructure.

---

## 📬 Connect with me
* **Telegram:** [@levp254](https://t.me/levp254)
* **Email:** rdin35051@gmail.com
* [📄 Download my Resume (PDF)](https://github.com/rdin777/rdin777/raw/main/assets/Rim_Dinov_Technical_PR_Resume.pdf)
* https://github.com/rdin777/rdin777/blob/main/assets/Rim_Dinov_Technical_PR_Resume.2.pdf

*Available for technical discussions regarding L2 architecture, node security, and ecosystem growth.*

## 👨‍💻 About Me

I am a **Security Researcher & Blockchain Engineer** specializing in infrastructure audits, L2 protocols, and internal tooling security. My approach combines deep static code analysis (SAST) with dynamic testing (strace, fuzzing) to uncover critical flaws in complex systems.

### 🛡️ Featured Security Research

#### **Blockchain & L2 (Optimism/Base)**
* **[Node Panic (DoS) in op-geth](https://github.com/rdin777/op-stack-state-panic)** — Discovered a state management flaw leading to node instability in the Optimism/Base stack.

#### **Infrastructure & Fintech (Nubank Audit)**
A comprehensive security review of Nubank's internal tooling (Vessel), identifying multiple attack vectors:
* **Critical RCE**: Identified Server-Side Code Injection in image building logic (Clojure).
* **Argument Injection**: Demonstrated shell escape via unsanitized CLI parameters.
* **Sensitive Data Exposure**: Uncovered plaintext credential leakage in application logs.
* **Resource Exhaustion**: Application-level DoS via unsafe EDN parsing.

### 🛠️ Tech Stack

* **Languages:** Go (Geth architecture), Solidity, Python, Clojure, Rust (Foundational).
* **Tools:** Foundry (Forge/Cast), Hardhat, Linux Kernel Debugging.
* **Focus:** Smart Contract Security, L1/L2 Infrastructure, Technical Writing.

---
*“I don’t just find bugs; I analyze the architecture to prevent entire classes of vulnerabilities.”*

Markdown
* **[Node Panic (DoS) in Optimism-Geth (op-geth)](https://github.com/rdin777/op-stack-state-panic)** — Found a Nil Pointer Dereference in the state journal management (Base/Optimism L2 infrastructure).

**Blockchain Engineer | L2 Core Contributor**

Expert in blockchain infrastructure, node stability, and high-performance Go development. Focused on enhancing Layer 2 protocols and ensuring data integrity.

Blockchain & Web3 Security Research

In this repository I collect my findings as part of the Bug Bounty programs.

Vulnerabilities found:

BSC Geth: Deterministic Network Halt (PoC)
https://github.com/rdin777/bsc-halt-poc
https://paragraph.com/@levp254@gmail.com/bsc-halt-poc-developing-a-reproduction-environment-for-a-deterministic-node-panic-in-the-bsc-geth-client?referrer=0xBDDD7973D0DE27B715A4A5cbdb87d0DF78757b3A


https://github.com/rdin777/-blog.cex.io-Sensitive-Information-Disclosure-via-WordPress-User-Enumeration
-blog.cex.io-Sensitive-Information-Disclosure-via-WordPress-User-Enumeration
https://medium.com/@rdin777/how-i-uncovered-employee-data-on-a-crypto-exchange-via-wordpress-misconfiguration-c8723d0cc2c4


Solana Dependency Hell: Why your next audit will start with the desire to quit everything
https://medium.com/p/98ed9be3ee45


https://github.com/rdin777/rujira-liquidation-vulnerability
The "Unstoppable" Debt: How a Decimal Mismatch Frozen Liquidations in CosmWasm
https://medium.com/p/940363ce2437

https://github.com/rdin777/Permanent-loss-of-user-funds-Panoptic]
Precision Loss in DeFi: When a 0.000001% Difference Leads to 100% Fund Loss
https://medium.com/p/2613d4893524

https://github.com/rdin777/rujira-ghost-pool/tree/main
Rujira Ghost Vault: Systemic DoS & Inflation Attack (H-01)
https://medium.com/@rdin777/e5cd349dd414

https://github.com/rdin777/kuru-precision-loss-audit-report/tree/main
describes a classic problem in Solidity—division before multiplication—which leads to a loss of precision.
https://medium.com/@rdin777/how-a-single-line-of-code-can-zero-out-your-trades-kuru-labs-precision-loss-case-study-34e4ef4cb06e

https://github.com/rdin777/linea-rpc-exposure-research/tree/main

🐧 radxa-zero3-minimal-kernel — Lightweight (8.9MB) Linux kernel for RK3566. Fixed ARM64-specific GPU driver memory conflicts.
https://github.com/rdin777/radxa-zero3-minimal-kernel/tree/main
https://app.hackernoon.com/mobile/69a940941121431525a04baf

Markdown
#### **Fintech & Infrastructure (Nubank Audit)**
> 📝 **Read the Full Research:** [Anatomy of a Build Tool Vulnerability](https://medium.com/@rdin777/anatomy-of-a-build-tool-vulnerability-auditing-nubanks-vessel-dd824a73f99d)
> https://medium.com/@rdin777/hunting-for-deterministic-panic-in-layer-2-infrastructure-a-deep-dive-into-op-geth-83219f3e26e1



* **[Critical RCE in Vessel Builder](https://github.com/rdin777/vessel-rce-research)** — Implementation of Argument Injection in Clojure-based build systems.
* **[Vessel Security Research](https://github.com/rdin777/vessel-security-research)** — Deep dive into `sh.clj` and command execution wrappers.


* **[P1 Critical: Cronos Devnet Infrastructure Flaw](https://github.com/rdin777/cronos-infrastructure-security)** — Identification of a critical misconfiguration in Cronos Devnet environments allowing for infrastructure-level compromise.

Markdown
* **[Critical RCE in Nubank Vessel Builder](https://github.com/rdin777/vessel-rce-research)** — Deep code audit of Clojure-based image builder identifying a Server-Side Injection vector (RCE) via unsanitized input in build configurations.

* **[Application-Level DoS in vessel.misc/read-string](https://github.com/rdin777/vessel-edn-dos-research)** — Exploiting unsafe EDN parsing in Nubank's Vessel tool to cause resource exhaustion and service denial.

* **[Sensitive Data Exposure in vessel.jib.pusher](https://github.com/rdin777/vessel-credential-leak-research)** — Research on plaintext credential leakage in application error logs during registry push operations.

* **[Argument Injection in Nubank Vessel](https://github.com/rdin777/vessel-security-research)** — Security audit of a Clojure-based container management tool. Identified unsanitized input vectors in CLI arguments that could lead to RCE in CI/CD pipelines.

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
