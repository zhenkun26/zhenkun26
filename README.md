# Hi! I am zhenkun. 👋

> **AI 应用与 Python 后端开发者**<br>
> **AI Application & Python Backend Developer**

我专注于构建**可控的 Agent 工作流、可验证的 RAG，以及面向可靠性的后端系统**。目前正在寻找 AI 应用工程 / Python 后端开发相关机会。

I build **controllable agent workflows, evidence-backed RAG, and reliability-oriented backend systems**. Open to AI application engineering and Python backend opportunities.

[![Email](https://img.shields.io/badge/Email-zzk26personal%40163.com-555?style=flat-square&logo=maildotru&logoColor=white)](mailto:zzk26personal@163.com)
[![GitHub](https://img.shields.io/badge/GitHub-zhenkun26-181717?style=flat-square&logo=github)](https://github.com/zhenkun26)

---

## 作品精选 · Selected Work

### [BusinessAgent · 智多星](https://github.com/zhenkun26/BusinessAgent)

**中文 · ZH**

- **价值**：面向企业知识问答、数据分析和受控业务操作的多 Agent 工作流系统。
- **难点**：LangGraph 显式状态机、两阶段 RAG、RBAC 与审批、Saga 补偿、降级和可观测性。
- **证据**：我的工作重点包括生产就绪评审、RAG 质量、测试/CI、安全加固、性能与灾备、工单适配；仓库包含 [101 项自动化测试](https://github.com/zhenkun26/BusinessAgent/tree/main/enterprise-agent/tests)、[CI 安全检查](https://github.com/zhenkun26/BusinessAgent/actions/workflows/ci.yml)及部署与演练资产。外部 CRM 与邮件目前以 Mock/契约适配为主，工单链路完成 HTTP 适配与 stub 沙箱验收。

**English · EN**

- **Value**: A multi-agent workflow system for enterprise knowledge Q&A, data analysis, and controlled business operations.
- **Challenges**: LangGraph explicit state machines, two-stage RAG, RBAC with approval flows, Saga compensation, graceful degradation, and observability.
- **Evidence**: My focus includes production-readiness review, RAG quality, testing/CI, security hardening, performance & disaster recovery, and ticket-system adaptation. The repo includes [101 automated tests](https://github.com/zhenkun26/BusinessAgent/tree/main/enterprise-agent/tests), [CI security scanning](https://github.com/zhenkun26/BusinessAgent/actions/workflows/ci.yml), and deployment & drill assets. External CRM and email integrations currently use mock/contract adapters; ticket workflows are verified with HTTP adapters and stub sandbox acceptance.

`Python` `FastAPI` `LangGraph` `Milvus` `PostgreSQL` `Redis` `OpenTelemetry`

---

### [TripMate · 智能旅行助手](https://github.com/zhenkun26/TripMate)

**中文 · ZH**

- **价值**：基于高德候选数据生成结构化行程，并提供预算估算、天气、地图和分享输出。
- **难点**：并行外部数据采集、结构化输出校验与修复、Redis 缓存/限流、前后端契约同步。
- **证据**：[后端与前端测试](https://github.com/zhenkun26/TripMate/tree/main/backend/tests)、[ruff + mypy strict + pytest + Vitest CI](https://github.com/zhenkun26/TripMate/actions/workflows/ci.yml)、Pydantic → TypeScript 契约生成及 Docker Compose 启动链路。

**English · EN**

- **Value**: Generates structured itineraries from Amap candidate data, with budget estimation, weather, maps, and shareable output.
- **Challenges**: Parallel external data fetching, structured output validation & repair, Redis caching/rate-limiting, and frontend-backend contract synchronization.
- **Evidence**: [Backend & frontend tests](https://github.com/zhenkun26/TripMate/tree/main/backend/tests), [ruff + mypy strict + pytest + Vitest CI](https://github.com/zhenkun26/TripMate/actions/workflows/ci.yml), Pydantic → TypeScript contract generation, and Docker Compose launch pipeline.

`Python` `FastAPI` `Vue 3` `TypeScript` `Pydantic` `Redis` `LLM Structured Output`

---

### [Desktop-pet · 二次元桌宠](https://github.com/zhenkun26/Desktop-pet)

**中文 · ZH**

- **价值**：集成流式 AI 对话、会话存储、休息提醒和番茄钟的 macOS Electron 桌面应用。
- **难点**：Electron 进程隔离与 IPC、SSE 解析/取消/超时、SQLite 数据迁移、safeStorage 密钥保存。
- **证据**：[核心服务与测试](https://github.com/zhenkun26/Desktop-pet/tree/main/src/main/services)、[TypeScript 构建与测试 CI](https://github.com/zhenkun26/Desktop-pet/actions/workflows/ci.yml)、DMG 打包流程。角色美术资源仅用于非商业学习与交流。

**English · EN**

- **Value**: A macOS Electron desktop app integrating streaming AI chat, session storage, break reminders, and a Pomodoro timer.
- **Challenges**: Electron process isolation & IPC, SSE parsing/cancellation/timeout, SQLite data migration, and safeStorage key protection.
- **Evidence**: [Core services & tests](https://github.com/zhenkun26/Desktop-pet/tree/main/src/main/services), [TypeScript build & test CI](https://github.com/zhenkun26/Desktop-pet/actions/workflows/ci.yml), and DMG packaging pipeline. Character art assets are used for non-commercial learning and exchange only.

`Electron` `TypeScript` `DeepSeek API` `SSE` `SQLite` `safeStorage`

---

## 能力与证据 · Capabilities with Evidence

| 能力域 · Capability | 技术与设计 · Tech & Design | 项目证据 · Project Evidence |
| --- | --- | --- |
| Agent 工作流 · Agent Workflows | StateGraph, parallel fan-out, re-planning, tool gateway, Human-in-the-loop | [BusinessAgent](https://github.com/zhenkun26/BusinessAgent) |
| RAG 工程 · RAG Engineering | Milvus HNSW, BGE Reranker, source attribution, confidence-based decisions, retrieval fallback | [BusinessAgent](https://github.com/zhenkun26/BusinessAgent) |
| AI 应用集成 · AI App Integration | Structured output, external data constraints, SSE streaming, retry & fallback | [TripMate](https://github.com/zhenkun26/TripMate) · [Desktop-pet](https://github.com/zhenkun26/Desktop-pet) |
| Python 后端 · Python Backend | FastAPI, Pydantic, JWT/RBAC, PostgreSQL, Redis, rate-limiting & idempotency | [BusinessAgent](https://github.com/zhenkun26/BusinessAgent) · [TripMate](https://github.com/zhenkun26/TripMate) |
| 可靠性与交付 · Reliability & Delivery | Saga, task queues, audit logging, Metrics/Trace, CI, security scanning, containerization | [BusinessAgent](https://github.com/zhenkun26/BusinessAgent) |
| 工程质量 · Engineering Quality | pytest, Vitest, mypy strict, ruff, contract drift detection, adversarial fixtures | [TripMate](https://github.com/zhenkun26/TripMate) · [auto-coding](https://github.com/zhenkun26/auto-coding) |

---

## 工具与实验 · Tooling & Experiments

**中文 · ZH**

- **[auto-coding](https://github.com/zhenkun26/auto-coding)**：面向 AI 编码助手的风险感知交付 skill；包含风险路由、AST 契约检查、原子状态恢复、CI 与版本发布。
- **[EquiRebuild](https://github.com/zhenkun26/EquiRebuild)**：Hermes 生态扩展实验；提供可配置的代码加固扫描器与审查 skill，并以离线测试和并发冒烟验证。

**English · EN**

- **[auto-coding](https://github.com/zhenkun26/auto-coding)**: A risk-aware delivery skill for AI coding assistants; includes risk routing, AST contract checks, atomic state recovery, CI, and versioned releases.
- **[EquiRebuild](https://github.com/zhenkun26/EquiRebuild)**: A Hermes ecosystem extension experiment; provides a configurable code hardening scanner and review skill, verified with offline tests and concurrent smoke testing.

---

## 我在乎的 · What I Care About

**中文 · ZH**

- 让 Agent 的路由、权限和副作用边界可检查，而不是依赖模型临场发挥。
- 让 RAG 回答能追溯来源、评测质量，并在证据不足时明确拒答或降级。
- 让后端系统通过类型、测试、审计、指标和故障路径证明可靠性。

**English · EN**

- Making Agent routing, permissions, and side-effect boundaries auditable — rather than relying on model improvisation.
- Making RAG answers traceable to sources, evaluable for quality, and able to refuse or degrade gracefully when evidence is insufficient.
- Making backend systems prove their reliability through types, tests, audit trails, metrics, and well-defined failure paths.

---

## 联系 · Contact

正在寻找 **AI 应用工程 / Python 后端开发** 相关机会，也欢迎交流 Agent、RAG 和 AI 工程实践。

Open to **AI Application Engineering / Python Backend Development** opportunities. Always happy to chat about Agent, RAG, and AI engineering practices.

📧 [zzk26personal@163.com](mailto:zzk26personal@163.com) · 🐙 [github.com/zhenkun26](https://github.com/zhenkun26)
