<h1 align="center">Nirbhay Aggarwal</h1>
<p align="center"><strong>Software Engineer</strong> · Security &amp; ML Security · Homelab Builder</p>

<p align="center">
  <a href="https://nirbhay.dev">
    <img src="https://img.shields.io/badge/Website-nirbhay.dev-E3B341?style=for-the-badge" alt="Website" />
  </a>
  <a href="https://linkedin.com/in/nirbagga/">
    <img src="https://img.shields.io/badge/LinkedIn-0A0A0C?style=for-the-badge&logo=linkedin&logoColor=E3B341" alt="LinkedIn" />
  </a>
  <a href="mailto:hi@nirbhay.dev">
    <img src="https://img.shields.io/badge/Email-hi%40nirbhay.dev-0A0A0C?style=for-the-badge&logo=maildotru&logoColor=E3B341" alt="Email" />
  </a>
  <a href="https://github.com/nirbhayagga">
    <img src="https://img.shields.io/badge/GitHub-0A0A0C?style=for-the-badge&logo=github&logoColor=E3B341" alt="GitHub" />
  </a>
</p>

<p align="center">
  <strong>Live projects:</strong><br/>
  <a href="https://wikigolf.app">
    <img src="https://img.shields.io/badge/Play-WikiGolf-E3B341?style=for-the-badge" alt="Play WikiGolf" />
  </a>
  <a href="https://sudoku.nirbhay.dev">
    <img src="https://img.shields.io/badge/Play-Sudoku-E3B341?style=for-the-badge" alt="Play Sudoku" />
  </a>
  <a href="https://boardroom.nirbhay.dev">
    <img src="https://img.shields.io/badge/Play-Boardroom-E3B341?style=for-the-badge" alt="Play Boardroom" />
  </a>
  <a href="https://clientcrypt.nirbhay.dev">
    <img src="https://img.shields.io/badge/Try-ClientCrypt-E3B341?style=for-the-badge" alt="Try ClientCrypt" />
  </a>
  <a href="https://stepwise.nirbhay.dev">
    <img src="https://img.shields.io/badge/Try-Stepwise-E3B341?style=for-the-badge" alt="Try Stepwise" />
  </a>
  <a href="https://ragshield.dev">
    <img src="https://img.shields.io/badge/Visit-RAG_Shield-E3B341?style=for-the-badge" alt="Visit RAG Shield" />
  </a>
  <a href="https://rallyradio.onrender.com">
    <img src="https://img.shields.io/badge/Play-Rally_Radio-E3B341?style=for-the-badge" alt="Play Rally Radio" />
  </a>
</p>

---

### About Me

I'm a software engineer pursuing an **MS in Computer Science at UNLV** (expected May 2027), after finishing my BS in 2025. Lately that work is AI security: provenance for RAG pipelines and LLM-rewritten phishing. I build software to explore what I'm learning and to solve problems for people I know.

I work as a **Public Service Intern at UNLV OIT**, where I lead the annual audit verification of 8,000+ IT assets, and run a Proxmox and TrueNAS homelab. Open to full-time security, AppSec, and ML security roles starting in **2027**, as well as software and infrastructure work.

---

### Highlighted Projects

