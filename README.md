# Hi, I'm zhenkun 👋

一个喜欢把想法做成完整产品的开发者。

我做的项目横跨两个看似很远的方向：**桌面端的小而美**和**企业级的重而稳**。前者让我理解交互与陪伴，后者让我理解系统与边界。

---

## 🚀 Projects

### 🐱 [二次元桌宠 · Desktop-pet](https://github.com/zhenkun26/Desktop-pet)

一个 Electron 二次元桌宠应用：透明置顶窗口、拖拽互动、AI 角色对话、休息提醒与番茄钟，并预留多角色扩展框架（当前内置胡桃）。

- Electron 39 + TypeScript 5.7，electron-vite 三端构建
- DeepSeek 驱动的流式对话（SSE + 会话历史 + 角色设定 + 监听器级故障隔离）
- API Key 使用系统钥匙串级加密存储；HTTP 超时与输入参数校验等生产级加固
- 多角色框架：`pet-registry` 注册表 + petId 全链路隔离，新增桌宠仅需登记素材与人设
- 完整工程化：CI（typecheck + test + gitleaks）、81 项单元测试、OpenSpec 变更管理、多阶段 Docker 镜像（23MB）、K8s 参考清单、macOS 打包发版

### 🤖 [BusinessAgent · 企业知识工作流 Agent](https://github.com/zhenkun26/BusinessAgent)

企业级多 Agent 系统：员工用自然语言完成**知识问答、数据分析、业务执行**。

- 知识问答：RAG 两阶段检索（Milvus 粗排 + BGE 精排）+ 三级降级链，拒答优于编造
- 数据分析：LLM 规划 + Python 真实聚合，不编造数字
- 业务执行：RBAC 权限双闸 + 审批闭环 + Saga 补偿
- FastAPI + LangGraph + Milvus + PostgreSQL + Redis，支持 Docker / K8s 部署
- 58 项单元测试全绿，GitHub Actions 自动测试与构建镜像

---

## 🛠️ Tech Stack

| 方向 | 技术 |
| --- | --- |
| 桌面 / 前端 | TypeScript · Electron · electron-vite · HTML / CSS |
| 后端 | Python · FastAPI · Node.js |
| AI / Agent | LangGraph · RAG · Milvus · DeepSeek API · Ollama |
| 数据 / 存储 | PostgreSQL · Redis · SQLite |
| 工程化 | Docker · Kubernetes · GitHub Actions · OpenSpec |

---

## 📬 Contact

对桌宠、AI Agent 或者任何有趣的工程话题感兴趣，欢迎找我聊：

- 📧 **Email**: [zzk26personal@163.com](mailto:zzk26personal@163.com)
- 🐙 **GitHub**: [@zhenkun26](https://github.com/zhenkun26)

---

<sub>代码可以很正经，也可以很好玩。</sub>
