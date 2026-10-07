# Machine.Machine

**Private AI operations systems.** We design, deploy and operate AI workers for inboxes, documents, recruiting, reporting and company-specific workflows — running on infrastructure you control, with an audit-proof trail of every AI decision.

What makes it different: the fleet **improves itself**. Agents capture their own lessons, review their workflows and propose amendments — recursive self-improvement (RSI) applied to operating a business, with humans approving every change.

### Running right now

- **22** AI agents in production, each with its own desktop, browser, tools and memory
- **8-node NVIDIA DGX Spark** cluster + **4× RTX 3090** — all self-hosted, no data leaves our hardware
- Custom workflows run by **herds of agents** (we moved past n8n-style flowcharts)
- Odoo-based business systems wired to AI agents

### Start here

| Repo | What it is |
|---|---|
| [herdr-factory-loop-skill](https://github.com/machine-machine/herdr-factory-loop-skill) | **m2herd** — orchestrate herds of AI coding agents in a spec-driven factory loop (spec → plan → tasks → implement → review → evolve) |
| [fleet-playbook](https://github.com/machine-machine/fleet-playbook) | The operating model for autonomous AI organisations: identity, memory, trust levels, governance |
| [openclaw-m2-memory-skill](https://github.com/machine-machine/openclaw-m2-memory-skill) | Long-term memory for agents — hybrid semantic retrieval on Qdrant + BGE-M3 |
| [ask-fable-skill](https://github.com/machine-machine/ask-fable-skill) | Delegate hyper-complex tasks to a Claude Code worker inside herdr |

Many other repos here are forks of open-source tools we run and patch.

### Work with us

- 🌐 [machinemachine.ai](https://machinemachine.ai)
- 👤 Founder: [Mariusz Kreft](https://github.com/mariuszkreft) — AI strategy & engineering, [grait.io](https://grait.io)
- ✉️ hi@grait.io
