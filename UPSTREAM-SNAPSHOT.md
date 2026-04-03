# Upstream Snapshot — paperclip

- source repo: `https://github.com/paperclipai/paperclip.git`
- previous synced commit: `056a5ee32a1aac43474030c78b5815cda2c8a79a`
- current synced commit: `36049beeeacc54a79993aac05b8ae1dcf8ea580c`
- sync mode: `update`
- impact labels: README/소개, 설치/설정, CLI/명령어, 문서 구조, 소스코드
- guide repo: `paperclip-guide`

## 원본 한줄 요약

Quickstart &middot; Docs &middot; GitHub &middot;

## recent upstream commits

- `36049bee Merge pull request #2552 from paperclipai/PAPA-42-add-model-used-to-pr-template-and-checklist`
- `c041fee6 feat: add Model Used section to PR template and checklist`
- `82290451 Merge pull request #2541 from paperclipai/pap-1078-qol-fixes`
- `fb3b57ab merge master into pap-1078-qol-fixes`
- `ca8d35fd Merge pull request #2540 from paperclipai/pap-1078-inbox-operator-polish`
- `81a7f79d Merge pull request #2539 from paperclipai/pap-1078-workspaces-routines`
- `ad1ef6a8 fix(ui): address final Greptile follow-up`
- `833842b3 fix(inbox): address Greptile review findings`

## top-level structure

- `.agents/`
- `.claude/`
- `.dockerignore`
- `.env.example`
- `.mailmap`
- `.npmrc`
- `AGENTS.md`
- `cli/`
- `CONTRIBUTING.md`
- `doc/`
- `docker/`
- `Dockerfile`
- `docs/`
- `evals/`
- `LICENSE`
- `package.json`
- `packages/`
- `patches/`
- `pnpm-lock.yaml`
- `pnpm-workspace.yaml`

## changed files

- `.github/CODEOWNERS`
- `.github/PULL_REQUEST_TEMPLATE.md`
- `.gitignore`
- `README.md`
- `cli/src/__tests__/allowed-hostname.test.ts`
- `cli/src/__tests__/company-delete.test.ts`
- `cli/src/__tests__/company-import-url.test.ts`
- `cli/src/__tests__/company.test.ts`
- `cli/src/__tests__/doctor.test.ts`
- `cli/src/__tests__/feedback.test.ts`
- `cli/src/__tests__/onboard.test.ts`
- `cli/src/__tests__/routines.test.ts`
- `cli/src/__tests__/telemetry.test.ts`
- `cli/src/__tests__/worktree.test.ts`
- `cli/src/commands/client/company.ts`
- `cli/src/commands/client/feedback.ts`
- `cli/src/commands/client/issue.ts`
- `cli/src/commands/configure.ts`
- `cli/src/commands/onboard.ts`
- `cli/src/commands/routines.ts`

## README excerpt

