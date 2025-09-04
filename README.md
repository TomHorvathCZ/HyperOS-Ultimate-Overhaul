# HyperOS Ultimate Overhaul – Redmi Tab Pro

**Author:** Tom Horvath @Heyxtomas aka TomHorvathCZ 
**Date:** 2025-08-31  
**Device:** Redmi Tab Pro (HyperOS, A15)  
**Purpose:** Full HyperOS overhaul – speed, multitasking, snappy internet, clean system without bloatware.

**Works on:** Linux via .sh, Windows via .bat

---

## Overview

This repository contains **two shell scripts** designed specifically for the **Redmi Tab Pro** running HyperOS.  
The scripts **do not require root** and are meant to maximize performance, multitasking, and internet responsiveness while keeping full HyperOS gestures intact.

- **OverhaulBoost.sh** – applies the ultimate performance, workspace, and network optimizations.  
- **OverhaulReset.sh** – restores all changes to the original HyperOS defaults.

> ⚠️ **Important:** These scripts are **exclusively for the Redmi Tab Pro**. Using them on other devices may cause instability or unpredictable behavior.

---

## Features

### OverhaulBoost.sh

- **Super-fast UI:** instant animations, responsive interface  
- **Maximum multitasking:** aggressive RAM cache, more apps running simultaneously  
- **Multi-window / freeform + PiP:** desktop-like experience directly on the tablet  
- **Force GPU & 4x MSAA:** smooth graphics and UI rendering  
- **Workspace enlargement:** optimized DPI and icon layout  
- **Snappy & secure internet:** AdGuard DNS, Wi-Fi tweaks, TCP/IP optimization  
- **Clean system:** no bloatware, disabled unnecessary system processes

### OverhaulReset.sh

- Restores all settings modified by OverhaulBoost.sh:  
  - Animations  
  - Multitasking limits  
  - Force GPU / 4x MSAA  
  - Multi-window / PiP  
  - DPI and workspace layout

---

## Usage Instructions Linux

1. Connect your **Redmi Tab Pro via USB** and enable **ADB debugging**.  
2. Run the scripts as needed:  
   - `OverhaulBoost.sh` → apply full overhaul  
   - `OverhaulReset.sh` → reset to HyperOS default  
3. Restart the tablet (optional but recommended) for full effect.
---

## Usage Instructions Windows

1. Connect your **Redmi Tab Pro via USB** and enable **ADB debugging**.
(Install ADB on computer)  
2. Run the scripts as needed:  
   - `OverhaulBoost.bat` → apply full overhaul  
   - `OverhaulReset.bat` → reset to HyperOS default  
3. Restart the tablet (optional but recommended) for full effect.

---

## Notes & Limitations

- **Exclusively for Redmi Tab Pro**  
- Does **not enable Workstation Mode** or USB-C/HDMI output  
- Fully compatible with HyperOS gestures  
- No root require
