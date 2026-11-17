# Stencils

Connects your agent to [Stencils](https://stencils.app), the design tool whose canvas is real HTML and CSS, through the Stencils app on your Mac. Your agent can read your designs (their layers, styles, text and screenshots) and write to the canvas as you watch.

Through the app there's nothing to sign in to, edits are faster, and text uses the fonts installed on your Mac. While the app is closed, your agent keeps working through Stencils' servers.

## Before you start

1. Install [Stencils for Mac](https://stencils.app/docs/getting-started/install/). It installs the command this plugin starts, `~/.stencils/bin/stencils mcp`.
2. Open Stencils and sign in once, with an account that has a subscription.

Not on a Mac, or running your agent in the cloud? Use the `stencils-remote` plugin instead.

## Install

In Claude Code:

```sh
claude plugin install stencils --marketplace stencilsapp/plugins
```

In Codex:

```sh
codex plugin marketplace add stencilsapp/plugins
codex plugin add stencils@stencils
```

## Try it

- "Describe the design on the current page"
- "Design a pricing page with three plans"
- "Make the buttons on this page consistent"

More in [Connect your agent](https://stencils.app/docs/mcp/connect-your-agent/).
