# WORK IN PROGRESS!!

# BaldiCraft: Minecraft in Baldi's Basics Plus

**Play Baldi's Basics Plus with real Minecraft Java Edition (Fabric 26.2).**

Built using the [Universal Modder](https://github.com/rehan-remade/universal-modder) passthrough architecture. Real Minecraft Java and Baldi's Basics Plus run concurrently with live camera synchronization, schoolhouse collision sync, and direct inventory item integration.

---

## ⚡ Quick Start

1. Double-click **`Setup.bat`**
   - Automatically detects your Steam installation of *Baldi's Basics Plus*.
   - Configures the BepInEx plugin and verifies your Prism Launcher 26.2 Fabric instance.
2. Double-click **`Play.bat`** (or **`Play-Windowed.bat`**)
   - Starts the Minecraft Fabric companion instance.
   - Automatically launches *Baldi's Basics Plus* hooked into Minecraft.

---

## 📦 Adding Mods to the Modpack

Your Minecraft instance is a genuine **Prism Launcher 26.2 Fabric modpack**.
You can add any compatible Fabric mod directly:

* **Location**: Open `minecraft\mods` inside this folder (or your Prism Launcher instance's `mods/` directory).
* **Essential Mod Included**: The Essential mod (`Essential_1-4-1-1_fabric_26-2.jar`) is already bundled in `minecraft\mods` for:
  - Hosting multiplayer worlds without needing a dedicated server (P2P).
  - Inviting friends directly from your in-game friends list.
  - Custom cosmetics, wardrobe, and screenshots.
* **Performance Mods Included**: `Sodium`, `Iris` (Shaders), `ImmediatelyFast`, `Lithium`, and `Cloth Config`.

---

## 🎒 Baldi's Basics Items in Minecraft Inventory

When you pick up items in Baldi's Basics Plus, they are synchronized straight into your Minecraft player inventory:
* **BSODA / Diet BSODA** $\rightarrow$ Potion item with spray action
* **Energy Flavored Zesty Bar** $\rightarrow$ Food item (restores hunger and stamina)
* **Quarter** $\rightarrow$ Gold Nugget
* **Safety Scissors** $\rightarrow$ Shears
* **Principal's Whistle** $\rightarrow$ Goat Horn
* **Alarm Clock** $\rightarrow$ Clock
* **Baldi's Least Favorite Tape** $\rightarrow$ Music Disc
* **Apple for Baldi** $\rightarrow$ Apple
* **Faculty Nametag** $\rightarrow$ Name Tag
* **Teleporter** $\rightarrow$ Ender Pearl

Dropping or using items updates both games in real time.

---

## 💬 Chat and the `/pause` Command (Essential Mod)

* **Opening the Minecraft Pause Menu**:
  - Type `/pause` in chat, or press **Escape** / **F10**.
  - Minecraft opens the native `PauseScreen`.
  - The **Essential mod menu** will appear, allowing you to click **"Host World"**, **"Invite Friends"**, or access your **Social / Wardrobe** menu.
* **In-Game Chat**:
  - Press **T** or **/** to open Minecraft's chat.
  - Send messages to friends playing with you via Essential multiplayer!

---

## 🎮 Controls

| Key | Action |
|---|---|
| **W A S D** | Move |
| **Space** | Jump (double-tap in Creative to fly) |
| **Left Shift** | Sneak |
| **Left Ctrl** | Sprint |
| **Left Click** | Mine blocks / attack characters |
| **Right Click** | Place blocks / eat food / interact |
| **1 - 9 / Mouse Wheel** | Select hotbar slot |
| **E** | Minecraft inventory |
| **T** or **/** | Open Minecraft Chat |
| **`/pause`** or **Esc / F10** | Open Minecraft Pause Menu (Essential Multiplayer) |
| **F** | Use selected Baldi's Basics Plus item |
| **F5** | Toggle perspective (First person / Third person) |

---

## 🗑️ Uninstalling

To restore Baldi's Basics Plus to its original vanilla state, run **`Uninstall.bat`**.
