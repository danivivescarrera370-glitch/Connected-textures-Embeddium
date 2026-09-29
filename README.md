# Continuity (Embeddium Edition)

A specialized fork/configuration guide for **Continuity**, optimized to work seamlessly with **Embeddium**. 

[Continuity](https://modrinth.com/mod/continuity) is a client-side Minecraft mod that brings **OptiFine-format connected textures, emissive textures, and custom block layers** to modded setups without requiring OptiFine itself. By combining it with [Embeddium](https://modrinth.com/project/sk9rgfiA), you get high-performance rendering paired with beautiful, seamless textures.

---

## 🚀 Compatibility & Setup

Embeddium features built-in **Fabric Rendering API (FRAPI)** support. This means it handles complex rendering pipelines natively and does not require additional layout bridge mods (like Indium) to work with Continuity.

### 🧵 Fabric Setup
1. Download the official [Continuity](https://modrinth.com/mod/continuity) mod.
2. Download [Embeddium](https://modrinth.com/project/sk9rgfiA).
3. Drop both into your `mods` folder. They work together automatically!

### 🛠️ Forge / NeoForge Setup (Now without connector!)
If you are running a mixed modpack on Forge or NeoForge:
2. Add the unofficial fork of the Fabric **Continuity** called **Connected textures Embeddium** and Forge/NeoForge **Embeddium** to your folder.

### ⚡ Native NeoForge Setup (No Translation Layers)
If you want a pure NeoForge ecosystem without Sinytra Connector, use the community-maintained native fork:
* Install **[NeoContinuity](https://www.curseforge.com/minecraft/mc-mods/neocontinuity)** alongside Embeddium.

---

## 🎨 Features & Built-in Packs

Continuity includes two default resource packs that must be activated in your in-game Resource Packs menu:

* **Default Connected Textures:** Provides connected textures for glass, sandstone, and bookshelves (matching OptiFine's default look).
* **Glass Pane Culling Fix:** Culls interior faces between vertically stacked glass panes to make them look completely seamless.

---

## ⚙️ Recommended UI Fix

Embeddium completely replaces the default Minecraft video options menu, which can sometimes hide Continuity's built-in toggle settings. 

To fix this, it is highly recommended to install:
* **[Sodium/Embeddium Options Mod Compat](https://www.curseforge.com/minecraft/mc-mods/sodium-embeddium-options-mod-compat):** This cleanly injects Continuity’s options layout directly into the Embeddium settings menu.

---

## 🌐 Original Project Links
* **CurseForge:** [Official Continuity Page](https://www.curseforge.com/minecraft/mc-mods/continuity)
* **Modrinth:** [Official Continuity Page](https://modrinth.com/mod/continuity)
* **Source/Wiki:** [Continuity GitHub](https://github.com/PepperCode1/Continuity/wiki)
* **Community:** [Official Discord Server](https://discord.gg/7rnTYXu)
