# Lasso

Builds of Lasso, a Mac app for chatting with Claude about the Figma file you have open, by typing or by talking while you point at layers.

## Install

In Terminal, run:

```sh
curl -fsSL https://lasso-site.trylasso.workers.dev/install.sh | bash
```

It puts the latest Lasso in Applications and opens it; setup walks you through the rest. You need macOS 14 or later, the Figma desktop app, and [Claude Code](https://docs.claude.com/en/docs/claude-code) signed in to your Claude account.

Rather use a disk image? Download the `.dmg` from the [latest release](https://github.com/Dao-Ho/lasso-releases/releases/latest). Apple hasn't checked the app, so macOS blocks a copy downloaded in a browser the first time: open System Settings > Privacy & Security, click Open Anyway next to the message about Lasso, then open it again.

Installed copies update themselves from here.
