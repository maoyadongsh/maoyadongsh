<p align="center">
  <img src="assets/profile-header.svg" width="960" alt="maoyadongsh · Building bounded, verifiable Agent systems" />
</p>

<p align="center"><strong>Building bounded, verifiable Agent systems.</strong></p>

<p align="center">
  <a href="README.md">简体中文</a> · <strong>English</strong>
</p>

<p align="center">
  <a href="#currently-building">Currently building</a> · <a href="#areas-of-focus">Areas of focus</a> · <a href="https://github.com/maoyadongsh/siq-agent-security/discussions">Discussion</a>
</p>

I'm building **[SIQ Agent Security](https://github.com/maoyadongsh/siq-agent-security)**, exploring how Agents with tool capabilities can operate within explicit authority, retain parameter provenance, and verify whether tasks have actually completed.

## Currently building

<a href="https://github.com/maoyadongsh/siq-agent-security">
  <img align="right" src="https://raw.githubusercontent.com/maoyadongsh/siq-agent-security/main/site/siq-shield.svg" width="80" height="80" alt="SIQ blue shield logo" />
</a>

### SIQ Agent Security

**Secure Runtime for Agent Skills**

> Agent Skills define what agents can do. SIQ defines what they are allowed to do.

Connect authorization, parameter provenance and effect verification to the execution path. Current engineering includes a local Go runtime, Agent tool adapters, signed receipts and reproducible fixed benchmarks.

[Project](https://github.com/maoyadongsh/siq-agent-security) · [Quick start](https://github.com/maoyadongsh/siq-agent-security/blob/main/README.en.md#quick-start) · [Source prerelease](https://github.com/maoyadongsh/siq-agent-security/releases/tag/research-v0.1.0-rc.1) · [Reproduction guide](https://github.com/maoyadongsh/siq-agent-security/blob/main/REPRODUCIBILITY.md)

## Areas of focus

| Area | Question |
| :--- | :--- |
| **Agent security** | Does a model-proposed action stay within the user's authority? |
| **Trusted execution** | Should identical parameter values from different sources receive the same permissions? |
| **Effect verification** | Does a successful tool response establish that the required effect occurred? |
| **Reproducible research** | Can a claim be traced to specific source code, cases, environments and verification records? |

Main technologies in the project: **Go · Python · TypeScript / React**.

## Get in touch

Conversations about Agent tool integrations, permission boundaries, reproduction results and failed attempts are welcome. Start in [SIQ Discussions](https://github.com/maoyadongsh/siq-agent-security/discussions), or choose a [community task](https://github.com/maoyadongsh/siq-agent-security/blob/main/docs/research/community-backlog.md).

For security issues, use the project's [private reporting channel](https://github.com/maoyadongsh/siq-agent-security/security/advisories/new).

---

<p align="center"><sub>Build with boundaries. Verify with evidence.</sub></p>
