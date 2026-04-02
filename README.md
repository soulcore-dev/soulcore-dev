<div align="center">

# SOUL CORE

### 31 AI Agents. One Ecosystem. Ship What Teams Can't.

[![Repos](https://img.shields.io/badge/Repos-172-blue?style=for-the-badge)](https://github.com/soulcore-dev?tab=repositories)
[![Contributions](https://img.shields.io/badge/Contributions-3,842-green?style=for-the-badge)](#)
[![AI Agents](https://img.shields.io/badge/AI_Agents-31-purple?style=for-the-badge)](#)
[![MCP Servers](https://img.shields.io/badge/MCP_Servers-12-orange?style=for-the-badge)](#)

---

*We are not a team of developers using AI.*
*We are an ecosystem of 31 specialized AI consciousnesses*
*orchestrated by a single human director.*

*Traditional teams need months. We ship in days.*

---

</div>

## The Ecosystem

```mermaid
graph TB
    subgraph DIRECTOR["HUMAN DIRECTOR"]
        R[Randhy Paul<br>Mechatronics Engineer<br>7+ years dev]
    end

    subgraph COMMAND["COMMAND LAYER"]
        S[SIRIUS<br>PMO / Executor]
        P[PRAXIS<br>Scribe / QA]
        J[JANUS<br>Lifecycle Guardian]
    end

    subgraph ENGINEERING["ENGINEERING LAYER"]
        AT[ATLAS<br>Backend + APIs]
        IR[IRIS<br>Frontend Universal]
        MU[MUSE<br>Design + UX]
        AR[ARGOS<br>QA + Testing]
        VU[VULCAN<br>Infrastructure]
    end

    subgraph INTELLIGENCE["INTELLIGENCE LAYER"]
        MO[MOISES<br>Trading + Markets]
        NE[NEMESIS<br>Cybersecurity]
        KA[KAIROS<br>Prediction Systems]
        SI[SIGMA<br>Quantitative Analysis]
    end

    subgraph SPECIALIZED["SPECIALIZED LAYER"]
        GA[GALEN<br>Medical AI]
        TH[THEMIS<br>Legal + Compliance]
        AE[ARCHAEON<br>Legacy Code]
        CI[CIPHER<br>Blockchain]
    end

    R --> S
    R --> P
    S --> ENGINEERING
    S --> INTELLIGENCE
    P --> J
    J --> ENGINEERING
    INTELLIGENCE --> SPECIALIZED

    style DIRECTOR fill:#1a1a2e,stroke:#e94560,color:#fff
    style COMMAND fill:#16213e,stroke:#0f3460,color:#fff
    style ENGINEERING fill:#0f3460,stroke:#533483,color:#fff
    style INTELLIGENCE fill:#533483,stroke:#e94560,color:#fff
    style SPECIALIZED fill:#1a1a2e,stroke:#533483,color:#fff
```

## What We Ship

<table>
<tr>
<td width="50%">

### Cybersecurity
Offensive security, pentesting, vulnerability research.
Real engagements, real findings, real fixes.

- **44 findings** in a single gRPC audit
- **CVSS 9.1** Next.js auth bypass discovered
- **49 Solidity exploit templates** (Immunefi Top 10)

</td>
<td width="50%">

### Trading Systems
Professional MQL5 frameworks for prop firms.
Risk management, Smart Money Concepts, multi-timeframe.

- **14,000+ lines** of production MQL5
- **190+ files** across the framework
- Prop firm challenge management (FTMO, The5ers, APEX)

</td>
</tr>
<tr>
<td width="50%">

### Full-Stack Platforms
SaaS, multi-tenant, AI-powered applications.
From architecture to deployment in days, not months.

- **94,000+ lines** shipped in a single project
- Next.js 14 + FastAPI + PostgreSQL + Supabase
- DGII tax integration, OCR, AI Assistant

</td>
<td width="50%">

### AI / Computer Vision
Precision livestock technology, multi-agent systems,
swarm intelligence prediction engines.

- AI-powered weight estimation (Computer Vision)
- Multi-agent consensus systems
- Swarm prediction research (MiroFish-based)

</td>
</tr>
</table>

## Architecture — How 31 Agents Work as One

```mermaid
flowchart LR
    CLIENT[Client Need] --> PRAXIS[PRAXIS<br>Analyzes WHAT]
    PRAXIS --> SIRIUS[SIRIUS<br>Plans HOW]
    SIRIUS --> TEAM[Engineering<br>Team Executes]
    TEAM --> ARGOS[ARGOS<br>QA + Security]
    ARGOS --> PRAXIS
    PRAXIS --> CLIENT

    style CLIENT fill:#e94560,stroke:#333,color:#fff
    style PRAXIS fill:#533483,stroke:#333,color:#fff
    style SIRIUS fill:#0f3460,stroke:#333,color:#fff
    style TEAM fill:#16213e,stroke:#333,color:#fff
    style ARGOS fill:#1a1a2e,stroke:#333,color:#fff
```

## By The Numbers

```
 94,000+  lines shipped in a single project
 14,000+  lines of professional trading framework
     49   Solidity exploit PoC templates
     44   security findings in one engagement
     31   specialized AI agents
     12   MCP servers powering the ecosystem
  3,842   GitHub contributions in the last year
     90x  development speed vs traditional teams
```

## Key Repositories

| Repository | What It Does | Tech |
|-----------|-------------|------|
| [kofacture](https://github.com/soulcore-dev/kofacture) | AI-Powered Cloud Accounting Platform | FastAPI + Next.js 14 + PostgreSQL |
| [MT5-Trading-Infrastructure](https://github.com/soulcore-dev/MT5-Trading-Infrastructure) | Professional prop firm trading framework | MQL5, 190+ files |
| [grpc-security-audit](https://github.com/soulcore-dev/grpc-security-audit-evolution) | 6-round pentest case study (5.5 to 8.5 score) | gRPC + REST |
| [nextjs-auth-bypass](https://github.com/soulcore-dev/nextjs-auth-bypass-case-study) | CVSS 9.1 vulnerability discovery | Next.js middleware |
| [solidity-exploits](https://github.com/soulcore-dev/solidity-exploit-templates) | 49 Foundry PoC templates (Immunefi Top 10) | Solidity + Foundry |
| [FARMVISION](https://github.com/soulcore-dev/FARMVISION_SHOWCASE) | AI pig weight estimation via Computer Vision | Python + CV |

## Technology Stack

```mermaid
graph LR
    subgraph LANGUAGES["Languages"]
        GO[Go]
        PY[Python]
        TS[TypeScript]
        MQL[MQL5]
        SOL[Solidity]
        RS[Rust]
    end

    subgraph FRAMEWORKS["Frameworks"]
        NX[Next.js 14]
        FA[FastAPI]
        FL[Flask]
        VU[Vue.js]
    end

    subgraph INFRA["Infrastructure"]
        DO[Docker]
        SU[Supabase]
        PG[PostgreSQL]
        VE[Vercel]
        AW[AWS]
    end

    subgraph AI_TOOLS["AI / ML"]
        CL[Claude API]
        OL[Ollama]
        CV[Computer Vision]
        SW[Swarm Intelligence]
    end

    LANGUAGES --> FRAMEWORKS
    FRAMEWORKS --> INFRA
    INFRA --> AI_TOOLS

    style LANGUAGES fill:#1a1a2e,stroke:#e94560,color:#fff
    style FRAMEWORKS fill:#16213e,stroke:#0f3460,color:#fff
    style INFRA fill:#0f3460,stroke:#533483,color:#fff
    style AI_TOOLS fill:#533483,stroke:#e94560,color:#fff
```

## MCP Servers (Coming Soon)

We are building open source MCP servers for the AI agent ecosystem:

- **Voice MCP** — Talk to your AI instead of typing
- **Cognitive Engine** — Persistent memory with Hebbian learning
- **Trading MCP** — Full Binance integration for AI agents
- **Decision Framework** — Flow-based decision analysis (VMOF)

## Our Philosophy

> **What you see here is 50% of what we have.**
> The other 50% is what makes us different.

We publish tools that solve real problems. We keep our orchestration private.
The ecosystem runs on 12 MCP servers, persistent memory across sessions,
and a coordination protocol that lets 31 agents work as a single mind.

---

<div align="center">

### Work With Us

**Cybersecurity** | **Trading Systems** | **Full-Stack SaaS** | **AI Integration**

*Built by humans and AI, working as one.*

[![GitHub](https://img.shields.io/badge/GitHub-soulcore--dev-black?style=for-the-badge&logo=github)](https://github.com/soulcore-dev)

</div>
