# UE5 Gameplay Systems

A collection of gameplay systems I build in Unreal Engine 5 while learning gameplay programming, system design, debugging, and Blueprint architecture.

## 🎮 Project Overview

This project is focused on building gameplay systems from scratch and improving them through implementation, debugging, and refactoring.

The goal is not just to make features work, but to understand how they work and organize them into reusable systems.

## ⚙️ Current Systems

### Character Systems
- Sprint
- Stamina depletion and regeneration
- Crouch
- Dodge
- Jump
- Movement restrictions during attacks

### Combat Systems
- Light attacks
- Heavy attacks
- Attack combos
- Animation Montages
- Animation Notify States
- Staff hit tracing
- Unique enemy hit filtering
- Damage application
- Enemy death

### Weapon Systems
- Weapon pickup
- Weapon collision detection
- Player interaction validation
- Weapon attachment
- Weapon-in-hand state
- Pickup actor removal

### Code Organization
Gameplay logic has been progressively refactored into reusable functions, including:

- Sprint Start / Stop
- Stamina Depletion / Regeneration
- Crouch Start / Stop
- Dodge Start / End
- Jump Start / End
- Light Attack
- Heavy Attack
- Weapon Pickup
- Combat Trace Systems

## 🧠 What I Am Practicing

- Unreal Engine 5 Blueprint development
- Gameplay programming
- Animation systems
- Collision and tracing
- Actor vs Component references
- Blueprint casting
- Arrays and gameplay state
- Function-based code organization
- Debugging gameplay systems
- Refactoring working systems into reusable functions

## 🐛 Debugging & Development

A major part of this project is learning through debugging.

Examples include:

- Preventing an attack combo from locking player movement
- Making weapon traces follow the staff during an animation
- Preventing the same enemy from receiving damage multiple times during one attack
- Debugging Notify State execution
- Debugging Actor vs Component casting
- Debugging weapon pickup collision events
- Fixing pickup collision configuration

## 🚧 Currently Working On

- Target lock-on system
- Improved interaction system
- More advanced combat
- Better enemy behavior
- C++ gameplay systems

## 🛠️ Tech

- Unreal Engine 5
- Blueprints
- Animation Montages
- Animation Notify States
- Collision / Traces
- Gameplay debugging
