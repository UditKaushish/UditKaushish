<p align="center">
  <img src="assets/header.svg" alt="Udit Kaushish, AI Engineer and Product Manager" width="100%" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/udit-kaushish-99a0a61bb"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge" alt="LinkedIn" /></a>
  <a href="https://github.com/UditKaushish?tab=repositories"><img src="https://img.shields.io/badge/GitHub-Repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub repositories" /></a>
  <img src="https://img.shields.io/badge/Bengaluru-India-0D9488?style=for-the-badge" alt="Bengaluru, India" />
</p>

## About me

I build production GenAI systems and ship the products around them. My work covers RAG assistants with cited sources, AI agents with tool calling, NL2SQL engines and MCP servers, with evals and guardrails built in from the start.

- **Now:** Product Manager at **LiveSwitch**, leading the web and mobile platform and still writing production code
- **Before:** Software Engineer at **Zenon** (agentic workflows, NL2SQL) and **KnowESG** (RAG assistant, semantic search, MCP servers)
- **Side venture:** co-founder and CTO of **Quickboard AI**, where I built the full analytics platform
- **Research:** co-author of a published NLP paper on sarcasm detection

## Measured results

<p align="center">
  <img src="assets/metric-rag.svg" alt="99% RAG answer accuracy on a 145-question eval set at KnowESG" width="49%" />
  <img src="assets/metric-latency.svg" alt="2.8x faster RAG responses, median latency 9.4 s to 3.4 s at KnowESG" width="49%" />
</p>
<p align="center">
  <img src="assets/metric-agents.svg" alt="40% less manual intervention from an agentic workflow system at Zenon" width="49%" />
  <img src="assets/metric-speed.svg" alt="50% faster page loads after a platform migration at KnowESG" width="49%" />
</p>

## Systems I've built

| System | What it does | How |
|---|---|---|
| **RAG assistant** <br/> KnowESG | Answers only from platform content and cites its sources. 99% correct behaviour and 0.95 faithfulness on a 145-question eval, with 100% of prompt-injection attempts refused. | Retrieval over embeddings, grounded generation, eval set, injection guardrails, latency tuning (9.4 s to 3.4 s median) |
| **Agentic workflow system** <br/> Zenon | Connects internal APIs and databases so agents can complete stakeholder workflows, cutting manual intervention time by 40%. | AI agents, tool calling, API and database connectors |
| **NL2SQL engine** <br/> Zenon | Lets non-technical stakeholders query relational data in plain English, with no engineer in the loop. | Schema-aware prompting, SQL generation and validation |
| **MCP servers** <br/> KnowESG | Custom Model Context Protocol servers and agentic workflows that automate ESG data research. | MCP, agent orchestration |
| **Semantic search** <br/> KnowESG | Replaced rigid keyword matching across the core platform with meaning-based retrieval. | Embeddings, vector search |
| **In-house model pipeline** <br/> LiveSwitch | Matched Google Gemini's accuracy on its target task and replaced the external model dependency. | Open-source models, fine-tuning, benchmarking |
| **Analytics platform** <br/> Quickboard AI | Unifies Shopify, Meta Ads, delivery-partner and payment-partner data into one metrics pipeline, with an LLM layer that recommends strategies from each brand's data. | API integrations, data pipeline, configurable dashboards, LLM recommendations |
| **Platform migration** <br/> KnowESG | Moved the platform from Contentful and Netlify to Sanity and Vercel and refactored the Next.js frontend, making page loads 50% faster. | Next.js, Sanity, Vercel |
| **Mobile apps** <br/> LiveSwitch | Launched the iOS and Android apps, owning both the build and the requirements. | iOS, Android, weekly release pipeline |

## Tech stack

**LLM engineering**

<p>
<img src="https://img.shields.io/badge/RAG-4F46E5?style=flat-square" alt="RAG" />
<img src="https://img.shields.io/badge/AI%20agents-7C3AED?style=flat-square" alt="AI agents" />
<img src="https://img.shields.io/badge/Tool%20calling-7C3AED?style=flat-square" alt="Tool calling" />
<img src="https://img.shields.io/badge/MCP-0D9488?style=flat-square" alt="MCP" />
<img src="https://img.shields.io/badge/NL2SQL-0891B2?style=flat-square" alt="NL2SQL" />
<img src="https://img.shields.io/badge/Embeddings-2563EB?style=flat-square" alt="Embeddings" />
<img src="https://img.shields.io/badge/Vector%20search-2563EB?style=flat-square" alt="Vector search" />
<img src="https://img.shields.io/badge/Pinecone-334155?style=flat-square" alt="Pinecone" />
<img src="https://img.shields.io/badge/ChromaDB-334155?style=flat-square" alt="ChromaDB" />
<img src="https://img.shields.io/badge/LoRA%20·%20PEFT-DB2777?style=flat-square" alt="LoRA and PEFT fine-tuning" />
<img src="https://img.shields.io/badge/LLM%20evals-EA580C?style=flat-square" alt="LLM evals" />
<img src="https://img.shields.io/badge/Guardrails-EA580C?style=flat-square" alt="Guardrails" />
<img src="https://img.shields.io/badge/Prompt--injection%20defense-EA580C?style=flat-square" alt="Prompt-injection defense" />
<img src="https://img.shields.io/badge/LLM%20observability-334155?style=flat-square" alt="LLM observability" />
<img src="https://img.shields.io/badge/AutoGen-334155?style=flat-square" alt="AutoGen" />
</p>

