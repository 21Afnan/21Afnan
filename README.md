<p align="center">
  <img src="assets/hero.svg" alt="Afnan Shoukat - AI Lead Engineer @ IT CYBX" width="100%"/>
</p>

<p align="center">
  <a href="https://afnanshoukat.vercel.app"><img src="https://img.shields.io/badge/Portfolio-afnanshoukat.vercel.app-FF69B4?labelColor=1a0d2b&style=for-the-badge&logo=firefox&logoColor=white" alt="Portfolio"/></a>
  <a href="https://linkedin.com/in/afnanshoukat"><img src="https://img.shields.io/badge/LinkedIn-Afnan%20Shoukat-FF69B4?labelColor=1a0d2b&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:afnanshoukat35@gmail.com"><img src="https://img.shields.io/badge/Email-Get%20in%20touch-FF69B4?labelColor=1a0d2b&style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

<p align="center"><img src="assets/divider.svg" width="100%" alt=""/></p>

## About

I'm an AI Lead Engineer at [IT CYBX](https://itcybx.co.uk) in Islamabad and a final-year BS Artificial Intelligence student at NUML. I got into AI through ML projects and kept going until it became client work: today I build the systems that take repetitive admin off small teams, and I care most about the unglamorous part, making them keep working after the demo.

My background is a mix of research-style ML (quant trading, time-series forecasting, medical imaging) and applied automation (agents, chatbots, n8n workflows, voice AI). I like owning a project from data to dashboard.

## What I build

| | What it covers | Typical use |
|---|---|---|
| **AI agents & chatbots** | LangGraph / LangChain agents, RAG over company knowledge, human hand-off | Support, lead capture, booking and scheduling |
| **Business automation** | n8n workflows, API and backend integrations, Google Sheets / Drive pipelines | Applications, candidate screening, follow-ups, spreadsheet updates |
| **Voice AI** | Speech-to-text, retrieval, multi-LLM routing, spoken answers | Voice-first question answering over website content |
| **Applied ML & MLOps** | Forecasting, NLP, computer vision, feature stores, scheduled retraining | Predictions and dashboards that stay current without manual work |

## How I work

Prototypes are easy; production is where AI systems fail. Before I call something done I check:

- **Failure paths:** retries, fallbacks and what happens when an upstream API is down
- **Validation:** inputs and model outputs are checked, not trusted (hallucinations, malformed data, duplicates)
- **Evaluation:** honest backtests and held-out data. On CryptoSight I found and removed look-ahead bias in my own strategy evaluation
- **Operations:** monitoring, cost and latency at scale, and guardrails around anything customer-facing

<p align="center"><img src="assets/divider.svg" width="100%" alt=""/></p>

## Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">CryptoSight</h3>
      <p align="center">
        <a href="https://github.com/21Afnan/cryptosight">
          <img src="https://raw.githubusercontent.com/21Afnan/cryptosight/main/docs/screenshots/Dashboard.png" alt="CryptoSight dashboard" width="100%" />
        </a>
      </p>
      <p>
        Quant trading platform built solo during the NeuroG.AI internship. Reddit sentiment (FinBERT) and technical indicators feed 12 ML signal models. A vectorized backtester accounts for fees, slippage, PnL and drawdown, and trades execute on Bybit testnet from a live dashboard.
      </p>
      <p align="center"><sub><b>FinBERT · ML signals · Backtesting · Bybit · React</b></sub></p>
      <p align="center"><a href="https://github.com/21Afnan/cryptosight"><img src="https://img.shields.io/badge/View%20Repo-FF69B4?style=for-the-badge&logo=github&logoColor=white" alt="repo"/></a></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">AirLyst</h3>
      <p align="center">
        <a href="https://github.com/21Afnan/AirLyst">
          <img src="https://raw.githubusercontent.com/21Afnan/AirLyst/main/assets/ssfg/AeroVibe%20Main%20Dashboard.png" alt="AirLyst dashboard" width="100%" />
        </a>
      </p>
      <p>
        Forecasts Islamabad's air quality 72 hours ahead. A daily pipeline ingests weather and AQI data into a Hopsworks feature store, a weekly tournament (Ridge, Random Forest, XGBoost, LightGBM) promotes the best model (<b>R² 0.986</b>), and SHAP explanations are rewritten in plain language with Gemini. <a href="https://air-lyst.vercel.app">Live demo</a>.
      </p>
      <p align="center"><sub><b>Hopsworks · LightGBM · SHAP · FastAPI · Next.js · GitHub Actions</b></sub></p>
      <p align="center"><a href="https://github.com/21Afnan/AirLyst"><img src="https://img.shields.io/badge/View%20Repo-FF69B4?style=for-the-badge&logo=github&logoColor=white" alt="repo"/></a></p>
    </td>
  </tr>

  <tr>
    <td width="50%" valign="top">
      <h3 align="center">Multi-Role Hiring Automation</h3>
      <p align="center">
        <a href="https://github.com/21Afnan/n8n-multi-role-hiring-automation">
          <img src="https://raw.githubusercontent.com/21Afnan/n8n-multi-role-hiring-automation/main/assets/screenshots/Workflow1.png" alt="Hiring workflow" width="100%" />
        </a>
      </p>
      <p>
        Screens applicants across roles (software engineering, business development). Reads applications from Google Sheets, validates and deduplicates them, grades resumes from Drive with AI (strong / average / weak), then schedules interviews, notifies hiring managers or sends rejections and syncs status to a master sheet. Self-reported result: about 85% less manual screening time.
      </p>
      <p align="center"><sub><b>n8n · Google Sheets / Drive · LLM grading</b></sub></p>
      <p align="center"><a href="https://github.com/21Afnan/n8n-multi-role-hiring-automation"><img src="https://img.shields.io/badge/View%20Repo-FF69B4?style=for-the-badge&logo=github&logoColor=white" alt="repo"/></a></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">IT CYBX Live Bot</h3>
      <p align="center">
        <a href="https://github.com/21Afnan/itcybx_live_bot">
          <img src="https://opengraph.githubassets.com/1da239e2551ce36be42877215a45bed78d8179c170dcc4c136f686dd01c8fa40/21Afnan/itcybx_live_bot" alt="IT CYBX Live Bot" width="100%" />
        </a>
      </p>
      <p>
        Bilingual (English / Arabic) sales chatbot running on itcybx.co.uk. Answers FAQs from a RAG knowledge base, captures leads, books calls through Calendly and alerts the team.
      </p>
      <p align="center"><sub><b>LangGraph · Pinecone · FastAPI</b></sub></p>
      <p align="center"><a href="https://github.com/21Afnan/itcybx_live_bot"><img src="https://img.shields.io/badge/View%20Repo-FF69B4?style=for-the-badge&logo=github&logoColor=white" alt="repo"/></a></p>
    </td>
  </tr>

  <tr>
    <td width="50%" valign="top">
      <h3 align="center">VoiceIQ</h3>
      <p align="center">
        <a href="https://github.com/21Afnan/VoiceIQ">
          <img src="https://raw.githubusercontent.com/21Afnan/VoiceIQ/main/ScreenShots_website/frontpage.png" alt="VoiceIQ front page" width="100%" />
        </a>
      </p>
      <p>
        Voice-first assistant that answers questions from a website's content. Deepgram transcribes the question, FAISS retrieves context, several LLMs (Gemini, DeepSeek, Kimi) answer in parallel, and the reply comes back as text and audio.
      </p>
      <p align="center"><sub><b>Deepgram · FAISS · multi-LLM routing · FastAPI</b></sub></p>
      <p align="center"><a href="https://github.com/21Afnan/VoiceIQ"><img src="https://img.shields.io/badge/View%20Repo-FF69B4?style=for-the-badge&logo=github&logoColor=white" alt="repo"/></a></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">BillSense</h3>
      <p align="center">
        <a href="https://github.com/21Afnan/BillSense">
          <img src="https://raw.githubusercontent.com/21Afnan/BillSense/main/assets/img1.png" alt="BillSense screenshot" width="100%" />
        </a>
      </p>
      <p>
        Explains Pakistani utility bills (K-Electric, LESCO, IESCO). Local OCR, layout rules and arithmetic checks turn a bill into structured JSON, so users can inspect charges and taxes and ask follow-up questions in plain language. Built for the "Build with AI" track at Women Tech Quest 2026 (10Pearls, FAST-NUCES).
      </p>
      <p align="center"><sub><b>OCR · Rule-based validation · LLM Q&amp;A</b></sub></p>
      <p align="center"><a href="https://github.com/21Afnan/BillSense"><img src="https://img.shields.io/badge/View%20Repo-FF69B4?style=for-the-badge&logo=github&logoColor=white" alt="repo"/></a></p>
    </td>
  </tr>
