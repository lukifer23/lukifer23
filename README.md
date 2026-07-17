# Lukifer23

On-device AI for hardware people actually own.

I build local-first systems on **Apple Silicon** and **Android**: voice agents, small-model training and fine-tunes, chess engines, and practical desktop/mobile tools. The throughline is simple — privacy by default, measurable performance, and evidence before hype.

- **Current focus:** offline voice pipelines, chess evaluation / self-play, Android readers & on-device apps, vectorization tooling
- **Working rule:** if a result matters, it should have a config, a log, a benchmark, or a release artifact
- **Primary targets:** macOS (Metal / MLX / MPS), Android (Kotlin / on-device inference)

---

## Selected Work

### Local AI

**[MacBot](https://github.com/lukifer23/MacBot)** · Python · ⭐ flagship voice stack  
Offline macOS voice assistant with an interruptible pipeline: VAD → Whisper STT → local LLM (llama.cpp) → neural TTS. Metal acceleration, native macOS tools, secure local RAG, and a realtime WebSocket dashboard.

**[GemmaFischer](https://github.com/lukifer23/GemmaFischer)** · Python · [HF adapters](https://huggingface.co/collections/Dontbeafed69/gemmafischer-chess-engine-and-tutor-with-mixture-of-experts-68e6a915d31285cda968d204)  
Fine-tuned Gemma-3 as a UCI chess engine + interactive tutor. LoRA experts (UCI / tutor / director), MoE-style routing, and Apple Silicon MPS training/inference.

**[Matrix0](https://github.com/lukifer23/Matrix0)** · Python  
AlphaZero-style chess engine with SSL heads for tactical pattern recognition (threats, pins, forks, control). Multi-task RL on a ResNet backbone, MCTS, MPS optimization, WebUI, and fixed-baseline benchmarking.

### Tools & Apps

**[svg-X](https://github.com/lukifer23/svg-X)** · TypeScript · [releases](https://github.com/lukifer23/svg-X/releases)  
Desktop + CLI image→SVG converter (Electron/React). Triple pipeline: Potrace B&W, color posterization with Bezier fitting, and centerline stroke mode. Exports SVG / EPS / DXF / JSON paths.

**[XReader](https://github.com/lukifer23/XReader)** · Kotlin  
Native Android e-reader for DRM-free personal libraries. SAF import, app-private storage, multi-format conversion into a Readium path, local notes/bookmarks/search — no cloud required.

**[ChessTrainer](https://github.com/lukifer23/ChessTrainer)** · Java  
On-device Android chess trainer with local Stockfish / LC0 engines, lessons, analysis, and foldable-friendly UI.

**[Breakout-](https://github.com/lukifer23/Breakout-)** · Kotlin  
Offline brick-breaker built for phones and foldables: OpenGL rendering, fixed-step physics, multiple modes and powerups, no network or analytics SDK.

---

## Lab notes

Work in progress tends to stay private until configs, evals, and docs are honest enough to ship. Themes that show up across public and private repos:

- **Local LLMs** — post-training, adapters, and small-model stacks aimed at real devices
- **Realtime voice** — interruptible STT → LLM → TTS loops with latency budgets
- **Chess + evaluation** — engines, tutors, self-play, and reproducible match gates
- **Android privacy tools** — readers, on-device assistants, offline-first mobile apps

---

## How I ship

| Principle | Practice |
|---|---|
| **Local first** | Privacy by default; Apple Silicon primary, Android/Snapdragon where it fits |
| **Measured progress** | tokens/sec, latency, Elo, perplexity, pass rates, and failure examples over vibes |
| **Readable repos** | configs, docs, scripts, and run logs so work is reproducible without archaeology |
| **Releases when ready** | binaries, model artifacts, and notable metrics live on each project's Releases / HF / results |

---

## Elsewhere

- **GitHub:** [github.com/lukifer23](https://github.com/lukifer23)
- **Models:** [Hugging Face](https://huggingface.co/Dontbeafed69) (GemmaFischer LoRA collection)

For project-specific questions, open an issue in the relevant repo. For collaboration, start with the project closest to what you want to build or test.
