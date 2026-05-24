[![Metrics](/github-metrics.svg)](/KonTy/KonTy/blob/main/github-metrics.svg)

---

<a href="https://github.com/KonTy">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=180&section=header&text=KonTy&fontSize=70&fontColor=ffffff&fontAlignY=40&desc=Creator%20of%20smplOS%20%E2%80%A2%20Systems%20%26%20App%20Developer&descAlignY=60&descSize=18&animation=fadeIn" />
</a>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3000&pause=1000&color=A78BFA&center=true&vCenter=true&multiline=false&repeat=true&width=620&height=45&lines=Building+the+OS+that+just+works+%E2%9A%A1;Rust+%7C+C%2B%2B+%7C+Dart+%7C+Kotlin+%7C+C;Knowledge+bases.+Smartwatches.+XR.+OS.)](https://github.com/KonTy)

</div>

---

## 👾 About Me

> I build operating systems, apps, and tools — then ship them.

Creator of **smplOS**, a minimal Arch Linux distro under 800 MB RAM on cold boot. I write the full stack: kernel-level C, Rust GUI suites, Flutter/Dart mobile apps, Android Kotlin, C++ XR, and smartwatch OS layers. When upstream won't merge my features, I fork and ship anyway.

---

## 🚀 Projects

### 🖥️ OS & Desktop

<table>
<tr>
<td width="50%" valign="top">

#### [smplOS](https://github.com/smpl-os/smplos)
> *Minimal Arch Linux distro that just works*

- ⚡ **< 800 MB RAM** on a cold boot with full desktop
- 📦 **Fully offline install** in under 2 minutes
- 🎨 **14 built-in themes** — one command recolors everything
- 🔀 **Cross-compositor** — Hyprland + DWM, shared configs
- 🦀 Entire desktop shell in **Rust**

![Arch](https://img.shields.io/badge/Arch_Linux-1793D1?style=flat-square&logo=arch-linux&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-CE422B?style=flat-square&logo=rust&logoColor=white)
![Wayland](https://img.shields.io/badge/Wayland-FFB100?style=flat-square&logo=wayland&logoColor=black)

</td>
<td width="50%" valign="top">

#### [smpl-apps](https://github.com/smpl-os/smpl-apps)
> *The Rust GUI suite that replaces the desktop shell*

Six native apps — Slint UI, software-rendered, Wayland-native. No Electron. No Python. Pure Rust.

| App | Role |
|-----|------|
| 🔍 `start-menu` | App launcher |
| 🔔 `notif-center` | Notification center |
| ⚙️ `settings` | Settings panel |
| 📦 `app-center` | Package manager UI |
| 🌐 `webapp-center` | Web app manager |
| 🔄 `sync-center` | File sync & backup |

![Rust](https://img.shields.io/badge/Rust-CE422B?style=flat-square&logo=rust&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [st-smpl](https://github.com/smpl-os/st-smpl)
> *Patched suckless terminal — Wayland native*

Inline images like Kitty. **1/14th the RAM.**

- 🖼️ SIXEL images — Kitty ~350 MB vs st-smpl ~25 MB
- ⚡ Millisecond startup, alpha transparency
- 🔧 Upstream suckless bugs fixed in `config.def.h`

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Wayland](https://img.shields.io/badge/Wayland-FFB100?style=flat-square&logo=wayland&logoColor=black)

</td>
<td width="50%" valign="top">

#### [nemo-smpl](https://github.com/KonTy/nemo)
> *Nemo file manager — supercharged*

Features upstream refuses to accept:

- 🎬 F3 Quick Preview (text/image/video/hex/dir)
- 📷 Camera RAW preview (DNG, ARW, CR2, NEF…)
- 🗺️ Preview pane with GPS map
- ✅ Verify after copy (SHA-256)
- 📊 Disk usage Pareto charts
- 🗜️ Browse ZIP/7z/TAR as folders
- 🎨 smplOS live theming

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)

</td>
</tr>
</table>

---

### 🧠 Apps — Last 4 Months

<table>
<tr>
<td width="50%" valign="top">

#### [Grafium](https://github.com/KonTy/grafium)
> *Local-first personal knowledge base*

A fast, privacy-first knowledge base built on **Rust + SQLite**. Your notes stay as plain Markdown on disk — no lock-in, no cloud.

- 🧩 **Block-based outliner** with `[[bidirectional links]]`, `#tags`, `((block refs))`
- 📓 **Daily journal** — auto-created, infinite scroll
- 🔍 **Full-text search** (SQLite FTS5 + Porter stemming)
- 📊 **Embedded live SQL queries** — build dashboards inside your notes
- ✅ Tasks with `TODO/DOING/DONE`, scheduled & deadline dates
- 🃏 **Spaced repetition flashcards** (SM-2)
- 🖊️ **Ink / stylus support** — handwriting on tablet
- 🎙️ Audio notes with transcript storage
- 👁️ Live file watcher — edit externally, auto-reindex
- 🖥️ **Cross-platform**

![Rust](https://img.shields.io/badge/Rust-CE422B?style=flat-square&logo=rust&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

</td>
<td width="50%" valign="top">

#### [microcore](https://github.com/microcore-app/microcore)
> *Your entire health stack in one app*

A cross-platform **Flutter** health companion that tracks everything — no subscriptions, no data selling.

- 💪 **Gym & strength training** — sets, reps, PRs, progressive overload
- 🥗 **Diet & nutrition** — meals, macros, calories, custom foods
- ⏱️ **Intermittent fasting** — timers, 16:8, OMAD and more
- ⚖️ **Weight & body metrics** — trends, charts, streaks
- 😴 **Sleep tracking**
- 🧘 **Habits & daily check-ins**
- 📈 Beautiful charts for all your data
- 🔒 100% offline — your body data stays on your device

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [SilentPulse](https://github.com/KonTy/SilentPulse)
> *Privacy-first SMS + offline voice assistant*

Drop-in Android SMS replacement with a fully **offline, always-on voice assistant** for hands-free drive mode. Google is never contacted.

- 🎙️ Wake word **"Computer"** — Vosk on-device keyword spotter
- 🗺️ Navigation, weather (open-meteo), drive ETAs (OSRM)
- 📬 Reads & replies to notifications by voice
- 🎵 Music, audiobooks, stock prices — all offline
- 🔗 Cross-app: *"Computer, Microcore, log weight 220lbs"*
- 🔒 No cloud TTS, no Google Speech

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)

</td>
<td width="50%" valign="top">

#### [xr-workspace](https://github.com/KonTy/xr-workspace)
> *Virtual XR monitors on Hyprland/Wayland*

SpaceWalker for Linux. Head-tracked virtual monitors via **VITURE Pro glasses** + wlr-layer-shell.

- 🥽 Head tracking → virtual monitor positioning in 3D
- 🖥️ Renders real Wayland surfaces as XR overlays
- ⚡ EGL/GLES2 GPU-accelerated, minimal latency

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Wayland](https://img.shields.io/badge/Wayland-FFB100?style=flat-square&logo=wayland&logoColor=black)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [CodeFoundry](https://github.com/KonTy/codefoundry)
> *Local-first AI engineering platform*

FastAPI + Go CLI for running LLMs locally. Profile-driven from dev laptop to NVIDIA DGX Spark — no code changes.

- 🤖 Local LLM orchestration
- ⚙️ Auto hardware detection (RTX 4060Ti → DGX Spark)
- 🐍 FastAPI server + Go CLI client

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)

</td>
<td width="50%" valign="top">

#### [BolideOS](https://github.com/BolideOS)
> *Smartwatch OS built on AsteroidOS*

A Yocto/OE-based smartwatch OS with a unified QML shell — compositor, launcher, and settings in one.

- ⌚ Runs on AsteroidOS-compatible watches
- 🎨 Custom QML shell (compositor + launcher + settings)
- 🔧 Full meta-layer for Yocto/OE builds

![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![QML](https://img.shields.io/badge/QML-41CD52?style=flat-square&logo=qt&logoColor=white)

</td>
</tr>
</table>

---

## 🛠️ Stack

<div align="center">

![Rust](https://img.shields.io/badge/Rust-CE422B?style=for-the-badge&logo=rust&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Arch Linux](https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white)
![Wayland](https://img.shields.io/badge/Wayland-FFB100?style=for-the-badge&logo=wayland&logoColor=black)

</div>

---

<div align="center">

*"If you don't need it, it doesn't exist."*

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=100&section=footer" />

</div>