- **[RAG Shield](https://ragshield.dev):** Provenance for RAG pipelines. Signs every chunk at ingestion (SHA-256 plus an Ed25519 ledger), scores only what an edit adds, and drops tampered or unknown chunks before the model sees them. Caught 125 of 125 direct vector-store edits; a classifier fine-tuned on public data raised detection of prompt-injection edits from 23% to 97.6% at 3.2% false alarms on held-out documents with a calibrated threshold. Coursework startup project; source private for now.
- **PhishGuard:** Can LLM rewrites get phishing past detectors? A 28,899-email corpus with links scored in a separate channel, TF-IDF and DistilBERT detectors, and LLM-rewrite and adaptive attacks. Rewrites rarely evaded (0.4–3.1% at 1% FPR) and Claude refused most requests, but every trained detector ranked poorly on modern email (AUC 0.52–0.71) while zero-shot Claude Opus reached 0.96–0.99. Course project; source private for now.
- **[WikiGolf](https://wikigolf.app):** A two-pass Rust parser turns the English Wikipedia dump into a 7.2M-article link graph. The public game runs as a static export; a separate Rust server supports live path queries.
- **[PalDash](https://github.com/paldash/paldash):** Built for the Palworld server I host for friends. Combines monitoring and a world map with binary save editing, server-state checks, verified backups, and rollback checks.
- **[ClientCrypt](https://clientcrypt.nirbhay.dev):** Started with my cryptography coursework. RustCrypto runs in WebAssembly, inputs stay in the browser, and FIPS/RFC test vectors check the results.
- **[Stepwise](https://stepwise.nirbhay.dev):** Started with my algorithms coursework. Recorded execution frames let you step backward through algorithms, CPU schedules, and simulated thread interleavings.

Also built [Sudoku](https://sudoku.nirbhay.dev) for ad-free play with generated puzzles, hints, and a custom solver; [Boardroom](https://boardroom.nirbhay.dev) for remote game nights; [Rally Radio](https://rallyradio.onrender.com), a browser kart racer where a blindfolded driver follows a sighted navigator's calls; and firetv-reclaim, which replaces a Fire TV's ad-filled home screen without root. **Boardroom's hosted demo is AI-only; online multiplayer requires the self-hosted Node server.**

Team and coursework projects include F1tenth autonomous racing (our team placed first in four races; I managed the shared codebase), the Espresso compiler, and a Steam-review helpfulness paper, submitted to ITNG 2027 (under review), for which I built the scraper, the ETL and the first ML runs, then rebuilt the study as a one-command pipeline that reproduced its main table on a fresh machine. A semester of CS 789 AI-security assignments added a SOC copilot over a 37,808-alert knowledge graph, n8n and vLLM triage of live Wazuh alerts, phishing-detector distillation and a labels-only extraction attack, and DeepFool and Carlini-Wagner attacks written from scratch.

I also build **Silt**, a Rust version control system with Git-compatible interchange, and **Interlay**, experimental languages whose interpreters run commit and merge-policy hooks for Silt.

My **[Mario PPO agent](https://github.com/nirbhayagga/mario-ai)** cleared World 1-1 in 10/10 evaluation episodes after 10M training steps; results are limited to that trained level.

---

### Tech Stack

**Languages:**<br/>
![Python](https://img.shields.io/badge/Python-0A0A0C?style=flat-square&logo=python&logoColor=E3B341)
![Java](https://img.shields.io/badge/Java-0A0A0C?style=flat-square&logo=openjdk&logoColor=E3B341)
![C++](https://img.shields.io/badge/C%2B%2B-0A0A0C?style=flat-square&logo=c%2B%2B&logoColor=E3B341)
![Rust](https://img.shields.io/badge/Rust-0A0A0C?style=flat-square&logo=rust&logoColor=E3B341)
![JavaScript](https://img.shields.io/badge/JavaScript-0A0A0C?style=flat-square&logo=javascript&logoColor=E3B341)
![TypeScript](https://img.shields.io/badge/TypeScript-0A0A0C?style=flat-square&logo=typescript&logoColor=E3B341)
![SQL](https://img.shields.io/badge/SQL-0A0A0C?style=flat-square&logo=postgresql&logoColor=E3B341)

**Frameworks & Infrastructure:**<br/>
![React](https://img.shields.io/badge/React-0A0A0C?style=flat-square&logo=react&logoColor=E3B341)
![Astro](https://img.shields.io/badge/Astro-0A0A0C?style=flat-square&logo=astro&logoColor=E3B341)
![Vue.js](https://img.shields.io/badge/Vue.js-0A0A0C?style=flat-square&logo=vue.js&logoColor=E3B341)
![Node.js](https://img.shields.io/badge/Node.js-0A0A0C?style=flat-square&logo=node.js&logoColor=E3B341)
![PyTorch](https://img.shields.io/badge/PyTorch-0A0A0C?style=flat-square&logo=pytorch&logoColor=E3B341)
![Transformers](https://img.shields.io/badge/Transformers-0A0A0C?style=flat-square&logo=huggingface&logoColor=E3B341)
![Docker](https://img.shields.io/badge/Docker-0A0A0C?style=flat-square&logo=docker&logoColor=E3B341)
![ROS2](https://img.shields.io/badge/ROS2-0A0A0C?style=flat-square&logo=ros&logoColor=E3B341)
![Proxmox](https://img.shields.io/badge/Proxmox-0A0A0C?style=flat-square&logo=proxmox&logoColor=E3B341)
![Cloudflare](https://img.shields.io/badge/Cloudflare-0A0A0C?style=flat-square&logo=cloudflare&logoColor=E3B341)

---

<p align="center">
  <em>Open to full-time roles in Security Engineering, AppSec, and ML Security beginning in 2027.</em>
</p>
