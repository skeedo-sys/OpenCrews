# 🦞 Awesome OpenClaw Agents

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

> A curated collection of AI agent templates, MCP servers, tools, and resources for OpenClaw, Clawdbot, and MoltBot ecosystems.

<p align="center">
  <img src="assets/banner.png" alt="Awesome OpenClaw Agents" width="600">
</p>

## Contents

- [Agent Templates](#agent-templates)
  - [Productivity](#productivity)
  - [Development](#development)
  - [Marketing & Content](#marketing--content)
  - [Business](#business)
  - [Personal](#personal)
- [MCP Servers](#mcp-servers)
- [Integrations](#integrations)
- [Tools](#tools)
- [Tutorials](#tutorials)
- [Community](#community)

---

## Agent Templates

Ready-to-use SOUL.md templates for your AI agents.

### Productivity

| Agent | Description | Author |
|-------|-------------|--------|
| [🎯 Orion](agents/productivity/orion/) | Task coordinator and project manager | [@openclaw](https://github.com/openclaw) |
| [📋 TaskMaster](agents/productivity/taskmaster/) | Advanced task breakdown and tracking | Community |
| [📅 CalendarBot](agents/productivity/calendar-bot/) | Schedule management and reminders | Community |
| [📧 InboxZero](agents/productivity/inbox-zero/) | Email triage and response drafting | Community |
| [🎯 FocusGuard](agents/productivity/focus-guard/) | Deep work session manager | Community |

### Development

| Agent | Description | Author |
|-------|-------------|--------|
| [💻 CodeReviewer](agents/development/code-reviewer/) | PR review and code quality checks | Community |
| [🐛 BugHunter](agents/development/bug-hunter/) | Debugging assistant and error analyzer | Community |
| [📚 DocWriter](agents/development/doc-writer/) | Documentation generator | Community |
| [🔧 DevOpsBot](agents/development/devops-bot/) | CI/CD and infrastructure helper | Community |
| [🧪 TestCrafter](agents/development/test-crafter/) | Test case generator | Community |
| [🏗️ Architect](agents/development/architect/) | System design consultant | Community |

### Marketing & Content

| Agent | Description | Author |
|-------|-------------|--------|
| [✍️ Echo](agents/marketing/echo/) | Content writer for blogs, social, emails | [@openclaw](https://github.com/openclaw) |
| [🐦 TweetCrafter](agents/marketing/tweet-crafter/) | Viral Twitter/X thread creator | Community |
| [🔍 SEOExpert](agents/marketing/seo-expert/) | SEO optimization specialist | Community |
| [📰 NewsletterPro](agents/marketing/newsletter-pro/) | Email newsletter writer | Community |
| [🎨 CopyMaster](agents/marketing/copy-master/) | Sales and ad copy specialist | Community |
| [📱 SocialScheduler](agents/marketing/social-scheduler/) | Multi-platform content planner | Community |

### Business

| Agent | Description | Author |
|-------|-------------|--------|
| [📊 Radar](agents/business/radar/) | Data analyst and insights generator | [@openclaw](https://github.com/openclaw) |
| [💼 CEOAssistant](agents/business/ceo-assistant/) | Executive support and decision helper | Community |
| [📈 SalesCoach](agents/business/sales-coach/) | Sales strategy and outreach | Community |
| [🤝 CustomerSuccess](agents/business/customer-success/) | Customer support and retention | Community |
| [📑 ContractReviewer](agents/business/contract-reviewer/) | Legal document analyzer | Community |
| [💰 FinanceAdvisor](agents/business/finance-advisor/) | Budget and financial planning | Community |

### Personal

| Agent | Description | Author |
|-------|-------------|--------|
| [🏠 HomeManager](agents/personal/home-manager/) | Household task coordinator | Community |
| [🏋️ FitnessCoach](agents/personal/fitness-coach/) | Workout and nutrition planner | Community |
| [📖 LearningBuddy](agents/personal/learning-buddy/) | Study assistant and tutor | Community |
| [✈️ TravelPlanner](agents/personal/travel-planner/) | Trip planning and booking helper | Community |
| [🧘 MindfulBot](agents/personal/mindful-bot/) | Mental wellness companion | Community |

---

## MCP Servers

Model Context Protocol servers to extend agent capabilities.

### Official

| Server | Description | Install |
|--------|-------------|---------|
| [@anthropic/mcp-server-fetch](https://github.com/anthropics/mcp-server-fetch) | Web fetching and browsing | `npx -y @anthropic/mcp-server-fetch` |
| [@anthropic/mcp-server-filesystem](https://github.com/anthropics/mcp-server-filesystem) | File system access | `npx -y @anthropic/mcp-server-filesystem` |

### Community

| Server | Description | Author |
|--------|-------------|--------|
| [mcp-notion](https://github.com/community/mcp-notion) | Notion integration | Community |
| [mcp-google-calendar](https://github.com/community/mcp-google-calendar) | Google Calendar access | Community |
| [mcp-github](https://github.com/community/mcp-github) | GitHub operations | Community |
| [mcp-slack](https://github.com/community/mcp-slack) | Slack messaging | Community |
| [mcp-postgres](https://github.com/community/mcp-postgres) | PostgreSQL queries | Community |
| [mcp-stripe](https://github.com/community/mcp-stripe) | Stripe payments | Community |
| [mcp-shopify](https://github.com/community/mcp-shopify) | Shopify store management | Community |
| [mcp-twitter](https://github.com/community/mcp-twitter) | Twitter/X posting | Community |
| [mcp-discord](https://github.com/community/mcp-discord) | Discord bot integration | Community |
| [mcp-linear](https://github.com/community/mcp-linear) | Linear issue tracking | Community |

---

## Integrations

Connect your agents to external services.

### Messaging

- [Telegram Integration](integrations/telegram/) - Chat with agents via Telegram
- [Slack Integration](integrations/slack/) - Slack workspace connection
- [Discord Integration](integrations/discord/) - Discord server bot
- [WhatsApp Integration](integrations/whatsapp/) - WhatsApp Business API

### Mobile

- [iOS Shortcuts](integrations/ios-shortcuts/) - Control agents from iPhone
- [iOS Widgets](integrations/ios-widgets/) - Home screen quick access
- [Android Tasker](integrations/android-tasker/) - Android automation

### Automation

- [n8n Workflows](integrations/n8n/) - n8n integration nodes
- [Zapier](integrations/zapier/) - Zapier connection
- [Make.com](integrations/make/) - Make scenarios
- [GitHub Actions](integrations/github-actions/) - CI/CD integration

---

## Tools

Utilities and helpers for working with OpenClaw.

### CLI Tools

| Tool | Description |
|------|-------------|
| [openclaw-cli](tools/openclaw-cli/) | Official command line interface |
| [agent-validator](tools/agent-validator/) | Validate SOUL.md syntax |
| [mcp-tester](tools/mcp-tester/) | Test MCP server connections |

### Development

| Tool | Description |
|------|-------------|
| [openclaw-sdk-typescript](tools/sdk-typescript/) | TypeScript SDK |
| [openclaw-sdk-python](tools/sdk-python/) | Python SDK |
| [agent-debugger](tools/agent-debugger/) | Debug agent conversations |

### Monitoring

| Tool | Description |
|------|-------------|
| [agent-analytics](tools/agent-analytics/) | Usage analytics dashboard |
| [cost-tracker](tools/cost-tracker/) | API cost monitoring |
| [health-checker](tools/health-checker/) | Gateway health monitoring |

---

## Tutorials

Learn how to build and deploy agents.

### Getting Started

- [Quick Start Guide](tutorials/quickstart.md) - First agent in 5 minutes
- [SOUL.md Anatomy](tutorials/soul-anatomy.md) - Understanding agent configuration
- [MCP Basics](tutorials/mcp-basics.md) - Adding tools to agents

### Intermediate

- [Multi-Agent Workflows](tutorials/multi-agent.md) - Agents working together
- [Telegram Bot Setup](tutorials/telegram-setup.md) - Mobile access
- [iOS Shortcuts Guide](tutorials/ios-shortcuts.md) - iPhone integration

### Advanced

- [Custom MCP Servers](tutorials/custom-mcp.md) - Build your own tools
- [Agent Memory](tutorials/agent-memory.md) - Persistent context
- [Production Deployment](tutorials/production.md) - Railway, Fly.io, etc.

### Video Tutorials

- [YouTube: OpenClaw in 10 Minutes](https://youtube.com/watch?v=xxx)
- [YouTube: Building Your First Agent](https://youtube.com/watch?v=xxx)
- [YouTube: iOS Shortcuts Deep Dive](https://youtube.com/watch?v=xxx)

---

## Community

### Projects

Awesome projects built with OpenClaw:

| Project | Description | Author |
|---------|-------------|--------|
| [AI Content Studio](https://github.com/xxx) | Multi-agent content pipeline | @xxx |
| [DevOps Copilot](https://github.com/xxx) | Infrastructure automation | @xxx |
| [Personal CRM](https://github.com/xxx) | AI-powered relationship manager | @xxx |

### Articles

- [Building an AI Team That Works 24/7](https://medium.com/xxx)
- [OpenClaw vs AutoGPT vs CrewAI](https://dev.to/xxx)
- [The Future of AI Agents](https://blog.xxx.com)

### Podcasts

- [AI Agents Weekly - Episode 42](https://podcast.xxx)
- [The Claude Cast - OpenClaw Deep Dive](https://podcast.xxx)

---

## Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md).

### How to Add an Agent

1. Fork this repository
2. Create folder: `agents/[category]/[agent-name]/`
3. Add `SOUL.md` and `README.md`
4. Submit a Pull Request

### Agent Template

```markdown
# Agent Name

Brief description of what this agent does.

## Use Cases

- Use case 1
- Use case 2

## Setup

\`\`\`bash
openclaw agents add agent-name --workspace ./agents/agent-name
\`\`\`

## Example Prompts

- "Example prompt 1"
- "Example prompt 2"
```

---

## Related Projects

- [OpenClaw](https://github.com/anthropics/claude-code) - Official OpenClaw repository
- [Clawdbot](https://github.com/xxx/clawdbot) - Advanced coordinator agent
- [MoltBot](https://github.com/xxx/moltbot) - Content transformation agent
- [Anthropic MCP](https://github.com/anthropics/mcp) - Model Context Protocol

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=username/awesome-openclaw-agents&type=Date)](https://star-history.com/#username/awesome-openclaw-agents&Date)

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.

---

<p align="center">
  Made with 🦞 by the OpenClaw Community
</p>
