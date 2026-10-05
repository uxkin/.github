## Real UI, not AI slop.

[UXKIN](https://uxkin.com) gives coding agents real app and website designs to look at before they build a screen, so what they ship looks like a real product instead of the same purple gradient every time.

Works with Claude, Cursor, Codex, Windsurf, VS Code and any MCP client.

### What's here

| | What it does | Cost |
|---|---|---|
| [**agent**](https://github.com/uxkin/agent) | The UXKIN MCP server (`https://uxkin.com/mcp`): your agent searches real mobile screens, user flows and website designs while it works. Also holds the **no-ui-slop** skill. | Server needs a [UXKIN plan](https://uxkin.com/pricing); the skill is free |
| [**ui-check**](https://github.com/uxkin/ui-check) | A GitHub Action that reviews the UI code each pull request adds: buttons that do nothing, missing loading/empty/error states, one-off colours, accessibility basics. | Free, no account |

### Get started

- Connect your agent: [uxkin.com/docs](https://uxkin.com/docs)
- Add the pull request check: [`uses: uxkin/ui-check@v1`](https://github.com/uxkin/ui-check#usage)
- Browse the library: [mobile](https://uxkin.com/mobile) · [web](https://uxkin.com/web)

Questions: support@uxkin.com
