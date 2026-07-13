# skills

A collection of [Agent Skills](https://docs.claude.com/en/docs/claude-code/skills) for Claude Code and other agents.

| Skill | What it does | Docs |
|-------|--------------|------|
| [`pirate-mode`](skills/pirate-mode/SKILL.md) | Fast, no-bureaucracy development mode. Say "pirate mode" and Claude ships by the shortest honest route — pirate tone included. | [docs/pirate-mode.md](docs/pirate-mode.md) |
| [`design-psychology`](skills/design-psychology/SKILL.md) | A pre-design interview grounded in behavioral psychology: perception gap, smart defaults, goal gradient, loss aversion and more. Claude grills you until the design brief actually makes sense. | [docs/design-psychology.md](docs/design-psychology.md) |

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

Both skills become available immediately — `pirate-mode` triggers on request ("pirate mode"), `design-psychology` is invoked explicitly.

## Layout

```
skills/
  pirate-mode/SKILL.md
  design-psychology/SKILL.md
docs/
  pirate-mode.md
  design-psychology.md
.claude-plugin/marketplace.json
```

Each skill is a single `SKILL.md` with YAML frontmatter (`name`, `description`) — the standard Agent Skills format.
