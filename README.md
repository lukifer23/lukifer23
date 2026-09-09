# Luke Scaggs

**AI/software systems builder · commercial products · operations tooling · automotive software · analytics · local-first AI**

I build practical software for real workflows — from commercial desktop products and custom operational systems to local AI, model evaluation, automotive tooling, and analytics.

My work spans **AI agents, computer vision, geospatial measurement, model evaluation, post-training experiments, automotive acquisition tooling, workflow automation, analytics, chess systems, desktop software, and Android applications**. The common thread is simple: identify a real problem, build around the actual workflow, measure what matters, and make the result dependable enough to use.

I am especially interested in the space between **software engineering, applied AI, and operations**: tools that reduce repetitive work, surface better decisions, connect fragmented systems, and turn domain knowledge into useful software. Some of that work becomes internal tooling; some becomes public software; some has gone on to commercial use.

Most of my AI work targets **Apple Silicon, Android, and consumer GPUs**, using Python, Swift/SwiftUI, Kotlin, TypeScript, MLX, MPS, llama.cpp, ONNX, local inference runtimes, and conventional software engineering where AI is not the right tool.

---

## What I build

- **Commercial & custom software** — end-to-end products and tailored systems built around specific workflows and users
- **AI & agent systems** — local inference, tool use, durable tasks, retrieval, voice, model lifecycle, and bounded automation
- **Operations software** — custom internal tools, workflow automation, data integration, decision support, and reliability-focused utilities
- **Automotive solutions** — acquisition intelligence, wholesale workflows, transportation/logistics tooling, auction data, and buyer decision support
- **Analytics & evaluation** — dashboards, governed metrics, model benchmarking, evidence pipelines, uncertainty analysis, and reproducible reporting
- **Desktop & mobile products** — macOS, Android, Electron/React, accessible interfaces, offline-first workflows, and native integrations

---

## Featured projects

### [StreetSpec](https://github.com/lukifer23/StreetSpec)
**Commercial geospatial measurement and computer-vision desktop application** · Electron · React · TypeScript · ONNX

Cross-platform software for measuring real-world objects from Google Street View imagery using camera geometry, depth data, calibration workflows, and local Depth Anything V2 inference through ONNX Runtime. It includes point, polyline, area, and volume measurements; confidence scoring; depth caching; CSV export; Google Maps/Solar integrations; and packaged desktop workflows. Originally developed as a commercial product and later sold; the source is now public following the applicable confidentiality period.

### [MacBot](https://github.com/lukifer23/MacBot)
**Local-first macOS AI assistant and agent runtime** · Python · SwiftUI · llama.cpp

A native-first assistant for Apple Silicon with local inference, voice, document retrieval, durable tasks, encrypted local persistence, model lifecycle management, recovery tooling, and explicit capability boundaries. The project is designed around one owned runtime rather than a collection of loosely connected demos.

### [GemmaFischer](https://github.com/lukifer23/GemmaFischer)
**Local-first chess training and game-to-mastery system** · Python · Stockfish · MLX

Imports real games, identifies high-value decisions with a bounded Stockfish pipeline, turns mistakes into interactive lessons, supports delayed review, and keeps chess authority deterministic and auditable. Optional local-model work is isolated from grading and factual chess evaluation.

### [UMI — Unified Model Index](https://github.com/lukifer23/UMI---Unified-Model-Index)
**Auditable model evaluation and comparison framework** · Python

A reproducible system for comparing exact model configurations across capability, operational efficiency, and economics using governed public evidence. It includes source validation, uncertainty analysis, ablation, score certificates, dashboards, and fail-closed handling when evidence is incomplete.

### [svg-X](https://github.com/lukifer23/svg-X)
**Desktop + CLI raster-to-vector toolkit** · TypeScript · Electron · React

Converts raster images into SVG/EPS/DXF/JSON paths through multiple vectorization pipelines, including monochrome tracing, color-region reconstruction, and centerline output. Recent work focuses on bounded curve fitting, throughput, packaging, and regression-tested performance.

### [XReader](https://github.com/lukifer23/XReader)
**Privacy-focused Android reader** · Kotlin

