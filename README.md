# 🚂 Minimal Create Server — Modpack 1.20.1

Everything you need to join our Forge Create server.

## Requirements

| Thing | Version |
|---|---|
| Minecraft | **1.20.1** (Java Edition) |
| Mod loader | **Forge 1.20.1-47.4.10** |
| Java | **17** (the official launcher and Prism install this automatically) |
| Server address | `YOUR-SERVER.seedloaf.gg` ← replace with the real address |

## Step 1 — Download the mods

Go to **[Releases](../../releases)** (right side of this page) and download
**`client-mods-1.20.1-forge-v106.zip`**, then unzip it — you'll get a `mods`
folder with 46 `.jar` files inside, including the FTB claim mods. Nothing
else to download.

## Step 2a — Official Minecraft Launcher

1. Download the Forge installer for **1.20.1-47.4.10** from
   [files.minecraftforge.net](https://files.minecraftforge.net/net/minecraftforge/forge/index_1.20.1.html)
   and run it (choose **Install client**).
2. Open the Minecraft Launcher, select the new **forge** installation, and
   run it once so the `mods` folder is created. Close the game.
3. Open the game folder:
   - **Windows:** press `Win+R`, type `%appdata%\.minecraft`, Enter
   - **Mac:** Finder → Go → Go to Folder → `~/Library/Application Support/minecraft`
   - **Linux:** `~/.minecraft`
4. Copy all **46** `.jar` files into the **`mods`** folder.
5. Launch the game with the **forge** installation → Multiplayer → Add Server →
   paste the server address above → Join!

## Step 2b — Prism Launcher

1. Prism Launcher → **Add Instance** → choose **1.20.1**, check **Forge**,
   pick version **47.4.10** → OK.
2. Right-click the new instance → **Open → Minecraft folder** (or click
   **Folder** on the right side) → open the `minecraft` folder.
3. Copy all **46** `.jar` files into the **`mods`** folder.
   (Alternative: select the instance → **Mods** → **Add File** for each jar.)
4. Launch the instance → Multiplayer → Add Server → paste the address → Join!

## Included mods (46)

Create 6.0.8 + Metalwork, Renewable Brass, Renewable Netherite, Stones,
Aquatic Ambitions, High Pressure, Ultimate Factory, Cobblestone, Goggles,
Liquid Fuel, Ore Excavation, Fast Schematic Cannon, Schematic Checker,
Train Perspective, Farmer's Delight, Storage Drawers, EnderChests,
Building Wands, Big Contraptions, Trading Floor, JEI, Embeddium,
FerriteCore, Modern Shop, Create: Currency Shops
(+ Architectury, Cloth Config, ShetiphianCore libraries,
+ FTB Library, FTB Teams, FTB Chunks, FTB Essentials).

## Server commands (once you're in)

- `/tpa <name>`, `/tpahere <name>`, `/home set`, `/home`, `/rtp`, `/warp`
  (FTB Essentials) — set homes and teleport to friends
- Open the FTB Chunks map (inventory screen button or keybind) to
  **claim chunks** — claimed land is grief-proof (creepers can't break it)
- `/shop` (Modern Shop) and Create Currency Shops for trading

## Notes

- ⚠️ If you play without a paid Minecraft account (offline mode), pick a
  **unique username** — two players with the same name kick each other.
- Everyone must use the **exact same mod files** — if you can't join, you
  probably have an extra, missing, or outdated jar. Re-download the zip.
- Optional performance boost (not required): add
  [ModernFix](https://modrinth.com/mod/modernfix) (Forge 1.20.1) to your
  `mods` folder too.
