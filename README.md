<div align="center">

# Syed Sohail Hussain

**Full-Stack AI Software Engineer** — building AI-native web platforms, running LLMs down to the metal, and treating prediction markets as a systems problem.

`TypeScript` · `Rust` · `Python` · `AWS Bedrock` · `RAG` · `Quant Systems`

</div>

---

### What I'm building right now

- **[sagelib](https://github.com/syedsohailhussain1/sagelib)** — a native Rust TF-IDF search & document ingestion engine with Node.js (`napi-rs`) and Python (`PyO3`) bindings, built for composable AI retrieval pipelines.


---

### Core focus

- **Applied AI / RAG** — Amazon Bedrock, the Strands Agents SDK, and the Converse API for production agent workflows; building out a standalone RAG SDK; daily driver of Claude Code and Cursor for AI-assisted development.
- **Local inference & model tooling** — running and benchmarking open models via Ollama, llama.cpp, and LM Studio; sourcing and evaluating models from Hugging Face; hands-on GPU compute optimization on consumer hardware, including a double-buffered VRAM streaming setup for MoE expert weights on a 4GB card.
- **Systems programming** — Rust engines with cross-language native bindings, plus long-standing contributions to web tooling (Vite, Tailwind CSS).
- **Full-stack & cloud infrastructure** — production REST APIs, JWT/OAuth/RBAC auth, and AWS architecture spanning EC2, Lambda, S3, IAM, Route 53, and CloudWatch, deployed through Docker and GitHub Actions CI/CD.

---

### Technical toolkit

<div align="center">

| Category | Technologies |
| :--- | :--- |
| **AI & Agents** | ![Bedrock](https://img.shields.io/badge/AWS_Bedrock-FF9900?style=flat-square&logo=amazonaws&logoColor=white) ![Strands Agents](https://img.shields.io/badge/Strands_Agents_SDK-black?style=flat-square) ![Converse API](https://img.shields.io/badge/Converse_API-black?style=flat-square) ![RAG](https://img.shields.io/badge/RAG-black?style=flat-square) ![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square) ![Cursor](https://img.shields.io/badge/Cursor-000000?style=flat-square) |
| **Local LLM / Model Tooling** | ![Ollama](https://img.shields.io/badge/Ollama-black?style=flat-square) ![llama.cpp](https://img.shields.io/badge/llama.cpp-black?style=flat-square) ![LM Studio](https://img.shields.io/badge/LM_Studio-black?style=flat-square) ![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black) |
| **APIs & Security** | ![REST APIs](https://img.shields.io/badge/REST_APIs-black?style=flat-square) ![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white) ![gRPC](https://img.shields.io/badge/gRPC-black?style=flat-square) ![JWT Auth](https://img.shields.io/badge/JWT_Auth-black?style=flat-square) ![OAuth](https://img.shields.io/badge/OAuth-black?style=flat-square) ![RBAC](https://img.shields.io/badge/RBAC-black?style=flat-square) |
| **Cloud & DevOps** | ![AWS EC2](https://img.shields.io/badge/AWS_EC2-232F3E?style=flat-square&logo=amazonec2&logoColor=white) ![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=flat-square&logo=amazons3&logoColor=white) ![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white) ![IAM](https://img.shields.io/badge/AWS_IAM-232F3E?style=flat-square) ![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=flat-square) ![Route 53](https://img.shields.io/badge/Route_53-232F3E?style=flat-square) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white) |
| **Languages & Frameworks** | ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![C#/.NET](https://img.shields.io/badge/C%23_.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB) |
| **Data & Trading** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![Pine Script](https://img.shields.io/badge/Pine_Script-131722?style=flat-square&logo=tradingview&logoColor=white) ![LightGBM](https://img.shields.io/badge/LightGBM-black?style=flat-square) |
| **Fintech & Utilities** | ![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white) ![Stripe Connect](https://img.shields.io/badge/Stripe_Connect-635BFF?style=flat-square) ![Puppeteer](https://img.shields.io/badge/Puppeteer-40B5A4?style=flat-square&logo=puppeteer&logoColor=white) |

</div>

---

### Featured project: sagelib

A high-performance, native Rust TF-IDF search and document ingestion engine designed for composable AI pipelines.

- **Multi-language support** — unified native bindings for Node.js (`napi-rs`) and Python (`PyO3`).
- **Engine capabilities** — real-time semantic chunking, dual-retriever options, and retrieval-time authorization for secure, tenant-scoped ingestion.
- **Distribution** — published to NPM (`sagelib`) and Test PyPI (`sagelib`), with automated multi-platform build pipelines.

---

### Open source contributions

- **[Vite](https://github.com/vitejs/vite)** (`chore-deprecate-plugin-hooks`) — Deprecated legacy config hooks and introduced explicit JSDoc `@deprecated` compiler tags to streamline ecosystem API migration. Analyzed tryListen port-binding and wildcard interface validation in dev server modules.
- **[Tailwind CSS](https://github.com/tailwindlabs/tailwindcss)** (`fix-duplicate-with-typo`) — Fixed syntax bugs and duplicate class rule declarations in the core CSS parser test suites to prevent compiler verification errors.
- **[React Router](https://github.com/remix-run/react-router)** (`refactor-deferred-types`) — Refactored internal router utility methods to implement definite assignment type assertions in `createDeferred`, improving strict TypeScript compilation.
- **[Docusaurus](https://github.com/facebook/docusaurus)** (`refactor-relative-breadcrumb`) — Refactored relative path computations inside `content-docs` to utilize `path.posix.relative` for correct and standardized breadcrumb resolution on Unix systems.
- **[Supabase](https://github.com/supabase/supabase)** (`refactor-option-type`) — Refactored shared UI select primitives to make the `Option` interface generic, enabling first-class support for custom enum values in schema configurations.

---

### GitHub stats

<div align="center">

| Contributions Summary | Commit Streak Stats |
| :--- | :--- |
| <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=syedsohailhussain1&theme=solarized_dark" width="400" alt="Sohail's GitHub Stats" /> | <img src="https://github-readme-streak-stats.herokuapp.com/?user=syedsohailhussain1&theme=dark&hide_border=true" width="380" alt="Sohail's Streak Stats" /> |

</div>
