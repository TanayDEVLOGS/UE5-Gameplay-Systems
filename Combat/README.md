# Combat System

A melee combat system built in Unreal Engine 5 using Blueprints and animation-driven gameplay.

## Features

- Light attack combo system
- Heavy attacks
- Attack movement control
- Animation Montages
- Animation Notify States
- Continuous weapon tracing during attacks
- Damage application
- Enemy hit detection
- One-hit-per-enemy filtering during each attack
- Enemy death
- Weapon-dependent attack validation

## Weapon Tracing

The combat system uses the weapon's socket positions to trace the weapon's movement during an active attack.

Instead of checking for a hit on only one animation frame, the trace runs throughout the Notify State, allowing the trace to follow the weapon's actual movement.

```text
Attack Montage
      ↓
Attack Notify State
      ↓
Weapon Trace
      ↓
Hit Result
      ↓
Check Hit Actor
      ↓
Already Hit?
   ↙       ↘
 Yes        No
  ↓          ↓
Ignore    Add Actor
             ↓
        Apply Damage
