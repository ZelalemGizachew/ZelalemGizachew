<!--
  ZG / ENGINEERING OS
  A hand-built GitHub profile. Visual assets live in ./assets.
  Public-facing status information is descriptive, not live telemetry.
-->

<div align="center">

<img src="./assets/profile-hero.svg" width="100%" alt="ZG Engineering OS — Zelalem Gizachew. Software Engineer, fintech, backend, Android and realtime voice AI." />

<br/>

<a href="https://zenonymous.lovable.app/"><img src="https://img.shields.io/badge/◈_PORTFOLIO-0C1727?style=for-the-badge&amp;labelColor=0C1727&amp;color=26657E" alt="Portfolio" /></a>
<a href="https://www.linkedin.com/in/zelalem-gizachew-28012a230/"><img src="https://img.shields.io/badge/◈_LINKEDIN-0C1727?style=for-the-badge&amp;labelColor=0C1727&amp;color=26657E" alt="LinkedIn" /></a>
<a href="https://shagiz-technologies.github.io/"><img src="https://img.shields.io/badge/◈_SHAGIZ_TECHNOLOGIES-0C1727?style=for-the-badge&amp;labelColor=0C1727&amp;color=247E75" alt="Shagiz Technologies website" /></a>
<a href="mailto:zelalemgizachew890@gmail.com"><img src="https://img.shields.io/badge/◈_CONTACT-0C1727?style=for-the-badge&amp;labelColor=0C1727&amp;color=247E75" alt="Email" /></a>

<br/><br/>

**The systems should be interesting. Their failure modes should be boring.**

<sub>SOFTWARE ENGINEER · SAFARICOM ETHIOPIA · ADDIS ABABA, ETHIOPIA</sub>

</div>

---

### \`00 / boot_sequence\`

~~~console
$ ssh zelalem@engineering-os
Authenticating... [human]
Loading engineering profile...

IDENTITY     Zelalem Gizachew
ROLE         Software Engineer
DOMAIN       Backend Engineering / Fintech / Realtime AI / Android
LOCATION     Addis Ababa, Ethiopia
MODE         BUILD  →  SHIP  →  BREAK  →  HARDEN  →  OPEN SOURCE

> Welcome to the part of the internet where failure paths are first-class features.
~~~

I work on **fintech and digital-channel engineering at Safaricom Ethiopia**. Outside my day job, I build products, developer tooling, and open-source integrations. I gravitate toward the problems that appear *after* the happy-path demo: concurrency, retries, state reconciliation, unreliable networks, latency, and observability.

My engineering interests span backend platforms, payment APIs, Android systems, and low-latency voice agents. **The connecting principle is operational reliability.**

### \`01 / mission_registry\`

<img src="./assets/mission-registry.svg" width="100%" alt="Visual mission registry showing TeleVault, AddisAI LiveKit, M-Pesa SDKs, and Vireon with their current public or private project statuses." />

<table>
<tr>
<td width="50%" valign="top">

#### <a href="https://github.com/Shagiz-Technologies/televault">A01 / TELEVAULT ↗</a>

**Storage and privacy infrastructure disguised as an Android media app.**

Public, open-source Android backup manager and encrypted vault built around user-controlled Telegram storage.

- TDLib integration and resilient background uploads
- Sync state and crash recovery
- Retry / flood-wait handling and Android WorkManager
- Streaming AES-256-GCM encrypted vault containers
- Release hardening, privacy and CI workflows

<sub><code>Flutter</code> · <code>Kotlin</code> · <code>TDLib</code> · <code>Drift/SQLite</code></sub>

