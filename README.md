<!-- ===================================================================== -->
<!-- FAJRI ABDURAHMAN GHURRI (FAJRIAG) — EXECUTIVE ENGINEERING PORTFOLIO   -->
<!-- ===================================================================== -->

<div align="center">
  <img src="./assets/hero-banner.svg" width="100%" alt="Fajri Abdurahman Ghurri — Full-Stack Software & AI Systems Engineer" />
  <br/><br/>

  <!-- Primary Action & Contact Badges -->
  <p align="center">
    <a href="mailto:fajriabdurahmanghurri@gmail.com">
      <img src="https://img.shields.io/badge/EMAIL-fajriabdurahmanghurri%40gmail.com-0B1120?style=for-the-badge&logo=gmail&logoColor=38BDF8&labelColor=060911" alt="Email" />
    </a>
    <a href="https://linkedin.com/in/fajri-abdurahman-ghurri/">
      <img src="https://img.shields.io/badge/LINKEDIN-Fajri%20Abdurahman%20Ghurri-0B1120?style=for-the-badge&logo=linkedin&logoColor=38BDF8&labelColor=060911" alt="LinkedIn" />
    </a>
    <a href="https://github.com/FAJRIAG?tab=repositories">
      <img src="https://img.shields.io/badge/REPOSITORIES-66%20Engineered%20Systems-0B1120?style=for-the-badge&logo=github&logoColor=818CF8&labelColor=060911" alt="Repositories" />
    </a>
    <img src="https://img.shields.io/badge/CONTRIBUTIONS-11%2C380%2B%20Commits-0B1120?style=for-the-badge&logo=git&logoColor=10B981&labelColor=060911" alt="Contributions" />
  </p>
</div>

---

## Executive Summary · Ringkasan Eksekutif

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🌐 International Profile (EN)</h4>
      <p>
        <strong>Full-Stack Software &amp; AI Systems Engineer</strong> specializing in the end-to-end architecture, development, and deployment of <strong>scalable enterprise web &amp; mobile applications</strong>, <strong>high-concurrency backend microservices</strong>, and <strong>production Artificial Intelligence pipelines</strong>.
      </p>
      <p>
        Proven track record across <strong>66 software repositories</strong> and <strong>11,380+ code contributions</strong> delivering full-lifecycle products—from modern frontend &amp; mobile interfaces (<em>TypeScript, Next.js, React, Tailwind CSS, Flutter, Swift</em>) and resilient backend cores (<em>Go, Laravel 12, FastAPI, Node.js, PostgreSQL, Redis</em>) to enterprise <strong>LLM/RAG platforms, Computer Vision, and Smart City GIS/IoT ecosystems</strong>.
      </p>
    </td>
    <td width="50%" valign="top">
      <h4>🇮🇩 Profil Eksekutif (ID)</h4>
      <p>
        <strong>Full-Stack Software &amp; AI Systems Engineer</strong> dengan spesialisasi pada perancangan arsitektur, pengembangan, dan deployment <strong>aplikasi web &amp; mobile skala enterprise (Full-Stack)</strong>, <strong>backend berkonkurensi tinggi</strong>, serta <strong>sistem Artificial Intelligence produksi</strong>.
      </p>
      <p>
        Berpengalaman membangun <strong>66 repositori sistem</strong> dengan <strong>11.380+ kontribusi kode</strong> yang mencakup pengembangan end-to-end—mulai dari antarmuka frontend &amp; mobile modern (<em>TypeScript, Next.js, React, Flutter, Swift</em>) dan arsitektur backend tangguh (<em>Go, Laravel 12, FastAPI, Node.js, PostgreSQL, Redis</em>) hingga integrasi <strong>pipeline LLM/RAG, Computer Vision, dan Smart City GIS/IoT</strong>.
      </p>
    </td>
  </tr>
</table>

---

## System Architecture Blueprint

<div align="center">
  <img src="./assets/architecture-overview.svg" width="100%" alt="Production System Architecture Blueprint" />
