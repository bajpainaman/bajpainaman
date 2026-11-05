<p>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.png">
  <img alt="Naman Bajpai. Co-founder and CTO of The Singularity. Markets, systems, and machine intelligence." src="assets/hero-light.png" width="100%">
</picture>
</p>

<p align="center">
  <a href="https://namanbajpai.com"><img alt="Website: namanbajpai.com" src="https://img.shields.io/badge/Website-namanbajpai.com-F4F3F0?style=for-the-badge&labelColor=08080A"></a>
  <a href="https://www.linkedin.com/in/bajpainaman"><img alt="LinkedIn: bajpainaman" src="https://img.shields.io/badge/LinkedIn-bajpainaman-F4F3F0?style=for-the-badge&labelColor=08080A"></a>
  <a href="https://x.com/defibagholder"><img alt="X: @defibagholder" src="https://img.shields.io/badge/X-%40defibagholder-F4F3F0?style=for-the-badge&labelColor=08080A"></a>
  <a href="mailto:namanbajpai23@gmail.com"><img alt="Email: namanbajpai23@gmail.com" src="https://img.shields.io/badge/Email-namanbajpai23%40gmail.com-F4F3F0?style=for-the-badge&labelColor=08080A"></a>
  <a href="https://github.com/bajpainaman/resume"><img alt="Resume (PDF)" src="https://img.shields.io/badge/Resume-PDF-FF6FB5?style=for-the-badge&labelColor=08080A"></a>
  <a href="https://github.com/bajpainaman?tab=followers"><img alt="GitHub followers" src="https://img.shields.io/github/followers/bajpainaman?style=for-the-badge&label=Followers&labelColor=08080A&color=F4F3F0&logo=github&logoColor=F4F3F0"></a>
</p>

