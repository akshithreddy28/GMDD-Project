# Super Mario 2D – 20-Level Adventure (Unity 6)

A professional, feature-packed **Super Mario 2D platformer** built with **Unity 6** (6000.5.8f1) featuring **20 fully playable progressive levels**, **4 world boss battles**, responsive physics, and an arcade checkpoint & life system.

---

## 🎮 How to Play / Run

### 1. Open Directly in Unity Editor
- Double-click **`Open_In_Unity.bat`**.
- Unity 6 will open the project directly to `SuperUnityScene`.
- Hit **Play (▶️)** at the top of the Unity Editor!
- *Menu Shortcut:* You can also click **Tools -> Super Unity -> Build Full Mario Game Scene** in the top Unity menu bar to regenerate the level layouts at any time.

### 2. Instant Playable Web Preview
- Double-click **`Play_Super_Mario.bat`**.
- Your browser will open the high-performance retro HTML5 Canvas version with full 8-bit sound effects, music, and physics!

---

## 🕹️ Controls

| Action | Primary Key | Alternative Key |
| :--- | :--- | :--- |
| **Move Left / Right** | Left / Right Arrows | A / D |
| **Jump** (Variable height) | Spacebar | W / Up Arrow |
| **Run / Sprint (Dash)** | Left Shift | Right Shift / X |
| **Crouch** (Super / Fire) | Down Arrow | S |
| **Shoot Fireball** (Fire Mario) | F | Left Ctrl / C |
| **Restart Level** | R | |
| **Mute / Unmute Audio** | M | |

---

## 🗺️ 20 Levels Across 4 Distinct Worlds

### 🌲 World 1 – Green Grassland (Levels 1–5)
- **Level 1: Beginner's Journey** – Basic movement, jumping, simple platforming, coins, basic Goombas, and castle finish.
- **Level 2: Mushroom Fields** – Mushroom-themed obstacles, varied elevation platforms, question blocks, and patrolling Koopas.
- **Level 3: Underground Adventure** – Cave aesthetics, narrow tunnels, moving platforms, and hidden coin caverns.
- **Level 4: Dangerous Bridges** – Treacherous bridge gaps, floating platforms, and tighter jumps.
- **Level 5: World 1 Castle Boss** – Castle dungeon, lava barriers, multiple enemy waves, and the World 1 Castle Boss encounter.

### 🏜️ World 2 – Desert Adventure (Levels 6–10)
- **Level 6: Desert Run** – Desert dunes, sandy platforms, and cactus obstacles.
- **Level 7: Moving Sands** – Falling platforms, sinking sand hazards, and fast-moving enemies.
- **Level 8: Pyramid Mystery** – Pyramid interior, hidden passages, traps, and secret coin rooms.
- **Level 9: Desert Storm** – Intense platforming combinations with flying Paratroopas and hazards.
- **Level 10: Desert Castle Boss** – Large castle fortress with jumping puzzles and the Desert Castle Boss.

### ❄️ World 3 – Frozen Kingdom (Levels 11–15)
- **Level 11: Snowy Mountains** – Snow mountain peaks, icy terrain, and slippery physics.
- **Level 12: Frozen Lake** – Slippery frozen platforms, breaking ice blocks, and water hazards.
- **Level 13: Ice Caves** – Subterranean ice caverns, falling icicles, and moving lifts.
- **Level 14: Blizzard Challenge** – Frigid mountain trails, treacherous platform gaps, and multiple enemy squads.
- **Level 15: Ice Castle Boss** – Frozen citadel, spike traps, and the Frost Castle Boss.

### 🌋 World 4 – Dark Volcano World (Levels 16–20)
- **Level 16: Volcanic Valley** – Molten terrain, dangerous stepping stones, and fire obstacles.
- **Level 17: Burning Bridges** – Collapsing bridges, moving lava platforms, and Fire Podoboo jumps.
- **Level 18: Dark Underground** – Deep volcanic caves, tricky traps, and armored enemies.
- **Level 19: Ultimate Challenge** – Gauntlet combining all mechanics, complex platforming, and multiple checkpoints.
- **Level 20: FINAL BOSS – King of the Volcano** – Epic final castle arena, multi-phase boss fight with fire projectiles, shockwaves, bridge collapse switch, victory fanfare, and game ending screen.

---

## 🌟 Key Gameplay & Technical Features

### 1. Mario Movement & Physics
- **Enhanced Jump Mechanics**: Responsive variable jump height (+18% tuned jump height: short hops on tap, high jumps on hold) with full air steering, jump buffering, and coyote time.
- **Power-Up States**: Small Mario, Super Mario (breaks brick blocks), and Fire Mario (shoots bouncing fireballs).
- **Death & Respawn System**:
  - Dramatic death pop animation and 2.0-second respawn delay.
  - Checkpoint respawn: Mario respawns directly at the latest checkpoint without restarting or reloading the entire level.
  - Coins and score are preserved across respawns.
  - 3-life counter system with life reduction and Game Over screen with **Retry Level** and **Main Menu** options.

### 2. World Bosses & Enemies
- **4 Unique World Bosses**: Health bars, custom attack phases, fire breath, jump shockwaves, and bridge collapse switch mechanics.
- **Classic Enemies**: Goomba, Koopa Troopa (kickable sliding shells), Piranha Plants, Flying Paratroopas, Spiny enemies, and Fire Podoboos.

### 3. Progression & UI
- **Save System**: Permanent progress tracking using `PlayerPrefs` (unlocked levels and high scores persist between sessions).
- **In-Game HUD & Menus**: Live display of current World-Level, Lives, Coins, Score, and Boss Health. Includes Level Select, World Select, Character Skin Selector, and Pause Menu.
