<h1 align="center">Satura Izhato Rufi</h1>
<p align="center"><i>D4 Telecommunications Engineering — Politeknik Negeri Semarang</i></p>

<p align="center">
  <code>ya vybirayu logiku</code> — i choose logic
</p>

---

### about

Telecom engineering student building toward an edge-deployed AI security stack as thesis work. Comfortable moving between signal theory coursework and full systems — networking, embedded vision, local LLM orchestration.

Currently on Ubuntu 24.04, living mostly in the terminal.

### currently building — Project Nexus / Dozor

A home-server AI orchestration framework ("Cyrene"), designed as a 4-layer system: ingress/gateway, intent routing, context/state management, and an event bus feeding out to modular "satellites."

- 🛰️ **[Lazarus Guard](https://github.com/AyamGorengMadura/lazarus-guard)** — face recognition access control. 936-dim landmark embeddings, cosine similarity matching, publishing live match/unknown events to Redis with debounce/cooldown logic.
- 🧠 **Contextual Module** — tiered trust system (owner / family / guest / unknown), static-assigned trust to resist manipulation over time, backing a context-injection pipeline for the framework's local LLM narrator.
- 🔀 **Router** — local Ollama-based intent classifier, feeding a Postgres + pgvector memory layer (active / episodic / archival tiers).
- 🗺️ **[nexus-docs](https://github.com/AyamGorengMadura/nexus-docs)** — the full technical writeup, drafted as thesis material.

### other projects

- 💬 **CliChat** — a terminal chat app built for a networking coursework project: curses TUI, auth, DMs, admin commands, and encryption, deployed over Tailscale.

### stack

`Python` · `Redis` · `PostgreSQL / pgvector` · `Ollama (Qwen2.5)` · `Docker` · `Linux (Ubuntu / Arch)` · `Zsh + Starship`

---

<p align="center"><sub>semarang, id</sub></p>
