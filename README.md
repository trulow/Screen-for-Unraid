# Screen for Unraid

![Screen for Unraid](https://github.com/trulow/Screen-for-Unraid/blob/main/icon.png?raw=true)

A plugin for [Unraid](https://unraid.net) that installs [GNU Screen](https://www.gnu.org/software/screen/) — a terminal multiplexer that allows you to manage multiple persistent terminal sessions from a single SSH session.

## Installation

Go to the **Plugins** tab > **Install Plugin** and enter the following URL:

```
https://raw.githubusercontent.com/trulow/Screen-for-Unraid/main/plugin/Screen-for-Unraid.plg
```

Or install via Community Applications by searching for "Screen for Unraid".

## Usage

After installation, Screen is available via the command line:

```bash
screen --version
```

### Common screen commands

| Command | Description |
|---------|-------------|
| `screen -S session_name` | Start a new named session |
| `screen -ls` | List active sessions |
| `screen -r session_name` | Reattach to a session |
| `screen -d -r session_name` | Detach and reattach remotely |
| `Ctrl+A, d` | Detach from current session (within screen) |

## Package Source

```
https://slackware.pkgs.org/current/slackware-x86_64/
```

## Support

- **Forum thread:** https://forums.unraid.net/topic/168065-plugin-screen-for-terminal-unraid/
- **GitHub:** https://github.com/trulow/Screen-for-Unraid

## Changelog

### 2026.07.29
- Install screen-5.0.2-x86_64-1.txz with automatic checksum validation and mirror fallback

### 2026.05.17 (Provided by @rasooll)
- Removed the fixed screenBuild package value.
- Added dynamic lookup for the latest available screen-5.0.1-x86_64-*.txz build from CHECKSUMS.md5.
- Kept checksum validation before installation.
- Kept mirror fallback support.
- Updated the plugin version to 2026.05.17.
- Updated changelog entries in the plugin and README.

### 2026.05.17
- Install the latest available 5.0.1 build with automatic checksum validation and mirror fallback

### 2026.01.23
- Install 5.0.1 with automatic checksum validation and mirror fallback

### 2024.06.11
- Initial release to install screen-4.9.0-x86_64-1
