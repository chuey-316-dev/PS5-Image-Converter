# MKPFS GUI v1.0.0

A native desktop graphical user interface (GUI) designed for the PlayStation 5 homebrew community to simplify `mkpfs` operations. This utility automates game image handling for pipelines like **ShadowMountPlus**.

* **GUI Frontend Wrapper Created by:** chuey_316
* **Original Core CLI Engine Created by:** Renan Barreto 

---

## Features
* **Visual Mode Selection**: Dynamically switch between packing files, packing folders, inspecting metadata, and unpacking images.
* **Dark Mode Stability**: Pre-configured system layout integrations preventing text visibility blocks on Linux Mint dark themes.
* **Auto-Formatting Elements**: Handles file strings containing internal spaces perfectly without character truncation errors.
* **Real-time Console Tracking**: An integrated live terminal log tracking compression progress benchmarks smoothly.

---

## Developer Command Suite Targets
Depending on the process being performed, this tool automates the following official developer syntax:

* **Convert an .exfat or .ffpkg file into a PFSC compressed image .ffpfsc**
  `mkpfs pack file --compress --verify input.exfat output.ffpfsc`
* **Convert a homebrew folder into a PFS image with compression and verification**
  `mkpfs pack folder --compress --verify input-app output.ffpfs`
* **Inspect the generated image**
  `mkpfs inspect input.ffpfs`
* **Unpack the image back into a folder**
  `mkpfs unpack input.ffpfs output-extracted/`

---

## 🚀 How to Install & Run

1. Download the `MKPFS GUI.zip` package from the **Releases** tab.
2. Extract the files to your preferred folder.
3. Open a terminal window inside that extracted folder, copy this exact command, paste it in, and press **Enter**:

gio set "MKPFS GUI.desktop" metadata::trusted true && chmod +x "MKPFS GUI.desktop"
4. Run the application by double-clicking the **MKPFS GUI** icon.

---

## Requirements & License
* Designed and optimized for Linux systems running Python 3.8+ with `python3-tk` extensions.
* Uses native file system hooks for balanced UI layouts.
* Free to use and share.
