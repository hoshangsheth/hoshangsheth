<div align="center">

# <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&pause=1000&color=7AA2F7&center=true&vCenter=true&width=820&lines=Hoshang+Sheth;Generative+AI+Engineer;Backend+%2B+MLOps+%2B+Automation;Building+production-grade+AI+systems" alt="Typing SVG" />

<img src="https://komarev.com/ghpvc/?username=hoshangsheth&label=Profile%20Views&color=7aa2f7&style=for-the-badge" alt="Profile Views" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Hoshang%20Sheth-7AA2F7?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/hoshangsheth/)
[![GitHub](https://img.shields.io/badge/GitHub-hoshangsheth-7AA2F7?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/hoshangsheth)
[![Portfolio](https://img.shields.io/badge/Portfolio-hoshangsheth.com-7AA2F7?style=for-the-badge\&logo=vercel\&logoColor=white)](https://hoshangsheth.com)
[![Email](https://img.shields.io/badge/Email-hoshangsheth@gmail.com-7AA2F7?style=for-the-badge\&logo=gmail\&logoColor=white)](mailto:hoshangsheth@gmail.com)

<br/>

<img src="https://img.shields.io/badge/AI%20Engineering-Production%20Systems-1ABC9C?style=flat-square" />
<img src="https://img.shields.io/badge/Backend%20Engineering-FastAPI%20%7C%20Python-9B59B6?style=flat-square" />
<img src="https://img.shields.io/badge/MLOps%20%26%20Automation-Scalable%20Workflows-F39C12?style=flat-square" />
<img src="https://img.shields.io/badge/Open%20Source-Recruiter%20Ready-7AA2F7?style=flat-square" />

</div>

---

## About Me

I'm a Generative AI Engineer with a BCA in AI & Data Science from Amrita Vishwa Vidyapeetham, backed by certifications in Data Science, Data Analytics, and Generative AI. I build backend APIs, retrieval-augmented generation systems, and ML pipelines — and I care more about whether a system survives real usage than whether a demo looks good in a screen recording.

My default engineering approach: get the simplest version working end-to-end first, then harden it. That usually means starting with a clean FastAPI service and a working data flow before adding clustering, embeddings, or explainability layers on top. When something breaks in production — a memory ceiling on a free-tier host, a schema mismatch in a pipeline — I treat it as a design problem to solve, not a bug to patch around.

**Focus areas:** backend API development, RAG systems, LLM integrations, recommendation systems, feature engineering, and deploying ML-backed products on constrained infrastructure (free-tier hosting, no dedicated ops team).

---

## Featured Projects

<table>
  <tr>
    <th align="left">Project</th>
    <th align="left">What it does</th>
    <th align="left">Engineering notes</th>
  </tr>
  <tr>
    <td><strong>SchemaHealer</strong></td>
    <td>Detects CSV schema drift and repairs column mismatches using rule-based logic, fuzzy matching, and GPT-assisted semantic mapping.</td>
    <td>Focused on auditability — every automated fix is logged so data teams can review what changed and why, not just trust a black-box repair.</td>
  </tr>
  <tr>
    <td><strong>FilmOracle</strong></td>
    <td>Hybrid recommendation engine for movies and games, combining semantic similarity with structured product logic.</td>
    <td>Refactored from a single 1,200+ line Streamlit app into a FastAPI + React monorepo. Precomputed similarity matrices caused OOM crashes on Render's free tier, so I redesigned the engine to compute cosine similarity on demand instead of persisting large matrices.</td>
  </tr>
  <tr>
    <td><strong>Recovia</strong></td>
    <td>Fintech SaaS product that scores loan recovery priority using engineered financial features, clustering-based risk segmentation, and supervised learning, with SHAP-based explainability for each prediction.</td>
    <td>Rebuilt from a 1,500+ line Streamlit prototype into a FastAPI backend + React/Vite/Tailwind frontend. Ships an animated SVG risk gauge, a live segmentation feature, and auto-generated PDF reports via ReportLab.</td>
  </tr>
  <tr>
    <td><strong>Customer Segmentation</strong></td>
    <td>KMeans-driven clustering for marketing and user understanding.</td>
    <td>Feature engineering and cluster validation focused on producing segments that are actually usable for targeting and campaign design, not just statistically distinct.</td>
  </tr>
</table>

**Common design principles across projects:** API-first architecture, stateless services, input validation on all external data, and clean boundaries between the ML/data layer and the API layer — so a model or pipeline can change without breaking the interface around it.

---

## Engineering Stack

<table>
<tr>
<td valign="top" width="33%">

### Languages

<img src="https://skillicons.dev/icons?i=python,mysql,js,ts,html,css" />

</td>
<td valign="top" width="33%">

### Frontend

<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind" />

</td>
<td valign="top" width="33%">

### Backend

<img src="https://skillicons.dev/icons?i=fastapi,flask,docker" />

</td>
</tr>

<tr>
<td valign="top">

### AI / Machine Learning

<img src="https://skillicons.dev/icons?i=tensorflow,pytorch,sklearn" />

Pandas • NumPy • LangChain • LlamaIndex • Hugging Face • ChromaDB • OpenAI APIs • XGBoost

</td>

<td valign="top">

### Databases

<img src="https://skillicons.dev/icons?i=postgres,mysql,sqlite" />

</td>

<td valign="top">

### Deployment & Tools

<img src="https://skillicons.dev/icons?i=git,githubactions,vercel" />

Docker • Render • Hugging Face Spaces • Linux • Postman

</td>
</tr>
</table>

---

## Professional Highlights

* Rebuilt two production ML applications (SLRS, FilmOracle) from Streamlit prototypes into FastAPI + React products, including solving a real memory-constraint failure on free-tier hosting
* Applied feature engineering, clustering, and supervised learning to real segmentation and scoring problems, with explainability (SHAP) as a first-class requirement rather than an afterthought
* Designed and shipped RAG and LLM-integration components as part of larger application architectures, not standalone notebooks
* Worked backend-first: API contracts, validation, and error handling designed before UI polish
* Deploy exclusively to free-tier infrastructure (Render, Vercel), which forces deliberate tradeoffs around memory, cold starts, and artifact size

---

## GitHub Metrics

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=hoshangsheth&theme=tokyonight&hide_border=true" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=hoshangsheth&theme=tokyo-night&hide_border=true" />

<br/><br/>

<img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" alt="Contribution Snake" />

</div>

---

## Let's Connect

<p align="center">
<a href="mailto:hoshangsheth@gmail.com"><img src="https://img.shields.io/badge/Email-hoshangsheth%40gmail.com-7AA2F7?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/hoshangsheth/"><img src="https://img.shields.io/badge/LinkedIn-hoshangsheth-7AA2F7?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://github.com/hoshangsheth"><img src="https://img.shields.io/badge/GitHub-hoshangsheth-7AA2F7?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="https://hoshangsheth.com"><img src="https://img.shields.io/badge/Portfolio-hoshangsheth.com-7AA2F7?style=for-the-badge&logo=vercel&logoColor=white" /></a>
</p>

---

<div align="center">

> "Build systems that survive real traffic, real failures, and real business pressure — everything else is just a demo."

</div>
