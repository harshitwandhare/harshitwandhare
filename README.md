<h1 align="center">Harshit Wandhare</h1>

<p align="center">
  Software and product engineer. Three years shipping production systems: backend, cloud, web, mobile.<br />
  M.S. Computer Science, UT Dallas (Intelligent Systems), expected May 2028.
</p>

<p align="center">
  <a href="https://harshitwandhare.com"><img src="https://img.shields.io/badge/Portfolio-harshitwandhare.com-A3480A?style=for-the-badge" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/harshit-wandhare-a088201aa/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:Harshit.Wandhare@utdallas.edu"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<p align="center">
  <b>Open to Summer 2027 software, product and AI/ML engineering internships</b><br />
  Richardson, TX · open to relocation · drawn to forward-deployed engineering, where the
  product work and the customer are the same conversation
</p>

<p align="center">
  <a href="https://github.com/YosemiteCrew/Yosemite-Crew/commits/main?author=harshit%40yosemitecrew.com"><img src="https://img.shields.io/badge/1%2C394%20commits-more%20than%20anyone%20else%20on%20the%20repo-1f6feb?style=flat-square" alt="1,394 commits on Yosemite Crew, more than any other contributor" /></a>
  <a href="https://github.com/YosemiteCrew/Yosemite-Crew"><img src="https://img.shields.io/github/stars/YosemiteCrew/Yosemite-Crew?style=flat-square&label=stars%20on%20that%20project&color=8957e5" alt="Stars on Yosemite Crew" /></a>
  <img src="https://img.shields.io/badge/100K%2B-monthly%20users%20served%20at%20Jio-238636?style=flat-square" alt="100K+ monthly users" />
  <img src="https://img.shields.io/badge/A%2A-top%20annual%20rating%20at%20Jio-bb8009?style=flat-square" alt="A* rating" />
</p>

---

I like owning a system from the schema to the store listing, and I like being close enough to the
user to know which half of it matters. At Reliance Jio I ran daily scrum for a 30-engineer program
and solo-owned two of its modules, on products serving 100K+ monthly users. Then I was the engineer
at a three-person company in Germany, where I built the platform, shipped the mobile app to both
stores, ran the customer discovery calls, wrote the specs, and hired and onboarded the engineer who
came after me.

That mix is why forward-deployed and product engineering interest me: sitting with the people using
the thing, then going and building it. Right now I am deep in agent systems and developer tooling,
and writing a lot of Rust badly on purpose.

## Experience

**Product Engineer, Yosemite Crew (DuneXploration UG, Germany)** · Remote · 2025 to 2026

