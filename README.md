# Hi, I'm Alif 👋

**Full-Stack Software Engineer building AI-powered systems & high-performance web applications**

📍 Medan, Indonesia · Web Developer at [Katsudoto.id](https://katsudoto.id)

[![Portfolio](https://img.shields.io/badge/Portfolio-alifakbar.pw-blue?style=flat-square&logo=google-chrome&logoColor=white)](https://alifakbar.pw)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-alifakbxr-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alifakbxr)
[![Email](https://img.shields.io/badge/Email-hello%40alifakbar.pw-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:hello@alifakbar.pw)

---

## 👨‍💻 About Me

I have over 4 years of experience engineering scalable web applications and resilient REST APIs for SaaS and B2B platforms. Currently expanding deep into the LLM engineering space — focusing on **Retrieval-Augmented Generation (RAG)**, **autonomous agents**, **tool calling / MCP**, and rigorous LLM evaluations built on rock-solid backend infrastructure.

---

## 🛠️ Tech Stack

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Backend & Systems** | PHP (Laravel), Go (Gin), REST API Architecture, Microservices |
| **Frontend** | TypeScript, Next.js, Vue 3, Inertia.js, Tailwind CSS |
| **Databases & Cache** | PostgreSQL, MySQL, Redis, Supabase, pgvector |
| **AI & Automation** | Claude API, Gemini API, RAG Pipelines, Model Context Protocol (MCP), Python (FastAPI) |
| **DevOps & Cloud** | Linux/POSIX internals, Docker, Git CI/CD |

---

## 🏆 Open Source Contributions & Impact

Proud contributor to foundational open-source ecosystems and enterprise cloud SDKs:

### ☁️ Google Cloud Platform — Official Contributor

[![Google Cloud Contributor](https://img.shields.io/badge/Google%20Cloud-Official%20Contributor-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)](https://github.com/googleapis/google-cloud-php/pull/9436)
[![Packagist Downloads](https://img.shields.io/badge/Packagist%20Downloads-150M%2B-blue?style=for-the-badge&logo=packagist&logoColor=white)](https://packagist.org/packages/google/cloud-core)
[![PR Merged](https://img.shields.io/badge/PR-%239436%20Merged-34A853?style=for-the-badge&logo=github&logoColor=white)](https://github.com/googleapis/google-cloud-php/pull/9436)

* **Repository:** [`googleapis/google-cloud-php`](https://github.com/googleapis/google-cloud-php)
* **Impact Package:** [`google/cloud-core`](https://packagist.org/packages/google/cloud-core) *(151M+ total downloads, ~6M monthly)*
* **Key Contribution ([PR #9436](https://github.com/googleapis/google-cloud-php/pull/9436)):** 
  * Diagnosed and patched a low-level **poison-message CPU-spin deadlock** in the background `Core/Batch` daemon runner.
  * Resolved an issue where payloads exceeding the 8192-byte limit on systems with elevated `kernel.msgmax` caused `msg_receive()` to fail with `E2BIG` in an infinite non-blocking loop, spinning CPU cores to 100%.
  * Dynamically allocated the IPC receive buffer based on actual OS queue capacities via `msg_stat_queue()`.
  * Reviewed and merged by Google Cloud engineers under official Google CLA.

### 🌐 Community & Open Source Projects

| Project | Organization / Maintainer | Role / Contribution | Status |
| :--- | :--- | :--- | :---: |
| **[Photobooth](https://github.com/PhotoboothProject/photobooth)** | PhotoboothProject | Screensaver custom media folder path configuration ([PR #1615](https://github.com/PhotoboothProject/photobooth/pull/1615)) | ⏳ In Review |
| **[Streak Stats](https://github.com/DenverCoder1/github-readme-streak-stats)** | DenverCoder1 (6.5k+ ⭐) | Indonesian & Portuguese internationalization ([PR #797](https://github.com/DenverCoder1/github-readme-streak-stats/pull/797), [#798](https://github.com/DenverCoder1/github-readme-streak-stats/pull/798)) | ✅ Merged |

---

## 🚀 Projects In Development

* **RentPilot AI**  
  *A RAG-based copilot for rental property operators that answers tenant queries directly from house rules and contracts, equipped with tool calling and human handoff.*  
  `Stack:` TypeScript · PostgreSQL + pgvector · Redis · LangChain/LlamaIndex

* **Document Extraction Pipeline**  
  *Automated intelligent extraction pipeline parsing unstructured invoices and contracts into strictly validated JSON schemas with an active human-in-the-loop review queue.*  
  `Stack:` Laravel · Inertia.js · PostgreSQL · OpenAI/Claude Structured Outputs

* **DevPatch**  
  *Autonomous code assistant agent that inspects repository pull requests, runs lint/test suites in an isolated sandbox, and proposes verified diff fixes.*  
  `Stack:` TypeScript · Python · GitHub Apps & Webhooks · Docker Sandbox

---

<p align="center">
  <i>Let's connect and build something impactful together!</i>
</p>
