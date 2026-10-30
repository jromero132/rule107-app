# Rule 107 client

The Rule 107 client sits next to your F1 game, reads the game's UDP telemetry and
sends it to your [Rule 107](https://rule107.com) account, so your laps, live
dashboard, history and leaderboards are always up to date.

Supports **F1 25** and **F1 26**.

## Download

Always the latest version:

| Platform | Download |
|---|---|
| Windows 10 or newer | [Rule107-windows-x64.zip](https://github.com/jromero132/rule107-app/releases/latest/download/Rule107-windows-x64.zip) |
| macOS (Apple silicon & Intel) | [Rule107-macos.zip](https://github.com/jromero132/rule107-app/releases/latest/download/Rule107-macos.zip) |
| Linux x64 | [Rule107-linux-x64.tar.gz](https://github.com/jromero132/rule107-app/releases/latest/download/Rule107-linux-x64.tar.gz) |

Older versions are on the [Releases](https://github.com/jromero132/rule107-app/releases)
page. Android and iOS apps are coming soon.

## Getting started

1. Create a free account at [rule107.com](https://rule107.com/get-started).
2. Unzip the download and run the app.
3. Paste your **unique identifier** (shown on your profile page) into the app.
4. In the game, open **Settings → Telemetry Settings** and set:
   - UDP Telemetry: **On**
   - UDP Broadcast Mode: **Off**
   - UDP IP Address and UDP Port: the values shown by the app (default port `20777`)
   - UDP Send Rate: **60Hz** (30Hz also works)
   - UDP Format: the newest available
   - Your Telemetry: **Public**
5. Start a session and drive. Your laps appear on your dashboard.

## First launch

The builds are not yet code-signed, so your system may warn you the first time:

- **Windows:** on "Windows protected your PC", choose **More info → Run anyway**.
- **macOS:** right-click the app, choose **Open**, then confirm.
- **Linux:** extract the archive and run the `rule107_client` executable.

## Updating

Download the latest version from the table above and replace the old one. Your
settings are kept.

## Help and feedback

Use the feedback form on [rule107.com](https://rule107.com), or write to
support@yukabyte.com. This repository only hosts release builds; it does not
accept source contributions.

## License

See [license-app](license-app). Rule 107 is not affiliated with, endorsed by or
sponsored by Formula 1, the FIA or Codemasters/EA.
