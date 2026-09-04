<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:F59E0B,50:D97706,100:B45309&height=190&section=header&text=Heshan%20Nethmina&fontSize=46&fontColor=FFFBEB&animation=fadeIn&fontAlignY=36&desc=Software%20Engineering%20%C2%B7%20AI%20Engineering%20%C2%B7%20CSE%20%40%20University%20of%20Moratuwa&descSize=15&descAlignY=57&descColor=FFF7E6" width="100%"/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=21&duration=3200&pause=900&color=F59E0B&center=true&vCenter=true&width=720&height=46&lines=I+build+systems%2C+not+demos.;Go+%C2%B7+Next.js+%C2%B7+TypeScript+%C2%B7+Python;Real-time+backends+and+LLM+agents;Datasets+and+models+for+problems+in+Sri+Lanka" />
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=21&duration=3200&pause=900&color=B45309&center=true&vCenter=true&width=720&height=46&lines=I+build+systems%2C+not+demos.;Go+%C2%B7+Next.js+%C2%B7+TypeScript+%C2%B7+Python;Real-time+backends+and+LLM+agents;Datasets+and+models+for+problems+in+Sri+Lanka" alt="Heshan Nethmina" />
</picture>

<br/>

<a href="https://www.linkedin.com/in/heshan-nethmina-5b9824277"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
<a href="mailto:heshannethmina169@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20hello-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Colombo,%20Sri%20Lanka-D97706?style=flat-square&logo=googlemaps&logoColor=white"/>
<img src="https://img.shields.io/github/followers/heshannethmina?style=flat-square&color=D97706&labelColor=292524&logo=github&logoColor=white"/>
<img src="https://komarev.com/ghpvc/?username=heshannethmina&label=Profile%20views&color=D97706&style=flat-square"/>

</div>

---

## About

I'm a **Computer Science & Engineering undergraduate** at the **University of Moratuwa**, working across **software engineering** and **AI engineering**.

I learn by building. I'd rather ship one working system and understand every layer of it than collect tutorials — which is why my projects tend to include the unglamorous parts: the WebSocket hub, the leakage-free data splits, the evaluation harness that proves the model is actually right.

|  |  |
| :-- | :-- |
| 🎓 **University** | University of Moratuwa, Sri Lanka |
| 📚 **Programme** | B.Sc. Computer Science & Engineering — 3rd Year |
| 🎯 **Focus** | Full-stack systems · AI / LLM engineering |
| 🧱 **Interests** | Distributed systems · Clean architecture · Applied ML |
| 💼 **Open to** | Software & AI engineering internships |
| ♟️ **Off-screen** | Strategy games and coffee |

---

## Featured Work

### 🧑‍💻 [SyncR — Collaborative Code Editor for Technical Interviews](https://github.com/heshannethmina/RAD-Lanka-Project-for-Intern)

<img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white"/> <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/WebSockets-6B7280?style=flat-square"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>

An interviewer opens a room and sends a link; the candidate starts typing. Both sides see the same document live — and the code actually runs. Built as a leaner alternative to CoderPad and HackerRank for startups, small teams and university placement programmes.

- Hand-built WebSocket hub in Go: **one goroutine owns each room's document**, so state moves by message instead of being guarded by locks
- Code execution runs inside isolated **Judge0** containers, never in the application process
- Next.js App Router + Monaco on the front end, PostgreSQL for users, sessions and rooms

<a href="https://demo-syncr.vercel.app/"><img src="https://img.shields.io/badge/▶_Live_demo-000000?style=for-the-badge&logo=vercel&logoColor=white"/></a>


---

### 🌊 [Sri Lanka Flood Dataset & Early-Warning Model](https://github.com/heshannethmina/Srilanka-Flood-Data-Set-Creation)

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white"/> <img src="https://img.shields.io/badge/Deep%20Learning-EF4444?style=flat-square"/> <img src="https://img.shields.io/badge/Sentinel--1%20SAR-0B3D91?style=flat-square"/> <img src="https://img.shields.io/badge/GloFAS%20%C2%B7%20ERA5%20%C2%B7%20NASA%20POWER-6B7280?style=flat-square"/>

A multimodal flood early-warning dataset for Sri Lanka, plus a DNN baseline trained on it — because the country has the flooding but not the machine-readable record of it.

- **410K daily hydro-meteorological node records** fused from GloFAS, NASA POWER and ERA5
- **1,045 paired Sentinel-1 SAR chips** aligned to those nodes for visual ground truth
- Leakage-free splits designed specifically for **GNN + CNN fusion**, so reported accuracy means something

