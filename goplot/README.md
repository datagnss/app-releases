# goPlot

Windows amd64 portable GNSS analysis tool.

- [Download v0.0.6 (manual installation)](https://github.com/datagnss/app-releases/releases/download/goplot-v0.0.6/goPlot-latest-windows-amd64.zip)
- [Release and checksums](https://github.com/datagnss/app-releases/releases/tag/goplot-v0.0.6)
- [Stable update catalog](windows-amd64/stable/releases.json)
- [Version catalog](windows-amd64/versions/v0.0.6/releases.json)

The manual ZIP contains `goplot.exe` and `nmeacheck.exe`; RTKLIB is not included. The versioned ZIP contains `goplot.exe` for the updater and is verified with the existing goPlot Ed25519 release identity. Download and installation are initiated by the user.

Channel: `https://raw.githubusercontent.com/datagnss/app-releases/main/goplot/windows-amd64/stable/releases.json`. Clients using the old docs feed must first install a new-channel build manually. No old-feed transition was published.

Application source: `a540b18`; session log: `9e0d4a8`. Gitea goPlot PR #76 remains open. Public assets do not imply source merge or completed GUI install/restart and multi-DPI acceptance. Public catalog, asset bytes and updater signature/hash validation are verified separately.

Binary packages are GitHub Release attachments and are not stored in Git history.
