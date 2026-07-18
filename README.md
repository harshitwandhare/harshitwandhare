<h1 align="center">Harshit Wandhare</h1>

<p align="center">
  <b>Full-Stack & AI/ML Software Engineer</b> · 3+ years shipping production web &amp; mobile at scale
</p>
<p align="center">
  🎓 <b>MS in Computer Science — UT Dallas</b> (Fall 2026, Intelligent Systems) ·
  🔬 <b>Generative AI Systems Research Assistant</b> — UTD ATC 3D Studio (LightSquad) · 📍 Richardson, TX
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/harshit-wandhare-a088201aa/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:harshitwandhare45@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://job-sentinel.vercel.app"><img src="https://img.shields.io/badge/Live_Project-059669?style=for-the-badge&logo=vercel&logoColor=white" alt="Live project" /></a>
  <img src="https://komarev.com/ghpvc/?username=harshitwandhare&color=059669&style=for-the-badge&label=Profile+views" alt="Profile views" />
</p>

<p align="center">
  🟢 <b>Open to SWE &amp; AI/ML internships and new-grad roles</b> — I love building reliable systems end to end.
</p>

---

I build production-grade software from the ground up — from cross-platform apps used by **100K+ people**
to **local-first, open-source AI tooling**. Previously an SDE at **Reliance Jio** and Product Engineer at
**Yosemite Crew**; now focused on **AI/ML systems** and engineering open source to a professional bar
(typed end-to-end, tested, CI-gated, documented).

## 🚀 Featured work

<a href="https://github.com/harshitwandhare/atlas-ra">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=harshitwandhare&repo=atlas-ra&theme=transparent&hide_border=true" alt="ATLAS" />
</a>

**[ATLAS](https://github.com/harshitwandhare/atlas-ra)** — a **multi-team AI agent system** built like
infrastructure, not a demo: an orchestrator routes goals to specialist teams, a **Critic verifies every
result** before it counts as done, **three memory tiers** (episodic SQLite ledger · semantic store ·
versioned skill playbooks) make it compound over time, and destructive host actions are
**human-approval-gated in code**, not prompts. Three interchangeable agent runtimes (Claude Agent SDK /
LangGraph / **fully-local Ollama**) behind one typed protocol, a live WebSocket dashboard, an eval
harness gating CI, and ready-to-load **ComfyUI / TouchDesigner / StreamDiffusion** workflows for
generative-video work on a 10 GB VRAM budget.
**[Live dashboard →](https://atlas-ra.vercel.app)**

> Python · FastAPI · asyncio · Next.js 14 · WebSocket · SQLite · `mypy --strict` · 55 tests incl. full
> e2e · behavioral evals in CI · Storybook · Vercel CD · MIT

<a href="https://github.com/harshitwandhare/job-sentinel">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=harshitwandhare&repo=job-sentinel&theme=transparent&hide_border=true" alt="Job Sentinel" />
</a>

**[Job Sentinel](https://github.com/harshitwandhare/job-sentinel)** — a local-first, open-source career
platform: searches jobs across multiple sources, scores how well your profile matches a role with a
**local (or bring-your-own-key) LLM**, tracks your whole application pipeline, and generates **ATS-tuned
résumés &amp; cover letters** — all on your own machine, nothing leaves it. Ships with a **clip-to-track
browser extension**, a Next.js web UI, a Typer CLI, and a FastAPI backend.
**[Live demo →](https://job-sentinel.vercel.app)** · [docs](https://harshitwandhare.github.io/job-sentinel/)

> Python · FastAPI · Playwright · Next.js/React · SQLite · `mypy --strict` · ~450 tests ·
> CI gates: CodeQL · OpenSSF Scorecard · gitleaks · pip-audit · license compliance · reproducible `uv.lock` builds · MIT

**[Kalki](https://github.com/harshitwandhare/kalki)** — an autonomous AI content-generation platform:
LLM-scripted short-form video with automated media processing and scheduled publishing.

## 💼 Experience

**Generative AI Systems Research Assistant — UT Dallas, ATC 3D Studio (LightSquad)** · 2026–
Real-time generative pipelines on constrained GPUs: **StreamDiffusion** deployment on Windows/CUDA
(xformers + TensorRT acceleration, benchmarked), an **OSC-controlled TouchDesigner bridge** for live
AI video, and **ComfyUI workflows** for LoRA training and **Wan 2.2** image-to-video inside a 10 GB
VRAM budget.

**Product Engineer — Yosemite Crew (DuneXploration UG, Germany)** · Remote · 2025–2026
Single-handedly built the **entire cross-platform React Native app and the web PIMS frontend** for an
open-source veterinary platform that grew to **2.1k+ GitHub stars, 78 forks, 3,100+ commits**. Integrated
IDEXX Labs &amp; Merck Veterinary Manual APIs; ran the full AWS stack (Amplify, Cognito, S3, CloudFront)
plus Supabase/Redis; shipped to the App Store &amp; Play Store; authored 14 GitHub Actions workflows
(CodeQL, Gitleaks, SonarCloud, Chromatic, Playwright E2E).
*(Full-time under the company account [@harshit-yc](https://github.com/harshit-yc).)*

**Software Development Engineer I — Reliance Jio Platforms** · 2023–2025
Built and maintained high-traffic web &amp; mobile apps serving **100K+ monthly active users** (React,
Next.js, Angular, React Native). Shipped a shared React + TypeScript component library adopted by **3+
teams** and cut average page load **~40%** via SSR and performance tuning.

## 🔬 AI / ML

**Agentic systems** — [ATLAS](https://github.com/harshitwandhare/atlas-ra): multi-team orchestration
with critic verification, three-tier memory, and approval-gated host execution; provider-agnostic across
Claude Agent SDK, LangGraph, and fully-local Ollama.

**Real-time diffusion** — StreamDiffusion on consumer CUDA hardware (xformers/TensorRT, benchmarked),
TouchDesigner live-video bridge over OSC, ComfyUI LoRA-training and Wan 2.2 video workflows engineered
for a 10 GB VRAM ceiling.

**Parkify — Automated Number-Plate Recognition** (undergraduate research): an end-to-end YOLOv5 +
custom-CNN pipeline reaching **95.45% mAP** detection and **89.66%** character-recognition accuracy, with
an OpenCV preprocessing stack and a local CUDA training setup.

## 🧰 Tech

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000?logo=next.js&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?logo=node.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

**Languages:** TypeScript · Python · JavaScript · Java
**Frontend/Mobile:** React · Next.js · Angular · React Native · Tailwind
**Backend/Data:** Node/Express · FastAPI · Spring Boot · Supabase · Redis · MySQL · MongoDB
**Cloud/DevOps:** AWS · Docker · CI/CD · SonarCloud · Playwright
**AI/ML:** PyTorch · OpenCV · YOLOv5/CNNs · agentic systems (Claude Agent SDK · LangGraph · Ollama) ·
RAG · diffusion pipelines (StreamDiffusion · ComfyUI · Wan 2.2) · CUDA/TensorRT · quantization

## 🎓 Education

- **M.S. Computer Science**, The University of Texas at Dallas — *Intelligent Systems*, Fall 2026
- **B.E. Computer Engineering**, University of Mumbai (Vidyalankar Institute) — **CGPA 9.53/10**

---

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=harshitwandhare&show_icons=true&hide_rank=true&theme=transparent&hide_border=true" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=harshitwandhare&layout=compact&hide=html,css&theme=transparent&hide_border=true" alt="Top languages" />

<br/>

<img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=harshitwandhare&theme=transparent&hide_border=true" alt="GitHub streak" />

</div>
