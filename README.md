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

我的开发实践覆盖 **Agent 运行时与安全、企业平台、知识与研究系统，以及面向业务的 AI 应用**。我关注从业务建模、服务边界和交互设计，到数据证据、权限控制与工程验证的完整链路。

## 工程版图

<table>
<tr>
<td width="50%" valign="top">
<p><sub>01 / AGENT SYSTEMS</sub></p>
<h3>智能体与安全</h3>
<p>围绕工具调用构建授权、来源与效果证据，让 Agent 行动可约束、可核验。</p>
<p><strong>运行时接入 · 权限边界 · 效果核验</strong></p>
<p><a href="https://github.com/maoyadongsh/siq-agent-security">公开作品：SIQ Agent Security →</a></p>
</td>
<td width="50%" valign="top">
<p><sub>02 / ENTERPRISE PLATFORMS</sub></p>
<h3>企业平台与流程</h3>
<p>连接身份权限、人工审批、模型治理与统一工作台，组织可协作的企业服务。</p>
<p><strong>身份与授权 · 流程编排 · 服务治理</strong></p>
<p><sub>私有研发实践 · 能力概述</sub></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<p><sub>03 / KNOWLEDGE &amp; RESEARCH</sub></p>
<h3>知识与智能研究</h3>
<p>从文档与结构化证据出发，连接知识检索与多智能体分析，让研究结论可追溯。</p>
<p><strong>文档理解 · 证据溯源 · 研究工作流</strong></p>
<p><sub>私有研发实践 · 能力概述</sub></p>
</td>
<td width="50%" valign="top">
<p><sub>04 / BUSINESS APPLICATIONS</sub></p>
<h3>业务应用与决策</h3>
<p>面向投资研究与管理、公司治理、人才运营，把领域模型、审批和分析嵌入用户工作流。</p>
<p><strong>业务建模 · 决策支持 · 产品交互</strong></p>
<p><sub>私有研发实践 · 能力概述</sub></p>
</td>
</tr>
</table>

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

## 交流

欢迎交流 **企业 AI 应用、Agent 基础设施、知识与研究系统、工程验证方法**。围绕公开项目的技术讨论与复现反馈，可以从 [SIQ Discussions](https://github.com/maoyadongsh/siq-agent-security/discussions) 开始，或选择一个[社区任务](https://github.com/maoyadongsh/siq-agent-security/blob/main/docs/research/community-backlog.md)。安全问题请走[私密报告入口](https://github.com/maoyadongsh/siq-agent-security/security/advisories/new)。

---

<p align="center"><sub>Clear boundaries. Traceable evidence. Useful systems.</sub></p>
