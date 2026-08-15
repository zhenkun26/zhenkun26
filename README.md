<div align="center">

# 👋 Hi, I'm Zhenkun

> **AI 应用工程师 · Python 后端开发者**<br>
> **AI Application Engineer · Python Backend Developer**

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&center=true&width=680&lines=Controllable+Agent+Workflows;Evidence-backed+RAG;Reliability-first+Backend+Systems;Local-first+AI+Applications;Open+to+AI+Application+Engineering)

![Python](https://img.shields.io/badge/Python-3.11%2B-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-Agent_Workflow-1c3c3c?style=flat-square&logo=langgraph&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-Milvus_%26_BM25-6d28d9?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-Local_LLM-000000?style=flat-square&logo=ollama&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-39-47848F?style=flat-square&logo=electron&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5.7-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</div>

---

## 🧭 关于我 · About Me

我专注于把 LLM 应用与 Agent 系统做成**可靠的产品**：路由、权限与副作用边界可审计；RAG 回答可追溯、可评测；后端行为用测试与指标证明。我习惯亲手走完「设计 → 实现 → 测试 → 上线」的完整链路，并把关键决策沉淀为仓库里的自动化测试、CI 检查与部署资产——**让代码自己讲述它的可靠性**。

I focus on turning LLM applications and agent systems into **reliable products**: auditable routing, permissions, and side-effect boundaries; RAG answers that are traceable and evaluable; backend behavior proven by tests and metrics. I walk the full path — design → implementation → testing → shipping — and encode every key decision into automated tests, CI checks, and deployment assets, **so the code tells its own reliability story**.

近期我持续探索 [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness) 这一受到关注的开源 AI coding harness 项目，并将仓库理解、证据驱动分析与有界变更生命周期适配为 [RepoAtlas](https://github.com/zhenkun26/RepoAtlas) 插件，重点关注公开工具注册、bundle 加载、兼容性验证与默认只读的安全边界。

Recently I've been following the fast-moving open-source [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness) project and adapting repository understanding, evidence-backed analysis, and bounded change lifecycles into the [RepoAtlas](https://github.com/zhenkun26/RepoAtlas) plugin, with a focus on public tool registration, bundle loading, compatibility verification, and read-only-by-default safety boundaries.

工作中我熟练运用 **Vibe Coding**——以 AI 编码助手为第一生产力，用自然语言驱动「设计 → 实现 → 测试 → 上线」的全流程，并深度使用 **Codex、Claude Code、Cursor、Kimi、DeepSeek** 等多模型组合，按任务特性灵活切换。我始终带着**产品化意识**做工程：不满足于「能跑」，而是追求可维护、可测试、可交付、真正被用户用起来。

In practice I'm fluent in **Vibe Coding** — AI coding assistants as the primary driver across design → implementation → testing → shipping — working hands-on with a multi-model stack (**Codex, Claude Code, Cursor, Kimi, DeepSeek**) chosen per task. I bring a **product mindset** to engineering: code that merely runs isn't the bar; it must be maintainable, testable, shippable, and usable by real people.

---

## 🚀 作品精选 · Selected Work

### 🧭 [RepoAtlas · 代码星图](https://github.com/zhenkun26/RepoAtlas)

- **价值 · Value**：近期持续探索 [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness) 这一受到关注的开源 AI coding harness 项目，并完成 RepoAtlas 适配插件——面向陌生代码库提供安全优先、证据驱动的分析与有界变更生命周期；默认只读，受控动作显式审批。
  Recently exploring the fast-moving open-source [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness) ecosystem and building RepoAtlas as an adapted plugin — safety-first, evidence-backed repository analysis and a bounded change lifecycle for unfamiliar codebases; read-only by default, with explicit approval for controlled actions.
- **难点 · Challenges**：将代码库接手、证据与推断区分、Goal/approval policy gate、ReAct 分析、补丁审阅与验证串成可审计的生命周期，同时保持与 Harness 核心解耦，不扩大 Shell、网络、依赖安装或远程写入权限。
  Turning repository onboarding, evidence-versus-inference boundaries, Goal/approval policy gates, ReAct analysis, patch review, and verification into an auditable lifecycle while keeping the plugin decoupled from Harness core and avoiding broader Shell, network, dependency-installation, or remote-write permissions.
- **落地 · Shipped**：完成公开 `ctx.tools.register` 接入、`repo-atlas/harness` bundle 加载与 pinned Harness revision 的真实兼容性 smoke，采用 source-first 方式发布 `0.1.1`。
  Delivered public `ctx.tools.register` integration, `repo-atlas/harness` bundle loading, and real compatibility smoke coverage against a pinned Harness revision; released `0.1.1` as a source-first plugin bundle.

`TypeScript` `Node.js` `DeepSeek Harness` `Evidence-backed Analysis` `Sandbox-aware Lifecycle`

---

### 🏢 [BusinessAgent · 智多星](https://github.com/zhenkun26/BusinessAgent)

- **价值 · Value**：面向企业知识问答、数据分析和受控业务操作的多 Agent 工作流系统——回答有据可查、操作有审批、执行有审计。已在内部业务场景中落地并持续运行，核心链路经过真实数据与流程验证。
  A multi-agent workflow system for enterprise knowledge Q&A, data analysis, and controlled operations — answers with sources, operations with approvals, execution with audit trails. Deployed and running in internal production environments, with core paths validated against real data and workflows.
- **难点 · Challenges**：多 Agent 协作的落地难题——任务流转的显式编排、知识与数据双通道检索、高风险操作的审批与权限、跨环节失败的一致性补偿、故障时的优雅降级；生产对抗性审查修复 12 个漏洞（含 3 个 P0 级认证/凭证类）。
  Turning multi-agent orchestration into production — explicit workflow state machines, two-stage retrieval for knowledge and data, approvals and permissions for high-risk actions, consistent compensation when a step fails mid-chain, and graceful degradation; 12 vulnerabilities fixed in adversarial production review (3 P0 auth/credential class).
- **落地 · Shipped**：[101 项自动化测试](https://github.com/zhenkun26/BusinessAgent/tree/main/enterprise-agent/tests)、[3 道 CI 安全门禁（gitleaks + pip-audit + Trivy）](https://github.com/zhenkun26/BusinessAgent/actions/workflows/ci.yml)、工单系统真实接入（幂等键 + Saga 补偿 + 审计回写，stub 沙箱验收 7/7）、模型分层（高频 qwen3.5:4b + 推理 DeepSeek，成本降低 40%+）、三级降级链（LLM/检索/Checkpointer）、k6 阶梯压测与备份恢复演练。
  [101 automated tests](https://github.com/zhenkun26/BusinessAgent/tree/main/enterprise-agent/tests), [3 CI security gates (gitleaks + pip-audit + Trivy)](https://github.com/zhenkun26/BusinessAgent/actions/workflows/ci.yml), real ticket system pilot (idempotency keys + Saga compensation + audit write-back, stub sandbox 7/7), model tiering (high-freq qwen3.5:4b + reasoning DeepSeek, 40%+ cost reduction), three-stage degradation chain (LLM/retrieval/checkpointer), k6 staircase load tests and backup-restore drills.

`Python` `FastAPI` `LangGraph` `Milvus` `PostgreSQL` `Redis` `OpenTelemetry`

---

### 🔍 [Insight · 洞察者](https://github.com/zhenkun26/Insight)

- **价值 · Value**：面向气象业务文档的本地优先 RAG 应用——混合检索（BM25 + 向量 + RRF 融合）、证据不足时明确拒答、全链路阶段级可观测。零云依赖，本地运行。
  A local-first RAG application for meteorological operational documents — hybrid retrieval (BM25 + vector + RRF fusion), explicit refusal on insufficient evidence, stage-level observability across the full pipeline. Zero cloud dependencies, runs entirely locally.
- **难点 · Challenges**：中文专业文档检索的工程难题——CJK 分词避免单字过匹配的 Bigram 策略、BM25 与向量语义两路融合的 RRF 调参、证据评分门控防止大模型幻觉、扫描件 PDF 的按需 OCR（仅处理无文本层页面）、流式生成中断后的优雅降级、全链路阶段计时与状态追踪。
  Real engineering challenges in Chinese domain document retrieval — CJK bigram tokenization to prevent single-character overmatching, RRF fusion of BM25 lexical and vector semantic paths, score-threshold gating to prevent LLM hallucination, on-demand OCR for scan PDFs (only pages with zero text layers), graceful fallback when streaming generation breaks, and full-pipeline stage timing with status tracking.
- **落地 · Shipped**：[49 项自动化测试](https://github.com/zhenkun26/Insight/tree/main/tests)（含检索评测脚本，支持 hit_rate / MRR / refusal_accuracy / 阶段延迟）、[ruff + pytest CI](https://github.com/zhenkun26/Insight/actions/workflows/ci.yml)、12 条评测问题（10 条可验证 + 2 条拒答测试）、Docker Compose 一键部署（API + Milvus + etcd + MinIO）、零依赖前端控制台（纯 HTML/CSS/JS，无构建步骤）。
  [49 automated tests](https://github.com/zhenkun26/Insight/tree/main/tests) (including evaluation CLI with hit_rate, MRR, refusal_accuracy, and per-stage latency), [ruff + pytest CI](https://github.com/zhenkun26/Insight/actions/workflows/ci.yml), 12 evaluation questions (10 grounded + 2 refusal test cases), Docker Compose one-command deployment (API + Milvus + etcd + MinIO), zero-dependency frontend console (pure HTML/CSS/JS, no build step).

`Python` `FastAPI` `Milvus` `Ollama` `BM25` `RRF` `SQLite` `SSE Streaming`

---

### 🧳 [TripMate · 智能旅行助手](https://github.com/zhenkun26/TripMate)

- **价值 · Value**：基于高德候选数据生成结构化行程，预算估算、天气、地图、品牌分享一站式输出。
  Structured itineraries from Amap candidate data — budget, weather, maps, and branded shareable output in one flow.
- **难点 · Challenges**：真实出行的工程问题——多数据源并行采集、AI 输出格式漂移的自动校验与修复、Kubernetes 部署就绪（多架构镜像 + lifecycle 探针 + Prometheus 指标）、结构化 JSON 日志与请求链追踪、前后端契约 CI 强制同步。
  Real-world travel engineering — parallel fetching from multiple data sources, auto-validating and repairing AI output drift, Kubernetes readiness (multi-arch images + lifecycle probes + Prometheus metrics), structured JSON logging with request chain tracing, and CI-enforced frontend-backend contract sync.
- **落地 · Shipped**：[后端 83 项测试（行覆盖率 90%）+ 前端 Vitest](https://github.com/zhenkun26/TripMate/tree/main/backend/tests)、[ruff + mypy strict + pytest + Vitest CI](https://github.com/zhenkun26/TripMate/actions/workflows/ci.yml)、多模型 LLM 适配（配置切换 OpenAI 兼容端点，默认 DeepSeek）、Docker Compose 一键启动。
  [83 backend tests (90% line coverage) + frontend Vitest](https://github.com/zhenkun26/TripMate/tree/main/backend/tests), [ruff + mypy strict + pytest + Vitest CI](https://github.com/zhenkun26/TripMate/actions/workflows/ci.yml), multi-model LLM adapter (config-switchable OpenAI-compatible endpoints, default DeepSeek), one-command Docker Compose startup.

`Python` `FastAPI` `Vue 3` `TypeScript` `Pydantic` `Redis` `Kubernetes` `Structured Logging`

---

## 🧰 能力与落地 · Capabilities Delivered

| 能力 · Capability | 技术与设计 · Tech & Design | 项目落地 · Shipped |
| --- | --- | --- |
| 🤖 Agent 工作流 · Agent Workflows | StateGraph, parallel fan-out, re-planning, tool gateway, Human-in-the-loop, model tiering | [BusinessAgent](https://github.com/zhenkun26/BusinessAgent) |
| 📚 RAG 工程 · RAG Engineering | Milvus HNSW, BM25 + vector hybrid, RRF fusion, CJK bigram tokenization, source attribution, confidence gating, explicit refusal, stage-level tracing | [Insight](https://github.com/zhenkun26/Insight) · [BusinessAgent](https://github.com/zhenkun26/BusinessAgent) |
| 🖥️ 桌面端 AI · Desktop AI | Electron, node:sqlite (WAL), SSE streaming, safeStorage encryption, XSS sanitization, database-as-truth architecture | [Desktop-pet](https://github.com/zhenkun26/Desktop-pet) |
| ⚙️ AI 应用集成 · AI App Integration | Structured output, external data constraints, SSE streaming, multi-model adapter, retry & fallback | [TripMate](https://github.com/zhenkun26/TripMate) · [Desktop-pet](https://github.com/zhenkun26/Desktop-pet) |
| 🐍 Python 后端 · Python Backend | FastAPI, Pydantic, JWT/RBAC, PostgreSQL, Redis, rate-limiting & idempotency, structured JSON logging | [BusinessAgent](https://github.com/zhenkun26/BusinessAgent) · [TripMate](https://github.com/zhenkun26/TripMate) · [Insight](https://github.com/zhenkun26/Insight) |
| 🛡️ 可靠性与交付 · Reliability & Delivery | Saga, task queues, audit logging, Metrics/Trace, CI, security scanning, containerization, degradation chains | [BusinessAgent](https://github.com/zhenkun26/BusinessAgent) · [Desktop-pet](https://github.com/zhenkun26/Desktop-pet) |
| ✅ 工程质量 · Engineering Quality | pytest, Vitest, mypy strict, ruff, contract drift detection, adversarial fixtures, multi-arch Docker, gitleaks, Trivy | [TripMate](https://github.com/zhenkun26/TripMate) · [auto-coding](https://github.com/zhenkun26/auto-coding) · [Insight](https://github.com/zhenkun26/Insight) |

---

## 🛠️ 工具与实验 · Tooling & Experiments

- **[auto-coding](https://github.com/zhenkun26/auto-coding)**：面向 AI 编码助手的风险感知交付 skill——按风险分级规划执行深度、三层自检 + 逃逸门检测、结构级契约检查、自适应工具链、中断后的安全恢复、CI 与版本发布。已重构为 14 份按需读取的 references，通过 Codex 插件分发。
  A risk-aware delivery skill for AI coding assistants — risk-graded planning, three-layer self-check with escape hatch detection, structural contract checks, adaptive toolchain, safe recovery after interruptions, CI, and versioned releases. Refactored into 14 on-demand references, distributed via Codex plugin.
- **[EquiRebuild](https://github.com/zhenkun26/EquiRebuild)**：Hermes 生态扩展——可配置的代码审查与加固 skill（5 维度对抗性审查），57 项测试（行覆盖率 95%），仅依赖标准库，新增实例级 timeout 追踪与高熵字符串检测。
  A Hermes ecosystem extension — configurable code review and hardening skill (5-dimension adversarial review), 57 tests (95% line coverage), standard-library-only dependency, with instance-level timeout tracking and high-entropy string detection.
- **[daily-information](https://github.com/zhenkun26/daily-information)**：个人 AI 每日信息摘要管线——多源信号采集（GitHub / RSS / X）、去重与多维评分（相关性、新颖性、可信度）、LLM 策划与结构化输出验证、中文 Markdown 日报归档。四阶段管道设计（采集 → 候选 → 事件 → 发布），参考实现已跑通 Twitter 监控 + AI 摘要 + 飞书推送。
  A personal AI daily digest pipeline — multi-source signal collection (GitHub / RSS / X), deduplication with multi-dimensional scoring (relevance, novelty, credibility), LLM curation with structured output validation, and Chinese Markdown daily archives. Four-stage pipeline design (collect → candidate → event → publish), with a reference implementation running Twitter monitoring + AI summarization + Feishu push.
- **DeepSeek Harness 插件设计落地 · DeepSeek Harness Plugin Design & Delivery**：近期跟进 DeepSeek Harness 插件生态的设计与落地，围绕 manifest、权限声明、Harness 兼容性检查、本地插件目录扫描与 Profile 生成，推进可复现、可审计的安装前校验流程。
  Recently following through on the design and delivery of DeepSeek Harness plugins, focusing on manifests, permission declarations, Harness compatibility checks, local plugin catalog scanning, and profile generation to establish reproducible, auditable pre-install validation.

---

## 💡 我在乎的 · What I Care About

- ✅ 让 Agent 的路由、权限和副作用边界**可检查**，而不是依赖模型临场发挥。
  Making agent routing, permissions, and side-effect boundaries **auditable** — not left to model improvisation.
- 📚 让 RAG 回答**可追溯来源、可评测质量**，证据不足时明确拒答或降级——不幻想、不编造。
  Making RAG answers **traceable and evaluable** — refusing or degrading clearly when evidence is insufficient. No hallucination, no fabrication.
- 🛡️ 让后端系统通过类型、测试、审计、指标与故障路径**证明可靠性**。
  Making backend systems **prove reliability** through types, tests, audit trails, metrics, and well-defined failure paths.
- 🔍 让 AI 管线**每一阶段可观测**——检索、融合、重排、生成，每个环节的延迟和状态都可见、可复盘。
  Making AI pipelines **observable at every stage** — retrieval, fusion, rerank, generation, each with visible latency and status, ready for post-mortem.

---

## 📫 联系 · Contact

正在寻找 **AI 应用工程 / Python 后端开发** 相关机会，也欢迎交流 Agent、RAG、桌面端 AI 与云原生工程实践。

Open to **AI Application Engineering / Python Backend Development** roles — always happy to chat about agents, RAG, desktop AI, and cloud-native engineering practice.

[![Email](https://img.shields.io/badge/Email-zzk26personal%40163.com-555?style=flat-square&logo=maildotru&logoColor=white)](mailto:zzk26personal@163.com)
[![GitHub](https://img.shields.io/badge/GitHub-zhenkun26-181717?style=flat-square&logo=github)](https://github.com/zhenkun26)

> *Keep building. Keep verifying. Let what's shipped speak.*<br>
> *持续构建，持续验证，让交付说话。*
