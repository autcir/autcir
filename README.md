<div align="center">

# Ciro Autuori

<!-- markdownlint-disable-next-line MD001 -->
### Founder @ StudioCentOS · software & AI studio · Salerno × Barcelona

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=16&pause=1200&color=F3F4F6&center=true&vCenter=true&width=600&lines=Founder+%40+StudioCentOS;Building+er0s+%E2%80%94+the+sovereign+agent+OS;Rust+%C2%B7+Next.js+%C2%B7+self-hosted+infrastructure;Your+server%2C+your+data%2C+your+code;Salerno+%C3%97+Barcelona)](https://git.io/typing-svg)

[![Website](https://img.shields.io/badge/studiocentos.com-0f172a?style=for-the-badge&logo=googlechrome&logoColor=38bdf8)](https://studiocentos.com)
[![er0s](https://img.shields.io/badge/er0s-engine-0f172a?style=for-the-badge&logo=rust&logoColor=f74c00)](https://studiocentos.com/er0s)
[![YouTube](https://img.shields.io/badge/YouTube-@autcir-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@autcir)
[![GitHub](https://img.shields.io/badge/GitHub-autcir-0f172a?style=for-the-badge&logo=github&logoColor=white)](https://github.com/autcir)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ciro_Autuori-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ciroautuori)
[![Instagram](https://img.shields.io/badge/@autcir-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/autcir)

</div>

---

## 🏛️ Autuori Holding — What We Run Today

| Brand | Domain | Role & Platform |
| --- | --- | --- |
| ⚙️ **er0s** | [studiocentos.com/er0s](https://studiocentos.com/er0s) | The digital office: deterministic kernel + 6 AI roles (CEO, CFO, CTO, COO, CBO, CLO) sharing one Brain, with a human approval gate — installed by hand on your own European server |
| 🏢 **StudioCentOS** | [studiocentos.com](https://studiocentos.com) | Ciro's software & AI studio — websites, digital offices and automations for professional studios and small businesses |
| 🧬 **my0s** | [my0s.com](https://my0s.com) | Your personal space online: @username showcase and QR, CV in PDF, linked-notes Second Brain |
| 🛒 **markettina** | [markettina.com](https://markettina.com) (paused) | Curated tech & desk-products store — only what passes the field use test enters the catalog |
| 🏙️ **salernos** | [salernos.it](https://salernos.it) | Independent guide to Salerno: what to see, eat and do, Luci d'Artista, getting around; free for local businesses to join |

| 🎬 **AutCir** | [youtube.com/@autcir](https://www.youtube.com/@autcir) · [autcir.studiocentos.com](https://autcir.studiocentos.com) | YouTube channel (Italian, audio in 5 languages): I really test AI tools and automation on real work, mistakes included |

**Customer cases** — see [studiocentos.com](https://studiocentos.com/#prodotti).

---

## 🔧 Building Now — er0s Architecture

One Rust codebase runs every company of the holding and every client, with data isolated per organization:

- **Engine** (`er0s-*` crates, Rust) — the agent runtime: providers, the native Brain (memory + lessons), permissions and guardrails. No vendored forks, fully ours.
- **Laya** — local System1 decision engine: decides among closed options on the small on-server model, never authoritative over what it decides (replaces external judgment).
- **er0s-api** (Rust) — the only server: logic and data live here; the Next.js web layer is pure presentation (brand sites, back office, console).
- **Multi-tenant by design** — every client is an isolated organization; clients with their own node run it on their server with their own credentials. **Fail-closed** everywhere; the merge on `main` never deploys by itself.
- **Deterministic kernel first** — calculations run without model calls (zero token cost); models are connected only where the project requires them.

---

## 🐍 Contribution Activity

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/autcir/autcir/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/autcir/autcir/output/github-contribution-grid-snake.svg">
    <img alt="GitHub Contribution Snake" src="https://raw.githubusercontent.com/autcir/autcir/output/github-contribution-grid-snake-dark.svg" width="100%">
  </picture>
</div>

---

## ⚡ Tech Stack & Infrastructure

![Rust](https://img.shields.io/badge/Rust-CE422B?style=for-the-badge&logo=rust&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python_3.12-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC2626?style=for-the-badge&logo=qdrant&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Arch Linux](https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=archlinux&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

---

## 🚀 Key Open-Source Repositories

- ⚡ [**Openvidia**](https://github.com/autcir/openvidia) — Multi-key proxy for NVIDIA NIM with native desktop dashboard: auto-rotation, cooldowns, RPM limiting, Claude Code + Codex CLI + opencode support
- 🎙️ [**Whispy**](https://github.com/autcir/whispy) — Local & multi-provider voice dictation for Linux (whisper.cpp, Groq, OpenAI, Faster-Whisper) — hold a key, speak, release
- 💻 [**ArchLegion**](https://github.com/autcir/archlegion) — Automated Arch Linux DevOps workstation setup for Lenovo Legion (GPU switching, hardening, NVIDIA Optimus)
- 💻 [**ArchLOQ**](https://github.com/autcir/archloq) — Automated Arch Linux setup for Lenovo LOQ 17IRX10 (NVIDIA Blackwell RTX 5060, power/fan/CPU tuning, KDE Plasma Wayland dotfiles)
- 🦐 [**Awesome Salerno**](https://github.com/autcir/awesome-salerno) — Curated list of resources for Salerno, the Amalfi Coast and the Cilento

---

<div align="center">
  <sub>© 2026 Ciro Autuori · Autuori Holding</sub>
</div>
