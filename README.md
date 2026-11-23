# My Agent Skills

A personal, growing collection of skills for AI coding agents. This repository starts as a clean scaffold: add your own skills under `skills/` as you create them.

## Install

Install all skills and choose the agent(s) with the interactive prompt:

```bash
npx skills@latest add 0bi0n3/skills
```

Install one skill by name:

```bash
npx skills@latest add 0bi0n3/skills --skill=<skill-name>
```

To update installed skills, run `npx skills@latest update`. If you add new skills to this repository later, run the `add` command again to select them.

## Add a skill

1. Create `skills/<skill-name>/SKILL.md` (use lowercase kebab-case for the directory name).
2. Start from [`templates/SKILL.md`](./templates/SKILL.md) and write your own instructions.
3. Give the skill a concise `name` and a clear `description` in its YAML frontmatter. Put the skill's working instructions in the Markdown body.
4. Test it with your agent before sharing or relying on it.

See [`skills/README.md`](./skills/README.md) for the folder convention. This repository currently contains no ready-to-use skills; the template is only a starting outline.

## Compatibility

The `skills` CLI supports multiple agent harnesses, but support and installation behavior vary. Check the target agent's current documentation if installation or skill discovery does not work as expected.
