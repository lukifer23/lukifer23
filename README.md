# Lukifer23 — On-Device AI, Apple-Silicon First

**I build privacy-first, on-device AI for Apple Silicon and Android** — local LLM chat (**IRISStar**), a low-latency Mac voice assistant (**MacBot**), chess engines that play *and* teach (**Matrix0**, **GemmaFischer**), and a high-fidelity PNG→SVG tool (**svg-X**).

- **Focus:** Apple Silicon (M-series) & Snapdragon • local LLMs • realtime voice • chess engines • vectorization  
- **Philosophy:** Results > rhetoric. If it’s not measurable, it’s not done.

---

## Now
- Finalizing **GemmaFischer**: LoRA adapters on HF + tutor-mode evaluations + transcript examples  
- Next up: **IRISStar** (packaging, device matrix) → **MacBot** (demos, latency table) → **Matrix0** (checkpoint, Elo ladder)

> I’ll add numbers and binaries here *after* they’re published in each repo’s Releases.

---

## Selected Work (with status)

**Legend:** 🚀 available • 🛠️ active update • 🔬 research/prototype

- 🚀 **[svg-X](https://github.com/lukifer23/svg-X)** — PNG→SVG with quantization + curve fitting (desktop/CLI).  
  *Cross-platform app; releases available in the repo.*

- 🛠️ **[GemmaFischer](https://github.com/lukifer23/GemmaFischer)** — MoE chess LLM (UCI + tutor mode).  
  *Linking LoRA adapters on HF and adding a small eval harness + tutor transcripts.*

- 🛠️ **[IRISStar](https://github.com/lukifer23/IRISStar)** — Android offline LLM client (GGUF) tuned for Snapdragon/Apple GPU backends.  
  *Packaging and a concise device/perf matrix are in progress.*

- 🛠️ **[MacBot](https://github.com/lukifer23/MacBot)** — local VAD → Whisper v3 → LLM → TTS with a live dashboard (macOS).  
  *Short demo clips and a simple latency table are coming alongside a pre-alpha app bundle.*

- 🛠️ **[Matrix0](https://github.com/lukifer23/Matrix0)** — self-play chess engine with SSL heads and a web UI.  
  *Publishing a small checkpoint and a provisional Elo ladder vs a fixed baseline.*

- 🔬 **[FusterCluck](https://github.com/lukifer23/FusterCluck)** — compact text-only LLM training pipeline for Apple Silicon.  
  *Early-stage; staged curriculum and tooling are public.*

---

## How I work
- **On-device first:** privacy by default; minimal dependencies; clear fallbacks.  
- **Reproducible setups:** pinned configs and end-to-end quickstarts.  
- **Evidence over adjectives:** when a metric or binary exists, it appears in the repo’s **Releases** and **/results**.

---

## Where to find releases
- Each project publishes artifacts **in its own repo** under **Releases** when ready.  
- I’ll surface notable numbers (latency, tokens/s, Elo, size deltas) here once they’re live.

---

## Contact
- X / email / website: *add your links here*  
- Issues and PRs welcome.
