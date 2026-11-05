<div align="center">
  <img src="https://raw.githubusercontent.com/Walternater/Walternater/main/banner.svg" alt="Wang Chongfei — agent-assisted, human-accountable" width="100%"/>
</div>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=500&size=22&duration=2800&pause=900&color=A78BFA&center=true&vCenter=true&width=720&lines=AI+writes+the+code.;I+read+every+line.;Agents+do+the+busywork.;Humans+do+the+judging." alt="typing"/>
</div>

<div align="center">
  <img src="https://img.shields.io/badge/Software-Engineer-39d0d8?style=flat-square&labelColor=0d1117" alt=""/>
  <img src="https://img.shields.io/badge/Agent--assisted-OSS-a78bfa?style=flat-square&labelColor=0d1117" alt=""/>
  <img src="https://img.shields.io/badge/Every%20diff-reviewed-39d0d8?style=flat-square&labelColor=0d1117" alt=""/>
  <img src="https://img.shields.io/badge/Accountability-human-a78bfa?style=flat-square&labelColor=0d1117" alt=""/>
</div>

<br/>

Software engineer. This README documents how this account works, so that
maintainers and reviewers know exactly what to expect from my pull requests.

## ⚙️ How contributions here are made

I work with AI coding agents (agent-assisted workflow). The division of labor:

1. **🧭 I** choose the problem, the repository, and the scope.
2. **🤖 The agent** investigates the codebase, reads issues and docs, implements a
   candidate fix, and runs the test suite.
3. **👀 I** review every line of the resulting diff, reproduce the verification
   myself, and only then open the PR.
4. **✍️ I** take full responsibility for everything submitted under this account.

The agent never opens, updates, or merges a PR on its own. Every submission
passes through my review first.

## 🧱 Operating principles

<table>
<tr>
<td width="33%" valign="top">

**👤 Human accountable**

I can explain what every change does and how it interacts with the rest of the
system, without asking the AI.

</td>
<td width="33%" valign="top">

**📣 Disclosure**

Every PR states that it was prepared with AI assistance, naming the tool.

</td>
<td width="33%" valign="top">

**🧩 Small & reviewable**

Small diffs, one problem per PR, tests included, low cadence.

</td>
</tr>
<tr>
<td width="33%" valign="top">

**📜 Respect upstream rules**

Contribution guides, issue-first workflows, CLA/DCO — checked before code.

</td>
<td width="33%" valign="top">

**🚫 No benchmark gaming**

Evaluation harnesses are never modified; results only via official channels.

</td>
<td width="33%" valign="top">

**🤐 No marketing**

PRs carry no product or brand promotion.

</td>
</tr>
</table>

<!-- merged-prs:start -->
## 📊 Merged open-source contributions

**72** merged pull requests in total: **29** in upstream repositories (2 projects) and **43** in my own. From 2026-03-29 to 2026-11-05.

Every one of them was reviewed line by line before submission, discloses its AI assistance in the body, and is my responsibility.

### Upstream repositories

