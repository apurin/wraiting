# wraiting

An agent skill for writing text that another AI will read as instructions or context: skills, CLAUDE.md and AGENTS.md, system prompts, subagent briefs and handovers, tool descriptions, specs, and plans.

It treats the reader as a capable model that lacks your context, and holds only guidance that changes how a model writes for that reader: supply what the reader cannot know, keep what binds it and the reasons that guide its judgment, preserve each statement's status through edits, turn user corrections into the rules behind them, and check important text with a fresh reader.

## Install

```sh
npx skills add apurin/wraiting
```

This installs into the current project; add `-g` to install it for all projects. Then ask your agent to write, review, or revise AI-facing text. The guidance is in [SKILL.md](SKILL.md).

## License

[MIT](LICENSE)
