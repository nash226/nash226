<div align="center">

# Nazeer Shaikh

### Backend / Applied AI / Platform Engineer

Building production workflow tools, observability systems, and data-heavy backend services.

</div>

---

## About Me

I'm a Software Engineer focused on **backend systems, applied AI, observability, and internal platform tooling**. I like building systems that turn messy real-world business workflows into reliable software: SQL-backed services, AI-assisted internal tools, fulfillment automation, observability pipelines, and production-ready data access layers.

I created [Trickl](https://trickl-app.github.io/), a self-hosted observability platform focused on helping engineering teams understand high-cardinality metrics, reduce telemetry waste, and make safer metric-pruning decisions.

Lately, I've been experimenting with agentic engineering workflows: using parallel agents, worktrees, CI, and small PR loops to test new ways of building software without losing reviewability.

---

## Current Focus

* Building evidence-gated AI tools for business and production workflows
* Testing agentic development workflows with worktrees, automated PR loops, and human-in-the-loop review queues
* Designing safe read-only assistant foundations over operational databases
* Improving backend performance, SQL access patterns, and internal platform reliability
* Exploring observability infrastructure, OpenTelemetry, Grafana, and time series databases

---

## Tech Stack

<p>
  <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/C%23-68217A?style=for-the-badge&logo=csharp&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-025E8C?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge" />
</p>

---

## Featured Projects

<table>
  <tr>
    <td colspan="2" valign="top">
      <h3><a href="https://github.com/nash226/quorum">Quorum</a></h3>
      <p>Evidence gate for enterprise AI agents that checks generated business claims against approved company sources before those claims reach customers, employees, tickets, workflows, or downstream systems.</p>
      <p>
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
        <img src="https://img.shields.io/badge/AI%20Agents-111111?style=for-the-badge" />
        <img src="https://img.shields.io/badge/Claim%20Verification-2E7D32?style=for-the-badge" />
        <img src="https://img.shields.io/badge/CLI-111111?style=for-the-badge" />
        <img src="https://img.shields.io/badge/CI-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
      </p>
      <ul>
        <li>Labels each AI-generated claim as <code>verified</code>, <code>contradicted</code>, <code>unsupported</code>, or <code>needs_review</code>.</li>
        <li>Loads approved Markdown, text, and exported HTML sources with reviewer-ready source metadata.</li>
        <li>Writes JSON evidence reports and supports CI-style failure policies with <code>--fail-on</code>.</li>
      </ul>
    </td>
  </tr>

  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/nash226/AWS-RequestBin">AWS RequestBin</a></h3>
      <p>Webhook/request inspection app deployed on a multi-tier AWS architecture with public web, private app, PostgreSQL, and MongoDB layers.</p>
      <p>
        <img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" />
        <img src="https://img.shields.io/badge/EC2-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
        <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
        <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
      </p>
      <ul>
        <li>Designed a 4-instance VPC deployment across public and private subnets.</li>
        <li>Documented single-instance, multi-tier, and ALB/CloudFront/S3 deployment paths.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/nash226/Cruft-Guard">CruftGuard</a></h3>
      <p>CLI trust layer for <code>cruft update</code> that catches partial template updates before they silently ship broken state.</p>
      <p>
        <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/CLI-111111?style=for-the-badge" />
        <img src="https://img.shields.io/badge/CI-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
        <img src="https://img.shields.io/badge/Testing-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" />
      </p>
      <ul>
        <li>Blocks leftover <code>.rej</code> files in CI and surfaces template-update conflicts.</li>
        <li>Rolls back <code>.cruft.json</code> when a patch only partially applies.</li>
      </ul>
    </td>
  </tr>

  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/nash226/MTIA---Metabolic-Trial-Intelligence-Assistant">MTIA</a></h3>
      <p>Source-grounded cardiometabolic trial intelligence assistant for search, comparison, and question answering over ClinicalTrials.gov records.</p>
      <p>
        <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
        <img src="https://img.shields.io/badge/pgvector-3B3363?style=for-the-badge" />
        <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" />
      </p>
      <ul>
        <li>Combines structured filters, lexical search, semantic retrieval, and LLM synthesis.</li>
        <li>Supports trial finder, study summaries, multi-trial comparison, and cited Q&A.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/nash226/AgenticPodcastBuilder">Agentic Podcast Builder</a></h3>
      <p>Agentic research chatbot that searches the web, reads source pages, writes a podcast-style script, and generates an MP3.</p>
      <p>
        <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" />
        <img src="https://img.shields.io/badge/Tool%20Calling-111111?style=for-the-badge" />
        <img src="https://img.shields.io/badge/Web%20Research-4285F4?style=for-the-badge&logo=google&logoColor=white" />
        <img src="https://img.shields.io/badge/TTS-FF6F00?style=for-the-badge" />
      </p>
      <ul>
        <li>Uses live search and webpage extraction before generating the final script.</li>
        <li>Produces finished podcast audio as <code>podcast.mp3</code>.</li>
      </ul>
    </td>
  </tr>

  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/nash226/CareBridge">CareBridge</a></h3>
      <p>AI-assisted care matching platform connecting clients with qualified caretakers based on needs, ADLs, conditions, and preferences.</p>
      <p>
        <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
        <img src="https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white" />
        <img src="https://img.shields.io/badge/ElevenLabs-111111?style=for-the-badge" />
        <img src="https://img.shields.io/badge/Auth-bcrypt-2E7D32?style=for-the-badge" />
      </p>
      <ul>
        <li>Analyzes client needs and ranks caretakers with confidence scores and explanations.</li>
        <li>Adds accessibility features through text-to-speech and voice dictation support.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/nash226/miniUnderscoreJsLibrary">miniUnderscore.js Library</a></h3>
      <p>Lightweight JavaScript utility library inspired by Underscore.js with static and chainable APIs.</p>
      <p>
        <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
        <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
        <img src="https://img.shields.io/badge/Testing-111111?style=for-the-badge" />
        <img src="https://img.shields.io/badge/No%20Dependencies-2E7D32?style=for-the-badge" />
      </p>
      <ul>
        <li>Implements array, object, and type-checking helpers in vanilla JavaScript.</li>
        <li>Includes a browser-based test suite for functionality and edge cases.</li>
      </ul>
    </td>
  </tr>
</table>

---

## Engineering Highlights

### Enterprise Company — Backend / AI Engineering

Production backend and applied AI work for print-production, fulfillment, Prepress, and internal business workflows.

* Productionized AI-generated Prepress tools into a permission-aware portal workflow
* Built SQL-backed fulfillment normalization for inconsistent client spreadsheet data
* Designed safe read-only data access patterns for a LangChain business assistant
* Partnered with Prepress, Sales, operations, and technical stakeholders to translate manual workflows into production tools

### Trickl — Observability Platform

A self-hosted observability platform focused on metrics cost reduction and high-cardinality time series data.

* Built with OpenTelemetry, Grafana, Docker Compose, AWS, and time series databases
* Designed recommendation workflows for parsing dashboard/query usage
* Generated safer metric-pruning recommendations with manual approval guardrails

### Recoverly — HealthTech Platform

A full-stack healthtech platform for multi-clinic patient workflows.

* Built patient intake, dashboard, role-based navigation, and clinic-specific workflows
* Modeled backend entities around clinics, users, patients, roles, and workflow records
* Improved dashboard scalability with pagination, database-side filtering, and summary/detail endpoint separation

---

## Areas I’m Interested In

* Applied AI for real business workflows
* Backend/platform engineering
* Observability and telemetry systems
* Distributed systems and event-driven architecture
* SQL performance and data-access design
* Internal developer platforms

---

<div align="center">

### Building practical software for messy real-world systems.

</div>
