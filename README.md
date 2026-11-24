# ROBO Recovery

**Free PC & Android Data Recovery Utility for Windows (64-bit)**

ROBO Recovery helps you recover deleted files from PC drives, USB sticks, SD cards, disk images (`.img`), and non-rooted Android phones over USB or Wi-Fi ADB — with built-in previews, duplicate removal, and multi-method file repair.

*(Note: This repository hosts official binary releases and documentation. Source code is not included.)*

---

## Features

- **PC Quick & Deep Recovery:**
  - **Quick Scan:** Reads NTFS (`$MFT`), FAT32, exFAT, and `$Recycle.Bin` to restore original file names, folders, and dates.
  - **Deep Scan:** Sector-by-sector file carving across **Photos, Camera RAW (CR2/CR3/NEF/ARW/DNG), Design (PSD/SVG), Videos, Audio, Documents (PDF/DOCX/XLSX/PPTX/RTF/EPUB), Email (PST), Archives (ZIP/RAR/7z/ISO), 3D Models (GLB/FBX/BLEND), Fonts, Programs (EXE/DLL), and Databases**.
  - **RAW / Lost Partition Scan & Disk Imaging:** Scan unmounted physical drives or clone failing drives to `.img` with bad-sector skipping.
  - **Save & Resume Sessions (`.rpro`).**
- **Android Recovery (No Root Needed):**
  - Connects via USB Debugging or Wi-Fi ADB (includes 1-click download for Google's official `adb` platform-tools).
  - Finds deleted items in `.trashed-*`, gallery recycle bins, `.thumbnails`, WhatsApp / WhatsApp Business media & voice notes (`.opus`), Telegram media, and `.vcf` contact backups.
- **Preview, Filter, Deduplicate & Multi-Method Repair:**
  - Live search, Category / Date / Recovery-Chance / Repair-State filters, and Photo Gallery Grid view.
  - Auto-detects **Repairable vs Not Repairable** files and supports chained repair for JPEGs, PNGs, MP4/MOVs (including reference-video `moov` rebuild), MP3s, PDFs, and ZIP/Office files.
  - 5 built-in themes and 11 languages.

---

## System Requirements

- **OS:** Windows 10 or Windows 11 (64-bit / `win-x64`)
- **Runtime:** **None required** — `ROBO Recovery.exe` is self-contained.
- **Privileges:** Administrator rights are requested on launch to read raw PC drives/partitions.
- **Android (optional):** USB Debugging enabled on the phone (guided instructions included in-app).

---

## Download & Installation

1. Go to the **[Releases](../../releases)** page.
2. Download **`ROBO-Recovery-Portable.zip`** (56.35 MB) or **`ROBO Recovery.exe`** (133.74 MB).
3. Extract (if ZIP) and double-click **`ROBO Recovery.exe`**.

### SHA-256 Checksums (`v1.0.0`)

```text
DCF426BB843EECB430558605D0122772D035847A4CF59B6E1CA0A2D34F809210  ROBO Recovery.exe
1F6DFA2AF2FD26B5DC194C4A5D2DB4E6D5200ACFC44AB367041213FAC40B5757  ROBO-Recovery-Portable.zip
```

---

## Troubleshooting

- **Windows SmartScreen:** Because this free release is not yet signed with a paid EV/Authenticode certificate, Windows SmartScreen may warn on first run.
- **Deleted files on SSDs:** Modern SSDs use TRIM, which often erases deleted data blocks immediately.
- **Android internal storage (no root):** Without root, Android blocks raw sector access to internal storage; ROBO Recovery scans all accessible trash, thumbnail caches, WhatsApp/Telegram media, and backups. For an SD card, use a PC card reader for a full deep scan.

---

## Feedback & Support

- **Discord:** https://discord.com/channels/1165514636033007646/1571527120046391306
- **Email:** robotninjaofficial@gmail.com
- **GitHub:** https://github.com/Robo-YT
- **Donate:** [Buy Me a Coffee](https://buymeacoffee.com/robotninja) • [PayPal](https://paypal.me/INDRobo99)
