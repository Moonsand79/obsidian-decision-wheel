# 🎡 Obsidian Decision Wheel

Stuck overanalyzing a decision? Too many options cluttering your workflow? Stop wasting mental bandwidth. Drop your choices into a visual wheel, give it a spin, and let destiny handle the rest—right inside your Obsidian sidebar.

The **Obsidian Decision Wheel** is a clean, interactive canvas utility designed to break decision paralysis. Built natively for Obsidian with fluid spinning physics, customizable style pallets, and a persistent vault manager to index your setups.

---

## ✨ Features

* **HTML5 Canvas Vector Rendering:** A responsive, sharp visual wheel drawn on the fly. No heavy imagery or external lag.
* **Friction & Inertia Physics:** Click "SPIN" and watch the wheel realistically accelerate, coast through friction loss, and organically snap to a calculated winner.
* **Smart Contrast Algorithm:** Your slices will never share a border color with an identical color block unless mathematically unavoidable. No more adjacent color clashing.
* **Modular Theme Browser:** Filter style palettes by length (2 to 7 color slots) or search by category. Design custom hex packs and group them natively.
* **Persistent Choice Vault:** Save your standard wheels (like a basic *Yes/No/Maybe* framework) into dedicated categories. Edit, duplicate, re-tag, or delete configuration arrays instantly. 

---

## 📸 Interface Preview

*(Tip: Drop a screenshot link or an optimized GIF of your wheel spinning right here!)*

---

## 🛠️ Installation

### Method A: Manual Desktop Installation
1. Navigate to the latest **[Releases](../../releases)** tab on this repository.
2. Download the packaged release assets: `main.js`, `manifest.json`, and `versions.json`.
3. Locate your Obsidian vault's hidden plugin architecture directory: `YourVault/.obsidian/plugins/`
4. Create a folder named exactly `decision-wheel` and paste the three files inside.
5. Boot up Obsidian, head to **Settings** -> **Community Plugins**, and toggle **Decision Wheel** on.

### Method B: Via BRAT (Beta Reviewer's Auto-update Tool)
1. Install the **BRAT** plugin from Obsidian's official community store.
2. Open the Command Palette (`Ctrl + P` or `Cmd + P`) and type `BRAT: Add a beta plugin for testing`.
3. Paste the URL of this GitHub repository into the input box and click **Add Plugin**.

---

## 🧭 How It Works & Control Guide

1. Click the **Dice Icon (🎲)** sitting on your left ribbon framework to unfold the view pane.
2. **Add Items:** Type your choices into the sleek text bar at the bottom and hit `Enter`. 
3. **Customize Style:** Tap **🎨 Colors** to invoke the style browser. Switch to a pre-built color palette, filter by choice array lengths, or inject raw hex strings to map your own palette.
4. **Manage Vault Arrays:** Click **📂 Wheels Vault** to name and save your current configuration block under custom category labels (e.g., *Life, Work, Food*). Use the canvas grid matrix to load or duplicate them later.

---

## 💻 Local Workspace Development

Want to adjust the wheel graphics, tweak the friction settings, or add custom default themes? Setting up your local environment on Linux/Kubuntu or Windows takes less than two minutes.

### Setup Requirements
Ensure you have **Node.js** matching modern npm runtime engines operational on your local machine.

### Installation & Compilation Sequences
Clone down your fork branch locally:
```bash
git clone [https://github.com/YOUR_USERNAME/decision-wheel.git](https://github.com/YOUR_USERNAME/decision-wheel.git)
cd decision-wheel
