# Awesome-Workflow-Integration-Add-Ons

# Top Workflow Integration Add-Ons Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Platform Extensions, Automation Connectors & Self-Hosted Integration Infrastructure*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Workflow Integration Add-Ons**. These tools enable teams to extend their existing work management platforms—Trello, Jira, Slack, Miro, ClickUp, Monday, Asana—with automation, connectors, and custom functionality, bridging the gaps between tools without replacing them.

**Examples** include Trello Power-Ups, Zapier, Make, Workato, Slack Integrations, Jira Plugins, Miro Add-ons, ClickUp Integrations, Monday Apps, and Asana Apps (the category leaders).

**Open-source emphasis**: Workflow Integration Add-Ons is a domain where open-source tooling is **exceptionally strong at the automation layer but fragmented at the platform-extension layer**. The strongest active projects are **Activepieces** (MIT, 500+ integrations, self-hostable Zapier/Make alternative with AI agents and MCP support) and **n8n** (Sustainable Use License, visual canvas with 1500+ integrations). For Trello specifically, **Kan** provides an open-source kanban board with direct Trello import, while **WeKan** and **Vikunja** offer mature self-hosted alternatives with Trello importers . For Jira alternatives, **Windshift** bundles service management, knowledge base, and test management into a single Go binary, and **Plane** provides an AI-native project management platform with 47,800+ GitHub stars . The critical gap: **no open-source project replicates the platform-native Power-Ups/Apps ecosystem** of Trello, Jira, or Slack—those require deep platform API integration that commercial vendors and platform owners control.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Trello Power-Ups](https://trello.com/power-ups)**  
  Trello's native add-on ecosystem with 150+ Power-Ups for calendar views, automation (Butler), time tracking, and third-party integrations; deep platform API access and in-card functionality.

- **[Zapier](https://zapier.com/)**  
  Market-leading no-code automation platform with 9,000+ app integrations; triggers and actions-based workflows for connecting SaaS tools without engineering effort.

- **[Make](https://www.make.com/)**  
  Visual automation platform (formerly Integromat) with 3,000+ pre-built apps; features a visual Scenario Builder, If-Else and Merge modules, and scenario run replay.

- **[Workato](https://www.workato.com/)**  
  Enterprise automation platform with AI-powered recipe building, low-code connectors, and comprehensive security compliance (PCI-DSS, ISO 27001, SOC 2, HIPAA).

- **[Slack Integrations](https://slack.com/apps)**  
  Slack's app directory with thousands of integrations for notifications, workflow automation (Workflow Builder), and third-party service connectivity.

- **[Jira Plugins (Atlassian Marketplace)](https://marketplace.atlassian.com/)**  
  Atlassian's marketplace with thousands of plugins for Jira, Confluence, and other Atlassian products; covers time tracking, reporting, automation, and third-party integrations.

- **[Miro Add-ons (Marketplace)](https://marketplace.miro.com/)**  
  Miro's app marketplace for whiteboard extensions, including integrations with Jira, Asana, Slack, and AI-powered diagramming tools.

- **[ClickUp Integrations](https://clickup.com/integrations)**  
  ClickUp's native integration library and app directory for connecting project management workflows with Slack, GitHub, Google Drive, and other tools.

- **[Monday Apps](https://monday.com/marketplace)**  
  monday.com's app marketplace for extending boards with automations, dashboards, and third-party integrations.

- **[Asana Apps](https://asana.com/apps)**  
  Asana's integration directory for connecting projects with Slack, Jira, GitHub, Zoom, and other work tools.

## Open-Source GitHub Projects

### Workflow Automation Platforms (Zapier/Make/Workato Alternatives)

- **[Activepieces](https://github.com/activepieces/activepieces)**  
  The strongest open-source **Zapier/Make alternative** available (MIT, 9,646+ GitHub stars) . Self-hostable with **500+ pre-built pieces** (Google Sheets, Slack, OpenAI, HTTP, webhooks), visual flow builder with branches/loops/conditional logic, **AI Agents and Copilot** built into the editor, human-in-the-loop approval steps, custom code steps (JavaScript/TypeScript), and **MCP server support** for AI tool integrations . Deployable on Railway with one click or Docker. **The best starting point for teams wanting a privacy-first automation platform** without per-task fees.

- **[n8n](https://github.com/n8n-io/n8n)**  
  Leading open-source workflow automation platform (Sustainable Use License, 47,810+ GitHub stars); combines a visual canvas with custom code (JavaScript/Python); 1500+ integrations and 9,000+ workflow templates; AI-native capabilities for building multi-step agents with model flexibility (OpenAI, Anthropic, Google, open-source models).

- **[AutoKitteh](https://github.com/autokitteh/autokitteh)**  
  Developer-focused **code-based workflow automation platform** (Python, Starlark) built on Temporal for durable execution . Positioned as an alternative to no/low-code platforms (Zapier, Workato, Make, n8n) with unlimited flexibility for long-running, reliable workflows. Self-hostable with built-in integrations for Slack, GitHub, Twilio, ChatGPT, Gemini, Gmail, and more.

- **[dliy-io](https://hub.docker.com/r/deathlegion/dliy-io)**  
  Open-source, self-hostable workflow automation platform (TypeScript/Node.js) with visual node editor (React Flow), **115+ pre-built integrations**, AI via GLM-4.6, and custom JavaScript/Python code nodes . Docker-deployable.

- **[FlowForge](https://github.com/DeveloperSarim/FlowForge)**  
  Open-source, self-hosted n8n/Zapier alternative for **PHP shared hosting** (AGPL-3.0); 1,690 apps, AI workflow builder, AI voice agents, and MCP support. Runs on cPanel/Hostinger with one cron job . **Best for teams without Node.js infrastructure** who need automation on shared hosting.

### Project Management Platform Alternatives (Trello/Jira/Monday/ClickUp)

- **[Kan](https://github.com/kanbn/kan)**  
  Open-source Trello alternative (Next.js, tRPC, Tailwind) with **direct Trello board import**, granular permissions, comments, activity log, and Docker deployment . **The closest open-source equivalent to Trello's board experience** with a clean migration path—but lacks Power-Ups and native mobile apps.

- **[WeKan](https://github.com/wekan/wekan)**  
  The most mature open-source Trello alternative (MIT, 21k+ GitHub stars, active since 2014); real-time boards, swimlanes, WIP limits, webhooks, and **importers for Trello, Jira, and Asana** . Requires MongoDB and at least 1GB RAM. **The best overall for Trello-style boards** with production-grade stability.

- **[Vikunja](https://github.com/go-vikunja/vikunja)**  
  Open-source task manager (AGPL-3.0, 5.6k+ GitHub stars) with **four views** (List, Gantt, Table, Kanban), reminders, repeating tasks, and **Trello/Todoist importers** . Single binary or Docker. **Best when you want more than a board**—to-dos, Gantt, and reminders in one tool.

- **[Plane](https://github.com/makeplane/plane)**  
  AI-native project management platform (AGPL-3.0, 47,800+ GitHub stars) positioned as a Jira/Linear/Monday/ClickUp alternative; features work items, cycles (sprints), modules, pages, and five layout views (List, Board, Spreadsheet, Gantt, Calendar) . **The strongest open-source Jira alternative** with active development and a modern UI.

- **[Windshift](https://github.com/windshiftapp/core)**  
  Open-source, self-hosted work management platform (AGPL v3, single Go binary) positioned as a **Jira alternative** . Bundles projects, epics, sprints, boards, custom workflows, **service management with SLAs**, knowledge base, test management, time tracking, and asset/CMDB register. JQL-style query language and Jira importer. **The most complete all-in-one replacement for Jira + Confluence + service desk** in a single binary.

- **[Paca](https://github.com/Paca-AI/paca)**  
  AI-native, free, open-source alternative to Jira, Trello, ClickUp, and Monday (Apache-2.0); built for Scrum teams where humans and AI agents collaborate; features sprints, tasks, documents, and an **MCP server** for AI agent integration . Self-hosted with Docker/Kubernetes.

- **[Leantime](https://github.com/leantime/leantime)**  
  Open-source project management system (PHP/MySQL) combining design thinking, lean methodology, and Agile practices; features kanban boards, Gantt charts, goal tracking, time tracking, and **Slack/Mattermost/Discord integrations** . **For teams wanting an integrated project management + collaboration platform.**

### Additional Strong Open-Source Options

- **Kanboard** — Minimal open-source kanban board (MIT, 9.9k+ GitHub stars) with automatic actions, plugins, and LDAP/OAuth2 support; in maintenance mode but stable for simple boards .
- **ByteChef** — Open-source low-code API integration and workflow automation platform (Java, 201 GitHub stars) ; an alternative for Java-centric teams.
- **Actionsflow** — Free Zapier/IFTTT alternative for developers using GitHub Actions; **CAUTION**: no commits in 90+ days per OpenSSF scorecard, effectively stale .

**Frameworks for building custom systems**: For **Zapier-like automation**, Activepieces (MIT, 500+ integrations, AI agents) or n8n (visual canvas, 1500+ integrations) are the strongest options. For **Trello replacement with import**, Kan or WeKan. For **Jira replacement**, Plane or Windshift. For **AI-agent integration**, Paca (MCP server) or Activepieces (MCP support). No open-source project replicates the **platform-native Power-Ups/Apps ecosystem**—those require deep integration with proprietary platform APIs that only the platform owners control.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Workflow integration platforms handling business data and credentials must comply with applicable privacy regulations and organizational security policies; API keys and OAuth tokens require secure storage and rotation.
- **Open-source workflow integration is strongest at the automation layer**—Activepieces and n8n provide production-grade Zapier alternatives, and Kan/WeKan/Plane provide platform replacements . However, **no open-source project replicates the platform-native add-on ecosystems** (Trello Power-Ups, Jira Plugins, Slack Apps) that require deep proprietary API integration. Organizations requiring native platform extensions should evaluate commercial apps or build custom integrations.
- Verify license terms for commercial use; Activepieces uses MIT , n8n uses the Sustainable Use License (not OSI-approved, with restrictions on resale), and Kan/WeKan use MIT .

---

**Made for integration engineers, automation developers, IT operations teams, and work management platform administrators.**  
Let's make workflow integration more open, but with clear eyes about the platform-native add-on gap that commercial ecosystems still fill.
