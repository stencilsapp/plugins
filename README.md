# Stencils plugins

Plugins that connect your agent to [Stencils](https://stencils.app), the design tool whose canvas is real HTML and CSS. With one installed, your agent can read your designs (their layers, styles, text and screenshots) and write to the canvas as you watch: build a screen from your codebase, turn a design into code, or tidy up a page.

There are two plugins. Pick the one for where your agent runs:

| Plugin | Use it | How it connects |
| --- | --- | --- |
| `stencils` | On a Mac with [Stencils for Mac](https://stencils.app/docs/getting-started/install/) | Through the app: nothing to sign in to, faster edits, and your Mac's fonts. While the app is closed, through Stencils' servers. Open Stencils and sign in once first. |
| `stencils-remote` | Anywhere else, such as another computer or a cloud agent | Through Stencils' servers at `https://mcp.stencils.app`. Your agent signs in with your Stencils account in your browser the first time. |

Both need a Stencils account with a subscription.

## Claude Code

```sh
claude plugin install stencils --marketplace stencilsapp/plugins
```

Or, in Claude Code, run `/plugin install stencils --marketplace stencilsapp/plugins`. To connect through Stencils' servers, install `stencils-remote` instead, then run `/mcp`, choose `stencils-remote` and sign in.

## Codex

```sh
codex plugin marketplace add stencilsapp/plugins
codex plugin add stencils@stencils
```

Add `stencils-remote@stencils` instead to connect through Stencils' servers. Codex opens your browser to sign in.

## Other agents

See [Connect your agent](https://stencils.app/docs/mcp/connect-your-agent/) for Cursor, VS Code, GitHub Copilot, OpenCode, Antigravity and other agents, and for setting up Claude Code or Codex by hand.

## Try it

Once it's connected, try one of these:

- "Describe the design on the current page"
- "Design a pricing page with three plans"
- "Make the buttons on this page consistent"
