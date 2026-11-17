# Stencils (remote)

Connects your agent to [Stencils](https://stencils.app), the design tool whose canvas is real HTML and CSS, through Stencils' servers at `https://mcp.stencils.app`. Your agent can read your designs (their layers, styles, text and screenshots) and write to the canvas, from any computer or from the cloud, with no app to install.

## Before you start

You need a Stencils account with a subscription. The first time your agent uses Stencils, it opens your browser to sign in: check the account, then click **Allow**. In Claude Code, run `/mcp` and choose `stencils` to sign in.

On a Mac with Stencils installed, the `stencils` plugin is faster, and it uses your Mac's fonts.

## Install

In Claude Code:

```sh
claude plugin install stencils-remote --marketplace stencilsapp/plugins
```

In Codex:

```sh
codex plugin marketplace add stencilsapp/plugins
codex plugin add stencils-remote@stencils
```

## Try it

- "Describe the design on the current page"
- "Design a pricing page with three plans"
- "Make the buttons on this page consistent"

More in [Connect your agent](https://stencils.app/docs/mcp/connect-your-agent/).
