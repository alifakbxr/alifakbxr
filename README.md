# Hi, I'm Alif 👋

**Full-Stack Engineer building AI-powered applications**

Web Developer at [Katsudoto.id](https://katsudoto.id) · Medan, Indonesia

[Portfolio](https://alifakbar.pw) · [LinkedIn](https://www.linkedin.com/in/alifakbxr) · [Email](mailto:hello@alifakbar.pw)

---

## About

I have about four years of experience shipping web applications and REST APIs for SaaS and B2B products. I'm now focusing on LLM applications: retrieval-augmented generation (RAG), tool calling, agents, and evaluation, built on top of reliable backends.

## Tech Stack

| | |
|---|---|
| **Backend** | PHP (Laravel), Go (Gin), REST API design |
| **Frontend** | Vue 3, Inertia.js, Next.js, TypeScript |
| **Data** | PostgreSQL, MySQL, Redis, Supabase |
| **AI (building now)** | Claude API, RAG with pgvector, MCP, Python (FastAPI) |


## 🏆 Open Source Contributions & Impact

Proud contributor to foundational open source ecosystems and enterprise cloud SDKs:

### ☁️ Google Cloud Platform — Official Contributor
[![Google Cloud Contributor](https://img.shields.io/badge/Google%20Cloud-Official%20Contributor-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)](https://github.com/googleapis/google-cloud-php/pull/9436)
[![Packagist Downloads](https://img.shields.io/badge/Packagist%20Downloads-150M%2B-blue?style=for-the-badge&logo=packagist&logoColor=white)](https://packagist.org/packages/google/cloud-core)
[![PR Merged](https://img.shields.io/badge/PR-%239436%20Merged-34A853?style=for-the-badge&logo=github&logoColor=white)](https://github.com/googleapis/google-cloud-php/pull/9436)

* **Repository:** [`googleapis/google-cloud-php`](https://github.com/googleapis/google-cloud-php)
* **Impact Package:** [`google/cloud-core`](https://packagist.org/packages/google/cloud-core) *(151M+ total downloads, ~6M/month)*
* **Contribution ([PR #9436](https://github.com/googleapis/google-cloud-php/pull/9436)):** 
  * Diagnosed and fixed a critical **poison-message CPU-spin deadlock** in the background `Core/Batch` daemon runner.
  * Resolved an issue where messages exceeding the 8192-byte limit on systems with elevated `kernel.msgmax` caused `msg_receive()` to fail with `E2BIG` in an infinite non-blocking loop, maxing out CPU cores to 100%.
  * Dynamically allocated the IPC receive buffer based on actual OS queue capacities via `msg_stat_queue()`.
  * Verified and merged by Google Cloud engineers under official Google CLA.

---

### 🌐 Other Community & Open Source Contributions

| Project | Organization / Maintainer | Role / Contribution | Status |
| :--- | :--- | :--- | :---: |
| **[google-cloud-php](https://github.com/googleapis/google-cloud-php)** | Google Cloud | Core Batch runtime & IPC memory fix ([PR #9436](https://github.com/googleapis/google-cloud-php/pull/9436)) | ✅ Merged |
| **[photobooth](https://github.com/PhotoboothProject/photobooth)** | PhotoboothProject | Screensaver custom folder configuration ([PR #1615](https://github.com/PhotoboothProject/photobooth/pull/1615)) | ⏳ Open |
| **[github-readme-streak-stats](https://github.com/DenverCoder1/github-readme-streak-stats)** | DenverCoder1 (6.5k+ ⭐) | Indonesian & Portuguese localization ([PR #797](https://github.com/DenverCoder1/github-readme-streak-stats/pull/797), [#798](https://github.com/DenverCoder1/github-readme-streak-stats/pull/798)) | ✅ Merged |

## Upcoming Projects

- **RentPilot AI** — a RAG-based copilot for rental operators that answers tenant questions from house rules and contracts, with tool calling and human handoff. *TypeScript, PostgreSQL + pgvector, Redis.*
- **Document Extraction Pipeline** — LLM extraction of invoices and contracts into validated JSON, with a human review queue. *Laravel, Inertia, PostgreSQL.*
- **DevPatch** — an agent that reviews pull requests and proposes fixes in a sandbox. *TypeScript/Python, GitHub App.*
