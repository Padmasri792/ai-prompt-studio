# ⚡ AI Prompt Studio

> Build, test, manage, and reuse AI prompts — with live variable substitution, multi-model tagging, history, and one-click export. Zero dependencies, runs entirely in the browser.

![Version](https://img.shields.io/badge/version-1.0-teal) ![License](https://img.shields.io/badge/license-MIT-green) ![Zero Dependencies](https://img.shields.io/badge/dependencies-zero-blue)

## 🖥️ Live Demo

➡️ **[Open Prompt Studio](https://padmasri792.github.io/ai-prompt-studio/ai-prompt-studio.html)**

---

## ✨ Features

| Feature | Description |
|---|---|
| 📝 **Prompt Editor** | Monospace editor with live character count |
| `{{variables}}` | Auto-detect and fill dynamic variables inline |
| 🤖 **Model Targeting** | Tag prompts for GPT-4o, Claude 3.5, Gemini 2.0, Llama 3.3, Mistral |
| 🏷️ **Tags & Categories** | Organise by type: Writing, Code, Legal, Marketing, Research, Creative |
| ▶️ **Run & Compile** | Substitutes all variables and shows the final ready-to-paste prompt |
| 📊 **Token Estimator** | Live word / character / ~token count on every run |
| 🕓 **History** | Last 50 runs saved in-session, click to reload any |
| 💾 **Save & Library** | Full prompt library with sidebar search |
| 📤 **Export / Import** | Download all prompts as JSON, re-import on any device |
| 🌙 **Dark / Light Mode** | System preference + manual toggle |
| 📱 **Responsive** | Works on desktop, tablet, and mobile |

---

## 🚀 Quick Start

```bash
# Clone the repo
git clone https://github.com/Padmasri792/ai-prompt-studio.git
cd ai-prompt-studio

# Open directly in browser — no build step needed
open ai-prompt-studio.html
```

Or just **download `ai-prompt-studio.html`** and open it — it's fully self-contained.

---

## 💡 How to Use Variables

Wrap any dynamic part in double curly braces:

```
You are a {{role}} expert. Write a {{word_count}}-word {{content_type}} about {{topic}} for {{audience}}.
Tone: {{tone}}. Make it {{style}}.
```

The studio **auto-detects all variables**, shows input fields for each, and on **Run** produces the final compiled prompt with everything substituted.

---

## 📦 Built-in Starter Prompts

- **Blog Post Writer** — Content marketing with tone/audience control
- **Code Reviewer** — Multi-language code review with security checks  
- **Legal Brief Summary** — Plain-English legal document summaries (UK/India compatible)

---

## 🛠️ Tech Stack

- **Pure HTML + CSS + Vanilla JS** — zero npm, zero build tools
- Lucide Icons (CDN)
- JetBrains Mono + Inter (Google Fonts)
- Nexus Design System tokens
- OKLCH color space for precise theming

---

## 🗺️ Roadmap

- [ ] Folder/collection grouping
- [ ] Prompt versioning (diff view)
- [ ] Share prompt via URL
- [ ] OpenAI / Anthropic API direct call integration
- [ ] Prompt scoring & analytics
- [ ] Team collaboration mode

---

## 📄 License

MIT — free to use, fork, and build on.

---

*Built with ❤️ in 2026 — designed for AI practitioners, legal tech professionals, and builders.*