**[Tencent/teamai-cli](https://github.com/Tencent/teamai-cli)**

| PR | What | Size | Merged |
|---|---|---|---|
| [#1729](https://github.com/Tencent/teamai-cli/pull/1729) | test(relations): cover a learning that lives in the learnings worktree | +78/-1 | 2026-11-05 |
| [#1727](https://github.com/Tencent/teamai-cli/pull/1727) | fix(tool-launch): give a confined Codex judge the member's CODEX_API_KEY | +204/-1 | 2026-11-05 |
| [#1726](https://github.com/Tencent/teamai-cli/pull/1726) | fix(update): report an interrupted install as interrupted, not as a failure | +92/-6 | 2026-11-05 |
| [#1695](https://github.com/Tencent/teamai-cli/pull/1695) | feat(shared-instructions): accept `agentsmd/` as a shared-instruction source directory | +473/-49 | 2026-11-04 |
| [#1679](https://github.com/Tencent/teamai-cli/pull/1679) | test(sessions): cover reading Qoder and Qoder CN transcripts (#1418) | +144/-0 | 2026-11-03 |
| [#1637](https://github.com/Tencent/teamai-cli/pull/1637) | feat(lint,viz,stats): see asset relations — lint counts, health view, opens via relation (#1562, stacked) | +1613/-116 | 2026-11-02 |
| [#1636](https://github.com/Tencent/teamai-cli/pull/1636) | feat(relations): derived rule-path edges and reconcile candidates (#1563) | +676/-19 | 2026-11-02 |
| [#1629](https://github.com/Tencent/teamai-cli/pull/1629) | feat(recall): declared asset relations on recall hits, checked by review --branch (#1552 first slice) | +1612/-210 | 2026-10-31 |
| [#1628](https://github.com/Tencent/teamai-cli/pull/1628) | feat(recall): record query text in the session recall-quality cache | +60/-5 | 2026-10-31 |
| [#1555](https://github.com/Tencent/teamai-cli/pull/1555) | rank(search): ignore question words and normalize the title field | +268/-36 | 2026-10-30 |
| [#1549](https://github.com/Tencent/teamai-cli/pull/1549) | rank(recall): prefer the codebase page the query names, and keep the top 3 source-diverse | +299/-3 | 2026-10-29 |
| [#1547](https://github.com/Tencent/teamai-cli/pull/1547) | fix(hooks): record what a CodeBuddy session does, and what it loads | +289/-42 | 2026-10-29 |
| [#1542](https://github.com/Tencent/teamai-cli/pull/1542) | fix(workflow): a stop of an attempt reaches the setup's process group | +89/-17 | 2026-10-29 |
| [#1524](https://github.com/Tencent/teamai-cli/pull/1524) | fix(recall): rank an explicit docs match above a saturated codebase hit | +248/-17 | 2026-10-29 |
| [#1522](https://github.com/Tencent/teamai-cli/pull/1522) | test(workflow): give the eight flaky workflow cases a budget that fits their real work (#1504) | +8/-4 | 2026-10-28 |
| [#1521](https://github.com/Tencent/teamai-cli/pull/1521) | test(ci): forget a pid the runner cannot signal, and run the CodeBuddy gate on Windows (#1504) | +34/-3 | 2026-10-28 |
| [#1497](https://github.com/Tencent/teamai-cli/pull/1497) | feat(hooks): run project team hooks on OpenCode and OMP (#1492) | +729/-28 | 2026-10-28 |
| [#1465](https://github.com/Tencent/teamai-cli/pull/1465) | feat(worktree): one side-branch checkout per self-mode repo (#1443) | +610/-46 | 2026-10-28 |
| [#1445](https://github.com/Tencent/teamai-cli/pull/1445) | fix(worktree): evict a stale side-branch checkout from either scope (#1443) | +140/-11 | 2026-10-27 |
| [#1421](https://github.com/Tencent/teamai-cli/pull/1421) | fix(ci): read changes through the default branch and accept skin-tone rejections | +53/-6 | 2026-10-26 |
| [#1417](https://github.com/Tencent/teamai-cli/pull/1417) | fix(import): preserve curated docs and domain metadata across imports | +366/-2 | 2026-10-26 |
| [#1411](https://github.com/Tencent/teamai-cli/pull/1411) | fix(ci): preserve the instance scheme, paginate the MR lookup, address the project by path | +288/-257 | 2026-10-26 |
| [#1321](https://github.com/Tencent/teamai-cli/pull/1321) | feat(ci): support GitLab in ci extract-mr comments and rejection marks | +645/-24 | 2026-10-26 |
| [#321](https://github.com/Tencent/teamai-cli/pull/321) | test(providers/gitlab): add opt-in live smoke test against real GitLab | +22/-0 | 2026-08-25 |

**[first-tree-ai/first-tree](https://github.com/first-tree-ai/first-tree)**

| PR | What | Size | Merged |
|---|---|---|---|
| [#2430](https://github.com/first-tree-ai/first-tree/pull/2430) | test(server): stop the durable-ack fallback cases from racing their own window | +18/-6 | 2026-11-05 |
| [#2429](https://github.com/first-tree-ai/first-tree/pull/2429) | test(server): give the lost-wake provider-models test real timing headroom | +9/-4 | 2026-11-04 |
| [#2428](https://github.com/first-tree-ai/first-tree/pull/2428) | test(web): pin Intl default locale in schedules-section-dom assertions | +20/-0 | 2026-11-04 |
| [#2427](https://github.com/first-tree-ai/first-tree/pull/2427) | fix(server): send non-ASCII attachment names as RFC 5987 filename* | +31/-6 | 2026-11-04 |
| [#1975](https://github.com/first-tree-ai/first-tree/pull/1975) | fix(kimi-code): pass KIMI_CODE_HOME to harness for config/credential resolution | +237/-7 | 2026-07-27 |

### My own projects

**[Walternater/tinypowers](https://github.com/Walternater/tinypowers)**

| PR | What | Size | Merged |
|---|---|---|---|
| [#61](https://github.com/Walternater/tinypowers/pull/61) | fix(skills/proxy-node-bench): 三家混合端口统一为 7897，端口归属按内核进程校验 | +20/-8 | 2026-11-02 |
| [#60](https://github.com/Walternater/tinypowers/pull/60) | feat(skills/proxy-node-bench): 三家 mihomo 代理工具节点测速与管理 | +495/-0 | 2026-11-02 |
| [#53](https://github.com/Walternater/tinypowers/pull/53) | feat: add Critical severity + intent mapping | +68/-29 | 2026-05-13 |
| [#52](https://github.com/Walternater/tinypowers/pull/52) | [codex] add one-click installer for Claude Code | +395/-4 | 2026-04-16 |
| [#51](https://github.com/Walternater/tinypowers/pull/51) | refactor: rebuild tinypowers as a clean minimal v1.0 | +9852/-33215 | 2026-04-15 |
| [#46](https://github.com/Walternater/tinypowers/pull/46) | fix(skills): 修复 Java 工程实测发现的全部问题 P0/P1/P2 | +164/-44 | 2026-04-08 |
| [#45](https://github.com/Walternater/tinypowers/pull/45) | perf(init): 优化 tinypowers 安装路径检测逻辑 | +44/-11 | 2026-04-08 |
| [#44](https://github.com/Walternater/tinypowers/pull/44) | feat(install): 优化更新体验，支持交互式确认和自动备份 | +43/-5 | 2026-04-08 |
| [#43](https://github.com/Walternater/tinypowers/pull/43) | docs(readme): remove AI knowledge extraction references after PR #40 revert | +1/-21 | 2026-04-08 |
| [#42](https://github.com/Walternater/tinypowers/pull/42) | Revert PR #40: AI knowledge extraction (correct) | +19/-5418 | 2026-04-08 |
| [#41](https://github.com/Walternater/tinypowers/pull/41) | Revert PR #40: AI knowledge extraction | +2/-2 | 2026-04-08 |
| [#40](https://github.com/Walternater/tinypowers/pull/40) | feat(knowledge): add AI-driven automatic knowledge extraction | +5418/-19 | 2026-04-08 |
| [#38](https://github.com/Walternater/tinypowers/pull/38) | docs: 精简 knowledge.md，删除与 README 重复的章节 | +294/-4 | 2026-04-08 |
| [#37](https://github.com/Walternater/tinypowers/pull/37) | chore: cleanup git state - add hooks and remove embedded worktree | +4127/-59 | 2026-04-08 |
| [#36](https://github.com/Walternater/tinypowers/pull/36) | fix(doctor): avoid misclassifying copied installs as repo | +6/-2 | 2026-04-03 |
| [#35](https://github.com/Walternater/tinypowers/pull/35) | Optimize workflow execution, installation, and closure flow | +6833/-311 | 2026-04-03 |
| [#34](https://github.com/Walternater/tinypowers/pull/34) | refactor(workflow): converge state management and cleanup docs | +1119/-2257 | 2026-04-03 |
| [#33](https://github.com/Walternater/tinypowers/pull/33) | refactor(workflow): 概念收敛 + 恢复确认点与测试交付物 | +500/-613 | 2026-04-02 |
| [#24](https://github.com/Walternater/tinypowers/pull/24) | refactor: 全流程优化 — Medium 路由、审查合并、提交修复 | +330/-444 | 2026-04-02 |
| [#23](https://github.com/Walternater/tinypowers/pull/23) | refactor(workflow): streamline flow O-01~O-07 | +182/-250 | 2026-04-02 |
| [#20](https://github.com/Walternater/tinypowers/pull/20) | Optimize/add docs | +9956/-0 | 2026-04-02 |
| [#19](https://github.com/Walternater/tinypowers/pull/19) | feat: complete end-to-end workflow simplification | +1838/-1337 | 2026-04-02 |
| [#15](https://github.com/Walternater/tinypowers/pull/15) | feat: redesign tech:init bootstrap flow | +595/-215 | 2026-04-01 |
| [#13](https://github.com/Walternater/tinypowers/pull/13) | refactor: consolidate and slim archived docs | +56/-1969 | 2026-04-01 |
| [#12](https://github.com/Walternater/tinypowers/pull/12) | refactor: inline Wave 2 skill support docs | +77/-745 | 2026-04-01 |
| [#11](https://github.com/Walternater/tinypowers/pull/11) | refactor: remove Wave 1 legacy surfaces | +161/-475 | 2026-04-01 |
| [#10](https://github.com/Walternater/tinypowers/pull/10) | refactor: align tech flow worktree boundaries | +231/-75 | 2026-04-01 |
| [#9](https://github.com/Walternater/tinypowers/pull/9) | refactor(tech-feature): thin orchestration layer (v4→v5) | +58/-339 | 2026-03-31 |
| [#6](https://github.com/Walternater/tinypowers/pull/6) | refactor: thin orchestration layer for tech:code | +130/-1149 | 2026-03-31 |
| [#5](https://github.com/Walternater/tinypowers/pull/5) | feat(hooks): SPEC-STATE 门禁 hook + skill 意图路由 | +541/-236 | 2026-03-31 |
| [#4](https://github.com/Walternater/tinypowers/pull/4) | refactor: 精简 skill 文档与 hook 代码，去除冗余描述 | +227/-780 | 2026-03-30 |
| [#3](https://github.com/Walternater/tinypowers/pull/3) | refactor: 精简框架 — 删除过度设计，保留核心价值 | +3062/-2935 | 2026-03-30 |
| [#2](https://github.com/Walternater/tinypowers/pull/2) | feat: 整合12个优秀项目的最佳实践优化 | +1713/-96 | 2026-03-30 |
| [#1](https://github.com/Walternater/tinypowers/pull/1) | feat: 结构审计优化 — EARS/Context Budget/Gap Analyzer/Gotchas | +1631/-82 | 2026-03-29 |

**[Walternater/tennis-court-compare](https://github.com/Walternater/tennis-court-compare)**

| PR | What | Size | Merged |
|---|---|---|---|
| [#2](https://github.com/Walternater/tennis-court-compare/pull/2) | fix: 逐时空闲按片计数，修复"显示有空场实际订不到"的失真 | +105/-28 | 2026-08-13 |
| [#1](https://github.com/Walternater/tennis-court-compare/pull/1) | fix: 畅笑渠道场馆区名归一化，修复按区筛选漏掉鲲鹏场馆 | +5/-2 | 2026-08-13 |

**[Walternater/lead-acquisition-data](https://github.com/Walternater/lead-acquisition-data)**

| PR | What | Size | Merged |
|---|---|---|---|
| [#7](https://github.com/Walternater/lead-acquisition-data/pull/7) | chore: 上传数据文件支持断点续跑 (raw/clean/rejects/l2_cost/report + offline.db) | +13190/-1 | 2026-08-02 |
| [#6](https://github.com/Walternater/lead-acquisition-data/pull/6) | fix(p1): Round 3 P1 数据 / 成本 / 安全 / API — rebase + 10 P1 fixes | +609/-51 | 2026-08-02 |
| [#5](https://github.com/Walternater/lead-acquisition-data/pull/5) | fix(etl): Round 3 P0 全部修复 + P2 nit + web handler 400 | +520/-27 | 2026-08-01 |
| [#4](https://github.com/Walternater/lead-acquisition-data/pull/4) | fix(etl): enrich_daemon CORE_FIELDS ImportError + dead imports from 833e9b8 | +86/-4 | 2026-08-01 |
| [#3](https://github.com/Walternater/lead-acquisition-data/pull/3) | docs: 新增 README（项目简介、架构速览、文档导航） | +43/-0 | 2026-08-01 |

**[Walternater/context-tree](https://github.com/Walternater/context-tree)**

| PR | What | Size | Merged |
|---|---|---|---|
| [#3](https://github.com/Walternater/context-tree/pull/3) | Seed Phase 2 — initial leaves across 3 domains | +405/-36 | 2026-07-30 |
| [#1](https://github.com/Walternater/context-tree/pull/1) | Seed Phase 1 — initial tree structure | +240/-8 | 2026-07-28 |

<!-- merged-prs:end -->

## 🧰 Tooling

<div align="center">
  <img src="https://skillicons.dev/icons?i=java,py,ts,docker,k8s,linux,git&theme=dark" alt="toolbox"/>
</div>

AI coding agents (Claude Code and similar), mainstream standard-compatible
model APIs, sandboxed execution for untrusted upstream code.

## 📬 Contact

Open an issue or discussion in the relevant repository — I read everything.

---

<div align="center">
  中文版说明见 <a href="README.zh-CN.md">README.zh-CN.md</a>
</div>