A native reader for personal DRM-free libraries with local import, persistence, notes, search, reading continuity, analytics, and offline narration/audiobook workflows. Built around app-owned storage and local operation rather than mandatory cloud services.

---

## Operations, automotive & analytics

A significant part of my work is building **custom tools around operational problems**, especially where existing software leaves people stitching together spreadsheets, browser tabs, APIs, and repetitive manual decisions.

Current and ongoing work includes:

- **Automotive acquisition intelligence** — tools for wholesale buyers that combine auction context, vehicle data, pricing signals, rules, and decision support
- **Transportation & logistics workflows** — automation and coordination around dispatch, carrier workflows, status tracking, and operational handoffs
- **Analytics systems** — KPI design, dashboards, model/evidence comparison, operational reporting, and decision-support surfaces
- **Workflow automation** — connecting APIs and internal processes while keeping failure states visible and recoverable
- **Commercial product development** — taking domain-specific ideas from problem definition through implementation, packaging, deployment, and real-world use

Some domain-specific systems remain private while they are actively used, contain integration-sensitive work, or are being prepared for a cleaner public release.

---

## Other work

- **[MowerBoy](https://github.com/lukifer23/mowerboy)** — accessible touch-first mowing and vacuuming game with offline play and cross-platform release verification.
- **[Qwen 3.8 27B ternary-style quantization experiments](https://github.com/lukifer23/Qwen-3.8-27B-Ternary-Style-Quant-)** — activation-aware reconstruction and aggressive local-model compression experiments.
- **[Matrix0](https://github.com/lukifer23/Matrix0)** — AlphaZero-style chess engine with MCTS, self-play, and auxiliary tactical objectives.
- **[ChessTrainer](https://github.com/lukifer23/ChessTrainer)** — Android chess training with local engine analysis and foldable-friendly UI.
- **[Breakout-](https://github.com/lukifer23/Breakout-)** — offline Android brick-breaker built for phones and foldables.

---

## Engineering principles

| Area | Approach |
|---|---|
| **Solve the workflow** | Start from the actual operational problem, not from a preferred technology |
| **Commercial usefulness** | Build for deployment, handoff, reliability, and real users — not just demos |
| **Local AI** | Run useful models on real consumer hardware when local execution makes sense |
| **Evaluation** | Prefer reproducible evidence, fixed configs, logs, benchmarks, and failure cases over vibes |
| **Agents** | Explicit authority, durable state, recoverable execution, bounded tools, visible failure modes |
| **Analytics** | Metrics should support decisions; definitions, provenance, and uncertainty should be clear |
| **Performance** | Measure latency, throughput, memory, Elo, quality gates, and regressions instead of guessing |
| **Product quality** | Persistence, accessibility, packaging, failure recovery, documentation, and real release checks matter |
| **Privacy** | Local-first by default when the product can reasonably support it |

---

## Current focus

- Applied AI and custom software for **operations, automotive, analytics, and domain-specific workflows**
- Local and on-device AI systems for **Apple Silicon, Android, and consumer GPUs**
- Agent architecture, tool use, persistence, recovery, and computer interaction
- Computer vision, geospatial tooling, and measurement systems
- Small-model inference, post-training, compression, and evaluation
- Reproducible model benchmarking and evidence-backed comparison
- Workflow automation and API integrations for real operational systems
- Building complete applications around AI rather than isolated model demos

---

## Stack

**Languages:** Python · Swift/SwiftUI · Kotlin/Java · TypeScript/JavaScript · C/C++

**AI / ML:** MLX · PyTorch/MPS · llama.cpp · ONNX Runtime · local LLM/VLM runtimes · LoRA/post-training · MCTS · computer vision

**Application & data work:** macOS · Android · Electron/React · FastAPI · SQLite · APIs/integrations · dashboards · operational analytics · geospatial tooling

---

## Elsewhere

- **GitHub:** [github.com/lukifer23](https://github.com/lukifer23)
- **Models / experiments:** [Hugging Face](https://huggingface.co/Dontbeafed69)

I am particularly interested in **applied AI, commercial software, agents, model evaluation, automotive technology, operational tooling, analytics, computer vision, and engineering work that turns domain knowledge into dependable products**.
