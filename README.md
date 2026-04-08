# Spellisde
**Witchjam 2026** | **Unreal Engine 5.6** | **3D Action Game**

[![Download Game Build](https://img.shields.io/badge/Download-MEGA-red?style=for-the-badge)](https://mega.nz/folder/qtwxnDSY#h1tAJ5ScUSkt004hUkA2LQ)


---

## About the Game
You play as Nahiri—a vision-haunted figure sentenced to death and cast into the sea. You wake up with no memories in a world governed by its own unsettling laws. Uncover the mysteries of reality, develop your abilities, and face your enemies to discover the truth about yourself and the world.

![Spellisde Gameplay Trailer](/screenshots/game.gif)

---

## My role in the project

### 1. Level & Environment Design
I was responsible for designing and building the game's environments, focusing on atmosphere and clear player guidance.

![level 1](/screenshots/level_1.jpeg)
*Level 1. Editor view. This level presents a journey from a forest and mountain setting to a sanctuary where the boss battle takes place.*

![level 2](/screenshots/level_2.jpeg)
*Level 2. Editor view. The level takes you on a journey up a mountain, after which you jump down into a valley where the boss awaits.*

### 2. Performance Optimization
To ensure smooth gameplay, I implemented several key optimization passes across the levels, significantly reducing CPU and GPU overhead:

* I used hierarchical instancing to merge multiple static meshes into single actors, drastically cutting down draw calls.
* I conducted lighting pass to ensure minimal light overlap, managing light counts.
* I performed a texture optimization pass and tuned foliage density.

### 3. Gameplay Systems (Ice & Lava)
I programmed the player's reactions to ice and fire effects, as well as how objects behave when hit by a specific spell.

**Ice Surface Mechanics**

![ice mechanic](/screenshots/ice.gif)

**Lava Surface Mechanics**

![lava mechanic](/screenshots/fire.gif)

**Blueprint:**
![blueprint logic](/screenshots/fire_and_ice_material.jpeg)

### 4. Assets and Materials
* I sourced environment assets from FAB and modified their material graphs to dynamically react and adapt to the game's "2nd dimension" transition mechanic.
* I configured dynamic highlight material instances to clearly visually indicate interactable objects to the player.

---

## 👥 The Team
While I focused on the environment design, technical optimization, and gameplay systems listed above, this project was brought to life alongside my amazing teammates: 
* Patryk Kaczyński - AI design and implementation, game integration, level design, boss and NPC design, Gameplay Developer
* Mikołaj Kaim - Gameplay Developer responsible for the combat system, character and enemy abilities, animation integration, VFX implementation, UI systems, and game balance