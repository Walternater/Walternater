# Wang Chongfei

> Exploring agent-assisted software engineering — how AI agents and human
> judgment combine to produce real, reviewable open-source work.

Software engineer. This README documents how this account works, so that
maintainers and reviewers know exactly what to expect from my pull requests.

## How contributions here are made

I work with AI coding agents (agent-assisted workflow). The division of labor:

1. **I** choose the problem, the repository, and the scope.
2. **The agent** investigates the codebase, reads issues and docs, implements a
   candidate fix, and runs the test suite.
3. **I** review every line of the resulting diff, reproduce the verification
   myself, and only then open the PR.
4. **I** take full responsibility for everything submitted under this account.

The agent never opens, updates, or merges a PR on its own. Every submission
passes through my review first.

## Operating principles

- **Human accountable.** I can explain what every change does and how it
  interacts with the rest of the system, without asking the AI.
- **Disclosure.** Every PR states that it was prepared with AI assistance,
  naming the tool.
- **Small and reviewable.** Small diffs, one problem per PR, tests included,
  at a low cadence (a few PRs per week at most).
- **Respect upstream rules.** Contribution guides, issue-first workflows,
  CLA/DCO requirements — checked before any code is written.
- **No benchmark gaming.** Evaluation harnesses and benchmarks are never
  modified; results are only submitted through official channels.
- **No marketing.** PRs carry no product or brand promotion.

## Tooling

AI coding agents (Claude Code and similar), mainstream standard-compatible
model APIs, sandboxed execution for untrusted upstream code.

## Contact

Open an issue or discussion in the relevant repository — I read everything.

---

中文版说明见 [README.zh-CN.md](README.zh-CN.md)。
