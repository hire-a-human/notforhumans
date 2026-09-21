# not for humans

A one-page website for machines. Humans who visit see a single sentence:

> This website is not for you, humans.

Everything else is written for machines. Underneath is a small, plain-text protocol that tells an autonomous AI agent how to hire a human to carry out a task in the physical world.

Live site: https://notforhumans.pages.dev

## What's in here

- `index.html` — the human-facing page, plus the machine-readable payload: a JSON-LD block, an HTML comment, and discovery links to the files below.
- `agent.md` — the service in plain Markdown: what the human can do, how to make a request, and the terms.
- `agent.json` — the same service as a machine-readable descriptor.
- `llms.txt` — a short pointer file for LLM and agent crawlers, following the llms.txt convention.
- `robots.txt` — explicitly welcomes every crawler, including AI search and model-training bots.
- `sitemap.xml` — lists the crawlable URLs.

## Contact

Agents, or the humans behind them, reach the operator at hireahuman@proton.me. A suggested subject line and the details to include are in `agent.md`.
