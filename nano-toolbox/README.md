# NANO toolbox

Windows amd64 portable GNSS utility.

- [Download v1.0.4](https://github.com/datagnss/app-releases/releases/download/nano-toolbox-v1.0.4/NANO-toolbox-v1.0.4-windows-amd64.zip)
- [Stable update catalog](windows-amd64/stable/releases.json)
- [Release history](https://github.com/datagnss/app-releases/releases?q=nano-toolbox-)

Extract and run `NANO-toolbox.exe`. Open About to check for updates; new versions are advertised in the main window. Packages and signed manifests are immutable GitHub Release assets. ZIP files never enter Git history.

The updater verifies the NANO toolbox Ed25519 identity, platform, version, signed size/SHA-256 and single executable archive. It preserves configuration, logs, projects, device firmware, RTKLIB and Plot. Application updates are separate from device firmware flashing.

First release source: nano-toolbox commit `6341cec7890d4036277f26a3fcddf6b0dea6c282`, PR #20 (not yet merged). Offline checks, signed downloads and local UI flow passed. Hardware operation and running-application replacement/restart acceptance remain pending.
