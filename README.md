<p align="center">
  <img src="assets/app-icon.png" width="128" height="128" alt="Universal Display icon">
</p>

<h1 align="center">Universal Display</h1>

<p align="center">
  <strong>Turn the screens you already have into displays for your Mac.</strong><br>
  Use an Android tablet or another Mac as a real second display — and see and control your Mac from
  your phone, your tablet or another Mac.
</p>

<p align="center">
  <a href="https://github.com/hertlyhq/universal-display/releases/latest/download/UniversalDisplay-mac.zip"><img alt="Download for Mac" src="https://img.shields.io/badge/Download_for_Mac-macOS_14+-2A4BE8?style=for-the-badge&logo=apple&logoColor=white"></a>
  &nbsp;
  <a href="https://github.com/hertlyhq/universal-display/releases/latest/download/UniversalDisplay.apk"><img alt="Android app" src="https://img.shields.io/badge/Android_app-8.0+-3DDC84?style=for-the-badge&logo=android&logoColor=white"></a>
</p>

<p align="center">
  <a href="https://github.com/hertlyhq/universal-display/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/hertlyhq/universal-display?label=latest&color=5B67F5"></a>
  <a href="https://github.com/hertlyhq/universal-display/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/hertlyhq/universal-display/total?color=5B67F5"></a>
  <img alt="Apple silicon" src="https://img.shields.io/badge/Apple_silicon-native-111">
</p>

<p align="center">
  <img src="assets/hero.svg" width="100%" alt="A Mac extending its desktop onto a tablet">
</p>

<p align="center">
  <a href="#what-it-does">What it does</a> ·
  <a href="#get-started">Get started</a> ·
  <a href="#touch-and-keyboard">Touch and keyboard</a> ·
  <a href="#performance">Performance</a> ·
  <a href="#privacy-and-security">Privacy</a> ·
  <a href="#faq">FAQ</a>
</p>

## What it does

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>🖥️ Second display</h3>
      Turn an Android tablet into a true extended display — not a mirror. macOS sees a new monitor sized
      for the tablet: drag windows onto it, keep a chat or reference open, use it as a dashboard.
    </td>
    <td width="33%" valign="top">
      <h3>💻 Mac to Mac</h3>
      Use another Mac as a display with one click, over Wi‑Fi or — with the lowest latency, about
      15&nbsp;ms — a USB‑C cable between the two.
    </td>
    <td width="33%" valign="top">
      <h3>📱 Remote desktop</h3>
      See and control your Mac from an Android phone or tablet, or from another Mac. At home, or
      anywhere over <a href="https://tailscale.com">Tailscale</a>.
    </td>
  </tr>
</table>

### Highlights

- **⚡️ Smooth and sharp.** Hardware encoding on the Mac, hardware decoding on the device: ~57–60 fps
  with ~15–70 ms from Mac to screen. The pointer travels on its own, ahead of the picture, so it never
  lags.
- **📐 Looks native.** Text and windows keep the same physical size as on your Mac's own screen. Put the
  display left, right, above or below — it remembers where you put it.
- **🔌 USB, cable or Wi‑Fi — switch freely.** Unplug the tablet and the picture moves to Wi‑Fi without
  your windows jumping around. Nothing connects until you click **Connect**.
