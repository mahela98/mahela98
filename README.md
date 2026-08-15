<div align="center">
  <h1 align="center">Hi there, I'm <span style="color: #0078D4;">Chandima Mahela Siriwardana</span> 👋</h1>
  
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=20&pause=1200&color=0078D4&center=true&vCenter=true&width=680&lines=AI+Engineer+%26+Solutions+Architect;Cross-Platform+Mobile+Developer+(Flutter+%26+Dart);Multi-Agent+Systems+%26+Azure+AI+Foundry;Microsoft+Agent+Framework+%26+Semantic+Kernel;Secure+Enterprise+System+Design;Python+%7C+Flutter+%7C+.NET+%7C+TypeScript+%7C+Cloud" alt="Typing SVG" />
  </a>

  <p align="center">
    <a href="https://www.linkedin.com/in/chandima-mahela-siriwardana/" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="mailto:chandimaofficial@gmail.com">
      <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
    <a href="https://github.com/mahela98">
      <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
    </a>
    <img src="https://komarev.com/ghpvc/?username=mahela98&style=for-the-badge&color=0078D4&label=PROFILE+VIEWS" alt="Profile Views" />
  </p>

  <!-- GitHub Profile Trophies -->
  <p align="center">
    <a href="https://github.com/ryo-ma/github-profile-trophy">
      <img src="https://github-profile-trophy.vercel.app/?username=mahela98&theme=tokyonight&no-frame=true&no-bg=true&margin-w=4" alt="mahela98's trophies" />
    </a>
  </p>
</div>

---

### 🚀 About Me

Hey there! 👋 I'm an **AI Engineer & Solutions Architect** with strong foundations in **Cross-Platform Mobile Engineering (Flutter)** and **Enterprise Software Architecture**. I help businesses turn ambitious ideas into secure, high-impact, enterprise-grade AI and mobile systems.

- 🤖 **Agentic AI & Intelligent Systems**: Architecting autonomous multi-agent workflows, tool-augmented copilots, and high-precision RAG systems using **Microsoft Agent Framework**, **Azure AI Foundry**, and **Semantic Kernel**.
- 📱 **Cross-Platform Mobile (Flutter & Dart)**: Crafting fluid, production-ready iOS & Android apps with modern state management (**Riverpod**, **Bloc**), geolocation/maps, push notifications, and offline-first syncing.
- 🛡️ **Secure by Design**: Designing high-availability architectures built on **Zero-Trust principles**, **Threat Modeling**, **OWASP LLM Security**, and enterprise RBAC/Auth0.
- ⚡ **Full-Stack & Distributed Backends**: Deep hands-on experience across **Python (FastAPI)**, **.NET 8 / C#**, and **React / Next.js** to deliver rock-solid production platforms.
- 🔌 **Agentic Tooling & MCP**: Building custom **Model Context Protocol (MCP)** servers to bridge AI agents with native mobile emulators and real-world tools.

---

### 🏛️ Core Architectural & Engineering Pillars

<table>
  <tr>
    <td width="33%" valign="top">
      <h4 align="center">🤖 Agentic AI & RAG</h4>
      <ul>
        <li><b>Microsoft Agent Framework</b> & AutoGen</li>
        <li><b>Azure AI Foundry</b> & Azure OpenAI</li>
        <li><b>Semantic Kernel</b> & LangChain</li>
        <li>Advanced RAG & Vector Indexing</li>
        <li>Model Context Protocol (MCP) Tooling</li>
      </ul>
    </td>
    <td width="33%" valign="top">
      <h4 align="center">📱 Mobile & Edge Engineering</h4>
      <ul>
        <li><b>Flutter & Dart</b> (iOS & Android)</li>
        <li><b>Riverpod & Bloc</b> State Architecture</li>
        <li>Supabase, Firebase Core & Cloud Messaging</li>
        <li>Google Maps API & Geolocation Tracking</li>
        <li>Mobile Screen MCP (Agentic Device Control)</li>
      </ul>
    </td>
    <td width="33%" valign="top">
      <h4 align="center">🛡️ Secure Enterprise Systems</h4>
      <ul>
        <li><b>Zero Trust Architecture</b> & Threat Modeling</li>
        <li><b>Python</b> (FastAPI, SQLAlchemy Async)</li>
        <li><b>.NET 8 / C#</b> (ASP.NET Core, EF Core)</li>
        <li><b>Next.js & React</b> (TypeScript, Tailwind)</li>
        <li>PostgreSQL (pgvector), MSSQL, Docker</li>
      </ul>
    </td>
  </tr>
</table>

---

### 🔍 Interactive System Blueprints & Architecture Deep-Dives

<details>
<summary><b>🤖 Click to expand: Enterprise Multi-Agent & RAG Architecture Blueprint</b></summary>
<br />

