# Agent Repo Rules Starter (free, MIT)

These are free rules files for AI coding agents such as Cursor, Cline, Windsurf and Claude Code. They come from the paid **Agent Repo Rules Starter Pack** by Rene Vergara.

This repo has 3 of the 6 rule sets as Cursor `.mdc` rules:

| File | For |
|---|---|
| `rules/mcp-server.mdc` | MCP (Model Context Protocol) tool servers |
| `rules/cost-guarded-api-client.mdc` | LLM API clients with budgets and retries |
| `rules/prompt-library.mdc` | Versioned prompt collections |

## How to use
1. Copy a file into `.cursor/rules/` in your repo. For Cline, rename it to `.clinerules`. For Claude Code, paste it into `CLAUDE.md`. For Windsurf, use `.windsurfrules`.
2. Edit the `PROJECT FACTS` block at the top. The rules stay generic until you fill it in.
3. Delete any rule you do not actually enforce. If the agent sees a rule broken in the codebase, it ignores that rule.

## Full pack (paid, disclosed)
The full pack has all 6 rule sets (adding LangGraph apps, agent-eval repos and Python tool servers) in both `.clinerules` and `.cursorrules` form, plus a one-page guide to writing your own. It is sold by the author on Gumroad, pay what you want from $1:
https://renevibe76.gumroad.com/l/toahua

Disclosure: that link goes to the author's own product. The free files in this repo work without it.

License: MIT. Built by Rene Vergara.