</table>

<details>
<summary><b>More projects (7)</b></summary>
<br/>

| Project | What it does | Stack | Repo |
|---|---|---|---|
| **Inbox Guardian** | Local email triage: classifies mail, sends important items to Discord, cleans junk from Gmail | n8n · Gemini · Docker | [Open](https://github.com/21Afnan/Inbox_Guardian) |
| **SOC Analyst Advisor** | Cybersecurity copilot for threat detection, incident response and playbooks, running a local model | Mistral 7B | [Open](https://github.com/21Afnan/SOC_Analyst_Advisor) |
| **NeuroAssistAI** | Brain-tumour classification from MRI and glioma-stage prediction from gene-mutation data, to assist neurologists | Deep learning | [Open](https://github.com/21Afnan/NeuroAssistAI) |
| **TumorSense-AI** | Brain MRI tumour classifier | CNN · ResNet-18 | [Open](https://github.com/21Afnan/TumorSense-AI) |
| **CycleSenseAI** | Cycle-date prediction with an embedded chatbot and Supabase auth | LSTM · Supabase | [Open](https://github.com/21Afnan/CycleSenseAI) |
| **PakShield AI** | Border-monitoring computer vision and threat intelligence | Computer vision | [Open](https://github.com/21Afnan/PakShield_Defence_AI) |
| **Voice Modules** | Reusable speech-to-text, text-to-speech and speech-to-speech APIs | FastAPI · OpenAI | [Open](https://github.com/21Afnan/Voice_Module) |

</details>

<p align="center"><img src="assets/divider.svg" width="100%" alt=""/></p>

## Experience & Education

| When | Where | What |
|---|---|---|
| **Present** | **IT CYBX**: AI Lead Engineer | Agents, chatbots, automation and AI-integrated systems for agencies and growing teams |
| **Summer 2026** | **NeuroG.AI**: AI/ML Engineer intern (Neuroship) | Designed and built CryptoSight end to end, solo, with mentor guidance |
| **Summer 2026** | **10Pearls Pakistan**: Shine Internship, Data Sciences | Data science and MLOps practice; also competed at Women Tech Quest 2026 |
| **Oct 2025** | **Prudential Solutions**: Conversational AI intern | Conversational AI development |
| **Mentoring** | **DevSynt**: AI Automation internship mentor | Guided interns through Python, LangChain, LangGraph, n8n, Telegram bots and Gemini integrations |
| **2023 - 2027** | **NUML Islamabad**: BS Artificial Intelligence | CGPA 3.79 / 4.0 |

## Tech I work with

<p align="center">
  <img src="assets/tools.svg" alt="Languages, ML, agents and deployment tools" width="100%"/>
</p>

## Activity

<p align="center">
  <img src="assets/contrib3d.svg" alt="3D isometric view of the last year of contributions" width="100%"/>
</p>

<p align="center"><img src="assets/divider.svg" width="100%" alt=""/></p>

## Writing

I write on LinkedIn about running AI in the real world: RAG vs fine-tuning, why prototypes break in production, how tokens and context windows drive usage, and lessons from shipping software to a real business. [Follow along on LinkedIn](https://linkedin.com/in/afnanshoukat).

## Work with me

Open to AI agent, chatbot and workflow-automation projects, and to conversations about applied ML.

- Email: [afnanshoukat35@gmail.com](mailto:afnanshoukat35@gmail.com)
- LinkedIn: [linkedin.com/in/afnanshoukat](https://linkedin.com/in/afnanshoukat)
- Portfolio: [afnanshoukat.vercel.app](https://afnanshoukat.vercel.app)
