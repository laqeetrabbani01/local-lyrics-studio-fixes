# Local Lyrics

Make synced lyrics (with romaji) for your own local songs and see them in Spotify's lyrics view.

## What it does

- **Lyrics for your local songs** in Spotify's lyrics view, synced line by line, with romaji (or another
  romanization) under Japanese, Korean, Chinese, Hindi, Thai, Russian, Arabic and more.
- **Romaji for Spotify's own songs** too, and you can switch each song between original, romaji, or both.
- **Music videos** in Spotify's Video player for your local songs, with the lyrics on top as captions
  (the CC button or the C key turns them on and off).
- **Edit from Spotify** (2.4 and later): right-click a song › Local Lyrics to change its details, lyrics or video.
- **Downloads** (2.5 and later): right-click Spotify songs › Download (or use the Download button on a playlist
  or album) to keep an offline copy in your library. Local Lyrics finds each song on YouTube and saves it as an
  MP3; when your internet goes out, Spotify plays that copy instead. Tick "with music videos" to get the video too.
  Only download songs you have the right to keep a copy of.
- **Search with Local Lyrics** (2.6 and later): type in Spotify's search bar and press Shift+Enter, or paste a
  YouTube link and press Enter, then tick the songs and videos you want.
- Imported songs are evened out to Spotify's volume, so they aren't louder than everything else.

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
