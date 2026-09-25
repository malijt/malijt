# Muhammad Ali

Director of Agentic AI at Value & Growth Advisory. I design and build multi-agent systems that hold up in production. Six years across software, machine learning, and applied research.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muhammad-ali-jt/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mdotali533@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=aboutdotme&logoColor=white)](https://ali.teknikki.com)
[![Resume](https://img.shields.io/badge/Resume-4285F4?style=for-the-badge&logo=googledocs&logoColor=white)](https://ali.teknikki.com/M_Ali_Lead_AI_Engineer.pdf)

Lahore, Pakistan

---

## Currently Building

**Director of Agentic AI, Value & Growth Advisory** — Mar 2026–Present
Own the architecture and implementation of a multi-tenant Agents-as-a-Service platform, and lead a four-person AI team within a 30-person engineering team.

Try the live guardrail pipeline → [ali.teknikki.com/#ask](https://ali.teknikki.com/#ask)

## Selected Work

**Guardrails and evaluation for a multi-tenant agent platform** — VGA
Replaced a false-positive-prone deny-list and a reply-rewriting stage that corrupted numbers with a two-stage guardrail (deterministic checks, then a label-only LLM judge) and tool-grounded verification of times, phone numbers, and links. Releases are gated on a labeled evaluation corpus with LLM-as-a-judge scoring and offline RAGAS benchmarks.
*FastAPI · LangChain · RAGAS · Langfuse*

**Real-time voice agents on Pipecat, in Arabic and English** — VGA
Streaming phone (Telnyx) and browser (WebRTC) voice agents with turn-taking and interruption handling; Kuwaiti and Najdi Arabic dialect controls backed by retrieved style examples, and multi-provider TTS fallback.
*Pipecat · Pipecat Flows · Telnyx · WebRTC*

**Multi-agent sales assistants — 1,000+ interactions a day** — Kavak (contract)
A LangGraph supervisor coordinates specialist agents — verification, lead capture, sales, human escalation — for Navi (WhatsApp) and Neha (Synthflow voice), with runtime conversation state and thread/run tracing to diagnose failures in long-running workflows.
*LangGraph · Synthflow · WhatsApp*

**Neblo-AI — freight broker agent** — Cloudpacer
WhatsApp/Telegram agent for US trucking with conversation state machines, broker handoffs, and dispatch-API integrations. Cut load-booking response time from about 45 minutes to under 2 minutes.
*WhatsApp · Telegram · State machines*

**CloudGenie — text-to-SQL agent** — Cloudpacer (sole architect)
Retrieval over schema metadata, business-term interpretation, and multi-schema reasoning, with SQL validation, a FastAPI backend, and a React Native client for iOS and Android.
*RAG · SQL validation · FastAPI · React Native*

---

**Stack:** LangGraph · PydanticAI · MCP · Agent2Agent (A2A) · OpenAI · Anthropic Claude · Gemini · LLM-as-a-judge · pgvector/HNSW · Deepgram · ElevenLabs · Twilio · PostgreSQL · Docker · AWS · GitHub Actions · pytest

**Education:** MS Data Science, NUST · BS Software Engineering, Riphah International University (Gold Medalist) · DAAD Research Fellow, Germany (precision agriculture, 89% pest-detection accuracy)
