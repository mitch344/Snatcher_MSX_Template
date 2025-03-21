# Snatcher English Translation Setup (MSX via OpenMSX on Windows x64)

This template provides a structured setup for installing the English translation of *Snatcher* on MSX using OpenMSX on Windows x64.

## Important Notes
- **No binaries, ROMs, or disk images are included**—only placeholders are provided.
- SCC+ sound cartridge is enabled for optimal audio, including *Jingle Bells*.
- A pre-configured save disk (`Snatcher_Saves.dsk`) and `SunriseIDE_Nextor.xml` configuration file are included.

## Setup Instructions

### 1. Install OpenMSX
1. Download OpenMSX from [https://openmsx.org/](https://openmsx.org/).
2. Extract `openmsx-XX.X-windows-vc-x64-bin.zip` to a location of your choice.
3. Run `openmsx.exe` once, then close it—this generates the `openMSX` folder in your Documents directory.

### 2. Replace Required Files
1. Locate the `openmsx-XX.X-windows-vc-x64-bin` folder inside the template.
2. Replace the following placeholder files with actual versions (placeholders are provided in the template):
   - `Nextor-2.1.1.SunriseIDE.ROM`
   - `fs-a1gt_firmware.rom`
   - `fs-a1gt_kanjifont.rom`
   - `FS-A1GT_U20.bin`
   
   *(These files must be dumped or obtained separately.)*

3. Navigate to the `Documents` folder in the template and replace `SnatcherHDD.dsk` with the actual disk image (a placeholder is provided).
   - Check the `README` inside for additional details.

### 3. Copy & Replace Files from Template to OpenMSX
1. Copy the `Documents/openMSX` folder from the template into your existing `Documents/openMSX` folder (overwrite if necessary).
2. Copy the contents of `openmsx-XX.X-windows-vc-x64-bin` from the template into the extracted `openmsx-XX.X-windows-vc-x64-bin` folder wherevere you unzipped earlier.

### 4. Launch the Game
- `openmsx.exe -machine Panasonic_FS-A1GT -ext SunriseIDE_Nextor -ext scc+ -diska Snatcher_Saves.dsk -command "set fullscreen on"`

### 5. Enjoy!
Once everything is in place, launch OpenMSX and enjoy playing *Snatcher*!

---

**Disclaimer:** This guide does not provide copyrighted files. Ensure you obtain them legally.
