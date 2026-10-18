<div align="center">

[English](README.md) · [**简体中文**](README.zh-CN.md) · [日本語](README.ja.md)

# Hi, I'm XY 👋

### AI Application Builder · Agent Workflow Explorer · Cybersecurity Researcher

把 AI 从「会回答」做成「能行动、可验证、可回退」的应用。

[![GitHub](https://img.shields.io/badge/GitHub-XY--code1-181717?style=flat-square&logo=github)](https://github.com/XY-code1)
[![Email](https://img.shields.io/badge/Email-xyuzzz123456%40gmail.com-4A90E2?style=flat-square&logo=gmail&logoColor=white)](mailto:xyuzzz123456@gmail.com)
[![小红书](https://img.shields.io/badge/小红书-@XY-FF2442?style=flat-square&logo=xiaohongshu&logoColor=white)](https://www.xiaohongshu.com/user/profile/6a63c2420000000013031400)

</div>

---

## About me

我是 **AI 独立开发者**，关注 **AI 应用开发、LLM、AI Agents、RAG** 与 **AI 安全探索**。

我喜欢把模糊想法拆成可运行的产品流程：理解输入、规划行动、保留人工控制、执行变更，再用真实结果完成验证。现在正持续补强工程基础，也乐于通过 Hackathon 与开源协作，把学习变成可见、可复用的作品。

- 🔭 正在构建可靠、可解释、可验证的 AI Agent 应用
- 🧠 正在深入 LLM / RAG / Agent workflow 与 AI 安全
- 🌱 正在探索 Rust，并持续夯实前端与工程化能力
- 🤝 期待参与 AI 应用、开发者工具与用户体验相关的开源项目

## Tech & Tools

> 按实际熟练度分类；持续更新，而不是堆砌关键词。

| 方向 | 技术与工具 |
| --- | --- |
| **主要语言** | Python |
| **应用开发基础** | React · Vite · TypeScript / JavaScript |
| **课程与工程基础** | Java · C |
| **正在探索** | Rust |
| **AI 方向** | LLM Applications · AI Agents · RAG · Human-in-the-loop · AI Security |
| **工程协作** | Git · GitHub · Pull Requests · CI |

## Featured Work

### 🛡️ [Schedule Guardian / Plan Guardian](https://github.com/XY-code1/plan-guardian)

面向日程冲突的 **Human-in-the-loop Agent**。它理解自然语言改期请求，检测时间冲突，提出可行方案，并且只在用户明确批准后执行；写入后重新读取状态，验证操作是否真正完成。

`conflict detection` → `plan` → `approve / reject` → `execute` → `reread & verify`

**我关注的工程问题：** 人工审批边界、计划与版本绑定、失败关闭、拒绝路径不写入，以及执行后的结果验证。

---

### 🎵 AI 同屏助手 / 同频现场

腾讯音乐 Hackathon 项目，围绕音乐兴趣匹配、AI 破冰与沉浸式社交界面展开：让共同的音乐偏好成为真实交流的起点。

**关键词：** `music-interest matching` · `AI icebreaking` · `immersive social UI`

> 项目仓库暂未公开，因此这里不放置仓库链接。

## Open Source

我关注 Agent 基础设施、运行时可靠性与开源供应链安全。以下仅展示可在 GitHub 公开核验的代表性贡献，并明确区分已合并与仍在 review 的工作。

### 🦌 [ByteDance DeerFlow · PR #6894](https://github.com/bytedance/deer-flow/pull/6894) · **Merged**

修复 run event 时间戳写入 SQLite 后丢失时区偏移的问题：在三个数据库写入路径统一转换为 UTC，保证带 offset 的时间戳持久化前后仍表示同一时刻，并补充真实 SQLite 回归测试。

`Python` · `SQLite` · `runtime persistence` · `timezone correctness`

### 🛡️ [OpenSSF Scorecard · PR #5339](https://github.com/ossf/scorecard/pull/5339) · **Open**

修复 GitLab Code-Review 分析使用无序 commit 列表首项作为查询时间边界的问题；改为计算最新有效提交时间，同时保持原有提交顺序与兼容行为。

`Go` · `GitLab API` · `open-source security` · `regression tests`

### 🧠 [TencentDB Agent Memory · PR #1717](https://github.com/TencentCloud/TencentDB-Agent-Memory/pull/1717) · **Open**

修复 L2 memory extraction 失败被误判为“无数据成功”的问题，让结构化失败进入既有 worker 重试路径，同时保留合法的零工作量流程。

`TypeScript` · `AI memory pipeline` · `failure propagation` · `retry semantics`

### 🔎 [Tencent BrowserSkill · PR #457](https://github.com/Tencent/BrowserSkill/pull/457) · **Open**

针对 [Issue #386](https://github.com/Tencent/BrowserSkill/issues/386) 增强 session idle 可观测性：暴露剩余 idle 生命周期，并保留结构化 timeout reason，避免会话回收后只看到模糊的状态丢失。

`Rust` · `browser automation` · `session lifecycle` · `observability`

## What I Care About

```text
Useful AI      > impressive demos only
Verified state > optimistic success messages
Human control  > silent automation
Clear evidence > vague claims
```

## Let's Connect

- GitHub: [@XY-code1](https://github.com/XY-code1)
- Email: [xyuzzz123456@gmail.com](mailto:xyuzzz123456@gmail.com)
- 小红书: [个人主页](https://www.xiaohongshu.com/user/profile/6a63c2420000000013031400)

<div align="center">

_Keep building. Keep verifying. Stay curious._

</div>

<!--
Profile README publishing notes:
1. Create a public repository named exactly `XY-code1` under the XY-code1 account.
2. Put `README.md`, `README.zh-CN.md`, and `README.ja.md` at the repository root.
3. Before publishing, recheck contribution statuses and replace “待合并” only after the upstream repository records a merge.
4. Suggested commit:
   git add README.md README.zh-CN.md README.ja.md
   git commit -m "docs: add multilingual GitHub profile README"
   git push origin main
-->
