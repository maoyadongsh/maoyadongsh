<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/profile-hero-dark.svg" />
  <img src="assets/profile-hero-light.svg" width="1000" alt="maoyadongsh · AI systems, built for work. 从智能体能力到业务系统。" />
</picture>

<p align="center"><strong>AI 应用与企业系统工程</strong><br />
让智能体能力进入真实业务，让系统运行有边界、结果有依据。</p>

<p align="center">
  <strong>简体中文</strong> · <a href="README.en.md">English</a><br />
  <a href="#工程版图">工程版图</a> · <a href="#开源作品">开源作品</a> · <a href="#技术与方法">技术与方法</a> · <a href="#交流">交流</a>
</p>

我的开发实践从 **投资研究与管理、公司治理、人才运营** 等业务场景出发，延伸到研究与知识系统、Agent 运行时与安全，以及可复用的企业平台服务。我关注业务模型、产品交互、数据证据、权限控制与工程验证之间的衔接。

## 工程版图

**业务应用 → 研究与知识 → 智能体系统 → 企业平台**

从用户工作流展开到支撑能力，涵盖独立应用与 SIQ 服务体系。公开项目提供源码入口；标注「私有」的项目对应私有仓库，仅展示功能概述与工程职责。

### 01 · 业务应用与决策

<sub>BUSINESS APPLICATIONS · 投资研究 / 投资管理 / 公司治理 / 人才运营</sub>

将领域模型、证据分析与人工决策组织为可操作的产品工作流。

| 项目与仓库 | 核心工作 | 状态 |
| :--- | :--- | :--- |
| **SIQ Investment · 投资管理**<br />`siq-investment` | 面向多 GP、基金与直投项目，组织募资、尽调、投委会、交割、投后与退出流程，关联资金事实、审批与审计。 | 私有 |
| **FinSight · 投研工作台**<br />`finsight` | 将财报获取、解析、研究报告、事实核查、持续跟踪与法务分析汇集到统一工作台，结合多角色智能体交互。 | 私有 |
| **集团化公司治理平台** | 围绕集团及成员企业的主体档案、股权关系、议案决议与治理文档，提供信息查询、证据追溯与智能分析。 | 私有 |
| **HRsight · 智能 HR**<br />`hrsight` | 面向集团与子公司的人才运营 MVP，整合人才看板、HR 工作台、报表、待办、制度问答与法务合规。 | 私有 |

### 02 · 研究与知识工程

<sub>KNOWLEDGE &amp; RESEARCH · 文档理解 / 事实组织 / 检索与记忆</sub>

从原始材料建立可引用的事实与知识，让研究过程、证据来源和上下文使用可追溯。

| 项目与仓库 | 核心工作 | 状态 |
| :--- | :--- | :--- |
| **SIQ Research Engine · 研究引擎**<br />`siq-research-engine` | 连接多市场官方披露、财报解析、LLM Wiki 证据组织、检索与多智能体研究，保留质量检查与人工签核环节。 | 私有 |
| **SIQ Document Engine · 文档引擎**<br />`siq-document-engine` | 将 PDF、Office 等材料转为版本化解析产物，提供质量检查、原文位置追溯、引用校验与检索能力。 | 私有 |
| **SIQ Memory · 授权记忆**<br />`siq-memory` | 管理跨会话的用户偏好、纠错与项目上下文，覆盖候选确认、按权限召回、保留与删除，以及检索回执。 | 私有 |

### 03 · 智能体运行与安全

<sub>AGENT SYSTEMS · 执行运行时 / 生命周期治理 / 授权与效果核验</sub>

分别处理智能体如何执行、如何上架与管理，以及工具动作依据什么授权、产生了什么效果。

