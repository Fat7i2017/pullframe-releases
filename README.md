# PullFrame

PullFrame is a polished desktop app for saving supported public media links through a clean local workflow.

Current version: **PullFrame 0.3.5**

**PullFrame 0.3.5 is the only current release.** It includes Apple Silicon macOS and a Windows x64 beta. Older releases are outdated and retained for historical reference.

## Download

Download the current macOS or Windows package from the Releases page:

https://github.com/Fat7i2017/pullframe-releases/releases/latest

Current recommended release assets:

```text
macOS (Apple Silicon):  PullFrame-0.3.5.dmg
Windows x64 beta:       PullFrame-0.3.5-Windows.zip
```

Direct downloads:

- macOS (Apple Silicon): https://github.com/Fat7i2017/pullframe-releases/releases/download/v0.3.5/PullFrame-0.3.5.dmg
- Windows x64 beta: https://github.com/Fat7i2017/pullframe-releases/releases/download/v0.3.5/PullFrame-0.3.5-Windows.zip

## Windows beta status

The 0.3.5 Windows package targets **Windows 10/11 x64** and requires [Microsoft Edge WebView2 Runtime](https://developer.microsoft.com/microsoft-edge/webview2/). Python and the downloader tools are bundled. It is an unsigned beta.

Built and automatically checked on GitHub’s Windows runner. **The desktop interface and a real YouTube download have not been manually verified on Windows.**

## Install on macOS

1. Download `PullFrame-0.3.5.dmg`.
2. Open the DMG file.
3. Drag PullFrame into Applications.
4. Open PullFrame from Applications.
5. If macOS blocks it, right-click / Control-click PullFrame, then choose Open.

PullFrame is not Apple-notarized yet, so macOS may show a first-open security warning. This warning should only need to be bypassed once per installed version.

## Install on Windows x64

1. Download `PullFrame-0.3.5-Windows.zip`.
2. Extract the entire ZIP to a writable folder.
3. Run `PullFrame.exe` from that folder; keep `_internal` beside it.

Do not run from inside the ZIP preview. Download only from this official release repository. History and logs are stored in `%LOCALAPPDATA%/PullFrame`; videos default to `Downloads/PullFrame`.

## What PullFrame Does

- Analyze a supported media link
- Show available qualities and formats
- Download locally using bundled downloader tools
- Show title, thumbnail, duration, quality, format, estimated size, and progress
- Keep a local Downloads history with Download Again, Reveal, Copy Link, and Remove

## YouTube sign-in

If YouTube asks you to sign in, expand **YouTube sign-in** on Analyze and choose a browser where you are already signed in (Chrome/Safari/Firefox on macOS; Chrome/Edge/Firefox on Windows). Browser access is off by default, applies to YouTube links, and is used consistently for analysis and downloading. macOS may request browser-data or Keychain access. Chrome/Edge may restrict Windows cookie access; Firefox can be selected if you are already signed in there. YouTube rate limits may still require waiting.

## Updates

PullFrame checks this public releases repository for updates. The current public release is 0.3.5, including the Windows x64 beta. All older releases and Windows betas are outdated and retained only as history.

## Bundled Tools

PullFrame includes:

- yt-dlp 2026.10.26
- FFmpeg 9.0.2
- FFprobe 9.0.2
- Deno 2.9.8 (bundled JavaScript runtime for YouTube challenges)

These tools run locally on your computer.

## Support

Support email:

```text
me@fat7i2017.com
```

Website:

https://pullframe.fat7i2017.com

## Safety and Legal Note

Use PullFrame only for content you own, have permission to download, or are legally allowed to save.

PullFrame is not affiliated with yt-dlp, FFmpeg, YouTube, Instagram, TikTok, X/Twitter, Vimeo, Facebook, Apple, Microsoft, or any supported platform.
