---
name: hermes-gateway-restart
description: "Restart/reload the Hermes gateway to apply config.yaml changes (model.default, provider, toolsets, etc.), especially when the normal `hermes gateway restart` is BLOCKED because you are running inside the gateway/desktop process itself. Covers the self-kill guard, the working bypass (`_HERMES_GATEWAY=0`), and post-restart verification."
version: 1.0.0
author: Hermes Agent
license: MIT
platforms: [linux, macos, windows]
tags: [general]
---

# Hermes Gateway Restart — Skill

Restart/reload the Hermes gateway to apply config.yaml changes (model.default, provider, toolsets, etc.), especially when the normal `hermes gateway restart` is BLOCKED because you are running inside the gateway/desktop process itself. Covers the self-kill guard, the working bypass (`_HERMES_GATEWAY=0`), and post-restart verification.

## Install

```bash
cp -r <skill-name> ~/.hermes/skills/<skill-path>/
```

Or clone this repository:

```bash
git clone https://github.com/iizcm/hermes-gateway-restart-skill.git ~/.hermes/skills/<skill-path>/
```

## Usage

Invoke your AI agent with a clear instruction matching this skill's purpose. The agent will route tasks to this skill when the instruction matches its description or trigger keywords.

Refer to `README.md` in this repository for:
- Detailed step-by-step installation guide
- Bilingual documentation (English + Indonesian)
- Troubleshooting table
- Security best practices
- Customization tips

## Safety rules

- Never commit private keys, seed phrases, API tokens, or personal data to version control
- Use placeholders (`<YOUR_...>`) in all examples and code snippets
- Validate all outputs before acting on them
- Keep real credentials in your runtime's secure credential store only
