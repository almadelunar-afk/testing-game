# Testing Game - Slap Hand Gamepass

A Roblox game featuring a purchasable **Slap Hand** gamepass for 5 Robux that sends you flying when you slap someone.

## Features

- **Gamepass**: Purchase slap hand ability for 5 Robux
- **Slap Mechanic**: Click to slap players and send them flying
- **Flight Effect**: Ragdoll physics when hit by slap hand

## Structure

- `src/` - Game scripts and modules
  - `GamepassHandler.lua` - Handles gamepass detection and permissions
  - `SlapHandler.lua` - Slap mechanic and physics
- `config/` - Configuration files
  - `GamepassConfig.lua` - Gamepass ID and settings

## Setup

1. Create a Roblox game
2. Get your gamepass ID from Roblox Creator Hub
3. Update `config/GamepassConfig.lua` with your gamepass ID
4. Insert scripts into appropriate game locations
