### Hi, I'm Benedikt

Operator and builder. I spend most of my time running businesses — and some of it writing the tools that help me do that better.

The repos below are remote MCP servers — connectors that let AI assistants (like Claude) access external services over the internet. Deploy once to the cloud; connect from any device without running anything locally. Built with [Claude Code](https://claude.ai/code).

---

**[garmin-connect-mcp](https://github.com/benediktwen/garmin-connect-mcp)** — Ask your AI assistant about any Garmin metric from any device. The server runs in the cloud, not on your machine — no desktop app, no local setup. 96+ tools covering sleep, HRV, training load, activities, and more. Adapted from [Taxuspt/garmin_mcp](https://github.com/Taxuspt/garmin_mcp).

**[icloud-mail-mcp](https://github.com/benediktwen/icloud-mail-mcp)** — Read, search, flag, and draft replies in iCloud Mail. Works with aliases and custom domains on your Apple ID.

**[icloud-calendar-mcp](https://github.com/benediktwen/icloud-calendar-mcp)** — Read and write Apple iCloud Calendar events via CalDAV.

---

All three use the same auth pattern: GitHub OAuth + Redis token persistence, deployable to any container platform (Render, Railway, Fly.io). Fork any of them to run your own instance.

---

All code here was built with AI assistance ([Claude Code](https://claude.ai/code)) — vibe-coded with the best intentions. Security has been a priority throughout, but nothing has been independently audited. Use at your own risk. Issues and pull requests are very welcome.