Owned engineering for [**YosemiteCrew/Yosemite-Crew**](https://github.com/YosemiteCrew/Yosemite-Crew),
an open-source veterinary practice-management system, at a three-person company. Wrote
[**1,394 commits, more than any other contributor on the
project**](https://github.com/YosemiteCrew/Yosemite-Crew/commits/main?author=harshit%40yosemitecrew.com), which has
since passed 2,000 GitHub stars. Designed HL7/FHIR-aligned clinical data models. Integrated IDEXX
Laboratories and Merck Veterinary Manual APIs. Built the auth stack on AWS Cognito and Amplify Gen 2
(Lambda OTP triggers, WebAuthn passkeys, TOTP MFA, OAuth) and led its migration to SuperTokens.
Owned Lambda, S3, CloudFront, Redis and the GitHub Actions estate across three codebases in a
Turborepo monorepo. Shipped the React Native app to both stores, ran customer discovery calls, and
onboarded the next engineer against specs I wrote.

**Software Development Engineer I, Reliance Jio Platforms** · Navi Mumbai · 2023 to 2025

Rated **A\***, the firm's highest annual performance category. Ran daily scrum for a
**30-engineer** program spanning 10+ modules and solo-owned two of them end to end, across products
serving **100K+ monthly active users**. Designed the SDK layer for secure WebView-to-native message
passing between React Native shells and embedded Angular and Next.js apps, which became the standard
integration layer across products. Built an internal CMS on Next.js and Strapi. Cut average page
load **~40%** with an Angular 17 SSR migration on EC2.

## Featured work

**[ATLAS](https://github.com/harshitwandhare/atlas-ra)** is a multi-team AI agent system built like
infrastructure rather than a demo. An orchestrator routes goals to specialist teams and a **Critic
verifies every result** before it counts as done. **Three memory tiers** (an episodic SQLite ledger,
an embedding-backed semantic store queried by vector similarity, and versioned skill playbooks) let
it compound across runs, and destructive host actions are **approval-gated in code, not in prompts**.
Three interchangeable runtimes, Claude Agent SDK, LangGraph and fully-local Ollama, sit behind one
typed protocol. **[Live dashboard](https://atlas-ra.vercel.app)**

> Python · FastAPI · asyncio · Next.js · WebSocket · SQLite · `mypy --strict` · 59 tests ·
> behavioural evals gating CI · MIT

**[Job Sentinel](https://github.com/harshitwandhare/job-sentinel)** is a local-first, open-source
career platform. It aggregates postings across sources, scores role fit with a local or
bring-your-own-key LLM, tracks the whole application pipeline, and generates ATS-tuned résumés,
all on your own machine with nothing leaving it. Ships a clip-to-track browser extension, a Typer
CLI, a Next.js UI and a FastAPI backend.
**[Live demo](https://job-sentinel.vercel.app)** · [docs](https://harshitwandhare.github.io/job-sentinel/)

> Python · FastAPI · Playwright · Next.js · SQLite · `mypy --strict` · 500+ tests ·
> CI gates: CodeQL · OpenSSF Scorecard · gitleaks · pip-audit · license compliance · MIT

**[Portfolio](https://github.com/harshitwandhare/portfolio)** is this site's source. The centrepiece
is a *tipkyanchi rangoli*, a dot lattice with a single unbroken line drawn around every dot, solved
live in the browser and then drawn over a year of real commit history.
**[harshitwandhare.com](https://harshitwandhare.com)**

> Next.js · TypeScript strict · Playwright across 4 browsers · axe · Lighthouse 100/100/100/100 · MIT

## Research

**[Integrating YOLOv5 and CNN for Number Plate Recognition](https://harshitwandhare.com/papers/number-plate-recognition.pdf)**,
first author. A YOLOv5 detector at **95.45% mAP** (88.7% precision, 96.4% recall) and a custom CNN
over 36 character classes at **89.66%** accuracy, with an OpenCV preprocessing stack (Hough deskew,
contour segmentation) trained on a local CUDA setup.

**[A Comprehensive Survey of Methodologies in Social Media Analytics for Disaster
Management](https://harshitwandhare.com/papers/social-media-disaster-management.pdf)**, first author.

## Tech

**Languages:** Python · TypeScript · JavaScript · Java · SQL · Bash
**AI/ML:** PyTorch · OpenCV · YOLOv5 and CNNs · LLM agent systems (Claude Agent SDK · LangGraph · Ollama) · RAG · embeddings and vector search · CUDA
**Backend and data:** FastAPI · Node/Express · Spring Boot · REST · WebSockets · Redis · PostgreSQL · MongoDB · MySQL · SQLite
**Cloud and infrastructure:** AWS (Cognito · Lambda · S3 · CloudFront · Amplify) · Docker · GitHub Actions · Linux · Turborepo
**Testing and quality:** pytest · Jest · Playwright · mypy `--strict` · CodeQL · Gitleaks · SonarCloud
**Frontend and mobile:** React · Next.js · Angular · React Native · Redux · Tailwind

*Learning:* Rust

## Education

**M.S. Computer Science**, The University of Texas at Dallas, Intelligent Systems track, expected
May 2028. Jonsson School Dean's Graduate Scholarship.

**B.E. Computer Engineering**, University of Mumbai (Vidyalankar Institute), **CGPA 9.53/10**.