```mermaid
flowchart TD
    Client[📱 Client App / Teams Bot] -->|HTTPS + OAuth2 JWT| Gateway[🛡️ Zero-Trust API Gateway & Guardrails]
    Gateway --> Orchestrator[🧠 Semantic Kernel / MS Agent Framework]
    
    subgraph Agentic_Orchestrator [Agentic Multi-Agent System]
        Orchestrator --> Planner[📋 Planner Agent]
        Planner --> RAG[🔍 RAG Agent]
        Planner --> ToolAgent[🔌 Tool / MCP Agent]
        Planner --> Verifier[✅ Guardrail & Verification Agent]
    end

    RAG <--> VectorDB[(🗄️ Azure AI Search / pgvector)]
    ToolAgent <--> ExtAPIs[(⚡ External APIs / Enterprise DB)]
    Verifier -->|Grounded & Sanitized Response| Gateway
    Gateway -->|Streaming Output| Client
```

> **Key Design Highlights**:
> - **Input/Output Sanitization**: OWASP LLM prompt injection defenses and PII masking.
> - **Hybrid Retrieval**: Dense vector embeddings paired with sparse BM25 keyword search.
> - **Multi-Agent Coordination**: Autonomous tool-calling with deterministic fallback loops.
</details>

<details>
<summary><b>📱 Click to expand: Flutter Production State & Clean Architecture Flow</b></summary>
<br />

```mermaid
flowchart LR
    subgraph Presentation_Layer [Presentation Layer]
        UI[📱 Flutter UI Screens] -->|watch / read| Providers[⚡ Riverpod 2.5 StateNotifier]
    end

    subgraph Domain_Layer [Domain & State Layer]
        Providers --> UseCases[⚙️ App Controllers & Business Logic]
    end

    subgraph Data_Layer [Data & Integration Layer]
        UseCases --> Repo[📦 Repository Layer]
        Repo --> Cache[(💾 SQLite / Local Cache)]
        Repo --> Remote[(☁️ Supabase / REST / Firebase)]
    end
```

> **Key Design Highlights**:
> - **Predictable State Flow**: Unidirectional data flow with Riverpod providers and GoRouter routing.
> - **Offline-First Resilience**: Automatic local persistence with background synchronization.
> - **Agentic Device QA**: Automated testing via custom Mobile Screen MCP integration.
</details>

<details>
<summary><b>🛡️ Click to expand: Zero-Trust Security & Identity Blueprint</b></summary>
<br />

```mermaid
flowchart TD
    User([👤 User / Client Request]) -->|1. Authentication Handshake| IdP[🔐 Auth0 / Azure Entra ID]
    IdP -->|2. Issue Signed JWT with Scopes| User
    User -->|3. Request + Bearer Token| Gate[🛡️ API Gateway / Reverse Proxy]
    Gate -->|4. Claims Verification & Rate Limiting| AuthGuard[🔒 RBAC Guard & Policy Engine]
    AuthGuard -->|5. Authorized Execution| Microservice[⚙️ Backend Microservice]
    Microservice -->|6. Encrypted TLS Connection| Database[(🗄️ Encrypted Database & Vector Store)]
```
</details>

---

### 💻 Technologies & Tools

<div align="center">

#### 🤖 AI, Machine Learning & LLMOps
<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Microsoft_Azure_AI_Foundry-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure AI Foundry" />
  <img src="https://img.shields.io/badge/Microsoft_Agent_Framework-0089D6?style=flat-square&logo=microsoft&logoColor=white" alt="Microsoft Agent Framework" />
  <img src="https://img.shields.io/badge/Semantic_Kernel-0078D4?style=flat-square&logo=microsoft&logoColor=white" alt="Semantic Kernel" />
  <img src="https://img.shields.io/badge/OpenAI_/_Azure_OpenAI-412991?style=flat-square&logo=openai&logoColor=white" alt="Azure OpenAI" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/Model_Context_Protocol_(MCP)-101828?style=flat-square&logo=anthropic&logoColor=white" alt="MCP" />
</p>

#### 📱 Mobile Development & Cross-Platform
<p align="center">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter" />
  <img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white" alt="Dart" />
  <img src="https://img.shields.io/badge/Riverpod-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Riverpod" />
  <img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Android" />
  <img src="https://img.shields.io/badge/iOS-000000?style=flat-square&logo=apple&logoColor=white" alt="iOS" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/Firebase_Messaging-FFCA28?style=flat-square&logo=firebase&logoColor=black" alt="Firebase Messaging" />
  <img src="https://img.shields.io/badge/Google_Maps_API-4285F4?style=flat-square&logo=googlemaps&logoColor=white" alt="Google Maps" />
</p>

#### ☁️ Cloud, Security & DevOps
<p align="center">
  <img src="https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Microsoft Azure" />
  <img src="https://img.shields.io/badge/Azure_AI_Search-008AD7?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure AI Search" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Auth0-EB5424?style=flat-square&logo=auth0&logoColor=white" alt="Auth0" />
  <img src="https://img.shields.io/badge/Linux_/_Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white" alt="Linux" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash" />
</p>

#### ⚙️ Backend, Web & Enterprise Languages
<p align="center">
  <img src="https://img.shields.io/badge/.NET_8-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt=".NET" />
  <img src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white" alt="C#" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React.js-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" alt="NestJS" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Material_UI-007FFF?style=flat-square&logo=mui&logoColor=white" alt="Material UI" />
