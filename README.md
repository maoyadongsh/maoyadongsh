<p align="center">
  <img src="assets/profile-header.svg" width="960" alt="maoyadongsh · 构建有边界、可验证的 Agent 系统" />
</p>

<p align="center"><strong>构建有边界、可验证的 Agent 系统。</strong></p>

<p align="center">
  <strong>简体中文</strong> · <a href="README.en.md">English</a>
</p>

<p align="center">
  <a href="#正在构建">正在构建</a> · <a href="#关注方向">关注方向</a> · <a href="https://github.com/maoyadongsh/siq-agent-security/discussions">交流与讨论</a>
</p>

我正在构建 **[SIQ Agent Security](https://github.com/maoyadongsh/siq-agent-security)**，探索 Agent 在获得工具能力之后，如何明确执行权限、保留来源依据，并验证任务是否真正完成。

## 正在构建

<a href="https://github.com/maoyadongsh/siq-agent-security">
  <img align="right" src="https://raw.githubusercontent.com/maoyadongsh/siq-agent-security/main/site/siq-shield.svg" width="80" height="80" alt="SIQ 蓝色盾牌标识" />
</a>

### SIQ Agent Security

**Secure Runtime for Agent Skills**

面向 Agent Skills 的可信执行安全运行时

> Skills 给 Agent 能力，SIQ 给能力边界。

将授权检查、参数来源和效果核验连接到执行链路。现有工程包括本地 Go 运行时、Agent 工具适配器、签名回执与可复现的固定基准。

[项目首页](https://github.com/maoyadongsh/siq-agent-security) · [快速体验](https://github.com/maoyadongsh/siq-agent-security#快速开始) · [源码预发布](https://github.com/maoyadongsh/siq-agent-security/releases/tag/research-v0.1.0-rc.1) · [复现指南](https://github.com/maoyadongsh/siq-agent-security/blob/main/REPRODUCIBILITY.md)

## 关注方向

| 方向 | 关注的问题 |
| :--- | :--- |
| **Agent 安全** | 模型提出的动作，是否在用户授权范围内？ |
| **可信执行** | 同一个参数值，来自不同来源时，是否应该得到相同权限？ |
| **效果核验** | 工具返回成功，是否意味着要求的效果已经发生？ |
| **可复现研究** | 结论能否回到具体源码、案例、运行环境和验证记录？ |

项目中的主要技术：**Go · Python · TypeScript / React**。

## 一起交流

欢迎交流 Agent 工具接入、权限边界、复现结果与失败案例。可以从 [SIQ Discussions](https://github.com/maoyadongsh/siq-agent-security/discussions) 开始，或选择一个[社区任务](https://github.com/maoyadongsh/siq-agent-security/blob/main/docs/research/community-backlog.md)。

安全问题请使用项目的[私密报告入口](https://github.com/maoyadongsh/siq-agent-security/security/advisories/new)。

---

<p align="center"><sub>Build with boundaries. Verify with evidence.</sub></p>
