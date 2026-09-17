# tungsten.wtf

Releases for Tungsten. macOS on Apple Silicon.

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
