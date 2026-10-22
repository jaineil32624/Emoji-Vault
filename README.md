<div align="center">

<img src="icons/icon-192.png" width="104" alt="Emoji Vault icon">

# 🗂️ Emoji Vault — *tap to copy*

**A playful sticker sheet of 400+ emoji.** Search by name or mood, tap to copy, build combos, save favorites, pick skin tones — and play a speedy emoji guessing game. 🎮

[![Open the app](https://img.shields.io/badge/▶_Open_the_app-jaineil32624.github.io/Emoji--Vault-FFC94A?style=for-the-badge&labelColor=1F2430)](https://jaineil32624.github.io/Emoji-Vault/)
[![Download APK](https://img.shields.io/badge/🤖_Android-Download_APK-2F9C8F?style=for-the-badge&labelColor=1F2430)](https://github.com/jaineil32624/Emoji-Vault/releases/latest/download/EmojiVault.apk)
[![All downloads](https://img.shields.io/badge/📦_Releases-All_downloads-8E8FFA?style=for-the-badge&labelColor=1F2430)](https://github.com/jaineil32624/Emoji-Vault/releases/latest)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Web Audio](https://img.shields.io/badge/Web_Audio-synth_music-FF6B5E)
![PWA](https://img.shields.io/badge/PWA-installable-5A0FC8?logo=pwa&logoColor=white)
![Capacitor](https://img.shields.io/badge/Android-Capacitor-119EFF?logo=capacitor&logoColor=white)
![Offline](https://img.shields.io/badge/works-offline-2F9C8F)
![No backend](https://img.shields.io/badge/backend-none!-FFC94A)

<img src="docs/screenshots/social.png" alt="Emoji Vault preview" width="100%">

</div>

---

## ✨ Features

| | Feature | What it does |
|---|---|---|
| 📋 | **Tap to copy** | Every sticker lands straight on your clipboard — with a little emoji burst 💥 |
| 🔍 | **Smart search** | Search by name, mood or category (`fire`, `happy dog`) — or paste an emoji to find it |
| ⭐ | **Favorites** | Right-click or long-press any sticker → ☆ Favorite. Your own tab, saved on your device |
| 🕘 | **Recent** | Everything you copied, newest first |
| 🧩 | **Combo builder** | Tap several stickers to build a string like 🔥😂💯 and copy it all at once |
| ✋🏽 | **Skin tones** | 100+ hand & people emoji with all five skin-tone options |
| 🔎 | **Details sheet** | Big preview, keyword tags, Unicode code (`U+1F602`), HTML entity, related emoji, share |
| 🎲 | **Surprise me** | Spotlights and copies a random sticker |
| 🎮 | **Emoji Guess** | 10 timed rounds — faster answers + streaks = more points. Beat your 🏆 best score |
| 🌙 | **Dark mode** | Follows your system, or toggle it yourself |
| 🔍 | **Sticker size** | Zoom slider from tiny to huge |
| ⌨️ | **Keyboard friendly** | `/` search · arrows to move · `Enter` copy · `C` combo · `R` random · `G` game · `F` favorite · `D` dark |
| 🎵 | **Synth music + sfx** | Ambient generative music and click pops, all made with the Web Audio API — no audio files |
| 🔗 | **Deep links** | `?q=heart` opens straight to a search |

## 📸 Screenshots

<table>
<tr>
<td><img src="docs/screenshots/home.png" alt="Home"><p align="center">🗂️ <b>The sticker sheet</b></p></td>
<td><img src="docs/screenshots/dark.png" alt="Dark mode"><p align="center">🌙 <b>Dark mode</b></p></td>
</tr>
<tr>
<td><img src="docs/screenshots/details.png" alt="Details"><p align="center">🔎 <b>Details</b> — codes, tags, related</p></td>
<td><img src="docs/screenshots/combo.png" alt="Combo"><p align="center">🧩 <b>Combo builder</b></p></td>
</tr>
<tr>
<td><img src="docs/screenshots/game.png" alt="Emoji Guess"><p align="center">🎮 <b>Emoji Guess</b> mini-game</p></td>
<td><img src="docs/screenshots/skin-tones.png" alt="Skin tones"><p align="center">✋🏽 <b>Skin-tone picker</b></p></td>
</tr>
</table>

<p align="center">
<img src="docs/screenshots/mobile.png" width="30%" alt="Mobile">
<img src="docs/screenshots/mobile-game.png" width="30%" alt="Mobile game">
<img src="docs/screenshots/mobile-details-dark.png" width="30%" alt="Mobile details dark">
<br><em>📱 Made for phones — long-press for details, swipe the category chips</em>
</p>

## 📥 Get Emoji Vault

| Platform | How |
|---|---|
| 🌐 **Web** | Open **[jaineil32624.github.io/Emoji-Vault](https://jaineil32624.github.io/Emoji-Vault/)** — nothing to install |
| 🤖 **Android** | Download **[EmojiVault.apk](https://github.com/jaineil32624/Emoji-Vault/releases/latest/download/EmojiVault.apk)** → open it → allow *Install unknown apps* if asked |
| 💻 **Windows / Mac / Chromebook** | Open the website in Chrome or Edge → **⬇ Get the app** → **Install** |
| 🍎 **iPhone / iPad** | Open the website in Safari → **Share** → **Add to Home Screen** |
| 📦 **Offline zip** | Grab **EmojiVault-web.zip** from [Releases](https://github.com/jaineil32624/Emoji-Vault/releases/latest), unzip, open `index.html` |

> 💡 Works **100% offline** once installed. No account, no ads, no tracking — favorites and scores stay on your device.

<p align="center"><img src="docs/screenshots/get-the-app.png" width="80%" alt="Get the app"></p>

## 🛠️ Run it locally

```bash
git clone https://github.com/jaineil32624/Emoji-Vault.git
cd Emoji-Vault
python3 -m http.server 8000      # then open http://localhost:8000
```

It's a single `index.html` — no build step, no dependencies.

## 🗂️ Project structure

```
Emoji-Vault/
├── index.html              🧱 the whole app: data, styles, logic, synth audio
├── sw.js                   📴 offline service worker
├── manifest.webmanifest    📲 installable-app manifest
├── icons/                  🖼️ app icons (SVG + PNG + maskable)
├── vendor/                 🔤 fonts bundled for offline use
├── docs/screenshots/       📸 images for this README
├── VERSION                 🏷️ bump to publish a new release
└── .github/workflows/
    ├── release.yml         🤖 builds the Android APK + publishes a Release
    └── vendor.yml          ⬇️ refreshes the offline fonts
```

## 🚀 Releasing a new version

Bump the number in `VERSION` and push — GitHub Actions builds the APK and publishes the release automatically:

```bash
echo "1.1.0" > VERSION
git commit -am "Release 1.1.0" && git push
```

## ➕ Adding emoji

Add a row to the `DATA` array in `index.html`: `["🦄","unicorn magic horse fantasy","animals"]` — emoji, search keywords, category. Skin-tone support is detected automatically.

---

<div align="center">

Made with 💛, ☕ and way too many 😂 by **[Jaineil Rana](https://github.com/jaineil32624)**

⭐ *If Emoji Vault saved you a scroll, give it a star!* ⭐

</div>
