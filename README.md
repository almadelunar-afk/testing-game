# Testing Game - Slap Hand Gamepass + Skins + Horror Elements

A Roblox game inspired by Piggy featuring:

- **Gamepass**: Purchasable slap hand ability for 5 Robux that sends you flying
- **Skins**: Different character skins (normal, scary variations)
- **Horror Atmosphere**: Scary ambiance, jumpscare mechanics, creepy NPCs
- **Survival Gameplay**: Hide and survive against scary creatures

## Features

### Gamepasses
- **Slap Hand** (5 Robux) - Click to slap players, send them flying with ragdoll physics

### Skins
- Default player skin
- Scary creature skins
- Piggy-inspired skins
- Cosmetic variations

### Horror Elements
- Scary ambient music and sound effects
- Jumpscare mechanics
- Creepy NPC enemies
- Dark lighting and atmospherics
- Survival/escape gameplay

## Project Structure

```
src/
  GamepassHandler.lua       - Gamepass detection and permissions
  SlapHandler.lua           - Slap mechanic and physics
  SkinSystem.lua            - Skin loading and switching
  HorrorManager.lua         - Scary effects, jumpscare logic
  NPCBehavior.lua           - Enemy AI (Piggy-like creatures)
  SoundManager.lua          - Ambient sounds and audio effects

config/
  GamepassConfig.lua        - Gamepass IDs and settings
  SkinConfig.lua            - Skin definitions and cosmetics
  HorrorConfig.lua          - Jumpscare triggers, atmosphere settings
  
assets/
  Sounds/                   - Scary audio, ambience
  Models/                   - NPC models, skin meshes
```

## Setup

1. Create Roblox game
2. Add gamepass ID to `config/GamepassConfig.lua`
3. Import skin models to `assets/Models/`
4. Add horror sounds to `assets/Sounds/`
5. Place scripts in appropriate game locations
