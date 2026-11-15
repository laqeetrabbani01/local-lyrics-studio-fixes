# Local Lyrics

Make synced lyrics (with romaji) for your own local songs and see them in Spotify's lyrics view.

## Download

Get the newest version from **[Releases](https://github.com/laqeetrabbani01/local-lyrics-studio-fixes/releases/latest)**:

- **Mac (Apple Silicon):** `Local-Lyrics-…-mac-arm64.zip`. Unzip it and drag the app into Applications. The app isn't signed by Apple yet, so the first time, open Terminal and run:
  ```
  xattr -cr "/Applications/Local Lyrics.app"
  ```
  Then open it normally.
- **Windows:** `Local-Lyrics-…-windows-setup.exe` (installer) or the `windows-x64.zip`. If Windows SmartScreen warns you, click **More info**, then **Run anyway**.

## What's in this repo

`updates/patches.signed.json` is a signed fix file the app downloads only when a Spotify update breaks the lyrics. The app rejects anything not signed with the project's key.
