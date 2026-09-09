# Luke Scaggs

**AI systems builder · operations tooling · automotive software · analytics · local-first AI**

I build practical software for real workflows — from local AI systems and model evaluation to **custom operational, automotive, and analytics solutions**.

My work spans **AI agents, model evaluation, post-training experiments, automotive acquisition tooling, workflow automation, analytics, chess systems, desktop software, and Android applications**. The common thread is simple: identify a real problem, build the system around the workflow, measure what matters, and make the result dependable enough to use.

I am especially interested in the space between **software engineering, applied AI, and operations**: tools that reduce repetitive work, surface better decisions, connect fragmented systems, and turn domain knowledge into useful software.

Most of my AI work targets **Apple Silicon, Android, and consumer GPUs**, using Python, Swift/SwiftUI, Kotlin, TypeScript, MLX, MPS, llama.cpp, local inference runtimes, and conventional software engineering where AI is not the right tool.

---

## What I build

- **AI & agent systems** — local inference, tool use, durable tasks, retrieval, voice, model lifecycle, and bounded automation
- **Operations software** — custom internal tools, workflow automation, data integration, decision support, and reliability-focused utilities
- **Automotive solutions** — acquisition intelligence, wholesale workflows, transportation/logistics tooling, auction data, and buyer decision support
- **Analytics & evaluation** — dashboards, governed metrics, model benchmarking, evidence pipelines, uncertainty analysis, and reproducible reporting
- **Desktop & mobile products** — macOS, Android, Electron/React, accessible interfaces, offline-first workflows, and native integrations

---

## Featured projects

### [GemmaFischer](https://github.com/lukifer23/GemmaFischer)
**Local-first chess training and game-to-mastery system** · Python · Stockfish · MLX

Imports real games, identifies high-value decisions with a bounded Stockfish pipeline, turns mistakes into interactive lessons, supports delayed review, and keeps chess authority deterministic and auditable. Optional local-model work is isolated from grading and factual chess evaluation.

### [MacBot](https://github.com/lukifer23/MacBot)
**Private macOS AI assistant and local agent runtime** · Python · SwiftUI · llama.cpp

A native-first assistant for Apple Silicon with local inference, voice, document retrieval, durable tasks, encrypted local persistence, model lifecycle management, recovery tooling, and explicit capability boundaries. The project is designed around one owned runtime rather than a collection of loosely connected demos.

### [UMI — Unified Model Index](https://github.com/lukifer23/UMI---Unified-Model-Index)
**Auditable model evaluation and comparison framework** · Python

A reproducible system for comparing exact model configurations across capability, operational efficiency, and economics using governed public evidence. It includes source validation, uncertainty analysis, ablation, score certificates, dashboards, and fail-closed handling when evidence is incomplete.

### [svg-X](https://github.com/lukifer23/svg-X)
**Desktop + CLI raster-to-vector toolkit** · TypeScript · Electron · React

Converts raster images into SVG/EPS/DXF/JSON paths through multiple vectorization pipelines, including monochrome tracing, color-region reconstruction, and centerline output. Recent work focuses on bounded curve fitting, throughput, packaging, and regression-tested performance.

### [XReader](https://github.com/lukifer23/XReader)
**Privacy-focused Android reader** · Kotlin

A native reader for personal DRM-free libraries with local import, persistence, notes, search, reading continuity, and offline narration/audiobook workflows. Built around app-owned storage and local operation rather than mandatory cloud services.

### [MowerBoy](https://github.com/lukifer23/mowerboy)
**Accessible touch-first game for phones and tablets** · TypeScript

A deliberately simple, no-fail mowing and vacuuming game designed for one-finger play. It includes responsive touch controls, accessibility modes, offline support, reproducible releases, cross-platform hosting, and extensive browser/production verification.

---

## Operations, automotive & analytics

A significant part of my work is building **custom tools around operational problems**, especially where existing software leaves people stitching together spreadsheets, browser tabs, APIs, and repetitive manual decisions.

Current and ongoing work includes:

- **Automotive acquisition intelligence** — tools for wholesale buyers that combine auction context, vehicle data, pricing signals, rules, and decision support
- **Transportation & logistics workflows** — automation and coordination around dispatch, carrier workflows, status tracking, and operational handoffs
- **Analytics systems** — KPI design, dashboards, model/evidence comparison, operational reporting, and decision-support surfaces
- **Workflow automation** — connecting APIs and internal processes while keeping failure states visible and recoverable

Some domain-specific systems remain private while they are actively used, contain integration-sensitive work, or are being prepared for a cleaner public release.

---

## Other work

- **[Qwen 3.8 27B ternary-style quantization experiments](https://github.com/lukifer23/Qwen-3.8-27B-Ternary-Style-Quant-)** — activation-aware reconstruction and aggressive local-model compression experiments.
- **[Matrix0](https://github.com/lukifer23/Matrix0)** — AlphaZero-style chess engine with MCTS, self-play, and auxiliary tactical objectives.
- **[ChessTrainer](https://github.com/lukifer23/ChessTrainer)** — Android chess training with local engine analysis and foldable-friendly UI.
- **[Breakout-](https://github.com/lukifer23/Breakout-)** — offline Android brick-breaker built for phones and foldables.

---

## Engineering principles

| Area | Approach |
|---|---|
| **Solve the workflow** | Start from the actual operational problem, not from a preferred technology |
| **Local AI** | Run useful models on real consumer hardware when local execution makes sense |
| **Evaluation** | Prefer reproducible evidence, fixed configs, logs, benchmarks, and failure cases over vibes |
| **Agents** | Explicit authority, durable state, recoverable execution, bounded tools, visible failure modes |
| **Analytics** | Metrics should support decisions; definitions, provenance, and uncertainty should be clear |
| **Performance** | Measure latency, throughput, memory, Elo, quality gates, and regressions instead of guessing |
| **Product quality** | Persistence, accessibility, packaging, failure recovery, documentation, and real release checks matter |
| **Privacy** | Local-first by default when the product can reasonably support it |

---

## Current focus

- Local and on-device AI systems for **Apple Silicon, Android, and consumer GPUs**
- Custom **operations, automotive, and analytics software**
- Agent architecture, tool use, persistence, recovery, and computer interaction
- Small-model inference, post-training, compression, and evaluation
- Reproducible model benchmarking and evidence-backed comparison
- Workflow automation and API integrations for real operational systems
- Building complete applications around AI rather than isolated model demos

---

## Stack

**Languages:** Python · Swift/SwiftUI · Kotlin/Java · TypeScript/JavaScript · C/C++

**AI / ML:** MLX · PyTorch/MPS · llama.cpp · local LLM/VLM runtimes · LoRA/post-training · MCTS · ONNX

**Application & data work:** macOS · Android · Electron/React · FastAPI · SQLite · APIs/integrations · dashboards · operational analytics

---

## Elsewhere

- **GitHub:** [github.com/lukifer23](https://github.com/lukifer23)
- **Models / experiments:** [Hugging Face](https://huggingface.co/Dontbeafed69)

I am particularly interested in **applied AI, agents, model evaluation, automotive technology, operational tooling, analytics, and engineering work that turns domain knowledge into dependable software**.
