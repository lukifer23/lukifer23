# Lukifer23 - Local AI Systems on Apple Silicon

I build local-first AI systems that run on hardware people actually own: small language-model training stacks, realtime Mac voice agents, chess engines, and practical desktop tools.

The throughline is simple: on-device performance, reproducible configs, and evidence before hype.

- **Current focus:** Apple Silicon MLX training, local LLM post-training, realtime voice, chess evaluation, vectorization.
- **Working rule:** if a result matters, it should have a config, a log, a benchmark, or a release artifact.

---

## Current Lab

- **Dense80M v1 / AnarchoBot:** from-scratch dense GPT-style training on Apple Silicon, with a ChatML + FIM tokenizer, staged corpus tooling, MLX checkpoints, eval gates, and SFT -> DPO alignment path.
- **MacBot:** low-latency local voice assistant for macOS: VAD -> Whisper -> local LLM -> TTS, with a dashboard and latency tracking.
- **GemmaFischer / Matrix0:** chess-model work focused on tutor behavior, self-play evaluation, transcripts, checkpoints, and reproducible match results.

---

## Selected Work

**[AnarchoBot](https://github.com/lukifer23/AnarchoBot)**

Apple Silicon language-model training stack for compact ChatML models. Current work includes Dense80M v1 pretraining, tokenizer/data manifests, post-training configs, and checkpoint/eval runbooks.

**[MacBot](https://github.com/lukifer23/MacBot)**

Offline macOS voice assistant with an interruptible local pipeline, Metal acceleration, native tool integrations, secure local RAG, and a realtime dashboard.

**[svg-X](https://github.com/lukifer23/svg-X)**

PNG-to-SVG desktop and CLI tool using quantization and curve fitting. Releases are available in the repo.

**[GemmaFischer](https://github.com/lukifer23/GemmaFischer)**

Chess LLM work around UCI play, tutor-mode responses, LoRA adapters, evaluation harnesses, and transcript quality.

**[Matrix0](https://github.com/lukifer23/Matrix0)**

Self-play chess engine work with SSL heads, checkpoint tracking, web UI experiments, and fixed-baseline evaluation.

---

## How I Ship

- **Local first:** privacy by default, Apple Silicon as the primary target, Android/Snapdragon where it makes sense.
- **Measured progress:** tokens/sec, latency, Elo, perplexity, pass rates, and failure examples beat vague claims.
- **Readable repos:** configs, docs, scripts, and run logs should make the work reproducible without archaeology.
- **Releases when ready:** binaries, model artifacts, and notable metrics live in each project's own Releases/results surfaces.

---

## Contact

For project-specific questions, open an issue in the relevant repo. For collaboration, start with the project that is closest to what you want to build or test.
