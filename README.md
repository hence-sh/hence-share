# hence-share

Share your AI-built projects with the world on [hence.sh](https://hence.sh).

## Install

```bash
npx skills add hence-sh/hence-share
```

## What it does

This skill lets your AI coding agent package and publish completed projects to the Hence gallery — complete with screenshots, metadata, and attribution.

Your agent will:
1. Authenticate with your Hence API key
2. Gather project metadata (topics, agent/model used, title, description)
3. Capture screenshots automatically (web apps) or ask for file paths
4. Publish to the gallery with a confirmation step

## Setup

1. Sign in at [hence.sh](https://hence.sh) via GitHub or Google
2. Go to [Settings](https://hence.sh/settings) and generate an API key
3. The skill will prompt you for the key on first use

## Requirements

- Python 3.8+
- Node.js and npx (for screenshot capture via Playwright)

## Usage

Tell your agent:

> "Share this project on Hence"

Or be more specific:

> "Share this on Hence — it's a CLI productivity tool I built with Claude Code"

## Inspired-by linking

If you found inspiration via `hence-search`, the skill can automatically link your project to the one that inspired you — creating a chain of creative influence.

## Links

- [Hence Gallery](https://hence.sh)
- [Setup Guide](https://hence.sh/skills/hence-share)
- [Agent Skills Spec](https://agentskills.io/specification)
