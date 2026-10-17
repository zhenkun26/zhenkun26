# Hi, I'm Zhenkun

**AI 应用开发 · Python 后端**

我用 Python 构建能查资料、处理业务请求的 AI 应用，关注三件事：**回答有来源、操作有边界、结果可验证**。

## 我能带来什么

- **把需求做成应用**：从使用界面到后端服务，打通数据、模型与交互流程。
- **让 AI 有据可查**：为回答保留资料来源，为操作加入权限检查与人工审批。
- **把异常处理做进去**：通过输出校验、失败处理和自动化测试，检查正常与异常路径。

主要使用 **Python / FastAPI、TypeScript / Vue、LangGraph、Docker**。

## 精选项目

### [BusinessAgent · 智多星](https://github.com/zhenkun26/BusinessAgent) — 企业业务助手

将查制度、分析数据和执行业务操作放进同一个对话流程。重点实现**权限检查、人工审批和多步骤失败补偿**。当前以模拟业务工具和样例数据演示，真实系统接入与生产验收仍待完成。

[工作流实现](https://github.com/zhenkun26/BusinessAgent/tree/main/enterprise-agent/app/graph) · [自动化测试](https://github.com/zhenkun26/BusinessAgent/tree/main/enterprise-agent/tests)

### [Insight · 洞察者](https://github.com/zhenkun26/Insight) — 本地文档问答

把气象业务资料整理成可检索的知识库，回答附带文件名及可用的页码或章节。重点是结合关键词与语义检索，**没有片段通过证据阈值时明确拒答**，并保留检索失败时的降级路径。

[检索实现](https://github.com/zhenkun26/Insight/tree/main/app/retrieval) · [自动化测试](https://github.com/zhenkun26/Insight/tree/main/tests)

### [TripMate](https://github.com/zhenkun26/TripMate) — 智能旅行助手

根据目的地、日期和偏好，生成包含每日安排、预算估算、天气与地图的行程。重点是**用高德候选数据约束生成结果**，校验景点、酒店与日期，并由后端重新计算预算。

[行程生成与校验](https://github.com/zhenkun26/TripMate/blob/main/backend/app/agents/planner_agent.py) · [自动化测试](https://github.com/zhenkun26/TripMate/tree/main/backend/tests)

### [RepoAtlas · 代码星图](https://github.com/zhenkun26/dsh-repo-atlas) — 代码库理解工具

为 DeepSeek Harness 编码助手提供仓库分析、源码证据搜索和潜在影响查询。**默认只读**，结论保留文件依据与分析范围；当前版本仍处于实验验证阶段。

[插件实现](https://github.com/zhenkun26/dsh-repo-atlas/blob/main/src/harness/plugin.ts) · [测试与兼容性检查](https://github.com/zhenkun26/dsh-repo-atlas/actions)

## 更多探索与联系

我也在整理 [AI 编码交付方法](https://github.com/zhenkun26/auto-coding)，并在[个人博客](https://zhenkun26.github.io/Zhenkun-blog-site/)记录学习与项目实践。

关注 **AI 应用工程 / Python 后端开发**相关机会，欢迎交流或合作。

[Email](mailto:zzk26personal@163.com) · [全部公开仓库](https://github.com/zhenkun26?tab=repositories)

---

<details>
<summary>English</summary>

## About me

I build AI applications and Python backends, with a focus on **answers with sources, controlled actions, and verifiable results**.

- **Application development:** connect interfaces, backend services, data, and models.
- **Grounded AI:** preserve source references and add permission checks and human approval to actions.
- **Failure handling:** validate model output and test both normal and failure paths.

Primary tools: **Python / FastAPI, TypeScript / Vue, LangGraph, Docker**.

## Selected projects

- **[BusinessAgent](https://github.com/zhenkun26/BusinessAgent):** enterprise knowledge Q&A, data analysis, and business operations in one conversation workflow, with permission checks, approvals, and failure compensation. It currently demonstrates mock tools and sample data; real integrations and production acceptance remain pending.
- **[Insight](https://github.com/zhenkun26/Insight):** local document search and Q&A for meteorological materials. Combines keyword and semantic retrieval, returns source references, refuses when no passage passes the evidence threshold, and handles retrieval failures.
- **[TripMate](https://github.com/zhenkun26/TripMate):** travel planning with daily itineraries, budget estimates, weather, and maps. Validates generated plans against Amap candidates and recalculates budgets in the backend.
- **[RepoAtlas](https://github.com/zhenkun26/dsh-repo-atlas):** repository analysis, source evidence search, and potential impact queries for DeepSeek Harness. Read-only by default, with explicit analysis limits; the current version remains experimental.

## More & contact

I also maintain [AI coding delivery guidance](https://github.com/zhenkun26/auto-coding) and write about learning and project work on my [blog](https://zhenkun26.github.io/Zhenkun-blog-site/).

Open to **AI application engineering / Python backend development** opportunities and collaboration.

[Email](mailto:zzk26personal@163.com) · [Public repositories](https://github.com/zhenkun26?tab=repositories)

</details>
