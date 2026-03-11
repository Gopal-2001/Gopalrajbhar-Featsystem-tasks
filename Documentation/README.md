# 🤖 AI/ML Work Activity — Gopalrajbhar Featsystem Tasks

> A comprehensive record of all AI/ML research, development, and deployment work completed across multiple projects — including OCR pipelines, compliance chatbots, voice agents, and real-time calling systems.

---

## 📁 Repository Structure

```
📦 Gopalrajbhar-Featsystem-tasks
 ┣ 📂 Documentation
 ┃ ┣ 📄 README.md
 ┃ ┗ 📄 Work_Activity_Report.docx
```

---

## 🗂️ Project Overview

| # | Project Area | Key Technologies |
|---|---|---|
| 1 | Foundation & Learning | LLMs, Git/GitHub, Django |
| 2 | OCR & Document Intelligence | PaddleOCR, MiniCPM, OlmOCR, EasyOCR, Donut, Granite, DeepSeek |
| 3 | Compliance Chatbot | REST APIs, Architecture Design, Django |
| 4 | Bank Chequebook Data Extraction | HDFC Dataset, rf-detr, pytesseract, OlmOCR |
| 5 | Classification & Data Extraction | Qwen3, LLM Fine-tuning |
| 6 | Voice & Conversational AI | Moshi, Mini-omni2, Sarvam.ai, Personaplex, TTS/STT, Twilio |

---

## 🚀 Phase 1 — Foundation & Learning

Built a strong technical foundation before moving into project work.

- 📖 **LLM Fundamentals** — Studied transformer architecture, tokenization, inference, and prompt engineering
- 🔧 **Git & GitHub** — Mastered version control workflows, branching, merging, pull requests
- 🌐 **Django Chatbot** — Built a chatbot using the Django framework with REST API integration

---

## 🔍 Phase 2 — OCR & Document Intelligence

Extensive research and fine-tuning of OCR models for structured document extraction.

### PaddleOCR Fine-Tuning (Det + Rec)
- Fine-tuned both Detection and Recognition components
- Multiple training iterations for domain-specific accuracy

### Multi-Model Evaluation — Bank Chequebook Extraction

| Model | Approach |
|---|---|
| **MiniCPM-v 4.5** | Multimodal vision-language extraction |
| **EasyOCR + Donut** | Combined pipeline for field detection |
| **Granite 4.0** | IBM model for structured document fields |
| **Granite 4.0 + PaddleOCR** | Hybrid pipeline for best coverage |
| **DeepSeekOCR** | Financial document OCR exploration |
| **OlmOCR** | Multiple sessions + custom fine-tuning |
| **rf-detr + pytesseract** | Object detection + Tesseract OCR |
| **OlmOCR + pytesseract** | Ensemble approach for improved reliability |

### Fine-Tuning Work
- ✅ OlmOCR fine-tuned on custom labeled chequebook dataset
- ✅ MiniCPM dataset prepared and fine-tuning pipeline executed

---

## 🛡️ Phase 3 — Compliance-Focused Chatbot

End-to-end design and development of a Compliance Chatbot system.

### Architecture & Design
- Designed full system architecture, workflow, and technical requirements
- Developed multi-phase workflow with in-depth phase analysis
- Created master architecture presentation for stakeholder review

### APIs Built

| Endpoint | Description | Status |
|---|---|---|
| `POST /register` | User registration with secure credential storage | ✅ Done |
| `POST /login` | JWT-based authentication | ✅ Done |
| `POST /refresh` | Token refresh for session continuity | ✅ Done |
| `GET /file` | Secure file retrieval | ✅ Done |
| All APIs | Live demo presented to team | ✅ Presented |

---

## 🏦 Phase 4 — HDFC Dataset Preparation & Classification

### Dataset Preparation
- 9+ sessions of dedicated HDFC bank document data collection, annotation, and cleaning
- Ensured data quality and consistency for downstream model training

### Qwen3 Classification & Extraction
- Configured Qwen3 LLM for document classification
- Ran classification experiments and extended to data extraction tasks

---

## 🎙️ Phase 5 — Voice & Conversational AI

Built real-time voice and conversation bots using state-of-the-art speech models.

### Models Explored & Built

| Model / Platform | Work Done | Status |
|---|---|---|
| **Interview Bot** | Error fixes and optimization attempts | 🔄 Ongoing |
| **Kyutai Moshi** | Full conversation bot — 10+ dev sessions | ✅ Built |
| **Mini-omni2** | Live voice conversation bot | ✅ Built |
| **Flash Lab** | Conversation bot endpoint | ✅ Built |
| **NVIDIA Personaplex** | Multi-turn conversation bot | ✅ Deployed |
| **NVIDIA Magpie (TTS)** | Text-to-Speech endpoint | ✅ Built |

---

## 📞 Phase 6 — EMI Recovery Agent & AI Calling Agents

Intelligent AI-powered calling agents for automated EMI recovery.

### Pipeline Components Built

| Component | Details | Status |
|---|---|---|
| **Sarvam.ai Integration** | Indian language STT/TTS models integrated | ✅ Done |
| **STT Integration** | Speech-to-Text in calling agent | ✅ Done |
| **TTS Integration** | Text-to-Speech in calling agent | ✅ Done |
| **Twilio Dialer** | Real phone dialing capability | ✅ Done |
| **Latency Optimization** | Reduced end-to-end response time | ✅ Done |
| **Actionable Endpoints** | REST APIs for Actionable team integration | ✅ Done |
| **REST API** | Full calling agent via REST | ✅ Working |
| **WebSocket Upgrade** | Real-time communication (explored) | 🔄 In Progress |
| **Personaplex S2S Deploy** | Final Speech-to-Speech deployment | ✅ Deployed |

---

## 🛠️ Technologies Used

**AI / ML Models**
`Qwen3` `MiniCPM-v` `OlmOCR` `PaddleOCR` `Granite 4.0` `DeepSeekOCR` `EasyOCR` `Donut` `Moshi` `Mini-omni2` `NVIDIA Personaplex` `NVIDIA Magpie` `Sarvam.ai`

**Frameworks & Tools**
`Django` `FastAPI` `Twilio` `pytesseract` `rf-detr` `Git` `GitHub`

**Techniques**
`LLM Fine-tuning` `OCR Fine-tuning` `STT/TTS Integration` `REST API` `WebSocket` `Dataset Preparation` `Model Evaluation`

---

## 📄 Documentation

- 📝 Full detailed report: [`Work_Activity_Report.docx`](./Work_Activity_Report.docx)

---

## 👤 Author

**Gopal Rajbhar**  
AI / ML Developer  
[@Gopal-2001](https://github.com/Gopal-2001)
