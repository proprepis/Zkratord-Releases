# Zkratord Releases

Official public Windows binary releases of Zkratord. This repository intentionally contains no application source code or private vocabulary data.

## Download

Download [Zkratord v2.8.26](https://github.com/proprepis/Zkratord-Releases/releases/tag/v2.8.26). The release page provides one complete Windows ZIP with Launcher, Unified, Zkrat, and Database executables.

This update fixes automatic capitalization after suffix expansions and one-word sentences, including Text on Tap compatibility output. It also includes the current Shift-key overlap, chord, NumPad decimal and settings-save safeguards. Minimize the Launcher to its icon by the Windows clock; a red circled cross indicates that Unified is not armed.

Unified uses a single Start/Stop button. Prepared texts are under **List of abbreviations → Texts**; while Unified is running, press **F7** in your text editor to open the player.

On first launch, choose the interface language, built-in autocorrections, and automatic sentence capitalization. The optional English/Czech beginner guide leads to creating a first short form and can be reopened later from Files.

## Included autocorrections and empty templates

The public package contains two optional built-in autocorrection vocabularies:

- `_Zkratord/Slovníky/data_CZ.csv`
- `_Zkratord/Slovníky/data_ENG.csv`

The following editable templates intentionally remain empty:

- `_Zkratord/data.csv`
- `_Zkratord/Data_secondary.csv`
- `_Zkratord/Data/data.txt`
- `_Zkratord/Data/koncovky.txt`

Add your own abbreviations and chord data through Launcher, or select your existing libraries through Files > Libraries. Keep the extracted folder writable.

## Package contents

The complete ZIP includes `Zkratord Launcher.exe` at the top level. Unified, Zkrat, Database, portable configuration, both built-in autocorrection vocabularies, empty editable templates, an empty `Scripts` folder, manuals, and SHA-256 checksums are kept in `_Zkratord`.

## Integrity

Compare the executables with SHA256SUMS.txt. The release notes also publish the SHA-256 digest of the complete ZIP archive.
