# Luke Scaggs

**AI systems builder · local-first software · model evaluation · practical tooling**

I build software around a simple idea: advanced AI should be useful on hardware people actually own.

My work spans **local AI agents, model evaluation, post-training experiments, chess systems, desktop tooling, and Android applications**, with an emphasis on privacy, reproducibility, measurable performance, and software that survives contact with real users.

Most of my projects target **Apple Silicon, Android, and consumer GPUs**, using Python, Swift/SwiftUI, Kotlin, TypeScript, MLX, MPS, llama.cpp, local inference runtimes, and conventional software engineering where AI is not the right tool.

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

## Other work

- **[Qwen 3.8 27B ternary-style quantization experiments](https://github.com/lukifer23/Qwen-3.8-27B-Ternary-Style-Quant-)** — activation-aware reconstruction and aggressive local-model compression experiments.
- **[Matrix0](https://github.com/lukifer23/Matrix0)** — AlphaZero-style chess engine with MCTS, self-play, and auxiliary tactical objectives.
- **[ChessTrainer](https://github.com/lukifer23/ChessTrainer)** — Android chess training with local engine analysis and foldable-friendly UI.
- **[Breakout-](https://github.com/lukifer23/Breakout-)** — offline Android brick-breaker built for phones and foldables.

---

## What I care about

| Area | Approach |
|---|---|
| **Local AI** | Run useful models on real consumer hardware; minimize unnecessary cloud dependency |
| **Evaluation** | Prefer reproducible evidence, fixed configs, logs, benchmarks, and failure cases over vibes |
| **Agents** | Explicit authority, durable state, recoverable execution, bounded tools, visible failure modes |
| **Performance** | Measure latency, throughput, memory, Elo, quality gates, and regressions instead of guessing |
| **Product quality** | Persistence, accessibility, packaging, failure recovery, documentation, and real release checks matter |
| **Privacy** | Local-first by default when the product can reasonably support it |

---

## Current focus

- Local and on-device AI systems for **Apple Silicon, Android, and consumer GPUs**
- Small-model inference, post-training, compression, and evaluation
- Agent architecture, tool use, persistence, recovery, and computer interaction
- Reproducible model benchmarking and evidence-backed comparison
- Building complete applications around AI rather than isolated model demos

---

## Stack

**Languages:** Python · Swift/SwiftUI · Kotlin/Java · TypeScript/JavaScript · C/C++

**AI / ML:** MLX · PyTorch/MPS · llama.cpp · local LLM/VLM runtimes · LoRA/post-training · MCTS · ONNX

**Application work:** macOS · Android · Electron/React · FastAPI · SQLite · native desktop/mobile integration

---

## Elsewhere

- **GitHub:** [github.com/lukifer23](https://github.com/lukifer23)
- **Models / experiments:** [Hugging Face](https://huggingface.co/Dontbeafed69)

I am particularly interested in **local AI, model evaluation, agents, applied ML, and engineering work that turns research capabilities into dependable software**.
