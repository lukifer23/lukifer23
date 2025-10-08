# Luke Scaggs — On-Device AI, Apple-Silicon First

**I build privacy-first, on-device AI for Apple Silicon and Android** — local LLM chat (**IRISStar**), a low-latency Mac voice assistant (**MacBot**), chess engines that both play and teach (**Matrix0**, **GemmaFischer**), and a high-fidelity PNG→SVG tool (**svg-X**). **Releases, benchmarks, and clear docs.**

- **Focus:** Apple Silicon (M-series) & Snapdragon • local LLMs • realtime voice • chess engines • vectorization  
- **Philosophy:** Results > rhetoric. If it’s not measurable, it’s not done.

---

## Now
- Publishing **GemmaFischer** LoRA adapters on HF + tutor-mode evals  
- Tagging **IRISStar v0.1** with a signed APK + device matrix  
- Recording short demo clips and adding latency/Elo/tokens-per-second tables across repos

---

## Highlights (keep current as you measure)
- **MacBot** median STT latency: ~**N** ms on **M3 Pro** @ 16 kHz  
- **Matrix0** strength: ~**ELO** at **TC** (vs fixed baseline)  
- **svg-X**: average SVG size ↓ **X%** vs baseline on complex logos

> Tip: keep this section honest and tiny—three numbers maximum, updated as releases land.

---

## Selected Work
- **[MacBot](https://github.com/lukifer23/MacBot)** — local VAD → Whisper v3 → LLM → TTS with a live dashboard (macOS). *Goal:* <300 ms STT median, responsive barge-in, simple app bundle.
- **[IRISStar](https://github.com/lukifer23/IRISStar)** — Android offline LLM client (GGUF) tuned for Snapdragon/Apple GPU backends. *Goal:* signed APK + device/perf matrix.
- **[Matrix0](https://github.com/lukifer23/Matrix0)** — self-play chess engine with SSL heads, Apple-Silicon optimizations, and a web UI. *Goal:* provisional Elo ladder @ 5+0 with a small checkpoint.
- **[GemmaFischer](https://github.com/lukifer23/GemmaFischer)** — MoE chess LLM (UCI + tutor mode). *Action:* link LoRA adapters on HF + tutor-mode eval harness.
- **[svg-X](https://github.com/lukifer23/svg-X)** — PNG→SVG with quantization + curve fitting (desktop/CLI). *Goal:* .dmg + AppImage + 10-sec before/after GIF.

---

## Quick Links
**Releases:**  
[MacBot → Releases](https://github.com/lukifer23/MacBot/releases) •
[IRISStar → Releases](https://github.com/lukifer23/IRISStar/releases) •
[Matrix0 → Releases](https://github.com/lukifer23/Matrix0/releases) •
[GemmaFischer → Releases](https://github.com/lukifer23/GemmaFischer/releases) •
[svg-X → Releases](https://github.com/lukifer23/svg-X/releases)


<details>
<summary><b>Results at a Glance</b></summary>

| Project     | Metric            | Value  | Notes                                   |
|---          |---                |---:    |---                                      |
| MacBot      | STT latency (p50) | **N** ms | 16 kHz, streaming VAD → Whisper v3       |
| IRISStar    | Tokens/s          | **N**   | 3–7B GGUF on recent Snapdragon           |
| Matrix0     | Elo @ 5+0         | **N**   | vs fixed baseline depth/time             |
| GemmaFischer| Tutor eval score  | **N**%  | rubric: clarity + correctness            |
| svg-X       | Size reduction     | **X**%  | vs baseline on complex logos             |

*Details live in each repo’s `/results` with exact commands, models, and seeds.*
</details>

---

## Roadmap (short and public)
- **IRISStar:** signed APK on tag; “What’s different from upstream” + crash-safe loader; perf presets (4B-Lite / 7B-Balanced / 13B-Max).  
- **MacBot:** zipped macOS app bundle; two short audio demos; latency table (median/p95) by device.  
- **Matrix0:** upload a small checkpoint; publish Elo vs baseline; web-UI GIF.  
- **GemmaFischer:** HF LoRA adapters; UCI demo script; tutor-mode transcript GIF; small eval harness.  
- **svg-X:** macOS .dmg + Linux AppImage; 10-sec before/
