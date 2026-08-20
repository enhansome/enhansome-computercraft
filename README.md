<!--lint disable double-link-->

<!--
SPDX-FileCopyrightText: 2024 awesome-computercraft contributors

SPDX-License-Identifier: CC-BY-SA-4.0
-->

<!--lint ignore-->

# Awesome ComputerCraft with stars

[<img src="assets/cc-tweaked-logo.png" align="right" width="100">](https://computercraft.cc)

> Useful programs, libraries, literature, and mods for [ComputerCraft](https://computercraft.info) and [its forks](https://computercraft.cc).

**ComputerCraft** is a mod for Minecraft which adds computers which are programmable with the Lua programming language. **ComputerCraft: Tweaked** is a fork of the mod for newer Minecraft versions.

This project lives [on GitHub](https://github.com/tomodachi94/awesome-computercraft) ⭐ 318 | 🐛 4 | 🌐 Just | 📅 2026-08-02 and might not render correctly on third-party websites.

If you think something should be added to the list, please [reach out](https://github.com/tomodachi94/awesome-computercraft/issues/new/choose) ⭐ 318 | 🐛 4 | 🌐 Just | 📅 2026-08-02.

If you want to contribute, see [CONTRIBUTING.md](./CONTRIBUTING.md).
If you have other questions, see the [FAQ](./FAQ.md).

A note on abbreviations: `CC` is ComputerCraft, `CC:T` is ComputerCraft: Tweaked, and `CC:R` is ComputerCraft: Restitched.

## Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->

<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

* [Mods](#mods)
  * [ComputerCraft mods](#computercraft-mods)
  * [Add-on mods](#add-on-mods)
  * [Resource packs](#resource-packs)
* [Lua programs](#lua-programs)
  * [Utility](#utility)
  * [Library](#library)
  * [Fun](#fun)
  * [Operating systems](#operating-systems)
  * [Economy](#economy)
  * [Mod-specific programs](#mod-specific-programs)
* [Non-Lua programs](#non-lua-programs)
  * [Bridging](#bridging)
  * [Emulators](#emulators)
  * [Plugins](#plugins)
  * [Tools](#tools)
* [Literature](#literature)
  * [Essays](#essays)
  * [Tutorials](#tutorials)
  * [Charts, tables, and calculators](#charts-tables-and-calculators)
  * [Other lists](#other-lists)
* [Resources](#resources)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Mods

### ComputerCraft mods

<!--lint disable double-link-->

* [ComputerCraft: Tweaked](https://computercraft.cc) -  A fork of the original ComputerCraft for modern versions of Minecraft.
* [ComputerCraft: Restitched](https://www.curseforge.com/minecraft/mc-mods/cc-restitched) -  A set of patches for CC:T that allow running it on Fabric.
* [ComputerCraft](https://computercraft.info) -  A mod which adds computers to allow execution of Lua programs.

### Add-on mods

* [sc-peripherals](https://github.com/SwitchCraftCC/sc-peripherals) ⚠️ Archived - A mod that adds 3D printers which allow creating custom blocks and posters.
* [Roadworks](https://github.com/znepb/Roadworks) ⭐ 9 | 🐛 0 | 🌐 Kotlin | 📅 2025-02-21 - A mod that adds traffic lights controllable by ComputerCraft.
* [Advanced Peripherals](https://www.curseforge.com/minecraft/mc-mods/advanced-peripherals) -  A mod which adds various peripherals and APIs for interacting with other mods.
* [Classic Peripherals](https://modrinth.com/mod/classicperipherals) - A mod which adds various peripherals, including a Radio Tower (for long-range communication; Ender Modems are nerfed) and a Cryptographic Accelerator (providing methods for cryptographic operations).
* [Computronics](https://wiki.vexatos.com/wiki:computronics) -  A mod which adds various peripherals, notably for detecting events in the world and for manipulation of sound.
* [Plethora](https://plethora.madefor.cc) -  A mod which adds peripherals and allows many blocks to be accessed as such. In addition, it also allows for manipulation of the player as a peripheral.
  * [Plethora Fabric](https://github.com/SwitchCraftCC/Plethora-Fabric) ⭐ 16 | 🐛 34 | 🌐 Kotlin | 📅 2026-03-17 - A 1.19+ port of Plethora to Fabric.
* [CC:C Bridge](https://modrinth.com/mod/cccbridge) - A mod that adds compatibility between ComputerCraft and [Create](https://modrinth.com/mod/create).
* [Turtlematic](https://www.curseforge.com/minecraft/mc-mods/turtlematic) - A mod which expands the applications of turtles, making them extremely powerful.
* [UnlimitedPeripheralWorks](https://www.curseforge.com/minecraft/mc-mods/unlimitedperipheralworks) - A mod which adds various peripherals to extend CC:T capabilities. Also adds a lot of peripherals for other mods.

### Resource packs

* [ComputerCreate](https://modrinth.com/resourcepack/computercreate) -  A resource pack which adds texture packs in the style of the [Create mod](https://modrinth.com/mod/create).

## Lua programs

### Utility

* [Mildly Better Shell (MBS)](https://github.com/SquidDev-CC/mbs) ⭐ 83 | 🐛 6 | 🌐 Lua | 📅 2023-12-08 -  An improved shell that includes scrollback and improved resolution of completions.
* [Artist](https://github.com/SquidDev-CC/artist) ⭐ 64 | 🐛 8 | 🌐 Lua | 📅 2025-01-10 -  One of the first item management systems for ComputerCraft.
* [CCVim](https://github.com/Minater247/CCVim/tree/rewrite-2026) ⭐ 31 | 🐛 2 | 🌐 Lua | 📅 2026-08-17 - A faithful port of Vim for ComputerCraft.
* [MISC](https://github.com/Storehaus/CC-MISC) ⭐ 26 | 🐛 10 | 🌐 Lua | 📅 2026-02-08 -  Modular Inventory Storage and Crafting.
* [`hopper.lua`](https://github.com/umnikos/hopper.lua) ⭐ 25 | 🐛 0 | 🌐 Lua | 📅 2026-07-25 - A command-line program for moving items between containers.
* [Howl](https://github.com/SquidDev-CC/Howl) ⚠️ Archived -  A build system for CC and CC:T.
* [netshell](https://github.com/lyqyd/cc-netshell) ⭐ 12 | 🐛 1 | 📅 2015-05-30 -  Access a computer's shell from another computer.
* [OrangeBox](https://github.com/walksanatora/orangebox) ⭐ 8 | 🐛 1 | 🌐 Lua | 📅 2023-01-17 - Virtualization support for ComputerCraft computers.
* [GEMU](https://github.com/9551-Dev/GEMU) ⭐ 0 | 🐛 0 | 🌐 Lua | 📅 2022-08-24 -  CraftOS-PC graphics mode emulator based on Pixelbox.
* [ComputerCraft Advanced Shell (cash)](https://cash.madefor.cc) -  A Bourne-compatible shell for ComputerCraft.
* [Consult](https://consult.madefor.cc) -  A text editor emphasizing ease of use and compatibility with many systems.
  * [Consult: Recrafted](https://github.com/manaphoenix/CONSULT_RECRAFTED) ⭐ 1 | 🐛 0 | 🌐 Lua | 📅 2022-08-31 -  A fork of Consult for Recrafted systems.
* [`gist`](https://pastebin.com/zSLPYpqs) -  A GitHub Gist download/upload program which aims to extend the built-in `pastebin` program, but for Gists.
* [LuaIDE](https://web.archive.org/web/20230211195528/http://www.computercraft.info/forums2/index.php?/topic/12347-luaide-10-you-might-actually-like-editing-in-game/) -  A full-fledged IDE for editing Lua files in-game.
* [ModemShark](https://gist.github.com/MCJack123/56ca71555d9c0f78d4c985f1e9ad28e8) -  Modem packet sniffer with a simple UI.
* [rawshell](https://gist.github.com/MCJack123/8c8861e5e3082d2bed18d07641b5b2cc) -  A modern alternative to netshell supporting CraftOS-PC's "raw mode" format, with file transfers, encryption, passwords, WebSockets, and more.
* [ShrekPrint](https://pinestore.cc/projects/115/shrekprint) - Printing software with full color and book support.
* [ShrekWord](https://pinestore.cc/projects/114/shrekword) - Word-like document editor.
* [unicornpkg](https://unicornpkg.madefor.cc) -  Modern package management that doesn't suck.
* [FSEncrypt](https://gist.github.com/MCJack123/32c56917dc61da336ec0e8ca6aae39f8) -  Transparent filesystem encryption.

### Library

* [`Pixelbox Lite`](https://github.com/9551-Dev/pixelbox_lite) ⭐ 52 | 🐛 0 | 🌐 Lua | 📅 2025-03-15 - A very fast and flexible teletext 2D rendering library for ComputerCraft.
* [Milo](https://github.com/kepler155c/opus-apps/wiki/Milo-\(crafting---storage-system\)) ⭐ 42 | 🐛 11 | 🌐 Lua | 📅 2023-09-16 -  A crafting and inventory management system. Note that this depends on OpusOS and Plethora.
* [ecnet](https://github.com/migeyel/ecnet) ⭐ 35 | 🐛 0 | 🌐 Lua | 📅 2026-03-21 -  Secure network communications in ComputerCraft.
* [Pine3D](https://github.com/Xella37/Pine3D) ⭐ 31 | 🐛 0 | 🌐 Lua | 📅 2024-11-12 - A 3D rendering engine designed to be fast.
* [Luz](https://github.com/MCJack123/Luz) ⭐ 15 | 🐛 0 | 🌐 Lua | 📅 2025-04-01 - An extremely light compression algorithm for Lua files.
* [PngLua](https://github.com/9551-Dev/pngLua) ⭐ 15 | 🐛 0 | 🌐 Lua | 📅 2024-09-01 -  PNG parsing library designed for ComputerCraft.
* [CC-Archive](https://github.com/MCJack123/CC-Archive) ⭐ 11 | 🐛 0 | 🌐 Lua | 📅 2026-02-07 -  Various libraries for archiving and unarchiving files.
* [Tampl](https://github.com/9551-Dev/tampl) ⭐ 3 | 🐛 0 | 🌐 Lua | 📅 2024-09-03 - A Lua tokenization and parsing library designed for dynamic code generation and injecting code into existing programs.
* [IsometriH](https://github.com/9551-Dev/IsometriH) ⭐ 2 | 🐛 0 | 🌐 Lua | 📅 2023-08-29 -  An [isometric rendering](https://en.wikipedia.org/wiki/Isometric_video_game_graphics) engine.
* [Acidity](https://github.com/9551-Dev/acidity) ⭐ 0 | 🐛 0 | 🌐 Lua | 📅 2023-10-07 -  A simple procedual world generation-oriented noise generation library.
* [Tamperer](https://github.com/Fatboychummy-CC/Tamperer) ⭐ 0 | 🐛 0 | 🌐 Lua | 📅 2026-02-19 -  A library allowing easy creation of settings menus.
* [Anavrins' ChaCha20](https://web.archive.org/web/20200924232302/http://www.computercraft.info/forums2/index.php?/topic/25474-chacha20-encryption-in-computercraft/) -  Implementation of [ChaCha20](https://en.wikipedia.org/wiki/ChaCha20-Poly1305). <!-- FIXME: Broken link -->
* Anavrins' hashing libraries:
  * [MD5](https://pastebin.com/6PVSRckQ) -  Implementation of [MD5](https://en.wikipedia.org/wiki/MD5).
  * [SHA-1](https://pastebin.com/SfL7vxP3) -  Implementation of [SHA-1](https://en.wikipedia.org/wiki/SHA-1) with [HMAC](https://en.wikipedia.org/wiki/HMAC) support.
  * [SHA-256](https://web.archive.org/web/20230211193054/http://www.computercraft.info/forums2/index.php?/topic/8169-sha-256-in-pure-lua/) -  Implementation of [SHA-256](https://en.wikipedia.org/wiki/SHA-2) with support for [HMAC](https://en.wikipedia.org/wiki/HMAC) and [PBKDF2](https://en.wikipedia.org/wiki/PBKDF2).
* [AUKit](https://mcjack123.github.io/AUKit/) -  The quintessential audio processing and conversion library for ComputerCraft.
* [Basalt](https://basalt.madefor.cc/) -  A GUI library emphasizing the user experience.
* [Bigfont](https://pastebin.com/3LfWxRWh) -  A library that makes writing something in different font sizes easy.
* [C3D](https://c3d.madefor.cc/) -  An advanced 3D rendering API.
* [dbprotect](https://gist.github.com/MCJack123/4cf6fc941a2d412b4195caafb9636363) -  A protection wrapper over the `debug` API, allowing restricting access to upvalues in protected functions.
* [`ecc.lua`](https://web.archive.org/web/20190808224502/http://www.computercraft.info/forums2/index.php?/topic/29803-elliptic-curve-cryptography/) -  Implements [elliptic-curve cryptography](https://en.wikipedia.org/wiki/Elliptic-curve_cryptography). <!-- FIXME: Broken link -->
* [GuiH](https://guih.madefor.cc) -  A powerful GUI and graphics library.
* [RedRun](https://gist.github.com/MCJack123/473475f07b980d57dd2bd818026c97e8) -  A small library for running processes in the background of CraftOS after exiting the program, similar to DOS TSRs.
* [Telem](https://telem.cyberbit.dev) - A telemetry library for peripherals, facilitating in-game and cloud-based monitoring dashboards for storage, energy, and machinery.
* [VeriCode](https://gist.github.com/MCJack123/7752c85918bcf23ada028abd615e8750) -  Provides simple code signing functions for safely transferring code over modems.

### Fun

* [AUKit austream](https://github.com/MCJack123/AUKit/blob/master/austream.lua) ⭐ 43 | 🐛 2 | 🌐 Lua | 📅 2026-04-10 -  Based on AUKit, a simple audio player supporting WAV, DFPWM, AIFF, AU, and FLAC.
* [CCDoom](https://github.com/Xella37/CCDoom) ⭐ 24 | 🐛 0 | 🌐 Lua | 📅 2023-10-19 - The [*Doom* shooter](https://en.wikipedia.org/wiki/Doom_\(1993_video_game\)) ported to ComputerCraft using Pine3D.
* [lunatic86](https://github.com/MCJack123/lunatic86) ⭐ 19 | 🐛 0 | 🌐 Lua | 📅 2021-02-01 -  A port of an 8086 PC emulator for ComputerCraft.
* [Musicify](https://github.com/knijn/musicify) ⭐ 13 | 🐛 9 | 🌐 Lua | 📅 2025-07-07 -  A lightweight client for playing music on ComputerCraft: Tweaked.
  * [tracc](https://github.com/MCJack123/tracc/tree/playAudio) ⭐ 11 | 🐛 0 | 🌐 Lua | 📅 2026-08-18 -  An XM module tracker/player for ComputerCraft, supporting 8 channel polyphony in-game.
* [CC-Minecraft](https://github.com/Xella37/CC-Minecraft) ⭐ 12 | 🐛 0 | 🌐 Lua | 📅 2023-10-19 - *Minecraft* ported to ComputerCraft using Pine3D.
* [LuaGB](https://github.com/MCJack123/LuaGB) ⭐ 12 | 🐛 0 | 🌐 Lua | 📅 2025-02-02 -  A port of a Game Boy (Color) emulator for ComputerCraft. Works best in CraftOS-PC.
* [battleship](https://gist.github.com/MCJack123/7082da1d2ac725c33ff77389877ad7f4) -  An implementation of the popular two-player game *[Battleship](https://en.wikipedia.org/wiki/Battleship_\(game\))*.
* [YahtCC](https://gist.github.com/MCJack123/4f7f1635998f44630c8440e81213d32e) -  An implementation of the *[Yahtzee](https://en.wikipedia.org/wiki/Yahtzee)* dice game.
* [YouCube](https://youcube.madefor.cc) -  Access YouTube and other services in ComputerCraft.
* [YTP2CCP](https://pastebin.com/nxEMWHY3) -  Convert commented YouTube piano notes and play them in CC:T.

### Operating systems

* [Opus](https://github.com/kepler155c/opus) ⭐ 198 | 🐛 10 | 🌐 Lua | 📅 2023-12-17 -  An OS which includes a GUI, an app store, and many system-related APIs.
* [Recrafted](https://github.com/ocawesome101/recrafted) ⭐ 17 | 🐛 4 | 🌐 Lua | 📅 2026-03-20 -  A rewrite of CraftOS aiming for full feature parity while maintaining "saner API design."
* [cOS](https://github.com/knijn/cos) ⭐ 8 | 🐛 0 | 🌐 Lua | 📅 2024-04-26 - The NixOS inspired configurable ComputerCraft OS.
* [LevelOS](https://install.leveloper.cc) -  A modern GUI operating system intended to mimic Windows.
* [Phoenix](https://phoenix.madefor.cc) -  An OS which emphasizes modularity. It implements its own kernel.
  * Phoenix is currently in alpha.
* [UnBIOS](https://gist.github.com/MCJack123/42bc69d3757226c966da752df80437dc) -  A program to "undo" CraftOS, returning the system to the same state it was in before running the BIOS. Useful for OS development.

### Economy

* [Radon](https://github.com/Allymonies/Radon) ⭐ 10 | 🐛 10 | 🌐 Lua | 📅 2024-03-02 - A highly configurable Krist shop, supporting categories, nameless shops, and support for multiple currencies.
* [LP](https://github.com/migeyel/lp) ⭐ 8 | 🐛 0 | 🌐 Lua | 📅 2024-09-27 - A Krist shop which dynamically adjusts buy and sell prices based on supply and demand.
* [msks](https://github.com/ShrekshellraiserCC/msks) ⭐ 6 | 🐛 3 | 🌐 Lua | 📅 2023-01-05 -  A modern, simple shop for the Krist virtual currency.
* [`colorful.kst`](https://github.com/znepb/colorful) ⭐ 0 | 🐛 0 | 🌐 Lua | 📅 2024-09-28 - A Krist store which sells colorful blocks, coloring them on demand.
* [printshop](https://github.com/znepb/printshop) ⭐ 0 | 🐛 0 | 🌐 Lua | 📅 2024-09-28 - A Krist shop which sells 3D prints and posters, also allowing players to print their own designs.
* [Kristify](https://kristify.madefor.cc/) - Software for highly customizable Krist shops in modern versions of ComputerCraft, powered by [Basalt](https://basalt.madefor.cc).

### Mod-specific programs

> Note: This section contains programs which are exclusive to a mod and would not make sense in the Utilities section.

* [DraconicControl](https://pastebin.com/UqVHTht5) -  Allows controlling Draconic Evolution's Draconic Reactor from a computer.
* [ReactorControl and TurbineControl](https://pastebin.com/p4zeq7Ma) -  Automatic management of reactors and turbines in Big Reactors.
  * [ReactorControl patched](https://pastebin.com/2ZrbnH5w) -  The preceeding program uses the `parallel` API recursively, which could cause it to break. A patch has been developed to fix this.
* [`cc-mek-scada`](https://github.com/MikaylaFischler/cc-mek-scada) ⭐ 571 | 🐛 14 | 🌐 Lua | 📅 2026-08-16 - Configurable control system for Mekanism fission reactors.
* [`shrekflight`](https://p.sc3.io/t6ZRrJutrN) - A program which provides Creative Mode-like flight and automatic flight to specified coordinates.

## Non-Lua programs

> Note: This section is for programs that are not mods or Lua programs and **directly** relate to the subject of this list.

### Bridging

> Note: This subsection is for programs which allow ComputerCraft things to be accessed out of the game, primarily through the Internet.

<!-- vale Google.WordList = NO -->

* [Cloud Catcher](https://github.com/SquidDev-CC/cloud-catcher) ⭐ 85 | 🐛 11 | 🌐 TypeScript | 📅 2024-12-08 -  A program which enables interaction with computers outside of the game.

<!-- vale Google.WordList = YES -->

* [Krist Server](https://github.com/tmpim/Krist) ⭐ 32 | 🐛 1 | 🌐 TypeScript | 📅 2026-02-07 -  A server for the Krist virtual currency, intended for use with CC and CC:T.
  * [KristForge](https://github.com/tmpim/kristforge) ⚠️ Archived -  A miner for the Krist virtual currency.
  * [KristWeb2](https://github.com/tmpim/KristWeb2) ⭐ 12 | 🐛 10 | 🌐 TypeScript | 📅 2026-07-19 -  A web wallet for Krist, written in React.
* [Netmount](https://github.com/tmpim/netmountcc) ⭐ 13 | 🐛 0 | 🌐 TypeScript | 📅 2024-07-14 - Configurable WebSocket and WebDAV remote storage solution.
* [Turtleshell](https://turtleshell.ginger.services/) - A relay server that allows in-game computers to be accessed over [SSH](https://en.wikipedia.org/wiki/Secure_Shell).
* [Ultron Control](https://gitlab.com/Merith-TK/ultron-control) -  A program which exposes a web API for controlling turtles.

### Emulators

* [CCEmuX](https://emux.cc) -  A CC and CC:T emulator which executes the mods directly.
* [Copy Cat](https://github.com/SquidDev-CC/copy-cat) ⭐ 50 | 🐛 7 | 🌐 TypeScript | 📅 2026-06-18 -  A CC:T emulator that runs in a web browser.
* [CraftOS-PC](https://www.craftos-pc.cc) -  A CC:T emulator written in C++ with the intention of speed.

### Plugins

* [CraftOS-PC for VS Code](https://www.craftos-pc.cc/docs/extension) -  Extension for manipulating and running programs via CraftOS-PC in VSCode.
* [`craftos2-plugins`](https://github.com/MCJack123/craftos2-plugins) ⭐ 3 | 🐛 0 | 🌐 C++ | 📅 2025-12-06 -  A collection of small plugins for CraftOS-PC, maintained by the creator.
* [VSCode Extensions for ComputerCraft](https://marketplace.visualstudio.com/items?itemName=lemmmy.computercraft-extension-pack) -  Self-explanatory. Contains autocomplete for CC and CC:T functions, as well as a Lua language server.

### Tools

* [`cc-tstl-template`](https://github.com/MCJack123/cc-tstl-template) ⭐ 76 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-15 -  A template for the TypeScriptToLua compiler that allows writing ComputerCraft programs in TypeScript.
* [sanjuuni](https://github.com/MCJack123/sanjuuni) ⭐ 65 | 🐛 13 | 🌐 C++ | 📅 2026-06-04 -  A program to quickly convert image and video files into various formats for playback and streaming in ComputerCraft.
* [BIMG-Generator](https://github.com/ShrekshellraiserCC/BIMG-Generator) ⭐ 6 | 🐛 2 | 🌐 Java | 📅 2025-02-18 - A Java program to convert images to the BIMG format.
* [ComputerCraft Music Converter](https://music.madefor.cc) - A web app to convert various sound formats to DFPWM (ComputerCraft's sound format).
* [Quartz Encoder](https://cc.alexdevs.me/index.html) - An API to convert links to audio files into DFPWM and MDFPWM.

## Literature

### Essays

* [JackMacWindows's essay on ComputerCraft OSes](https://gist.github.com/MCJack123/4b2bca21bdc0cf5c67ce7177326c2154) -  Contains suggestions, discouragement, and encouragement for building a proper operating system.
* [JackMacWindows's essay on sane APIs](https://gist.github.com/MCJack123/39ac0847579b3676cc098aca5860c758) -  Has suggestions for making your APIs easy to use.

### Tutorials

#### Basics

* [Direwolf20's tutorials](https://www.youtube.com/watch?v=wrUHUhfCY5A) -  A series of videos explaining the basics of ComputerCraft programming.
* [Sethbling's tutorials](https://www.youtube.com/watch?v=DSsx4VSe-Uk) -  Another series of videos explaining ComputerCraft programming.
* Lyqyd's *Computer Basics* series ([1](https://web.archive.org/web/20170617144334/http://www.computercraft.info/forums2/index.php?/topic/15033-computer-basics-i/), [2](https://web.archive.org/web/20230719181359/https://www.computercraft.info/forums2/index.php?/topic/15041-computer-basics-ii/), [3](https://web.archive.org/web/20230719181437/https://www.computercraft.info/forums2/index.php?/topic/20905-computer-basics-iii/)) -  Though a bit dated, they are excellent for the beginnings of your journey.
* [The FTB Wiki's Getting Started guide for ComputerCraft](https://ftb.fandom.com/wiki/Getting_Started_\(ComputerCraft\)) -  A useful all-around resource for getting started.

#### Moderate or advanced

* [Bomb Bloke's *Guide to Coroutines*](https://web.archive.org/web/20230210142049/https://www.computercraft.info/forums2/index.php?/topic/25670-bbs-guide-to-coroutines/) -  Explains why you should not use coroutines, and includes tutorials on using them.

### Charts, tables, and calculators

* [JackMacWindows's coroutine flow chart](https://web.archive.org/web/20231212184953/https://cdn.discordapp.com/attachments/477911902152949771/959769473437560862/Blank_Diagram_1_Page_1.png) -  Demonstrates how coroutines work. Each column represents one coroutine's code flow.
* [KingOfGamesYami's event flow chart](https://forums.computercraft.cc/index.php?topic=26.0) -  Demonstrates the flow of events when a program runs.

<!--lint ignore-->

* [Wojbie's decimal font chart](https://web.archive.org/web/20231212200503/https://cdn.discordapp.com/attachments/477911902152949771/933498000385400862/1642633650325141456271.png) and [Cake's hex font chart](https://web.archive.org/web/20231118175928/https://thox.madefor.cc/_images/encodings-cc-chars.png) -  Contains decimal and hex mappings to ComputerCraft font characters.
* [Emma's ComputerCraft compatibility chart](https://docs.google.com/spreadsheets/d/1s4d21cL3QrUyegEzYaVXvqDr1zNorgyZ-fDWeopIC1k/edit?usp=sharing) -  Shows compatibility across emulators and in-game mods.
* [MasonGulu's monitor size calculator](https://monitorsize.madefor.cc/) - An online gadget which calculates how many characters and pixels will fit onto a monitor.

### Other lists

* [Awesome Lua](https://github.com/LewisJEllis/awesome-lua) ⭐ 4,555 | 🐛 47 | 📅 2024-08-11 - An Awesome list specific to the Lua programming language.
* [Hengestone's list of languages which compile to Lua](https://github.com/hengestone/lua-languages/blob/master/README.md) ⭐ 690 | 🐛 0 | 📅 2025-12-11 -  A list of languages which compile to Lua.
* [Awesome CC: Tweaked](https://github.com/Shlomo1412/awesome-cctweaked) ⭐ 29 | 🐛 0 | 📅 2026-08-19 - An Awesome list which only lists things relevant to CC: Tweaked.
* [Awesome SwitchCraft](https://github.com/aspen-reeves/awesome-switchcraft) ⚠️ Archived - An Awesome list specific to the SwitchCraft server.

## Resources

* [`tweaked.cc` documentation](https://tweaked.cc) -  Contains documentation for most methods in CC and CC:T.
* [CC's forums](https://computercraft.info/forums2) -  An extremely valuable resource, filled with tutorials and programs. <!-- FIXME: Broken link -->
* [CC:T's forums](https://forums.computercraft.cc) -  Also extremely valuable, but is newer.
* [Minecraft Computer Mods Discord](https://discord.gg/H2UyJXe) -  A Discord server for getting help with programming in CC and CC:T.
* [ComputerCraft's subreddit](https://reddit.com/r/computercraft) - A subreddit for showing off your ComputerCraft creations, as well as getting help.

<!-- vale Vale.Terms = NO -->

* [Lua's manual](https://www.lua.org/manual/) -  Contains documentation on methods not covered in `Tweaked.cc`. Sections 5 (Auxillary Library) and 6 (Standard Library) are of particular interest.

<!-- vale Vale.Terms = YES -->

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-20._
