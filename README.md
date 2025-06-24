# 🧭 Adventure Platformer Game

A simple yet engaging **2D platformer** built using **Unity**, featuring classic gameplay elements like walking, jumping, coin collection, and spike-based hazards. Perfect as a beginner-level project showcasing fundamental game mechanics and Unity development workflow.

---

## 🎮 Game Overview

* 🔹 **Genre**: 2D Platformer / Adventure
* 🔹 **Engine**: Unity
* 🔹 **Current Version**: v1.0
* 🔹 **Platform**: PC (Windows/macOS)

---

## 🧩 Features

* ✅ Smooth **walking and jumping** mechanics
* 🪙 **Collectible coins** (18 in total)
* ⚠️ **Hazards**: 4 spikes placed strategically to test player reflexes
* 🏁 **One complete level** with a winning condition when all coins are collected
* 🔄 Respawn/retry logic upon collision with spikes
* 🎨 Built with Unity's built-in **2D physics and animation** systems

---

## 🎥 Gameplay

> *Player moves through a side-scrolling level, collecting coins while avoiding spikes. Once all coins are collected, the level is considered complete.*

---

## 🛠️ How to Run

### 🎮 Play (for users)

1. Download the release build (Windows/macOS).
2. Unzip and run the executable (`AdventurePlatformer.exe` or `AdventurePlatformer.app`).

### 🧑‍💻 Run in Unity (for developers)

1. Open **Unity Hub**
2. Click **"Add Project"** and select this folder
3. Open the project in **Unity 2022.x** (or compatible version)
4. Run the game using the **Play** button in the editor

---

## 📂 Project Structure

```
Assets/
├── Scenes/             # Main game scene
├── Scripts/            # Player controller, coin manager, hazard logic
├── Prefabs/            # Coin, spike, player prefab
├── Art/                # 2D sprites and tilemaps
└── Audio/              # (optional) SFX/Music
```

---

## 🧠 Learnings / Concepts Used

* Unity's **2D Rigidbody and Colliders**
* Basic **C# scripting** for movement, triggers, and hazards
* Using **tags** and **layers** for collision logic
* Scene management and UI basics (score counter, game over)
* Platform-specific build creation
