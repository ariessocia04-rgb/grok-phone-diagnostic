# Grok Phone Diagnostic

Update channel used by the sideloaded APK.

- `update.json` — version + HTML/APK URLs
- `index.html` — diagnostic UI the app can hot-load

When you tell Grok to update the tool, Grok bumps `htmlRevision` / `versionCode` here. The installed app checks this file on launch.
