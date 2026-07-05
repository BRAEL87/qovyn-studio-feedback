# 🌌 Qovyn Studio — Premium Agentic IDE

[![Version](https://img.shields.io/badge/version-1.1.0-blue.svg)](https://qovyn-studio.vercel.app)
[![Status](https://img.shields.io/badge/status-active-success.svg)](https://qovyn-studio.vercel.app)
[![License](https://img.shields.io/badge/license-proprietary-red.svg)](https://qovyn-studio.vercel.app/terms)

> **Qovyn Studio** is a next-generation, high-performance agentic IDE designed for autonomous software development. By leveraging frontier AI models and native agentic workflows, Qovyn transforms the IDE from a text editor into a true autonomous collaborator.

---

## 🚀 The Agentic Edge

Qovyn Studio is built for developers who demand peak productivity. It goes beyond autocomplete to offer a full-cycle development experience.

* **🔄 Autonomous Agent Loops**: Agents can plan, execute, and self-critique complex multi-file changes.
* **🐙 Deep GitHub Integration**: Build, commit, list issues, and open Pull Requests directly from the agent interface.
* **⚡ Free Frontier Models**: Powered by **Puter.js**, providing access to high-end models without subscription friction.
* **🧠 Hierarchical Memory**: Long-term task retention and context-aware reasoning.

---

## 💰 Why Qovyn beats $20/month subscriptions

The market is flooded with $20/month AI coding tools. Qovyn Studio gives you more for less — or for free.

| Feature | Qovyn Studio | Claude Code / Codex |
|---|---|---|
| **Pricing** | Free tier available — $0 to start | $20/month minimum |
| **Models** | Bring your own API key or use free Puter.js models | Locked to their model |
| **Provider fallback** | 18 providers in an automatic fallback chain — if one fails, the next takes over | Single provider, single point of failure |
| **Agent loop** | Autonomous plan → execute → verify cycle with self-correction | Basic chat with file read/write |
| **File snapshots** | Automatic file snapshots before every mutation — revert any change | No built-in revert |
| **Inline completion** | Context-aware, no-subscription completion via the same provider chain | Included, but only with subscription |
| **Diff view** | Side-by-side Monaco diff for every agent change | Text-only diffs |
| **Privacy Shield** | Auto-excludes sensitive files (.env, .pem, credentials) from agent context | Manual configuration required |
| **Terminal integration** | Full PowerShell terminal with command execution, async commands, and session management | Limited terminal access |

**The bottom line**: If you already have an API key (OpenAI, Anthropic, Google, Groq, etc.), Qovyn costs you nothing. You use your own quota at cost price — no monthly markup. And if you want to start for free, Puter.js gives you access to frontier models immediately.

---

## 🔧 Features that matter

### True autonomy, not just chat

Qovyn's agent loop is structurally different from a chatbot with file access. Each turn follows a disciplined cycle:

1. **Think** — the agent analyzes the task and context
2. **Act** — one mutation per turn (write, edit, delete, create) plus any number of reads
3. **Verify** — the system automatically lists the parent directory after every mutation so the agent confirms the result
4. **Repeat** — the agent continues until all plan items are complete or it needs clarification

This means the agent never races ahead creating three files at once and assuming success. It confirms each step before proceeding — like a senior developer reviewing their own work.

### 18-provider fallback chain

Qovyn doesn't lock you into one model. Configure multiple providers and the system cascades through them automatically on failure:

```
OpenAI → Anthropic → Google Gemini → Groq → OpenRouter → GitHub Models
→ Azure OpenAI → Together AI → DeepInfra → Cerebras → NVIDIA NIM
→ Fireworks AI → Mistral AI → OpenCode AI → Kimi → Z.ai
→ Wafer AI → Puter.js (free)
```

Your workflow never stops because one API is down.

### File snapshots & revert

Before every file mutation, Qovyn takes a snapshot of the affected files. You can revert to any point in the agent's timeline — undoing changes file by file or in bulk. No more "the AI broke my code and I can't get it back."

### Diff preview for every change

Every write, edit, or replacement the agent makes can be opened in Monaco's side-by-side diff editor. Green for new lines, red for removed — clear, visual, immediate.

### Terminal as a first-class tool

The agent runs real PowerShell commands, not simulations. It can execute builds, run tests, install packages, check file existence, and read command output — all within the same loop that writes your code.

---

## 📥 Getting Started

Qovyn Studio is currently in **Early Access**.

1. **Download**: Get the latest build for your OS from the [Official Website](https://qovyn-studio.vercel.app).
2. **Install**:
   * **Windows**: Run the `.exe`. Note: As an indie project, you may see a "SmartScreen" warning. Click *More Info* -> *Run Anyway*.
   * **macOS and Linux**: Coming soon.
3. **Connect**: Link your GitHub account to enable autonomous PR workflows.

### First run

Open the app, switch to **Agent mode**, and try:

```
Create a responsive navbar component with HTML, CSS, and a dark mode toggle
```

Watch the agent plan the files, create them one by one, verify each step, and report back. No $20 subscription required.

---

## 💬 Community & Feedback

This repository is the dedicated hub for the Qovyn Studio community. While the core engine remains proprietary, we are committed to building Qovyn in the open with our users.

* **🐛 Bug Reports**: Use the [Issues](https://github.com/braeljr/qovyn-studio-feedback/issues) tab to report reproducible bugs.
* **💡 Feature Requests**: Have an idea for a new agent tool? Open a [Discussion](https://github.com/braeljr/qovyn-studio-feedback/discussions).
* **📖 Documentation**: Check our [Docs](https://qovyn-studio.vercel.app/docs) for advanced configuration.

---

## 🛡️ Privacy & Security

Qovyn Studio is designed with a **Privacy-First** architecture:
* **Privacy Shield**: Sensitive files (`.env`, `.pem`, etc.) are automatically ignored by the AI agent.
* **Local Processing**: File indexing and context synthesis happen entirely on your local machine.
* **Your key, your cost**: When using your own API keys, Qovyn charges nothing — you pay only what your provider charges.

---

## 🗺️ Roadmap

* macOS and Linux native builds
* Agent version control with visual branch timeline
* Custom tool creation API
* Team collaboration mode with shared agent contexts
* VS Code extension mode

---

*Built with ❤️ by the Qovyn Studio Team.*
