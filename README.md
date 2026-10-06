<div align="center">

<img src="assets/header.svg" alt="Sheik Iqbal Meera John, AI Engineer and Full-Stack Developer, Visakhapatnam" width="100%"/>

### I build AI that **remembers**, **sees**, and knows when to say no.

<sub>Memory-first AI · visual search agents · payment agents · shipped with tests you can run</sub>

[![Portfolio](https://img.shields.io/badge/Portfolio-iqbalmeerajohn.github.io-f2b134?style=for-the-badge&logo=googlechrome&logoColor=070b16&labelColor=ece8dc)](https://iqbalmeerajohn.github.io/portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sheik-iqbal-meera-john-056191253/)
[![Email](https://img.shields.io/badge/Email-iqbalmeerajohn1%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:iqbalmeerajohn1@gmail.com)

![Profile views](https://komarev.com/ghpvc/?username=iqbalmeerajohn&color=f2b134&style=flat-square&label=profile+views)

</div>

<br/>

<a href="https://iqbalmeerajohn.github.io/portfolio/"><img src="https://iqbalmeerajohn.github.io/portfolio/assets/og.jpg" alt="My portfolio: 24,000 particles that rebuild each project as you scroll" width="100%"/></a>

<p align="center"><sub>My portfolio is one Three.js particle system: 24,000 dots that burst and re-form into each project as you scroll, with a custom shader and sound generated live in the browser. <a href="https://iqbalmeerajohn.github.io/portfolio/"><b>Open it</b></a> · <a href="https://github.com/Iqbalmeerajohn/portfolio">how it works</a></sub></p>

---

## About me

I build AI products and the backend systems under them: memory layers, vector search, agent loops with hard guardrails, and the APIs and frontends that ship them.

- **Now:** Web Developer Intern at **Spotmies** (Sep 2026 to present)
- **Education:** B.Tech, Computer Science (Data Science), GITAM University, Visakhapatnam, 2022 to 2026
- **Open to:** full-time AI, backend and full-stack roles, and freelance web projects

<div align="center">

| 1,216 | 1,059 | ~20,000 | 92% | Top 30 / ~350 |
|:---:|:---:|:---:|:---:|:---:|
| backend tests passing in GUMMY OS | saree images indexed for visual search | randomized inputs proving SALVAGE never overspends | speech emotion accuracy on RAVDESS | GITAM tech poster presentation 2026 |

</div>

---

## Projects

<table>
<tr>
<td width="50%" valign="top">

### 🧠 GUMMY OS
**A memory-first personal AI operating system that runs on your own machine.**

It learns from conversations, stores memories in PostgreSQL with pgvector, and ranks them by meaning, importance, recency and confidence before any agent replies.

| Backend tests | API endpoints | Migrations | Agents | Tools |
|:---:|:---:|:---:|:---:|:---:|
| **1,216** | **73** across 15 routers | **25** | **6** routed + general + recall | **17** |

`FastAPI` `SQLAlchemy async` `PostgreSQL` `pgvector` `Alembic` `Ollama` `Langfuse` `Next.js 16` `Docker`

[**Watch it work (24s)**](https://github.com/Iqbalmeerajohn/GUMMY-OS/raw/2716be98830e/docs/media/gummy-os.mp4) · [Code](https://github.com/Iqbalmeerajohn/GUMMY-OS)

</td>
<td width="50%" valign="top">

<a href="https://github.com/Iqbalmeerajohn/GUMMY-OS/raw/2716be98830e/docs/media/gummy-os.mp4"><img src="https://github.com/Iqbalmeerajohn/GUMMY-OS/raw/2716be98830e/docs/media/gummy-os-poster.jpg" alt="GUMMY OS answering a question from a local document, citing Resume.pdf page 1" width="100%"/></a>

</td>
</tr>

<tr>
<td width="50%" valign="top">

<a href="https://saree-visual-similarity-search.streamlit.app/"><img src="https://raw.githubusercontent.com/Iqbalmeerajohn/saree-visual-similarity-search/main/eval/grids/query_00041.png" alt="A real query and its top five visually similar sarees" width="100%"/></a>
<sub>A real query (left) and its top 5 matches, from the project's evaluation set.</sub>

</td>
<td width="50%" valign="top">

### 🥻 Saree Visual Similarity Search
**Upload a saree photo, get the closest designs back, with reasons.**

A LangChain agent on Gemini decides when to run visual search, applies filters, and explains each match with similarity sub-scores. Tiled multi-crop embeddings and attribute reranking handle fine-grained patterns.

| Images | Designs | CI tests |
|:---:|:---:|:---:|
| **1,059** | **645** | **85** |

`FashionSigLIP` `FAISS exact cosine` `LangChain` `Gemini` `Streamlit` `GitHub Actions`

[**Live app**](https://saree-visual-similarity-search.streamlit.app/) · [Code](https://github.com/Iqbalmeerajohn/saree-visual-similarity-search)

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 💸 SALVAGE, the revenue recovery agent
**Built for the Razorpay AI Builder Buildathon 2026 (Track 03).**

When a payment fails, SALVAGE decides who deserves a retry, prices the nudge, and measures lift against a real control group. The LLM only proposes; a pure, tested policy function owns every rupee.

| Agent loop | Tests | Property inputs |
|:---:|:---:|:---:|
| **9** stages | **27** | **~20,000** |

Exactly-once execution and a hash-chained audit log.

`FastAPI` `Gemini` `Razorpay test mode` `SQLite` `Next.js`

[Code](https://github.com/Iqbalmeerajohn/Salvage)

</td>
<td width="50%" valign="top">

```
payment.failed
→ observe → reason → plan
→ POLICY GATE
  (pure function,
   owns the money)
→ approve → execute
→ verify → audit
→ recover
```
<sub>The model can suggest. It can never move more money than the merchant's caps allow.</sub>

</td>
</tr>

<tr>
<td width="50%" valign="top">

```
audio
→ MFCC: 120 coeffs × 94 frames
→ multi-head attention
→ 8 emotions

trained with FedAvg:
raw audio never leaves
its client
```

</td>
<td width="50%" valign="top">

### 🎙️ Speech Emotion Recognition
**Top 30 of ~350 projects at the GITAM tech poster presentation 2026.**

Classifies 8 emotions (neutral, calm, happy, sad, angry, fearful, disgust, surprised) with **92% accuracy on RAVDESS**, trained across partitioned clients with FedAvg.

`TensorFlow` `librosa` `FastAPI` `Streamlit`

[Code](https://github.com/Iqbalmeerajohn/emotion-recognition-speech)

</td>
</tr>

<tr>
<td width="50%" valign="top">

### ☕ KAFA Cafe Digital Platform
**A mobile-first restaurant platform.**

Digital menu, QR ordering, table reservations and an admin dashboard.

`Next.js 15` `TypeScript` `React` `Tailwind CSS` `Vercel`

[**Live site**](https://kafa-cafe-resto.vercel.app) · [Code](https://github.com/Iqbalmeerajohn/kafa-cafe-resto)

<a href="https://kafa-cafe-resto.vercel.app"><img src="https://iqbalmeerajohn.github.io/portfolio/assets/kafa.webp" alt="KAFA Cafe homepage" width="100%"/></a>

</td>
<td width="50%" valign="top">

### 🍬 CHOMPY
**A playful candy-brand homepage that reads like a real company.**

Brand identity, illustration, motion and responsive craft.

`Next.js` `TypeScript` `Tailwind CSS`

[**Live site**](https://candy-brand-homepage.vercel.app) · [Code](https://github.com/Iqbalmeerajohn/candy-brand-homepage)

<a href="https://candy-brand-homepage.vercel.app"><img src="https://iqbalmeerajohn.github.io/portfolio/assets/chompy.webp" alt="CHOMPY homepage" width="100%"/></a>

</td>
</tr>
</table>

---

## Experience

| When | Role | Where |
|---|---|---|
| Sep 2026 to present | **Web Developer Intern** | Spotmies |
| Apr 2025 to Jun 2025 | AWS Data Engineering Virtual Intern: ETL pipelines, cloud storage | EduSkills |
| Jul 2024 | Data Science Virtual Intern: sales prediction, fraud detection, analytics | Cognorise InfoTech |

---

## Tech I use

<div align="center">

<img src="https://skillicons.dev/icons?i=python,ts,js,fastapi,postgres,sqlite,nextjs,react,tailwind,threejs,tensorflow,docker,git,vercel&perline=7" alt="Python, TypeScript, JavaScript, FastAPI, PostgreSQL, SQLite, Next.js, React, Tailwind, Three.js, TensorFlow, Docker, Git, Vercel"/>

<br/><br/>

**AI and search:** `LangChain` `Gemini` `Ollama` `RAG` `Embeddings` `pgvector` `FAISS` `FashionSigLIP` `Federated learning`
<br/>
**Backend:** `FastAPI` `SQLAlchemy` `Alembic` `JWT` `REST` `async Python`
<br/>
**Frontend and motion:** `Next.js` `React` `Tailwind CSS` `Three.js` `GSAP` `WebAudio` `Streamlit`

</div>

---

## How I work

I write software to ship. Every system starts with what the user actually needs: clear APIs, predictable behaviour, and tests that catch regressions before they reach anyone.

In AI work, the value is usually in the layer around the model: the memory, the retrieval, and the guardrails that decide what the model is allowed to touch. The model is a component; the architecture is the product.

---

<div align="center">

**Hiring, or need a website that works?**

[![Portfolio](https://img.shields.io/badge/See%20my%20portfolio-f2b134?style=for-the-badge&logo=googlechrome&logoColor=070b16)](https://iqbalmeerajohn.github.io/portfolio/)
[![Email](https://img.shields.io/badge/iqbalmeerajohn1%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:iqbalmeerajohn1@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:f2b134,45:14203f,100:070b16&height=110&section=footer" width="100%"/>

</div>