</div>

<br/>

<details>
  <summary><strong>📐 Interactive End-to-End Production Topology (Mermaid Architecture Diagram) — Click to Expand</strong></summary>
  <br/>

```mermaid
flowchart LR
    subgraph Edge["01 · Client & Edge Layer"]
        A1["Flutter & iOS (Swift) Clients"]
        A2["Next.js / TS & Laravel Blade UI"]
        A3["ESP32 IoT Grid & RTSP Cameras"]
    end

    subgraph Core["02 · API Gateway & Orchestration"]
        B1["Go High-Concurrency Core"]
        B2["FastAPI Async Inference Gateway"]
        B3["Laravel 12 Enterprise Core"]
    end

    subgraph AI["03 · Applied AI & ML Engine"]
        C1["Multi-LLM Router & Hybrid RAG"]
        C2["PyTorch / YOLOv8 / MobileNetV2"]
        C3["Acoustic Phoneme & GIS Analytics"]
    end

    subgraph Data["04 · Distributed Persistence"]
        D1[("PostgreSQL / MySQL")]
        D2[("Vector Index (HNSW)")]
        D3[("Redis Pub/Sub & Cache")]
    end

    A1 & A2 & A3 -->|HTTPS / WSS / MQTT| B1 & B2 & B3
    B1 & B2 & B3 -->|gRPC / Async Queue| C1 & C2 & C3
    B1 & B3 --> D1 & D3
    C1 --> D2
    C2 & C3 --> D1
```
</details>

---

## Core Engineering Domains & Technical Depth

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>1. Full-Stack Web, Enterprise SaaS &amp; Mobile Engineering</h3>
      <ul>
        <li><strong>Modern Frontend &amp; Full-Stack Web:</strong> Architected responsive, high-performance web applications, SaaS dashboards, and digital platforms using <code>TypeScript</code>, <code>Next.js</code>, <code>React</code>, and <code>Laravel 12</code> (<code>Linkswear</code>, <code>Akugrow</code>, <code>SignalCore</code>, <code>token.fajriag.my.id</code>).</li>
        <li><strong>Enterprise ERP, E-Commerce &amp; Billing Systems:</strong> Built end-to-end commercial platforms including multi-tenant office/ERP systems (<code>kantor</code>), e-commerce storefronts (<code>Fajthia-Commerce</code>, <code>vps-store</code>), ISP billing automation (<code>pembayaran-wifi</code>), and Learning Management Systems (<code>LMS</code>, <code>BenkyouHub</code>).</li>
        <li><strong>Cross-Platform &amp; Native Mobile:</strong> Engineered production mobile applications in <code>Flutter (Dart)</code> with Clean Architecture and native iOS applications in <code>Swift</code> (<code>First-Ios-Mobile</code>).</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>2. High-Concurrency Backend &amp; Distributed Systems</h3>
      <ul>
        <li><strong>Go (Golang) Execution Engines:</strong> Architected concurrent backend services and automated trading/business orchestration cores (<code>AlphaStream</code>, <code>BusinessOS</code>, <code>DAGANG-BOT-ID</code>) utilizing goroutine worker pools, non-blocking I/O, and WebSocket streams.</li>
        <li><strong>Asynchronous Python &amp; Node.js APIs:</strong> Deployed low-latency <code>FastAPI</code>, <code>Flask</code>, and <code>Node.js</code> microservices for real-time data processing, media streaming (<code>KuyNonton</code>, <code>dramabox</code>), and ML inference gateways.</li>
        <li><strong>Database Architecture &amp; Security:</strong> Designed normalized relational schemas (<code>PostgreSQL</code>, <code>MySQL</code>), <code>Redis</code> caching &amp; pub/sub layers, RBAC authentication, and containerized <code>Docker</code> deployments.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>3. Generative AI, LLMs &amp; Retrieval Architecture</h3>
      <ul>
        <li><strong>Hybrid RAG Pipelines:</strong> Engineered semantic document intelligence systems (<code>RAG-DocSearch</code>, <code>NeuraSearch</code>) combining dense vector embeddings with lexical retrieval, dynamic chunking, and cross-encoder re-ranking.</li>
        <li><strong>Multi-Model LLM Orchestration:</strong> Built unified AI gateways and agentic workspaces (<code>JriGPT Platform</code>, <code>DASBAORD9ROUTER</code>) with automated provider failover, token streaming, and structured JSON output enforcement.</li>
        <li><strong>Transformer Internals &amp; Auditing:</strong> Implemented custom GPT architectures from scratch in PyTorch (<code>pytorch-gpt-from-scratch</code>) and automated semantic verification engines (<code>SemantiCheck</code>, <code>ai-autopsy-engine</code>).</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>4. Computer Vision, Speech AI &amp; Smart City GIS/IoT</h3>
      <ul>
        <li><strong>Computer Vision &amp; Speech AI:</strong> Real-time industrial PPE compliance detection using <code>YOLOv8 &amp; OpenCV</code> (<code>Safety-helmet-detector</code>), mobile <code>MobileNetV2</code> agricultural diagnostics, and acoustic pronunciation scoring APIs (<code>Nihongo AI</code>).</li>
        <li><strong>Geospatial &amp; Decision Support Systems:</strong> Built wildfire hotspot prediction and urban spatial planning platforms (<code>Karhutla-Indonesia</code>, <code>SITARU</code>, <code>geo-dcm</code>) plus multi-criteria DSS engines (<code>AHP</code>, <code>TOPSIS</code>, <code>SMART</code>).</li>
        <li><strong>Edge-to-Cloud IoT Telemetry:</strong> Hardware-level firmware in <code>C++ / ESP32</code> streaming sensor telemetry via <code>MQTT</code> and <code>Node-RED</code> into real-time analytical dashboards.</li>
      </ul>
    </td>
  </tr>
