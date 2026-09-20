# Saffron community

Bug reports, feature requests and questions for [Saffron](https://saffron-ai.io),
the Gherkin test runner that records a scenario once with an AI agent and
replays it in a real browser at zero tokens.

This repository holds no source code. Saffron is free to use and closed
source; this is where its users and its author talk.

| I want to | Go to |
|---|---|
| Report something broken | [New bug report](../../issues/new?template=bug.yml) |
| Ask for a feature | [New feature request](../../issues/new?template=feature.yml) |
| Ask a question, show what you built | [Discussions](../../discussions) |
| Read the docs | [saffron-ai.io/docs](https://saffron-ai.io/docs) |
| See what is planned | [Roadmap](https://saffron-ai.io/docs/roadmap) |
| See what changed | [Changelog](https://saffron-ai.io/docs/changelog) |

## Before you file a bug

1. Update first: `npm i -D saffron-ai@latest`. Fixes ship often.
2. Include `npx saffron --version`, your OS and your browser engine.
3. Attach the failing scenario's entry from `.saffron/reports/latest.json`
   if you can. **Check it for secrets first.** Saffron masks `{env:VAR}`
   values, but it cannot know about a secret your page displays.

## Packages

- Runner: [`saffron-ai` on npm](https://www.npmjs.com/package/saffron-ai)
- VS Code: [Saffron on the Marketplace](https://marketplace.visualstudio.com/items?itemName=ChathurangaJayasinghe.saffron-vscode)
- JetBrains: [Saffron on the Marketplace](https://plugins.jetbrains.com/plugin/34240-saffron)
- Claude Code: [saffron-claude-plugin](https://github.com/s-chathuranga-j/saffron-claude-plugin)

Security problem? Please do not open a public issue: email
genius.chathuranga@gmail.com.
