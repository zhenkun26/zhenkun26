# Hi, I'm zhenkun 👋

一个想法很多的开发者。
A developer with many ideas.

---

## 🚀 Projects / 项目

### ⚡ auto-coding · AI 编程搭档 / AI Coding Partner

一套面向 AI 编码助手的并联开发体系：**grill-me（反思追问）+ OpenSpec（业务规划）+ Pipeline（工程执行）+ Ponytail（代码最小化）** 各跑强项、互不重叠，按变更复杂度自动分流，并在作业过程中持续沉淀经验。

A parallel development system for AI coding assistants: **grill-me (reflective questioning) + OpenSpec (product planning) + Pipeline (engineering execution) + Ponytail (code minimalism)** — each playing to its strengths without overlap, auto-routing by change complexity and continuously accumulating experience along the way.

- 全流程兜底：探索 → 立项 → 执行 → L0/L1/L2 三层自检 → 质量闸门 → 收尾归档，拒绝「开发到一半直接变垃圾」/ end-to-end safety net: explore → propose → execute → L0/L1/L2 self-checks → quality gates → archive; no more "half-built garbage"
- 复杂度分流 C0–C2，覆盖率 ≥80% / 分支 ≥70% 硬性闸门，跨会话断点恢复 / C0–C2 complexity routing, coverage ≥80% / branch ≥70% hard gates, cross-session resume
- 以 Codex Plugin 形态分发，一键安装 / distributed as a Codex plugin — one-command install
- Python 3.12，工具模块覆盖率 88%，36 个 pytest 用例，CI + Release 全自动 / Python 3.12, 88% tool-module coverage, 36 pytest cases, automated CI + Release
- 仓库本身就是 dogfooding 的产物——从产品化到发布全靠这套体系自己迭代完成 / this repo is itself a dogfooding product, built and shipped with the very system it describes

### 🐱 Desktop-pet · 二次元桌宠 / Anime Desktop Pet

一个 Electron 二次元桌宠应用：透明置顶窗口、拖拽互动、AI 角色对话、休息提醒与番茄钟，并预留多角色扩展框架（当前内置胡桃）。

An Electron anime-style desktop pet: transparent always-on-top window, drag-and-drop, AI roleplay chat, rest reminders and a Pomodoro timer, with a multi-character framework (currently ships with Hutao).

- Electron 39 + TypeScript 5.7，electron-vite 三端构建 / three-target build
- DeepSeek 驱动的流式对话（SSE + 会话历史 + 角色设定 + 监听器级故障隔离）/ DeepSeek-driven streaming chat (SSE + history + personas + isolated event dispatch)
- API Key 系统钥匙串级加密存储，HTTP 超时与输入校验等生产级加固 / keychain-encrypted API key storage with production-grade hardening
- 多角色框架：`pet-registry` 注册表 + petId 全链路隔离，新增桌宠仅需登记素材与人设 / multi-character framework: `pet-registry` + petId isolation, add a pet by registering assets & persona only
- CI（typecheck + test + gitleaks）、81 项单元测试、OpenSpec、Docker（23MB）、K8s 清单、macOS 打包 / CI, 81 unit tests, OpenSpec, Docker (23MB), K8s manifests, macOS packaging

### 🤖 BusinessAgent · 智多星 / Enterprise Multi-Agent Platform

企业级多智能体平台：员工用自然语言完成**知识问答、数据分析、业务执行**，以 RBAC 权限、审批闭环、全栈降级与全链路可观测为护栏（v1.3.0 生产就绪）。

An enterprise multi-agent platform (v1.3.0, production-ready): employees complete **knowledge Q&A, data analysis, and business execution** in natural language, guarded by RBAC, approval loops, full-stack degradation, and end-to-end observability.

- 知识问答：RAG 两阶段检索（Milvus 粗排 + BGE 精排）+ 三级降级链，拒答优于编造 / two-stage RAG retrieval with a three-tier fallback; refusing to answer beats fabricating
- 数据分析：LLM 规划 + Python 真实聚合，数字绝不编造 / LLM planning + real Python aggregation — numbers are never fabricated
- 业务执行：RBAC 双闸 + 审批闭环 + Saga 补偿，高风险操作自动建审批单 / RBAC dual gates + approval loop + Saga compensation for high-risk operations
- FastAPI + LangGraph + Milvus + PostgreSQL + Redis，支持 Docker / K8s 部署 / Docker & K8s ready
- 89 项单元测试全绿、13 项 OpenSpec 规格、对抗性审查 12 项漏洞修复 / 89 passing unit tests, 13 OpenSpec specs, 12 vulnerabilities fixed in adversarial review

---

## 🛠️ Tech Stack / 技术栈

| 方向 / Area | 技术 / Tech |
| --- | --- |
| 桌面 / 前端 · Desktop / Frontend | TypeScript · Electron · electron-vite · HTML / CSS |
| 后端 · Backend | Python · FastAPI · Node.js |
| AI / Agent | LangGraph · RAG · Milvus · DeepSeek API · Ollama |
| AI 编程方法论 · AI Coding | OpenSpec · grill-me · Pipeline · Ponytail · Codex Plugin |
| 数据 / 存储 · Data & Storage | PostgreSQL · Redis · SQLite |
| 工程化 · Engineering | Docker · Kubernetes · GitHub Actions |

---

## 📬 Contact / 联系我

对桌宠、AI Agent、AI 编程或者任何有趣的工程话题感兴趣，欢迎找我聊。
Interested in desktop pets, AI agents, AI-assisted coding, or any fun engineering topic? Let's talk.

- 📧 **Email**: [zzk26personal@163.com](mailto:zzk26personal@163.com)
- 🐙 **GitHub**: [@zhenkun26](https://github.com/zhenkun26)

---

<sub>代码可以很正经，也可以很好玩。 / Code can be serious — and fun too.</sub>