**AI and ML**

<p>
<img src="https://img.shields.io/badge/Anthropic-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Anthropic" />
<img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge" alt="OpenAI" />
<img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Google Gemini" />
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain" />
<img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" />
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" />
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn" />
</p>

**Backend and data**

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
<img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask" />
<img src="https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
</p>

**Frontend and platform**

<p>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
<img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" />
<img src="https://img.shields.io/badge/Claude%20Code-D97757?style=for-the-badge&logo=claude&logoColor=white" alt="Claude Code" />
</p>

## Featured projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/UditKaushish/inquira">inquira</a></h3>
      <p>Open-source AI analytics copilot. Ask a question in plain English and get validated, read-only SQL, a chart and an answer, streamed from your own warehouse. Works with Postgres, Snowflake, DuckDB and MySQL, on Gemini, Claude, OpenAI or local models.</p>
      <p>
<img src="https://img.shields.io/badge/NL2SQL-4F46E5?style=flat-square" alt="NL2SQL" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square" alt="Python" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square" alt="FastAPI" />
<img src="https://img.shields.io/badge/React-0891B2?style=flat-square" alt="React" />
<img src="https://img.shields.io/badge/Docker-334155?style=flat-square" alt="Docker" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/UditKaushish/slash-prompt">slash-prompt</a></h3>
      <p>A <code>/prompt</code> command for Claude Code and Codex CLI that turns a rough request into a clear, structured prompt without changing its meaning, then runs it.</p>
      <p>
<img src="https://img.shields.io/badge/Prompt%20engineering-7C3AED?style=flat-square" alt="Prompt engineering" />
<img src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square" alt="Claude Code" />
<img src="https://img.shields.io/badge/Codex%20CLI-334155?style=flat-square" alt="Codex CLI" />
<img src="https://img.shields.io/badge/Shell-4EAA25?style=flat-square" alt="Shell" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/UditKaushish/arogo">arogo</a></h3>
      <p>Question answering over medical textbooks. Query expansion, hybrid BM25 and sentence-transformer retrieval, cross-encoder re-ranking, a Flask API and a Next.js frontend.</p>
      <p>
<img src="https://img.shields.io/badge/RAG-4F46E5?style=flat-square" alt="RAG" />
<img src="https://img.shields.io/badge/BM25-0D9488?style=flat-square" alt="BM25" />
<img src="https://img.shields.io/badge/Sentence%20Transformers-DB2777?style=flat-square" alt="Sentence Transformers" />
<img src="https://img.shields.io/badge/Flask-334155?style=flat-square" alt="Flask" />
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square" alt="Next.js" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/UditKaushish/RecoBot">RecoBot</a></h3>
      <p>A recommendation chatbot for movies, songs and books, built on nearest-neighbour collaborative filtering.</p>
      <p>
<img src="https://img.shields.io/badge/Recommender%20systems-EA580C?style=flat-square" alt="Recommender systems" />
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square" alt="scikit-learn" />
<img src="https://img.shields.io/badge/Jupyter-334155?style=flat-square" alt="Jupyter" />
      </p>
    </td>
  </tr>
</table>

## Experience

| Role | Company | Period |
|---|---|---|
| Product Manager | **LiveSwitch**, Bengaluru | Mar 2026 to present |
| Co-founder and CTO | **Quickboard AI** (part-time venture) | Jan 2025 to Apr 2026 |
| Software Engineer I | **Zenon**, Noida | Jul 2025 to Mar 2026 |
| Software Engineer (Contract) | **KnowESG**, remote | Jun 2024 to Jun 2025 |

## Publication

**DWAEF: A Deep Weighted Average Ensemble Framework Harnessing Novel Indicators for Sarcasm Detection**
*Data Science* (IOS Press), 2023. The ensemble NLP model reached 92% accuracy against a 78.6% SVM baseline.

## Education

- **Master of Computer Applications (MCA)**, GGSIPU (USICT), Delhi
- **B.Sc. (Hons) Computer Science**, Keshav Mahavidyalaya, University of Delhi

## Get in touch

I'm happy to talk about GenAI systems, LLM evals and agents. The fastest way to reach me is [LinkedIn](https://www.linkedin.com/in/udit-kaushish-99a0a61bb).

<p align="center">
  <img src="assets/footer.svg" alt="" width="100%" />
</p>
