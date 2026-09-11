# Lenz — your phone as a wireless webcam for Windows 11

Lenz turns an Android phone into a sharp, low-latency wireless webcam. Windows sees it as a normal camera called
**Lenz Camera**, so it works in Discord, OBS, Teams, Zoom and your browser. Free beta, no account, no watermark.

**Website:** https://btparov-eng.github.io/lenz/

## Download

Get both files from the [latest release](https://github.com/btparov-eng/lenz/releases/latest):

* `Lenz-Setup-<version>.exe` — the Windows app (Windows 11 22H2 or newer, 64-bit)
* `Lenz-phone-<version>.apk` — the Android app (Android 9 or newer)

Windows shows *"Windows protected your PC"* because the installer is not code-signed yet: **More info → Run anyway**.
On the phone, allow your browser or file manager to install the APK. Each release lists the SHA-256 of both files.

## Setup

1. Install and open Lenz on the PC and on the phone. Both must be on the same WiFi.
2. The phone appears on the PC: press **Connect**. Check that the same 6-digit code shows on both screens, then accept
   on both. You only do this once.
3. In your app (Discord, OBS, Teams, …) choose **Lenz Camera**.

## Problems or ideas?

Open an [issue](https://github.com/btparov-eng/lenz/issues). In the PC app, *About & diagnostics → Copy diagnostics*
copies the details that help fix it; paste them into the issue.

## Privacy

No accounts, no analytics, no servers: the video goes only from your phone to your PC, encrypted, on your local
network. Read the [privacy policy](https://btparov-eng.github.io/lenz/privacy.html).

---

This repository hosts the website, the downloads and the issue tracker. The source code is not public.
