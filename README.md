<div align="center">

# Enrique Bodí — AI Agent Engineer & LLM Engineer

**I build AI agents, private RAG systems and AI-powered workflow automation that run in production,<br/>backed by 10+ years of shipping Kotlin, Android and backend software.**

Founder of [FundRadar](https://fundradar.ai) · Independent AI & Software Engineering Consultant · Valencia, Spain · Remote across Europe

[ǃ[Website](https://img.shields.io/badge/kikebodi.com-0D1117?style=for-the-badge&logo=googlechrome&logoColor=white)](https://kikebodi.com)
[ǃ[LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge)](https://www.linkedin.com/in/kikebodi/)
[ǃ[FundRadar](https://img.shields.io/badge/FundRadar.ai-111827?style=for-the-badge)](https://fundradar.ai)
[ǃ[Email](https://img.shields.io/badge/me%40kikebodi.com-0D1117?style=for-the-badge)](mailto:me@kikebodi.com)

</div>

---

## About me

I'm a software engineer who moved into **AI engineering** after a decade of building production software: the **IKEA** Android app, **regulated medical-device apps** in health tech, and **payment systems**.

Today I design and build **AI agents, LLM applications and Retrieval-Augmented Generation (RAG) pipelines** that solve real business problems, with an emphasis on **privacy-centric AI** (on-premise / local LLMs where data must not leave the building).

What I bring from classic software engineering into Agentic AI:

- **Evaluation before demos.** I measure retrieval and answers (MRR, nDCG, LLM-as-judge) instead of trusting a good-looking prompt.
- **Architecture and maintainability.** Clear boundaries, testable components and CI/CD, the same standards I applied to large Kotlin codebases.
- **Idea → working product.** I built [FundRadar](https://fundradar.ai), an AI funding-intelligence platform, end to end as a solo founder.

---

## Technical expertise

<p>
  ‹img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  ‹img alt="Kotlin" src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" />
  ‹img alt="LangChain" src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
  ‹img alt="Ollama" src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" />
  ‹img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  ‹img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL%20%2B%20pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  ‹img alt="Android" src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white" />
  ‹img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
</p>

| Area | What I work with |
|---|---|
| **AI & LLM Engineering** | AI agents and agentic workflows · RAG (chunking, embeddings, retrievers) · private RAG with local LLMs (Ollama) · multi-model routing (LiteLLM) · semantic search + LLM re-ranking · retrieval evaluation (MRR, nDCG, LLM-as-judge) · token and cost optimisation · OpenAI / Anthropic / OpenRouter APIs · GitHub Copilot customisation |
| **Languages** | Python · Kotlin · Java · JavaScript |
| **Frameworks & Libraries** | LangChain · Chroma · FastAPI · Gradio · Android Jetpack (ViewModel, LiveData, Navigation, Data Binding) · Jetpack Compose · Kotlin Multiplatform |
| **Infrastructure & DevOps** | CI/CD · GitHub Actions · Gradle · selective testing · SonarQube |
| **Data & Databases** | PostgreSQL + pgvector · Chroma vector store · Room |
| **Software Engineering** | Software architecture (MVVM, MVP, modular apps) · test automation · code review · regulated software (medical devices, payments) |

---

## Featured projects

### FundRadar: AI funding-intelligence platform · [fundradar.ai](https://fundradar.ai)
Monitors Spanish and EU official sources (BDNS, BOE, DOGV, EU Funding & Tenders, CORDIS, IVACE and regional gazettes), structures every new call, and matches it against each company's profile. A weekly digest delivers the grants, tenders and regulatory changes that fit.

- **Stack:** Python · PostgreSQL + pgvector · LLM classification and re-ranking · RAG-generated reports · automated email workflows
- **Why it's interesting:** a complete applied-AI product, from crawling and document structuring to a **three-layer matching engine** (deterministic SQL filtering → semantic vector search → LLM re-ranking) and delivery to paying users. *Closed source.*

```mermaid
flowchart LR
    A[Official bulletins<br/>BDNS · BOE · DOGV · EU] --> B[Crawl & parse]
    B --> C[LLM classification<br/>& structuring]
    C --> D[(PostgreSQL + pgvector)]
    P[Company profile<br/>CNAE · region · size · TRL] --> E
    D --> E[SQL filter → semantic search → LLM re-rank]
    E --> F[Scored weekly digest]
```

### [LLM Engineering Examples](https://github.com/kikebodi/llm-engineering-examples): RAG, agents and evaluation patterns
A reference repository of applied LLM engineering: private RAG with LangChain + Chroma, retriever evaluation (MRR, nDCG, keyword coverage, LLM-as-judge), embedding-space visualisation (t-SNE), LiteLLM model routing and agentic workflow patterns.

- **Stack:** Python · LangChain · Chroma · LiteLLM · FastAPI · Gradio
- **Why it's interesting:** it treats RAG as an engineering system with measurable quality, not a prompt.

### Private RAG: from tutorial series to client deployment
A five-part series on building a **100% private, on-premise RAG system** with Ollama, LangChain and Chroma, from vector-database population and retrieval to implementation and evaluation. I applied the same approach for [Desert Leaves](https://kikebodi.com/desert-leaves.html) to streamline its technical office's knowledge workflows.

- **Stack:** Python · Ollama · LangChain · Chroma · embeddings
- **Why it's interesting:** privacy-centric AI for organisations whose documents can't go to a third-party cloud.

<details>
<summary><b>Earlier Kotlin & Android open source</b></summary>

- [custom_view_databinding](https://github.com/kikebodi/custom_view_databinding): a Kotlin custom view with two-way data binding, LiveData and ViewModel ([write-up](https://kikebodi.com/two-way-databinding-android.html)).
- [navigation-example](https://github.com/kikebodi/navigation-example): Android Architecture Components Navigation.
- Arctic Code Vault Contributor (GitHub Archive Program, 2020).

</details>

---

## Experience highlights

| Role | What I did |
|---|---|
| **Founder** · FundRadar (Valencia, 2026–) | Designed and built the platform end to end: data ingestion from official sources, LLM-based classification, pgvector semantic matching, RAG reports and automated delivery. |
| **Founder & Consultant** · EBP Consulting (Copenhagen, 2021–) | Independent software engineering and AI consulting for international clients. |
| **Android Engineer** · IKEA app (~3.5 years) | Built and evolved the Search, Browse and product Details experiences in Kotlin; improved architecture; mentored on Kotlin Multiplatform. **Fine-tuned GitHub Copilot for the team's chat and code reviews, improving PR quality and reducing review time** (per my engineering manager). |
| **Senior Android Developer** · Dawn Health (formerly Trifork eHealth) | Built regulated digital-health and medical-device apps, including Novo Nordisk patient and HCP apps, plus Growth Journey (ML-based growth tracking with AR measurement). |
| **Android Engineer** · Loomis Pay (Pay-Mobile) | Built an Android POS routing system with secure peripheral connections in a compliance-regulated payments environment. |

Earlier: Cortrium C3 ECG companion app, My4 and Appnaerobic.

---

## Currently building & exploring

- **[FundRadar](https://fundradar.ai)**: expanding coverage and improving matching quality for Spanish SMEs, associations and public bodies.
- **AI agent consulting**: custom AI agents, private RAG and AI workflow automation for SMEs and institutions, plus AI for developer productivity (Copilot customisation, selective testing to cut CI cost).
- **Exploring**: Kotlin-native agents (Koog), MCP-based tool integration, multi-agent systems and agentic software engineering.

---

## Writing

Technical articles on [kikebodi.com](https://kikebodi.com):

- [RAG Series, Part 1–2: Populate your private vector database](https://kikebodi.com/private-rag-vector-database.html)
- [RAG Series, Part 3: Create the vector retriever](https://kikebodi.com/private-rag-retriever.html)
- [RAG Series, Part 4: RAG implementation with Ollama, LangChain and Chroma](https://kikebodi.com/private-rag-implementation.html)
- [RAG Series, Part 5: Evaluating retrieval and answer quality](https://kikebodi.com/private-rag-evaluation.html)
- [LLM Engineering: Token optimisation for cheaper, faster LLM apps](https://kikebodi.com/llm-engineering-token-optimization.html)
- [LLM Engineering: Running local LLMs and APIs](https://kikebodi.com/llm-engineering-basic-usage.html)

---

## Let's connect

I work with **AI-focused companies, CTOs and technical founders** across Europe and remote-first teams, and with **SMEs and institutions** that need custom AI agents, private RAG or workflow automation built properly.

- **Email:** [me@kikebodi.com](mailto:me@kikebodi.com) · FundRadar: [hello@fundradar.ai](mailto:hello@fundradar.ai)
- **LinkedIn:** [linkedin.com/in/kikebodi](https://www.linkedin.com/in/kikebodi/)
- **Website:** [kikebodi.com](https://kikebodi.com)

<sub>Last updated: November 2026</sub>
