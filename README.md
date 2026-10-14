<h1 align="center">Harshit Wandhare</h1>

<p align="center">
  Software and product engineer. Three years shipping production systems: backend, cloud, web, mobile.<br />
  M.S. Computer Science, UT Dallas (Intelligent Systems), expected May 2028.
</p>

<p align="center">
  <a href="https://harshitwandhare.com"><img src="https://img.shields.io/badge/Portfolio-harshitwandhare.com-A3480A?style=for-the-badge" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/harshit-wandhare/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:Harshit.Wandhare@utdallas.edu"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<p align="center">
  <b>Open to Summer 2027 software, product and AI/ML engineering internships</b><br />
  Richardson, TX · open to relocation · drawn to forward-deployed engineering, where the
  product work and the customer are the same conversation
</p>

<p align="center">
  <a href="#open-source-contributions"><img src="https://img.shields.io/badge/28%20pull%20requests-merged%20into%20Google%2C%20AWS%2C%20NVIDIA%20%26%20Anthropic%20repos-8957e5?style=flat-square" alt="28 pull requests merged into upstream repositories" /></a>
  <a href="https://apps.apple.com/us/app/yosemite-crew/id6756180296"><img src="https://img.shields.io/badge/Shipped%20to%20both%20app%20stores-React%20Native%2C%20empty%20repo%20to%20release-1f6feb?style=flat-square" alt="Mobile app shipped to the App Store and Google Play" /></a>
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

**Student Assistant, Identity and Access Management, UT Dallas Office of Information Technology** · Richardson · 2026 to present

Identity and access management for university-wide systems, on Python and Django deployed on AWS.
Design and maintain **RBAC role hierarchies** and primary-permission mappings governing access
across enterprise systems, implement **row-level permissions and database-level access controls**
enforcing least privilege, and run recurring audits for over-provisioned accounts and stale role
assignments. Build reusable reference components for the internal Django platform to standardise
provisioning workflows, and maintain the legacy Perl automation behind identity provisioning.

**Product Engineer, Yosemite Crew (DuneXploration UG, Germany)** · Remote · 2025 to 2026

Owned engineering for Yosemite Crew, an open-source veterinary practice-management system, at a
three-person company. Wrote **1,394 commits, more than any other engineer on the project**. Built
the React Native app from an empty repository and shipped it to the
[**App Store**](https://apps.apple.com/us/app/yosemite-crew/id6756180296) and
[**Google Play**](https://play.google.com/store/apps/details?id=com.mobileappyc), owning builds,
signing, store listings and review. Designed HL7/FHIR-aligned clinical data models. Integrated IDEXX
Laboratories and Merck Veterinary Manual APIs. Built sign-in on AWS Cognito and Amplify Gen 2,
covering OAuth across several identity providers and email with one-time codes, and wrote the
integration docs the backend engineer worked from. Owned Lambda, S3, CloudFront, Redis and the
GitHub Actions estate across three codebases in a Turborepo monorepo. Ran requirements-gathering
interviews with practising veterinarians, vet nurses and
practice owners, mapping their workflows and the systems they already used, and turned the findings
into the roadmap. Hired and onboarded the next engineer against specs I wrote.

**Software Development Engineer I, Reliance Jio Platforms** · Navi Mumbai · 2023 to 2025

Rated **A\***, the firm's highest annual performance category. Ran daily scrum for a
**30-engineer** program spanning 10+ modules and solo-owned two of them end to end, across products
serving **100K+ monthly active users**. Designed the SDK layer for secure WebView-to-native message
passing between React Native shells and embedded Angular and Next.js apps, which became the standard
integration layer across products. Built an internal CMS on Next.js and Strapi. Cut average page
load **~40%** with an Angular 17 SSR migration on EC2.

## Open source contributions

**28 pull requests merged into other companies' repositories** since August 2026, **23 of them
into agent orchestration frameworks**. Every one is public and checkable.

| Repository | Owner | Language | Merged |
| --- | --- | --- | --- |
| [awslabs/cli-agent-orchestrator](https://github.com/awslabs/cli-agent-orchestrator/pulls?q=is%3Apr+is%3Amerged+author%3Aharshitwandhare) | AWS | Python | **16** |
| [google/adk-go](https://github.com/google/adk-go/pulls?q=is%3Apr+is%3Amerged+author%3Aharshitwandhare) | Google | Go | **5** |
| [anthropics/buffa](https://github.com/anthropics/buffa/pulls?q=is%3Apr+is%3Amerged+author%3Aharshitwandhare) | Anthropic | Rust | **4** |
| [a2aproject/a2a-js](https://github.com/a2aproject/a2a-js/pulls?q=is%3Apr+is%3Amerged+author%3Aharshitwandhare) | Agent2Agent / Linux Foundation | TypeScript | **2** |
| [NVIDIA/cosmos-framework](https://github.com/NVIDIA/cosmos-framework/pulls?q=is%3Apr+is%3Amerged+author%3Aharshitwandhare) | NVIDIA | Python | **1** |

The ones I would point at first, because they say what kind of engineer I am more than a count does:

- **`fix(api): make the same-origin check scheme-aware`** and **`fix(api): make _origin_authority
  total against a malformed Origin`** (awslabs). Two security fixes to an origin check that was
  neither scheme-aware nor safe against a malformed header.
- **`test(remoteagent): name the awaited event instead of panicking on a closed channel`**
  (adk-go). A concurrency bug that failed by panicking rather than by saying what it was waiting on.
- **`fix(llminternal): classify a dropped live connection by type, not by error string`** (adk-go).
- **`fix(mcp): enforce a profile's tools allowlist for assign and handoff`** (awslabs). A tool
  allowlist that was not being checked on two code paths.

The method is the same every time: reproduce it first, write the test that fails before the fix,
state the broken invariant in one sentence, and run the project's own CI gates locally before
opening the pull request.

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

**Languages:** Python · TypeScript · JavaScript · Java · Go · Rust · C++ · SQL · Bash
**AI/ML:** PyTorch · OpenCV · YOLOv5 and CNNs · LLM agent systems (Claude Agent SDK · LangGraph · Ollama) · RAG · embeddings and vector search · CUDA
**Backend and data:** FastAPI · Django · Node/Express · Spring Boot · REST · GraphQL · WebSockets · Redis · PostgreSQL · MongoDB · MySQL · SQLite
**Cloud and infrastructure:** AWS (Cognito · Lambda · S3 · CloudFront · Amplify) · Docker · GitHub Actions · Linux · Turborepo
**Testing and quality:** pytest · Jest · Playwright · mypy `--strict` · CodeQL · Gitleaks · SonarCloud
**Frontend and mobile:** React · Next.js · Angular · React Native · Redux · Tailwind


## Education

**M.S. Computer Science**, The University of Texas at Dallas, Intelligent Systems track, expected
May 2028. Jonsson School Dean's Graduate Scholarship.

**B.E. Computer Engineering**, University of Mumbai (Vidyalankar Institute), **CGPA 9.53/10**.
