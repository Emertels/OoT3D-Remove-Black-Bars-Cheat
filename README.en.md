<div align="center">

[![Português (Brasil)](https://img.shields.io/badge/Portugu%C3%AAs%20(Brasil)-PT--BR-009739?style=for-the-badge)](README.md)
[![English](https://img.shields.io/badge/English-EN-1F4E79?style=for-the-badge)](README.en.md)

# Ocarina of Time 3D — Remove Black Bars

**A cheat that removes the black bars while aiming and using items.**

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

## About Emerson Teles

Developer focused on intelligent automation, reverse engineering, technical translation, and Brazilian Portuguese localization. A fan of retro and modern gaming, Emerson creates tools, automation, and localization projects to solve practical problems and support user communities.

### Other projects

| Project | Description | Repository |
| :--- | :--- | :---: |
| **Silent Hill: Homecoming PT-BR** | Brazilian Portuguese translation and proofreading. | [Visit](https://github.com/Emertels/Silent-Hill-Homecoming-Traducao-PTBR) |
| **PSBBN Translator** | Automated translation and localization for the PSBBN Definitive Project. | [Visit](https://github.com/Emertels/PSBBN-Translator) |
| **Emulator Suite** | PowerShell tools for emulators and frontends. | [Visit](https://github.com/Emertels/Suite-Emuladores) |
| **AI-Chat-Vault** | Backup and recovery of local conversations from AI tools. | [Visit](https://github.com/Emertels/AI-Chat-Vault) |
| **Microsoft Photos Fix** | Fixes for Quick Launch and wallpapers in the Photos app. | [Visit](https://github.com/Emertels/Microsoft-Photos-Fix) |
| **Roccat Syn Pro Air Fix** | Audio and stability tools for the headset. | [Visit](https://github.com/Emertels/Roccat-Syn-Pro-Air-Fix) |
| **Cursor PT-BR Translation** | Cursor AI localization into Brazilian Portuguese. | [Visit](https://github.com/Emertels/Cursor-Traducao-PTBR) |
| **Google Antigravity PT-BR Translation** | Google Antigravity Desktop localization. | [Visit](https://github.com/Emertels/Antigravity-Traducao-PTBR) |
| **ZCode PT-BR Translation** | ZCode Desktop localization. | [Visit](https://github.com/Emertels/ZCode-Traducao-PTBR) |
| **Official Portal** | Portal for tools, projects, and community channels. | [Visit](https://github.com/Emertels/emertels.github.io) |

[View all Emerson Teles repositories on GitHub](https://github.com/Emertels?tab=repositories)

---

## Connect with me

[![Website](https://img.shields.io/badge/Website-emertels.github.io-0070F3?style=for-the-badge&logo=googlechrome&logoColor=white)](https://emertels.github.io)
[![Discord](https://img.shields.io/badge/Discord-Official%20Community-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://emertels.github.io/discord)
[![YouTube](https://img.shields.io/badge/YouTube-@emersonteles2379-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@emersonteles2379)
[![Telegram](https://img.shields.io/badge/Telegram-Apps%20%26%20Mods-24A1DE?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/apksmodsandroid)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-Support%20Projects-FF5E5B?style=for-the-badge&logo=kofi&logoColor=white)](https://ko-fi.com/emertels)
[![X](https://img.shields.io/badge/X-@emertels-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/emertels)
