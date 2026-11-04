# Robert Zerby (@HindsightWise)
### Human–AI Systems Director & Oversight Architect | 25-Year Physical Systems Diagnostician

> Directing frontier AI coding and research agents through 25+ years of real-world root-cause diagnostic instinct, comprehensive system context, and deterministic verification guardrails.

[Email](mailto:ZerbytheBoss@gmail.com) • [LinkedIn](https://www.linkedin.com/in/robert-zerby-49520596/) • [X (@Zerbytheboss)](https://x.com/Zerbytheboss) • [Kaggle](https://www.kaggle.com/zerbytheboss) • Yorba Linda, CA

---

## 🤝 How We Work ("The Reality of Us")

Every repository on this profile is built through an explicit **Human–AI division of labor**:

- **What I Bring (The Human Operator)**: I am not a traditional academic ML theorist or a solo whiteboard syntax grinder. For 25 years, I diagnosed, built, and audited high-consequence physical, mechanical, and regulatory systems—scaling **Mission Service and Parts, Inc.** 5x across 80+ Southern California fuel sites with a **100% pass rate** across EPA, SCAQMD, Weights & Measures, and SWRCB UST audits. I provide the **system architecture, root-cause failure intuition, persistent cross-project context, and verification gates** that stop autonomous agents from drifting or hallucinating.
- **What the AI Brings (The Compute Engine)**: My AI collaborators (Claude, Gemini, and specialized local/remote critic models) translate those architectural constraints into raw Python, Rust, TypeScript, and mathematical implementations—verified at every step by deterministic test harnesses and orthogonal red-team gates.

---

## 🛡️ AI Oversight, Red-Teaming & Agent Harnesses

### 1. [Sovereign Oversight Harness (`sovereign-oversight-harness`)](https://github.com/HindsightWise/sovereign-oversight-harness)
*41-Subclass Agent Oversight Hierarchy (`s7..s41`), Budget-Augmented POMDP & Episodic Memory Web*
- **Reset-Aware Settled-State Oracle (`s15`)**: Prevents false-positive grading on transient `Cycle 0` states by enforcing verification on settled `Cycle 1+` state.
- **Spec-Only Context-Poisoning Regeneration (`s29`)**: Separates compiler/lint errors (routed to surgical repair) from semantic failures that poison the context window ($\Delta_{c1} > 0$), purging broken drafts and regenerating cleanly from the specification.
- **Budget-Augmented POMDP (`budget_pomdp.py`)**: Tracks multi-resource agent expenditure across `steps`, `tool_calls`, `tokens`, and `turns` across 11 cost-conditioned reward objectives.
- **2-WL Loop Detection (`s11`) & NREM/REM Sleep Consolidation (`sleep_cycle.py`)**: Halts repetitive agent tool loops and compresses working memory with zero-forgetting rollback guards.

### 2. [Orthogonal Red-Team Harness (`orthogonal-redteam-harness`)](https://github.com/HindsightWise/orthogonal-redteam-harness)
*Tri-Tier Cross-Model Adversarial Critic & Isolated Pytest Counterexample Sandbox*
- **Breaking Correlated Blind Spots**: Routes code and plans written by a primary coding agent to independent critic models (`moonshotai/Kimi-Dev-72B` for adversarial test generation; `DeepSeek-R1-Distill-Qwen-32B` for mathematical and strategic critique).
- **Sandboxed Counterexample Execution**: Extracts critic-generated `pytest` suites and executes them against the target module in an isolated subprocess sandbox.
- **Zero-Idle Compute Lifecycle**: Model Context Protocol (MCP) server with POSIX `0600` masked token storage and automatic `google.colab.runtime.unassign()` shutdown immediately after verification completes.

### 3. [MLX Code Surgeon (`mlx-code-surgeon`)](https://github.com/HindsightWise/mlx-code-surgeon)
*Zero-Swap Apple Silicon Metal Fill-In-The-Middle (FIM) & Speculative Decoding MCP Server*
- **Hardware-Bounded Local Compute**: Runs 4-bit `Qwen2.5-Coder` (`0.5B`, `3B`, `7B`) on Apple Metal with parallel speculative decoding (`0.5B` draft accelerating `3B`/`7B` targets) at up to **93.9 tok/s**.
- **Strict Memory Ceiling**: Keeps peak wired Metal RAM under **4.97 GB** on a 16 GB unified-memory Mac, with explicit GPU cache unloading (`unload=True`) to prevent OS swap collapse.

### 4. [Teleos Consensus Engine (`teleos-consensus-engine`)](https://github.com/HindsightWise/teleos-consensus-engine)
*Multi-Cohort Signal Probe & TF-IDF Bigram Graph Consensus Clusterer*
- Harvests operational friction signals across GitHub issues, Hacker News, and developer cohorts, requiring cross-cohort graph consensus before synthesizing engineering blueprints.

---

## 🔬 Benchmarks, Evaluations & Simulation Engines

### 5. [Gemma 4 Developer Agent Evaluation Suite (`gemma-4-developer-agent`)](https://github.com/HindsightWise/gemma-4-developer-agent)
*Long-Horizon SWE Benchmark & Dual-Container Anti-Tampering Sandbox*
- End-to-end evaluation harness for autonomous coding agents across 120+ GitHub issue resolution tasks (`FastAPI`, `Rich`, `Requests`, `HTTPX`), enforcing strict container isolation between agent tool execution and unseen ground-truth `pytest` grading.

### 6. [ARC-AGI-3 DualBrain & Apex Engine (`ARC-AGI-3-DualBrain`)](https://github.com/HindsightWise/ARC-AGI-3-DualBrain)
*Two-Phase Meta-Planning & Working Memory Substrate for Interactive Reasoning*
- Implements two-phase planning (*Plan to Plan* reconnaissance followed by *Plan a Plan* execution) and offline action-queue verification optimized for Relative Human Action Efficiency (RHAE).

### 7. [Kaggriculture Simulation Engine (`kaggriculture-simulation-engine`)](https://github.com/HindsightWise/kaggriculture-simulation-engine)
*720-Step Economic & Multi-Agent Tournament Platform*
- 2-player economic simulation engine modeling Automated Market Maker (AMM) pricing dynamics and crop lifecycles, verified via multi-seed Monte Carlo stress testing.

### 8. [Monad (`Monad`)](https://github.com/HindsightWise/Monad) & [Venom-Arsenal (`Venom-Arsenal`)](https://github.com/HindsightWise/Venom-Arsenal)
*Async Rust Multi-Agent Runtime & Model Context Protocol (MCP) Tool Suite*
- Actor-model concurrency, WASM sandboxing, and low-latency MCP server tooling built in Rust and Python.

---

## 📐 Core Operating Principles

1. **Human Direction + Machine Compute**: Never pretend the human is a solo code compiler or that the AI has real-world physical judgment. Pair human architectural intuition and failure-mode diagnosis with machine-speed implementation.
2. **Orthogonal Verification Over Self-Grading**: An agent should never be the sole grader of its own output. Enforce settled-state oracles, isolated test sandboxes, and cross-model adversarial critique.
3. **Black-Box Vertical Bricks**: Organize systems into self-contained vertical capabilities with a single public interface and explicit state contracts, preventing horizontal coupling knots.
