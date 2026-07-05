<div align="center">

<img src="https://raw.githubusercontent.com/stephencreate/BatchPress/main/icon.png" width="128" alt="BatchPress Icon"/>

# BatchPress

**Batch export Adobe InDesign and Photoshop files — fast, headless, and without the clicks.**

[![Version](https://img.shields.io/badge/version-5.2-orange)](#)
[![Platform](https://img.shields.io/badge/platform-macOS%2013%2B-lightgrey)](#)
[![License](https://img.shields.io/badge/licence-Commercial-orange)](#)

[Download](#download) · [Features](#features) · [How It Works](#how-it-works) · [Buy a Licence](https://stephencreate.gumroad.com/l/BatchPress) · [Website](https://batchpress.carrd.co)

---

</div>

## What is BatchPress?

BatchPress is a native macOS utility built for designers and studios who need to export large numbers of Adobe InDesign (`.indd`) and Photoshop (`.psd`) files without babysitting the process. Drop your files in, set your export settings once, and let BatchPress do the rest — running entirely headless through InDesign and Photoshop in the background.

Built specifically for print and production workflows where exporting dozens or hundreds of files manually is simply not an option.

---

## Features

- **Batch export InDesign files** to PDF (using your own saved PDF presets), JPEG, or PNG
- **Batch export Photoshop files** to JPEG, PNG, TIFF, or PDF
- **Headless operation** — launches Adobe apps automatically if not already running, runs scripts silently, and returns BatchPress to the front when done
- **Drag and drop** file loading with individual file cards, folder collation support
- **Per-format settings** — quality, DPI, colour mode (RGB/CMYK/Greyscale), resampling, metadata, smart sharpen, resize to longest edge, update links, spreads
- **Preview mode** — export just the first file to check settings before committing the full batch
- **Progress tracking** with elapsed time display
- **Open Output Folder** shortcut to jump straight to exported files in Finder
- **7-day free trial** — no account required, no sign-up
- **Licence key activation** — single purchase, permanent, stored locally
- **Automatic update checking** via GitHub Releases

---

## Screenshots

<img width="784" height="739" alt="Screenshot" src="https://github.com/user-attachments/assets/1f3566e1-ba85-4acf-ad32-6061febaddd7" />

---

## Download

Grab the latest release directly from the [Releases](../../releases) page.

**System requirements:**
- macOS 13 (Ventura) or later
- Apple Silicon or Intel Mac
- Adobe InDesign and/or Adobe Photoshop (2021 or later recommended)

---

## How It Works

BatchPress injects export settings and file paths as JavaScript variables into Adobe's own JSX scripting engine, then triggers the script via AppleScript. This means it uses InDesign and Photoshop's native export pipeline — the same quality as exporting manually, just without any of the clicks.

```
Your files → BatchPress → JSX script → InDesign / Photoshop → Output files
```

No plugins. No extensions. No cloud. Everything runs locally on your Mac.

---

## Supported Export Formats

| Input | Output Formats |
|-------|---------------|
| `.indd` (InDesign) | PDF, JPEG, PNG |
| `.psd` / `.psb` (Photoshop) | JPEG, PNG, TIFF, PDF |

---

## Licence

BatchPress is commercial software with a **7-day free trial**.

After the trial period, a licence key is required to continue using the app. Licence keys are available at:

**[stephencreate.gumroad.com/l/BatchPress](https://stephencreate.gumroad.com/l/BatchPress)**

Licence keys are:
- Tied to a single purchase
- Stored locally on your Mac (no account needed)
- Valid permanently — no subscription

---

## Updates

BatchPress checks for updates automatically on launch. You can also check manually via **Help → Check for Updates...** in the menu bar.

When a new version is available, BatchPress will prompt you to download it. Updates are distributed via GitHub Releases.

---

## About

Developed by **Stephen Underwood**  
[batchpress.carrd.co](https://batchpress.carrd.co)

BatchPress is an independent tool and is not affiliated with or endorsed by Adobe Inc. Adobe InDesign and Adobe Photoshop are trademarks of Adobe Inc.

---

© 2026 Stephen Underwood. All rights reserved.
