<div align="center">

[**English**](README.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md)

# Hi, I'm XY 👋

### AI Application Builder · Agent Workflow Explorer · Cybersecurity Researcher

I turn AI from something that “answers” into applications that **act, verify, and recover**.

[![GitHub](https://img.shields.io/badge/GitHub-XY--code1-181717?style=flat-square&logo=github)](https://github.com/XY-code1)
[![Email](https://img.shields.io/badge/Email-xyuzzz123456%40gmail.com-4A90E2?style=flat-square&logo=gmail&logoColor=white)](mailto:xyuzzz123456@gmail.com)
[![Xiaohongshu](https://img.shields.io/badge/Xiaohongshu-@XY-FF2442?style=flat-square&logo=xiaohongshu&logoColor=white)](https://www.xiaohongshu.com/user/profile/6a63c2420000000013031400)

</div>

---

## About Me

I am an **independent AI developer** focused on **AI application development, LLMs, AI Agents, RAG**, and **AI security research**.

I enjoy turning ambiguous ideas into working product flows: understand the input, plan an action, preserve human control, execute the change, and verify the result against real state. I keep strengthening my engineering fundamentals and turn what I learn into visible, reusable work through hackathons and open-source collaboration.

- 🔭 Building reliable, explainable, and verifiable AI Agent applications
- 🧠 Going deeper into LLMs, RAG, agent workflows, and AI security
- 🌱 Exploring Rust while improving frontend and software-engineering fundamentals
- 🤝 Open to contributing to AI applications, developer tools, and user-experience projects

## Tech & Tools

> Grouped by real experience—not by the number of keywords I can list.

| Area | Technologies & Tools |
| --- | --- |
| **Primary language** | Python |
| **Application development** | React · Vite · TypeScript / JavaScript |
| **Programming foundations** | Java · C |
| **Currently exploring** | Rust |
| **AI** | LLM Applications · AI Agents · RAG · Human-in-the-loop · AI Security |
| **Engineering workflow** | Git · GitHub · Pull Requests · CI |

## Featured Work

### 🛡️ [Schedule Guardian / Plan Guardian](https://github.com/XY-code1/plan-guardian)

A **human-in-the-loop agent** for schedule conflicts. It understands natural-language rescheduling requests, detects time conflicts, proposes feasible alternatives, and executes only after explicit user approval. After writing a change, it rereads the state to verify that the operation actually succeeded.

`conflict detection` → `plan` → `approve / reject` → `execute` → `reread & verify`

**Engineering concerns:** approval boundaries, plan/version binding, fail-closed behavior, no writes on rejection, and post-execution verification.

---

### 🎵 AI Co-Screen Assistant / In-Sync Live

A Tencent Music Hackathon project centered on music-interest matching, AI-assisted icebreaking, and an immersive social interface—using shared music tastes as a starting point for genuine interaction.

**Keywords:** `music-interest matching` · `AI icebreaking` · `immersive social UI`

> The repository is not public, so no repository link is provided.

## Open Source

I contribute around agent infrastructure, runtime reliability, and open-source supply-chain security. The representative contributions below are publicly verifiable on GitHub, with merged and in-review work clearly distinguished.

### 🦌 [ByteDance DeerFlow · PR #6894](https://github.com/bytedance/deer-flow/pull/6894) · **Merged**

Fixed timezone offsets being lost when run-event timestamps were persisted to SQLite. The change normalizes timestamps to UTC across all three database write paths, preserving the same instant after a round trip, with regression tests against real SQLite databases.

`Python` · `SQLite` · `runtime persistence` · `timezone correctness`

### 🛡️ [OpenSSF Scorecard · PR #5339](https://github.com/ossf/scorecard/pull/5339) · **Open**

Fixed GitLab Code-Review analysis using the first item of an unordered commit list as its query-time boundary. The change computes the latest valid commit date while preserving commit order and existing compatibility behavior.

`Go` · `GitLab API` · `open-source security` · `regression tests`

### 🧠 [TencentDB Agent Memory · PR #1717](https://github.com/TencentCloud/TencentDB-Agent-Memory/pull/1717) · **Open**

Fixed failed L2 memory extraction being treated as a successful no-data run. Structured failures now reach the worker's existing retry path, while legitimate zero-work outcomes retain their original behavior.

`TypeScript` · `AI memory pipeline` · `failure propagation` · `retry semantics`

### 🔎 [Tencent BrowserSkill · PR #457](https://github.com/Tencent/BrowserSkill/pull/457) · **Open**

Improved session-idle observability for [Issue #386](https://github.com/Tencent/BrowserSkill/issues/386): exposes estimated idle lifetime and preserves a structured timeout reason, making session reclamation diagnosable instead of appearing as unexplained state loss.

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
- Xiaohongshu: [Profile](https://www.xiaohongshu.com/user/profile/6a63c2420000000013031400)

<div align="center">

_Keep building. Keep verifying. Stay curious._

</div>

<!--
Profile README publishing notes:
1. Create a public repository named exactly `XY-code1` under the XY-code1 account.
2. Put README.md, README.zh-CN.md, and README.ja.md in the repository root.
3. Recheck contribution statuses before publishing; describe a PR as merged only when the upstream repository records a merge.
4. Suggested commit:
   git add README.md README.zh-CN.md README.ja.md
   git commit -m "docs: add multilingual GitHub profile README"
   git push origin main
-->