- **👆 Touch, trackpad and keyboard.** Tap, drag, scroll, pinch, three‑finger swipes between desktops,
  the on‑screen keyboard or a real one. [All gestures ↓](#touch-and-keyboard)
- **🔓 Even a locked Mac.** Remote desktop can unlock your Mac and keeps working through the lock screen.
- **🛡️ You stay in charge.** Touch your own mouse, trackpad or keyboard and remote control pauses until
  5 seconds after you stop — you never fight a remote pointer.
- **👀 Always know what's connected.** The menu bar icon changes when a device uses this Mac as a
  display or controls it, and the menu lists every connection.
- **🔄 Up to date by itself.** The Mac app updates itself, and keeps the tablet app updated too.

## Get started

### 1. Install on your Mac

1. [Download `UniversalDisplay-mac.zip`](https://github.com/hertlyhq/universal-display/releases/latest/download/UniversalDisplay-mac.zip),
   unzip it and move **Universal Display** to **Applications**.
2. Open it — it lives in the menu bar.
3. Allow **Screen Recording** when macOS asks (System Settings › Privacy & Security), then reopen the
   app.

> [!NOTE]
> Universal Display is a personal project and isn't notarized by Apple. If macOS won't open it the first
> time, go to **System Settings › Privacy & Security** and click **Open Anyway**.

### 2. Add a device

<details open>
<summary><b>Android tablet as a display</b></summary>

- **Over USB (easiest):** turn on *USB debugging* on the tablet (Settings › Developer options), plug it
  into the Mac and click **Connect** next to it in the menu. The Mac installs the tablet app for you and
  starts showing your screen.
- **Over Wi‑Fi:** install [`UniversalDisplay.apk`](https://github.com/hertlyhq/universal-display/releases/latest/download/UniversalDisplay.apk)
  and open it. Click **Connect** next to the tablet in the Mac's menu and type the 4‑digit code the
  tablet shows.

</details>

<details>
<summary><b>Another Mac as a display</b></summary>

Install Universal Display on both Macs. On the Mac you want to extend, click **Connect** next to the
other Mac and type the code it shows. For the lowest latency, connect the two with a USB‑C or
Thunderbolt cable — it's used automatically.

</details>

<details>
<summary><b>Control your Mac from a phone, tablet or another Mac</b></summary>

Open the app on the phone or tablet (or the **Remote Control** tab of the menu on another Mac) and pick
your Mac. It shows a 4‑digit code: type it on your Mac. Pair once at home; with
[Tailscale](https://tailscale.com) it keeps working away from home. Allow **Accessibility** on the Mac
when asked.

</details>

<details>
<summary><b>Control the Mac from the tablet you use as a display</b></summary>

Tap the tablet and press **Request control**, then **Allow** on your Mac — or click the cursor icon next
to the device in the menu. Allow **Accessibility** when macOS asks.

</details>

## Touch and keyboard

| On the tablet or phone | Does |
|---|---|
| Tap / double tap | Click / double click |
| Drag | Drag, select, move windows |
| Two‑finger drag | Scroll, with momentum |
| Long press or two‑finger tap | Right click |
| Pinch | Zoom in / out |
| Three‑finger swipe left / right | Switch desktops (Spaces) |
| Three‑finger swipe up / down | Mission Control / App windows |
| ⌨ button | On‑screen keyboard, with a row of Mac keys |

Remote desktop also offers a trackpad mode (move the pointer like on a laptop) besides direct touch.

## Performance

Measured on a MacBook Air (M3), a MacBook Pro (M1 Pro) and an 11" MediaTek tablet:

| Setup | Frame rate | Mac → screen |
|---|---:|---:|
| Mac → Mac, USB‑C cable | 55–60 fps | ~12–22 ms |
| Mac → Mac, Wi‑Fi | 55–60 fps | ~22–40 ms |
| Remote control Mac → Mac, Wi‑Fi | 57 fps | ~25–35 ms |
| Mac → tablet, USB | 57 fps | ~60 ms |
| Mac → tablet, Wi‑Fi | 57 fps | ~70 ms |

## Privacy and security

- **Nothing goes through a server.** The picture travels straight from your Mac to the device over USB,
  a cable or your local network. Away from home it goes over your own Tailscale network, encrypted end to
  end.
- **Pair once with a code.** A device can only connect after you type the 4‑digit code it shows. See,
  remove or block devices in **Settings › Devices**.
- **Blocked means gone.** A blocked device can't connect and doesn't even see your Mac.
- **Control is opt‑in.** A display can't touch your Mac unless you allow it, and you can take back the
  mouse at any time.

## Requirements

| | |
|---|---|
| **Mac** | macOS 14 Sonoma or later, Apple silicon |
| **Android** | Android 8.0 or later. USB needs *USB debugging*; Wi‑Fi needs the same network as the Mac |
| **Mac as a display** | Universal Display on both Macs |

## Updates

- **Mac:** automatic — it checks every hour and never interrupts a session. Or use **Updates** in the
  menu.
- **Android:** the Mac updates the tablet app over USB. For Wi‑Fi only, add this repository to
  [Obtainium](https://github.com/ImranR98/Obtainium).

## FAQ

<details>
<summary><b>How is this different from Sidecar?</b></summary>

Sidecar is Apple's own and only works with an iPad. Universal Display adds what Sidecar can't do:
Android tablets as displays, a Mac as another Mac's display, and remote desktop from Android phones and
tablets. For an iPad, Sidecar is a great choice.
</details>

<details>
<summary><b>Does the tablet need to be on the same Wi‑Fi?</b></summary>

As a display, yes — or plug it in over USB. Remote desktop also works away from home over Tailscale.
</details>

<details>
<summary><b>Can several Macs use the same tablet?</b></summary>

Yes, one at a time. A Mac connecting by itself never kicks out the one already showing; clicking
**Connect** or plugging in over USB takes over.
</details>

<details>
<summary><b>Will my Mac sleep while a tablet is connected?</b></summary>

Not while it's showing a picture. Turn on **Keep awake** in **Settings › General** to keep it
reachable for remote desktop too.
</details>

<details>
<summary><b>How do I uninstall it?</b></summary>

Quit it from the menu and move **Universal Display** from Applications to the Trash. On Android,
uninstall the app as usual.
</details>

<details>
<summary><b>Where is the source code?</b></summary>

The source is private for now. This repository builds it and publishes the releases.
</details>

---

<p align="center"><sub>Made by <a href="https://github.com/hertlyhq">Hertly</a>. Not affiliated with Apple or Google.</sub></p>
