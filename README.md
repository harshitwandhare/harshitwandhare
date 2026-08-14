<h1 align="center">Harshit Wandhare</h1>

<p align="center">
  <b>Software Engineer</b> · production systems end to end — backend, infrastructure, mobile
</p>
<p align="center">
  🎓 <b>M.S. Computer Science — UT Dallas</b> (Intelligent Systems) · 📍 Richardson, TX
</p>

<p align="center">
  <a href="https://harshitwandhare.com"><img src="https://img.shields.io/badge/Portfolio-harshitwandhare.com-A3480A?style=for-the-badge" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/harshit-wandhare-a088201aa/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:Harshit.Wandhare@utdallas.edu"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<p align="center">
  🟢 <b>Open to Summer 2027 SWE and AI/ML internships</b>
</p>

---

I build production systems end to end — and have shipped them alone. Three years across
enterprise platforms serving **100K+ monthly users** at Reliance Jio, then the **entire
engineering function** at a three-person company in Germany: architecture, web, mobile,
integrations, auth, cloud, CI and release.

## 💼 Experience

**Product Engineer — Yosemite Crew (DuneXploration UG, Germany)** · Remote · 2025–2026
Sole engineer-owner of [**YosemiteCrew/Yosemite-Crew**](https://github.com/YosemiteCrew/Yosemite-Crew) —
an open-source veterinary practice-management system — at a three-person company.
[**1,200+ commits**](https://github.com/search?q=repo%3AYosemiteCrew%2FYosemite-Crew+author-name%3A%22Harshit+Wandhare%22&type=commits)
on a project that has grown past **2,000 GitHub stars**. Designed HL7/FHIR-aligned clinical data models; integrated IDEXX
Laboratories and Merck Veterinary Manual APIs; built the auth stack on AWS Cognito and Amplify
Gen 2 (Lambda OTP triggers, WebAuthn passkeys, TOTP MFA, OAuth) and led its migration to
SuperTokens; owned Lambda/S3/CloudFront/Redis and the GitHub Actions estate across three
codebases in a Turborepo monorepo. Shipped the React Native app to **both stores**, ran customer
discovery, and hired and onboarded the engineer who followed.

**Software Development Engineer I — Reliance Jio Platforms** · 2023–2025
**Rated A\***, the firm's highest annual performance category. Ran daily scrum for a
**30-engineer** program spanning 10+ modules and solo-owned two of them end to end, across
products serving **100K+ monthly active users**. Designed the SDK layer for secure
WebView-to-native message passing between React Native shells and embedded Angular/Next.js
apps — adopted as the standard integration layer. Built an internal CMS on Next.js and Strapi;
cut average page load **~40%** via an Angular 17 SSR migration on EC2.

## 🚀 Featured work

**[ATLAS](https://github.com/harshitwandhare/atlas-ra)** — a multi-team AI agent system built
like infrastructure, not a demo. An orchestrator routes goals to specialist teams and a
**Critic verifies every result** before it counts as done. **Three memory tiers** (episodic
SQLite ledger · embedding-backed semantic store queried by vector similarity · versioned skill
playbooks) let it compound across runs, and
destructive host actions are **approval-gated in code, not prompts**. Three interchangeable
runtimes — Claude Agent SDK, LangGraph, fully-local Ollama — behind one typed protocol.
**[Live dashboard →](https://atlas-ra.vercel.app)**

> Python · FastAPI · asyncio · Next.js · WebSocket · SQLite · `mypy --strict` · 59 tests ·
> behavioural evals gating CI · MIT

**[Job Sentinel](https://github.com/harshitwandhare/job-sentinel)** — a local-first,
open-source career platform: aggregates postings across sources, scores role fit with a local
or bring-your-own-key LLM, tracks the whole application pipeline, and generates ATS-tuned
résumés — all on your own machine, nothing leaves it. Ships a clip-to-track browser extension,
a Typer CLI, a Next.js UI and a FastAPI backend.
**[Live demo →](https://job-sentinel.vercel.app)** · [docs](https://harshitwandhare.github.io/job-sentinel/)

> Python · FastAPI · Playwright · Next.js · SQLite · `mypy --strict` · 500+ tests ·
> CI gates: CodeQL · OpenSSF Scorecard · gitleaks · pip-audit · license compliance · MIT

**[Portfolio](https://github.com/harshitwandhare/portfolio)** — this site's source.
The centrepiece is a *tipkyanchi rangoli* — a dot lattice with a single unbroken line drawn
around every dot — solved live in the browser, then drawn over a year of real commit history.
**[harshitwandhare.com →](https://harshitwandhare.com)**

> Next.js · TypeScript strict · Playwright × 4 browsers · axe · Lighthouse 100/100/100/100 · MIT

## 🔬 Research

**Integrating YOLOv5 and CNN for Number Plate Recognition** — first author, unpublished
manuscript. YOLOv5 detector at **95.45% mAP** (88.7% precision, 96.4% recall) and a custom CNN
over 36 character classes at **89.66%** accuracy, with an OpenCV preprocessing stack
(Hough deskew, contour segmentation) and a local CUDA training environment.

**A Comprehensive Survey of Methodologies in Social Media Analytics for Disaster Management** —
first author, unpublished manuscript.

## 🧰 Tech

**Languages:** Python · TypeScript · JavaScript · Java · SQL · Bash
**AI/ML:** PyTorch · OpenCV · YOLOv5 & CNNs · LLM agent systems (Claude Agent SDK · LangGraph · Ollama) · RAG · embeddings & vector search · CUDA
**Backend & Data:** FastAPI · Node/Express · Spring Boot · REST · WebSockets · Redis · PostgreSQL · MongoDB · MySQL · SQLite
**Cloud & Infrastructure:** AWS (Cognito · Lambda · S3 · CloudFront · Amplify) · Docker · GitHub Actions · Linux · Turborepo
**Testing & Quality:** pytest · Jest · Playwright · mypy `--strict` · CodeQL · Gitleaks · SonarCloud
**Frontend & Mobile:** React · Next.js · Angular · React Native · Redux · Tailwind

*Currently learning:* Rust

## 🎓 Education

- **M.S. Computer Science**, The University of Texas at Dallas — *Intelligent Systems* ·
  Jonsson School Dean's Graduate Scholarship
- **B.E. Computer Engineering**, University of Mumbai (Vidyalankar Institute) — **CGPA 9.53/10**

---

<p align="center">
  <sub>The stat cards that used to sit here were served by a third party that started
  returning 500s. Rather than swap in another one that will break next month, the work is
  linked above — it speaks for itself.</sub>
</p>
