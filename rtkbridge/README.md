# RTKbridge

| Edition | Update manifest | Release history |
| --- | --- | --- |
| Full | [Stable manifest](full/stable/manifest.json) | [Full releases](https://github.com/datagnss/app-releases/releases?q=rtkbridge-full-) |
| Lite | [Stable manifest](lite/stable/manifest.json) | [Lite releases](https://github.com/datagnss/app-releases/releases?q=rtkbridge-lite-) |

Choose the `apkUrl` in the matching manifest to download the current signed APK. Full and Lite are different Android packages and have independent channels. Android installation requires confirmation; source authorization may be required.

Layout within each edition: `stable/manifest.json` is the current release; `versions/<versionCode>/manifest.json` records that version. Manifest fields are `versionCode`, `versionName`, `apkUrl`, `sizeBytes`, and `sha256`. A version must never be replaced with different bytes or moved backwards.

Older updater builds continue using their existing docs.datagnss.com manifest URLs, which mirror these channels. Old APK download paths are preserved. APK signature verification in the app remains required.
