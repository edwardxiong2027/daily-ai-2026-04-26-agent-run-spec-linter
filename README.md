# Agent Run Spec Linter

A tiny static tool for linting autonomous agent run specs and exporting a machine-readable recommendation bundle.

## Pitch
Built from this week’s agent-platform news, this app helps an operator or supervisor agent choose the right runtime posture for a job:
- **Anthropic Managed Agents** for long-horizon session / harness / sandbox workflows
- **Google Gemini Enterprise Agent Platform** for governed enterprise orchestration
- **GitHub Copilot + GPT-5.5** for premium complex coding runs
- **OpenAI’s SWE-bench warning** as a guardrail against brittle benchmark-only evals

## Why this exists
Fresh signals this week point in the same direction: AI agents are becoming real operators, and the operator stack now matters as much as the base model.

Primary sources used:
- https://www.anthropic.com/engineering/managed-agents
- https://cloud.google.com/blog/products/ai-machine-learning/introducing-gemini-enterprise-agent-platform
- https://github.blog/changelog/2026-04-24-gpt-5-5-is-generally-available-for-github-copilot/
- https://openai.com/index/why-we-no-longer-evaluate-swe-bench-verified/

Supporting validation / signal sources:
- https://news.google.com/rss/search?q=Reuters%20AI%20agents%20enterprise%20April%202026&hl=en-US&gl=US&ceid=US:en
- https://hn.algolia.com/?dateRange=all&page=0&prefix=false&query=GPT-5.5%20is%20generally%20available%20for%20GitHub%20Copilot&sort=byPopularity&type=story
- https://hn.algolia.com/?dateRange=all&page=0&prefix=false&query=Why%20SWE-bench%20Verified%20no%20longer%20measures%20frontier%20coding%20capabilities&sort=byPopularity&type=story

## Files
- `index.html` — single-page app
- `LICENSE` — MIT
- `.gitignore`

## Local preview
```bash
python3 -m http.server 8000
```
Then open: http://localhost:8000

## Live URL
Pending deployment.

## Repo URL
Pending creation.