**[Explore source →](https://github.com/Shagiz-Technologies/televault)**

</td>
<td width="50%" valign="top">

#### A02 / ADDISAI × LIVEKIT

**African-language speech integrations for realtime AI agents.**

Proposed upstream STT/TTS provider plugins for **Amharic** and **Afaan Oromo** in two LiveKit ecosystems.

- Asynchronous provider requests and error mapping
- Retry-safe, idempotent speech generation flows
- Tests, documentation, and agent examples
- Python and TypeScript implementations

<sub><code>LiveKit Agents</code> · <code>Python</code> · <code>TypeScript</code> · <code>STT/TTS</code></sub>

**[Python PR #6601 →](https://github.com/livekit/agents/pull/6601)** · **[Node.js PR #2160 →](https://github.com/livekit/agents-js/pull/2160)**

<sub>Both upstream pull requests are currently open, not merged.</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### A03 / M-PESA SDK SUITE

**Payment integrations should have predictable developer contracts.**

Public client projects exploring API authentication, transaction requests, callbacks, and error handling across languages.

**[Java](https://github.com/ZelalemGizachew/mpesa-java-sdk)** · **[Python](https://github.com/ZelalemGizachew/mpesa-python-sdk)** · **[Go](https://github.com/ZelalemGizachew/mpesa-go-sdk)** · **[Node.js](https://github.com/ZelalemGizachew/mpesa-node-js-sdk)** · **[PHP](https://github.com/ZelalemGizachew/mpesa-php-sdk)**

<sub><code>Payments</code> · <code>API clients</code> · <code>Authentication</code> · <code>Developer tooling</code></sub>

</td>
<td width="50%" valign="top">

#### A04 / VIREON

**A personal planning system designed as an operating environment.**

An Android-first productivity project built around deterministic daily plans rather than infinite, mutable to-do lists.

- Frozen daily plans and routine-generated tasks
- Timed reminders and native Android notification HUDs
- Local-first state and weekly performance reviews
- Mechanical, science-fiction-inspired UI

<sub><code>Flutter</code> · <code>Dart</code> · <code>Kotlin</code> · <code>Android</code></sub>

<sub>Private development. No public source link yet.</sub>

</td>
</tr>
</table>

### \`02 / experimental_lab\`

**[Spring Documentation MCP Server →](https://github.com/ZelalemGizachew/spring-documentation-mcp-server)**

A separate **educational, AI-assisted experiment** in documentation-aware developer tools: Spring AI, MCP interfaces, PostgreSQL full-text search, pgvector semantic retrieval, and documentation synchronization.

<sub>This is not an official Spring project. The repository documents its AI-assisted code authorship.</sub>

### \`03 / system_topology\`

<img src="./assets/engineering-map.svg" width="100%" alt="Futuristic conceptual topology: backend systems, Android clients, payment APIs, and voice AI connected by reliability principles." />

<details>
<summary><b>Expand: what I optimize for</b></summary>

<br/>

| Engineering surface | The questions worth asking |
|:--|:--|
| **Distributed state** | What happens if two actors update the same thing? |
| **Failure recovery** | Can we safely resume after a timeout or crash? |
| **Payment integrations** | Is every external action identifiable and idempotent? |
| **Observability** | Can we explain *why* a transaction failed without guessing? |
| **Realtime voice** | Where is the latency budget spent, and how do interruptions behave? |
| **Android** | What survives process death, bad connectivity, and background limits? |

</details>

### \`04 / runtime_dependencies\`

<div align="center">

<img src="https://img.shields.io/badge/Java-0E1B2B?style=flat-square&amp;logo=openjdk&amp;logoColor=F5A05B" alt="Java" />
<img src="https://img.shields.io/badge/Spring_Boot-0E1B2B?style=flat-square&amp;logo=springboot&amp;logoColor=7DCF79" alt="Spring Boot" />
<img src="https://img.shields.io/badge/Python-0E1B2B?style=flat-square&amp;logo=python&amp;logoColor=82BFF4" alt="Python" />
<img src="https://img.shields.io/badge/FastAPI-0E1B2B?style=flat-square&amp;logo=fastapi&amp;logoColor=73DDC5" alt="FastAPI" />
<img src="https://img.shields.io/badge/PostgreSQL-0E1B2B?style=flat-square&amp;logo=postgresql&amp;logoColor=7EB5E6" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/Docker-0E1B2B?style=flat-square&amp;logo=docker&amp;logoColor=59B7FF" alt="Docker" />

<img src="https://img.shields.io/badge/Flutter-0E1B2B?style=flat-square&amp;logo=flutter&amp;logoColor=68D4FC" alt="Flutter" />
<img src="https://img.shields.io/badge/Kotlin-0E1B2B?style=flat-square&amp;logo=kotlin&amp;logoColor=AD9AFF" alt="Kotlin" />
<img src="https://img.shields.io/badge/TypeScript-0E1B2B?style=flat-square&amp;logo=typescript&amp;logoColor=78B0FB" alt="TypeScript" />
<img src="https://img.shields.io/badge/LiveKit-0E1B2B?style=flat-square&amp;logoColor=8FFBD1" alt="LiveKit" />
<img src="https://img.shields.io/badge/Redis-0E1B2B?style=flat-square&amp;logo=redis&amp;logoColor=FF7A7A" alt="Redis" />
<img src="https://img.shields.io/badge/Linux-0E1B2B?style=flat-square&amp;logo=linux&amp;logoColor=FFDA84" alt="Linux" />

</div>

### \`05 / operating_principles\`

~~~rust
// Engineering axioms. Not executable Rust.

const ASSUME_FAILURE: bool = true;
const MAKE_STATE_EXPLICIT: bool = true;
const OBSERVABILITY_IS_A_FEATURE: bool = true;

// Network call ≠ transaction.
// Retry ≠ repeat blindly.
// Shipped ≠ finished.
// Complexity belongs inside the system,
// not in the user's experience.
~~~

**I like software that is difficult to build well, but easy for someone else to depend on.**

### \`06 / open_channels\`

I’m interested in technical collaboration and international opportunities in **backend/platform engineering, fintech infrastructure, developer tools, and realtime voice/AI**.

<div align="center">

**[Portfolio](https://zenonymous.lovable.app/)** &nbsp; / &nbsp; **[Shagiz Technologies](https://shagiz-technologies.github.io/)** &nbsp; / &nbsp; **[LinkedIn](https://www.linkedin.com/in/zelalem-gizachew-28012a230/)** &nbsp; / &nbsp; **[Email](mailto:zelalemgizachew890@gmail.com)**

<sub>ZG / ENGINEERING OS · SYSTEMS OVER HYPE · SIGNAL OVER NOISE</sub>

</div>
