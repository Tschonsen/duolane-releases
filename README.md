<p align="center"><b>Duolane</b> — a shared planning board for you and Claude Code.</p>

## Download 0.10.0

| Platform | File |
|---|---|
| Windows 10/11 (x64) | [Duolane-Setup-0.10.0.exe](https://github.com/Tschonsen/duolane-releases/releases/download/v0.10.0/Duolane-Setup-0.10.0.exe) |
| macOS 12+ (Apple silicon: M1–M4) | [Duolane-0.10.0-arm64.dmg](https://github.com/Tschonsen/duolane-releases/releases/download/v0.10.0/Duolane-0.10.0-arm64.dmg) |
| macOS 12+ (Intel) | [Duolane-0.10.0-x64.dmg](https://github.com/Tschonsen/duolane-releases/releases/download/v0.10.0/Duolane-0.10.0-x64.dmg) |

**Windows:** the installer is not code-signed yet. SmartScreen asks once: *More info → Run anyway*. Later versions install themselves from inside the app.

**macOS (experimental):** open the dmg and drag Duolane into *Applications*. The app is not notarized, so run this once in Terminal:

```
xattr -cr /Applications/Duolane.app
```

The app tells you about new versions and opens the download.

**Requires** [Claude Code](https://docs.claude.com/en/docs/claude-code), installed and signed in. On first start, *Connect Claude Code* registers Duolane's MCP server.

Release notes and older versions: [Releases](https://github.com/Tschonsen/duolane-releases/releases).

This repository only hosts the installers. Duolane is proprietary software, see [LICENSE](LICENSE).