---

### 🎙️ [Emotion-Labelled Sinhala Speech Dataset & Expressive Sinhala TTS](https://github.com/DSEgrp18/Dataset-creation-withEmotion)

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/> <img src="https://img.shields.io/badge/Google%20Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white"/> <img src="https://img.shields.io/badge/XTTS--v2-10B981?style=flat-square"/> <img src="https://img.shields.io/badge/F5--TTS-14B8A6?style=flat-square"/> <img src="https://img.shields.io/badge/Speech%20Processing-6B7280?style=flat-square"/>

Two halves of the same problem: building the emotion-labelled Sinhala speech corpus that does not exist, then using it to train a Sinhala text-to-speech voice that actually sounds human — natural prosody and audible emotion, not flat read-speech.

**The dataset** — sentence-level clips with transcripts and emotion labels, mined from SLBC radio dramas.

- Radio drama is the source on purpose — shouting, crying, whispering and arguing are exactly what read-speech corpora lack
- **64.2% usable yield** per episode against an original projection of 10–20%, with **zero overlapping clips**, asserted at the end of every run
- Every open-weight Sinhala ASR checkpoint was benchmarked and failed on this domain; the transcription decision is documented against measured output, not model cards
- 201 episodes / 82 hours available, with ~52 hours of clean speech projected

**The TTS** — **XTTS-v2** fine-tuned on the corpus, with **F5-TTS** as the comparison baseline.

- XTTS-v2 is the primary model: multilingual pretraining plus speaker conditioning means the corpus is spent on Sinhala prosody and emotion rather than on learning speech from scratch
- Emotion is carried by reference audio at inference, so one voice can be re-conditioned across emotions instead of training a separate model per emotion
- Naturalness is the target metric — MOS listening tests against the baseline, with the corpus and the fine-tuning recipe released together so the numbers can be reproduced

<sub>Group project · DSE Group 18</sub>

---

### 🛡️ [Security Scanner Triage Agent](https://github.com/Heshan-Nethmina/Security-Scanner-Triage-Agent)

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/LLM%20Agent-F59E0B?style=flat-square"/> <img src="https://img.shields.io/badge/RAG%20%C2%B7%20ChromaDB-8B5CF6?style=flat-square"/> <img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white"/> <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>

Scanner output is a flat, noisy list with generic severities and no fix guidance. This agent ingests raw Nuclei / Semgrep JSON and returns a deduplicated, re-prioritized, **remediated** report with a dashboard.

- **Grounded in retrieved data, not model memory** — RAG over a local CVE/CWE vector store returns the correct Log4Shell fix (`2.17.1`) where the bare model insists on `2.15.1`
- **Re-prioritizes rather than relabels**: escalates an exposed `.env` above the scanner's own severity, with a stated reason
- **Measured, not vibes** — an eval harness scores priority accuracy and false-positive precision/recall against a labelled key; every model call logs tokens, latency and cost
- Defensive by design: it explains how to fix findings, and never generates exploits or payloads

---

### 📊 [LeadDesk — Multi-Tenant Lead Tracking CRM](https://github.com/heshannethmina/leaddesk)

<img src="https://img.shields.io/badge/React%2018-61DAFB?style=flat-square&logo=react&logoColor=black"/> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/> <img src="https://img.shields.io/badge/Vite%205-646CFF?style=flat-square&logo=vite&logoColor=white"/> <img src="https://img.shields.io/badge/Tailwind%20v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/> <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white"/> <img src="https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white"/>

A lightweight CRM for small businesses. Owners log inquiries arriving across WhatsApp, Instagram, Facebook, phone and walk-in, then move each one through **New → Contacted → Quoted → Won / Lost** with quick-reply templates and a metrics dashboard.

- Multi-tenancy enforced in the database with **Supabase Row Level Security**, not in application code
- **Stripe** billing with plan-based usage limits and team seats
- Tailwind v4 with OKLCH design tokens, Recharts dashboards, Supabase Edge Functions

<a href="https://leaddesk-orpin.vercel.app"><img src="https://img.shields.io/badge/▶_Live_demo-000000?style=for-the-badge&logo=vercel&logoColor=white"/></a>

---

<details>
<summary><b>Earlier projects</b></summary>

<br/>

**🚌 OnTime G1 — IoT Bus Tracking System** · `Arduino` `C++` `MQTT` `GPS/GSM`<br/>
Real-time vehicle tracking on an Arduino Nano with a NEO-6M GPS and SIM800L GSM module, publishing positions over MQTT.

