## Hi, I'm Russell

I build AI tools at [Savvy Wealth](https://www.savvywealth.com) in New York.

Most of my work is about making AI agents useful inside a real company: giving people a place to share what they build with Claude, connecting Claude to the tools they already use, and putting checks around agents so their work can be trusted.

### What I'm working on

- **An internal AI platform.** Employees publish Claude Skills and small apps, share them with their teams, and use them from Claude and Slack.
- **Workflow capture.** Recording how people do repetitive work in the browser so an agent can learn to repeat it.
- **Keeping agent-written code honest.** Most of my code is written with Claude Code. The tools below are how I make that reliable.

### Open source

| Project | What it does |
| --- | --- |
| [rstack](https://github.com/russellmoss/rstack) | A Claude Code toolkit. Adds decision history, doc drift checks, schema verification and cross-model plan review on top of [gstack](https://github.com/garrytan/gstack). |
| [context-ledger](https://github.com/russellmoss/context_ledger) | Records architecture decisions and abandoned approaches, and lets agents query them over MCP instead of asking the same questions again. |
| [agent-guard](https://github.com/russellmoss/agent-guard) | Keeps docs in sync with code: generated inventories, a pre-commit check, and CI audits. |
| [council-of-models-mcp](https://github.com/russellmoss/Council_of_models_mcp) | Lets Claude ask GPT, Codex and Gemini for a second opinion on a plan. |
| [schema-context-mcp](https://github.com/russellmoss/schema_context_mcp) | Gives agents data warehouse context (field gotchas, metric definitions, query linting) before they write SQL. |

All of them install from npm under [@mossrussell](https://www.npmjs.com/~mossrussell).

### How I think about it

Agents usually fail from missing context, not missing capability. So I write the context down where the agent can check it: past decisions, schema rules, docs that stay current, and a second model that reviews the plan before any code is written.

### Before this

Revenue operations and analytics engineering, plus tools for wine hospitality: a tasting-room chatbot, Commerce7 dashboards and guest data capture.

### Stack

TypeScript · Next.js · Postgres · BigQuery · Python · Claude Code · MCP · Vercel
