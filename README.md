### Hi, I'm Benedikt

Operator and builder. I spend most of my time running businesses — and some of it writing the tools that help me do that better.

The repos here are self-hosted MCP servers: they connect [Claude](https://claude.ai) to services I use daily over a secure remote connection, with no local setup required. Built with [Claude Code](https://claude.ai/code).

---

**[garmin-connect-mcp](https://github.com/benediktwen/garmin-connect-mcp)** — 96+ Garmin Connect tools via MCP. Sleep, HRV, activities, training load, body composition. Adapted from [Taxuspt/garmin_mcp](https://github.com/Taxuspt/garmin_mcp).

**[icloud-mail-mcp](https://github.com/benediktwen/icloud-mail-mcp)** — Read, search, flag, and draft replies in iCloud Mail via IMAP. Works with aliases and custom domains.

**[icloud-calendar-mcp](https://github.com/benediktwen/icloud-calendar-mcp)** — Read and write Apple iCloud Calendar events via CalDAV.

---

All three use the same auth pattern: GitHub OAuth + Redis token persistence, deployed on Render. Fork any of them to run your own instance.