</table>

---

## Featured Engineering Case Studies

### 01 · Enterprise Full-Stack SaaS, E-Commerce & Digital Platforms (`BusinessOS`, `Linkswear`, `Kantor`, `Fajthia-Commerce`)
> **Domain:** `Full-Stack Software Engineering` · `Enterprise SaaS & ERP` · `E-Commerce & FinTech`  
> **Architecture Stack:** `TypeScript` · `Next.js / React` · `Laravel 12` · `Go` · `PostgreSQL / MySQL` · `Redis` · `Tailwind CSS`

- **Engineering Challenge:** Modern commercial and enterprise workflows require cohesive end-to-end software systems that combine responsive, high-conversion user interfaces with transactional backend reliability, real-time inventory/billing state, and role-based access control.
- **Architectural Solution:** Engineered a suite of full-stack production platforms spanning enterprise office & operations management (`kantor`, `BusinessOS`), high-traffic digital commerce & automated billing (`Linkswear`, `Fajthia-Commerce`, `vps-store`, `pembayaran-wifi`), and interactive education/media ecosystems (`LMS`, `BenkyouHub`, `KuyNonton`, `dramabox`).
- **Key Technical Capabilities:** Modular full-stack architecture, SSR/CSR frontend optimization, RESTful & WebSocket API integration, automated payment/billing workflows, Redis session/query caching, and multi-role administrative dashboards.

---

### 02 · AlphaStream & High-Concurrency Go Backend Core (`AlphaStream`, `DAGANG-BOT-ID`, `SignalCore`)
> **Domain:** `Distributed Backend` · `Concurrent Systems` · `Real-Time Automation`  
> **Architecture Stack:** `Go (Golang)` · `TypeScript` · `PostgreSQL` · `Redis Pub/Sub` · `REST & WebSockets` · `Docker`

