<div align="center">

<!-- Animated typing header -->
<a href="https://github.com/dubeykrish0307">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0d0d,100:1a1a2e&height=120&section=header&text=&animation=fadeIn" width="100%"/>
</a>

<!-- Name + tagline -->
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=32&pause=1000&color=E0E0E0&center=true&vCenter=true&width=800&lines=Hi%2C+I'm+Krish+Dubey.;I+build+AI+systems.;Then+I+measure+whether+they+work." alt="Typing SVG" />

<br/>

<p align="center">
  <em>CS student @ SRH Munich &nbsp;·&nbsp; LLM agents · Voice AI · ML APIs &nbsp;·&nbsp; Build it. Measure it. Ship it.</em>
</p>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-dubeykrish-%230077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/dubeykrish)
[![GitHub](https://img.shields.io/badge/GitHub-dubeykrish0307-%23181717?style=flat-square&logo=github&logoColor=white)](https://github.com/dubeykrish0307)
[![Email](https://img.shields.io/badge/Email-dubeykrish0307%40gmail.com-%23EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:dubeykrish0307@gmail.com)
[![Location](https://img.shields.io/badge/Munich%2C_Germany-Student_Visa_(20_hrs%2Fwk)-%23404040?style=flat-square&logo=googlemaps&logoColor=white)](#)

</div>

---

<br/>

## `> whoami`

```python
krish = {
    "role"      : "CS Student → Werkstudent (Applied AI / ML / Backend)",
    "studying"  : "B.Sc. Computer Science @ SRH Hochschule München (2026–2029)",
    "building"  : ["real-time voice AI", "multi-agent document analysis", "ML inference APIs"],
    "mindset"   : "Build it. Measure it. Ship it.",
    "currently" : "Speech-to-text benchmark for SEVRIN · German (Goethe B1)",
    "available" : "20 hrs/week · Open to Werkstudent roles · Munich-based",
}
```

<br/>

---

## `> stack --list`

<div align="center">

**Languages & Core**

![Python](https://img.shields.io/badge/Python-Advanced-%233776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-Intermediate-%23003B57?style=flat-square&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**LLMs & Agents**

![Claude API](https://img.shields.io/badge/Claude_API-%23D97757?style=flat-square&logo=anthropic&logoColor=white)
![OpenAI API](https://img.shields.io/badge/OpenAI_API-%23412991?style=flat-square&logo=openai&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB_RAG-%23444?style=flat-square)
![Pydantic](https://img.shields.io/badge/Pydantic-%23E92063?style=flat-square&logo=pydantic&logoColor=white)

**Voice AI**

![faster-whisper](https://img.shields.io/badge/faster--whisper-%23444?style=flat-square)
![whisper.cpp](https://img.shields.io/badge/whisper.cpp-%23444?style=flat-square)
![ECAPA-TDNN](https://img.shields.io/badge/ECAPA--TDNN_Speaker_Verification-%23444?style=flat-square)

**Backend & APIs**

![FastAPI](https://img.shields.io/badge/FastAPI-%23009688?style=flat-square&logo=fastapi&logoColor=white)
![WebSockets](https://img.shields.io/badge/asyncio_WebSockets-%23404040?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-%232496ED?style=flat-square&logo=docker&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-%2347848F?style=flat-square&logo=electron&logoColor=white)

**ML & Computer Vision**

![Scikit-learn](https://img.shields.io/badge/Scikit--learn-%23F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP_Explainability-%23444?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-%235C3EE8?style=flat-square&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO_Pipelines-%23111?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-%23150458?style=flat-square&logo=pandas&logoColor=white)

</div>

<br/>

---

## `> projects --featured`

<br/>

### 🔷 [SEVRIN](https://github.com/dubeykrish0307/Personal-VA) — Real-Time Voice AI Assistant

> A voice assistant that runs on my laptop, checks it's my voice, and knows when to stay quiet.

| Part | How it works |
|---|---|
| Backend | Python asyncio WebSocket server + Electron desktop app |
| Speech-to-text | faster-whisper plus a resident whisper.cpp server (large-v3-turbo) |
| Speaker verification | ECAPA-TDNN embeddings with cohort score normalisation |
| Reasoning | Claude API, with persistent memory and fact checks before anything is stored |
| Conversation | Wake word, streaming TTS, barge-in, proactive speech (rules first, LLM only for unclear cases) |

**Next:** speech-to-text benchmark (word error rate + latency on my own commands), speaker-verification false-accept / false-reject rates, demo video.

<br/>

### 🔷 [NexusIQ](https://github.com/dubeykrish0307/NexusIQ) — Multi-Agent Document Intelligence

> Agents that extract, analyse and validate financial and legal documents.

Built with FastAPI · OpenAI API · ChromaDB · PyMuPDF · Pydantic · SQLAlchemy · Streamlit · pytest · Docker

**Next (v2):** a labelled evaluation set (retrieval recall@5, faithfulness, field accuracy), hybrid search + reranker, German contracts.

<br/>

### 🔷 [DecisionAPI](https://github.com/dubeykrish0307/DecisionAPI) — Live Churn-Prediction API

> A deployed inference service, not a notebook. [Live docs](https://decisionapi.onrender.com/docs)

| Metric | Result |
|---|---|
| Model quality | **ROC-AUC 0.84** (logistic regression, Telco dataset, ~7,000 customers) |
| Avg. response latency | **< 120 ms** |
| Request validation | **8** input fields checked with Pydantic |
| Drift checks | **3** numeric features, flagged beyond 3σ (Z-score) |
| Model management | Versioned models + retrain endpoint, predictions logged to SQLite |

Built with FastAPI · Docker · Scikit-learn · Z-score drift monitoring · SQLite logging

<br/>

### 🔷 [Explainable Credit Risk Decision System](https://github.com/dubeykrish0307/Explainable-Credit-Risk-Decision-System)

> ML that explains itself, and an honest look at what accuracy hides. [Live app](https://explainable-credit-risk-decision-system.streamlit.app/)

| Held-out test set (200 applicants, 60 defaults) | Result |
|---|---|
| Baseline: approve everyone | **70%** accuracy, **0** defaults caught |
| Logistic regression | **75%** accuracy, ROC-AUC **0.81**, **47 of 60** defaults caught |
| Models compared | **2** (logistic regression, random forest) |
| Decision bands | Approve < 30% · Review 30–60% · Reject > 60% default risk |

Built with Scikit-learn · SHAP · Streamlit · bias checks across age and gender / nationality proxies

<br/>

### 🔷 [German Business Data Insight Engine](https://github.com/dubeykrish0307/GermanBusinessDataAutopsy)

> German retail turnover vs energy prices, read by a rule-based insight engine.

| Part | Detail |
|---|---|
| Data | Destatis retail turnover (nominal and real) + Eurostat non-household electricity prices |
| Span | 2020–2024, half-yearly (where both series overlap) |
| Insight rules | **4**: margin pressure, illusory growth, healthy growth, demand shock |

Built with Pandas · NumPy · Rule-based insight generation

<br/>

---

## `> experience --timeline`

```
2025 Oct  ←─────────────────── BookYouBrand · Computer Vision Engineer (contract)
                                 Rakshak traffic-monitoring system
                                 OpenCV pipelines · 50,000+ frames · 8 camera feeds
                                 YOLO dataset prep · 6 revision rounds · ~28,000 training samples

2025 Mar  ←─────────────────── AWS · ML Intern
                                 Computer-vision project · maintained the ML pipeline
                                 Pipeline documentation · fault and bug reports

2024 Sep  ←─────────────────── Enclo Industries · Freelance Web Developer
                                 Full corporate site · 4-week delivery
```

<br/>

---

## `> stats --github`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=dubeykrish0307&show_icons=true&theme=transparent&hide_border=true&title_color=e0e0e0&text_color=9e9e9e&icon_color=888888&rank_icon=github" height="165"/>
&nbsp;&nbsp;
<img src="https://github-readme-streak-stats.herokuapp.com/?user=dubeykrish0307&theme=transparent&hide_border=true&stroke=333&ring=888888&fire=e0e0e0&currStreakLabel=e0e0e0&sideLabels=9e9e9e&dates=555" height="165"/>

<br/><br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dubeykrish0307&layout=compact&theme=transparent&hide_border=true&title_color=e0e0e0&text_color=9e9e9e&langs_count=6" height="130"/>

</div>

<br/>

---

## `> roadmap --next`

```
Oct 2026   SEVRIN speech-to-text benchmark (word error rate + latency)
Nov 2026   NexusIQ v2: labelled eval set, hybrid search, German contracts
Nov 2026   hackaTUM (applying)
Dec 2026   Munich MCP server + agent eval harness
Jan 2027   Training my own model in PyTorch
```

<br/>

---

## `> contact`

<div align="center">

I'm looking for a **Werkstudent role** in applied AI / LLM engineering, ML engineering or backend in Munich, 20 hrs/week.

If you're building something real and want someone who measures before claiming, let's talk.

<br/>

[![Email Me](https://img.shields.io/badge/→_dubeykrish0307%40gmail.com-reach_out-%23111?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dubeykrish0307@gmail.com)
[![LinkedIn](https://img.shields.io/badge/→_LinkedIn-connect-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/dubeykrish)

</div>

<br/>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,100:0d0d0d&height=80&section=footer" width="100%"/>
</div>
