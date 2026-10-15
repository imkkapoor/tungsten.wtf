# tungsten.wtf

Tungsten is an AI agent orchestrator for macOS. It runs coding agents in terminals side by side on an
infinite canvas, with each agent working in its own git worktree. Claude Code, Codex and Pi have
built-in support, and any other CLI agent runs too.

Website: [tungsten.wtf](https://tungsten.wtf)

This repo holds the releases. macOS on Apple Silicon.

## Install

1. Download the `.dmg` from [Releases](https://github.com/imkkapoor/tungsten.wtf/releases).
2. Drag Tungsten to `/Applications`.
3. Run this once, or it will not open:

```
xattr -dr com.apple.quarantine /Applications/Tungsten.app
```

Tungsten is ad-hoc signed, with no Developer ID and no notarization. A copy that crossed the network
carries a quarantine flag and dies with **"Tungsten is damaged and can't be opened"** — that is the
signing policy, not a broken build. Step 3 clears it.

There is no auto-update. The app tells you when a release is out; the download is by hand.
