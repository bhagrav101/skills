# Skills

A collection of reusable skills for AI agents.

## Skills

- **Operating manual** — Interviews you about your patterns and turns what you confirm into a practical personal operating manual.

Example output (illustrative):

> **Rule:** When I miss the morning plan, restart at 3pm. Missing one block isn't missing the day.

## Install

### Claude Code

In Claude Code, add the marketplace and install the plugin:

```text
/plugin marketplace add bhagrav101/skills
/plugin install operating-manual@bhagrav-skills
```

### Other agents

```sh
npx skills@latest add bhagrav101/skills
```

### Claude.ai

Download `operating-manual.skill` from [Releases](https://github.com/bhagrav101/skills/releases), then upload it in Claude.ai's Skills settings and select **Save skill**.

## License

[MIT](LICENSE)
