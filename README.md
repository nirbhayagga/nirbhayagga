<h1 align="center">Nirbhay Aggarwal</h1>
<p align="center"><strong>Software Engineer</strong> · Security &amp; ML Security · Homelab Builder</p>

<p align="center">
  <a href="https://nirbhay.dev">
    <img src="badges/web.svg" alt="Website: nirbhay.dev" />
  </a>
  <a href="https://linkedin.com/in/nirbhayagga/">
    <picture><source media="(prefers-color-scheme: dark)" srcset="badges/dark/linkedin.svg"><img src="badges/light/linkedin.svg" alt="LinkedIn: nirbhayagga" /></picture>
  </a>
  <a href="mailto:hi@nirbhay.dev">
    <picture><source media="(prefers-color-scheme: dark)" srcset="badges/dark/mail.svg"><img src="badges/light/mail.svg" alt="Email: hi@nirbhay.dev" /></picture>
  </a>
</p>

<p align="center">
  <strong>Live projects:</strong><br/>
  <a href="https://wikigolf.app">
    <picture><source media="(prefers-color-scheme: dark)" srcset="badges/dark/live-wikigolf.svg"><img src="badges/light/live-wikigolf.svg" alt="Play WikiGolf" /></picture>
  </a>
  <a href="https://sudoku.nirbhay.dev">
    <picture><source media="(prefers-color-scheme: dark)" srcset="badges/dark/live-sudoku.svg"><img src="badges/light/live-sudoku.svg" alt="Play Sudoku" /></picture>
  </a>
  <a href="https://boardroom.nirbhay.dev">
    <picture><source media="(prefers-color-scheme: dark)" srcset="badges/dark/live-boardroom.svg"><img src="badges/light/live-boardroom.svg" alt="Play Boardroom" /></picture>
  </a>
  <a href="https://clientcrypt.nirbhay.dev">
    <picture><source media="(prefers-color-scheme: dark)" srcset="badges/dark/live-clientcrypt.svg"><img src="badges/light/live-clientcrypt.svg" alt="Try ClientCrypt" /></picture>
  </a>
  <a href="https://stepwise.nirbhay.dev">
    <picture><source media="(prefers-color-scheme: dark)" srcset="badges/dark/live-stepwise.svg"><img src="badges/light/live-stepwise.svg" alt="Try Stepwise" /></picture>
  </a>
  <a href="https://ragshield.dev">
    <picture><source media="(prefers-color-scheme: dark)" srcset="badges/dark/live-rag-shield.svg"><img src="badges/light/live-rag-shield.svg" alt="Visit RAG Shield" /></picture>
  </a>
  <a href="https://rallyradio.onrender.com">
    <picture><source media="(prefers-color-scheme: dark)" srcset="badges/dark/live-rally-radio.svg"><img src="badges/light/live-rally-radio.svg" alt="Play Rally Radio" /></picture>
  </a>
</p>

---

### About Me

I'm a software engineer pursuing an **MS in Computer Science at UNLV** (expected May 2027), after finishing my BS in 2025. Lately that work is AI security: change control for the documents RAG pipelines read, and LLM-rewritten phishing. I build software to explore what I'm learning and to solve problems for people I know.

I work as a **Public Service Intern at UNLV OIT**, where I lead the annual audit verification of 8,000+ IT assets, and run a Proxmox and TrueNAS homelab. Open to full-time security, AppSec, and ML security roles starting in **2027**, as well as software and infrastructure work.

---

### Highlighted Projects

- **[RAG Shield](https://ragshield.dev):** Change control for the documents a RAG pipeline reads. Scores only what each edit adds, holds risky edits for review while the previous version keeps serving, and signs every chunk (SHA-256 plus an Ed25519 ledger) so tampered or unknown chunks are dropped before the model sees them. Caught 125 of 125 direct vector-store edits; a classifier fine-tuned on public data raised detection of prompt-injection edits from 23% to 96.0% on held-out documents with a calibrated threshold, flagging 0 of 62 benign edits. Coursework startup project, released as open source: [source](https://github.com/nirbhayagga/rag-shield), [`pip install rag-shield`](https://pypi.org/project/rag-shield/), and the classifier on [Hugging Face](https://huggingface.co/nirbhayagga/ragshield-injection-v5).
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
<picture><source media="(prefers-color-scheme: dark)" srcset="badges/dark/stack-python.svg"><img src="badges/light/stack-python.svg" alt="Python" /></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="badges/dark/stack-java.svg"><img src="badges/light/stack-java.svg" alt="Java" /></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="badges/dark/stack-cpp.svg"><img src="badges/light/stack-cpp.svg" alt="C++" /></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="badges/dark/stack-rust.svg"><img src="badges/light/stack-rust.svg" alt="Rust" /></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="badges/dark/stack-javascript.svg"><img src="badges/light/stack-javascript.svg" alt="JavaScript" /></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="badges/dark/stack-typescript.svg"><img src="badges/light/stack-typescript.svg" alt="TypeScript" /></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="badges/dark/stack-sql.svg"><img src="badges/light/stack-sql.svg" alt="SQL" /></picture>

**Frameworks & Infrastructure:**<br/>
<picture><source media="(prefers-color-scheme: dark)" srcset="badges/dark/stack-react.svg"><img src="badges/light/stack-react.svg" alt="React" /></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="badges/dark/stack-astro.svg"><img src="badges/light/stack-astro.svg" alt="Astro" /></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="badges/dark/stack-vuejs.svg"><img src="badges/light/stack-vuejs.svg" alt="Vue.js" /></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="badges/dark/stack-nodejs.svg"><img src="badges/light/stack-nodejs.svg" alt="Node.js" /></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="badges/dark/stack-pytorch.svg"><img src="badges/light/stack-pytorch.svg" alt="PyTorch" /></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="badges/dark/stack-transformers.svg"><img src="badges/light/stack-transformers.svg" alt="Transformers" /></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="badges/dark/stack-docker.svg"><img src="badges/light/stack-docker.svg" alt="Docker" /></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="badges/dark/stack-ros2.svg"><img src="badges/light/stack-ros2.svg" alt="ROS2" /></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="badges/dark/stack-proxmox.svg"><img src="badges/light/stack-proxmox.svg" alt="Proxmox" /></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="badges/dark/stack-cloudflare.svg"><img src="badges/light/stack-cloudflare.svg" alt="Cloudflare" /></picture>

---

<p align="center">
  <em>Open to full-time roles in Security Engineering, AppSec, and ML Security beginning in 2027.</em>
</p>
