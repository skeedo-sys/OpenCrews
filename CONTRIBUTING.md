# Contributing to Awesome OpenClaw Agents

First off, thank you for considering contributing! 🦞

This project thrives on community contributions. Whether you're adding a new agent template, fixing a typo, or improving documentation, your help is appreciated.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Adding an Agent Template](#adding-an-agent-template)
- [Adding an MCP Server](#adding-an-mcp-server)
- [Adding a Tutorial](#adding-a-tutorial)
- [Style Guidelines](#style-guidelines)
- [Pull Request Process](#pull-request-process)

---

## Code of Conduct

Be kind, respectful, and constructive. We're all here to build cool things with AI.

---

## How Can I Contribute?

### 🤖 Add Agent Templates
Share your custom agents with the community.

### 🔧 Add MCP Servers
Document new MCP servers you've discovered or created.

### 📚 Improve Documentation
Fix typos, clarify instructions, add examples.

### 🔗 Add Resources
Share tutorials, articles, videos, or tools.

### 🐛 Report Issues
Found a broken link or outdated info? Open an issue.

---

## Adding an Agent Template

### Step 1: Fork & Clone

```bash
git clone https://github.com/YOUR-USERNAME/awesome-openclaw-agents.git
cd awesome-openclaw-agents
```

### Step 2: Create Agent Folder

Choose the right category:
- `agents/productivity/` - Task management, coordination
- `agents/development/` - Coding, DevOps, testing
- `agents/marketing/` - Content, social media, SEO
- `agents/business/` - Analytics, sales, finance
- `agents/personal/` - Health, learning, lifestyle

```bash
mkdir -p agents/[category]/[agent-name]/
```

### Step 3: Create SOUL.md

This is the agent's personality file:

```markdown
# Agent Name

Brief description of the agent.

## Core Identity

- **Role:** What the agent does
- **Personality:** How it behaves
- **Communication:** How it talks

## Responsibilities

1. **Primary Task**
   - Detail 1
   - Detail 2

2. **Secondary Task**
   - Detail 1
   - Detail 2

## Behavioral Guidelines

### Do:
- Good behavior 1
- Good behavior 2

### Don't:
- Bad behavior 1
- Bad behavior 2

## Example Interactions

**User:** Example prompt
**Agent:** Example response
```

### Step 4: Create README.md

```markdown
# 🎯 Agent Name

> One-line description

## Overview

What this agent does and why it's useful.

## Quick Start

\`\`\`bash
# Installation commands
\`\`\`

## Use Cases

| Request | Output |
|---------|--------|
| Example 1 | Result 1 |
| Example 2 | Result 2 |

## Example

\`\`\`
You: Example prompt
Agent: Example response
\`\`\`

## Author

Created by [@your-username](https://github.com/your-username)
```

### Step 5: Update Main README

Add your agent to the appropriate table in the main `README.md`:

```markdown
| [🎯 AgentName](agents/category/agent-name/) | Brief description | [@username](https://github.com/username) |
```

### Step 6: Submit PR

```bash
git add .
git commit -m "Add [AgentName] agent template"
git push origin main
```

Then open a Pull Request.

---

## Adding an MCP Server

### In README.md, add to the MCP Servers section:

```markdown
| [mcp-service-name](https://github.com/xxx) | What it does | Author |
```

### If you created the server, consider:

1. Adding a folder in `tools/mcp-servers/[name]/`
2. Including configuration examples
3. Adding usage documentation

---

## Adding a Tutorial

### Step 1: Create Tutorial File

```bash
touch tutorials/[tutorial-name].md
```

### Step 2: Follow Structure

```markdown
# Tutorial Title

Brief description of what the reader will learn.

## Prerequisites

- Requirement 1
- Requirement 2

## Step 1: First Step

Explanation...

\`\`\`bash
# Commands
\`\`\`

## Step 2: Second Step

...

## Conclusion

Summary of what was accomplished.

## Next Steps

- Link to related tutorial 1
- Link to related tutorial 2
```

### Step 3: Add to README

Link your tutorial in the Tutorials section.

---

## Style Guidelines

### Agent Names
- Use descriptive names: `CodeReviewer` not `CR`
- CamelCase for multi-word names
- Include emoji in display name: `🎯 Orion`

### SOUL.md Format
- Use clear headers with `##`
- Include example interactions
- Keep behavioral guidelines specific
- Add integration notes if applicable

### README Format
- Start with emoji + name as title
- Include Quick Start section
- Add use case table
- Show example output
- Credit the author

### Markdown
- Use fenced code blocks with language hints
- Use tables for comparisons
- Keep lines under 100 characters
- One sentence per line in paragraphs

---

## Pull Request Process

### Before Submitting

- [ ] Agent tested with OpenClaw
- [ ] SOUL.md follows template
- [ ] README.md included
- [ ] Added to main README.md table
- [ ] No broken links
- [ ] Spell-checked

### PR Title Format

```
Add [AgentName] agent template
Add [mcp-xxx] to MCP servers
Add [Topic] tutorial
Fix: [description]
```

### PR Description Template

```markdown
## What

Brief description of what you're adding/changing.

## Why

Why is this valuable to the community?

## Testing

How did you test this agent/resource?

## Checklist

- [ ] Follows contribution guidelines
- [ ] Tested locally
- [ ] Documentation complete
```

### Review Process

1. Maintainer reviews within 48 hours
2. Feedback provided if changes needed
3. Once approved, merged to main

---

## Questions?

- Open an issue with the `question` label
- Join our Discord community
- Email: maintainer@example.com

---

Thank you for contributing! 🦞
