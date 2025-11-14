COMP 163 - Project 2: Character Abilities Showcase
Mariyah Curb

Project Overview
Implemented a simple character and combat battle system with weapons and abilities

Key Concepts Demonstrated

1. Inheritance


2. Polymorphism 


3. Composition



Implemented Classes

| Class Name | Inherits From | Key Feature(s) |
| :--- | :--- | :--- |
| `Character` | N/A | Base stats (`health`, `strength`, `magic`), `attack`, `take_damage`. |
| `Player` | `Character` | Adds `character_class`, `level`, `experience`, and `equip_weapon`. |
| `Warrior` | `Player` | High strength/health. **Overridden `attack`** (extra physical damage) and `power_strike` ability. |
| `Mage` | `Player` | High magic. **Overridden `attack`** (uses magic for damage) and `fireball` ability. |
| `Rogue` | `Player` | Critical hit chance. **Overridden `attack`** (chance for double damage) and `sneak_attack` ability. |
| `Weapon` | N/A | Demonstrates **Composition**; provides a `damage_bonus`. |
| `SimpleBattle` | N/A | Provided utility class to test character implementations. |


**Author:** Mariyah Curb
**Date:** 11/11/2025
**AI Usage:** Used Gemini to assist in the debugging commit of the code and writing read file.
