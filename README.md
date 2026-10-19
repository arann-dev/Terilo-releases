# Terilo downloads

Desktop SSH workspace for macOS, Ubuntu and Windows.

[Download the latest release](https://github.com/arann-dev/terilo-releases/releases/latest)

This public repository distributes installers, release notes and SHA-256 checksums only. Application source code is maintained separately and is not published here.

## Choose an installer

| Platform            | File           |
| ------------------- | -------------- |
| Ubuntu amd64        | `.deb`         |
| macOS Apple Silicon | `_aarch64.dmg` |
| macOS Intel         | `_x64.dmg`     |
| Windows x64         | `.exe`         |

Ubuntu installation: `sudo apt install ./FILE.deb` (replace `FILE` with the downloaded filename). OpenSSH Client is required. A hosted APT repository is not available yet.

Compare the downloaded installer's SHA-256 hash with `SHA256SUMS` attached to the same release. macOS builds are ad-hoc signed and not notarized; Windows builds are unsigned. Security warnings may appear. Install only if you trust the publisher.

GitHub's automatic “Source code” archives contain only the documentation in this distribution repository, not the app's source code.
