# Awesome MCP Servers [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of MCP (Model Context Protocol) servers, tools, and resources for building AI-powered integrations.

[MCP](https://modelcontextprotocol.io) is Anthropic's open protocol that lets AI models like Claude connect to external tools and data sources. MCP servers expose capabilities that Claude and other AI assistants can use directly.

---

## Contents

- [Official](#official)
- [Productivity](#productivity)
- [Developer Tools](#developer-tools)
- [Data & Analytics](#data--analytics)
- [Communication](#communication)
- [CRM & Sales](#crm--sales)
- [Design](#design)
- [Finance](#finance)
- [Automation](#automation)
- [AI & ML](#ai--ml)
- [Database](#database)
- [Cloud & Infrastructure](#cloud--infrastructure)
- [Frameworks & SDKs](#frameworks--sdks)
- [Tutorials](#tutorials)
- [Community](#community)

---

## Official

- [MCP Specification](https://spec.modelcontextprotocol.io) — The protocol specification.
- [MCP SDKs](https://modelcontextprotocol.io/sdk) — Official TypeScript and Python SDKs.
- [Claude Desktop MCP](https://claude.ai/download) — Claude desktop app with built-in MCP support.
- [Claude.ai Connectors](https://claude.com/connectors) — MCP integrations available in Claude.ai.

## Productivity

- [Google Calendar](https://gcal.mcp.claude.com/mcp) — Read/write calendar events, check availability, create meetings.
- [Gmail](https://gmail.mcp.claude.com/mcp) — Search, read, send, and manage emails.
- [Notion](https://mcp.notion.com/mcp) — Query databases, create pages, update content.
- [Airtable](https://mcp.airtable.com/mcp) — Read/write records, manage bases, automate workflows.
- [ClickUp](https://mcp.clickup.com/mcp) — Manage tasks, projects, time tracking.
- [Asana](https://mcp.asana.com/v2/mcp) — Create tasks, manage projects, track progress.
- [Microsoft 365](https://microsoft365.mcp.claude.com/mcp) — Outlook, OneDrive, SharePoint, Teams.
- [Granola](https://mcp.granola.ai/mcp) — Meeting notes and transcription.

## Developer Tools

- [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/src/github) — Repos, issues, PRs, code search.
- [Sentry](https://mcp.sentry.dev/mcp) — Error monitoring, issue management, performance.
- [Vercel](https://mcp.vercel.com) — Deployments, domains, serverless functions.
- [Supabase](https://mcp.supabase.com/mcp) — Database management, auth, storage, edge functions.
- [n8n](https://docs.n8n.io/integrations/builtin/core-nodes/n8n-nodes-base.mcptrigger/) — Workflow automation with MCP triggers.
- [Webflow](https://mcp.webflow.com/mcp) — CMS, site management, form submissions.
- [WordPress](https://public-api.wordpress.com/wpcom/v2/mcp/v1) — Posts, pages, media, comments.

## Data & Analytics

- [Similarweb](https://mcp.similarweb.com) — Website traffic, competitive analysis, market research.
- [Windsor.ai](https://mcp.windsor.ai) — Marketing analytics, attribution, cross-channel data.

## Communication

- [Slack](https://slack.com/integrations) — Messages, channels, threads, file sharing.

## CRM & Sales

- [Clay](https://api.clay.com/v3/mcp) — Data enrichment, lead scoring, outbound automation.
- [Indeed](https://mcp.indeed.com/claude/mcp) — Job listings, candidate search, hiring.
- [Klaviyo](https://mcp.klaviyo.com/mcp) — Email marketing, segmentation, campaign management.
- [NotFair](https://github.com/nowork-studio/NotFair) — Open-source Claude Code agent skills for SEO and paid ads, connecting via Google Ads MCP, Meta Ads MCP, Google Search Console MCP, and Google Analytics (GA4) MCP.

## Design

- [Figma](https://mcp.figma.com/mcp) — Read designs, inspect components, export assets.
- [Canva](https://mcp.canva.com/mcp) — Create designs, templates, brand assets.
- [Gamma](https://mcp.gamma.app/mcp) — AI-powered presentations and documents.

## Finance

- [Stripe](https://github.com/stripe/agent-toolkit) — Payments, subscriptions, invoicing.

## Automation

- [Make](https://mcp.make.com) — Visual automation scenarios, 1500+ app integrations.
- [Zapier](https://mcp.zapier.com/api/v1/connect) — Trigger-action automations, 6000+ apps.

## Cloud & Infrastructure

- [AWS Marketplace](https://marketplace-mcp.us-east-1.api.aws/mcp) — Search and compare AWS solutions.
- [Cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) — Workers, KV, R2, DNS management.

## Frameworks & SDKs

- [TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) — Build MCP servers in TypeScript/Node.js.
- [Python SDK](https://github.com/modelcontextprotocol/python-sdk) — Build MCP servers in Python.
- [MCP Inspector](https://github.com/modelcontextprotocol/inspector) — Debug and test MCP servers.

## Tutorials

- [Building Your First MCP Server](https://modelcontextprotocol.io/quickstart/server) — Official quickstart guide.
- [MCP for Claude Desktop](https://modelcontextprotocol.io/quickstart/user) — Set up MCP in Claude desktop app.
- [Anthropic MCP Course](https://www.anthropic.com/learn) — Free course on building with MCP.

## Community

- [MCP Discord](https://discord.gg/modelcontextprotocol) — Official community server.
- [r/ClaudeAI](https://reddit.com/r/ClaudeAI) — Reddit community.
- [Claude Community](https://claude.com/community) — Official Claude community.

---

## How MCP Works

```
┌──────────────┐     MCP Protocol     ┌──────────────┐
│              │ ◄──────────────────► │              │
│   Claude     │   Tools + Resources  │  MCP Server  │
│   (Client)   │                      │  (Your App)  │
│              │ ◄──────────────────► │              │
└──────────────┘    Prompts + Data    └──────────────┘
```

MCP servers expose:
- **Tools** — Actions the AI can take (create task, send email, query database)
- **Resources** — Data the AI can read (documents, database records, API responses)
- **Prompts** — Pre-built prompt templates for common tasks

---

## Contributing

Your contributions are welcome!

1. Make sure the server is working and publicly accessible
2. Add it to the correct category in alphabetical order
3. Use the format: `[Name](URL) — Brief description.`
4. Submit a PR

Please ensure:
- Server is actively maintained
- URL is accessible
- Description is concise (one sentence)

---

## Disclaimer

This list is community-maintained. Inclusion does not imply endorsement. Always verify server security and data handling before connecting to your AI assistant.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
