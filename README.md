<div align="center">

# 🌌 LUNATIC - Neverness to Everness Internal

![LUNATIC Banner](logo.png)

[![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/9YxVw9ZA5c)
[![DirectX 11](https://img.shields.io/badge/DirectX-11-blue?style=for-the-badge)](https://learn.microsoft.com/en-us/windows/win32/direct3d11/atoc-dx-graphics-direct3d-11)
[![DirectX 12](https://img.shields.io/badge/DirectX-12-purple?style=for-the-badge)](https://learn.microsoft.com/en-us/windows/win32/direct3d12/direct3d-12-graphics)

**A premium, high-performance internal cheat for *Neverness to Everness (NTE)*.**

*Featuring DirectX 11 & DirectX 12 render loop hooking with a hardware-accelerated overlay menu.*

---

[Features](#-features) • [Screenshot](#-screenshot) • [How to Use](#-how-to-use) • [Directories & Configs](#-directories-and-configurations) • [Troubleshooting](#-troubleshooting) • [Community](#-community)

</div>

---

## ✨ Features

### 👤 Player
* **God Mode** - Complete invincibility and fall damage immunity.
* **Infinite Stamina** - Run and climb without consuming stamina.
* **No Clip** - Fly through walls and terrain with adjustable **No Clip Speed** slider.
* **Infinite Jump** - Jump continuously in mid-air.
* **Player Speedhack** - Multiplies character movement speed (adjustable with **Player Speed** slider).
* **Outfit** - Cycle forward or backward through character outfits and fashion models dynamically using the **Previous Outfit** and **Next Outfit** buttons.

### 🎭 Profile
* **Nickname** - Change your displayed name in-game (up to 16 characters).
* **UID** - Customize your displayed user ID (up to 12 characters).
* **Apply Profile** - Save and apply nickname and UID changes.
* **Restore Original** - Instantly revert profile changes to original game data.
* **UID Color Method** - Choose custom visual styles: *0: None (Default)*, *1: RGB Animation*, *2: Solid Color*, *3: Shadow Glow*, *4: Material - Distort*, or *5: Material - Dissolve*.
* **UID Color** - Pick specific colors for your custom UID using the visual color editor (when mode is *2: Solid Color*).

### ⚔️ Combat
* **No Cooldown** - Remove wait times for character skills and abilities.
* **Multi Hit** - Hit targets multiple times per attack (adjustable with **Multi Hit** count slider).
* **Mob Vacuum** - Pulls all nearby enemies to a single point (adjustable with **Mob Vacuum Range** slider).
* **Dumb Enemies** - Disables enemy AI, making monsters completely passive.

### 🌍 World
* **Auto Skip Video Cutscene** - Instantly skips cinematic scenes.
* **Auto Skip Dialogue** - Speeds through story and dialogue text.
* **No Crime** - Bypasses crime triggers and police detection.
* **Auto Quest** - Automates quest navigation and steps (with **Action Delay** slider).
* **Auto Pick Items** - Loots nearby items automatically (with **Auto Pick Radius** and **Auto Pick Delay** sliders).
* **Global Speedhack** - Speed up or slow down the entire game world speed (with **Global Speed** slider).

### 👁️ Visuals & ESP
* **No Camera Fade** - Disables camera fading effects.
* **POV Changer** - Adjust your Field of View (with **FOV** slider).
* **Enable FPS Unlocker** - Bypasses the default frame rate limit (with **FPS Preset** dropdown).
* **Smoothing Fix** - Fixes mouse smoothing and frame pacing issues.
* **ESP Toggle** - Turn the visual ESP overlay on or off (with **ESP Range** slider).
* **Draw Name** - Display target names.
* **Draw Line** - Draw lines to targets (with *Bottom*, *Center*, or *Top* screen origin options).
* **Draw Box** - Draw target boxes (with *2D* or *3D* outline options).
* **Target ESP Filters:**
  * Monster
  * Oracle Stone
  * Photo View
  * Treasure Box
  * Wertheimer Tower
  * ReroRero Phone
  * Locker
  * Lost Locker Key
  * World Safe Box
  * Chameleon Package
  * Collectible Items

### 🌀 Teleport
* **Teleport to ESP (Aim + Hold G + LClick)** - Aim at any ESP-marked target and hold `G` + Left Click to warp there directly.
* **Teleport to Mark** - Place a pin on your map, enable Track, close the map, and press `H` to warp there.
* **Current Location** - Shows your current coordinate values (X, Y, Z).
* **Location Name** - Save your current position to disk with a custom name.
* **Save Location** - Confirm saving the custom waypoint location.
* **Previous Teleport / Next Teleport** - Cycle through saved teleports using hotkeys.
* **Teleport Navigation** - Cycle navigation header.
* **Teleport List** - Lists saved waypoint categories with Warp, copy coordinates, and Delete buttons.

### 🚗 Vehicle
* **Vehicle God Mode** - Makes your vehicle indestructible.
* **Vehicle Fly Mode** - Drive vehicles in the air (use `Space` to rise, `Left Shift` to descend).
* **Vehicle Speed Hack** - Multiplies vehicle speed (with **Vehicle Speed** slider).
* **N2O / Boost** - Hold `CTRL` to activate a speed boost (Text: *Hold CTRL to boost!*).
* **Vehicle Spawner** - Select and spawn any vehicle dynamically from the database.

### ⚙️ Config
* **Open Menu Hotkey** - Assign a keyboard shortcut to toggle the cheat menu overlay (default: `INSERT`).
* **Save Config** - Saves your preferences to disk.
* **Show Overlay Watermark / Hide Overlay Watermark** - Toggle the screen overlay watermark visibility.

---

## 🖼️ Screenshot

![LUNATIC Screenshot](screenshot.png)

---

## 🚀 How to Use

### 1️⃣ Discord Account Verification (Required on First Run)
The loader requires a verification code linked to your Discord account to authorize usage.

```
+-------------------------------------------------------------+
| 1. Run LUNATIC.exe -> Get Verification Code                 |
|    Format: LUNA-XXXX-XXXX (e.g., LUNA-F9Z2-8H4A)            |
| 2. Join the Discord Server                                  |
| 3. Run "/verify code:LUNA-F9Z2-8H4A" in the Channel         |
| 4. Loader automatically unlocks and saves loader_auth.json  |
+-------------------------------------------------------------+
```

1. Run `LUNATIC.exe` as an administrator.
2. The loader will start and show a verification code on screen formatted as `LUNA-XXXX-XXXX`.
3. Join the official Discord server using the button or link: https://discord.gg/9YxVw9ZA5c
4. Go to the bot command channel and type:
   ```
   /verify code:YOUR_CODE
   ```
   *(Replace `YOUR_CODE` with the code shown on the loader, including prefix and hyphens)*
5. The loader will verify the connection and automatically unlock the menu.

### 2️⃣ Launching the Game
1. Open `LUNATIC.exe`.
2. Choose your rendering framework: **DirectX 11** or **DirectX 12**.
3. Click the **LAUNCH GAME** button.
   * *The loader will auto-detect your game installation folder. If auto-detection fails, select the folder containing `NTEGlobalLauncher.exe` manually.*
4. The game will launch. Once you are loaded in-game, press **INSERT** on your keyboard to open the cheat menu.

---

## 🐧 Running on Linux (Lutris / Steam / Proton)

### Lutris and Wine Prefix
1. Copy `LUNATIC.exe` into your Neverness to Everness game folder.
2. Open Lutris, click configure on the game, and change the Executable path to launch `LUNATIC.exe` instead of the standard game launcher.
3. Run the game via Lutris, select DirectX 11 or 12 in the loader, and launch.
4. Press **INSERT** in-game to toggle the menu.

### Steam and Proton Compatibility
1. Add `LUNATIC.exe` to Steam as a non-Steam game.
2. Go to the properties of the added shortcut, select **Compatibility**, and check "Force the use of a specific Steam Play compatibility tool". Select **Proton**.
3. Set the launch options to match the same Proton compatibility prefix (`STEAM_COMPAT_DATA_PATH`) as your Neverness to Everness installation.
4. Run the loader through Steam, select rendering options, launch, and play.

---

## 📂 Directories and Configurations

### Configuration Files
* **In-game settings** are saved in: `C:/lunatic/cfg.json` (created when clicking **Save Config** in the menu).
* **Loader settings** are saved in: `loader_cfg.json` (saved in the folder where `LUNATIC.exe` is run).

### Teleport Waypoints Format
* Custom waypoint folders are managed in: `C:/lunatic/tp/`
* Any `.txt` file placed in the `tp` folder will be read as a waypoint category (e.g. `C:/lunatic/tp/custom.txt`).
* Waypoints must be formatted as follows (Name, X, Y, Z comma-separated):
  ```
  Waypoint Name, X_Coordinate, Y_Coordinate, Z_Coordinate
  ```
  Example:
  ```
  Main City, -14502.4, 25890.1, 120.5
  Safe Zone, 4390.8, -12040.2, 50.0
  ```

---

## 🔍 Troubleshooting

> [!CAUTION]
> ### Error: OpenProcess Failed
> * **Cause:** The loader does not have administrator rights to inject the helper DLL.
> * **Fix:** Close the loader, right-click `LUNATIC.exe`, and select **Run as Administrator**.

> [!WARNING]
> ### Error: Game Folder Not Found
> * **Cause:** The loader could not read the registry keys to locate the game path automatically.
> * **Fix:** Browse manually and select the folder where the game launcher `NTEGlobalLauncher.exe` is located.

> [!IMPORTANT]
> ### Error: Injection Timeout or Retry Limit Reached
> * **Cause:** Hanging processes from previous game sessions are locking resources.
> * **Fix:** Open Task Manager (Ctrl + Shift + Esc) and end all processes related to the game before launching:
>   * `HTGame.exe`
>   * `NTEGlobalGame.exe`
>   * `NTEGlobalBrowser.exe`
>   * `NTEGlobalWebBooster.exe`
>   * `NTEGlobalUpdate.exe`

> [!NOTE]
> ### Error: Discord Authorization Denied or Failed
> * **Cause:** The verification code has expired, you typed it wrong, or you are not in the Discord server.
> * **Fix:** Re-run the loader to get a new code, join the server, and enter the code in the bot channel. To reset verification cache, delete the `loader_auth.json` file in the loader's directory.

---

## 💬 Community

Join the official Discord server for helper waypoints, general support, config sharing, and updates.

* **Discord Server:** https://discord.gg/9YxVw9ZA5c