- **Engineering Challenge:** High-throughput event ingestion and automated execution workflows require deterministic low latency and strict concurrency safety without memory bloat.
- **Architectural Solution:** Engineered the core backend services in **Go**, leveraging bounded goroutine worker pools, channel-based pipelines, Redis in-memory state synchronization, and connection pooling paired with TypeScript real-time monitoring interfaces.
- **Key Technical Capabilities:** Sub-50ms internal dispatch overhead, graceful fault recovery, real-time bidirectional WebSocket telemetry, and modular microservice boundaries.

---

### 03 · JriGPT Platform, NeuraSearch & Hybrid RAG Engine (`jrigpt-platform`, `RAG-DocSearch`, `DASBAORD9ROUTER`)
> **Domain:** `Full-Stack AI Platform` · `Enterprise RAG` · `Multi-LLM Gateway`  
> **Architecture Stack:** `Python` · `FastAPI` · `LangChain` · `Vector DB` · `Laravel 12` · `TypeScript` · `Redis`

- **Engineering Challenge:** Standard LLM integrations suffer from hallucination on proprietary enterprise documents, high token latency, and single-provider downtime risks.
- **Architectural Solution:** Designed a full-stack Generative AI platform pairing a **Hybrid Retrieval-Augmented Generation (RAG)** pipeline (dense vector similarity + keyword filtering) with a multi-provider LLM routing gateway and an intuitive full-stack web workspace.
- **Key Technical Capabilities:** Context-window optimization, automated document ingestion & chunk indexing, semantic similarity verification (`SemantiCheck`), and multi-provider API key/account orchestration (`AG_SWITCH_ACCOUNT`).

---

### 04 · Karhutla-Indonesia, SITARU & Smart City Geo-Intelligence (`Karhutla-Indonesia`, `SITARU`, `-dashboard-ecoedu`)
> **Domain:** `Full-Stack GIS` · `Smart City Infrastructure` · `Public-Sector Analytics`  
> **Architecture Stack:** `Python` · `Scikit-learn` · `TypeScript` · `Laravel` · `GeoJSON / GIS` · `MySQL`

- **Engineering Challenge:** Regional governments and environmental agencies require unified full-stack platforms to correlate spatial GIS layers, historical hazard data, and public health/education KPIs in real time.
- **Architectural Solution:** Built integrated geospatial intelligence platforms (`Karhutla-Indonesia`, `SITARU`, `indramayu-analytics-dashboard`) combining Python predictive modeling with interactive TypeScript and Laravel analytical dashboards.
- **Key Technical Capabilities:** Automated spatial risk clustering, interactive polygon/hotspot rendering, multi-criteria decision support (`AHP` / `TOPSIS` / `SMART`), and executive reporting exports.

---

### 05 · Nihongo AI, Cross-Platform Mobile & Industrial Vision Suite (`Nihongo AI`, `Safety-helmet-detector`, `First-Ios-Mobile`)
> **Domain:** `Mobile Engineering (Flutter & iOS)` · `Speech AI` · `Computer Vision`  
> **Architecture Stack:** `Flutter (Dart)` · `Swift (iOS)` · `FastAPI` · `PyTorch` · `YOLOv8` · `MobileNetV2` · `OpenCV`

- **Engineering Challenge:** Delivering responsive mobile user experiences alongside complex deep learning inference (speech phoneme evaluation and real-time video object detection) with minimal latency.
- **Architectural Solution:** Implemented **Clean Architecture** across **Flutter** and native **Swift** mobile clients, decoupled from optimized **FastAPI/PyTorch** inference microservices and lightweight on-device `MobileNetV2` models.
- **Key Technical Capabilities:** Real-time frame-by-frame PPE safety compliance detection (`Safety-helmet-detector`), automated acoustic pronunciation scoring, and reactive mobile state management.

---

## Production Technology Matrix

<div align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,nextjs,react,tailwind,laravel,php,go,python,fastapi,nodejs,flutter&perline=12" alt="Full-Stack Web, Backend & Mobile Stack" />
  <br/>
  <img src="https://skillicons.dev/icons?i=dart,swift,cpp,pytorch,tensorflow,sklearn,opencv,postgres,mysql,redis,docker,git&perline=12" alt="Mobile, AI/ML & Cloud Infrastructure" />
