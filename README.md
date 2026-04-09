# 5uck1ess Plugins

Claude Code plugin marketplace.

## Available Plugins

| Plugin | Description | Install |
|--------|-------------|---------|
| [devkit](https://github.com/5uck1ess/devkit) | Workflows, multi-agent consensus, improvement loops, safety guardrails, RTK token optimization | `/plugin install devkit@5uck1ess-plugins` |

## Setup

Add this marketplace to Claude Code:

```
/plugin marketplace add 5uck1ess/marketplace
```

Then install any plugin:

```
/plugin install devkit@5uck1ess-plugins
```

> **Note:** If you get SSH errors during install, run this once to force HTTPS:
> ```bash
> git config --global url."https://github.com/".insteadOf "git@github.com:"
> ```
