# 🧟‍♂️ Left 4 Dead 2: Custom Server Mod & Interactive Manual

Welcome! Whether you're a fellow Left 4 Dead 2 enthusiast exploring custom mods, or a technical recruiter taking a peek at my projects, I'm glad you're here.

## 📖 The Story Behind This Repo

To be completely honest, this project was born out of a desire for efficiency (and maybe a little laziness). I regularly develop and update a highly customized Left 4 Dead 2 server for my friend group. Eventually, typing out massive walls of text in our group chat to explain new patch notes, weapon balances, and shop prices became tedious.

Instead of spamming my friends with text, I built this **interactive, single-page web portfolio**. Now, whenever we play together, I just send them the link. They can easily sort through weapon stats, check the dynamic shop economy, and read up on the new game mechanics at their own pace.

## 🛠️ What's Actually In Here?

This repository primarily hosts the frontend web interface for my mod, but it serves as documentation for the heavy backend logic running on the game server.

### 1. The Frontend (This Website)
A lightweight, fully responsive single-page application (SPA) built without heavy frameworks.
* **Tech:** Vanilla HTML, CSS, and JavaScript.
* **Features:** Dynamic DOM manipulation, deferred lazy-loading for heavy image assets, custom data sorting algorithms for weapon stat tables, and an interactive side-by-side comparison tool.

### 2. The Backend (The Game Mod)
A complete overhaul of the Left 4 Dead 2 engine mechanics, written entirely in **Squirrel (VScript)**.
* **Dynamic Economy (RenShop):** A real-time, chat-based point shop where players earn credits via game event hooks (killing Bosses, healing teammates) to buy upgrades and items.
* **Engine Hacks & NetProps:** Safely intercepts and manipulates entity properties (`AllowTakeDamage` hooks) to create custom mechanics like Melee Life Steal, Reflected Friendly Fire Damage, and Incap AoE Explosions.
* **Complete Rebalance:** Custom damage scaling, movement speed penalties based on weapon weight, and newly scripted "Legendary" weapon tiers.

## 🎯 Purpose & Disclaimer

**This project (both the custom server mod and this web interface) is 100% for personal entertainment.** It is a passion project built to create a fun, chaotic, and deeply customized gaming experience for my friends. It also serves as a fun sandbox for me to practice scripting, performance optimization, and UI/UX design outside of my normal professional work. 