**🧠 SynapseAI — Study Companion** · `JavaScript` `HTML` `CSS`<br/>
AI-powered study tool with content generation and model selection.

</details>

---

## Tech Stack

<table>
<tr><td><b>Languages</b></td><td>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white"/>
<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black"/>
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
</td></tr>
<tr><td><b>Frontend</b></td><td>
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white"/>
<img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>
<img src="https://img.shields.io/badge/Recharts-22B5BF?style=flat-square"/>
<img src="https://img.shields.io/badge/Monaco%20Editor-0078D4?style=flat-square&logo=visualstudiocode&logoColor=white"/>
</td></tr>
<tr><td><b>Backend &amp; Data</b></td><td>
<img src="https://img.shields.io/badge/Go%20net%2Fhttp-00ADD8?style=flat-square&logo=go&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/WebSockets-6B7280?style=flat-square"/>
</td></tr>
<tr><td><b>AI &amp; ML</b></td><td>
<img src="https://img.shields.io/badge/LLM%20Agents-F59E0B?style=flat-square"/>
<img src="https://img.shields.io/badge/RAG%20%C2%B7%20Vector%20DBs-8B5CF6?style=flat-square"/>
<img src="https://img.shields.io/badge/Google%20Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/>
<img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white"/>
</td></tr>
<tr><td><b>Infra &amp; Tooling</b></td><td>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
<img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white"/>
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
<img src="https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white"/>
<img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white"/>
</td></tr>
</table>

---

## GitHub Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=heshannethmina&name=Heshan%20Nethmina&theme=gruvbox&bg_color=00000000&title_color=F59E0B&text_color=C9D1D9&icon_color=F59E0B&chart_color=F59E0B&border_color=30363D&animation=draw" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=heshannethmina&name=Heshan%20Nethmina&theme=default&bg_color=00000000&title_color=B45309&text_color=44403C&icon_color=D97706&chart_color=D97706&border_color=E7E0D4&animation=draw" width="700" alt="Contributions over the last year"/>
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=heshannethmina&exclude=html,css&theme=gruvbox&bg_color=00000000&title_color=F59E0B&text_color=C9D1D9&icon_color=F59E0B&chart_color=F59E0B&border_color=30363D&animation=draw" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=heshannethmina&exclude=html,css&theme=default&bg_color=00000000&title_color=B45309&text_color=44403C&icon_color=D97706&chart_color=D97706&border_color=E7E0D4&animation=draw" width="340" alt="Top languages by repository"/>
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=heshannethmina&exclude=html,css&theme=gruvbox&bg_color=00000000&title_color=F59E0B&text_color=C9D1D9&icon_color=F59E0B&chart_color=F59E0B&border_color=30363D&animation=draw" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=heshannethmina&exclude=html,css&theme=default&bg_color=00000000&title_color=B45309&text_color=44403C&icon_color=D97706&chart_color=D97706&border_color=E7E0D4&animation=draw" width="340" alt="Top languages by commit"/>
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=heshannethmina&utcOffset=5.5&theme=gruvbox&bg_color=00000000&title_color=F59E0B&text_color=C9D1D9&icon_color=F59E0B&chart_color=F59E0B&border_color=30363D&animation=draw" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=heshannethmina&utcOffset=5.5&theme=default&bg_color=00000000&title_color=B45309&text_color=44403C&icon_color=D97706&chart_color=D97706&border_color=E7E0D4&animation=draw" width="340" alt="Commits by hour of day"/>
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=heshannethmina&hide_logo=true&theme=gruvbox&bg_color=00000000&title_color=F59E0B&text_color=C9D1D9&icon_color=F59E0B&chart_color=F59E0B&border_color=30363D&animation=draw" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=heshannethmina&hide_logo=true&theme=default&bg_color=00000000&title_color=B45309&text_color=44403C&icon_color=D97706&chart_color=D97706&border_color=E7E0D4&animation=draw" width="340" alt="Contribution stats"/>
</picture>

</div>

---

## Connect

<div align="center">

<a href="https://www.linkedin.com/in/heshan-nethmina-5b9824277"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:heshannethmina169@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/heshannethmina"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

<br/><br/>

<b>Open to Software &amp; AI Engineering internships.</b><br/>
<sub>Always building something — if one of these projects is useful to you, say hello.</sub>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:B45309,50:D97706,100:F59E0B&height=110&section=footer" width="100%"/>
