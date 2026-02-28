# Ghostty — DoubleTrees Sepia

A warm, parchment-style Ghostty theme with calm contrast for long terminal sessions.

## Files

- `doubletrees-sepia.ghostty` — the theme config you can import/copy into Ghostty

## Install (Linux)

1. Create the Ghostty config directory (if it doesn’t exist):
   - `~/.config/ghostty/`

2. Copy the theme file:
   - Place `doubletrees-sepia.ghostty` somewhere you can reference (or keep it in this repo and copy it during setup).

3. Apply the theme
   - Open your Ghostty config and set the theme / colors to match this file.

## Notes

- This repo is meant to be cloned onto new machines so the exact palette stays consistent.

## Install (recommended)

Clone and copy the theme into your Ghostty config directory:

```bash
/bin/mkdir -p /home/zk/.config/ghostty/themes
/bin/cp -f /path/to/ghostty-doubletrees-sepia/doubletrees-sepia.ghostty \
  /home/zk/.config/ghostty/themes/doubletrees-sepia.ghostty
```

Then open your Ghostty config and reference/apply the theme settings.

## Quick update

/usr/bin/git -C /path/to/ghostty-doubletrees-sepia pull
/bin/cp -f /path/to/ghostty-doubletrees-sepia/doubletrees-sepia.ghostty \
~/.config/ghostty/themes/doubletrees-sepia.ghostty