```md
<p align="center">
  <img src="doc/assets/header.png" alt="Paperclip — runs your business" width="720" />
</p>

<p align="center">
  <a href="#quickstart"><strong>Quickstart</strong></a> &middot;
  <a href="https://paperclip.ing/docs"><strong>Docs</strong></a> &middot;
  <a href="https://github.com/paperclipai/paperclip"><strong>GitHub</strong></a> &middot;
  <a href="https://discord.gg/m4HZY7xNG3"><strong>Discord</strong></a>
</p>

<p align="center">
  <a href="https://github.com/paperclipai/paperclip/blob/master/LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue" alt="MIT License" /></a>
  <a href="https://github.com/paperclipai/paperclip/stargazers"><img src="https://img.shields.io/github/stars/paperclipai/paperclip?style=flat" alt="Stars" /></a>
  <a href="https://discord.gg/m4HZY7xNG3"><img src="https://img.shields.io/discord/000000000?label=discord" alt="Discord" /></a>
</p>

<br/>

<div align="center">
  <video src="https://github.com/user-attachments/assets/773bdfb2-6d1e-4e30-8c5f-3487d5b70c8f" width="600" controls></video>
</div>

<br/>

## What is Paperclip?

# Open-source orchestration for zero-human companies

**If OpenClaw is an _employee_, Paperclip is the _company_**

Paperclip is a Node.js server and React UI that orchestrates a team of AI agents to run a business. Bring your own agents, assign goals, and track your agents' work and costs from one dashboard.

It looks like a task manager — but under the hood it has org charts, budgets, governance, goal alignment, and agent coordination.

**Manage business goals, not pull requests.**

|        | Step            | Example                                                            |
| ------ | --------------- | ------------------------------------------------------------------ |
| **01** | Define the goal | _"Build the #1 AI note-taking app to $1M MRR."_                    |
| **02** | Hire the team   | CEO, CTO, engineers, designers, marketers — any bot, any provider. |
| **03** | Approve and run | Review strategy. Set budgets. Hit go. Monitor from the dashboard.  |

<br/>

> **COMING SOON: Clipmart** — Download and run entire companies with one click. Browse pre-built company templates — full org structures, agent configs, and skills — and import them into your Paperclip instance in seconds.

<br/>

<div align="center">
<table>
  <tr>
    <td align="center"><strong>Works<br/>with</strong></td>
    <td align="center"><img src="doc/assets/logos/openclaw.svg" width="32" alt="OpenClaw" /><br/><sub>OpenClaw</sub></td>
    <td align="center"><img src="doc/assets/logos/claude.svg" width="32" alt="Claude" /><br/><sub>Claude Code</sub></td>
    <td align="center"><img src="doc/assets/logos/codex.svg" width="32" alt="Codex" /><br/><sub>Codex</sub></td>
    <td align="center"><img src="doc/assets/logos/cursor.svg" width="32" alt="Cursor" /><br/><sub>Cursor</sub></td>
    <td align="center"><img src="doc/assets/logos/bash.svg" width="32" alt="Bash" /><br/><sub>Bash</sub></td>
    <td align="center"><img src="doc/assets/logos/http.svg" width="32" alt="HTTP" /><br/><sub>HTTP</sub></td>
  </tr>
</table>

<em>If it can receive a heartbeat, it's hired.</em>

</div>

<br/>

## Paperclip is right for you if

- ✅ You want to build **autonomous AI companies**
- ✅ You **coordinate many different agents** (OpenClaw, Codex, Claude, Cursor) toward a common goal
- ✅ You have **20 simultaneous Claude Code terminals** open and lose track of what everyone is doing
- ✅ You want agents running **autonomously 24/7**, but still want to audit work and chime in when needed
- ✅ You want to **monitor costs** and enforce budgets
- ✅ You want a process for managing agents that **feels like using a task manager**
- ✅ You want to manage your autonomous businesses **from your phone**

<br/>

## Features

<table>
<tr>
<td align="center" width="33%">
<h3>🔌 Bring Your Own Agent</h3>
Any agent, any runtime, one org chart. If it can receive a heartbeat, it's hired.
</td>
<td align="center" width="33%">
<h3>🎯 Goal Alignment</h3>
Every task traces back to the company mission. Agents know <em>what</em> to do and <em>why</em>.
</td>
<td align="center" width="33%">
<h3>💓 Heartbeats</h3>
Agents wake on a schedule, check work, and act. Delegation flows up and down the org chart.
</td>
</tr>
<tr>
<td align="center">
<h3>💰 Cost Control</h3>
Monthly budgets per agent. When they hit the limit, they stop. No runaway costs.
</td>
<td align="center">
<h3>🏢 Multi-Company</h3>
One deployment, many companies. Complete data isolation. One control plane for your portfolio.
</td>
<td align="center">
<h3>🎫 Ticket System</h3>
Every conversation traced. Every decision explained. Full tool-call tracing and immutable audit log.
</td>
</tr>
<tr>
<td align="center">
<h3>🛡️ Governance</h3>
You're the board. Approve hires, override strategy, pause or terminate any agent — at any time.
</td>
<td align="center">
<h3>📊 Org Chart</h3>
Hierarchies, roles, reporting lines. Your agents have a boss, a title, and a job description.
</td>
```
