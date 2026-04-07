# PrintKK Agent Skill

An [Agent Skill](https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills) for the [PrintKK](https://www.printkk.com/) print-on-demand platform. Teaches AI coding agents how to use the PrintKK API effectively — data model, workflow patterns, and gotchas.

## What this skill covers

- **Image management** — upload, organize, update images and folders
- **Design creation** — create designs (async), poll task status, update metadata, brand designs
- **Order lifecycle** — create orders, pay via wallet, update addresses, cancel, track shipping
- **Product catalog** — browse categories, list products, get product details and print areas

## Compatibility

Works with any AI agent that supports the [SKILL.md open standard](https://agentskills.io):

| Agent | Install path |
|-------|-------------|
| Claude Code | `~/.claude/skills/printkk/SKILL.md` |
| OpenAI Codex | `~/.codex/skills/printkk/SKILL.md` |
| Cursor | `.cursor/rules/printkk.md` |
| VS Code Copilot | `.github/copilot-instructions.md` |
| Windsurf | `.windsurfrules/printkk.md` |
| Gemini CLI | `.agents/skills/printkk/SKILL.md` |

## Quick install

### Claude Code

```bash
mkdir -p ~/.claude/skills/printkk
curl -o ~/.claude/skills/printkk/SKILL.md \
  https://raw.githubusercontent.com/printkk/printkk-agent-skill/main/printkk/SKILL.md
```

### OpenAI Codex

```bash
mkdir -p ~/.codex/skills/printkk
curl -o ~/.codex/skills/printkk/SKILL.md \
  https://raw.githubusercontent.com/printkk/printkk-agent-skill/main/printkk/SKILL.md
```

### Manual

Download `printkk/SKILL.md` and place it in the appropriate directory for your agent.

## API documentation

Full API reference: [https://api-docs.printkk.com/](https://api-docs.printkk.com/)

To get your API key: log in to [PrintKK Dashboard](https://dashboard.printkk.com) → **Settings** → **Api Management**

## About PrintKK

[PrintKK](https://www.printkk.com/) is a print-on-demand platform offering 1000+ customizable products across apparel, home decor, accessories, and more. PrintKK handles production and fulfillment with its own manufacturing network, shipping to 200+ countries.

- Website: [printkk.com](https://www.printkk.com/)
- Help Center: [printkk.com/help](https://www.printkk.com/help)
- Contact: support@printkk.com

## License

MIT License — see [LICENSE](LICENSE) for details.
