<div align="center">
  <img src="https://raw.githubusercontent.com/Walternater/Walternater/main/banner.svg" alt="王崇飞 — Agent 辅助，人工担责" width="100%"/>
</div>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=500&size=22&duration=2800&pause=900&color=39D0D8&center=true&vCenter=true&width=720&lines=AI+writes+the+code.;I+read+every+line.;Agents+do+the+busywork.;Humans+do+the+judging." alt="typing"/>
</div>

<div align="center">
  <img src="https://img.shields.io/badge/软件工程师-Software%20Engineer-39d0d8?style=flat-square&labelColor=0d1117" alt=""/>
  <img src="https://img.shields.io/badge/Agent辅助-开源贡献-a78bfa?style=flat-square&labelColor=0d1117" alt=""/>
  <img src="https://img.shields.io/badge/每个diff-人工审阅-39d0d8?style=flat-square&labelColor=0d1117" alt=""/>
  <img src="https://img.shields.io/badge/责任主体-本人-a78bfa?style=flat-square&labelColor=0d1117" alt=""/>
</div>

<br/>

软件工程师。这个页面说明本账号的运作方式，让维护者和 reviewer 确切知道
我的 PR 是怎么来的、可以期待什么。

## ⚙️ 贡献是如何产生的

我使用 AI 编程助手（agent 辅助工作流），分工如下：

1. **🧭 我**选题、选仓库、定边界。
2. **🤖 Agent** 调研代码、读 issue 和文档、实现候选修复、跑测试。
3. **👀 我**逐行审阅产出的每一个 diff，亲自复现验证结果，然后才提 PR。
4. **✍️ 我对**本账号提交的所有内容承担全部责任。

Agent 不会自行创建、更新或合并 PR——每次提交都先经过我的审阅。

## 🧱 运营原则

<table>
<tr>
<td width="33%" valign="top">

**👤 责任在人**

不借助 AI 也能讲清每处改动的作用及其与系统其余部分的关系。

</td>
<td width="33%" valign="top">

**📣 披露**

每个 PR 都会声明使用了 AI 辅助并注明工具。

</td>
<td width="33%" valign="top">

**🧩 小而可审**

diff 小、一个 PR 只解决一个问题、附测试、低频提交。

</td>
</tr>
<tr>
<td width="33%" valign="top">

**📜 遵守上游规则**

CONTRIBUTING、issue-first 流程、CLA/DCO 要求，写代码之前先确认。

</td>
<td width="33%" valign="top">

**🚫 不碰评测器**

评测框架和 benchmark 永不修改；成绩只走官方提交渠道。

</td>
<td width="33%" valign="top">

**🤐 不做广告**

PR 中不带任何产品或品牌推广。

</td>
</tr>
</table>

<!-- merged-prs:start -->
## 📊 已合并的开源贡献

在别人的仓库里被合并的 PR 共 **31** 个，覆盖 **2** 个开源项目。时间跨度 2026-07-27 → 2026-11-06。

每个 PR 都经过人工逐行审阅后提交，正文披露 AI 参与，并由我对全部内容负责。

### 上游仓库

**[Tencent/teamai-cli](https://github.com/Tencent/teamai-cli)**

| PR | 内容 | 规模 | 合并 |
|---|---|---|---|
| [#1740](https://github.com/Tencent/teamai-cli/pull/1740) | fix(benchmark): keep an arm's recall when a record is read back | +79/-5 | 2026-11-06 |
| [#1729](https://github.com/Tencent/teamai-cli/pull/1729) | test(relations): cover a learning that lives in the learnings worktree | +78/-1 | 2026-11-05 |
| [#1728](https://github.com/Tencent/teamai-cli/pull/1728) | feat(benchmark): give an arm a clone that deploys the team's recall | +175/-17 | 2026-11-05 |
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

| PR | 内容 | 规模 | 合并 |
|---|---|---|---|
| [#2430](https://github.com/first-tree-ai/first-tree/pull/2430) | test(server): stop the durable-ack fallback cases from racing their own window | +18/-6 | 2026-11-05 |
| [#2429](https://github.com/first-tree-ai/first-tree/pull/2429) | test(server): give the lost-wake provider-models test real timing headroom | +9/-4 | 2026-11-04 |
| [#2428](https://github.com/first-tree-ai/first-tree/pull/2428) | test(web): pin Intl default locale in schedules-section-dom assertions | +20/-0 | 2026-11-04 |
| [#2427](https://github.com/first-tree-ai/first-tree/pull/2427) | fix(server): send non-ASCII attachment names as RFC 5987 filename* | +31/-6 | 2026-11-04 |
| [#1975](https://github.com/first-tree-ai/first-tree/pull/1975) | fix(kimi-code): pass KIMI_CODE_HOME to harness for config/credential resolution | +237/-7 | 2026-07-27 |

<!-- merged-prs:end -->

## 🧰 工具

<div align="center">
  <img src="https://skillicons.dev/icons?i=java,py,ts,docker,k8s,linux,git&theme=dark" alt="toolbox"/>
</div>

AI 编程助手（Claude Code 等）、主流标准兼容模型 API、针对不可信上游
代码的沙箱执行环境。

## 📬 联系

在相关仓库开 issue 或 discussion——我都会看。

---

<div align="center">
  English version: <a href="README.md">README.md</a>
</div>
