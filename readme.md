<div align="center">

# 🌫️ Murky Installer

**One tiny download. One click. A faster, quieter browser.**

[![Platform](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D4?style=for-the-badge&logo=windows&logoColor=white)](#-install)
[![Size](https://img.shields.io/badge/Installer-~100%20KB-22c55e?style=for-the-badge)](#-features)
[![Latest](https://img.shields.io/badge/Always-Latest%20Murky-8b5cf6?style=for-the-badge)](#-how-it-works)

[**Download**](https://github.com/murkybrowser/Murky-Browser/releases) · [**Website**](https://murkybrowser.xyz) · [**Browser source**](https://github.com/murkybrowser/Murky-Browser) · [**Donate**](https://murkybrowser.xyz/donate)

</div>

---

## ✨ What is this?

**`MurkySetup.exe`** is the official installer for **Murky Browser**. It is a small native app that finds the **newest Murky release**, downloads it, checks it, installs it, and hands you a **Launch** button.

No bundled old version. No stale download. You always get the latest Murky.

---

## 🚀 Features

| | Feature | What it does |
|---|---|---|
| 🪶 | **Featherweight** | The installer itself is only ~100 KB. Murky is downloaded fresh when you run it. |
| 🔄 | **Always the latest** | Reads the GitHub releases and picks the newest stable build for your OS. |
| 🔐 | **Verified downloads** | Checks the SHA-256 checksum whenever GitHub provides one, so a corrupted file never gets installed. |
| 🤫 | **Silent install** | No clicking through wizard pages. Just watch it go. |
| 🎯 | **You decide when it opens** | The Windows installer never starts Murky by itself. It launches only when you **Launch**. |

---

## 🧠 How it works

- The newest release is picked **per OS**, so a newer Windows release never hides the latest Linux one, and the other way round.
- On Windows it downloads the `Setup` `.exe`. The portable version is never used.
- Drafts and pre-releases are skipped.

---

## 📦 Install

### 🪟 Windows

1. Download **`MurkySetup.exe`** from the [Releases](https://github.com/murkybrowser/Murky-Browser/releases) page.
2. Double-click it.
3. Wait for the progress bar to finish, keep or untick **Create a Desktop Shortcut**, and press **Launch**.

> [!NOTE]
> The installer is not code-signed yet, so Windows SmartScreen may show a warning. Choose **More info → Run anyway**.

### 🐧 Linux

Download **`murky-install-linux.sh`** from the [Releases](https://github.com/murkybrowser/Murky-Browser/releases) page and run it. All it needs is `curl`.

```bash
sh murky-install-linux.sh
```

It downloads the latest `.AppImage` to `~/.local/share/murky`, makes it executable, adds **Murky** to your app menu, and starts Murky when it's done.

Prefer a window? Run the Windows installer under [Mono](https://www.mono-project.com/) instead (best effort):

```bash
mono MurkySetup.exe
```

### 🍎 macOS

Not supported yet. The installer will tell you so.

---

## ⌨️ Keyboard shortcuts

| Key | Action |
|:---:|---|
| `Enter` | Press **Launch** or **Retry** |
| `Space` | Toggle **Create a Desktop Shortcut** |
| `Esc` | Close the window (disabled while installing) |

---

## ❓ FAQ

<details>
<summary><b>Why is the installer so small?</b></summary>

It doesn't contain Murky. It only fetches the newest version from GitHub and installs it, so the file you download never goes out of date.

</details>

<details>
<summary><b>Is it safe?</b></summary>

The installer only talks to GitHub, and it verifies the SHA-256 checksum of the download whenever GitHub provides one. Only download it from the official links above.

</details>

<details>
<summary><b>It says it couldn't reach GitHub.</b></summary>

Check your internet connection and press **Retry**.

</details>

<details>
<summary><b>Does it open Murky without asking?</b></summary>

The Windows installer doesn't. Murky only starts when you press **Launch**. The Linux script has no window, so it starts Murky as soon as it finishes.

</details>

<details>
<summary><b>Windows warned me about the file.</b></summary>

That's SmartScreen. The installer isn't code-signed yet, so Windows doesn't recognise the publisher. Choose **More info → Run anyway**.

</details>

---

## ⚠️ Stay safe

The only official Murky website is **[murkybrowser.xyz](https://murkybrowser.xyz)**. Be careful with websites claiming to be Murky.

---

## 💛 Support Murky

Murky is open source and grows with your help. If you like it, [**consider donating**](https://murkybrowser.xyz/donate). Every donation is appreciated!

<div align="center">

<sub>Made with care by the Murky team</sub>

</div>