</div>

<br/>

| Architectural Layer | Production Technologies, Frameworks & Protocols |
| :--- | :--- |
| **Frontend & Full-Stack Web** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Laravel](https://img.shields.io/badge/Laravel_12-FF2D20?style=flat-square&logo=laravel&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) `Blade` · `HTML5 / CSS3` · `SSR / SPA Architecture` |
| **Backend & Distributed Core** | ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![PHP](https://img.shields.io/badge/PHP_8.3+-777BB4?style=flat-square&logo=php&logoColor=white) ![Python](https://img.shields.io/badge/Python_3.12+-3776AB?style=flat-square&logo=python&logoColor=white) `Flask` · `RESTful APIs` · `WebSockets` · `Microservices` · `Worker Pools` |
| **Mobile Engineering** | ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white) ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white) ![Swift](https://img.shields.io/badge/Swift_iOS-F05138?style=flat-square&logo=swift&logoColor=white) `Clean Architecture` · `State Management` · `On-Device ML Inference` |
| **AI, LLM & Deep Learning** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) `YOLOv8` · `LangChain` · `Hybrid RAG` · `Transformers / PEFT` · `MobileNetV2` · `Speech AI` |
| **Data, Cloud & Embedded IoT** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) `Vector DB` · `Firebase` · `Git / CI-CD` · `ESP32 / C++` · `MQTT` · `Node-RED` |

---

## Professional Credentials, Licenses & Education

| Credential / Academic Degree | Issuing Institution | Verified Technical Scope |
| :--- | :--- | :--- |
| **IBM Generative AI Engineering Professional Certificate** | **IBM** | Transformer Architectures, Foundation Models, LLM Fine-Tuning (PEFT/LoRA), Retrieval-Augmented Generation (RAG), LangChain Agents & Prompt Engineering |
| **IBM AI Engineering Professional Certificate** | **IBM** | Deep Learning Architectures, CNNs, RNNs, Collaborative Filtering, PyTorch, TensorFlow, Keras & Scalable ML Pipelines |
| **Machine Learning, AI & Statistics Specialization** | **University of Pennsylvania** | Supervised & Unsupervised Learning, Statistical Inference, Probability Modeling, Regression & Algorithmic Optimization |
| **Applied AI & Advanced Prompt Engineering** | **Google** | Production LLM Workflow Design, Structured Output Engineering, Context Optimization & Enterprise AI Automation |
| **B.App.Sc. (D4) in Smart City Information Systems** | **Politeknik Negeri Indramayu** | Full-Stack Software Engineering, Enterprise Information Systems, Geospatial Information Systems (GIS), IoT Networks & Decision Support Systems (DSS) |

---

## GitHub Engineering Telemetry & Contribution Activity

<div align="center">
  <img src="./assets/github-telemetry.svg" width="100%" alt="GitHub Engineering Telemetry — 11,384 Contributions across 66 Repositories" />
</div>

---

## Executive Contact & Engineering Inquiries

Available for **Full-Stack Software Engineering (TypeScript / Next.js / Laravel / Go / Flutter)**, **AI & LLM Systems Architecture**, and **Enterprise Technical Consulting**.

- **Direct Email:** [fajriabdurahmanghurri@gmail.com](mailto:fajriabdurahmanghurri@gmail.com)
- **LinkedIn Profile:** [linkedin.com/in/fajri-abdurahman-ghurri](https://linkedin.com/in/fajri-abdurahman-ghurri/)
- **GitHub Portfolio:** [github.com/FAJRIAG](https://github.com/FAJRIAG)
- **Base Location:** Indonesia (Available for Remote Global & On-Site Enterprise Roles)

<br/>

<div align="center">
  <img src="./assets/footer-banner.svg" width="100%" alt="Fajri Abdurahman Ghurri — Footer Banner" />
</div>
