# NANO toolbox

Windows amd64 portable GNSS utility with an NSGo interface.

- [Download v1.1.0](https://github.com/datagnss/app-releases/releases/download/nano-toolbox-v1.1.0/NANO-toolbox-v1.1.0-windows-amd64.zip)
- [Stable update catalog](windows-amd64/stable/releases.json)
- [Release history](https://github.com/datagnss/app-releases/releases?q=nano-toolbox-)

Extract and run `NANO-toolbox.exe`. Open About to check for updates; new versions are advertised in the main window. Packages and signed manifests are immutable GitHub Release assets. ZIP files never enter Git history.

The updater verifies the NANO toolbox Ed25519 identity, platform, version, signed size/SHA-256 and single executable archive. It preserves configuration, logs, projects, device firmware, RTKLIB and Plot. Application updates are separate from device firmware flashing.

Version v1.1.0 was built from NANO toolbox commit `694d8c0a22da9deef5bf585a1c5cd5e57cd0b0cc`. The published v1.0.4 installer was verified with the signed v1.1.0 package in an isolated Windows directory. It started NSGo and preserved the test settings.

[Third-party notices](https://github.com/datagnss/app-releases/releases/download/nano-toolbox-v1.1.0/NANO-toolbox-v1.1.0-third-party-notices.zip)
