# 🌌 Firefly Chase

**Firefly Chase** is a tiny atmospheric first-person game made with Unity and Blender. You explore a dark, mysterious forest and try to catch glowing fireflies before time runs out.

---

## 🎮 Gameplay

- First-person movement
- Wander a forest at night
- Catch **5 glowing fireflies** within **60 seconds** to win
- Watch out — time's ticking!

---

## 🛠 Built With

- **Unity 2022 LTS** (URP)
- **Blender** for environment and firefly assets
- **C# scripts** for player movement, AI, and UI logic

---

## 📂 Project Structure

```
FireflyChase/
├── Assets/
│   ├── Environment/       # Ground, trees, sky models
│   ├── Materials/         # Stylized materials (glow, ground, tree, etc.)
│   ├── Prefabs/           # Firefly prefab with AI and light
│   ├── Scripts/           # All gameplay scripts
│   ├── UI/                # UI elements: timer, score, win/loss
│   └── Scenes/Main.unity
├── .gitignore
└── README.md
```

---

## 🎯 Features

- 🧠 Simple Firefly AI: flies randomly
- ✨ Glowing fireflies with light emission
- ⏱ Countdown timer
- 🔊 (Optional) Add sound & particle FX
- 🎮 Modular setup for easy expansion

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/FireflyChase.git
   ```

2. Open the project with Unity **2022 LTS** (URP template)

3. Open the scene:
   - `Assets/Scenes/Main.unity`

4. Press ▶️ **Play** in the editor to start chasing fireflies!

---

## 📦 Dependencies

- Unity Input System
- Starter Assets (First Person Controller) from Unity Package Manager
- TextMeshPro (built-in)

---

## 🧠 Scripts Overview

| Script | Description |
|--------|-------------|
| `FireflyAI.cs` | Makes fireflies float and wander |
| `PlayerPickup.cs` | Handles player-trigger firefly capture |
| `GameManager.cs` | Manages game loop, win/loss, spawn logic |
| `UIManager.cs` | Displays timer, score, end screen |

---

## 🧪 Ideas for Expansion

- Add **sound effects** and **ambient audio**
- Include **firefly particle trails**
- Implement **difficulty levels**
- Multiplayer “who catches more” mode
- Export for WebGL and publish to itch.io

---

## 📜 License

MIT — free to use, share, and modify.

---

## ✨ Credits

- Game & Code: Tamunodein Anyanwu
- Assets: Custom-made in Blender
- Engine: Unity 2022 LTS
