<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b27,50:3d59a1,100:7aa2f7&height=200&section=header&text=Hoshang%20Sheth&fontSize=52&fontColor=ffffff&fontAlignY=36&desc=Gen%20AI%20Engineer%20%C2%B7%20LLM%20Agents%20%C2%B7%20Python&descSize=18&descAlignY=58&animation=fadeIn" width="100%" alt="Hoshang Sheth" />

<a href="https://github.com/hoshangsheth">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3200&pause=900&color=7AA2F7&center=true&vCenter=true&width=640&lines=I+build+LLM+agents+that+ship+to+production;Text+to+SQL+%C2%B7+LangGraph+%C2%B7+FastAPI+%C2%B7+PostgreSQL;Measured%2C+tested+and+deployed%2C+not+just+demos" alt="Typing intro" />
</a>

<br/><br/>

<a href="https://www.linkedin.com/in/shethhoshang/"><img src="https://img.shields.io/badge/LinkedIn-shethhoshang-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:hoshangsheth@gmail.com"><img src="https://img.shields.io/badge/Email-hoshangsheth%40gmail.com-7AA2F7?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://ask-your-data-chi.vercel.app"><img src="https://img.shields.io/badge/Live%20Demo-Ask%20Your%20Data-1ABC9C?style=for-the-badge&logo=vercel&logoColor=white" alt="Live demo" /></a>
<img src="https://komarev.com/ghpvc/?username=hoshangsheth&label=Profile%20views&color=3d59a1&style=for-the-badge" alt="Profile views" />

</div>

---

## About me

- **Gen AI engineer** building LLM agents, text to SQL systems and FastAPI backends, based in **Mumbai, India**
- Built and deployed **Ask Your Data**, a LangGraph agent that answers business questions from any dataset, with **97.9% accuracy** on a 48 question benchmark
- Background in **data science and analytics** through two internships at AI Variant (customer segmentation, ETL pipelines, BI dashboards)
- **3+ years of corporate operations** experience, so I build for real users and real business workflows
- Pursuing a **BCA in Artificial Intelligence and Data Science** at Amrita Vishwa Vidyapeetham
- How I work: ship the smallest end to end version first, then measure it, test it and harden it

---

## Featured project

<table>
<tr>
<td width="100%">

### [Ask Your Data](https://github.com/hoshangsheth/ask-your-data) &nbsp;·&nbsp; [Live demo](https://ask-your-data-chi.vercel.app)

**Ask business questions in plain English and get answers with tables and charts.** A LangGraph agent writes, validates and runs SQL on the demo store or on your own uploaded CSV, Excel, JSON or Parquet files.

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL%20(Neon)-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
</p>

<table>
<tr>
<td align="center" width="33%"><b>97.9%</b><br/><sub>accuracy on 48 questions<br/>(100% on follow ups)</sub></td>
<td align="center" width="33%"><b>4.4 s</b><br/><sub>median answer time</sub></td>
<td align="center" width="33%"><b>$0.002</b><br/><sub>cost per answer</sub></td>
</tr>
<tr>
<td align="center"><b>18 of 18</b><br/><sub>unsafe queries blocked</sub></td>
<td align="center"><b>199 tests</b><br/><sub>about 87% coverage, CI on every push</sub></td>
<td align="center"><b>64,968 requests</b><br/><sub>load test, 0.0015% errors</sub></td>
</tr>
</table>

- **Intent routing:** each question is sent to SQL, answered from the schema, or politely declined
- **Conversation memory:** follow ups like *"and by city?"* are rewritten into standalone questions
- **Self correction loop:** SQL and database errors are fed back to the model for another attempt
- **Guardrails:** sqlglot AST validation, read only transactions and per user schema isolation
- **Evaluation harness:** execution accuracy by category, plus latency, tokens and cost per question
- **Product features:** accounts with private uploads, CSV, Excel and PDF exports, answer feedback logged to Excel or Google Sheets, and an animated light and dark theme

```mermaid
flowchart LR
    Q([Question]) --> R{Intent router}
    R -->|data question| G[Generate SQL]
    R -->|about the data| S[Answer from schema]
    R -->|out of scope| D[Decline]
    G --> V[Validate with sqlglot]
    V --> X[(Run read only)]
    X -->|error| G
    X --> A[Summarize and chart]
    A --> U([Answer])
    S --> U
```

</td>
</tr>
</table>

---

## Tech stack

<table>
<tr>
<td valign="top" width="50%">

**Generative AI**
<br/>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" />
<img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white" />
<img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
<br/>
<sub>RAG · prompt engineering · structured outputs · embeddings · vector databases · LLM evaluation</sub>

</td>
<td valign="top" width="50%">

**Machine learning and data**
<br/>
<img src="https://skillicons.dev/icons?i=python,sklearn,postgres,sqlite,mysql&perline=5" />
<br/>
<sub>Pandas · NumPy · XGBoost · clustering · feature engineering · ETL · Power BI · Tableau</sub>

</td>
</tr>
<tr>
<td valign="top">

**Backend and APIs**
<br/>
<img src="https://skillicons.dev/icons?i=fastapi,flask,docker,linux&perline=4" />
<br/>
<sub>Pydantic · SQLAlchemy · REST APIs · pytest</sub>

</td>
<td valign="top">

**Cloud, CI/CD and tools**
<br/>
<img src="https://skillicons.dev/icons?i=vercel,aws,githubactions,git,vscode&perline=5" />
<br/>
<sub>Neon Postgres · Vercel Blob · GitHub Actions CI · Ruff</sub>

</td>
</tr>
</table>

---

## Experience

- **Data Scientist Intern** · AI Variant · *Jan 2025 to Apr 2025*
  - Built a K-Means customer segmentation model whose segments contributed to a **20% lift** in targeted campaign conversion
  - Shared model outputs with stakeholders through a Streamlit app
- **Data Analyst Intern** · AI Variant · *Feb 2024 to May 2024*
  - Automated Python ETL pipelines feeding dashboards, cutting data processing time by **50%**
  - Built Power BI and Tableau KPI dashboards and supported A/B tests (**15%** engagement rise)
- **Earlier experience (2019 to 2023)** · Accurate Background, CommVersion, WNS Global Services
  - Operations, data verification and lead qualification roles: accurate records at volume and data driven workflow improvements

---

## Right now

- Hardening **Ask Your Data** with real user feedback
- Going deeper on **RAG, agent evaluation and LLM cost and latency optimisation**
- Open to **Gen AI, LLM engineering and Python developer** roles

---

## GitHub activity

<div align="center">

<img src="https://streak-stats.demolab.com?user=hoshangsheth&theme=tokyonight&hide_border=true&background=1a1b27" alt="GitHub streak" />

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hoshangsheth/hoshangsheth/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/hoshangsheth/hoshangsheth/output/github-snake.svg" />
  <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/hoshangsheth/hoshangsheth/output/github-snake-dark.svg" />
</picture>

</div>

---

<div align="center">

**Let's build something useful.** &nbsp;Reach me on [LinkedIn](https://www.linkedin.com/in/shethhoshang/) or by [email](mailto:hoshangsheth@gmail.com).

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7aa2f7,50:3d59a1,100:1a1b27&height=110&section=footer" width="100%" alt="" />

</div>
