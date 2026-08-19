# SilentDelete

A [Vencord](https://github.com/Vendicated/Vencord) userplugin that "silently" deletes your messages. It replaces the original text with a placeholder first so message loggers capture the dummy content instead of what you actually wrote.

## Features

- Silent delete from the message popover (trash icon)
- `/silentpurge` command to silently delete your recent messages in the current channel (1–100)
- Optional silent delete when you submit an empty edit
- Context menu action to silent-delete already-removed message history
- Configurable replacement text, delay, accent color, and notification suppression

## Author

- Discord: **Nandak070** (`1219803151180370021`)
- GitHub: [nanda070](https://github.com/nanda070)

## Install

This is a Vencord *userplugin* (source-only, not on the plugin store), so it needs a local Vencord build.

1. Build [Vencord from source](https://docs.vencord.dev/installing/custom-plugins/)
2. Copy this folder to `Vencord/src/userplugins/SilentDelete`
3. Rebuild Vencord (`pnpm build`)
4. Restart Discord (quit from the tray icon)
5. Enable **SilentDelete** in Settings → Vencord → Plugins

## Disclaimer

Educational use only. Automating or concealing message deletion may violate [Discord's Terms of Service](https://discord.com/terms). Use at your own risk.
