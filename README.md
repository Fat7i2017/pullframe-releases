# PullFrame

PullFrame is a polished desktop app for saving supported public media links through a clean local workflow.

Latest macOS version: **PullFrame 0.3.5**

**PullFrame 0.3.5 is the only current release (Apple Silicon macOS).** Older Windows beta packages are outdated and retained for historical reference.

## Download

Download the latest macOS version from the Releases page:

https://github.com/Fat7i2017/pullframe-releases/releases/latest

Current recommended release assets:

```text
macOS latest:    PullFrame-0.3.5.dmg
```

Direct downloads:

- macOS latest: https://github.com/Fat7i2017/pullframe-releases/releases/download/v0.3.5/PullFrame-0.3.5.dmg

## Windows status

There is no current Windows release. **PullFrame 0.3.3 Windows Beta is outdated**; a Windows 0.3.5 build has not been released.

Older Windows packages remain available in the release history, with outdated labels. Do not use the macOS DMG on Windows.

## Install on macOS

1. Download `PullFrame-0.3.5.dmg`.
2. Open the DMG file.
3. Drag PullFrame into Applications.
4. Open PullFrame from Applications.
5. If macOS blocks it, right-click / Control-click PullFrame, then choose Open.

PullFrame is not Apple-notarized yet, so macOS may show a first-open security warning. This warning should only need to be bypassed once per installed version.

## Legacy Windows beta installation (outdated)

1. Download `PullFrame-0.3.3-Windows.zip`.
2. Extract the ZIP first.
3. Open the extracted folder.
4. Run `PullFrame.exe` from inside the extracted folder.
5. If Windows SmartScreen appears, choose **More info**, then **Run anyway** only if you downloaded it from this official release repository.

Do not run PullFrame from inside the ZIP preview. Extract it first so Windows can access the included app files correctly.

## What PullFrame Does

- Analyze a supported media link
- Show available qualities and formats
- Download locally using bundled downloader tools
- Show title, thumbnail, duration, quality, format, estimated size, and progress
- Keep a local Downloads history with Download Again, Reveal, Copy Link, and Remove

## YouTube sign-in

If YouTube asks you to sign in, expand **YouTube sign-in** on Analyze and choose Chrome or Safari where you are already signed in. Browser access is off by default, applies to YouTube links, and is used consistently for analysis and downloading. macOS may request browser-data or Keychain access. YouTube rate limits may still require waiting.

## Updates

PullFrame checks this public releases repository for updates. The current macOS public release is 0.3.5. All older releases, including the Windows betas, are outdated and retained only as history.

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
