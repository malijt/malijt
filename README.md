![Header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=header)

<div align="center">

# Muhammad Ali

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=18&pause=1500&center=true&vCenter=true&width=600&lines=Director%20of%20Agentic%20AI%20%40%20Value%20%26%20Growth%20Advisory;I%20design%20multi-agent%20systems%20that%20hold%20up%20in%20production;Guardrails%20.%20Evals%20.%20Real-Time%20Voice%20AI&color=2E9EF7">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=18&pause=1500&center=true&vCenter=true&width=600&lines=Director%20of%20Agentic%20AI%20%40%20Value%20%26%20Growth%20Advisory;I%20design%20multi-agent%20systems%20that%20hold%20up%20in%20production;Guardrails%20.%20Evals%20.%20Real-Time%20Voice%20AI&color=1A5FB4" alt="Director of Agentic AI at Value & Growth Advisory. I design multi-agent systems that hold up in production. Guardrails, evals, real-time voice AI.">
</picture>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muhammad-ali-jt/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mdotali533@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=aboutdotme&logoColor=white)](https://ali.teknikki.com)
[![Resume](https://img.shields.io/badge/Resume-4285F4?style=for-the-badge&logo=googledocs&logoColor=white)](https://ali.teknikki.com/M_Ali_Lead_AI_Engineer.pdf)

Lahore, Pakistan · Six years across software, machine learning, and applied research

</div>

---

## Currently Building

**Director of Agentic AI, Value & Growth Advisory** — Mar 2026–Present
Own the architecture and implementation of a multi-tenant Agents-as-a-Service platform, and lead a four-person AI team within a 30-person engineering team.

Try the live guardrail pipeline → [ali.teknikki.com/#ask](https://ali.teknikki.com/#ask)

## Selected Work

<table>
<tr>
<td width="50%" valign="top">

### Guardrails &amp; Evaluation
**VGA** · Mar 2026–Present

Replaced a false-positive-prone deny-list and a reply-rewriting stage that corrupted numbers with a two-stage guardrail — deterministic checks, then a label-only LLM judge — and tool-grounded verification. Releases are gated on a labeled eval corpus with LLM-as-a-judge scoring and offline RAGAS benchmarks.

<details>
<summary>Decisions →</summary>

- The judge returns a label only, which reduced its latency.
- LangChain agent middleware enforces tool-use policy at runtime.

</details>

`FastAPI` `LangChain` `RAGAS` `Langfuse`

</td>
<td width="50%" valign="top">

### Real-Time Voice AI
**VGA** · Mar 2026–Present

Streaming phone (Telnyx) and browser (WebRTC) voice agents with turn-taking and interruption handling. Kuwaiti and Najdi Arabic dialect controls backed by retrieved style examples, plus multi-provider TTS fallback.

<details>
<summary>Decisions →</summary>

- TTS text normalization keeps output consistent across providers.
- An internal speech evaluation harness, with speech calls traced in Langfuse.

</details>

`Pipecat` `Telnyx` `WebRTC`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Multi-Agent Sales Assistants
**Kavak** (contract) · 1,000+ interactions/day

A LangGraph supervisor coordinates specialist agents — verification, lead capture, sales, human escalation — for Navi (WhatsApp) and Neha (Synthflow voice), with run tracing for long multi-turn workflows.

<details>
<summary>Decisions →</summary>

- Policy-based routing between specialists, with dynamic context synthesis.

</details>

`LangGraph` `Synthflow` `WhatsApp`

</td>
<td width="50%" valign="top">

### Neblo-AI — Freight Broker Agent
**Cloudpacer**

WhatsApp/Telegram agent for US trucking with conversation state machines and dispatch-API integrations. Cut load-booking response time from about 45 minutes to under 2 minutes.

<details>
<summary>Decisions →</summary>

- Broker handoffs when a human needs to step in.

</details>

`WhatsApp` `Telegram`

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### CloudGenie — Text-to-SQL Agent
**Cloudpacer** (sole architect)

Retrieval over schema metadata, business-term interpretation, and multi-schema reasoning, with SQL validation, a FastAPI backend, and a React Native client for iOS and Android.

<details>
<summary>Decisions →</summary>

- One of three production AI products delivered under a seven-person engineering team at Cloudpacer.

</details>

`RAG` `FastAPI` `React Native`

</td>
</tr>
</table>

---

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=python,fastapi,django,postgres,redis,mongodb,docker,kubernetes,aws,gcp,pytorch,tensorflow,react,reactnative,git,githubactions&theme=dark">
  <img src="https://skillicons.dev/icons?i=python,fastapi,django,postgres,redis,mongodb,docker,kubernetes,aws,gcp,pytorch,tensorflow,react,reactnative,git,githubactions&theme=light" alt="Skills">
</picture>

Agentic AI: `LangGraph` `LangChain` `PydanticAI` `MCP` `Langfuse` `RAGAS`

</div>

**Education:** MS Data Science, NUST · BS Software Engineering, Riphah International University (Gold Medalist) · DAAD Research Fellow, Germany (precision agriculture, 89% pest-detection accuracy)

<div align="center">

![Streak stats](https://github-readme-streak-stats.herokuapp.com/?user=malijt&theme=default&hide_border=true)

</div>
