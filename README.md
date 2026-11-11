# 🍅🥦 Veggie & Fruit Idle Adventure

> *An interactive English spelling, pronunciation, and nutrition idle adventure game designed for young learners.*  
> **Created by Papa W for M**

---

## 🌟 Overview

**Veggie & Fruit Idle Adventure** is a single-file, zero-dependency HTML5 game where a friendly gardener explores a sunny meadow and meets **20 unique fruits and vegetables**.

Designed as a gentle, engaging learning experience for toddlers and young children:
- Every time an attack lands, the fruit or vegetable **spells its name letter by letter** in lockstep with bouncing letter boxes and soft musical marimba chimes, followed by pronouncing the **complete word**.
- Instead of negative defeat animations, every completed fruit or vegetable **sprouts into a happy fruit-bearing tree** with golden sparkles!

---

## ✨ Key Features

- 🔤 **Synchronized Spelling & Voice Pronunciation:**
  - Uses the browser's built-in **Web Speech API** (`speechSynthesis`) + **Web Audio API** pentatonic marimba chimes.
  - Each letter box highlights at a relaxed, toddler-friendly pace (`0.75s` per letter) and speaks that exact letter at the exact moment it lights up, followed by full-word pronunciation.
  - Distinct voice pitch and melody profiles for different produce items, plus distinct tones for **Spawn**, **Spelling**, and **Tree Sprouting**.
- 🥗 **Interactive Nutrition & Discovery Card:**
  - Displays high-detail kawaii vector artwork, phonetic pronunciation, color badge, interactive spelling boxes, fun health facts, and key vitamins/nutrients.
- 🧑‍🌾 **Two Farming Tool Categories & 20 Visual Evolutions:**
  - **Melee Farming Tools (Ground Veggies):** High damage against ground produce (*Wooden Trowel → Iron Garden Spade → Silver Weeding Hoe → Crimson Garden Rake → Emerald Hay Pitchfork → Amethyst Pruning Sickle → Rose Pruning Shears → Golden Orchard Mattock → Lime Rotary Cultivator → Mythic Prismatic Scythe*).
  - **Ranged Farming Tools (Flying Fruits):** Required to reach flying fruits (*Twig Seed Slingshot → Bamboo Pea Shooter → Copper Watering Can → Crimson Mist Sprayer → Teal Garden Hose Nozzle → Golden Seed Spreader → Pink Nectar Pollinator → Silver Lawn Sprinkler → Ruby Fertilizer Launcher → Mythic Raincloud Maker*).
  - Every single upgrade level (`Lv. 1` to `Lv. 20`) changes the farming tool's sprite, color palette, and combat impact effects both on the upgrade cards and in the gardener's hand.
- 🌳 **Positive 20-Level Progression:**
  - 20 unique levels with **zero repeating enemies** and **zero repeating tool sprites**.
  - Auto-assist weapon switching after 2 missed swings on flying fruits so idle play never gets stuck.

---

## 🎮 How to Play

1. **Open the Game:** Double-click `index.html` in any modern web browser (Chrome, Edge, Safari, Firefox) — no server or installation required.
2. **Start Adventure:** Click **🔊 Start Adventure!** to unlock browser voice and sound effects.
3. **Switch Farming Tools:**
   - Use your **Melee Tool** for **Ground** produce (stronger damage).
   - Switch to your **Ranged Tool** (click the button or press `SPACE`) when **Flying** produce appears!
4. **Evolve Your Tools:** Spend collected **🌻 Sun Seeds** to evolve your Melee and Ranged farming tools across 20 unique tiers.
5. **Replay Pronunciation Anytime:** Click the **🔊 Hear Spelling & Word Again** button on the Produce Discovery Card at any time.

---

## 🍎 The 20 Produce Levels

| Level | Produce | Category | Type | Color |
| :--- | :--- | :--- | :--- | :--- |
| **1** | **Tomato** | Fruit / Veggie | Ground | Red |
| **2** | **Blueberry** | Berry Fruit | Flying | Blue |
| **3** | **Carrot** | Root Veggie | Ground | Orange |
| **4** | **Banana** | Tropical Fruit | Flying | Yellow |
| **5** | **Broccoli** | Green Veggie | Ground | Green |
| **6** | **Grape** | Vine Fruit | Flying | Purple |
| **7** | **Eggplant** | Garden Veggie | Ground | Indigo |
| **8** | **Strawberry** | Sweet Berry | Flying | Pink-Red |
| **9** | **Pumpkin** | Autumn Squash | Ground | Amber |
| **10** | **Lemon** | Citrus Fruit | Flying | Bright Yellow |
| **11** | **Potato** | Earth Tuber | Ground | Golden Brown |
| **12** | **Cherry** | Stone Fruit | Flying | Crimson |
| **13** | **Corn** | Sweet Grain | Ground | Gold |
| **14** | **Peach** | Fuzzy Fruit | Flying | Peach |
| **15** | **Radish** | Crisp Root | Ground | Magenta |
| **16** | **Pineapple** | Tropical Crown | Flying | Pineapple Gold |
| **17** | **Onion** | Bulb Veggie | Ground | Violet |
| **18** | **Watermelon** | Melon Fruit | Flying | Coral Red |
| **19** | **Cabbage** | Leafy Veggie | Ground | Jade Green |
| **20** | **Mango** | King of Fruits | Flying | Sunset Orange |

---

## 🚀 Deploying to GitHub Pages

Because the entire game is self-contained inside `index.html`:
1. Push `index.html` and `README.md` to your GitHub repository.
2. Go to **Settings → Pages** in your repository.
3. Under **Build and deployment**, select **Deploy from a branch** and choose `main` (root `/`).
4. Your game will be live and playable on any desktop, tablet, or phone!
