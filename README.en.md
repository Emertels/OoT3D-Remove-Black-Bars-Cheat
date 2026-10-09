<div align="center">



# Ocarina of Time 3D — Remove Black Bars

**A cheat that removes the black bars while aiming and using items.**

[![Português (Brasil)](https://img.shields.io/badge/Portugu%C3%AAs%20(Brasil)-PT--BR-009739?style=for-the-badge)](README.md)
[![English](https://img.shields.io/badge/English-EN-1F4E79?style=for-the-badge)](README.en.md)

[![Citra](https://img.shields.io/badge/Citra-Confirmed-2EA44F?style=for-the-badge)](#author-confirmed-compatibility)
[![Azahar](https://img.shields.io/badge/Azahar-Confirmed-2EA44F?style=for-the-badge)](#author-confirmed-compatibility)
[![Release](https://img.shields.io/github/v/release/Emertels/OoT3D-Remove-Black-Bars-Cheat?style=for-the-badge)](https://github.com/Emertels/OoT3D-Remove-Black-Bars-Cheat/releases)

**An original contribution by Emerson Teles (@Emertels), with the code developed by OpenAI Codex at the author's request.**

</div>

---

## What it does

Removes the black bars shown while aiming and using items in *The Legend of Zelda: Ocarina of Time 3D*. This is a small, standalone cheat. It does not change free camera behavior, the Single Screen layout, or other parts of the game.

## A specific OoT3D contribution

This cheat was created to address this specific behavior in the 3DS version of *Ocarina of Time*. Searches conducted while preparing this project did not find another publication of the same code for this purpose with documented Citra/Azahar support. Other patches may handle black bars in OoT3D differently; this repository documents this cheat solution, how to install it, and the author's test results.

## Author-confirmed compatibility

- **Citra Canary:** working on the North America / USA, Rev. 1 game release.
- **Azahar Plus:** working on the North America / USA, Rev. 1 game release.
- **Game title ID:** `0004000000033500`.
- The author reports normal operation in both emulators.
- Other regions, revisions, and title IDs have not been tested.

## Manual installation

1. Close the emulator.
2. Find the Citra or Azahar user data folder. In a portable setup, this is the `user` folder beside the emulator executable.
3. Inside `user`, open or create the `cheats` folder.
4. Copy this repository's `0004000000033500.txt` file into `user\cheats`.
5. Open the game and open *Ocarina of Time 3D* properties.
6. Under **Cheats**, enable **Remove Black Bars - Aiming and Item Use**.
7. Start or restart the game and test while aiming and using items.

The repository also includes the ready-to-copy path `user\cheats\0004000000033500.txt`. You can download the ZIP from [Releases](https://github.com/Emertels/OoT3D-Remove-Black-Bars-Cheat/releases) and copy its `cheats` folder into the emulator's `user` folder.

## Cheat code

```text
[Remove Black Bars - Aiming and Item Use]
D3000000 00000000
00330D98 1A00000F
D2000000 00000000
```

## Credits and notes

This project is maintained and published by **Emerson Teles (@Emertels)**. The code was prepared with assistance from **OpenAI Codex**, at Emerson's request, and tested by the author in Citra Canary and Azahar Plus.

*The Legend of Zelda* is a Nintendo trademark. This is an independent project and is not affiliated with Nintendo, Citra, or Azahar. No game, ROM, or game files are distributed here.

---

## 👨‍💻 About the Author

Developed and maintained by **Emerson Teles** (known in the community as **Emertels**).

Technology, computing, gaming, and system maintenance enthusiast dedicated to software localization into Brazilian Portuguese (PT-BR). Developer focused on practical utilities, productivity tools, intelligent PowerShell automation, and complete technical localization solutions that make modern software accessible to Brazilian users.

### 🛠️ Projects & Contributions

- [AI-Chat-Vault](https://github.com/Emertels/AI-Chat-Vault) — Portable backup and recovery tool for local chat histories across 20+ AI assistants.
- [Antigravity — PT-BR Translation](https://github.com/Emertels/Antigravity-Traducao-PTBR) — Complete Brazilian Portuguese localization package for Google Antigravity Desktop.
- [Codex Router — PT-BR Translation](https://github.com/Emertels/CodexRouter-Traducao-PTBR) — Portable translation and localization package for Codex Router Control Center in PT-BR.
- [Cursor AI — PT-BR Translation](https://github.com/Emertels/Cursor-Traducao-PTBR) — Deep Brazilian Portuguese localization and update suite for Cursor AI.
- [GPU Tweak III — PT-BR Translation](https://github.com/Emertels/GPU-Tweak-III-Traducao-PTBR) — Full PT-BR translation and automated installer for ASUS GPU Tweak III.
- [Microsoft Photos Fix](https://github.com/Emertels/Microsoft-Photos-Fix) — Advanced PowerShell & C# solution fixing fast route startup and photo viewing on Windows.
- [PSBBN-Translator](https://github.com/Emertels/PSBBN-Translator) — Enterprise translation and localization suite for the PS2 PSBBN Definitive Project in 40 languages.
- [Silent Hill: Homecoming — PT-BR Translation](https://github.com/Emertels/Silent-Hill-Homecoming-Traducao-PTBR) — Complete Brazilian Portuguese translation and revision for PC.
- [Suite-Emuladores](https://github.com/Emertels/Suite-Emuladores) — Intelligent PowerShell suite for automated downloads and updates of 56 game emulators & frontends on Windows.
- [ZCode — PT-BR Translation](https://github.com/Emertels/ZCode-Traducao-PTBR) — Full Brazilian Portuguese visual translation and localization for ZCode Desktop.

### 🌐 Connect with Me & Official Communities

<div align="left">

[![GitHub](https://img.shields.io/badge/GitHub-Emertels-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/emertels)
[![Website](https://img.shields.io/badge/Website-Emerson_Teles-0070F3?style=for-the-badge&logo=googlechrome&logoColor=white)](https://emertels.github.io)
[![Discord](https://img.shields.io/badge/Discord-Emertels%20Server-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://emertels.github.io/discord)
[![X / Twitter](https://img.shields.io/badge/X_Twitter-@emertels-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/emertels)
[![YouTube](https://img.shields.io/badge/YouTube-Emerson_Teles-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@emersonteles2379)
[![Telegram](https://img.shields.io/badge/Telegram-Aplicativos%20Mods-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/apksmodsandroid)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-Support%20Project-FF5E5B?style=for-the-badge&logo=kofi&logoColor=white)](https://ko-fi.com/emertels)

</div>
