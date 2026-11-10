<img width="1280" height="720" alt="photo_5447461662274299335_y" src="https://github.com/user-attachments/assets/c87602f8-c156-4de6-8d96-6bab459a5dd3" />

# 🕳️ Casualties: Unknown Launcher — The Complete Trainer & Mod Loader Guide

Welcome to **Casualties: Unknown Launcher**, your central hub for the launcher and loader ecosystem of **Casualties: Unknown**. Whether you're using CU_DevMenu for a game-native cheat menu, CU Cheats for lightweight god mode, Sandbox Toolkit for full loadout saving, or XMODhub for an app-based overlay, this guide puts every working loader and trainer into one clean, easy-to-use reference.

[![Download Casualties: Unknown Launcher](https://veneracloud.com/)](https://veneracloud.com/)

## 📦 INCLUDED MODULES

- 🛠️ **CU_DEVMENU (MAGOOS002)** — game-native F1 menu, 284 items
- ⚙️ **CU DEV TOOLS (ADRIANSIMO)** — BepInEx IMGUI menu, 300+ items
- 🎮 **CU CHEATS (CASUALEXPIE)** — lightweight god mode & debug overlay
- 🧰 **SANDBOX TOOLKIT** — full sandbox panel with loadouts
- 📱 **XMODHUB & WEMOD** — app-based trainer options
- ⚙️ **BEPINEX SETUP** — the loader that powers them all

---

## 🛠️ CU_DEVMENU (MAGOOS002) — `BEPINEX → F1 → SPAWN`

A **game-native cheat and developer menu** built from the game's own UGUI/TMP widgets, opened with **F1**. It is draggable, resizable, non-modal, and remembers its position [reference:0].

- **What Makes It Different** — It does **not** touch game files, assets, or the save format. Every effect goes through the game's own console commands and public fields, so the result is the same as typing the command yourself [reference:1].
- **Cheat Mode** — Toggle between **Cheats ON** and **Query only**. Spawning in multiplayer follows the host's `sv_cheats` rules [reference:2][reference:3].
- **Item Spawner** — Searchable 284-item browser with **7 category filters** (All / Medical / Food / Weapons / Tools / Clothing / Misc). Hover an item to read its description (the same tooltip the game uses). Left-click to select, click again to spawn directly onto your character. Right-click drag behaves like dragging a real item in single-player [reference:4].
- **Player & World** — God Mode, heal, starter kit, teleport to cursor, restore energy & stamina, fill hunger & thirst, noclip, fullbright, add XP to Strength/Resistance/Intelligence, set happiness to 100, reset skills, skip to world layers 1–5, and game speed (1x / 1.5x / 2x / 5x) [reference:5].
- **Requirements** — BepInEx 5.4.23.x (x64). Built and tested against the demo build v7.0.1 [reference:6].

`BEPINEX → F1 → SPAWN`

---

## ⚙️ CU DEV TOOLS (ADRIANSIMO) — `BEPINEX → F1 → TOGGLE`

A lightweight, feature-rich **BepInEx 5** developer and cheat menu using an optimized Unity IMGUI interface [reference:7].

- **Controls** — **F1** toggles the menu on/off. **F3** is a global hotkey to instantly teleport to the cursor (`tp cursor`) [reference:8].
- **Item Spawner** — Live search filter by name or ID, 300+ item database organized into Medical, Food, Weapons, Tools, Clothing, and Misc, plus an All tab. Custom ID spawning lets you enter any internal item ID directly [reference:9].
- **God Mode & Vitals** — Persistent immortality with automatic limb healing and optimal body temperature maintenance (37 °C). One-click restoration for Stamina, Energy, Hunger, and Thirst [reference:10].
- **World & Stats** — Toggle Noclip and Fullbright. Adjust game speed from 1.0x to 5.0x. Skip world layers (2, 3, 4). Add custom XP to Strength, Resistance, and Intelligence. Set Happiness to max or reset skills [reference:11].
- **Quality of Life** — Quick buttons for Starter Kit (`starterkit`) and Save & Quit (`saveandquit`). A direct native console input line for raw game commands. Automatic **input blocking** prevents mouse clicks from passing through the UI window, so you don't accidentally shoot or swing in-game [reference:12].

`BEPINEX → F1 → TOGGLE`

---

## 🎮 CU CHEATS (CASUALEXPIE) — `BEPINEX → F7/F8/F9 → SURVIVE`

A **lightweight, full-release-only** cheat mod that adds three essential functions, toggled with hotkeys. No console commands, no save editing—works on any run [reference:13].

- **F7 — No Fall Damage** — Falls and hard impacts don't hurt you. No mid-fall screaming and no "that hurt" lines on landing. You still ragdoll on big drops, so movement still feels like the game [reference:14].
- **F8 — God Mode** — You can't die or get hurt. Health, blood, bleeding, infection, sepsis, radiation, venom, temperature, and shock are reset instantly every frame. No broken bones, no dislocations. Hunger and thirst never drop below 30%—you won't starve, but you still have to eat and drink. Explosions still blow you back and knock you down, but you won't lose limbs, eyes, hearing, or armor durability, and you won't bleed [reference:15].
- **F9 — Debug Overlay** — A draggable in-game window showing engine stats (FPS, frame time, memory, object counts), world info (layer, biome, temperature, fog, rain, earthquakes), entity counts, mod cheat status, and a live log feed [reference:16].
- **Important Setup** — After installing BepInEx and the mod, open `<game folder>\BepInEx\config\BepInEx.cfg` and change `HideManagerGameObject = false` to `true`. This is **required** for the hotkeys to work [reference:17].

`BEPINEX → F7/F8/F9 → SURVIVE`

---

## 🧰 SANDBOX TOOLKIT (DEADSIGNAL1337) — `BEPINEX → F1 → SANDBOX`

A **full in-game sandbox panel** for testing, messing around, and taking the edge off a bad run. It is client-side and designed around single-player [reference:18].

- **Player** — Godmode blocks impact damage, fractures, dislocations, dismemberment, and eye loss, and continuously restores health, blood, oxygen, consciousness, limbs, and status effects. Infinite stamina, infinite oxygen, no bleeding, no hunger/thirst, no pain/infection. Fullbright, noclip with WASD flight, freecam with arrow keys, player speed 1x–5x, and game speed 1x/5x/20x. One-click full heal and starter kit [reference:19].
- **Items** — Searchable catalogue of every item prefab in Resources, with localized names and real categories. Spawn 1–20 items into your inventory or at your last aim point. Spawned magazines arrive fully loaded [reference:20].
- **Loadouts** — Save named loadouts containing every inventory slot, both hands, worn armor and clothing, favourites, condition values, and nested container contents. Item-specific state is saved through the game's own save data: loaded magazines, chambered rounds, gun safety, racked state, batteries, liquid stacks, pill counts, and more. Loadouts are stored in `BepInEx\config\SandboxToolkit\loadouts.json` [reference:21].
- **Installation** — Install BepInEx 5 (64-bit), run the game once, then extract the mod archive into the game folder next to `CasualtiesUnknown.exe`. The DLL ends up at `<Game Folder>\BepInEx\plugins\SandboxToolkit\SandboxToolkit.dll` [reference:22].

`BEPINEX → F1 → SANDBOX`

---

## 📱 XMODHUB & WEMOD — `APP → DETECT → TOGGLE`

App-based trainers for players who prefer a clean overlay over manual BepInEx installation.

- **XMODhub** — Auto-detects your game build (demo or Steam release, App 4576490). Toggle unlimited health, no hunger, and instant healing from the overlay. The guide hub states: *"Instead of juggling memory scans and hex-edited saves, XMODhub gives you a verified overlay that detects your game version automatically"* [reference:23].
- **WeMod** — Listed as supporting Casualties: Unknown on Steam. Standard WeMod functionality with hotkey activation and a clean overlay [reference:24].

`APP → DETECT → TOGGLE`

---

## ⚙️ BEPINEX SETUP — `INSTALL → RUN ONCE → PLUGINS`

**BepInEx 5 is the loader that powers CU_DevMenu, CU Dev Tools, CU Cheats, and Sandbox Toolkit.** Without it, none of the BepInEx-based mods will function.

- **Installation** — Download BepInEx 5 (x64) and unzip it directly into the game folder, so `winhttp.dll` and the `BepInEx` folder sit next to `CasualtiesUnknown.exe`. Start the game once, wait for the main menu, then close it. This generates the necessary folders [reference:25].
- **Plugin Placement** — Place mod DLLs in `<game folder>\BepInEx\plugins\`. Some mods (like Sandbox Toolkit) use a subfolder structure [reference:26][reference:27].
- **Hotkey Fix** — For CU Cheats, you **must** edit `BepInEx.cfg` and set `HideManagerGameObject = true` for F7/F8/F9 to work [reference:28].
- **Note** — If you already use the game's native **Mods** folder for Steam Workshop mods, BepInEx plugins are a separate system. They can coexist.

`BEPINEX → PLUGINS → PLAY`

---

## ⚠️ Important Notice

**Casualties: Unknown is a single-player survival game.** All BepInEx plugins and trainers described here are client-side and intended for single-player use. CU_DevMenu notes that spawning in multiplayer follows the host's `sv_cheats` rules [reference:29].

**This README is provided for informational and hypothetical purposes only.** Always back up your save before using loadout savers or progression editors.

## 💡 Why Choose Casualties: Unknown Launcher?

Casualties: Unknown is a brutal survival roguelike where managing injuries and bodily systems defines every run—but sometimes you just want to explore the Grey Planet without the medical minigames. This guide consolidates CU_DevMenu, CU Dev Tools, CU Cheats, and Sandbox Toolkit into one reference. CU_DevMenu gives you a game-native menu with 284 items and no file modifications, CU Cheats offers lightweight god mode and no fall damage, and Sandbox Toolkit handles full loadout saving. Whether you're here for the survival, the exploration, or just want to skip the grind, this guide delivers.

## 🎮 Why Use It?

- **Game-Native Menu** — CU_DevMenu uses the game's own UI and console commands
- **284+ Item Spawning** — Searchable browser with category filters
- **Lightweight God Mode** — CU Cheats for no fall damage and debug overlay
- **Full Loadout Saving** — Sandbox Toolkit preserves inventory, magazines, and nested containers
- **Stay Ready** — BepInEx setup, hotkey fixes, and installation steps included

## 🎛️ Control Panel

| Module | Primary Function | Highlights |
|---|---|---|
| CU_DevMenu (Magoos002) | Game-native menu | 284 items, 7 filters, god mode, world layers |
| CU Dev Tools (AdrianSimo) | IMGUI BepInEx menu | 300+ items, F3 teleport, input blocking |
| CU Cheats (casualexpie) | Lightweight hotkey mod | F7 No Fall Damage, F8 God Mode, F9 Debug Overlay |
| Sandbox Toolkit | Full sandbox panel | Loadout saving, item spawning, freecam |
| XMODhub & WeMod | App-based trainers | Auto-detect, unlimited health, no hunger |
| BepInEx Setup | Mod loader | Required for all BepInEx plugins |

## 🔍 SEO Keywords

Casualties: Unknown Launcher, Casualties Unknown trainer, Casualties Unknown cheat, Casualties Unknown CU_DevMenu, Casualties Unknown CU Dev Tools, Casualties Unknown CU Cheats, Casualties Unknown Sandbox Toolkit, Casualties Unknown BepInEx, Casualties Unknown mod loader, Casualties Unknown hack 2026, Casualties Unknown cheat panel, Casualties Unknown item spawner, Casualties Unknown god mode, Casualties Unknown no fall damage, Casualties Unknown trainer launcher