</p>

#### 🗄️ Databases & Vector Storage
<p align="center">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Microsoft_SQL_Server-CC292B?style=flat-square&logo=microsoftsqlserver&logoColor=white" alt="MSSQL" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/Firebase_Firestore-FFCA28?style=flat-square&logo=firebase&logoColor=black" alt="Firestore" />
</p>

</div>

---

### 📂 Featured Solutions & Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🤖 Transporter Mini — AI Fleet & Route Optimization</h4>
      <p>AI-powered corporate transport management system with automated agent booking, intelligent route planning, and MS Teams integration.</p>
      <p>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
        <img src="https://img.shields.io/badge/Azure_OpenAI-412991?style=flat-square&logo=openai&logoColor=white" alt="Azure OpenAI" />
        <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="Postgres" />
      </p>
      <ul>
        <li>Async SQLAlchemy 2.0 backend with Redis caching</li>
        <li>Conversational transport booking bot for MS Teams</li>
        <li>React 18 + TypeScript + Vite responsive dashboard</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>📱 Yakadaweda — Commercial Steel & Materials Platform</h4>
      <p>Production cross-platform mobile marketplace connecting customers and suppliers across Sri Lanka with realtime tracking.</p>
      <p>
        <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter" />
        <img src="https://img.shields.io/badge/Riverpod-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Riverpod" />
        <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase" />
        <img src="https://img.shields.io/badge/Google_Maps-4285F4?style=flat-square&logo=googlemaps&logoColor=white" alt="Google Maps" />
      </p>
      <ul>
        <li>Reactive state architecture powered by Flutter Riverpod 2.5</li>
        <li>Integrated Google Maps geolocation & live supplier discovery</li>
        <li>Supabase Postgres BaaS + Firebase Push Notifications</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🔌 Mobile Screen MCP — Agentic Mobile Automation</h4>
      <p>Model Context Protocol server enabling LLM agents to autonomously inspect, tap, type, and navigate booted iOS & Android emulators.</p>
      <p>
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
        <img src="https://img.shields.io/badge/MCP-101828?style=flat-square&logo=anthropic&logoColor=white" alt="MCP" />
        <img src="https://img.shields.io/badge/iOS_Simulator-000000?style=flat-square&logo=apple&logoColor=white" alt="iOS" />
        <img src="https://img.shields.io/badge/Android_Emulator-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Android" />
      </p>
      <ul>
        <li>Local screenshot capture & coordinate-based tap execution</li>
        <li>Automated agent-driven mobile QA and UX flows</li>
        <li>Cross-platform support for macOS Simulators and ADB devices</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🏢 <a href="https://github.com/mahela98/EMVS-Employee-Management-Visualization-System-Readme">EMVS — Enterprise Management & Visualization</a></h4>
      <p>Enterprise management platform built with modern architectural patterns, interactive analytics, and robust security.</p>
      <p>
        <img src="https://img.shields.io/badge/.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt=".NET" />
        <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
        <img src="https://img.shields.io/badge/MSSQL-CC292B?style=flat-square&logo=microsoftsqlserver&logoColor=white" alt="MSSQL" />
        <img src="https://img.shields.io/badge/Auth0-EB5424?style=flat-square&logo=auth0&logoColor=white" alt="Auth0" />
      </p>
      <ul>
        <li>OData REST APIs with Entity Framework Core & MSSQL</li>
        <li>Secure JWT & Auth0 enterprise authentication</li>
        <li>Material UI v5 & Chart.js data analytics visualization</li>
      </ul>
    </td>
  </tr>
</table>

---

### 🐍 Contribution Activity

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mahela98/mahela98/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/mahela98/mahela98/output/github-contribution-grid-snake.svg">
    <img alt="github contribution grid snake" src="https://raw.githubusercontent.com/mahela98/mahela98/output/github-contribution-grid-snake.svg" />
  </picture>
</div>

---

### 📊 GitHub Analytics

<div align="center">
  <p align="center">
    <img src="https://github-readme-stats.vercel.app/api?username=mahela98&show_icons=true&theme=tokyonight&count_private=true&include_all_commits=true&hide_border=true" alt="mahela98's GitHub Stats" />
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=mahela98&theme=tokyonight&hide_border=true" alt="mahela98's GitHub Streak" />
  </p>
  <p align="center">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mahela98&layout=compact&langs_count=8&theme=tokyonight&hide_border=true" alt="mahela98's Top Languages" />
  </p>
</div>

---

### 🤝 Let's Connect & Collaborate

<div align="center">
  <p>Always open to discussing <b>AI Solution Architecture</b>, <b>Mobile App Development (Flutter)</b>, or <b>Secure Enterprise Systems</b>.</p>
  <p>
    <a href="https://www.linkedin.com/in/chandima-mahela-siriwardana/" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-Connect%20on%20LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    &nbsp;
    <a href="mailto:chandimaofficial@gmail.com">
      <img src="https://img.shields.io/badge/Email-chandimaofficial%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
  </p>
</div>
