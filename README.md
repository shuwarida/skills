# skills

A collection of [Agent Skills](https://docs.claude.com/en/docs/claude-code/skills) for Claude Code and other agents.

| Skill | What it does | Docs |
|-------|--------------|------|
| [`pirate-mode`](skills/pirate-mode/SKILL.md) | Fast, no-bureaucracy development mode. Say "pirate mode" and Claude ships by the shortest honest route — pirate tone included. | [docs/pirate-mode.md](docs/pirate-mode.md) |
| [`design-thinking`](skills/design-thinking/SKILL.md) | A pre-brief interview run before any pixel exists: perception gap, the viewer's emotional state, predictive empathy, memory encoding, brand voice. Claude grills you until the brief actually makes sense. | [docs/design-thinking.md](docs/design-thinking.md) |
| [`design-ux`](skills/design-ux/SKILL.md) | A behavioral-psychology interview for screens and flows: smart defaults, goal gradient, reciprocity, IKEA effect, loss aversion, contrast. | [docs/design-ux.md](docs/design-ux.md) |

Every skill has a doc in [`docs/`](docs/) (`docs/<skill-name>.md`): quickstart, what it does, and when to reach for it.

## Quickstart with npx

Install a skill into the current project with the [skills](https://github.com/vercel-labs/skills) CLI:

```sh
npx skills add shuwarida/skills
```

Pick the skills you want from the interactive prompt, or install everything:

```sh
npx skills add shuwarida/skills --all
```

## Install as a Claude Code /plugin marketplace plugin

Add this repo as a marketplace, then install the plugin:

```
/plugin marketplace add shuwarida/skills
/plugin install shuwarida-skills@shuwarida-skills
```

All skills become available immediately — `pirate-mode` triggers on request ("pirate mode"), `design-thinking` and `design-ux` are invoked explicitly.

## Layout

```
skills/
  pirate-mode/SKILL.md
  design-thinking/SKILL.md
  design-ux/SKILL.md
docs/
  pirate-mode.md
  design-thinking.md
  design-ux.md
.claude-plugin/marketplace.json
```

Each skill is a single `SKILL.md` with YAML frontmatter (`name`, `description`) — the standard Agent Skills format.