I am the co-founder and CTO of **[The Singularity](https://github.com/0xTheSingularity)** (Entropy to Order), and I study Computer Science at Drexel University.

My work spans exchange infrastructure, GPU computing, distributed systems, compilers, and applied machine learning.

https://github.com/user-attachments/assets/fc0e0fb6-556c-4bd1-a242-e840f58a9fa2

## Building The Singularity

We are building the **Everything Exchange**: a common system for trading across centralized exchanges and on-chain markets.

My work here spans **OneBook** for order management, routing, and execution; **Hilsa** for cross-chain observation and verification; and the matching, consensus, custody, and settlement infrastructure underneath them.

<details>
<summary>Execution, consensus, and market design</summary>

- **Execution and shared state:** GPU execution, shared-state systems, and tooling across multiple VM families. The [ETO CLI](https://github.com/0xTheSingularity/eto-cli) documents EVM, SVM, Move, WASM, and ZK interfaces.
- **Rohu-Paplet:** Byzantine consensus research, including the relationship between ordering, execution, observation, and finality.
- **Correctness and security:** EVM differential testing, failure testing, and adversarial protocol analysis.
- **Market mechanisms:** DRI and Asset Factory work on asset issuance and index tracking, and Orbital experiments in AMM design. The [DRI paper](https://github.com/0xTheSingularity/docs/blob/main/Math%20Paper%20DRI%20.md) documents the earlier design.
- **Interfaces and integration:** command-line and [MCP tooling](https://github.com/0xTheSingularity/eto-mcp), plus work connecting execution and consensus to persistent state, including QMDB integration.

</details>

## Selected engineering and research

| Area | Work |
| --- | --- |
| **GPU systems**<br>![CUDA](https://img.shields.io/badge/-CUDA-F4F3F0?style=flat-square&labelColor=08080A&logo=nvidia&logoColor=F4F3F0) ![Rust](https://img.shields.io/badge/-Rust-F4F3F0?style=flat-square&labelColor=08080A&logo=rust&logoColor=F4F3F0) | Inference kernels for mixture-of-experts models and decode workloads. [FlashMap](https://github.com/bajpainaman/flash-map) is a bulk hash map in Rust with CUDA acceleration and CPU/Rayon fallbacks. |
| **Compilers and execution**<br>![Vx](https://img.shields.io/badge/-Vx-F4F3F0?style=flat-square&labelColor=08080A&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZD0iTTEyIDIuNSAyMC4yIDcuMjV2OS41TDEyIDIxLjVsLTguMi00Ljc1di05LjV6IiBmaWxsPSIjRjRGM0YwIi8%2BPC9zdmc%2B) ![EVM](https://img.shields.io/badge/-EVM-F4F3F0?style=flat-square&labelColor=08080A&logo=ethereum&logoColor=F4F3F0) | [EVM-vx](https://github.com/bajpainaman/EVM-vx), a research-stage CPU EVM with optimistic parallel execution; [vex](https://github.com/bajpainaman/vex), a prototype package manager; and upstream [Vx compiler contributions](https://github.com/vx-lang/Vx/pulls?q=is%3Apr+is%3Amerged+author%3Abajpainaman). |
| **Custody and authorization**<br>![Rust](https://img.shields.io/badge/-Rust-F4F3F0?style=flat-square&labelColor=08080A&logo=rust&logoColor=F4F3F0) ![Solana](https://img.shields.io/badge/-Solana-F4F3F0?style=flat-square&labelColor=08080A&logo=solana&logoColor=F4F3F0) | [Open Institutional Custody](https://github.com/0xTheSingularity/open-insititutional-custody): Rust components for payment approvals, spending limits, and EVM/Solana signing. A development preview with simulated chains. |
| **Verifier-guided learning**<br>[![Live demo](https://img.shields.io/badge/-Live%20demo-FF6FB5?style=flat-square&labelColor=08080A&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZD0iTTEyIDIuNSAyMC4yIDcuMjV2OS41TDEyIDIxLjVsLTguMi00Ljc1di05LjV6IiBmaWxsPSIjRjRGM0YwIi8%2BPC9zdmc%2B)](https://bajpainaman.github.io/daybreak-demo/) | [Daybreak](https://github.com/bajpainaman/daybreak-demo): experiments in independent emulator checks, bug-finding workflows, and verifier-generated training data. [Interactive demo](https://bajpainaman.github.io/daybreak-demo/). |
| **Strategic reasoning**<br>![Python](https://img.shields.io/badge/-Python-F4F3F0?style=flat-square&labelColor=08080A&logo=python&logoColor=F4F3F0) ![Rust](https://img.shields.io/badge/-Rust-F4F3F0?style=flat-square&labelColor=08080A&logo=rust&logoColor=F4F3F0) | [Sigma-Go](https://github.com/bajpainaman/scaling): research on counterfactual value prediction, poker AI, and learning in imperfect-information games. |
| **Agents and open networks**<br>![MCP](https://img.shields.io/badge/-MCP-F4F3F0?style=flat-square&labelColor=08080A&logo=modelcontextprotocol&logoColor=F4F3F0) ![TypeScript](https://img.shields.io/badge/-TypeScript-F4F3F0?style=flat-square&labelColor=08080A&logo=typescript&logoColor=F4F3F0) | [NANDA server and plugin integration](https://github.com/bajpainaman/Nanda-Sdk-Tsc), built on the MCP TypeScript SDK, and [Beckn AI tooling](https://github.com/bajpainaman/beckn-llm-layer) for developer assistance and retrieval. |

## Work in practice

- **Exelon / PECO:** GasGPT and production AI infrastructure for gas operations, including backend modernization supporting 1,000+ users.
- **Beckn Protocol:** an AI internship working on transaction interfaces and a knowledge-based developer assistant.
- **Drexel:** Computer Science, research, and teaching support.

<details>
<summary>Earlier ventures and applied ML</summary>

- **Encryptech / Mycelium:** decentralized and privacy-preserving machine learning, including federated learning and FHE. The public [architecture notes](https://github.com/bajpainaman/mycelium/blob/main/Architecture.MD) describe the federated-learning and Beckn direction.
- **Classcut / MPX:** educational software, video search, and ML product work.
- **Dynamic Rocketry:** earlier aerospace work on solid rocket motors and cold-gas thrusters.
- **[Delphic](https://github.com/bajpainaman/delphic):** API-to-chain oracle experiments, with contracts, off-chain ingestion, and TEE-oriented components.
- **[Indic LLM Toolkit](https://github.com/bajpainaman/indic-llm-toolkit):** data preparation, training, evaluation, and inference experiments for multilingual models.
- **[Insurance ML](https://github.com/bajpainaman/insurance_c):** experiments combining tabular, graph, text, and anomaly-detection models.

</details>

<details>
<summary>Developer tools and technical explorations</summary>

- **[DeltaMCP](https://github.com/bajpainaman/DeltaMCP):** git-delta integration for readable diffs and Git views in coding assistants.
- **[STE writing](https://github.com/bajpainaman/ste-writing):** technical-writing tools with agent edit hooks and Vale/Harper linting.
- **[Jev / Codex integration](https://github.com/bajpainaman/fast-jev-compaction/blob/main/CODEX.md):** a Codex history adapter and post-compaction context restoration contributed in my fork.
- **Research forks:** [Solidus](https://github.com/bajpainaman/solidus), for Lean 4 and Yul-to-EVM compilation, and [strevm](https://github.com/bajpainaman/strevm), for streaming asynchronous EVM execution.

</details>

## Milestones

<p>
  <img alt="HackMIT Codebase track: 2nd place" src="https://img.shields.io/badge/HackMIT%20%C2%B7%20Codebase%20track-2nd%20place-FFE34D?style=for-the-badge&labelColor=08080A">
  <img alt="ICPC North America Qualifier: 2nd place at Drexel" src="https://img.shields.io/badge/ICPC%20NA%20Qualifier-2nd%20at%20Drexel-FFE34D?style=for-the-badge&labelColor=08080A">
  <br>
  <img alt="$50K foundation grant" src="https://img.shields.io/badge/Foundation%20grant-%2450K-FFE34D?style=for-the-badge&labelColor=08080A">
  <img alt="Provisional patent filing for dynamic market-maker architecture" src="https://img.shields.io/badge/Provisional%20patent-Dynamic%20market%20maker-FFE34D?style=for-the-badge&labelColor=08080A">
</p>

## Tools

<p>
  <img alt="Rust" src="https://img.shields.io/badge/-Rust-F4F3F0?style=for-the-badge&labelColor=08080A&logo=rust&logoColor=F4F3F0">
  <img alt="CUDA / PTX" src="https://img.shields.io/badge/-CUDA%20%2F%20PTX-F4F3F0?style=for-the-badge&labelColor=08080A&logo=nvidia&logoColor=F4F3F0">
  <img alt="Go" src="https://img.shields.io/badge/-Go-F4F3F0?style=for-the-badge&labelColor=08080A&logo=go&logoColor=F4F3F0">
  <img alt="C / C++" src="https://img.shields.io/badge/-C%20%2F%20C%2B%2B-F4F3F0?style=for-the-badge&labelColor=08080A&logo=cplusplus&logoColor=F4F3F0">
  <br>
  <img alt="Python" src="https://img.shields.io/badge/-Python-F4F3F0?style=for-the-badge&labelColor=08080A&logo=python&logoColor=F4F3F0">
  <img alt="TypeScript" src="https://img.shields.io/badge/-TypeScript-F4F3F0?style=for-the-badge&labelColor=08080A&logo=typescript&logoColor=F4F3F0">
  <img alt="Solidity" src="https://img.shields.io/badge/-Solidity-F4F3F0?style=for-the-badge&labelColor=08080A&logo=solidity&logoColor=F4F3F0">
  <img alt="Lean 4" src="https://img.shields.io/badge/-Lean%204-F4F3F0?style=for-the-badge&labelColor=08080A&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZD0iTTEyIDIuNSAyMC4yIDcuMjV2OS41TDEyIDIxLjVsLTguMi00Ljc1di05LjV6IiBmaWxsPSIjRjRGM0YwIi8%2BPC9zdmc%2B">
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/wall-dark.webp">
  <img alt="" src="assets/wall-light.webp" width="100%">
</picture>
