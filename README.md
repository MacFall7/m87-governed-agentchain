# M87 Governed Claude AgentChain

> A fully governed orchestration framework for Claude sub-agents — with audit loops, emotional safety, and secure output handling.
> ⚠️ Heads up: This repo contains the orchestration engine only.  
> Prompt scaffolds, ClaudeDocs patterns, and session kits will be released separately.  
> DM Mac @ M87 Studio for early access or integration notes.
---

## 🎯 Overview

This project provides a **governed agent execution loop** compatible with Claude’s `~/.claude/commands/` system. It lets you run sub-agents for task orchestration, coding, and review — with built-in safety, test protection, and emotional signal modulation.

Originally built by [M87 Studio](https://www.m87studio.net), this open framework gives you:

- ✅ Modular agent orchestration via Claude-compatible `.md` prompts
- 🔒 Test integrity enforcement (no test rewriting)
- 🧠 Emotion-aware complexity tuning
- 🧾 Output logging, rerun-on-failure, and safe delivery

---

## 📂 Structure

```
.
├── .claude/
│   └── commands/
│       └── m87_governed_agentchain.md   # Main orchestrator file
├── examples/
│   ├── TASK.md                          # Task spec file
│   └── emotion_signal.json              # Emotional state input
├── docs/
│   └── governance-overview.pdf          # Optional architecture PDF
└── README.md
```

---

## 🚀 Quick Start

### 1. Install Claude CLI (if not done)
Follow Anthropic's instructions or your Claude CLI tool setup.

### 2. Copy the command file
Move the `m87_governed_agentchain.md` to your Claude command folder:
```bash
mkdir -p ~/.claude/commands/
cp .claude/commands/m87_governed_agentchain.md ~/.claude/commands/
```

### 3. Run it inside Claude:
```
/m87_governed_agentchain
```

---

## 🛡️ Governance Features

- **SPOT** — Flags data policy violations in output
- **FORT** — Prevents test modification or leakage
- **PARCEL** — Ensures safe output delivery
- **Emotion Signal Modulation** — Adjusts plan difficulty & tone based on user emotion

---

## 📖 Use Cases

- Secure multi-agent orchestration in LLM workflows
- Automated code generation and review with audit trails
- Emotionally adaptive feedback for safer task complexity

---

## 🧠 Origin

Developed by M87 Studio as part of the **Filament Governance Layer** and **MELD Emotional AI System**, this repo demonstrates a safe, extensible pattern for responsible agent orchestration.

Learn more: [www.m87studio.net](https://www.m87studio.net)

---

## 📄 License

MIT License — feel free to fork, adapt, and use with attribution.

---

### 📡 Join the M87 Testnet or Stakeholder Circle

If you're experimenting with Claude, Gemini, or governed agent workflows and want to get involved:

- 🧠 Join the early-access testnet  
- 💬 Chat with the dev team on Discord  
- 🚀 Stakeholder demos now forming

**→ [discord.gg/m87studio](https://discord.gg/m87studio)**  
**→ [github.com/MacFall7](https://github.com/MacFall7)**

Let’s build agent systems that deserve trust.
© 2025 M87 Studio. All rights reserved.
