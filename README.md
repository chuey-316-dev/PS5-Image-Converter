# PS5 Image Converter

A user-friendly GUI tool for converting images for PS5, powered by a robust CLI core.

## How to Install & Run

### Linux Standalone Version (Recommended)
1. **Download** the `PS5ImageConverter` executable from the Releases page.
2. **Right-click** the file, select **Properties**, and go to the **Permissions** tab.
3. Check **"Allow executing file as program"** (or run `chmod +x PS5ImageConverter` in your terminal).
4. **Launch:** Simply double-click the file to open. No installation or dependencies required.

### Linux Script-Based Version
1. **Download and extract** the `PS5_Image_Converter.zip` package.
2. **Install system dependencies** (see *Requirements* below).
3. **Grant execution permissions** to the launcher script. Open a terminal in the folder and run:
   chmod +x "PS5 Image Converter.sh"
4. **Launch:** Double-click the `PS5 Image Converter.sh` file.

### Windows Version (Coming Soon)
1. **Download and extract** the `PS5_Image_Converter.zip` package.
2. **Launch:** Double-click the `PS5 Image Converter` executable inside the folder. (Fully portable, no command line required).

---

## 📋 Requirements

### Linux Support
* **Python 3.8+**: Ensure you have Python 3 installed.
* **Tkinter**: Required for the GUI.
    * *Debian/Ubuntu/Mint*: sudo apt install python3-tk
* **Zenity**: Required for file browser popups.
    * *Debian/Ubuntu/Mint*: sudo apt install zenity

### Windows Support
* Natively compatible with Windows 7 64-bit and all newer versions (Windows 10/11) with zero extra setup.

---

## ⚖️ Credits
* **GUI Frontend:** KyroMod
* **Core CLI Engine:** Renan Barreto
* Free to use and share.
