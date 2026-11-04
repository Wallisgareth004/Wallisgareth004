# Gareth Wallis

**AI/agent engineer: agent security, reliability and integration.** I make Claude-based agents safe to hand real tools, with checks you can re-run yourself.

**Work with me:** [Upwork](https://www.upwork.com/freelancers/~01b99bf2efbfb9a02e)

## Proof

| Repo | What it shows |
|---|---|
| [support-bot-abuse-check](https://github.com/Wallisgareth004/support-bot-abuse-check) | 40 scripted attacks on a support bot, every tool call checked against written refund rules. The naive demo bot broke 35 of 40; the gated one 0, and still served 6 of 6 ordinary requests. |
| [memory-warden](https://github.com/Wallisgareth004/memory-warden) | Memory integrity for multi-agent Claude Code. Caught 51 of 53 CVE-linked attacks in its own suite; 0 false positives on a 2,000-call replay. |
| [claude-code-team-setup-sample](https://github.com/Wallisgareth004/claude-code-team-setup-sample) | A safe Claude Code setup for a team repo: permission rules, a guard hook and a gitleaks pre-commit, with 34 tests. |
| [finance-skill](https://github.com/Wallisgareth004/finance-skill) | A local finance pipeline that refuses to report a number it can't prove. 334 tests on synthetic data. |
| [trade-journal](https://github.com/Wallisgareth004/trade-journal) | A local journal that grades the process, not the P&L. A full test suite on made-up data, standard library only. |

## What I take on

- **Agent security check:** I try to talk your agent into what it mustn't do, and send each rule it breaks with the fix.
- **Claude Code setup for a small team:** permissions, guard hooks, CLAUDE.md and a secret scan on every commit.
- **A small MCP server or agent build:** tested, with the guard rails built in.

Every number above is measured and can be re-run from its repo. The demo bots are rule-based stand-ins, as that README says.
