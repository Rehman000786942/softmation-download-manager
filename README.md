# Softmation Download Manager

A fast download manager for Windows by **Softmation Inc**. It downloads files over many connections at once, continues where it stopped, grabs videos and whole YouTube playlists, and catches downloads straight from your browser.

**[Download the latest version](https://github.com/Rehman000786942/softmation-download-manager/releases/latest)**

---

## Features

### Fast, reliable downloads
- **Multi-connection downloading.** Each file is split into parts that download at the same time. When a part finishes, its connection helps the slowest one, so the download stays at full speed right to the end.
- **Pause and resume.** Stop a download and continue later, even after closing the app or restarting the PC. Nothing already downloaded is lost.
- **Automatic retry.** A dropped connection or a busy server doesn't fail the download. It retries by itself (10 times by default) and waits for the internet to come back if it goes down.
- **Refresh expired links.** Many sites give links that stop working after a while. Right-click the download, choose **Refresh download address**, paste a new link to the same file, and it continues where it stopped. When your browser hands over the same file again, the app offers to continue the old download with it.
- **Smart file names.** Links like `download.php?id=1` are saved under the file's real name (for example `report.pdf`). Pages that need a click in the browser are detected instead of being saved as a web page.
- **Speed limiter.** Limit all downloads, or a single one, so the rest of your internet stays usable.

### Video and YouTube
- **Video downloads** from YouTube and over 1,800 other sites.
- **Choose the quality.** Paste a video link and pick the resolution (up to 4K) or audio only (M4A), each with its download size.
- **Whole playlists.** Paste a YouTube playlist or channel link. Every video is listed with a tick box: pick the ones you want and one quality for all, and they download into a folder named after the playlist, numbered in order.
- **Live progress** with speed and time left, including while video and audio are merged.

### Adding downloads
- **Browser extension** for Chrome and Edge: downloads you start in the browser go to the app, and a download button appears on videos.
- **Clipboard watching.** Copy a file, video or playlist link anywhere and the download window opens. Ordinary page links are ignored. It can be turned off in Options.
- **Batch download.** Paste many links at once, or use a pattern: `https://site.com/photo*.jpg` from 1 to 50 (with 01, 02 numbering, or letters a to z).
- **Site Grabber.** Enter a web page and get a list of every file on it (videos, music, documents, archives, programs and pictures), optionally including the pages it links to. Tick the files you want and download them.

### Organised
- **Categories.** Files are sorted into Video, Music, Documents, Compressed and Programs folders automatically. You can add your own categories.
- **Scheduler.** Set times when downloads run, and different speed limits for busy and quiet hours.
- **When done:** open the file or its folder, or have the PC shut down, sleep or hibernate after a download.
- **Runs in the tray.** Closing the window keeps downloads going in the background.

### Always up to date
- **Automatic updates.** When a new version is released the app offers **Update now**, then installs it and reopens by itself. Your downloads list and license are kept. You can also use Help > Check for updates.

---

## Install

1. Download **SoftmationDownloadManager-Setup-1.0.11.exe** from the [latest release](https://github.com/Rehman000786942/softmation-download-manager/releases/latest) and run it.
   - No administrator rights are needed. It installs for your Windows user only.
   - Windows may show "Windows protected your PC" because the installer is new. Click **More info**, then **Run anyway**.
2. Open **Softmation Download Manager** from the Start menu or desktop.

### Browser extension (Chrome or Edge)
1. Download **SoftmationDownloadManager-Extension-1.0.11.zip** and unzip it to a folder you'll keep (for example `Documents\Softmation Extension`). A copy is also in the app's install folder, under `browser-extension`.
2. Open `chrome://extensions` (or `edge://extensions`) and turn on **Developer mode**.
3. Click **Load unpacked** and choose the unzipped folder.

The installer already connects the extension to the app, so nothing else is needed.

---

## License and free trial

- **Free trial:** 10 downloads within 3 days of the first launch (an internet connection is needed to start it and to count trial downloads).
- **License key:** go to **Help > Registration and license info** and enter your key to download without limits. Keys work on one PC each. To move a key to a new PC, click **Remove from this PC** on the old one first.
- **Offline:** once registered, the app keeps working without internet.
- **License details:** the same window shows your key, expiry date, days left, trial downloads left, and a **Check now** button.

Get a license key at **https://amoura.softmation.live**. Support: **support@softmation.live**

---

## Requirements

- Windows 10 or Windows 11 (64-bit)
- About 500 MB of disk space
- Chrome or Edge, for the browser extension (optional)

---

## Release files

| File | What it is |
|---|---|
| `SoftmationDownloadManager-Setup-1.0.11.exe` | The app installer |
| `SoftmationDownloadManager-Extension-1.0.11.zip` | The Chrome / Edge extension |

SHA-256 checksums are listed in each release.

© Softmation Inc
