<!-- Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:7F00FF,50:E100FF,100:FF6EC7&height=200&section=header&text=Hi%2C%20I'm%20Jeevana%20Nanepalli&fontColor=ffffff&fontSize=42&fontAlignY=38&desc=ML%20%E2%80%A2%20Speech%20Systems%20%E2%80%A2%20Honest%20Evaluation&descAlignY=58&descSize=18&animation=fadeIn" width="100%" alt="Header banner" />
</p>

<p align="center">
  <a href="https://github.com/jeevanananepalli-create">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=E100FF&center=true&vCenter=true&width=650&lines=B.Tech+CSE+(Data+Science)+%40+CMR+College;Machine+learning+%26+speech+systems+in+Python;Looking+for+a+Student+Researcher+placement" alt="Typing intro" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jeevana-nanepalli-b9847b419"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:jeevanananepalli@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/CGPA-9.25%20%2F%2010-8A2BE2?style=for-the-badge" alt="CGPA 9.25" />
  <img src="https://img.shields.io/badge/Hyderabad-India-FF6EC7?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Hyderabad, India" />
  <img src="https://komarev.com/ghpvc/?username=jeevanananepalli-create&style=for-the-badge&color=blueviolet&label=Profile+views" alt="Profile views" />
</p>

---

## 🌸 About me

- 🎓 Second-year **B.Tech in Computer Science (Data Science)** at CMR College of Engineering and Technology, Hyderabad (graduating 2029)
- 🧠 I work mainly in **Python** on **machine learning** and **speech systems**
- 📏 I care as much about **honest evaluation** as about the model: fixed holdouts, confidence intervals, leakage checks, and reporting weak results along with strong ones
- 📝 Co-author of a paper on **EchoSarathi**, a real-time voice AI calling platform
- 🔭 Looking for a **Student Researcher** placement to work on research problems at a larger scale

---

## 🚀 Featured projects

### 🫀 [CardioScope AI](https://github.com/jeevanananepalli-create/cardioscope-ai): cardiovascular risk prediction and visualization

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=flat-square)
![SHAP](https://img.shields.io/badge/SHAP-FF0D57?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Three.js](https://img.shields.io/badge/React%20Three%20Fiber-000000?style=flat-square&logo=threedotjs&logoColor=white)

- Predicts coronary artery disease and stenosis in the LAD, LCX and RCA vessels from **54 non-invasive inputs** (public Z-Alizadeh Sani dataset, 303 patients). Compared **22 candidate models** per target.
- Strict evaluation: a stratified 20% holdout used once, repeated 5-fold cross-validation, a selection rule fixed before looking at results, and 95% bootstrap intervals.
- 🎯 Holdout ROC-AUC **0.90** (95% CI 0.81–0.98) for coronary artery disease and **0.83** for LAD. LCX (0.76) and RCA (0.67) are weaker, and the write-up reports them as they are.
- Leakage guarded by an outcome blacklist, a feature whitelist and tests. Predictions are explained with SHAP and shown as vessel-level risk on an **interactive 3D heart**.
- ⚠️ Research prototype only: single-centre data, no external validation, not a medical device.

### 📞 EchoSarathi: real-time voice AI platform for India

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![LiveKit](https://img.shields.io/badge/LiveKit%20Agents-1F1F1F?style=flat-square)
![LLM](https://img.shields.io/badge/LLM%20tool%20calling-7F00FF?style=flat-square)
![STT/TTS](https://img.shields.io/badge/STT%20%2F%20TTS-E100FF?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

*Six-person, faculty-mentored team project (CEER, CMR College, Aug–Oct 2026)*

- Phones people, talks to them and records structured answers (for example, why a student was absent and when they'll return) with a confidence score per field. Each use case is a JSON config, not code.
- 🔁 Speech recognition → LLM with tool calling → speech synthesis, running through LiveKit and connected to an Indian telephony provider. Tested on real calls to +91 numbers.
- ⚡ Streaming synthesis cut time to first audio from **1,470 ms to 117 ms**. Total response time is still 2.7 s against our 1.5 s target.
- 🛠️ I fixed the LLM failover so the agent moves to the next provider within the same turn. The project has **477 automated tests**.
- 📄 Co-author of a paper covering design, latency, cost (about **₹0.80 per 50-second call**) and limitations.

### 📚 [AI Document Intelligence Assistant](https://github.com/jeevanananepalli-create/jeevana-ai-document-intelligence-assistant)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=flat-square)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

- Answers natural-language questions about stored documents using generative AI.
- Ingestion, processing and retrieval are separate layers, so each can be changed and tested on its own.
- PostgreSQL schema with metadata indexing, a REST API with Pydantic validation and consistent error handling, and Pytest unit tests.

### 🗜️ File Compression with Huffman Coding

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Algorithms](https://img.shields.io/badge/Greedy%20%7C%20Min--heap%20%7C%20Binary%20trees-FF6EC7?style=flat-square)

- Lossless compression tool in C with a min-heap, a binary tree and manual memory management (O(n log n)). Decompressed output is checked to match the original exactly.

---

## 🛠️ Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,c,js,ts,sklearn,fastapi,postgres,docker,react,nextjs,threejs,git,github&perline=13" alt="Tech stack icons" />
</p>

| | |
| --- | --- |
| 💻 **Languages** | Python, C, SQL, JavaScript, TypeScript |
| 🤖 **ML and data** | scikit-learn, XGBoost, SHAP, pandas, cross-validation, bootstrap intervals, generative AI, prompt engineering, LLM tool calling, STT/TTS pipelines |
| ⚙️ **Systems** | FastAPI, REST APIs, LiveKit, PostgreSQL, SQLAlchemy, Pydantic, Docker, Pytest, React, Next.js, Git |
| 🧩 **Foundations** | Data structures and algorithms, object-oriented design, concurrency and synchronization, memory management |

---

## 🏆 Certifications and hackathons

| 📜 Certifications | 🧑‍💻 Hackathons |
| --- | --- |
| **AI/ML for Geodata Analytics**<br/>IIRS, ISRO · Aug 2026 | **Multimodal AI Hackathon 2026**<br/>KamandPrompt, IIT Mandi · Sep–Oct 2026 |
| **GenAI Powered Data Analytics Job Simulation**<br/>Forage · Jun 2026 | **HackWithHyderabad 3.0**<br/>Hack With India × Devnovate, Microsoft Office Hyderabad · Oct 2026 |
| **Data Visualisation: Empowering Business with Effective Insights**<br/>Forage · Jun 2026 | **SPECATHON-2026**<br/>36-hour national-level hackathon, St. Peter's Engineering College · Sep 2026 |

🎖️ Also a cadet in the **National Cadet Corps (NCC)**.

---

## 📊 GitHub stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=jeevanananepalli-create&show_icons=true&theme=radical&hide_border=true&border_radius=12" alt="GitHub stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jeevanananepalli-create&layout=compact&theme=radical&hide_border=true&border_radius=12" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=jeevanananepalli-create&theme=radical&hide_border=true&border_radius=12" alt="GitHub streak" />
</p>

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=jeevanananepalli-create&theme=react-dark&hide_border=true&bg_color=141321&color=E100FF&line=FF6EC7&point=7F00FF&area=true" alt="Contribution graph" />
</p>

<!-- Footer -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF6EC7,50:E100FF,100:7F00FF&height=120&section=footer" width="100%" alt="Footer banner" />
</p>
