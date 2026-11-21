# Lucas Kopietz

I build the AI tools my payments team uses, and check that they work before anyone relies on them. I've spent nine years at one B2B software company, from customer support to payments. I also teach colleagues to use Claude.

My work is AI enablement, AI operations and product operations. Site: [lucaskopietz.com](https://www.lucaskopietz.com). LinkedIn: [lucaskopietz](https://www.linkedin.com/in/lucaskopietz).

## What I built in the open

- [honesty-kits](https://github.com/lkopietz3-byte/honesty-kits): 15 small TypeScript libraries. Most check what an AI product claims: citations, numbers, accuracy figures. A few guard how it runs: agent reports, audit logs, spend caps. You can try all 15 in your browser.
- [honesty-mcp](https://github.com/lkopietz3-byte/honesty-mcp): runs the kits as tools in Claude Code and other MCP clients that can start a local server. `npx -y honesty-mcp`.
- [accuracy-claim-kit](https://github.com/lkopietz3-byte/accuracy-claim-kit): does an accuracy number have the evidence to carry it? From a clone with Python 3, run npm ci, then npm run bench: it checks the kit against a second implementation of the same rules and against the holdout labels.

The four apps on my site (ContextOps, ProofPrism, Disclosed and LaunchPlanr) aren't on this account. Their pages show how they work and where they stop.

## How I teach

If you're getting a team started with Claude, read [Your team's first Claude session](https://www.lucaskopietz.com/work/first-claude-session). It's a 45-minute plan for a fictional library team, with three exercises and a one-page handout. I haven't run it as written. The [AI enablement starter kit](https://www.lucaskopietz.com/work/enablement-kit) covers what AI may decide and what a person confirms.

## How I work

- AI coding agents write most of the code here, and the commits say so. I write the brief, read the diff and watch a test fail before I trust a fix.
- The rules I give the agents are in AGENTS.md, for example [in honesty-mcp](https://github.com/lkopietz3-byte/honesty-mcp/blob/main/AGENTS.md).
- A second AI from a different vendor reviews important changes, and never its own work.
- Every kit says what it does not check.