| 项目与仓库 | 核心工作 | 状态 |
| :--- | :--- | :--- |
| **[SIQ Agent Security · 执行安全](https://github.com/maoyadongsh/siq-agent-security)**<br />`siq-agent-security` | 独立的 Agent Skills 安全运行时：核验授权与参数来源，关联签名回执和效果证据，提供公开案例与复现工具。 | **开源** |
| **SIQ Agent Hub · 智能体控制面**<br />`siq-agent-hub` | 管理智能体注册、版本化资产、评测上架、运行生命周期与会话台账，将数据策略与证据检查接入调用流程。 | 私有 |
| **Hermes Agent · SIQ 适配**<br />`hermes-agent` | 基于 Nous Research 的 [Hermes Agent](https://github.com/NousResearch/hermes-agent) 维护 SIQ 适配，聚焦运行状态目录隔离、工具白名单与平台接入。 | 私有 |

### 04 · 企业平台与协作基础

<sub>ENTERPRISE PLATFORM · 身份与权限 / 流程与协作 / 模型治理 / 部署交付</sub>

围绕明确的服务边界，连接身份、流程、交互、消息与部署，使业务应用能够复用平台能力。

| 项目与仓库 | 核心工作 | 状态 |
| :--- | :--- | :--- |
| **SIQ Org IAM · 身份与组织**<br />`siq-org-iam` | 统一用户、组织、岗位、角色与数据权限，管理登录会话、服务身份和委托授权。 | 私有 |
| **SIQ Flow Engine · 流程引擎**<br />`siq-flow-engine` | 以版本化流程定义组织审批、条件分支与任务编排；智能体提供顾问意见，由人工审批人决策。 | 私有 |
| **SIQ Gateway · 网关与模型治理**<br />`siq-gateway` | 汇集业务 API 与模型调用入口，管理模型访问、用量、配额、熔断与流式请求。 | 私有 |
| **SIQ Workbench · 统一工作台**<br />`siq-workbench` | 提供动态表单、流程设计、待办审批、智能体问答与管理界面，沉淀可复用的表单和 UI 组件。 | 私有 |
| **SIQ Notify · 消息触达**<br />`siq-notify` | 将流程与业务事件转为通知，管理接收人解析、渠道投递、失败重试与死信回放。 | 私有 |
| **SIQ Platform · 部署与集成**<br />`siq-platform` | 固化多服务部署拓扑、环境初始化、数据库迁移、健康检查与集成验收，维护 SIQ 全栈运行基线。 | 私有 |

## 开源作品

<img align="right" src="https://raw.githubusercontent.com/maoyadongsh/siq-agent-security/main/site/siq-shield.svg" width="72" height="72" alt="SIQ 蓝色盾牌标识" />

### [SIQ Agent Security](https://github.com/maoyadongsh/siq-agent-security)

**Secure Runtime for Agent Skills**

> Skills 给 Agent 能力，SIQ 给能力边界。

本地 Go 运行时、工具适配器、来源约束、签名回执与效果核验。公开提供源码预发布、固定控制案例和复现指南，便于检查具体实现与结论依据。

[阅读项目](https://github.com/maoyadongsh/siq-agent-security) · [快速体验](https://github.com/maoyadongsh/siq-agent-security#快速开始) · [复现指南](https://github.com/maoyadongsh/siq-agent-security/blob/main/REPRODUCIBILITY.md) · [源码预发布](https://github.com/maoyadongsh/siq-agent-security/releases/tag/research-v0.1.0-rc.1)

## 技术与方法

| 工程层次 | 实践技术 |
| :--- | :--- |
| 运行时与服务 | Go · Python · FastAPI · 版本化 API |
| 产品与交互 | TypeScript · React · Vite |
| 数据与知识 | PostgreSQL · Redis · Milvus · 对象存储 |
| 运行与交付 | Docker Compose · 本地模型服务 · CI · 契约与回归验证 |

**我的工程关注点：** 清晰的业务与服务边界、可追溯的数据与判断、可恢复的执行流程，以及能被复核的测试与交付记录。AI 辅助开发也需要设计、实现、审查和回归形成闭环。

**Vibe Coding Prompt Library** · `vibecoding-prompts` · **私有仓库**<br />
将 AI 辅助开发方法沉淀为可复用提示词：覆盖需求与领域设计、架构与交付计划、增量实现、维护恢复、对抗审查和回归验收，以文档与验证记录衔接不同开发阶段。

## 交流

欢迎交流 **企业 AI 应用、Agent 基础设施、知识与研究系统、工程验证方法**。围绕公开项目的技术讨论与复现反馈，可以从 [SIQ Discussions](https://github.com/maoyadongsh/siq-agent-security/discussions) 开始，或选择一个[社区任务](https://github.com/maoyadongsh/siq-agent-security/blob/main/docs/research/community-backlog.md)。安全问题请走[私密报告入口](https://github.com/maoyadongsh/siq-agent-security/security/advisories/new)。

---

<p align="center"><sub>Clear boundaries. Traceable evidence. Useful systems.</sub></p>
