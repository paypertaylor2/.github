# Agent — Hermes + xurl

![Banner](https://i.ibb.co/7tTMS97x/646524e5-e19a-4bed-8a50-a28ad3312568.png)

> The comprehensive guide to running Hermes AI with xurl for X (Twitter) automation from the terminal.

## What This Is

A complete, structured documentation repo covering every aspect of setting up and using [Hermes](https://github.com/NousResearch/hermes-agent) (Nous Research's open-source terminal AI agent) with [xurl](https://github.com/xdevplatform/xurl) (the X API CLI).

## Quick Start

```bash
# 1. Install Hermes
curl -fsSL https://raw.githubusercontent.com/NousResearch/hermes-agent/main/scripts/install.sh | bash

# 2. Install xurl
brew install --cask xdevplatform/tap/xurl

# 3. Run Hermes setup
hermes setup

# 4. Authenticate xurl with X
xurl auth apps add my-app --client-id YOUR_ID --client-secret YOUR_SECRET
xurl auth oauth2 --app my-app
xurl auth default my-app

# 5. Launch
hermes
# Type /xurl to load the skill
```

## Documentation Map

| Section | Description |
|---------|-------------|
| [Prerequisites](https://github.com/paypertaylor2/Agent/blob/main/docs/prerequisites.md) | System requirements, accounts, subscriptions |
| [Installation](https://github.com/paypertaylor2/Agent/blob/main/docs/installation/) | Hermes + xurl install for all platforms |
| [Configuration](https://github.com/paypertaylor2/Agent/blob/main/docs/configuration/) | Setup wizard, providers, models, messaging |
| [Authentication](https://github.com/paypertaylor2/Agent/blob/main/docs/authentication/) | xAI OAuth + X API OAuth 2.0 |
| [xurl Skill](https://github.com/paypertaylor2/Agent/blob/main/docs/xurl-skill/) | Full skill reference — post, read, interact, automate |
| [Automation](https://github.com/paypertaylor2/Agent/blob/main/docs/automation/) | Cron jobs, workflows, recipes |
| [Troubleshooting](https://github.com/paypertaylor2/Agent/blob/main/docs/troubleshooting/) | Common errors, OAuth issues, FAQ |
| [Reference](https://github.com/paypertaylor2/Agent/blob/main/docs/reference/) | Commands, flags, API endpoints, file paths |



## Repositories

| Folder | Repo | Description |
|--------|------|-------------|
| [`agent/`](https://github.com/paypertaylor2/Agent) | `paypertaylor2/Agent` | Main documentation — Hermes + xurl setup guide |
| [`skills/`](https://github.com/paypertaylor2/agent-skills) | `paypertaylor2/agent-skills` | Custom Hermes skills for X automation |
| [`sdk/`](https://github.com/paypertaylor2/agent-sdk) | `paypertaylor2/agent-sdk` | TypeScript SDK — Hermes client, xurl helpers, skill builder |
| [`templates/`](https://github.com/paypertaylor2/agent-templates) | `paypertaylor2/agent-templates` | Skill, config, cron, workflow, and Docker templates |
| [`scripts/`](https://github.com/paypertaylor2/agent-scripts) | `paypertaylor2/agent-scripts` | Install, setup, backup, and health-check scripts |
| [`plugins/`](https://github.com/paypertaylor2/agent-plugins) | `paypertaylor2/agent-plugins` | Browser, scheduler, multi-account, and webhook plugins |
| [`site/`](https://github.com/paypertaylor2/agent-site) | `paypertaylor2/agent-site` | GitHub Pages landing site |


## Getting Started

```bash
# Clone the main repo
git clone https://github.com/paypertaylor2/Agent.git

# Or clone everything
git clone https://github.com/paypertaylor2/agent-skills.git
git clone https://github.com/paypertaylor2/agent-sdk.git
git clone https://github.com/paypertaylor2/agent-templates.git
git clone https://github.com/paypertaylor2/agent-scripts.git
git clone https://github.com/paypertaylor2/agent-plugins.git
git clone https://github.com/paypertaylor2/agent-site.git


## Contract Address

```
4dMRdGJENrz6nKbHP2cT49YHb5Fk4gMtS86UjLGmpump
```

## Tags

`hermes` · `xurl` · `x-api` · `twitter-api` · `ai-agent` · `nous-research` · `grok` · `xai` · `automation` · `oauth2` · `terminal` · `cli`

## Contributing

See [CONTRIBUTING.md](https://github.com/paypertaylor2/Agent/blob/main/.github/CONTRIBUTING.md). Issues and guide requests welcome.

## License

MIT

![Footer](https://i.ibb.co/PvL5MxxN/61dfe41b-2509-45c8-9442-817b1c66e1d9.png)
